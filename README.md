# analysis



## QuickStart

<!-- add docs here for user -->

see [egg docs][egg] for more detail.

### Development

```bash
$ npm i
$ npm run dev
$ open http://localhost:7001/
```

### Deploy

```bash
$ npm start
$ npm stop
```

### npm scripts

- Use `npm run lint` to check code style.
- Use `npm test` to run unit test.
- Use `npm run autod` to auto detect dependencies upgrade, see [autod](https://www.npmjs.com/package/autod) for more detail.


[egg]: https://eggjs.org

### 调试
```
cd root
node --inspect-brk node_modules/egg-bin/bin/egg-bin.js dev
```
```
2019-07-29T11:37:12.660Z egg-core:plugin Loaded app plugins: []
2019-07-29T11:37:12.661Z egg-core:plugin Loaded egg plugins: ["onerror","session","i18n","watcher","multipart","security","development","logrotator","schedule","static","jsonp","view"]
2019-07-29T11:37:12.670Z egg-core#sequencify task: onerror is enabled by app
2019-07-29T11:37:12.670Z egg-core#sequencify task: session is enabled by app
2019-07-29T11:37:12.670Z egg-core#sequencify task: i18n is enabled by app
2019-07-29T11:37:12.671Z egg-core#sequencify task: watcher is enabled by app
2019-07-29T11:37:12.671Z egg-core#sequencify task: multipart is enabled by app
2019-07-29T11:37:12.671Z egg-core#sequencify task: security is enabled by app
2019-07-29T11:37:12.671Z egg-core#sequencify task: development is enabled by app
2019-07-29T11:37:12.671Z egg-core#sequencify task: schedule is enabled by logrotator
2019-07-29T11:37:12.671Z egg-core#sequencify task: logrotator is enabled by app
2019-07-29T11:37:12.671Z egg-core#sequencify task: static is enabled by app
2019-07-29T11:37:12.671Z egg-core#sequencify task: jsonp is enabled by app
2019-07-29T11:37:12.671Z egg-core#sequencify task: view is enabled by app
2019-07-29T11:37:12.671Z egg-core:plugin Got plugins {"sequence":["session","security","jsonp","onerror","i18n","watcher","schedule","multipart","development","logrotator","static","view"],"missingTasks":[],"recursiveDependencies":[]} after sequencify
2019-07-29T11:37:12.671Z egg-core:plugin Loaded plugins: ["session","security","jsonp","onerror","i18n","watcher","schedule","multipart","development","logrotator","static","view"]
2019-07-29T11:37:12.673Z egg-core Loaded dirs [{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-session","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-security","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-jsonp","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-onerror","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-i18n","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-watcher","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-schedule","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-multipart","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-development","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-logrotator","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-static","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-view","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg","type":"framework"},{"path":"/Users/didi/myproject/egg-analysis","type":"app"}]
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +0ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +1ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +17ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +2ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +10ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +4ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +1ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +1ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +1ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +1ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +1ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +1ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +3ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +1ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +2ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +1ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +1ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +2ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +2ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +1ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +7ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +4ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +1ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
  egg-ts-helper#watcher execution undefined +0ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +16ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
  egg-ts-helper#generators_extend file list : [] +0ms
  egg-ts-helper#watcher execution undefined +6ms
  egg-ts-helper#generators_class file list : [ 'home.js' ] +0ms
[egg-ts-helper] create typings/app/controller/index.d.ts (10ms)
  egg-ts-helper#watcher execution undefined +11ms
  egg-ts-helper#generators_class file list : [] +9ms
  egg-ts-helper#watcher execution undefined +1ms
  egg-ts-helper#generators_class file list : [] +2ms
  egg-ts-helper#watcher execution undefined +1ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +18ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
[egg-ts-helper] create typings/config/index.d.ts (38ms)
  egg-ts-helper#watcher execution undefined +39ms
[egg-ts-helper] create typings/config/plugin.d.ts (3ms)
  egg-ts-helper#watcher execution undefined +4ms
  egg-ts-helper#generators_class file list : [] +44ms
  egg-ts-helper#watcher execution undefined +1ms
[egg-ts-helper] create typings/app/index.d.ts (1ms)
  egg-ts-helper#watcher execution undefined +1ms
  egg-bin:start-cluster start cluster options: {"typescript":false,"declarations":true,"workers":1,"baseDir":"/Users/didi/myproject/egg-analysis","framework":"/Users/didi/myproject/egg-analysis/node_modules/egg"} +0ms
2019-07-29 19:37:13,145 INFO 4320 [master] node version v8.15.1
2019-07-29 19:37:13,145 INFO 4320 [master] egg version 2.23.0
  detect-port detect free port between [0, 10) +0ms
  detect-port get free null:63664 +4ms
  egg-ts-helper#register egg-ts-helper watcher has ran in 4320 +0ms
  egg-cluster new Agent with options {"framework":"/Users/didi/myproject/egg-analysis/node_modules/egg","baseDir":"/Users/didi/myproject/egg-analysis","workers":1,"plugins":null,"https":false,"typescript":false,"declarations":true,"clusterPort":63664} +0ms
  egg-core Loaded eggPaths ["/Users/didi/myproject/egg-analysis/node_modules/egg"] +0ms
  egg-core Loaded serverEnv "local" +1ms
  egg-core Loaded appname(analysis) from package.json +3ms
  egg-core:plugin Loaded app plugins: [] +0ms
  egg-core:plugin Loaded egg plugins: ["onerror","session","i18n","watcher","multipart","security","development","logrotator","schedule","static","jsonp","view"] +3ms
  egg-core#sequencify task: onerror is enabled by app +0ms
  egg-core#sequencify task: session is enabled by app +1ms
  egg-core#sequencify task: i18n is enabled by app +0ms
  egg-core#sequencify task: watcher is enabled by app +0ms
  egg-core#sequencify task: multipart is enabled by app +0ms
  egg-core#sequencify task: security is enabled by app +0ms
  egg-core#sequencify task: development is enabled by app +0ms
  egg-core#sequencify task: schedule is enabled by logrotator +0ms
  egg-core#sequencify task: logrotator is enabled by app +0ms
  egg-core#sequencify task: static is enabled by app +31ms
  egg-core#sequencify task: jsonp is enabled by app +0ms
  egg-core#sequencify task: view is enabled by app +0ms
  egg-core:plugin Got plugins {"sequence":["session","security","jsonp","onerror","i18n","watcher","schedule","multipart","development","logrotator","static","view"],"missingTasks":[],"recursiveDependencies":[]} after sequencify +40ms
  egg-core:plugin Loaded plugins: ["session","security","jsonp","onerror","i18n","watcher","schedule","multipart","development","logrotator","static","view"] +1ms
  egg-core Loaded dirs [{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-session","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-security","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-jsonp","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-onerror","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-i18n","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-watcher","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-schedule","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-multipart","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-development","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-logrotator","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-static","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-view","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg","type":"framework"},{"path":"/Users/didi/myproject/egg-analysis","type":"app"}] +52ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-session/config.default, {"session":{"maxAge":86400000,"key":"EGG_SESS","httpOnly":true,"encrypt":true}} +0ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-security/config.default, {"security":{"domainWhiteList":[],"protocolWhiteList":[],"defaultMiddleware":"csrf,hsts,methodnoallow,noopen,nosniff,csp,xssProtection,xframe,dta","csrf":{"enable":true,"useSession":false,"ignoreJSON":false,"cookieName":"csrfToken","sessionName":"csrfToken","headerName":"x-csrf-token","bodyName":"_csrf","queryName":"_csrf"},"xframe":{"enable":true,"value":"SAMEORIGIN"},"hsts":{"enable":false,"maxAge":31536000,"includeSubdomains":false},"dta":{"enable":true},"methodnoallow":{"enable":true},"noopen":{"enable":true},"nosniff":{"enable":true},"referrerPolicy":{"enable":false,"value":"no-referrer-when-downgrade"},"xssProtection":{"enable":true,"value":"1; mode=block"},"csp":{"enable":false,"policy":{}},"ssrf":{"ipBlackList":null,"checkAddress":null}},"helper":{"shtml":{}}} +8ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-jsonp/config.default, {"jsonp":{"limit":50,"callback":["_callback","callback"],"csrf":false}} +3ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-onerror/config.default, {"onerror":{"errorPageUrl":"","appErrorFilter":null,"templatePath":"/Users/didi/myproject/egg-analysis/node_modules/egg-onerror/lib/onerror_page.mustache"}} +1ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-i18n/config.default, {"i18n":{"defaultLocale":"en_US","dirs":[],"queryField":"locale","cookieField":"locale","cookieDomain":"","cookieMaxAge":"1y"}} +1ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-watcher/config.default, {"watcher":{"type":"default","eventSources":{"default":"/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/lib/event-sources/default","development":"/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/lib/event-sources/development"}}} +14ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-schedule/config.default, {"customLogger":{"scheduleLogger":{"consoleLevel":"NONE","file":"egg-schedule.log"}},"schedule":{"directory":[]}} +2ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-multipart/config.default, {"multipart":{"mode":"stream","autoFields":false,"defaultCharset":"utf8","fieldNameSize":100,"fieldSize":"100kb","fields":10,"fileSize":"10mb","files":10,"fileExtensions":[],"whitelist":null,"tmpdir":"/var/folders/2w/tt1p_4td3yq9xlbl7c2t4jn00000gn/T/egg-multipart-tmp/analysis","cleanSchedule":{"cron":"0 30 4 * * *"}}} +1ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-development/config.default, {"development":{"watchDirs":[],"ignoreDirs":[],"fastReady":false,"reloadOnDebug":true,"overrideDefault":false}} +1ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/config.default, {"logrotator":{"filesRotateByHour":null,"hourDelimiter":"-","filesRotateBySize":null,"maxFileSize":52428800,"maxFiles":10,"rotateDuration":60000,"maxDays":31}} +19ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-static/config.default, {"static":{"prefix":"/public/","dir":"/Users/didi/myproject/egg-analysis/app/public","dynamic":true,"preload":false,"buffer":false,"maxFiles":1000}} +11ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-view/config.default, {"view":{"root":"/Users/didi/myproject/egg-analysis/app/view","cache":true,"defaultExtension":".html","defaultViewEngine":"","mapping":{}}} +0ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg/config.default, {"env":"local","name":"analysis","keys":"","proxy":false,"maxProxyCount":0,"protocolHeaders":"x-forwarded-proto","ipHeaders":"x-forwarded-for","hostHeaders":"","pkg":{"name":"analysis","version":"1.0.0","description":"","private":true,"egg":{"declarations":true},"dependencies":{"egg":"^2.15.1","egg-scripts":"^2.11.0"},"devDependencies":{"autod":"^3.0.1","autod-egg":"^1.1.0","egg-bin":"^4.11.0","egg-ci":"^1.11.0","egg-mock":"^3.21.0","eslint":"^5.13.0","eslint-config-egg":"^7.1.0"},"engines":{"node":">=10.0.0"},"scripts":{"start":"egg-scripts start --daemon --title=egg-server-analysis","stop":"egg-scripts stop --title=egg-server-analysis","dev":"DEBUG=*,-common-bin egg-bin dev","debug":"egg-bin debug","test":"npm run lint -- --fix && npm run test-local","test-local":"egg-bin test","cov":"egg-bin cov","lint":"eslint .","ci":"npm run lint && npm run cov","autod":"autod"},"ci":{"version":"10"},"repository":{"type":"git","url":""},"author":"","license":"MIT"},"baseDir":"/Users/didi/myproject/egg-analysis","HOME":"/Users/didi","rundir":"/Users/didi/myproject/egg-analysis/run","dump":{"ignore":{}},"confusedConfigurations":{"bodyparser":"bodyParser","notFound":"notfound","sitefile":"siteFile","middlewares":"middleware","httpClient":"httpclient"},"notfound":{"pageUrl":""},"siteFile":{"/favicon.ico":{"type":"Buffer","data":[]}},"bodyParser":{"enable":true,"encoding":"utf8","formLimit":"100kb","jsonLimit":"100kb","strict":true,"queryString":{"arrayLimit":100,"depth":5,"parameterLimit":1000}},"logger":{"dir":"/Users/didi/myproject/egg-analysis/logs/analysis","encoding":"utf8","env":"local","level":"INFO","consoleLevel":"INFO","disableConsoleAfterReady":false,"outputJSON":false,"buffer":true,"appLogName":"analysis-web.log","coreLogName":"egg-web.log","agentLogName":"egg-agent.log","errorLogName":"common-error.log","coreLogger":{},"allowDebugAtProd":false},"httpclient":{"enableDNSCache":false,"dnsCacheLookupInterval":10000,"dnsCacheMaxLength":1000,"request":{"timeout":5000},"httpAgent":{"keepAlive":true,"freeSocketTimeout":4000,"maxSockets":9007199254740991,"maxFreeSockets":256},"httpsAgent":{"keepAlive":true,"freeSocketTimeout":4000,"maxSockets":9007199254740991,"maxFreeSockets":256}},"meta":{"enable":true,"logging":false},"coreMiddleware":["meta","siteFile","notfound","bodyParser","overrideMethod"],"workerStartTimeout":600000,"serverTimeout":null,"cluster":{"listen":{"path":"","port":7001,"hostname":""}},"clusterClient":{"maxWaitTime":60000,"responseTimeout":60000},"onClientError":null} +9ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/config.default, {"keys":"analysis_1564392234359_6362","middleware":[]} +126ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-security/config.local, {"security":{"hsts":{"enable":false}}} +1ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-watcher/config.local, {"watcher":{"type":"development"}} +1ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-view/config.local, {"view":{"cache":false}} +1ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg/config.local, {"logger":{"coreLogger":{"consoleLevel":"WARN"}}} +0ms
  egg-core:extend merge ["safeCurl"] to agent from /Users/didi/myproject/egg-analysis/node_modules/egg-security/app/extend/agent.js +0ms
  egg-core:extend merge ["ScheduleStrategy","TimerScheduleStrategy","schedule"] to agent from /Users/didi/myproject/egg-analysis/node_modules/egg-schedule/app/extend/agent.js +113ms
  egg-core:extend merge ["LogRotator"] to agent from /Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/app/extend/agent.js +2ms
  egg-core:extend merge ["securityOptions","isSafeDomain","nonce","csrf","ensureCsrfSecret","rotateCsrfSecret","assertCsrf","safeCurl"] to context from /Users/didi/myproject/egg-analysis/node_modules/egg-security/app/extend/context.js +21ms
  egg-core:extend merge ["acceptJSONP","createJsonpBody"] to context from /Users/didi/myproject/egg-analysis/node_modules/egg-jsonp/app/extend/context.js +3ms
  egg-core:extend merge ["locale"] to context from /Users/didi/myproject/egg-analysis/node_modules/egg-i18n/app/extend/context.js +1ms
  egg-core:extend merge ["cleanupRequestFiles","saveRequestFiles","multipart","getFileStream"] to context from /Users/didi/myproject/egg-analysis/node_modules/egg-multipart/app/extend/context.js +71ms
  egg-core:extend merge ["render","renderView","renderString","view"] to context from /Users/didi/myproject/egg-analysis/node_modules/egg-view/app/extend/context.js +1ms
  egg-core:extend merge ["cookies","httpclient","curl","router","helper","getLogger","logger","coreLogger","locals","state","runInBackground","_runInBackground","acceptJSON","queries","accept","ip","realStatus"] to context from /Users/didi/myproject/egg-analysis/node_modules/egg/app/extend/context.js +3ms
  egg:logger Init loggers with options {"env":"local","type":"agent","dir":"/Users/didi/myproject/egg-analysis/logs/analysis","encoding":"utf8","level":"INFO","consoleLevel":"INFO","outputJSON":false,"buffer":true,"appLogName":"analysis-web.log","coreLogName":"egg-web.log","agentLogName":"egg-agent.log","errorLogName":"common-error.log","concentrateError":"duplicate","disableConsoleAfterReady":false,"coreLogger":{"consoleLevel":"WARN"},"allowDebugAtProd":false} +0ms
  ready-callback [36b00540-b1f5-11e9-a017-95070c741dbf] Register task id `/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/lib/init.js:15:14` with {"timeout":10000,"isWeakDep":false,"name":"/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/lib/init.js:15:14"} +0ms
  ready-callback [36b02c50-b1f5-11e9-a017-95070c741dbf] Register task id `/Users/didi/myproject/egg-analysis/node_modules/egg-schedule/agent.js:12:9` with {"timeout":10000,"isWeakDep":false,"name":"/Users/didi/myproject/egg-analysis/node_modules/egg-schedule/agent.js:12:9"} +2ms
  ready-callback [36b05360-b1f5-11e9-a017-95070c741dbf] Register task id `/Users/didi/myproject/egg-analysis/node_modules/egg-development/agent.js:12:9` with {"timeout":10000,"isWeakDep":false,"name":"/Users/didi/myproject/egg-analysis/node_modules/egg-development/agent.js:12:9"} +0ms
  cluster-client [ClusterClient:Watcher] subscribe ["/Users/didi/myproject/egg-analysis/app","/Users/didi/myproject/egg-analysis/config","/Users/didi/myproject/egg-analysis/mocks","/Users/didi/myproject/egg-analysis/mocks_proxy","/Users/didi/myproject/egg-analysis/app.js"] +0ms
  egg-core:lifecycle register didLoad +0ms
  egg-core:loader parsing ["/Users/didi/myproject/egg-analysis/node_modules/egg-session/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-security/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-jsonp/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-onerror/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-i18n/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-schedule/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-multipart/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-development/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-static/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-view/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg/app/schedule","/Users/didi/myproject/egg-analysis/app/schedule"] +0ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +0ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +0ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-multipart/app/schedule/clean_tmpdir.js, properties ["cleanTmpdir"], export undefined +41ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/app/schedule/clean_log.js, properties ["cleanLog"], export {"schedule":{"type":"worker","cron":"0 0 * * *"}} +3ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/app/schedule/rotate_by_file.js, properties ["rotateByFile"], export {"schedule":{"type":"worker","cron":"1 0 0 * * *"}} +2ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/app/schedule/rotate_by_hour.js, properties ["rotateByHour"], export {"schedule":{"type":"worker","cron":"0 * * * *","disable":true}} +4ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/app/schedule/rotate_by_size.js, properties ["rotateBySize"], export {"schedule":{"type":"worker","interval":60000,"disable":true}} +3ms
  cluster-client:server listen 63664 success +0ms
  cluster-client [ClusterClient:Watcher] has seized port 63664, and serves as leader client. +0ms
  wt start rewatch timer every 60000ms +0ms
  wt watch(["/Users/didi/myproject/egg-analysis/app"]) +3ms
  wt walking /Users/didi/myproject/egg-analysis/app... +0ms
  wt watch(["/Users/didi/myproject/egg-analysis/config"]) +1ms
  wt walking /Users/didi/myproject/egg-analysis/config... +2ms
  ready-callback [36b02c50-b1f5-11e9-a017-95070c741dbf] End task id `/Users/didi/myproject/egg-analysis/node_modules/egg-schedule/agent.js:12:9`, error undefined +114ms
  ready-callback [36b00540-b1f5-11e9-a017-95070c741dbf] End task id `/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/lib/init.js:15:14`, error undefined +1ms
  wt fs.watch(/Users/didi/myproject/egg-analysis/app) start... +13ms
  wt fs.watch(/Users/didi/myproject/egg-analysis/config) start... +8ms
  wt _watchDir(/Users/didi/myproject/egg-analysis/config) done +1ms
  wt fs.watch(/Users/didi/myproject/egg-analysis/app/controller) start... +3ms
  ready-callback [36b05360-b1f5-11e9-a017-95070c741dbf] End task id `/Users/didi/myproject/egg-analysis/node_modules/egg-development/agent.js:12:9`, error undefined +14ms
  ready-callback [36b05360-b1f5-11e9-a017-95070c741dbf] Fire callback async +1ms
  egg-core:lifecycle didLoad done +128ms
  egg-core:lifecycle register willReady +0ms
  wt fs.watch(/Users/didi/myproject/egg-analysis/app/public) start... +1ms
  wt _watchDir(/Users/didi/myproject/egg-analysis/app) done +1ms
  ready-callback Fire callback directly +1ms
  egg-core:lifecycle trigger didReady +1ms
  egg-core:lifecycle trigger didReady done +0ms
  egg-cluster:messenger agent -> master, data: {"action":"agent-start","to":"master","from":"agent"} +0ms
  egg-cluster:messenger master -> app, data: {"action":"egg-pids","to":"app","data":[4322],"from":"master"} +0ms
  egg-cluster:messenger master -> app, data: {"action":"agent-start","to":"app","from":"master"} +1ms
2019-07-29 19:37:15,549 INFO 4320 [master] agent_worker#1:4322 started (2399ms)
  egg-cluster new Application with options {"framework":"/Users/didi/myproject/egg-analysis/node_modules/egg","baseDir":"/Users/didi/myproject/egg-analysis","workers":1,"plugins":null,"https":false,"typescript":false,"declarations":true,"clusterPort":63664} +0ms
  egg-core Loaded eggPaths ["/Users/didi/myproject/egg-analysis/node_modules/egg"] +0ms
  egg-core Loaded serverEnv "local" +1ms
  egg-core Loaded appname(analysis) from package.json +3ms
  egg-core:plugin Loaded app plugins: [] +0ms
  egg-core:plugin Loaded egg plugins: ["onerror","session","i18n","watcher","multipart","security","development","logrotator","schedule","static","jsonp","view"] +2ms
  egg-core#sequencify task: onerror is enabled by app +0ms
  egg-core#sequencify task: session is enabled by app +0ms
  egg-core#sequencify task: i18n is enabled by app +0ms
  egg-core#sequencify task: watcher is enabled by app +0ms
  egg-core#sequencify task: multipart is enabled by app +0ms
  egg-core#sequencify task: security is enabled by app +0ms
  egg-core#sequencify task: development is enabled by app +0ms
  egg-core#sequencify task: schedule is enabled by logrotator +1ms
  egg-core#sequencify task: logrotator is enabled by app +0ms
  egg-core#sequencify task: static is enabled by app +0ms
  egg-core#sequencify task: jsonp is enabled by app +0ms
  egg-core#sequencify task: view is enabled by app +0ms
  egg-core:plugin Got plugins {"sequence":["session","security","jsonp","onerror","i18n","watcher","schedule","multipart","development","logrotator","static","view"],"missingTasks":[],"recursiveDependencies":[]} after sequencify +13ms
  egg-core:plugin Loaded plugins: ["session","security","jsonp","onerror","i18n","watcher","schedule","multipart","development","logrotator","static","view"] +0ms
  egg-core Loaded dirs [{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-session","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-security","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-jsonp","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-onerror","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-i18n","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-watcher","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-schedule","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-multipart","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-development","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-logrotator","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-static","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg-view","type":"plugin"},{"path":"/Users/didi/myproject/egg-analysis/node_modules/egg","type":"framework"},{"path":"/Users/didi/myproject/egg-analysis","type":"app"}] +20ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-session/config.default, {"session":{"maxAge":86400000,"key":"EGG_SESS","httpOnly":true,"encrypt":true}} +0ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-security/config.default, {"security":{"domainWhiteList":[],"protocolWhiteList":[],"defaultMiddleware":"csrf,hsts,methodnoallow,noopen,nosniff,csp,xssProtection,xframe,dta","csrf":{"enable":true,"useSession":false,"ignoreJSON":false,"cookieName":"csrfToken","sessionName":"csrfToken","headerName":"x-csrf-token","bodyName":"_csrf","queryName":"_csrf"},"xframe":{"enable":true,"value":"SAMEORIGIN"},"hsts":{"enable":false,"maxAge":31536000,"includeSubdomains":false},"dta":{"enable":true},"methodnoallow":{"enable":true},"noopen":{"enable":true},"nosniff":{"enable":true},"referrerPolicy":{"enable":false,"value":"no-referrer-when-downgrade"},"xssProtection":{"enable":true,"value":"1; mode=block"},"csp":{"enable":false,"policy":{}},"ssrf":{"ipBlackList":null,"checkAddress":null}},"helper":{"shtml":{}}} +1ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-jsonp/config.default, {"jsonp":{"limit":50,"callback":["_callback","callback"],"csrf":false}} +1ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-onerror/config.default, {"onerror":{"errorPageUrl":"","appErrorFilter":null,"templatePath":"/Users/didi/myproject/egg-analysis/node_modules/egg-onerror/lib/onerror_page.mustache"}} +2ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-i18n/config.default, {"i18n":{"defaultLocale":"en_US","dirs":[],"queryField":"locale","cookieField":"locale","cookieDomain":"","cookieMaxAge":"1y"}} +15ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-watcher/config.default, {"watcher":{"type":"default","eventSources":{"default":"/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/lib/event-sources/default","development":"/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/lib/event-sources/development"}}} +2ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-schedule/config.default, {"customLogger":{"scheduleLogger":{"consoleLevel":"NONE","file":"egg-schedule.log"}},"schedule":{"directory":[]}} +5ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-multipart/config.default, {"multipart":{"mode":"stream","autoFields":false,"defaultCharset":"utf8","fieldNameSize":100,"fieldSize":"100kb","fields":10,"fileSize":"10mb","files":10,"fileExtensions":[],"whitelist":null,"tmpdir":"/var/folders/2w/tt1p_4td3yq9xlbl7c2t4jn00000gn/T/egg-multipart-tmp/analysis","cleanSchedule":{"cron":"0 30 4 * * *"}}} +8ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-development/config.default, {"development":{"watchDirs":[],"ignoreDirs":[],"fastReady":false,"reloadOnDebug":true,"overrideDefault":false}} +17ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/config.default, {"logrotator":{"filesRotateByHour":null,"hourDelimiter":"-","filesRotateBySize":null,"maxFileSize":52428800,"maxFiles":10,"rotateDuration":60000,"maxDays":31}} +3ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-static/config.default, {"static":{"prefix":"/public/","dir":"/Users/didi/myproject/egg-analysis/app/public","dynamic":true,"preload":false,"buffer":false,"maxFiles":1000}} +1ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-view/config.default, {"view":{"root":"/Users/didi/myproject/egg-analysis/app/view","cache":true,"defaultExtension":".html","defaultViewEngine":"","mapping":{}}} +3ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg/config.default, {"env":"local","name":"analysis","keys":"","proxy":false,"maxProxyCount":0,"protocolHeaders":"x-forwarded-proto","ipHeaders":"x-forwarded-for","hostHeaders":"","pkg":{"name":"analysis","version":"1.0.0","description":"","private":true,"egg":{"declarations":true},"dependencies":{"egg":"^2.15.1","egg-scripts":"^2.11.0"},"devDependencies":{"autod":"^3.0.1","autod-egg":"^1.1.0","egg-bin":"^4.11.0","egg-ci":"^1.11.0","egg-mock":"^3.21.0","eslint":"^5.13.0","eslint-config-egg":"^7.1.0"},"engines":{"node":">=10.0.0"},"scripts":{"start":"egg-scripts start --daemon --title=egg-server-analysis","stop":"egg-scripts stop --title=egg-server-analysis","dev":"DEBUG=*,-common-bin egg-bin dev","debug":"egg-bin debug","test":"npm run lint -- --fix && npm run test-local","test-local":"egg-bin test","cov":"egg-bin cov","lint":"eslint .","ci":"npm run lint && npm run cov","autod":"autod"},"ci":{"version":"10"},"repository":{"type":"git","url":""},"author":"","license":"MIT"},"baseDir":"/Users/didi/myproject/egg-analysis","HOME":"/Users/didi","rundir":"/Users/didi/myproject/egg-analysis/run","dump":{"ignore":{}},"confusedConfigurations":{"bodyparser":"bodyParser","notFound":"notfound","sitefile":"siteFile","middlewares":"middleware","httpClient":"httpclient"},"notfound":{"pageUrl":""},"siteFile":{"/favicon.ico":{"type":"Buffer","data":[]}},"bodyParser":{"enable":true,"encoding":"utf8","formLimit":"100kb","jsonLimit":"100kb","strict":true,"queryString":{"arrayLimit":100,"depth":5,"parameterLimit":1000}},"logger":{"dir":"/Users/didi/myproject/egg-analysis/logs/analysis","encoding":"utf8","env":"local","level":"INFO","consoleLevel":"INFO","disableConsoleAfterReady":false,"outputJSON":false,"buffer":true,"appLogName":"analysis-web.log","coreLogName":"egg-web.log","agentLogName":"egg-agent.log","errorLogName":"common-error.log","coreLogger":{},"allowDebugAtProd":false},"httpclient":{"enableDNSCache":false,"dnsCacheLookupInterval":10000,"dnsCacheMaxLength":1000,"request":{"timeout":5000},"httpAgent":{"keepAlive":true,"freeSocketTimeout":4000,"maxSockets":9007199254740991,"maxFreeSockets":256},"httpsAgent":{"keepAlive":true,"freeSocketTimeout":4000,"maxSockets":9007199254740991,"maxFreeSockets":256}},"meta":{"enable":true,"logging":false},"coreMiddleware":["meta","siteFile","notfound","bodyParser","overrideMethod"],"workerStartTimeout":600000,"serverTimeout":null,"cluster":{"listen":{"path":"","port":7001,"hostname":""}},"clusterClient":{"maxWaitTime":60000,"responseTimeout":60000},"onClientError":null} +4ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/config.default, {"keys":"analysis_1564392234359_6362","middleware":[]} +7ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-security/config.local, {"security":{"hsts":{"enable":false}}} +1ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-watcher/config.local, {"watcher":{"type":"development"}} +1ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg-view/config.local, {"view":{"cache":false}} +2ms
  egg-core:config Loaded config /Users/didi/myproject/egg-analysis/node_modules/egg/config.local, {"logger":{"coreLogger":{"consoleLevel":"WARN"}}} +3ms
  egg-core:extend merge ["sessionStore"] to application from /Users/didi/myproject/egg-analysis/node_modules/egg-session/app/extend/application.js +0ms
  egg-core:extend merge ["injectCsrf","injectNonce","injectHijackingDefense","safeCurl"] to application from /Users/didi/myproject/egg-analysis/node_modules/egg-security/app/extend/application.js +2ms
  egg-core:extend merge ["jsonp"] to application from /Users/didi/myproject/egg-analysis/node_modules/egg-jsonp/app/extend/application.js +3ms
  egg-core:extend merge ["LogRotator"] to application from /Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/app/extend/application.js +4ms
  egg-core:extend merge ["view"] to application from /Users/didi/myproject/egg-analysis/node_modules/egg-view/app/extend/application.js +8ms
  egg-core:extend merge ["host","protocol","ips","ip","acceptJSON","_customQuery","query","queries","accept"] to request from /Users/didi/myproject/egg-analysis/node_modules/egg/app/extend/request.js +6ms
  egg-core:extend merge ["length","type","realStatus"] to response from /Users/didi/myproject/egg-analysis/node_modules/egg/app/extend/response.js +4ms
  egg-core:extend merge ["securityOptions","isSafeDomain","nonce","csrf","ensureCsrfSecret","rotateCsrfSecret","assertCsrf","safeCurl"] to context from /Users/didi/myproject/egg-analysis/node_modules/egg-security/app/extend/context.js +10ms
  egg-core:extend merge ["acceptJSONP","createJsonpBody"] to context from /Users/didi/myproject/egg-analysis/node_modules/egg-jsonp/app/extend/context.js +1ms
  egg-core:extend merge ["locale"] to context from /Users/didi/myproject/egg-analysis/node_modules/egg-i18n/app/extend/context.js +1ms
  egg-core:extend merge ["cleanupRequestFiles","saveRequestFiles","multipart","getFileStream"] to context from /Users/didi/myproject/egg-analysis/node_modules/egg-multipart/app/extend/context.js +79ms
  egg-core:extend merge ["render","renderView","renderString","view"] to context from /Users/didi/myproject/egg-analysis/node_modules/egg-view/app/extend/context.js +1ms
  egg-core:extend merge ["cookies","httpclient","curl","router","helper","getLogger","logger","coreLogger","locals","state","runInBackground","_runInBackground","acceptJSON","queries","accept","ip","realStatus"] to context from /Users/didi/myproject/egg-analysis/node_modules/egg/app/extend/context.js +2ms
  egg-core:extend merge ["shtml","sjs","surl","spath","sjson","escape","cliFilter"] to helper from /Users/didi/myproject/egg-analysis/node_modules/egg-security/app/extend/helper.js +26ms
  egg-core:extend merge ["pathFor","urlFor"] to helper from /Users/didi/myproject/egg-analysis/node_modules/egg/app/extend/helper.js +2ms
  egg:plugin:i18n app.config.i18n.dirs: [ '/Users/didi/myproject/egg-analysis/node_modules/egg-session/config/locales',
  '/Users/didi/myproject/egg-analysis/node_modules/egg-security/config/locales',
  '/Users/didi/myproject/egg-analysis/node_modules/egg-jsonp/config/locales',
  '/Users/didi/myproject/egg-analysis/node_modules/egg-onerror/config/locales',
  '/Users/didi/myproject/egg-analysis/node_modules/egg-i18n/config/locales',
  '/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/config/locales',
  '/Users/didi/myproject/egg-analysis/node_modules/egg-schedule/config/locales',
  '/Users/didi/myproject/egg-analysis/node_modules/egg-multipart/config/locales',
  '/Users/didi/myproject/egg-analysis/node_modules/egg-development/config/locales',
  '/Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/config/locales',
  '/Users/didi/myproject/egg-analysis/node_modules/egg-static/config/locales',
  '/Users/didi/myproject/egg-analysis/node_modules/egg-view/config/locales',
  '/Users/didi/myproject/egg-analysis/node_modules/egg/config/locales',
  '/Users/didi/myproject/egg-analysis/config/locales' ] +0ms
  koa-locales Init locales with {"defaultLocale":"en_US","queryField":"locale","cookieField":"locale","localeAlias":{},"writeCookie":true,"cookieMaxAge":"1y","dirs":["/Users/didi/myproject/egg-analysis/node_modules/egg-session/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-security/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-jsonp/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-onerror/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-i18n/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-schedule/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-multipart/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-development/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-static/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-view/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg/config/locales","/Users/didi/myproject/egg-analysis/config/locales"],"functionName":"__","cookieDomain":""}, got [] resources +0ms
  egg:logger Init loggers with options {"env":"local","type":"application","dir":"/Users/didi/myproject/egg-analysis/logs/analysis","encoding":"utf8","level":"INFO","consoleLevel":"INFO","outputJSON":false,"buffer":true,"appLogName":"analysis-web.log","coreLogName":"egg-web.log","agentLogName":"egg-agent.log","errorLogName":"common-error.log","concentrateError":"duplicate","disableConsoleAfterReady":false,"coreLogger":{"consoleLevel":"WARN"},"allowDebugAtProd":false} +0ms
  cluster-client:server try to connecting 63664 +0ms
  ready-callback [37b5dc80-b1f5-11e9-a78c-8bde7215bddf] Register task id `/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/lib/init.js:15:14` with {"timeout":10000,"isWeakDep":false,"name":"/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/lib/init.js:15:14"} +0ms
  egg-core:loader parsing ["/Users/didi/myproject/egg-analysis/node_modules/egg-session/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-security/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-jsonp/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-onerror/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-i18n/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-schedule/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-multipart/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-development/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-static/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg-view/app/schedule","/Users/didi/myproject/egg-analysis/node_modules/egg/app/schedule","/Users/didi/myproject/egg-analysis/app/schedule"] +0ms
  snapdragon:compiler initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/compiler.js +0ms
  snapdragon:parser initializing /Users/didi/myproject/egg-analysis/node_modules/snapdragon/lib/parser.js +15ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-multipart/app/schedule/clean_tmpdir.js, properties ["cleanTmpdir"], export undefined +80ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/app/schedule/clean_log.js, properties ["cleanLog"], export {"schedule":{"type":"worker","cron":"0 0 * * *"}} +3ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/app/schedule/rotate_by_file.js, properties ["rotateByFile"], export {"schedule":{"type":"worker","cron":"1 0 0 * * *"}} +2ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/app/schedule/rotate_by_hour.js, properties ["rotateByHour"], export {"schedule":{"type":"worker","cron":"0 * * * *","disable":true}} +1ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/app/schedule/rotate_by_size.js, properties ["rotateBySize"], export {"schedule":{"type":"worker","interval":60000,"disable":true}} +1ms
  egg-core:lifecycle register didLoad +0ms
  egg-core:loader parsing ["/Users/didi/myproject/egg-analysis/node_modules/egg-session/app/service","/Users/didi/myproject/egg-analysis/node_modules/egg-security/app/service","/Users/didi/myproject/egg-analysis/node_modules/egg-jsonp/app/service","/Users/didi/myproject/egg-analysis/node_modules/egg-onerror/app/service","/Users/didi/myproject/egg-analysis/node_modules/egg-i18n/app/service","/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/app/service","/Users/didi/myproject/egg-analysis/node_modules/egg-schedule/app/service","/Users/didi/myproject/egg-analysis/node_modules/egg-multipart/app/service","/Users/didi/myproject/egg-analysis/node_modules/egg-development/app/service","/Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/app/service","/Users/didi/myproject/egg-analysis/node_modules/egg-static/app/service","/Users/didi/myproject/egg-analysis/node_modules/egg-view/app/service","/Users/didi/myproject/egg-analysis/node_modules/egg/app/service","/Users/didi/myproject/egg-analysis/app/service"] +4ms
  egg-core:loader parsing ["/Users/didi/myproject/egg-analysis/node_modules/egg-session/app/middleware","/Users/didi/myproject/egg-analysis/node_modules/egg-security/app/middleware","/Users/didi/myproject/egg-analysis/node_modules/egg-jsonp/app/middleware","/Users/didi/myproject/egg-analysis/node_modules/egg-onerror/app/middleware","/Users/didi/myproject/egg-analysis/node_modules/egg-i18n/app/middleware","/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/app/middleware","/Users/didi/myproject/egg-analysis/node_modules/egg-schedule/app/middleware","/Users/didi/myproject/egg-analysis/node_modules/egg-multipart/app/middleware","/Users/didi/myproject/egg-analysis/node_modules/egg-development/app/middleware","/Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/app/middleware","/Users/didi/myproject/egg-analysis/node_modules/egg-static/app/middleware","/Users/didi/myproject/egg-analysis/node_modules/egg-view/app/middleware","/Users/didi/myproject/egg-analysis/node_modules/egg/app/middleware","/Users/didi/myproject/egg-analysis/app/middleware"] +3ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-session/app/middleware/session.js, properties ["session"], export undefined +113ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-security/app/middleware/securities.js, properties ["securities"], export undefined +3ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-i18n/app/middleware/i18n.js, properties ["i18n"], export undefined +2ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-multipart/app/middleware/multipart.js, properties ["multipart"], export undefined +6ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-development/app/middleware/egg_loader_trace.js, properties ["eggLoaderTrace"], export undefined +2ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg-static/app/middleware/static.js, properties ["static"], export undefined +24ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg/app/middleware/body_parser.js, properties ["bodyParser"], export undefined +26ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg/app/middleware/meta.js, properties ["meta"], export undefined +1ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg/app/middleware/notfound.js, properties ["notfound"], export undefined +1ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg/app/middleware/override_method.js, properties ["overrideMethod"], export undefined +2ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/node_modules/egg/app/middleware/site_file.js, properties ["siteFile"], export undefined +1ms
  egg-core:loader loading item {"fullpath":"/Users/didi/myproject/egg-analysis/node_modules/egg-session/app/middleware/session.js","properties":["session"]} +0ms
  egg-core:loader loaded session +0ms
  egg-core:loader loading item {"fullpath":"/Users/didi/myproject/egg-analysis/node_modules/egg-security/app/middleware/securities.js","properties":["securities"]} +0ms
  egg-core:loader loaded securities +1ms
  egg-core:loader loading item {"fullpath":"/Users/didi/myproject/egg-analysis/node_modules/egg-i18n/app/middleware/i18n.js","properties":["i18n"]} +0ms
  egg-core:loader loaded i18n +2ms
  egg-core:loader loading item {"fullpath":"/Users/didi/myproject/egg-analysis/node_modules/egg-multipart/app/middleware/multipart.js","properties":["multipart"]} +0ms
  egg-core:loader loaded multipart +1ms
  egg-core:loader loading item {"fullpath":"/Users/didi/myproject/egg-analysis/node_modules/egg-development/app/middleware/egg_loader_trace.js","properties":["eggLoaderTrace"]} +1ms
  egg-core:loader loaded eggLoaderTrace +14ms
  egg-core:loader loading item {"fullpath":"/Users/didi/myproject/egg-analysis/node_modules/egg-static/app/middleware/static.js","properties":["static"]} +0ms
  egg-core:loader loaded static +0ms
  egg-core:loader loading item {"fullpath":"/Users/didi/myproject/egg-analysis/node_modules/egg/app/middleware/body_parser.js","properties":["bodyParser"]} +0ms
  egg-core:loader loaded bodyParser +0ms
  egg-core:loader loading item {"fullpath":"/Users/didi/myproject/egg-analysis/node_modules/egg/app/middleware/meta.js","properties":["meta"]} +0ms
  egg-core:loader loaded meta +0ms
  egg-core:loader loading item {"fullpath":"/Users/didi/myproject/egg-analysis/node_modules/egg/app/middleware/notfound.js","properties":["notfound"]} +0ms
  egg-core:loader loaded notfound +0ms
  egg-core:loader loading item {"fullpath":"/Users/didi/myproject/egg-analysis/node_modules/egg/app/middleware/override_method.js","properties":["overrideMethod"]} +0ms
  egg-core:loader loaded overrideMethod +0ms
  egg-core:loader loading item {"fullpath":"/Users/didi/myproject/egg-analysis/node_modules/egg/app/middleware/site_file.js","properties":["siteFile"]} +0ms
  egg-core:loader loaded siteFile +0ms
  egg-core:middleware middlewareNames: ["meta","siteFile","notfound","static","bodyParser","overrideMethod","session","securities","i18n","eggLoaderTrace"] +0ms
  egg-core use metaDebugWrapper +0ms
  egg-core:middleware Use middleware: meta with options: {"enable":true,"logging":false} +1ms
  egg-core use siteFileDebugWrapper +1ms
  egg-core:middleware Use middleware: siteFile with options: {"/favicon.ico":{"type":"Buffer","data":[]}} +1ms
  egg-core use notfoundDebugWrapper +7ms
  egg-core:middleware Use middleware: notfound with options: {"pageUrl":""} +8ms
  egg-core use staticDebugWrapper +4ms
  egg-core:middleware Use middleware: static with options: {"prefix":"/public/","dir":"/Users/didi/myproject/egg-analysis/app/public","dynamic":true,"preload":false,"buffer":false,"maxFiles":1000} +4ms
  egg-core use bodyParserDebugWrapper +4ms
  egg-core:middleware Use middleware: bodyParser with options: {"enable":true,"encoding":"utf8","formLimit":"100kb","jsonLimit":"100kb","strict":true,"queryString":{"arrayLimit":100,"depth":5,"parameterLimit":1000},"returnRawBody":true} +3ms
  egg-core use overrideMethodDebugWrapper +1ms
  egg-core:middleware Use middleware: overrideMethod with options: {"allowedMethods":["POST"]} +1ms
  koa-session session options {"maxAge":86400000,"key":"EGG_SESS","httpOnly":true,"encrypt":true,"overwrite":true,"signed":true,"autoCommit":true} +0ms
  egg-core use sessionDebugWrapper +8ms
  egg-core:middleware Use middleware: session with options: {"maxAge":86400000,"key":"EGG_SESS","httpOnly":true,"encrypt":true,"overwrite":true,"signed":true,"autoCommit":true} +8ms
  egg-core use securitiesDebugWrapper +18ms
  egg-core:middleware Use middleware: securities with options: {} +18ms
  egg-core use i18nDebugWrapper +1ms
  egg-core:middleware Use middleware: i18n with options: {"defaultLocale":"en_US","dirs":["/Users/didi/myproject/egg-analysis/node_modules/egg-session/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-security/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-jsonp/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-onerror/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-i18n/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-schedule/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-multipart/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-development/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-logrotator/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-static/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg-view/config/locales","/Users/didi/myproject/egg-analysis/node_modules/egg/config/locales","/Users/didi/myproject/egg-analysis/config/locales"],"queryField":"locale","cookieField":"locale","cookieDomain":"","cookieMaxAge":"1y","functionName":"__"} +1ms
  egg-core use eggLoaderTraceDebugWrapper +0ms
  egg-core:middleware Use middleware: eggLoaderTrace with options: {} +0ms
  egg-core:loader parsing ["/Users/didi/myproject/egg-analysis/app/controller"] +48ms
  egg-core:loader parse /Users/didi/myproject/egg-analysis/app/controller/home.js, properties ["home"], export {} +8ms
  egg-core:loader loading item {"fullpath":"/Users/didi/myproject/egg-analysis/app/controller/home.js","properties":["home"],"exports":{}} +0ms
  egg-core:loader loaded home +2ms
  ready-callback [37ed6740-b1f5-11e9-a78c-8bde7215bddf] Register task id `/Users/didi/myproject/egg-analysis/node_modules/egg-core/lib/egg.js:303:10` with {"timeout":10000,"isWeakDep":false,"name":"/Users/didi/myproject/egg-analysis/node_modules/egg-core/lib/egg.js:303:10"} +367ms
  egg-router:layer defined route HEAD,GET / +0ms
  egg-cluster:messenger app -> master, data: {"to":"master","action":"realport","data":{"port":7001,"protocol":"http"},"from":"app"} +2s
  cluster-client:server new socket 63665 from follower +2s
  egg-core use dispatch +64ms
  cluster-client:server test connected 63664 success, end now +414ms
  cluster-client [ClusterClient:Watcher] gives up seizing port 63664, and serves as follower client. +0ms
  cluster-client:server new socket 63666 from follower +22ms
  ready-callback [37ed6740-b1f5-11e9-a78c-8bde7215bddf] End task id `/Users/didi/myproject/egg-analysis/node_modules/egg-core/lib/egg.js:303:10`, error undefined +63ms
  cluster-client:server socket 63665 close +4ms
  cluster-client:server new Watcher_connection 63666 connected +13ms
  cluster-client#leader [Leader:Watcher] socket connected, port: 63666 +0ms
  serialize-json#JSONEncoder calling buildAst with type: object and data: {"success":true} +0ms
  serialize-json#JSONEncoder calling buildAst with type: string and data: "success" +1ms
  serialize-json#JSONEncoder calling buildAst with type: boolean and data: true +0ms
  serialize-json#JSONEncoder pack the json => success^^^^$0|-1] +0ms
  serialize-json#JSONDecoder decode packed json => success^^^^$0|-1], with dictionary ["success"] +0ms
  serialize-json#JSONDecoder --> unpack plain object begin +1ms
  serialize-json#JSONDecoder --> unpack plain object end, {"success":true} +1ms
  cluster-client#follower [Follower:Watcher] register to channel: Watcher success +0ms
  ready-callback [37b5dc80-b1f5-11e9-a78c-8bde7215bddf] End task id `/Users/didi/myproject/egg-analysis/node_modules/egg-watcher/lib/init.js:15:14`, error undefined +31ms
  ready-callback [37b5dc80-b1f5-11e9-a78c-8bde7215bddf] Fire callback async +0ms
  egg-core:lifecycle didLoad done +365ms
  egg-core:lifecycle register willReady +1ms
  ready-callback Fire callback directly +2ms
  egg-core:lifecycle trigger didReady +1ms
  egg-core:lifecycle trigger didReady done +0ms
  egg-cluster listen options 7001 +858ms
  egg-cluster:messenger app -> master, data: {"action":"app-start","data":{"workerPid":4323,"address":{"addressType":4,"address":null,"port":7001}},"to":"master","from":"app"} +84ms
  egg-cluster:messenger master -> agent, data: {"action":"egg-pids","to":"agent","data":[4323],"from":"master"} +1ms
2019-07-29 19:37:17,613 INFO 4320 [master] egg started on http://127.0.0.1:7001 (4467ms)
  egg-cluster:messenger master -> parent, data: {"action":"egg-ready","to":"parent","data":{"port":7001,"address":"http://127.0.0.1:7001","protocol":"http"},"from":"master"} +1ms
  egg-cluster:messenger master -> app, data: {"action":"egg-ready","to":"app","data":{"framework":"/Users/didi/myproject/egg-analysis/node_modules/egg","baseDir":"/Users/didi/myproject/egg-analysis","workers":1,"plugins":null,"https":false,"typescript":false,"declarations":true,"clusterPort":63664},"from":"master"} +0ms
  egg-cluster:messenger master -> agent, data: {"action":"egg-ready","to":"agent","data":{"framework":"/Users/didi/myproject/egg-analysis/node_modules/egg","baseDir":"/Users/didi/myproject/egg-analysis","workers":1,"plugins":null,"https":false,"typescript":false,"declarations":true,"clusterPort":63664},"from":"master"} +0ms
  egg:util:messenger:ipc [4322] got message egg-pids with [4323], receiverPid: undefined +0ms
  egg:util:messenger:ipc [4322] got message egg-ready with {"framework":"/Users/didi/myproject/egg-analysis/node_modules/egg","baseDir":"/Users/didi/myproject/egg-analysis","workers":1,"plugins":null,"https":false,"typescript":false,"declarations":true,"clusterPort":63664}, receiverPid: undefined +1ms
  egg:util:messenger:ipc [4323] got message egg-ready with {"framework":"/Users/didi/myproject/egg-analysis/node_modules/egg","baseDir":"/Users/didi/myproject/egg-analysis","workers":1,"plugins":null,"https":false,"typescript":false,"declarations":true,"clusterPort":63664}, receiverPid: undefined +0ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":3,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":4,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +60s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +0ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":5,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":6,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":7,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +1m
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +1ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":8,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":9,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":10,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +1m
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +0ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":11,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":12,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":13,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +1m
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +0ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":14,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":15,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":16,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +1m
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +0ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":17,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":18,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":19,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +1m
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +0ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":20,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":21,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":22,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +1m
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +0ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":23,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":24,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":25,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +1m
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +0ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":26,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":27,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":28,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +1m
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +0ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":29,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":30,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":31,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +1m
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +0ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":32,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":33,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":34,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +1m
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +1ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":35,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":36,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":37,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +1m
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +0ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":38,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":39,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":40,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +1m
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +0ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":41,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":42,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":43,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +1m
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +0ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":44,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":45,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":46,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +1m
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +1ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":47,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  egg-core:middleware [GET /] enter middleware: meta +15m
  egg-core:middleware [GET /] enter middleware: siteFile +0ms
  egg-core:middleware [GET /] enter middleware: notfound +1ms
  egg-core:middleware [GET /] enter middleware: static +0ms
  egg-core:middleware [GET /] enter middleware: bodyParser +1ms
  egg-core:middleware [GET /] enter middleware: overrideMethod +3ms
  egg-core:middleware [GET /] enter middleware: session +1ms
  egg-core:middleware [GET /] enter middleware: securities +1ms
  egg-core:middleware [GET /] enter middleware: i18n +2ms
  egg-core:middleware [GET /] enter middleware: eggLoaderTrace +1ms
  egg-router GET / +0ms
  egg-router test / /^(?:\/(?=$))?$/ +1ms
  egg-core:middleware [GET /favicon.ico] enter middleware: meta +41ms
  egg-core:middleware [GET /favicon.ico] enter middleware: siteFile +0ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":48,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":49,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/config, error: null, exists: true +1m
  wt [watchDirIfExists] /Users/didi/myproject/egg-analysis/app, error: null, exists: true +0ms
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":50,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":51,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s
  cluster-client#leader [Leader:Watcher] received heartbeat request from follower, req: {"id":52,"isResponse":false,"timeout":60000,"connObj":{"type":"heartbeat"}}, conn: 63666 +20s

```