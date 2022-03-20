
## Features

- Support ci container logs (#185)
- Add plugin for fastapi (#181)
- Add plugin for mysqlclient (#178)
- Move flake configs all together (#169)
- Introduce another set of flake8 extensions (#174)
- The local log stack depth is not truncated (#190)
- Introduce better coding style (#171)

## BugFix

- Fix sw_formatter wrongly set cache that impacts user handlers (#192)
- Fix agent bootup traceback not shown in sw-python cli (#183)
- Update mysql plugin to support two different parameter keys (#186)
- Flask + nginx got keyerror : 'remote_port ' in sw_flask.py plugin (#176)
- Updated deprecated configuration (#179)
- Fix aiohttp outgoing request url (#175)
- Refactor skywalking python to use the cli for ci instead of legacy setup (#165)
- Fix sw-rabbitmq typeerror when there are no headers (#182)
- Add missing ending quote (#177)
- Spans correctly reference finished parents (#161)
- Filled out rest of psycopg 0 plugin (#168)
- Revert `` the local log stack depth is not truncated `` (#191)

## Documentation

- Cleanup the release notes (#160)
- Fix broken url (#163)
- Right doc link for how to use with uwsgi (#189)
- Doc : add ` how to use with uwsgi ` (#188)
- Remove docs from main readme.md - add website doc links (#164)

## NonFunctional

- Add the code &gt; 0 is error (#187)
- Refactor current python agent docs to serve on skywalking official website (#162)
- Cleanup and python 3 0 support (#167)
- Enable faster ci by categorical parallelism (#170)
- Minimize ` exclude ` in lint (#173)
- Remove places that mentions python 3 0 support due to eol (#166)
