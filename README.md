OpenShift Go revel Cartridge
=============================

Use mLab MongoDB
=============================

please clone git ... then change db host in ....openshift-go-revel-leanote-mlab-db/bin/compile file

    sed -i 's/db.username=/db.username=admin/g' src/github.com/leanote/leanote/conf/app.conf
    sed -i 's/db.password=/db.password=leanote/g' src/github.com/leanote/leanote/conf/app.conf
    sed -i 's/db.host=127.0.0.1/db.host=ds145389.mlab.com/g' src/github.com/leanote/leanote/conf/app.conf
    sed -i 's/db.port=27017/db.port=45389/g' src/github.com/leanote/leanote/conf/app.conf

Create DB : mongorestore -h ds145389.mlab.com:45389 -d leanote -u admin -p leanote

     mongorestore -h ds145389.mlab.com:45389 -d leanote -u admin -p leanote --dir src/github.com/leanote/leanote/mongodb_backup/leanote_install_data

Append from : https://github.com/chio-nzgft/openshift-go-revel

To install to OpenShift from the CLI (you'll need version 1.9 or later of rhc), run:

    rhc create-app leanote https://cartreflect-claytondev.rhcloud.com/reflect?github=chio-nzgft/openshift-go-revel-leanote-mlab-db

![alt tag](https://github.com/chio-nzgft/openshift-go-revel-leanote-mlab-db/raw/master/show-note.png)


[root@test gocode]# rhc app start leanote

RESULT:

leanote started

[root@test gocode]# rhc app-show --gears quota leanote

Gear                     Cartridges                Used Limit

------------------------ ----------------------- ------ -----

58b669d60c1e22222222222 smarterclayton-go-1.5.2 0.8 GB  1 GB




