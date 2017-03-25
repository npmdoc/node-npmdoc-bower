# api documentation for  [bower (v1.8.0)](http://bower.io)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bower.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bower)
#### The browser package manager

[![NPM](https://nodei.co/npm/bower.png?downloads=true)](https://www.npmjs.com/package/bower)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bower/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-bower_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bower/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-bower/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Twitter"
    },
    "bin": {
        "bower": "bin/bower"
    },
    "bugs": {
        "url": "https://github.com/bower/bower/issues"
    },
    "dependencies": {},
    "description": "The browser package manager",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "55dbebef0ad9155382d9e9d3e497c1372345b44a",
        "tarball": "https://registry.npmjs.org/bower/-/bower-1.8.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "bin",
        "lib"
    ],
    "homepage": "http://bower.io",
    "keywords": [
        "bower"
    ],
    "license": "MIT",
    "main": "lib",
    "maintainers": [
        {
            "name": "desandro",
            "email": "desandrocodes@gmail.com"
        },
        {
            "name": "paulirish",
            "email": "paul.irish@gmail.com"
        },
        {
            "name": "satazor",
            "email": "andremiguelcruz@msn.com"
        },
        {
            "name": "sheerun",
            "email": "sheerun@sher.pl"
        },
        {
            "name": "sindresorhus",
            "email": "sindresorhus@gmail.com"
        },
        {
            "name": "vladikoff",
            "email": "vlad@vladikoff.com"
        },
        {
            "name": "wibblymat",
            "email": "mat@wibbly.org.uk"
        }
    ],
    "name": "bower",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bower/bower.git"
    },
    "scripts": {},
    "version": "1.8.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module bower](#apidoc.module.bower)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.help ()](#apidoc.element.bower.commands.help)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.home ()](#apidoc.element.bower.commands.home)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.info ()](#apidoc.element.bower.commands.info)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.init ()](#apidoc.element.bower.commands.init)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.install ()](#apidoc.element.bower.commands.install)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.link ()](#apidoc.element.bower.commands.link)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.list ()](#apidoc.element.bower.commands.list)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.login ()](#apidoc.element.bower.commands.login)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.lookup ()](#apidoc.element.bower.commands.lookup)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.prune ()](#apidoc.element.bower.commands.prune)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.register ()](#apidoc.element.bower.commands.register)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.search ()](#apidoc.element.bower.commands.search)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.uninstall ()](#apidoc.element.bower.commands.uninstall)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.unregister ()](#apidoc.element.bower.commands.unregister)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.update ()](#apidoc.element.bower.commands.update)
1.  [function <span class="apidocSignatureSpan">bower.</span>commands.version ()](#apidoc.element.bower.commands.version)
1.  [function <span class="apidocSignatureSpan">bower.</span>reset ()](#apidoc.element.bower.reset)
1.  object <span class="apidocSignatureSpan">bower.</span>abbreviations
1.  object <span class="apidocSignatureSpan">bower.</span>commands
1.  object <span class="apidocSignatureSpan">bower.</span>commands.cache
1.  object <span class="apidocSignatureSpan">bower.</span>config
1.  object <span class="apidocSignatureSpan">bower.</span>renderers
1.  string <span class="apidocSignatureSpan">bower.</span>version

#### [module bower.commands](#apidoc.module.bower.commands)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>help ()](#apidoc.element.bower.commands.help)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>home ()](#apidoc.element.bower.commands.home)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>info ()](#apidoc.element.bower.commands.info)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>init ()](#apidoc.element.bower.commands.init)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>install ()](#apidoc.element.bower.commands.install)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>link ()](#apidoc.element.bower.commands.link)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>list ()](#apidoc.element.bower.commands.list)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>login ()](#apidoc.element.bower.commands.login)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>lookup ()](#apidoc.element.bower.commands.lookup)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>prune ()](#apidoc.element.bower.commands.prune)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>register ()](#apidoc.element.bower.commands.register)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>search ()](#apidoc.element.bower.commands.search)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>uninstall ()](#apidoc.element.bower.commands.uninstall)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>unregister ()](#apidoc.element.bower.commands.unregister)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>update ()](#apidoc.element.bower.commands.update)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>version ()](#apidoc.element.bower.commands.version)
1.  object <span class="apidocSignatureSpan">bower.commands.</span>cache

#### [module bower.commands.cache](#apidoc.module.bower.commands.cache)
1.  [function <span class="apidocSignatureSpan">bower.commands.cache.</span>clean ()](#apidoc.element.bower.commands.cache.clean)
1.  [function <span class="apidocSignatureSpan">bower.commands.cache.</span>list ()](#apidoc.element.bower.commands.cache.list)

#### [module bower.commands.help](#apidoc.module.bower.commands.help)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>help ()](#apidoc.element.bower.commands.help.help)
1.  [function <span class="apidocSignatureSpan">bower.commands.help.</span>line (argv)](#apidoc.element.bower.commands.help.line)

#### [module bower.commands.home](#apidoc.module.bower.commands.home)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>home ()](#apidoc.element.bower.commands.home.home)
1.  [function <span class="apidocSignatureSpan">bower.commands.home.</span>line (argv)](#apidoc.element.bower.commands.home.line)

#### [module bower.commands.info](#apidoc.module.bower.commands.info)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>info ()](#apidoc.element.bower.commands.info.info)
1.  [function <span class="apidocSignatureSpan">bower.commands.info.</span>line (argv)](#apidoc.element.bower.commands.info.line)

#### [module bower.commands.init](#apidoc.module.bower.commands.init)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>init ()](#apidoc.element.bower.commands.init.init)
1.  [function <span class="apidocSignatureSpan">bower.commands.init.</span>line (argv)](#apidoc.element.bower.commands.init.line)

#### [module bower.commands.install](#apidoc.module.bower.commands.install)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>install ()](#apidoc.element.bower.commands.install.install)
1.  [function <span class="apidocSignatureSpan">bower.commands.install.</span>line (argv)](#apidoc.element.bower.commands.install.line)

#### [module bower.commands.link](#apidoc.module.bower.commands.link)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>link ()](#apidoc.element.bower.commands.link.link)
1.  [function <span class="apidocSignatureSpan">bower.commands.link.</span>line (argv)](#apidoc.element.bower.commands.link.line)

#### [module bower.commands.list](#apidoc.module.bower.commands.list)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>list ()](#apidoc.element.bower.commands.list.list)
1.  [function <span class="apidocSignatureSpan">bower.commands.list.</span>line (argv)](#apidoc.element.bower.commands.list.line)

#### [module bower.commands.login](#apidoc.module.bower.commands.login)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>login ()](#apidoc.element.bower.commands.login.login)
1.  [function <span class="apidocSignatureSpan">bower.commands.login.</span>line (argv)](#apidoc.element.bower.commands.login.line)

#### [module bower.commands.lookup](#apidoc.module.bower.commands.lookup)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>lookup ()](#apidoc.element.bower.commands.lookup.lookup)
1.  [function <span class="apidocSignatureSpan">bower.commands.lookup.</span>line (argv)](#apidoc.element.bower.commands.lookup.line)

#### [module bower.commands.prune](#apidoc.module.bower.commands.prune)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>prune ()](#apidoc.element.bower.commands.prune.prune)
1.  [function <span class="apidocSignatureSpan">bower.commands.prune.</span>line (argv)](#apidoc.element.bower.commands.prune.line)

#### [module bower.commands.register](#apidoc.module.bower.commands.register)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>register ()](#apidoc.element.bower.commands.register.register)
1.  [function <span class="apidocSignatureSpan">bower.commands.register.</span>line (argv)](#apidoc.element.bower.commands.register.line)

#### [module bower.commands.search](#apidoc.module.bower.commands.search)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>search ()](#apidoc.element.bower.commands.search.search)
1.  [function <span class="apidocSignatureSpan">bower.commands.search.</span>line (argv)](#apidoc.element.bower.commands.search.line)

#### [module bower.commands.uninstall](#apidoc.module.bower.commands.uninstall)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>uninstall ()](#apidoc.element.bower.commands.uninstall.uninstall)
1.  [function <span class="apidocSignatureSpan">bower.commands.uninstall.</span>line (argv)](#apidoc.element.bower.commands.uninstall.line)

#### [module bower.commands.unregister](#apidoc.module.bower.commands.unregister)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>unregister ()](#apidoc.element.bower.commands.unregister.unregister)
1.  [function <span class="apidocSignatureSpan">bower.commands.unregister.</span>line (argv)](#apidoc.element.bower.commands.unregister.line)

#### [module bower.commands.update](#apidoc.module.bower.commands.update)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>update ()](#apidoc.element.bower.commands.update.update)
1.  [function <span class="apidocSignatureSpan">bower.commands.update.</span>line (argv)](#apidoc.element.bower.commands.update.line)

#### [module bower.commands.version](#apidoc.module.bower.commands.version)
1.  [function <span class="apidocSignatureSpan">bower.commands.</span>version ()](#apidoc.element.bower.commands.version.version)
1.  [function <span class="apidocSignatureSpan">bower.commands.version.</span>line (argv)](#apidoc.element.bower.commands.version.line)

#### [module bower.config](#apidoc.module.bower.config)
1.  [function <span class="apidocSignatureSpan">bower.</span>config (config)](#apidoc.element.bower.config.config)
1.  [function <span class="apidocSignatureSpan">bower.config.</span>reset ()](#apidoc.element.bower.config.reset)
1.  [function <span class="apidocSignatureSpan">bower.config.</span>restore ()](#apidoc.element.bower.config.restore)

#### [module bower.renderers](#apidoc.module.bower.renderers)
1.  [function <span class="apidocSignatureSpan">bower.renderers.</span>Json ()](#apidoc.element.bower.renderers.Json)
1.  [function <span class="apidocSignatureSpan">bower.renderers.</span>Standard (command, config)](#apidoc.element.bower.renderers.Standard)



# <a name="apidoc.module.bower"></a>[module bower](#apidoc.module.bower)

#### <a name="apidoc.element.bower.commands.help"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.help ()](#apidoc.element.bower.commands.help)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.home"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.home ()](#apidoc.element.bower.commands.home)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.info"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.info ()](#apidoc.element.bower.commands.info)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.init"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.init ()](#apidoc.element.bower.commands.init)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.install"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.install ()](#apidoc.element.bower.commands.install)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.link"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.link ()](#apidoc.element.bower.commands.link)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.list"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.list ()](#apidoc.element.bower.commands.list)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.login"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.login ()](#apidoc.element.bower.commands.login)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.lookup"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.lookup ()](#apidoc.element.bower.commands.lookup)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.prune"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.prune ()](#apidoc.element.bower.commands.prune)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.register"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.register ()](#apidoc.element.bower.commands.register)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.search"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.search ()](#apidoc.element.bower.commands.search)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.uninstall"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.uninstall ()](#apidoc.element.bower.commands.uninstall)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.unregister"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.unregister ()](#apidoc.element.bower.commands.unregister)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.update"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.update ()](#apidoc.element.bower.commands.update)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.version"></a>[function <span class="apidocSignatureSpan">bower.</span>commands.version ()](#apidoc.element.bower.commands.version)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.reset"></a>[function <span class="apidocSignatureSpan">bower.</span>reset ()](#apidoc.element.bower.reset)
- description and source-code
```javascript
function clearRuntimeCache() {
    // Note that in edge cases, some architecture components instance's
    // in-memory cache might be skipped.
    // If that's a problem, you should create and fresh instances instead.
    var PackageRepository = require('./core/PackageRepository');
    PackageRepository.clearRuntimeCache();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands"></a>[module bower.commands](#apidoc.module.bower.commands)

#### <a name="apidoc.element.bower.commands.help"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>help ()](#apidoc.element.bower.commands.help)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.home"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>home ()](#apidoc.element.bower.commands.home)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.info"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>info ()](#apidoc.element.bower.commands.info)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.init"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>init ()](#apidoc.element.bower.commands.init)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.install"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>install ()](#apidoc.element.bower.commands.install)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.link"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>link ()](#apidoc.element.bower.commands.link)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.list"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>list ()](#apidoc.element.bower.commands.list)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.login"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>login ()](#apidoc.element.bower.commands.login)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.lookup"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>lookup ()](#apidoc.element.bower.commands.lookup)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.prune"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>prune ()](#apidoc.element.bower.commands.prune)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.register"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>register ()](#apidoc.element.bower.commands.register)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.search"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>search ()](#apidoc.element.bower.commands.search)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.uninstall"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>uninstall ()](#apidoc.element.bower.commands.uninstall)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.unregister"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>unregister ()](#apidoc.element.bower.commands.unregister)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.update"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>update ()](#apidoc.element.bower.commands.update)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.version"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>version ()](#apidoc.element.bower.commands.version)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.cache"></a>[module bower.commands.cache](#apidoc.module.bower.commands.cache)

#### <a name="apidoc.element.bower.commands.cache.clean"></a>[function <span class="apidocSignatureSpan">bower.commands.cache.</span>clean ()](#apidoc.element.bower.commands.cache.clean)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.cache.list"></a>[function <span class="apidocSignatureSpan">bower.commands.cache.</span>list ()](#apidoc.element.bower.commands.cache.list)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.help"></a>[module bower.commands.help](#apidoc.module.bower.commands.help)

#### <a name="apidoc.element.bower.commands.help.help"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>help ()](#apidoc.element.bower.commands.help.help)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.help.line"></a>[function <span class="apidocSignatureSpan">bower.commands.help.</span>line (argv)](#apidoc.element.bower.commands.help.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.home"></a>[module bower.commands.home](#apidoc.module.bower.commands.home)

#### <a name="apidoc.element.bower.commands.home.home"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>home ()](#apidoc.element.bower.commands.home.home)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.home.line"></a>[function <span class="apidocSignatureSpan">bower.commands.home.</span>line (argv)](#apidoc.element.bower.commands.home.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.info"></a>[module bower.commands.info](#apidoc.module.bower.commands.info)

#### <a name="apidoc.element.bower.commands.info.info"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>info ()](#apidoc.element.bower.commands.info.info)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.info.line"></a>[function <span class="apidocSignatureSpan">bower.commands.info.</span>line (argv)](#apidoc.element.bower.commands.info.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.init"></a>[module bower.commands.init](#apidoc.module.bower.commands.init)

#### <a name="apidoc.element.bower.commands.init.init"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>init ()](#apidoc.element.bower.commands.init.init)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.init.line"></a>[function <span class="apidocSignatureSpan">bower.commands.init.</span>line (argv)](#apidoc.element.bower.commands.init.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.install"></a>[module bower.commands.install](#apidoc.module.bower.commands.install)

#### <a name="apidoc.element.bower.commands.install.install"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>install ()](#apidoc.element.bower.commands.install.install)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.install.line"></a>[function <span class="apidocSignatureSpan">bower.commands.install.</span>line (argv)](#apidoc.element.bower.commands.install.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.link"></a>[module bower.commands.link](#apidoc.module.bower.commands.link)

#### <a name="apidoc.element.bower.commands.link.link"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>link ()](#apidoc.element.bower.commands.link.link)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.link.line"></a>[function <span class="apidocSignatureSpan">bower.commands.link.</span>line (argv)](#apidoc.element.bower.commands.link.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.list"></a>[module bower.commands.list](#apidoc.module.bower.commands.list)

#### <a name="apidoc.element.bower.commands.list.list"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>list ()](#apidoc.element.bower.commands.list.list)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.list.line"></a>[function <span class="apidocSignatureSpan">bower.commands.list.</span>line (argv)](#apidoc.element.bower.commands.list.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.login"></a>[module bower.commands.login](#apidoc.module.bower.commands.login)

#### <a name="apidoc.element.bower.commands.login.login"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>login ()](#apidoc.element.bower.commands.login.login)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.login.line"></a>[function <span class="apidocSignatureSpan">bower.commands.login.</span>line (argv)](#apidoc.element.bower.commands.login.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.lookup"></a>[module bower.commands.lookup](#apidoc.module.bower.commands.lookup)

#### <a name="apidoc.element.bower.commands.lookup.lookup"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>lookup ()](#apidoc.element.bower.commands.lookup.lookup)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.lookup.line"></a>[function <span class="apidocSignatureSpan">bower.commands.lookup.</span>line (argv)](#apidoc.element.bower.commands.lookup.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.prune"></a>[module bower.commands.prune](#apidoc.module.bower.commands.prune)

#### <a name="apidoc.element.bower.commands.prune.prune"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>prune ()](#apidoc.element.bower.commands.prune.prune)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.prune.line"></a>[function <span class="apidocSignatureSpan">bower.commands.prune.</span>line (argv)](#apidoc.element.bower.commands.prune.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.register"></a>[module bower.commands.register](#apidoc.module.bower.commands.register)

#### <a name="apidoc.element.bower.commands.register.register"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>register ()](#apidoc.element.bower.commands.register.register)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.register.line"></a>[function <span class="apidocSignatureSpan">bower.commands.register.</span>line (argv)](#apidoc.element.bower.commands.register.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.search"></a>[module bower.commands.search](#apidoc.module.bower.commands.search)

#### <a name="apidoc.element.bower.commands.search.search"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>search ()](#apidoc.element.bower.commands.search.search)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.search.line"></a>[function <span class="apidocSignatureSpan">bower.commands.search.</span>line (argv)](#apidoc.element.bower.commands.search.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.uninstall"></a>[module bower.commands.uninstall](#apidoc.module.bower.commands.uninstall)

#### <a name="apidoc.element.bower.commands.uninstall.uninstall"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>uninstall ()](#apidoc.element.bower.commands.uninstall.uninstall)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.uninstall.line"></a>[function <span class="apidocSignatureSpan">bower.commands.uninstall.</span>line (argv)](#apidoc.element.bower.commands.uninstall.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.unregister"></a>[module bower.commands.unregister](#apidoc.module.bower.commands.unregister)

#### <a name="apidoc.element.bower.commands.unregister.unregister"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>unregister ()](#apidoc.element.bower.commands.unregister.unregister)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.unregister.line"></a>[function <span class="apidocSignatureSpan">bower.commands.unregister.</span>line (argv)](#apidoc.element.bower.commands.unregister.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.update"></a>[module bower.commands.update](#apidoc.module.bower.commands.update)

#### <a name="apidoc.element.bower.commands.update.update"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>update ()](#apidoc.element.bower.commands.update.update)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.update.line"></a>[function <span class="apidocSignatureSpan">bower.commands.update.</span>line (argv)](#apidoc.element.bower.commands.update.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.commands.version"></a>[module bower.commands.version](#apidoc.module.bower.commands.version)

#### <a name="apidoc.element.bower.commands.version.version"></a>[function <span class="apidocSignatureSpan">bower.commands.</span>version ()](#apidoc.element.bower.commands.version.version)
- description and source-code
```javascript
function runApi() {
    var command = require(id);
    var commandArgs = [].slice.call(arguments);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.commands.version.line"></a>[function <span class="apidocSignatureSpan">bower.commands.version.</span>line (argv)](#apidoc.element.bower.commands.version.line)
- description and source-code
```javascript
function runFromArgv(argv) {
    var commandArgs;
    var command = require(id);

    commandArgs = command.readOptions(argv);

    return withLogger(function (logger) {
        commandArgs.unshift(logger);

        return command.apply(undefined, commandArgs);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.bower.config"></a>[module bower.config](#apidoc.module.bower.config)

#### <a name="apidoc.element.bower.config.config"></a>[function <span class="apidocSignatureSpan">bower.</span>config (config)](#apidoc.element.bower.config.config)
- description and source-code
```javascript
function defaultConfig(config) {
    config = config || {};

    return readCachedConfig(config.cwd || process.cwd(), config);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.config.reset"></a>[function <span class="apidocSignatureSpan">bower.config.</span>reset ()](#apidoc.element.bower.config.reset)
- description and source-code
```javascript
function resetCache() {
    restoreConfig();
    current = undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.config.restore"></a>[function <span class="apidocSignatureSpan">bower.config.</span>restore ()](#apidoc.element.bower.config.restore)
- description and source-code
```javascript
function restoreConfig() {
    if (current) {
        current.restore();
    }
}
```
- example usage
```shell
...
    }

    return config;
}

function restoreConfig() {
    if (current) {
        current.restore();
    }
}

function resetCache() {
    restoreConfig();
    current = undefined;
}
...
```



# <a name="apidoc.module.bower.renderers"></a>[module bower.renderers](#apidoc.module.bower.renderers)

#### <a name="apidoc.element.bower.renderers.Json"></a>[function <span class="apidocSignatureSpan">bower.renderers.</span>Json ()](#apidoc.element.bower.renderers.Json)
- description and source-code
```javascript
function JsonRenderer() {
    this._nrLogs = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.bower.renderers.Standard"></a>[function <span class="apidocSignatureSpan">bower.renderers.</span>Standard (command, config)](#apidoc.element.bower.renderers.Standard)
- description and source-code
```javascript
function StandardRenderer(command, config) {
    this._sizes = {
        id: 13,    // Id max chars
        label: 20, // Label max chars
        sumup: 5   // Amount to sum when the label exceeds
    };
    this._colors = {
        warn: chalk.yellow,
        error: chalk.red,
        conflict: chalk.magenta,
        debug: chalk.gray,
        default: chalk.cyan
    };

    this._command = command;
    this._config = config || {};

    if (this.constructor._wideCommands.indexOf(command) === -1) {
        this._compact = true;
    } else {
        this._compact = process.stdout.columns < 120;
    }

    var exitOnPipeError = function (err) {
        if (err.code === 'EPIPE') {
            process.exit(0);
        }
    };

    // It happens when piping command to "head" util
    process.stdout.on('error', exitOnPipeError);
    process.stderr.on('error', exitOnPipeError);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
