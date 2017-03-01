OpenShift Go revel Cartridge
=============================

Append from : https://github.com/chio-nzgft/openshift-go-revel

To install to OpenShift from the CLI (you'll need version 1.9 or later of rhc), run:

    rhc create-app mygorevel https://cartreflect-claytondev.rhcloud.com/reflect?github=chio-nzgft/openshift-go-revel

![alt tag](https://github.com/chio-nzgft/openshift-go-revel/raw/master/show.png)


]\> cat go/logs/go.log

Fri Feb 24 2017 02:18:15 GMT-0500 (EST): Starting application 'mygorevel' from bin/revel...

~

~ revel! http://revel.github.io

~

INFO  2017/02/24 02:18:15 revel.go:365: Loaded module static

INFO  2017/02/24 02:18:15 revel.go:365: Loaded module testrunner

INFO  2017/02/24 02:18:15 revel.go:230: Initialized Revel v0.13.1 (2016-06-06) for >= go1.4

INFO  2017/02/24 02:18:15 run.go:57: Running myapp (myapp) in dev mode

INFO  2017/02/24 02:18:15 harness.go:170: Listening on 127.8.216.129:8080

INFO  2017/02/24 02:18:54 build.go:179: Cleaning dir tmp

INFO  2017/02/24 02:18:54 build.go:179: Cleaning dir routes

INFO  2017/02/24 02:18:54 build.go:179: Cleaning dir tmp

INFO  2017/02/24 02:18:54 build.go:179: Cleaning dir routes

INFO  2017/02/24 02:19:08 revel.go:365: Loaded module static

INFO  2017/02/24 02:19:08 revel.go:365: Loaded module testrunner

INFO  2017/02/24 02:19:08 revel.go:230: Initialized Revel v0.13.1 (2016-06-06) for >= go1.4

INFO  2017/02/24 02:19:08 main.go:30: Running revel server

Go to /@tests to run the tests.

Listening on 127.8.216.129:15854...

2017/02/24 02:19:08.953 127.8.216.129 200 5.938682ms GET /

2017/02/24 02:19:09.228 127.8.216.129 200  512.322µs GET /public/css/bootstrap-3.3.6.min.css

2017/02/24 02:19:09.415 127.8.216.129 200 1.173821ms GET /public/js/jquery-2.2.4.min.js

2017/02/24 02:19:09.465 127.8.216.129 200  449.262µs GET /public/js/bootstrap-3.3.6.min.js

2017/02/24 02:19:09.934 127.8.216.129 200  391.126µs GET /public/fonts/glyphicons-halflings-regular.woff2

2017/02/24 02:19:10.581 127.8.216.129 200  418.102µs GET /public/img/favicon.png

2017/02/24 02:19:28.566 127.8.216.129 200  418.253µs GET /

2017/02/24 02:19:28.846 127.8.216.129 200  827.504µs GET /public/css/bootstrap-3.3.6.min.css

2017/02/24 02:19:29.074 127.8.216.129 200  395.814µs GET /public/js/jquery-2.2.4.min.js

2017/02/24 02:19:29.082 127.8.216.129 200  345.175µs GET /public/js/bootstrap-3.3.6.min.js

2017/02/24 02:19:29.091 127.8.216.129 200  410.028µs GET /public/img/favicon.png

2017/02/24 02:19:29.305 127.8.216.129 200  330.637µs GET /public/img/favicon.png

2017/02/24 02:19:29.546 127.8.216.129 200  326.263µs GET /public/fonts/glyphicons-halflings-regular.woff2

2017/02/24 02:19:29.969 127.8.216.129 200  336.641µs GET /public/img/favicon.png

