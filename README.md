OpenShift Go revel Cartridge
=============================

PS : Use mLab MongoDB
=============================

Append from : https://github.com/chio-nzgft/openshift-go-revel

To install to OpenShift from the CLI (you'll need version 1.9 or later of rhc), run:

    rhc create-app leanote mongodb-2.4 https://cartreflect-claytondev.rhcloud.com/reflect?github=chio-nzgft/openshift-go-revel-leanote-mlab-db

]\> cat go/logs/go.log

TRACE 2017/02/28 23:10:27 harness.go:127: Rebuild

INFO  2017/02/28 23:10:27 build.go:179: Cleaning dir tmp

INFO  2017/02/28 23:10:27 build.go:179: Cleaning dir routes

INFO  2017/02/28 23:10:29 build.go:179: Cleaning dir tmp

INFO  2017/02/28 23:10:29 build.go:179: Cleaning dir routes

TRACE 2017/02/28 23:10:29 build.go:158: Exec: [/usr/bin/git --git-dir=/var/lib/openshift/58b6467d2d52715b340000c4/app-

root/runtime/repo/src/github.com/leanote/leanote/.git describe --always --dirty]

TRACE 2017/02/28 23:10:29 build.go:101: Exec: [/var/lib/openshift/58b6467d2d52715b340000c4/go/cache/go-1.5.2/go/bin/go build -i -ldflags 
-X github.com/leanote/leanote/app.APP_VERSION=git-41f95cf-dirty -tags  -o /var/lib/openshift/58b6467d2d52715b340000c4/app-
root/runtime/repo/bin/revel.d/github.com/leanote/leanote/leanote github.com/leanote/leanote/app/tmp]

ERROR 2017/02/28 23:10:33 build.go:108: go install github.com/leanote/leanote/app/controllers: copying /tmp/go-
build068764012/github.com/leanote/leanote/app/controllers.a to /var/lib/openshift/58b6467d2d52715b340000c4/app-root/runtime/repo/pkg/linux_amd64/github.com/leanote/leanote/app/controllers.a: write /var/lib/openshift/58b6467d2d52715b340000c4/app-root/runtime/repo/pkg/linux_amd64/github.com/leanote/leanote/app/controllers.a: disk quota exceeded

ERROR 2017/02/28 23:10:33 build.go:308: Failed to parse build errors:
 go install github.com/leanote/leanote/app/controllers: copying /tmp/go-build068764012/github.com/leanote/leanote/app/controllers.a to /var/lib/openshift/58b6467d2d52715b340000c4/app-root/runtime/repo/pkg/linux_amd64/github.com/leanote/leanote/app/controllers.a: write /var/lib/openshift/58b6467d2d52715b340000c4/app-root/runtime/repo/pkg/linux_amd64/github.com/leanote/leanote/app/controllers.a: disk quota exceeded

TRACE 2017/02/28 23:10:33 harness.go:127: Rebuild

INFO  2017/02/28 23:10:33 build.go:179: Cleaning dir tmp

INFO  2017/02/28 23:10:33 build.go:179: Cleaning dir routes

INFO  2017/02/28 23:10:35 build.go:179: Cleaning dir tmp

INFO  2017/02/28 23:10:35 build.go:179: Cleaning dir routes

TRACE 2017/02/28 23:10:35 build.go:158: Exec: [/usr/bin/git --git-dir=/var/lib/openshift/58b6467d2d52715b340000c4/app-

root/runtime/repo/src/github.com/leanote/leanote/.git describe --always --dirty]

TRACE 2017/02/28 23:10:35 build.go:101: Exec: [/var/lib/openshift/58b6467d2d52715b340000c4/go/cache/go-1.5.2/go/bin/go build -i -ldflags 
-X github.com/leanote/leanote/app.APP_VERSION=git-41f95cf-dirty -tags  -o /var/lib/openshift/58b6467d2d52715b340000c4/app-root/runtime/repo/bin/revel.d/github.com/leanote/leanote/leanote github.com/leanote/leanote/app/tmp]
ERROR 2017/02/28 23:10:37 build.go:108: go install github.com/leanote/leanote/app/controllers: copying /tmp/go-build143858294/github.com/leanote/leanote/app/controllers.a to /var/lib/openshift/58b6467d2d52715b340000c4/app-root/runtime/repo/pkg/linux_amd64/github.com/leanote/leanote/app/controllers.a: write /var/lib/openshift/58b6467d2d52715b340000c4/app-root/runtime/repo/pkg/linux_amd64/github.com/leanote/leanote/app/controllers.a: disk quota exceeded

ERROR 2017/02/28 23:10:37 build.go:308: Failed to parse build errors:
 go install github.com/leanote/leanote/app/controllers: copying /tmp/go-build143858294/github.com/leanote/leanote/app/controllers.a to /var/lib/openshift/58b6467d2d52715b340000c4/app-root/runtime/repo/pkg/linux_amd64/github.com/leanote/leanote/app/controllers.a: write /var/lib/openshift/58b6467d2d52715b340000c4/app-root/runtime/repo/pkg/linux_amd64/github.com/leanote/leanote/app/controllers.a: disk quota exceeded


