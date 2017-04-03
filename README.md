# api documentation for  [newrelic (v1.38.2)](http://github.com/newrelic/node-newrelic)  [![npm package](https://img.shields.io/npm/v/npmdoc-newrelic.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-newrelic) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-newrelic.svg)](https://travis-ci.org/npmdoc/node-npmdoc-newrelic)
#### New Relic agent

[![NPM](https://nodei.co/npm/newrelic.png?downloads=true)](https://www.npmjs.com/package/newrelic)

[![apidoc](https://npmdoc.github.io/node-npmdoc-newrelic/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-newrelic_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-newrelic/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-newrelic/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-newrelic/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "New Relic Node.js agent team",
        "email": "nodejs@newrelic.com"
    },
    "bin": {
        "newrelic-naming-rules": "./bin/test-naming-rules.js"
    },
    "bugs": {
        "url": "https://github.com/newrelic/node-newrelic/issues"
    },
    "bundleDependencies": [
        "concat-stream",
        "https-proxy-agent",
        "json-stringify-safe",
        "readable-stream",
        "semver"
    ],
    "contributors": [
        {
            "name": "Saxon D'Aubin",
            "email": "saxon@newrelic.com",
            "url": "http://newrelic.com"
        },
        {
            "name": "Forrest L Norvell",
            "email": "forrest@newrelic.com",
            "url": "http://newrelic.com/"
        },
        {
            "name": "Jacob Groundwater",
            "email": "jacob@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Wraithan",
            "email": "wmcdonald@newrelic.com",
            "url": "Chris McDonald"
        },
        {
            "name": "Michael Hayes",
            "email": "mhayes@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Bryan Clement",
            "email": "bclement@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Jeff Olfert",
            "email": "jolfert@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Wilson Bilkovich",
            "email": "wbilkovich@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Jonathan Merrill",
            "email": "jmerrill@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Martin Kuba",
            "email": "mkuba@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Tim Krajcar",
            "email": "tkrajcar@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Eric Wang",
            "email": "ewang@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Natalie Wolfe",
            "email": "nwolfe@newrelic.com",
            "url": "https://newrelic.com"
        },
        {
            "name": "Seth Shober",
            "email": "sshober@newrelic.com",
            "url": "https://newrelic.com"
        }
    ],
    "dependencies": {
        "concat-stream": "^1.5.0",
        "https-proxy-agent": "^0.3.5",
        "json-stringify-safe": "^5.0.0",
        "readable-stream": "^1.1.13",
        "semver": "^5.3.0"
    },
    "description": "New Relic agent",
    "devDependencies": {
        "async": "^2.1.4",
        "eslint": "^2.9.0",
        "mocha": "*",
        "tap": "^9.0.3"
    },
    "directories": {
        "lib": "lib"
    },
    "dist": {
        "shasum": "c14cda98fc682be7fe770996c65beca88c4b6884",
        "tarball": "https://registry.npmjs.org/newrelic/-/newrelic-1.38.2.tgz"
    },
    "engines": {
        "node": ">=0.6.0"
    },
    "gitHead": "bbbeaa6dfd3cce9e1785b4567f89438e2b56afe9",
    "homepage": "http://github.com/newrelic/node-newrelic",
    "keywords": [
        "apm",
        "performance",
        "monitoring",
        "instrumentation",
        "debugging",
        "profiling"
    ],
    "licenses": [
        {
            "type": "proprietary",
            "url": "https://raw.github.com/newrelic/node-newrelic/master/LICENSE"
        }
    ],
    "maintainers": [
        {
            "name": "lykkin",
            "email": "bclement01@gmail.com"
        }
    ],
    "name": "newrelic",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/newrelic/node-newrelic.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "1.38.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module newrelic](#apidoc.module.newrelic)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>agent (config)](#apidoc.element.newrelic.agent)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>api (agent)](#apidoc.element.newrelic.api)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>aws_info (agent, callback)](#apidoc.element.newrelic.aws_info)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>config (config)](#apidoc.element.newrelic.config)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>reservoir (limit)](#apidoc.element.newrelic.reservoir)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>stub_api ()](#apidoc.element.newrelic.stub_api)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>system_info (agent, callback)](#apidoc.element.newrelic.system_info)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>timer ()](#apidoc.element.newrelic.timer)
1.  object <span class="apidocSignatureSpan">newrelic.</span>agent.prototype
1.  object <span class="apidocSignatureSpan">newrelic.</span>api.prototype
1.  object <span class="apidocSignatureSpan">newrelic.</span>config.prototype
1.  object <span class="apidocSignatureSpan">newrelic.</span>environment
1.  object <span class="apidocSignatureSpan">newrelic.</span>reservoir.prototype
1.  object <span class="apidocSignatureSpan">newrelic.</span>sampler
1.  object <span class="apidocSignatureSpan">newrelic.</span>shimmer
1.  object <span class="apidocSignatureSpan">newrelic.</span>stub_api.prototype
1.  object <span class="apidocSignatureSpan">newrelic.</span>timer.prototype
1.  object <span class="apidocSignatureSpan">newrelic.</span>uninstrumented

#### [module newrelic.agent](#apidoc.module.newrelic.agent)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>agent (config)](#apidoc.element.newrelic.agent.agent)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.</span>super_ ()](#apidoc.element.newrelic.agent.super_)

#### [module newrelic.agent.prototype](#apidoc.module.newrelic.agent.prototype)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_addEventFromTransaction (transaction)](#apidoc.element.newrelic.agent.prototype._addEventFromTransaction)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_addIntrinsicAttrsFromTransaction (transaction)](#apidoc.element.newrelic.agent.prototype._addIntrinsicAttrsFromTransaction)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_apdexTChange (apdexT)](#apidoc.element.newrelic.agent.prototype._apdexTChange)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_configChange ()](#apidoc.element.newrelic.agent.prototype._configChange)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_enabledChange ()](#apidoc.element.newrelic.agent.prototype._enabledChange)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_harvesterIntervalChange (interval, callback)](#apidoc.element.newrelic.agent.prototype._harvesterIntervalChange)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_processCustomEvents ()](#apidoc.element.newrelic.agent.prototype._processCustomEvents)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_processErrorEvents ()](#apidoc.element.newrelic.agent.prototype._processErrorEvents)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_restartHarvester (harvestSeconds)](#apidoc.element.newrelic.agent.prototype._restartHarvester)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_sendCustomEvents (callback)](#apidoc.element.newrelic.agent.prototype._sendCustomEvents)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_sendErrorEvents (callback)](#apidoc.element.newrelic.agent.prototype._sendErrorEvents)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_sendErrors (callback)](#apidoc.element.newrelic.agent.prototype._sendErrors)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_sendEvents (callback)](#apidoc.element.newrelic.agent.prototype._sendEvents)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_sendMetrics (callback)](#apidoc.element.newrelic.agent.prototype._sendMetrics)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_sendQueries (callback)](#apidoc.element.newrelic.agent.prototype._sendQueries)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_sendTrace (callback)](#apidoc.element.newrelic.agent.prototype._sendTrace)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_setupTracer ()](#apidoc.element.newrelic.agent.prototype._setupTracer)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_startHarvester (harvestSeconds)](#apidoc.element.newrelic.agent.prototype._startHarvester)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_stopHarvester ()](#apidoc.element.newrelic.agent.prototype._stopHarvester)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_transactionFinished (transaction)](#apidoc.element.newrelic.agent.prototype._transactionFinished)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>getTransaction ()](#apidoc.element.newrelic.agent.prototype.getTransaction)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>harvest (callback)](#apidoc.element.newrelic.agent.prototype.harvest)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>reconfigure (configuration)](#apidoc.element.newrelic.agent.prototype.reconfigure)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>reset ()](#apidoc.element.newrelic.agent.prototype.reset)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>setState (newState)](#apidoc.element.newrelic.agent.prototype.setState)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>start (callback)](#apidoc.element.newrelic.agent.prototype.start)
1.  [function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>stop (callback)](#apidoc.element.newrelic.agent.prototype.stop)

#### [module newrelic.api](#apidoc.module.newrelic.api)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>api (agent)](#apidoc.element.newrelic.api.api)

#### [module newrelic.api.prototype](#apidoc.module.newrelic.api.prototype)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>addCustomParameter (name, value)](#apidoc.element.newrelic.api.prototype.addCustomParameter)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>addCustomParameters (params)](#apidoc.element.newrelic.api.prototype.addCustomParameters)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>addIgnoringRule (pattern)](#apidoc.element.newrelic.api.prototype.addIgnoringRule)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>addNamingRule (pattern, name)](#apidoc.element.newrelic.api.prototype.addNamingRule)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>createBackgroundTransaction (name, group, handle)](#apidoc.element.newrelic.api.prototype.createBackgroundTransaction)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>createTracer (name, callback)](#apidoc.element.newrelic.api.prototype.createTracer)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>createWebTransaction (url, handle)](#apidoc.element.newrelic.api.prototype.createWebTransaction)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>endTransaction ()](#apidoc.element.newrelic.api.prototype.endTransaction)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>getBrowserTimingHeader ()](#apidoc.element.newrelic.api.prototype.getBrowserTimingHeader)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>incrementMetric (name, value)](#apidoc.element.newrelic.api.prototype.incrementMetric)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>noticeError (error, customParameters)](#apidoc.element.newrelic.api.prototype.noticeError)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>recordCustomEvent (eventType, attributes)](#apidoc.element.newrelic.api.prototype.recordCustomEvent)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>recordMetric (name, value)](#apidoc.element.newrelic.api.prototype.recordMetric)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>setControllerName (name, action)](#apidoc.element.newrelic.api.prototype.setControllerName)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>setIgnoreTransaction (ignored)](#apidoc.element.newrelic.api.prototype.setIgnoreTransaction)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>setTransactionName (name)](#apidoc.element.newrelic.api.prototype.setTransactionName)
1.  [function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>shutdown (options, cb)](#apidoc.element.newrelic.api.prototype.shutdown)

#### [module newrelic.aws_info](#apidoc.module.newrelic.aws_info)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>aws_info (agent, callback)](#apidoc.element.newrelic.aws_info.aws_info)
1.  [function <span class="apidocSignatureSpan">newrelic.aws_info.</span>_awsQuery (key, agent, callback)](#apidoc.element.newrelic.aws_info._awsQuery)
1.  [function <span class="apidocSignatureSpan">newrelic.aws_info.</span>clearCache ()](#apidoc.element.newrelic.aws_info.clearCache)

#### [module newrelic.config](#apidoc.module.newrelic.config)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>config (config)](#apidoc.element.newrelic.config.config)
1.  [function <span class="apidocSignatureSpan">newrelic.config.</span>getOrCreateInstance ()](#apidoc.element.newrelic.config.getOrCreateInstance)
1.  [function <span class="apidocSignatureSpan">newrelic.config.</span>initialize (config)](#apidoc.element.newrelic.config.initialize)
1.  [function <span class="apidocSignatureSpan">newrelic.config.</span>super_ ()](#apidoc.element.newrelic.config.super_)

#### [module newrelic.config.prototype](#apidoc.module.newrelic.config.prototype)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_alwaysUpdateIfChanged (json, key)](#apidoc.element.newrelic.config.prototype._alwaysUpdateIfChanged)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_applyHighSecurity ()](#apidoc.element.newrelic.config.prototype._applyHighSecurity)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_canonicalize ()](#apidoc.element.newrelic.config.prototype._canonicalize)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_emitIfSet (json, key)](#apidoc.element.newrelic.config.prototype._emitIfSet)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_fromEnvironment (metadata, data)](#apidoc.element.newrelic.config.prototype._fromEnvironment)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_fromPassed (external, internal, arbitrary)](#apidoc.element.newrelic.config.prototype._fromPassed)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_fromServer (params, key)](#apidoc.element.newrelic.config.prototype._fromServer)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_fromSpecial ()](#apidoc.element.newrelic.config.prototype._fromSpecial)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_updateIfChanged (json, key)](#apidoc.element.newrelic.config.prototype._updateIfChanged)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_updateNestedIfChanged (remote, local, remoteKey, localKey)](#apidoc.element.newrelic.config.prototype._updateNestedIfChanged)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_updateNestedIfChangedRaw ( remote, local, remoteKey, localKey)](#apidoc.element.newrelic.config.prototype._updateNestedIfChangedRaw)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>applications ()](#apidoc.element.newrelic.config.prototype.applications)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>clearDisplayHostCache ()](#apidoc.element.newrelic.config.prototype.clearDisplayHostCache)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>clearHostnameCache ()](#apidoc.element.newrelic.config.prototype.clearHostnameCache)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>getDisplayHost ()](#apidoc.element.newrelic.config.prototype.getDisplayHost)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>getHostnameSafe ()](#apidoc.element.newrelic.config.prototype.getHostnameSafe)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>getIPAddresses ()](#apidoc.element.newrelic.config.prototype.getIPAddresses)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>logDisabled (json, key)](#apidoc.element.newrelic.config.prototype.logDisabled)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>logUnknown (json, key)](#apidoc.element.newrelic.config.prototype.logUnknown)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>logUnsupported (json, key)](#apidoc.element.newrelic.config.prototype.logUnsupported)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>measureInternal (suffix, duration)](#apidoc.element.newrelic.config.prototype.measureInternal)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>onConnect (json, recursion)](#apidoc.element.newrelic.config.prototype.onConnect)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>publicSettings ()](#apidoc.element.newrelic.config.prototype.publicSettings)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>setLogger (bootstrapped)](#apidoc.element.newrelic.config.prototype.setLogger)
1.  [function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>validateFlags ()](#apidoc.element.newrelic.config.prototype.validateFlags)

#### [module newrelic.environment](#apidoc.module.newrelic.environment)
1.  [function <span class="apidocSignatureSpan">newrelic.environment.</span>clearDispatcher ()](#apidoc.element.newrelic.environment.clearDispatcher)
1.  [function <span class="apidocSignatureSpan">newrelic.environment.</span>clearFramework ()](#apidoc.element.newrelic.environment.clearFramework)
1.  [function <span class="apidocSignatureSpan">newrelic.environment.</span>get (name)](#apidoc.element.newrelic.environment.get)
1.  [function <span class="apidocSignatureSpan">newrelic.environment.</span>listPackages (root, packages)](#apidoc.element.newrelic.environment.listPackages)
1.  [function <span class="apidocSignatureSpan">newrelic.environment.</span>refresh ()](#apidoc.element.newrelic.environment.refresh)
1.  [function <span class="apidocSignatureSpan">newrelic.environment.</span>setDispatcher (dispatcher)](#apidoc.element.newrelic.environment.setDispatcher)
1.  [function <span class="apidocSignatureSpan">newrelic.environment.</span>setFramework (framework)](#apidoc.element.newrelic.environment.setFramework)
1.  [function <span class="apidocSignatureSpan">newrelic.environment.</span>toJSON ()](#apidoc.element.newrelic.environment.toJSON)

#### [module newrelic.reservoir](#apidoc.module.newrelic.reservoir)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>reservoir (limit)](#apidoc.element.newrelic.reservoir.reservoir)

#### [module newrelic.reservoir.prototype](#apidoc.module.newrelic.reservoir.prototype)
1.  [function <span class="apidocSignatureSpan">newrelic.reservoir.prototype.</span>add (item)](#apidoc.element.newrelic.reservoir.prototype.add)
1.  [function <span class="apidocSignatureSpan">newrelic.reservoir.prototype.</span>merge (items)](#apidoc.element.newrelic.reservoir.prototype.merge)
1.  [function <span class="apidocSignatureSpan">newrelic.reservoir.prototype.</span>overflow ()](#apidoc.element.newrelic.reservoir.prototype.overflow)
1.  [function <span class="apidocSignatureSpan">newrelic.reservoir.prototype.</span>setLimit (newLimit)](#apidoc.element.newrelic.reservoir.prototype.setLimit)
1.  [function <span class="apidocSignatureSpan">newrelic.reservoir.prototype.</span>toArray ()](#apidoc.element.newrelic.reservoir.prototype.toArray)

#### [module newrelic.sampler](#apidoc.module.newrelic.sampler)
1.  [function <span class="apidocSignatureSpan">newrelic.sampler.</span>checkEvents (agent)](#apidoc.element.newrelic.sampler.checkEvents)
1.  [function <span class="apidocSignatureSpan">newrelic.sampler.</span>sampleCpu (agent)](#apidoc.element.newrelic.sampler.sampleCpu)
1.  [function <span class="apidocSignatureSpan">newrelic.sampler.</span>sampleGc (agent, nativeMetrics)](#apidoc.element.newrelic.sampler.sampleGc)
1.  [function <span class="apidocSignatureSpan">newrelic.sampler.</span>sampleLoop (agent, nativeMetrics)](#apidoc.element.newrelic.sampler.sampleLoop)
1.  [function <span class="apidocSignatureSpan">newrelic.sampler.</span>sampleMemory (agent)](#apidoc.element.newrelic.sampler.sampleMemory)
1.  [function <span class="apidocSignatureSpan">newrelic.sampler.</span>start (agent)](#apidoc.element.newrelic.sampler.start)
1.  [function <span class="apidocSignatureSpan">newrelic.sampler.</span>stop ()](#apidoc.element.newrelic.sampler.stop)
1.  object <span class="apidocSignatureSpan">newrelic.sampler.</span>nativeMetrics
1.  string <span class="apidocSignatureSpan">newrelic.sampler.</span>state

#### [module newrelic.shimmer](#apidoc.module.newrelic.shimmer)
1.  boolean <span class="apidocSignatureSpan">newrelic.shimmer.</span>debug
1.  [function <span class="apidocSignatureSpan">newrelic.shimmer.</span>bootstrapInstrumentation (agent)](#apidoc.element.newrelic.shimmer.bootstrapInstrumentation)
1.  [function <span class="apidocSignatureSpan">newrelic.shimmer.</span>isWrapped (fn)](#apidoc.element.newrelic.shimmer.isWrapped)
1.  [function <span class="apidocSignatureSpan">newrelic.shimmer.</span>patchModule (agent)](#apidoc.element.newrelic.shimmer.patchModule)
1.  [function <span class="apidocSignatureSpan">newrelic.shimmer.</span>reinstrument (agent, modulePath)](#apidoc.element.newrelic.shimmer.reinstrument)
1.  [function <span class="apidocSignatureSpan">newrelic.shimmer.</span>unpatchModule ()](#apidoc.element.newrelic.shimmer.unpatchModule)
1.  [function <span class="apidocSignatureSpan">newrelic.shimmer.</span>unwrapAll ()](#apidoc.element.newrelic.shimmer.unwrapAll)
1.  [function <span class="apidocSignatureSpan">newrelic.shimmer.</span>unwrapMethod (nodule, noduleName, method)](#apidoc.element.newrelic.shimmer.unwrapMethod)
1.  [function <span class="apidocSignatureSpan">newrelic.shimmer.</span>wrapDeprecated (nodule, noduleName, property, options)](#apidoc.element.newrelic.shimmer.wrapDeprecated)
1.  [function <span class="apidocSignatureSpan">newrelic.shimmer.</span>wrapMethod (nodule, noduleName, methods, wrapper)](#apidoc.element.newrelic.shimmer.wrapMethod)

#### [module newrelic.stub_api](#apidoc.module.newrelic.stub_api)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>stub_api ()](#apidoc.element.newrelic.stub_api.stub_api)

#### [module newrelic.stub_api.prototype](#apidoc.module.newrelic.stub_api.prototype)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>addCustomParameter ()](#apidoc.element.newrelic.stub_api.prototype.addCustomParameter)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>addCustomParameters ()](#apidoc.element.newrelic.stub_api.prototype.addCustomParameters)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>addIgnoringRule ()](#apidoc.element.newrelic.stub_api.prototype.addIgnoringRule)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>addNamingRule ()](#apidoc.element.newrelic.stub_api.prototype.addNamingRule)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>createBackgroundTransaction (name, group, callback)](#apidoc.element.newrelic.stub_api.prototype.createBackgroundTransaction)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>createTracer (name, callback)](#apidoc.element.newrelic.stub_api.prototype.createTracer)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>createWebTransaction (url, callback)](#apidoc.element.newrelic.stub_api.prototype.createWebTransaction)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>endTransaction ()](#apidoc.element.newrelic.stub_api.prototype.endTransaction)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>getBrowserTimingHeader ()](#apidoc.element.newrelic.stub_api.prototype.getBrowserTimingHeader)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>incrementMetric ()](#apidoc.element.newrelic.stub_api.prototype.incrementMetric)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>noticeError ()](#apidoc.element.newrelic.stub_api.prototype.noticeError)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>recordCustomEvent ()](#apidoc.element.newrelic.stub_api.prototype.recordCustomEvent)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>recordMetric ()](#apidoc.element.newrelic.stub_api.prototype.recordMetric)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>setControllerName ()](#apidoc.element.newrelic.stub_api.prototype.setControllerName)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>setIgnoreTransaction ()](#apidoc.element.newrelic.stub_api.prototype.setIgnoreTransaction)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>setTransactionName ()](#apidoc.element.newrelic.stub_api.prototype.setTransactionName)
1.  [function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>shutdown (options, cb)](#apidoc.element.newrelic.stub_api.prototype.shutdown)

#### [module newrelic.system_info](#apidoc.module.newrelic.system_info)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>system_info (agent, callback)](#apidoc.element.newrelic.system_info.system_info)
1.  [function <span class="apidocSignatureSpan">newrelic.system_info.</span>_getDockerContainerId (agent, callback)](#apidoc.element.newrelic.system_info._getDockerContainerId)
1.  [function <span class="apidocSignatureSpan">newrelic.system_info.</span>_getMemoryStats (callback)](#apidoc.element.newrelic.system_info._getMemoryStats)
1.  [function <span class="apidocSignatureSpan">newrelic.system_info.</span>_getProcessorStats (callback)](#apidoc.element.newrelic.system_info._getProcessorStats)

#### [module newrelic.timer](#apidoc.module.newrelic.timer)
1.  [function <span class="apidocSignatureSpan">newrelic.</span>timer ()](#apidoc.element.newrelic.timer.timer)

#### [module newrelic.timer.prototype](#apidoc.module.newrelic.timer.prototype)
1.  [function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>begin ()](#apidoc.element.newrelic.timer.prototype.begin)
1.  [function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>end ()](#apidoc.element.newrelic.timer.prototype.end)
1.  [function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>endsAfter (other)](#apidoc.element.newrelic.timer.prototype.endsAfter)
1.  [function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>getDurationInMillis ()](#apidoc.element.newrelic.timer.prototype.getDurationInMillis)
1.  [function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>hasEnd ()](#apidoc.element.newrelic.timer.prototype.hasEnd)
1.  [function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>isActive ()](#apidoc.element.newrelic.timer.prototype.isActive)
1.  [function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>isRunning ()](#apidoc.element.newrelic.timer.prototype.isRunning)
1.  [function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>overwriteDurationInMillis (duration)](#apidoc.element.newrelic.timer.prototype.overwriteDurationInMillis)
1.  [function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>setDurationInMillis (duration, start)](#apidoc.element.newrelic.timer.prototype.setDurationInMillis)
1.  [function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>softEnd ()](#apidoc.element.newrelic.timer.prototype.softEnd)
1.  [function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>startedRelativeTo (other)](#apidoc.element.newrelic.timer.prototype.startedRelativeTo)
1.  [function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>toRange ()](#apidoc.element.newrelic.timer.prototype.toRange)
1.  [function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>touch ()](#apidoc.element.newrelic.timer.prototype.touch)

#### [module newrelic.uninstrumented](#apidoc.module.newrelic.uninstrumented)
1.  [function <span class="apidocSignatureSpan">newrelic.uninstrumented.</span>check ()](#apidoc.element.newrelic.uninstrumented.check)
1.  [function <span class="apidocSignatureSpan">newrelic.uninstrumented.</span>createMetrics (metrics)](#apidoc.element.newrelic.uninstrumented.createMetrics)



# <a name="apidoc.module.newrelic"></a>[module newrelic](#apidoc.module.newrelic)

#### <a name="apidoc.element.newrelic.agent"></a>[function <span class="apidocSignatureSpan">newrelic.</span>agent (config)](#apidoc.element.newrelic.agent)
- description and source-code
```javascript
function Agent(config) {
  EventEmitter.call(this)

  if (!config) throw new Error("Agent must be created with a configuration!")

  // The agent base attributes which last throughout its lifetime.
  this._state = 'stopped'
  this.config = config
  this.environment = require('./environment')
  this.version = this.config.version
  this.collector = new CollectorAPI(this)

  // Reset the agent to add all the sub-objects it needs. These object are the
  // ones that get re-created if the agent is told to restart from the collector.
  this.events = null
  this.customEvents = null
  this.errors = null
  this.mapper = null
  this.metricNameNormalizer = null
  this.metrics = null
  this.transactionNameNormalizer = null
  this.urlNormalizer = null
  this.txSegmentNormalizer = null
  this.userNormalizer = null
  this.reset()

  // Transaction tracing.
  this.tracer = this._setupTracer()
  this.traces = new TraceAggregator(this.config)

  // Query tracing.
  this.queries = new QueryTracer(this.config)

  // Set up all the configuration events the agent needs to listen for.
  var self = this
  this.config.on('apdex_t', this._apdexTChange.bind(this))
  this.config.on('data_report_period', this._harvesterIntervalChange.bind(this))
  this.config.on('agent_enabled', this._enabledChange.bind(this))
  this.config.on('change', this._configChange.bind(this))
  this.config.on('metric_name_rules', function updateMetricNameNormalizer() {
    self.metricNameNormalizer.load.apply(self.metricNameNormalizer, arguments)
  })
  this.config.on('transaction_name_rules', function updateTransactionNameNormalizer() {
    self.transactionNameNormalizer.load.apply(self.transactionNameNormalizer, arguments)
  })
  this.config.on('url_rules', function updateUrlNormalizer() {
    self.urlNormalizer.load.apply(self.urlNormalizer, arguments)
  })
  this.config.on('transaction_segment_terms', function updateSegmentNormalizer() {
    self.txSegmentNormalizer.load.apply(self.txSegmentNormalizer, arguments)
  })

  // Entity tracking metrics.
  this.totalActiveSegments = 0
  this.segmentsCreatedInHarvest = 0
  this.segmentsClearedInHarvest = 0
  this.activeTransactions = 0

  // Hidden class optimizations.
  this.harvesterHandle = null

  // Finally, add listeners for the agent's own events.
  this.on('transactionFinished', this._transactionFinished.bind(this))
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.api"></a>[function <span class="apidocSignatureSpan">newrelic.</span>api (agent)](#apidoc.element.newrelic.api)
- description and source-code
```javascript
function API(agent) {
  this.agent = agent
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.aws_info"></a>[function <span class="apidocSignatureSpan">newrelic.</span>aws_info (agent, callback)](#apidoc.element.newrelic.aws_info)
- description and source-code
```javascript
function fetchAWSInfo(agent, callback) {
  if (!agent.config.utilization || !agent.config.utilization.detect_aws) {
    return callback(null)
  }

  if (resultDict) {
    return callback(resultDict)
  }

  var awsQuery = module.exports._awsQuery

  awsQuery('instance-type', agent, function getInstanceType(type) {
    if (!type) return callback(null)
    awsQuery('instance-id', agent, function getInstanceId(id) {
      if (!id) return callback(null)
      awsQuery('placement/availability-zone', agent, function getZone(zone) {
        if (!zone) return callback(null)
        resultDict = {
          type: type,
          id: id,
          zone: zone
        }
        return callback(resultDict)
      })
    })
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.config"></a>[function <span class="apidocSignatureSpan">newrelic.</span>config (config)](#apidoc.element.newrelic.config)
- description and source-code
```javascript
function Config(config) {
  EventEmitter.call(this)

  // 1. start by cloning the defaults
  try {
    var basis = JSON.parse(stringifySync(DEFAULT_CONFIG))
    Object.keys(basis).forEach(function cb_forEach(key) {
      this[key] = basis[key]
    }, this)
  } catch (err) {
    logger.warn('Unable to clone the default config, %s: %s', DEFAULT_CONFIG_PATH, err)
  }

  if (config &&
      (process.env[ENV_MAPPING.ssl] === 'false' || config.ssl === false) &&
      process.env[ENV_MAPPING.port] === undefined && config.port === undefined ) {
    config.port = 80
  }

  // 2. initialize undocumented, internal-only default values

  // feature flags are mostly private settings for gating unreleased features
  // flags are set in the feature_flags.js file
  this.feature_flag = feature_flag.prerelease

  // set by environment
  this.newrelic_home = null
  // set by configuration file loader
  this.config_file_path = null
  // set by collector on handshake
  this.run_id = null
  this.application_id = null
  this.web_transactions_apdex = {}
  this.cross_process_id = null
  this.encoding_key = null
  this.obfuscatedId = null
  this.trusted_account_ids = null

  // how frequently harvester runs
  this.data_report_period = 60

  // this value is arbitrary
  this.max_trace_segments = 900

  // feature level of this account
  this.product_level = 0
  // product-level related
  this.collect_traces = true
  this.collect_errors = true

  // override options for utilization stats
  this.utilization.logical_processors = null
  this.utilization.total_ram_mib = null
  this.utilization.billing_hostname = null

  this.browser_monitoring.loader = 'rum'
  this.browser_monitoring.loader_version = ''

  // Settings to play nice with DLPs (see NODE-1044).
  this.compressed_content_encoding = "deflate"  // Deflate or gzip
  this.simple_compression = false               // Disables subcomponent compression
  this.put_for_data_send = false                // Changes http verb for harvest


  // 3. override defaults with values from the loaded / passed configuration
  this._fromPassed(config)

  // 3.5. special values (only Azure environment APP_POOL_ID for now)
  this._fromSpecial()

  // 4. override config with environment variables
  this._fromEnvironment()

  // 5. clean up anything that requires postprocessing
  this._canonicalize()

  // 6. put the version in the config
  this.version = require('../package.json').version

  // 7. apply high security overrides
  if (this.high_security === true) {
    this._applyHighSecurity()
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.reservoir"></a>[function <span class="apidocSignatureSpan">newrelic.</span>reservoir (limit)](#apidoc.element.newrelic.reservoir)
- description and source-code
```javascript
function Reservoir(limit) {
  this.limit = limit || 10
  this.seen = 0
  this._data = []
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.stub_api"></a>[function <span class="apidocSignatureSpan">newrelic.</span>stub_api ()](#apidoc.element.newrelic.stub_api)
- description and source-code
```javascript
function Stub() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.system_info"></a>[function <span class="apidocSignatureSpan">newrelic.</span>system_info (agent, callback)](#apidoc.element.newrelic.system_info)
- description and source-code
```javascript
function fetchSystemInfo(agent, callback) {
  var config = agent.config
  var systemInfo = {
    processorArch: os.arch()
  }

  var utilizationConfig = {}
  if (config.utilization) {
    var configProcessors = config.utilization.logical_processors
    var configRam = config.utilization.total_ram_mib
    var configHostname = config.utilization.billing_hostname

    if (configProcessors) {
      var parsedConfigProcessors = parseFloat(configProcessors, 10)
      if (!isNaN(parsedConfigProcessors) && isInteger(parsedConfigProcessors)) {
        utilizationConfig.logical_processors = parsedConfigProcessors
      } else {
        logger.info(
          '%s supplied in config for utilization.logical_processors, expected a number',
          configProcessors
        )
      }
    }

    if (configRam) {
      var parsedConfigRam = parseFloat(configRam, 10)
      if (!isNaN(parsedConfigRam) && isInteger(parsedConfigRam)) {
        utilizationConfig.total_ram_mib = parsedConfigRam
      } else {
        logger.info(
          '%s supplied in config for utilization.total_ram_mib, expected a number',
          configRam
        )
      }
    }

    if (configHostname) {
      if (typeof configHostname === 'string') {
        utilizationConfig.hostname = configHostname
      } else {
        logger.info(
          '%s supplied in config for utilization.Hostname, expected a string',
          configHostname
        )
      }
    }

    if (Object.keys(utilizationConfig).length > 0) {
      systemInfo.config = utilizationConfig
    }
  }

  var tasksDone = 0
  var numTasks = 5
  function finishedResponse() {
    if (++tasksDone === numTasks) return callback(systemInfo)
  }

  module.exports._getProcessorStats(function getProcessCB(processorStats) {
    systemInfo.packages = processorStats.packages
    systemInfo.logicalProcessors = processorStats.logical
    systemInfo.cores = processorStats.cores
    finishedResponse()
  })
  module.exports._getMemoryStats(function getMemCB(memory) {
    systemInfo.memory = memory
    finishedResponse()
  })
  getKernelVersion(function getVersionCB(kernelVersion) {
    systemInfo.kernelVersion = kernelVersion
    finishedResponse()
  })
  module.exports._getDockerContainerId(agent, function getContainerId(containerId) {
    if (containerId) {
      systemInfo.docker = {
        id: containerId
      }
    }
    finishedResponse()
  })
  fetchAWSInfo(agent, function getAWSInfo(aws) {
    systemInfo.aws = aws
    finishedResponse()
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.timer"></a>[function <span class="apidocSignatureSpan">newrelic.</span>timer ()](#apidoc.element.newrelic.timer)
- description and source-code
```javascript
function Timer() {
  this.state = PENDING
  this.touched = false
  this.duration = null
  this.hrDuration = null
  this.hrstart = null
  this.durationInMillis = null
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.newrelic.agent"></a>[module newrelic.agent](#apidoc.module.newrelic.agent)

#### <a name="apidoc.element.newrelic.agent.agent"></a>[function <span class="apidocSignatureSpan">newrelic.</span>agent (config)](#apidoc.element.newrelic.agent.agent)
- description and source-code
```javascript
function Agent(config) {
  EventEmitter.call(this)

  if (!config) throw new Error("Agent must be created with a configuration!")

  // The agent base attributes which last throughout its lifetime.
  this._state = 'stopped'
  this.config = config
  this.environment = require('./environment')
  this.version = this.config.version
  this.collector = new CollectorAPI(this)

  // Reset the agent to add all the sub-objects it needs. These object are the
  // ones that get re-created if the agent is told to restart from the collector.
  this.events = null
  this.customEvents = null
  this.errors = null
  this.mapper = null
  this.metricNameNormalizer = null
  this.metrics = null
  this.transactionNameNormalizer = null
  this.urlNormalizer = null
  this.txSegmentNormalizer = null
  this.userNormalizer = null
  this.reset()

  // Transaction tracing.
  this.tracer = this._setupTracer()
  this.traces = new TraceAggregator(this.config)

  // Query tracing.
  this.queries = new QueryTracer(this.config)

  // Set up all the configuration events the agent needs to listen for.
  var self = this
  this.config.on('apdex_t', this._apdexTChange.bind(this))
  this.config.on('data_report_period', this._harvesterIntervalChange.bind(this))
  this.config.on('agent_enabled', this._enabledChange.bind(this))
  this.config.on('change', this._configChange.bind(this))
  this.config.on('metric_name_rules', function updateMetricNameNormalizer() {
    self.metricNameNormalizer.load.apply(self.metricNameNormalizer, arguments)
  })
  this.config.on('transaction_name_rules', function updateTransactionNameNormalizer() {
    self.transactionNameNormalizer.load.apply(self.transactionNameNormalizer, arguments)
  })
  this.config.on('url_rules', function updateUrlNormalizer() {
    self.urlNormalizer.load.apply(self.urlNormalizer, arguments)
  })
  this.config.on('transaction_segment_terms', function updateSegmentNormalizer() {
    self.txSegmentNormalizer.load.apply(self.txSegmentNormalizer, arguments)
  })

  // Entity tracking metrics.
  this.totalActiveSegments = 0
  this.segmentsCreatedInHarvest = 0
  this.segmentsClearedInHarvest = 0
  this.activeTransactions = 0

  // Hidden class optimizations.
  this.harvesterHandle = null

  // Finally, add listeners for the agent's own events.
  this.on('transactionFinished', this._transactionFinished.bind(this))
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.agent.super_"></a>[function <span class="apidocSignatureSpan">newrelic.agent.</span>super_ ()](#apidoc.element.newrelic.agent.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.newrelic.agent.prototype"></a>[module newrelic.agent.prototype](#apidoc.module.newrelic.agent.prototype)

#### <a name="apidoc.element.newrelic.agent.prototype._addEventFromTransaction"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_addEventFromTransaction (transaction)](#apidoc.element.newrelic.agent.prototype._addEventFromTransaction)
- description and source-code
```javascript
function _addEventFromTransaction(transaction) {
  if (!this.config.transaction_events.enabled) return

  var intrinsicAttributes = this._addIntrinsicAttrsFromTransaction(transaction)
  var userAttributes = transaction.trace.custom
  var agentAttributes = transaction.trace.parameters

  var event = [
    intrinsicAttributes,
    userAttributes,
    agentAttributes
  ]

  this.events.add(event)
}
```
- example usage
```shell
...
  this.metrics.merge(transaction.metrics)
  this.errors.onTransactionFinished(transaction, this.metrics)
  this.traces.add(transaction)

  var trace = transaction.trace
  trace.intrinsics = transaction.getIntrinsicAttributes()

  this._addEventFromTransaction(transaction)
} else if (transaction.forceIgnore === true) {
  logger.debug("Explicitly ignoring %s.", transaction.name)
} else {
  logger.debug("Ignoring %s.", transaction.name)
}

this.activeTransactions--
...
```

#### <a name="apidoc.element.newrelic.agent.prototype._addIntrinsicAttrsFromTransaction"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_addIntrinsicAttrsFromTransaction (transaction)](#apidoc.element.newrelic.agent.prototype._addIntrinsicAttrsFromTransaction)
- description and source-code
```javascript
function _addIntrinsicAttrsFromTransaction(transaction) {
  var intrinsicAttributes = {
    webDuration: transaction.timer.duration / 1000,
    timestamp: transaction.timer.start,
    name: transaction.name,
    duration: transaction.timer.duration / 1000,
    type: 'Transaction',
    error: transaction.hasErrors()
  }

  var metric = transaction.metrics.getMetric(NAMES.QUEUETIME)
  if (metric) {
    intrinsicAttributes.queueDuration = metric.total
  }

  metric = transaction.metrics.getMetric(NAMES.EXTERNAL.ALL)
  if (metric) {
    intrinsicAttributes.externalDuration = metric.total
    intrinsicAttributes.externalCallCount = metric.callCount
  }

  metric = transaction.metrics.getMetric(NAMES.DB.ALL)
  if (metric) {
    intrinsicAttributes.databaseDuration = metric.total
    intrinsicAttributes.databaseCallCount = metric.callCount
  }

  // FLAG: cat
  if (this.config.feature_flag.cat) {
    if (!transaction.invalidIncomingExternalTransaction &&
         (
           transaction.referringTransactionGuid ||
           transaction.includesOutboundRequests()
         )
       ) {
      intrinsicAttributes['nr.guid'] = transaction.id
      intrinsicAttributes['nr.tripId'] = transaction.tripId || transaction.id
      intrinsicAttributes['nr.pathHash'] = hashes.calculatePathHash(
        this.config.applications()[0],
        transaction.name || transaction.nameState.getName(),
        transaction.referringPathHash
      )
      if (transaction.referringPathHash) {
        intrinsicAttributes['nr.referringPathHash'] = transaction.referringPathHash
      }
      if (transaction.referringTransactionGuid) {
        var refId = transaction.referringTransactionGuid
        intrinsicAttributes['nr.referringTransactionGuid'] = refId
      }
      var alternatePathHashes = transaction.alternatePathHashes()
      if (alternatePathHashes) {
        intrinsicAttributes['nr.alternatePathHashes'] = alternatePathHashes
      }
      if (transaction.webSegment) {
        var apdex = (this.config.web_transactions_apdex[transaction.name] ||
                     this.config.apdex_t)
        var duration = transaction.webSegment.getDurationInMillis() / 1000
        intrinsicAttributes['nr.apdexPerfZone'] = calculateApdexZone(duration, apdex)
      }
    }
  }

  if (transaction.syntheticsData) {
    intrinsicAttributes["nr.syntheticsResourceId"] = transaction.syntheticsData.resourceId
    intrinsicAttributes["nr.syntheticsJobId"] = transaction.syntheticsData.jobId
    intrinsicAttributes["nr.syntheticsMonitorId"] = transaction.syntheticsData.monitorId
  }

  return intrinsicAttributes
}
```
- example usage
```shell
...
}

Agent.prototype._addEventFromTransaction = _addEventFromTransaction

function _addEventFromTransaction(transaction) {
if (!this.config.transaction_events.enabled) return

var intrinsicAttributes = this._addIntrinsicAttrsFromTransaction(transaction)
var userAttributes = transaction.trace.custom
var agentAttributes = transaction.trace.parameters

var event = [
  intrinsicAttributes,
  userAttributes,
  agentAttributes
...
```

#### <a name="apidoc.element.newrelic.agent.prototype._apdexTChange"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_apdexTChange (apdexT)](#apidoc.element.newrelic.agent.prototype._apdexTChange)
- description and source-code
```javascript
function _apdexTChange(apdexT) {
  logger.debug("Apdex tolerating value changed to %s.", apdexT)
  this.metrics.apdexT = apdexT
  if (this.config.debug.supportability) {
    this.config.debug.supportability.apdexT = apdexT
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.agent.prototype._configChange"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_configChange ()](#apidoc.element.newrelic.agent.prototype._configChange)
- description and source-code
```javascript
function _configChange() {
  this.collector.reportSettings()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.agent.prototype._enabledChange"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_enabledChange ()](#apidoc.element.newrelic.agent.prototype._enabledChange)
- description and source-code
```javascript
function _enabledChange() {
  if (this.config.agent_enabled === false) {
    logger.warn('agent_enabled has been changed to false, stopping the agent.')
    this.stop(function nop() {})
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.agent.prototype._harvesterIntervalChange"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_harvesterIntervalChange (interval, callback)](#apidoc.element.newrelic.agent.prototype._harvesterIntervalChange)
- description and source-code
```javascript
function _harvesterIntervalChange(interval, callback) {
  var agent = this

  // only change the setup if the harvester is currently running
  if (this.harvesterHandle) {
    // force a harvest now, to be safe
    this.harvest(function cb_harvest(error) {
      agent._restartHarvester(interval)
      if (callback) callback(error)
    })
  } else if (callback) {
    process.nextTick(callback)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.agent.prototype._processCustomEvents"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_processCustomEvents ()](#apidoc.element.newrelic.agent.prototype._processCustomEvents)
- description and source-code
```javascript
function _processCustomEvents() {
  this.customEventsPool = this.customEvents.toArray()

  // Create the metrics so they are at least set to 0
  var dropped = this.metrics.getOrCreateMetric(NAMES.CUSTOM_EVENTS.DROPPED)
  var seen = this.metrics.getOrCreateMetric(NAMES.CUSTOM_EVENTS.SEEN)
  var sent = this.metrics.getOrCreateMetric(NAMES.CUSTOM_EVENTS.SENT)

  // Bail out if there are no events
  if (this.customEventsPool.length === 0) {
    return
  }

  if (this.config.custom_insights_events.enabled) {
    // Record their values
    var diff = this.customEvents.overflow()
    dropped.incrementCallCount(diff)
    seen.incrementCallCount(this.customEvents.seen)
    sent.incrementCallCount(this.customEvents.seen - diff)

    // Log any warnings about dropping events
    if (diff) {
      logger.warn('Dropped %s custom events out of %s.', diff, this.customEvents.seen)
    }

    // Create a new reservoir now (instead of at send time) so metrics match
    // what we actually send.
    this.customEvents = new Reservoir(
      this.config.custom_insights_events.max_samples_stored
    )
  } else if (this.customEventsPool.length > 0) {
    // We have events and custom events are disabled. Clear everything out so we
    // don't hold onto memory that we shouldn't. Only time this could happen is
    // if the server sent down settings disabling custom events in the middle of
    // a harvest cycle.
    this.customEventsPool = []
    this.customEvents = new Reservoir(
      this.config.custom_insights_events.max_samples_stored
    )
  }
}
```
- example usage
```shell
...
if (this.config.debug.supportability) {
  this.metrics.merge(this.config.debug.supportability)
}

// Send uninstrumented supportability metrics every harvest cycle
uninstrumented.createMetrics(this.metrics)

this._processCustomEvents()
this._processErrorEvents()

// wait to check until all the standard stuff has been added
if (this.metrics.toJSON().length < 1) {
  logger.debug("No metrics to send.")
  return process.nextTick(callback)
}
...
```

#### <a name="apidoc.element.newrelic.agent.prototype._processErrorEvents"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_processErrorEvents ()](#apidoc.element.newrelic.agent.prototype._processErrorEvents)
- description and source-code
```javascript
function _processErrorEvents() {
  var events = this.errors.getEvents()

  this._lastErrorEvents = [
    this.errors.getEventsLimit(),
    this.errors.getEventsSeen(),
    events
  ]

  // Create the metrics so they are at least set to 0
  var seen = this.metrics.getOrCreateMetric(NAMES.TRANSACTION_ERROR.SEEN)
  var sent = this.metrics.getOrCreateMetric(NAMES.TRANSACTION_ERROR.SENT)

  // Bail out if there are no events
  if (events.length === 0) {
    return
  }

  if (this.config.error_collector.capture_events) {
    // Record their values
    var diff = this.errors.events.overflow()
    seen.incrementCallCount(this.errors.events.seen)
    sent.incrementCallCount(this.errors.events.seen - diff)

    // Log any warnings about dropping events
    if (diff) {
      logger.warn('Dropped %s error events out of %s.', diff, this.errors.events.seen)
    }

    // clear the reservoir now (instead of at send time) so metrics match
    // what we actually send.
    this.errors.clearEvents()
  } else if (events.length > 0) {
    // We have events and error events are disabled. Clear everything out so we
    // don't hold onto memory that we shouldn't. Only time this could happen is
    // if the server sent down settings disabling error events in the middle of
    // a harvest cycle.
    this._lastErrorEvents = []
    this.errors.clearEvents()
  }
}
```
- example usage
```shell
...
  this.metrics.merge(this.config.debug.supportability)
}

// Send uninstrumented supportability metrics every harvest cycle
uninstrumented.createMetrics(this.metrics)

this._processCustomEvents()
this._processErrorEvents()

// wait to check until all the standard stuff has been added
if (this.metrics.toJSON().length < 1) {
  logger.debug("No metrics to send.")
  return process.nextTick(callback)
}
...
```

#### <a name="apidoc.element.newrelic.agent.prototype._restartHarvester"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_restartHarvester (harvestSeconds)](#apidoc.element.newrelic.agent.prototype._restartHarvester)
- description and source-code
```javascript
function _restartHarvester(harvestSeconds) {
  this._stopHarvester()
  this._startHarvester(harvestSeconds)
}
```
- example usage
```shell
...
function _harvesterIntervalChange(interval, callback) {
  var agent = this

  // only change the setup if the harvester is currently running
  if (this.harvesterHandle) {
    // force a harvest now, to be safe
    this.harvest(function cb_harvest(error) {
      agent._restartHarvester(interval)
      if (callback) callback(error)
    })
  } else if (callback) {
    process.nextTick(callback)
  }
}
...
```

#### <a name="apidoc.element.newrelic.agent.prototype._sendCustomEvents"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_sendCustomEvents (callback)](#apidoc.element.newrelic.agent.prototype._sendCustomEvents)
- description and source-code
```javascript
function _sendCustomEvents(callback) {
  // Must be enabled and actually have events to send, otherwise bail and nextTick
  if (this.config.custom_insights_events.enabled && this.customEventsPool.length > 0) {
    var agent = this
    var run_id = agent.config.run_id

    var payload = [
      run_id,
      agent.customEventsPool
    ]

    // send data to collector
    agent.collector.customEvents(payload, function cb_customEvents(err) {
      if (err && err.statusCode === 413 ) {
        var tooLarge = agent.metrics.getOrCreateMetric(NAMES.CUSTOM_EVENTS.TOO_LARGE)
        tooLarge.incrementCallCount()
        logger.warn('request too large; custom event data dropped')
      } else if (err) {
        var failed = agent.metrics.getOrCreateMetric(NAMES.CUSTOM_EVENTS.FAILED)
        failed.incrementCallCount()
        logger.warn('custom events failed to send; re-sampling')

        for (var i = 0; i < agent.customEventsPool.length; i++) {
          agent.customEvents.add(agent.customEventsPool[i])
        }
      }

      callback(err)
    })
  } else {
    process.nextTick(callback)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.agent.prototype._sendErrorEvents"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_sendErrorEvents (callback)](#apidoc.element.newrelic.agent.prototype._sendErrorEvents)
- description and source-code
```javascript
function _sendErrorEvents(callback) {
  if (this.config.error_collector.capture_events && this._lastErrorEvents &&
        this._lastErrorEvents[2].length > 0) {
    var agent = this
    var eventsLimit = this._lastErrorEvents[0]
    var eventsSeen = this._lastErrorEvents[1]
    var events = this._lastErrorEvents[2]
    var run_id = agent.config.run_id

    if (events.length < 1) {
      return process.nextTick(callback)
    }

    var metrics = {
      reservoir_size: eventsLimit,
      events_seen: eventsSeen
    }

    var payload = [
      run_id,
      metrics,
      events
    ]

    // send data to collector
    agent.collector.errorEvents(payload, function cb_errorEvents(err) {
      if (err && err.statusCode === 413 ) {
        logger.warn('request too large; event data dropped')
      } else if (err) {
        logger.warn('error events failed to send; re-sampling')
        agent.errors.mergeEvents(events)
      }
      callback(err)
    })
  } else {
    process.nextTick(callback)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.agent.prototype._sendErrors"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_sendErrors (callback)](#apidoc.element.newrelic.agent.prototype._sendErrors)
- description and source-code
```javascript
function _sendErrors(callback) {
  var agent = this

  if (this.config.collect_errors && this.config.error_collector.enabled) {
    if (!this.collector.isConnected()) {
      return process.nextTick(function cb_nextTick() {
        callback(new Error("not connected to New Relic (errors will be held)"))
      })
    } else if (this.errors.getTotalErrorCount() < 1) {
      logger.debug("No errors to send.")
      return process.nextTick(callback)
    }

    var errors = this.errors.getErrors()
    var payload = [this.config.run_id, errors]

    // reset now to avoid losing errors that come in after delivery starts
    this.errors.clearErrors()

    this.collector.errorData(payload, function cb_errorData(error) {
      if (error) agent.errors.merge(errors)

      callback(error)
    })
  } else {
<span class="apidocCodeCommentSpan">    /**
     * Reset the errors object even if collection is disabled due to error
     * counting. Also covers the case where the error collector gets disabled
     * in the middle of a harvest cycle so the agent doesn't continue to hold
     * on to the errors it had collected during the harvest cycle so far.
     */
</span>    this.errors.clearErrors()
    process.nextTick(callback)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.agent.prototype._sendEvents"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_sendEvents (callback)](#apidoc.element.newrelic.agent.prototype._sendEvents)
- description and source-code
```javascript
function _sendEvents(callback) {
  if (this.config.transaction_events.enabled) {
    var agent = this
    var events = agent.events
    var sample = events.toArray()
    var run_id = agent.config.run_id

    // bail if there are no events
    if (sample.length < 1) {
      return process.nextTick(callback)
    }

    var metrics = {
      reservoir_size: events.limit,
      events_seen: events.seen
    }

    var payload = [
      run_id,
      metrics,
      sample
    ]

    // clear events
    agent.events = new Reservoir(agent.config.transaction_events.max_samples_per_minute)

    // send data to collector
    agent.collector.analyticsEvents(payload, function cb_analyticsEvents(err) {
      if (err && err.statusCode === 413 ) {
        logger.warn('request too large; event data dropped')
      } else if (err) {
        logger.warn('analytics events failed to send; re-sampling')

        // boost the limit if a connection fails
        // and re-aggregate on failure
        var newlimit = agent.config.transaction_events.max_samples_stored
        agent.events.limit = newlimit

        for (var k = 0; k < sample.length; k++) agent.events.add(sample[k])
      } else {
        // if we had to limit events and sample them, emit a warning
        var diff = events.overflow()
        if (diff > 0) logger.warn(
          'analytics event overflow, dropped %d events; ' +
           'try increasing your limit above %d',
          diff, events.limit
        )
      }

      callback(err)
    })
  } else {
    process.nextTick(callback)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.agent.prototype._sendMetrics"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_sendMetrics (callback)](#apidoc.element.newrelic.agent.prototype._sendMetrics)
- description and source-code
```javascript
function _sendMetrics(callback) {
  var agent = this

  if (this.collector.isConnected()) {
    if (this.errors.getTotalErrorCount() > 0) {
      var count = this.errors.getTotalErrorCount()
      this.metrics.getOrCreateMetric(NAMES.ERRORS.ALL).incrementCallCount(count)

      count = this.errors.getWebTransactionsErrorCount()
      this.metrics.getOrCreateMetric(NAMES.ERRORS.WEB).incrementCallCount(count)

      count = this.errors.getBackgroundTransactionsErrorCount()
      this.metrics.getOrCreateMetric(NAMES.ERRORS.OTHER).incrementCallCount(count)
    }

    if (this.config.debug.supportability) {
      this.metrics.merge(this.config.debug.supportability)
    }

    // Send uninstrumented supportability metrics every harvest cycle
    uninstrumented.createMetrics(this.metrics)

    this._processCustomEvents()
    this._processErrorEvents()

    // wait to check until all the standard stuff has been added
    if (this.metrics.toJSON().length < 1) {
      logger.debug("No metrics to send.")
      return process.nextTick(callback)
    }

    var metrics = this.metrics
    var beginSeconds = metrics.started * FROM_MILLIS
    var endSeconds = Date.now() * FROM_MILLIS
    var payload = [this.config.run_id, beginSeconds, endSeconds, metrics]


    // reset now to avoid losing metrics that come in after delivery starts
    this.metrics = new Metrics(
      this.config.apdex_t,
      this.mapper,
      this.metricNameNormalizer
    )

    this.collector.metricData(payload, function cb_metricData(error, rules) {
      if (error) agent.metrics.merge(metrics)
      if (rules) agent.mapper.load(rules)

      callback(error)
    })
  } else {
    process.nextTick(function cb_nextTick() {
      callback(new Error("not connected to New Relic (metrics will be held)"))
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.agent.prototype._sendQueries"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_sendQueries (callback)](#apidoc.element.newrelic.agent.prototype._sendQueries)
- description and source-code
```javascript
function _sendQueries(callback) {
  var agent = this
  var queries = this.queries

  this.queries = new QueryTracer(agent.config)

  if (!this.config.slow_sql.enabled) {
    logger.debug('Slow Query is not enabled.')
    return process.nextTick(callback)
  }

  if (Object.keys(queries.samples).length < 1) {
    logger.debug('No queries to send.')
    return process.nextTick(callback)
  }

  queries.prepareJSON(function gotJSON(err, data) {
    if (err) {
      this.queries.merge(queries)
      logger.debug('Error while serializing query data: %s', err.message)
      return callback(err)
    }

    agent.collector.queryData([data], function handleResponse(error) {
      if (error) agent.queries.merge(queries)
      callback(error)
    })
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.agent.prototype._sendTrace"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_sendTrace (callback)](#apidoc.element.newrelic.agent.prototype._sendTrace)
- description and source-code
```javascript
function _sendTrace(callback) {
  var agent = this
  if (this.config.collect_traces && this.config.transaction_tracer.enabled) {
    if (!this.collector.isConnected()) {
      return process.nextTick(function cb_nextTick() {
        callback(new Error("not connected to New Relic (slow trace data will be held)"))
      })
    }

    this.traces.harvest(function cb_harvest(error, traces, trace) {
      if (error || !traces || traces.length === 0) return callback(error)

      var payload = [agent.config.run_id, traces]
      agent.collector.transactionSampleData(
        payload,
        function cb_transactionSampleData(error) {
          if (!error) agent.traces.reset(trace)

          callback(error)
        }
      )
    })
  } else {
    process.nextTick(callback)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.agent.prototype._setupTracer"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_setupTracer ()](#apidoc.element.newrelic.agent.prototype._setupTracer)
- description and source-code
```javascript
function _setupTracer() {
  var Tracer = require('./transaction/tracer')
  return new Tracer(this)
}
```
- example usage
```shell
...
this.transactionNameNormalizer = null
this.urlNormalizer = null
this.txSegmentNormalizer = null
this.userNormalizer = null
this.reset()

// Transaction tracing.
this.tracer = this._setupTracer()
this.traces = new TraceAggregator(this.config)

// Query tracing.
this.queries = new QueryTracer(this.config)

// Set up all the configuration events the agent needs to listen for.
var self = this
...
```

#### <a name="apidoc.element.newrelic.agent.prototype._startHarvester"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_startHarvester (harvestSeconds)](#apidoc.element.newrelic.agent.prototype._startHarvester)
- description and source-code
```javascript
function _startHarvester(harvestSeconds) {
  var agent = this

  function onError(error) {
    if (error) {
      logger.info(error, "Error on submission to New Relic (data held for redelivery):")
    }
  }

  function harvester() {
    agent.harvest(onError)
  }

  this.harvesterHandle = setInterval(harvester, harvestSeconds * TO_MILLIS)
  // timer.unref is 0.9+
  if (this.harvesterHandle.unref) this.harvesterHandle.unref()
}
```
- example usage
```shell
...
}

if (agent.collector.isConnected() && !agent.config.no_immediate_harvest) {
  // harvest immediately for quicker data display, but after at least 1
  // second or the collector will throw away the data.
  setTimeout(function one_sec_delayed_harvest() {
    agent.harvest(function cb_harvest(error) {
      agent._startHarvester(agent.config.data_report_period)

      agent.setState('started')
      callback(error, config)
    })
  }, 1000)
} else {
  process.nextTick(function cb_nextTick() {
...
```

#### <a name="apidoc.element.newrelic.agent.prototype._stopHarvester"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_stopHarvester ()](#apidoc.element.newrelic.agent.prototype._stopHarvester)
- description and source-code
```javascript
function _stopHarvester() {
  if (this.harvesterHandle) clearInterval(this.harvesterHandle)
  this.harvesterHandle = undefined
}
```
- example usage
```shell
...
 */
Agent.prototype.stop = function stop(callback) {
if (!callback) throw new TypeError("callback required!")

var agent = this

this.setState('stopping')
this._stopHarvester()
sampler.stop()

if (this.collector.isConnected()) {
  this.collector.shutdown(function cb_shutdown(error) {
    if (error) {
      agent.setState('errored')
      logger.warn(error, "Got error shutting down connection to New Relic:")
...
```

#### <a name="apidoc.element.newrelic.agent.prototype._transactionFinished"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>_transactionFinished (transaction)](#apidoc.element.newrelic.agent.prototype._transactionFinished)
- description and source-code
```javascript
function _transactionFinished(transaction) {
  // only available when this.config.debug.tracer_tracing is true
  if (transaction.describer) {
    logger.trace({trace_dump: transaction.describer.verbose}, 'Dumped transaction state.')
  }

  // Allow the API to explicitly set the ignored status on bg-tx.
  // This is handled for web-tx when setName is called on the tx.
  if (!transaction.isWeb() && transaction.forceIgnore !== null) {
    transaction.ignore = transaction.forceIgnore
  }

  if (!transaction.ignore) {
    if (transaction.forceIgnore === false) {
      logger.debug("Explicitly not ignoring %s.", transaction.name)
    }
    this.metrics.merge(transaction.metrics)
    this.errors.onTransactionFinished(transaction, this.metrics)
    this.traces.add(transaction)

    var trace = transaction.trace
    trace.intrinsics = transaction.getIntrinsicAttributes()

    this._addEventFromTransaction(transaction)
  } else if (transaction.forceIgnore === true) {
    logger.debug("Explicitly ignoring %s.", transaction.name)
  } else {
    logger.debug("Ignoring %s.", transaction.name)
  }

  this.activeTransactions--
  this.totalActiveSegments -= transaction.numSegments
  this.segmentsClearedInHarvest += transaction.numSegments
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.agent.prototype.getTransaction"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>getTransaction ()](#apidoc.element.newrelic.agent.prototype.getTransaction)
- description and source-code
```javascript
function getTransaction() {
  return this.tracer.getTransaction()
}
```
- example usage
```shell
...
 */
API.prototype.setTransactionName = function setTransactionName(name) {
var metric = this.agent.metrics.getOrCreateMetric(
  NAMES.SUPPORTABILITY.API + '/setTransactionName'
)
metric.incrementCallCount()

var transaction = this.agent.tracer.getTransaction()
if (!transaction) {
  return logger.warn("No transaction found when setting name to '%s'.", name)
}

if (!name) {
  if (transaction && transaction.url) {
    logger.error("Must include name in setTransactionName call for URL %s.",
...
```

#### <a name="apidoc.element.newrelic.agent.prototype.harvest"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>harvest (callback)](#apidoc.element.newrelic.agent.prototype.harvest)
- description and source-code
```javascript
function harvest(callback) {
  if (!callback) throw new TypeError("callback required!")

  var agent = this
  var harvestSteps = [
    '_sendMetrics',
    '_sendErrors',
    '_sendTrace',
    '_sendEvents',
    '_sendCustomEvents',
    '_sendQueries',
    '_sendErrorEvents'
  ]

  logger.trace({
    segmentTotal: this.totalActiveSegments,
    harvestCreated: this.segmentsCreatedInHarvest,
    harvestCleared: this.segmentsClearedInHarvest,
    activeTransactions: this.activeTransactions
  }, 'Entity stats on harvest')

  this.segmentsCreatedInHarvest = 0
  this.segmentsClearedInHarvest = 0

  if (!this.collector.isConnected()) {
    return process.nextTick(function cb_nextTick() {
      callback(new Error("Not connected to New Relic!"))
    })
  }
  runHarvestStep(0)

  function runHarvestStep(n) {
    agent[harvestSteps[n++]](next)

    function next(error) {
      if (error || n >= harvestSteps.length) return callback(error)
      runHarvestStep(n)
    }
  }
}
```
- example usage
```shell
...
  logger.warn(
    'options.timeout should be of type "number". Got %s',
    typeof options.timeout
  )
}

agent.on('started', function shutdownHarvest() {
  agent.harvest(cb_harvest)
})
agent.on('errored', function logShutdownError(error) {
  agent.stop(callback)
  if (error) {
    logger.error(
      error,
      'The agent encountered an error after calling shutdown.'
...
```

#### <a name="apidoc.element.newrelic.agent.prototype.reconfigure"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>reconfigure (configuration)](#apidoc.element.newrelic.agent.prototype.reconfigure)
- description and source-code
```javascript
function reconfigure(configuration) {
  if (!configuration) throw new TypeError("must pass configuration")

  this.config.onConnect(configuration)
}
```
- example usage
```shell
...
}
this.customEvents.setLimit(this.config.custom_insights_events.max_samples_stored)

// Error tracing.
if (!this.errors) {
  this.errors = new ErrorAggregator(this.config)
}
this.errors.reconfigure(this.config)

// Metrics.
this.mapper = new MetricMapper()
this.metricNameNormalizer = new MetricNormalizer(this.config, 'metric name')
this.metrics = new Metrics(this.config.apdex_t, this.mapper, this.metricNameNormalizer)

// Transaction naming.
...
```

#### <a name="apidoc.element.newrelic.agent.prototype.reset"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>reset ()](#apidoc.element.newrelic.agent.prototype.reset)
- description and source-code
```javascript
function reset() {
  // Insights events.
  if (!this.events) {
    this.events = new Reservoir()
  }
  this.events.setLimit(this.config.transaction_events.max_samples_per_minute)
  if (!this.customEvents) {
    this.customEvents = new Reservoir()
  }
  this.customEvents.setLimit(this.config.custom_insights_events.max_samples_stored)

  // Error tracing.
  if (!this.errors) {
    this.errors = new ErrorAggregator(this.config)
  }
  this.errors.reconfigure(this.config)

  // Metrics.
  this.mapper = new MetricMapper()
  this.metricNameNormalizer = new MetricNormalizer(this.config, 'metric name')
  this.metrics = new Metrics(this.config.apdex_t, this.mapper, this.metricNameNormalizer)

  // Transaction naming.
  this.transactionNameNormalizer = new MetricNormalizer(this.config, 'transaction name')
  this.urlNormalizer = new MetricNormalizer(this.config, 'URL')

  // Segment term based tx renaming for MGI mitigation.
  this.txSegmentNormalizer = new TxSegmentNormalizer()

  // User naming and ignoring rules.
  this.userNormalizer = new MetricNormalizer(this.config, 'user')
  this.userNormalizer.loadFromConfig()

  // Supportability.
  if (this.config.debug.internal_metrics) {
    this.config.debug.supportability = new Metrics(
      this.config.apdex_t,
      this.mapper,
      this.metricNameNormalizer
    )
  }
}
```
- example usage
```shell
...
this.mapper = null
this.metricNameNormalizer = null
this.metrics = null
this.transactionNameNormalizer = null
this.urlNormalizer = null
this.txSegmentNormalizer = null
this.userNormalizer = null
this.reset()

// Transaction tracing.
this.tracer = this._setupTracer()
this.traces = new TraceAggregator(this.config)

// Query tracing.
this.queries = new QueryTracer(this.config)
...
```

#### <a name="apidoc.element.newrelic.agent.prototype.setState"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>setState (newState)](#apidoc.element.newrelic.agent.prototype.setState)
- description and source-code
```javascript
function setState(newState) {
  if (STATES.indexOf(newState) === -1) {
    throw new TypeError("Invalid state " + newState)
  }
  logger.debug("Agent state changed from %s to %s.", this._state, newState)
  this._state = newState
  this.emit(this._state)
}
```
- example usage
```shell
...
 * @param {Function} callback Continuation and error handler.
 */
Agent.prototype.start = function start(callback) {
  if (!callback) throw new TypeError("callback required!")

  var agent = this

  this.setState('starting')

  if (this.config.agent_enabled !== true) {
logger.warn("The New Relic Node.js agent is disabled by its configuration. " +
            "Not starting!")

this.setState('stopped')
return process.nextTick(callback)
...
```

#### <a name="apidoc.element.newrelic.agent.prototype.start"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>start (callback)](#apidoc.element.newrelic.agent.prototype.start)
- description and source-code
```javascript
function start(callback) {
  if (!callback) throw new TypeError("callback required!")

  var agent = this

  this.setState('starting')

  if (this.config.agent_enabled !== true) {
    logger.warn("The New Relic Node.js agent is disabled by its configuration. " +
                "Not starting!")

    this.setState('stopped')
    return process.nextTick(callback)
  }

  if (!(this.config.license_key)) {
    logger.error("A valid account license key cannot be found. " +
                 "Has a license key been specified in the agent configuration " +
                 "file or via the NEW_RELIC_LICENSE_KEY environment variable?")

    this.setState('errored')
    return process.nextTick(function cb_nextTick() {
      callback(new Error("Not starting without license key!"))
    })
  }

  sampler.start(agent)

  logger.info("Starting New Relic for Node.js connection process.")

  this.collector.connect(function cb_connect(error, config) {
    if (error) {
      agent.setState('errored')
      return callback(error, config)
    }

    if (agent.collector.isConnected() && !agent.config.no_immediate_harvest) {
      // harvest immediately for quicker data display, but after at least 1
      // second or the collector will throw away the data.
      setTimeout(function one_sec_delayed_harvest() {
        agent.harvest(function cb_harvest(error) {
          agent._startHarvester(agent.config.data_report_period)

          agent.setState('started')
          callback(error, config)
        })
      }, 1000)
    } else {
      process.nextTick(function cb_nextTick() {
        callback(null, config)
      })
    }
  })
}
```
- example usage
```shell
...
throw new Error(message)
      }

      var shimmer = require('./lib/shimmer.js')
      shimmer.patchModule(agent)
      shimmer.bootstrapInstrumentation(agent)

      agent.start(function cb_start(error) {
if (!error) {
  return logger.debug("New Relic for Node.js is connected to New Relic.")
}

var errorMessage = "New Relic for Node.js halted startup due to an error:"
logger.error(error, errorMessage)
...
```

#### <a name="apidoc.element.newrelic.agent.prototype.stop"></a>[function <span class="apidocSignatureSpan">newrelic.agent.prototype.</span>stop (callback)](#apidoc.element.newrelic.agent.prototype.stop)
- description and source-code
```javascript
function stop(callback) {
  if (!callback) throw new TypeError("callback required!")

  var agent = this

  this.setState('stopping')
  this._stopHarvester()
  sampler.stop()

  if (this.collector.isConnected()) {
    this.collector.shutdown(function cb_shutdown(error) {
      if (error) {
        agent.setState('errored')
        logger.warn(error, "Got error shutting down connection to New Relic:")
      } else {
        agent.setState('stopped')
        logger.info("Stopped New Relic for Node.js.")
      }

      callback(error)
    })
  } else {
    process.nextTick(callback)
  }
}
```
- example usage
```shell
...
function cb_harvest(error) {
  if (error) {
    logger.error(
      error,
      'An error occurred while running last harvest before shutdown.'
    )
  }
  agent.stop(callback)
}

if (options && options.collectPendingData && agent._state !== 'started') {
  if (typeof options.timeout === 'number') {
    var shutdownTimeout = setTimeout(function shutdownTimeout() {
      agent.stop(callback)
    }, options.timeout)
...
```



# <a name="apidoc.module.newrelic.api"></a>[module newrelic.api](#apidoc.module.newrelic.api)

#### <a name="apidoc.element.newrelic.api.api"></a>[function <span class="apidocSignatureSpan">newrelic.</span>api (agent)](#apidoc.element.newrelic.api.api)
- description and source-code
```javascript
function API(agent) {
  this.agent = agent
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.newrelic.api.prototype"></a>[module newrelic.api.prototype](#apidoc.module.newrelic.api.prototype)

#### <a name="apidoc.element.newrelic.api.prototype.addCustomParameter"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>addCustomParameter (name, value)](#apidoc.element.newrelic.api.prototype.addCustomParameter)
- description and source-code
```javascript
function addCustomParameter(name, value) {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/addCustomParameter'
  )
  metric.incrementCallCount()

  // If high security mode is on, custom params are disabled.
  if (this.agent.config.high_security === true) {
    logger.warnOnce(
      "Custom params",
      "Custom parameters are disabled by high security mode."
    )
    return false
  }

  var ignored = this.agent.config.ignored_params || []

  var transaction = this.agent.tracer.getTransaction()
  if (!transaction) {
    return logger.warn("No transaction found for custom parameters.")
  }

  var trace = transaction.trace
  if (!trace.custom) {
    return logger.warn(
      "Couldn't add parameter %s to nonexistent custom parameters.",
      name
    )
  }

  if (CUSTOM_BLACKLIST.indexOf(name) !== -1) {
    return logger.warn("Not overwriting value of NR-only parameter %s.", name)
  }

  if (ignored.indexOf(name) !== -1) {
    return logger.warn("Not setting ignored parameter name %s.", name)
  }

  if (name in trace.custom) {
    logger.debug(
      "Changing custom parameter %s from %s to %s.",
      name,
      trace.custom[name],
      value
    )
  }

  trace.custom[name] = value
}
```
- example usage
```shell
...

Programmatic version of 'rules.ignore' above. Ignoring rules can not be removed
until the Node process is restarted. They can also be added via the module's
configuration. The pattern is mandatory.

### Other API calls

#### newrelic.addCustomParameter(name, value)

Set a custom parameter value to be attached to a transaction trace and/or error
in the New Relic UI. This must be called within the context of a transaction,
so it has a place to set the custom parameters.

#### newrelic.addCustomParameters(params)
...
```

#### <a name="apidoc.element.newrelic.api.prototype.addCustomParameters"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>addCustomParameters (params)](#apidoc.element.newrelic.api.prototype.addCustomParameters)
- description and source-code
```javascript
function addCustomParameters(params) {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/addCustomParameters'
  )
  metric.incrementCallCount()

  for (var key in params) {
    if (!params.hasOwnProperty(key)) {
      continue
    }

    this.addCustomParameter(key, params[key])
  }
}
```
- example usage
```shell
...

#### newrelic.addCustomParameter(name, value)

Set a custom parameter value to be attached to a transaction trace and/or error
in the New Relic UI. This must be called within the context of a transaction,
so it has a place to set the custom parameters.

#### newrelic.addCustomParameters(params)

Set multiple custom parameter values to be attached to a transaction trace and/or
error in the New Relic UI. This must be called within the context of a transaction,
so it has a place to set the custom parameters.

Example of setting multiple custom parameters at once:
...
```

#### <a name="apidoc.element.newrelic.api.prototype.addIgnoringRule"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>addIgnoringRule (pattern)](#apidoc.element.newrelic.api.prototype.addIgnoringRule)
- description and source-code
```javascript
function addIgnoringRule(pattern) {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/addIgnoringRule'
  )
  metric.incrementCallCount()

  if (!pattern) return logger.error("Must include a URL pattern to ignore.")

  this.agent.userNormalizer.addSimple(pattern, null)
}
```
- example usage
```shell
...

#### newrelic.addNamingRule(pattern, name)

Programmatic version of 'rules.name' above. Naming rules can not be removed
until the Node process is restarted. They can also be added via the module's
configuration. Both parameters are mandatory.

#### newrelic.addIgnoringRule(pattern)

Programmatic version of 'rules.ignore' above. Ignoring rules can not be removed
until the Node process is restarted. They can also be added via the module's
configuration. The pattern is mandatory.

### Other API calls
...
```

#### <a name="apidoc.element.newrelic.api.prototype.addNamingRule"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>addNamingRule (pattern, name)](#apidoc.element.newrelic.api.prototype.addNamingRule)
- description and source-code
```javascript
function addNamingRule(pattern, name) {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/addNamingRule'
  )
  metric.incrementCallCount()


  if (!name) return logger.error("Simple naming rules require a replacement name.")

  this.agent.userNormalizer.addSimple(pattern, '/' + name)
}
```
- example usage
```shell
...
Can also be set via the environment variable 'NEW_RELIC_IGNORING_RULES', with
multiple rules passed in as a list of comma-delimited patterns:
'NEW_RELIC_IGNORING_RULES='^/socket\.io/\*/xhr-polling,ignore_me'' Note that
currently there is no way to escape commas in patterns.

### API for adding naming and ignoring rules

#### newrelic.addNamingRule(pattern, name)

Programmatic version of 'rules.name' above. Naming rules can not be removed
until the Node process is restarted. They can also be added via the module's
configuration. Both parameters are mandatory.

#### newrelic.addIgnoringRule(pattern)
...
```

#### <a name="apidoc.element.newrelic.api.prototype.createBackgroundTransaction"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>createBackgroundTransaction (name, group, handle)](#apidoc.element.newrelic.api.prototype.createBackgroundTransaction)
- description and source-code
```javascript
function createBackgroundTransaction(name, group, handle) {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/createBackgroundTransaction'
  )
  metric.incrementCallCount()

  if (handle === undefined && typeof group === 'function') {
    handle = group
    group = 'Nodejs'
  }
  // FLAG: custom_instrumentation
  if (!this.agent.config.feature_flag.custom_instrumentation) {
    return handle
  }

  var fail = false
  if (!name) {
    logger.warn('createBackgroundTransaction called without an url')
    fail = true
  }

  if (typeof handle !== 'function') {
    logger.warn(
      'createBackgroundTransaction called with a handle arg that is not a function'
    )
    fail = true
  }

  if (fail) {
    // If name is undefined but handle is defined we should make a best effort
    // to return it so things don't crash.
    return handle
  }

  logger.debug(
    'creating background transaction generator %s:%s (%s)',
    name,
    group,
    handle && handle.name
  )

  var tracer = this.agent.tracer

  return tracer.transactionNestProxy('bg', function createBackgroundSegment() {
    var tx = tracer.getTransaction()

    logger.debug(
      'creating background transaction %s:%s (%s) with transaction id: %s',
      name,
      group,
      handle && handle.name,
      tx.id
    )

    tx.setBackgroundName(name, group)
    tx.bgSegment = tracer.createSegment(name, recordBackground)
    tx.bgSegment.partialName = group
    tx.bgSegment.start()

    return tracer.bindFunction(handle, tx.bgSegment).apply(this, arguments)
  })
}
```
- example usage
```shell
...
independent transaction and any calls within the 'handle' will be bound to the
new web transaction.

Custom transactions **must** be ended manually by calling 'endTransaction()'.
Timing for custom transaction starts from when the returned wrapped function is
called until 'endTransaction()' is called.

#### newrelic.createBackgroundTransaction(name, [group], handle)

'name' is the name of the job. It should be pretty static, and not include job
ids or anything very specific to that run of the job. 'group' is optional, and
allows you to group types of jobs together. This should follow similar rules as
the 'name'. 'handle' is a function that encompases your background job. Both
custom and auto instrumentation will be captured as part of the transaction.
...
```

#### <a name="apidoc.element.newrelic.api.prototype.createTracer"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>createTracer (name, callback)](#apidoc.element.newrelic.api.prototype.createTracer)
- description and source-code
```javascript
function createTracer(name, callback) {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/createTracer'
  )
  metric.incrementCallCount()

  // FLAG: custom_instrumentation
  if (!this.agent.config.feature_flag.custom_instrumentation) {
    return callback
  }

  var fail = false
  if (!name) {
    logger.warn('createTracer called without a name')
    fail = true
  }

  if (typeof callback !== 'function') {
    logger.warn('createTracer called with a callback arg that is not a function')
    fail = true
  }

  if (fail) {
    // If name is undefined but callback is defined we should make a best effort
    // to return it so things don't crash.
    return callback
  }

  var tracer = this.agent.tracer
  var txn = tracer.getTransaction()
  if (!txn) {
    logger.debug(
      'createTracer called with %s (%s) outside of a transaction, ' +
        'unable to create tracer.',
      name,
      callback && callback.name
    )
    return callback
  }

  logger.debug(
    'creating tracer %s (%s) on transaction %s.',
    name,
    callback && callback.name,
    txn.id
  )

  var segment = tracer.createSegment(name, customRecorder)
  segment.start()
  return tracer.bindFunction(callback, segment, true)
}
```
- example usage
```shell
...
called until 'endTransaction()' is called.

#### newrelic.endTransaction()

This takes no arguments and must be called to end any custom transaction. It
will detect what kind of transaction was active and end it.

#### newrelic.createTracer(name, handle)

'name' is the name of the tracer. It will show up as a segment in your
transaction traces and create its own metric. 'handle' is the function to be
bound to the tracer.

Timing is from when 'createTracer' is called until the 'handle' done executing.
This should be called inside of a transaction to get data. If it is called
...
```

#### <a name="apidoc.element.newrelic.api.prototype.createWebTransaction"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>createWebTransaction (url, handle)](#apidoc.element.newrelic.api.prototype.createWebTransaction)
- description and source-code
```javascript
function createWebTransaction(url, handle) {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/createWebTransaction'
  )
  metric.incrementCallCount()

  // FLAG: custom_instrumentation
  if (!this.agent.config.feature_flag.custom_instrumentation) {
    return handle
  }

  var fail = false
  if (!url) {
    logger.warn('createWebTransaction called without an url')
    fail = true
  }

  if (typeof handle !== 'function') {
    logger.warn('createWebTransaction called with a handle arg that is not a function')
    fail = true
  }

  if (fail) {
    // If name is undefined but handle is defined we should make a best effort
    // to return it so things don't crash.
    return handle
  }

  logger.debug(
    'creating web transaction generator %s (%s).',
    url,
    handle && handle.name
  )

  var tracer = this.agent.tracer

  return tracer.transactionNestProxy('web', function createWebSegment() {
    var tx = tracer.getTransaction()

    logger.debug(
      'creating web transaction %s (%s) with transaction id: %s',
      url,
      handle && handle.name,
      tx.id
    )
    tx.nameState.setName(NAMES.CUSTOM, null, NAMES.ACTION_DELIMITER, url)
    tx.url = url
    tx.applyUserNamingRules(tx.url)
    tx.webSegment = tracer.createSegment(url, recordWeb)
    tx.webSegment.start()

    return tracer.bindFunction(handle, tx.webSegment).apply(this, arguments)
  })
}
```
- example usage
```shell
...
varieties of socket servers, and background jobs. These are things that the
agent can't automatically instrument because without your knowledge of your
application, the agent can't tell when they should begin and end.

Read more at:
https://docs.newrelic.com/docs/agents/nodejs-agent/supported-features/nodejs-custom-instrumentation

#### newrelic.createWebTransaction(url, handle)

'url' is the name of the web transaction. It should be pretty static, not
including anything like user ids or any other data that is very specific to the
request. 'handle' is the function you'd like to wrap in the web transaction.
Both custom and auto instrumentation will be captured as part of the
transaction.
...
```

#### <a name="apidoc.element.newrelic.api.prototype.endTransaction"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>endTransaction ()](#apidoc.element.newrelic.api.prototype.endTransaction)
- description and source-code
```javascript
function endTransaction() {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/endTransaction'
  )
  metric.incrementCallCount()

  // FLAG: custom_instrumentation
  if (!this.agent.config.feature_flag.custom_instrumentation) {
    return
  }

  var tracer = this.agent.tracer
  var tx = tracer.getTransaction()

  if (tx) {
    if (tx.webSegment) {
      tx.setName(tx.url, 0)
      tx.webSegment.markAsWeb(tx.url)
      tx.webSegment.end()
    } else if (tx.bgSegment) {
      tx.bgSegment.end()
    }
    logger.debug('ending transaction with id: %s and name: %s', tx.id, tx.name)
    tx.end()
  } else {
    logger.debug('endTransaction() called while not in a transaction.')
  }
}
```
- example usage
```shell
...
transaction and any calls within the 'handle' will be bound to the new,
independent background transaction.

Custom transactions **must** be ended manually by calling 'endTransaction()'.
Timing for custom transaction starts from when the returned wrapped function is
called until 'endTransaction()' is called.

#### newrelic.endTransaction()

This takes no arguments and must be called to end any custom transaction. It
will detect what kind of transaction was active and end it.

#### newrelic.createTracer(name, handle)

'name' is the name of the tracer. It will show up as a segment in your
...
```

#### <a name="apidoc.element.newrelic.api.prototype.getBrowserTimingHeader"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>getBrowserTimingHeader ()](#apidoc.element.newrelic.api.prototype.getBrowserTimingHeader)
- description and source-code
```javascript
function getBrowserTimingHeader() {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/getBrowserTimingHeader'
  )
  metric.incrementCallCount()

  var config = this.agent.config

<span class="apidocCodeCommentSpan">  /**
   * Gracefully fail.
   *
   * Output an HTML comment and log a warning the comment is meant to be
   * innocuous to the end user.
   *
   * @param {number} num          - Error code from 'RUM_ISSUES'.
   * @param {bool} [quite=false]  - Be quiet about this failure.
   *
   * @see RUM_ISSUES
   */
</span>  function _gracefail(num, quiet) {
    if (quiet) {
      logger.debug(RUM_ISSUES[num])
    } else {
      logger.warn(RUM_ISSUES[num])
    }
    return '<!-- NREUM: (' + num + ') -->'
  }

  var browser_monitoring = config.browser_monitoring

  // config.browser_monitoring should always exist, but we don't want the agent
  // to bail here if something goes wrong
  if (!browser_monitoring) return _gracefail(2)

  /* Can control header generation with configuration this setting is only
   * available in the newrelic.js config file, it is not ever set by the
   * server.
   */
  if (!browser_monitoring.enable) {
    // It has been disabled by the user; no need to warn them about their own
    // settings so fail quietly and gracefully.
    return _gracefail(0, true)
  }

  var trans = this.agent.getTransaction()

  // bail gracefully outside a transaction
  if (!trans) return _gracefail(1)

  var name = trans.getName()

  /* If we're in an unnamed transaction, add a friendly warning this is to
   * avoid people going crazy, trying to figure out why browser monitoring is
   * not working when they're missing a transaction name.
   */
  if (!name) return _gracefail(3)

  var time = trans.timer.getDurationInMillis()

  /*
   * Only the first 13 chars of the license should be used for hashing with
   * the transaction name.
   */
  var key = config.license_key.substr(0, 13)
  var appid = config.application_id

  /* This is only going to work if the agent has successfully handshaked with
   * the collector. If the networks is bad, or there is no license key set in
   * newrelis.js, there will be no application_id set.  We bail instead of
   * outputting null/undefined configuration values.
   */
  if (!appid) return _gracefail(4)

  /* If there is no browser_key, the server has likely decided to disable
   * browser monitoring.
   */
  var licenseKey = browser_monitoring.browser_key
  if (!licenseKey) return _gracefail(5)

  /* If there is no agent_loader script, there is no point
   * in setting the rum data
   */
  var js_agent_loader = browser_monitoring.js_agent_loader
  if (!js_agent_loader) return _gracefail(6)

  /* If rum is enabled, but then later disabled on the server,
   * this is the only parameter that gets updated.
   *
   * This condition should only be met if rum is disabled during
   * the lifetime of an application, and it should be picked up
   * on the next ForceRestart by the collector.
   */
  var loader = browser_monitoring.loader
  if (loader === 'none') return _gracefail(7)

  // This hash gets written directly into the browser.
  var rum_hash = {
    agent: browser_monitoring.js_agent_file,
    beacon: browser_monitoring.beacon,
    errorBeacon: browser_monitoring.error_beacon,
    licenseKey: licenseKey,
    applicationID: appid,
    applicationTime: time,
    transactionName: hashes.obfuscateNameUsingKey(name, key),
    queueTime: trans.queueTime,
    ttGuid: trans.id,

    // we don't use these parameters yet
    agentToken: null
  }

  // if debugging, do pretty format of JSON
  var tabs = config.browser_monitoring.debug ? 2 : 0
  var json = JSON.stringify(rum_hash, null, tabs)


  // the complete header to be written to the browser
  var out = util.format(
    RUM_STUB,
    json,
    js_agent_loader
  )

  logger.trace('generating RUM header', out)

  return out
}
```
- example usage
```shell
...
times.

Headers must be manually injected, but no extra configuration is necessary to
enable browser timings.

### Basics

- Insert the result of 'newrelic.getBrowserTimingHeader()'
into your html page.
- The browser timing headers should be placed in the beginning of your '<head>' tag.
  - As an exception to the above, for maximum IE compatability, the results of 'getBrowserTimingHeader()'
should be placed *after* any 'X-UA-COMPATIBLE HTTP-EQUIV' meta tags.
- Do *not* cache the header, call it once for every request.

### Example
...
```

#### <a name="apidoc.element.newrelic.api.prototype.incrementMetric"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>incrementMetric (name, value)](#apidoc.element.newrelic.api.prototype.incrementMetric)
- description and source-code
```javascript
function incrementMetric(name, value) {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/incrementMetric'
  )
  metric.incrementCallCount()

  // FLAG: custom_metrics
  if (!this.agent.config.feature_flag.custom_metrics) {
    return
  }

  if (!value && value !== 0) {
    value = 1
  }

  if (typeof value !== 'number' || value % 1 !== 0) {
    logger.warn('Metric Increment value must be an integer')
    return
  }

  this.recordMetric(name, {
    count: value,
    total: 0,
    min: 0,
    max: 0,
    sumOfSquares: 0
  })
}
```
- example usage
```shell
...
'Custom/' typically followed by segments for 'category' and 'label'.
(eg.'Custom/my_category/my_label').
'value' is either a numerical value to associate with the metric sample,
or an object representing multiple samples for the metric. If 'value' is
an object, it must include keys for 'count', 'total', 'min', 'max', and
'sumOfSquares'.

#### newrelic.incrementMetric(name[, amount])

'name' is the metric name to record, it must be a string that beings with
'Custom/' typically followed by segments for 'category' and 'label'.
(eg.'Custom/my_category/my_label').
'amount' is optional, but must be an integer if provided.  'amount' is
the number of times to increment the metrics 'count', it defaults to 1.
...
```

#### <a name="apidoc.element.newrelic.api.prototype.noticeError"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>noticeError (error, customParameters)](#apidoc.element.newrelic.api.prototype.noticeError)
- description and source-code
```javascript
function noticeError(error, customParameters) {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/noticeError'
  )
  metric.incrementCallCount()


  if (typeof error === 'string') error = new Error(error)
  var transaction = this.agent.tracer.getTransaction()

  this.agent.errors.addUserError(transaction, error, customParameters)
}
```
- example usage
```shell
...
Allows you to explicitly filter out long-polling routes or requests you know
are going to be time-consuming in an uninteresting way, and also allows you
to gather metrics for requests that would otherwise be ignored. Note that
to prevent a transaction from being ignored with this function, you **must**
pass 'false' as the parameter – in this case 'null' or 'undefined' will be
ignored.

#### newrelic.noticeError(error, customParameters)

If your app is doing its own error handling with domains or try/catch clauses,
but you want all of the information about how many errors are coming out of the
app to be centrally managed, use this call. Unlike most of the calls here, this
function can be used outside of route handlers, but will have additional
context if called from within transaction scope. If custom parameters are
passed in on an object literal, they will be passed back to New Relic for
...
```

#### <a name="apidoc.element.newrelic.api.prototype.recordCustomEvent"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>recordCustomEvent (eventType, attributes)](#apidoc.element.newrelic.api.prototype.recordCustomEvent)
- description and source-code
```javascript
function recordCustomEvent(eventType, attributes) {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/recordCustomEvent'
  )
  metric.incrementCallCount()

  if (!this.agent.config.custom_insights_events.enabled) {
    return
  }
  // Check all the arguments before bailing to give maximum information in a
  // single invocation.
  var fail = false

  if (!eventType || typeof eventType !== 'string') {
    logger.warn(
      'recordCustomEvent requires a string for its first argument, got %s (%s)',
      stringify(eventType),
      typeof eventType
    )
    fail = true
  } else if (!CUSTOM_EVENT_TYPE_REGEX.test(eventType)) {
    logger.warn(
      'recordCustomEvent eventType of %s is invalid, it must match /%s/',
      eventType,
      CUSTOM_EVENT_TYPE_REGEX.source
    )
    fail = true
  } else if (eventType.length > 255) {
    logger.warn(
      'recordCustomEvent eventType must have a length less than 256, got %s (%s)',
      eventType,
      eventType.length
    )
    fail = true
  }
  // If they don't pass an attributes object, or the attributes argument is not
  // an object, or if it is an object and but is actually an array, log a
  // warning and set the fail bit.
  if (!attributes || typeof attributes !== 'object' || Array.isArray(attributes)) {
    logger.warn(
      'recordCustomEvent requires an object for its second argument, got %s (%s)',
      stringify(attributes),
      typeof attributes
    )
    fail = true
  } else if (_checkKeyLength(attributes, 255)) {
    fail = true
  }

  if (fail) {
    return
  }

  var instrinics = {
    type: eventType,
    timestamp: Date.now()
  }

  this.agent.customEvents.add([instrinics, attributes])
}
```
- example usage
```shell
...
},

/**
 * Custom Insights Events
 *
 * Custom insights events are JSON object that are sent to New Relic
 * Insights. You can tell the agent to send your custom events via the
 * 'newrelic.recordCustomEvent()' API. These events are sampled once the max
 * reservoir size is reached. You can tune this setting below.
 *
 * Read more here: http://newrelic.com/insights
 */
custom_insights_events: {
  /**
   * If this is disabled, the agent does not collect, nor try to send, custom
...
```

#### <a name="apidoc.element.newrelic.api.prototype.recordMetric"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>recordMetric (name, value)](#apidoc.element.newrelic.api.prototype.recordMetric)
- description and source-code
```javascript
function recordMetric(name, value) {
  var supportMetric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/recordMetric'
  )
  supportMetric.incrementCallCount()

  // FLAG: custom_metrics
  if (!this.agent.config.feature_flag.custom_metrics) {
    return
  }

  if (typeof name !== 'string') {
    logger.warn('Metric name must be a string')
    return
  }

  var metric = this.agent.metrics.getOrCreateMetric(name)

  if (typeof value === 'number') {
    metric.recordValue(value)
    return
  }

  if (typeof value !== 'object') {
    logger.warn('Metric value must be either a number, or a metric object')
    return
  }

  var stats = {}
  var required = ['count', 'total', 'min', 'max', 'sumOfSquares']
  var keyMap = {count: 'callCount'}

  for (var i = 0, l = required.length; i < l; ++i) {
    if (typeof value[required[i]] !== 'number') {
      logger.warn('Metric object must include ' + required[i] + ' as a number')
      return
    }

    var key = keyMap[required[i]] || required[i]
    stats[key] = value[required[i]]
  }

  if (typeof value.totalExclusive === 'number') {
    stats.totalExclusive = value.totalExclusive
  } else {
    stats.totalExclusive = value.total
  }

  metric.merge(stats)
}
```
- example usage
```shell
...
transaction traces and create its own metric. 'handle' is the function to be
bound to the tracer.

Timing is from when 'createTracer' is called until the 'handle' done executing.
This should be called inside of a transaction to get data. If it is called
outside of a transaction it will just pass through.

#### newrelic.recordMetric(name, value)

'name' is the metric name to record, it must be a string that begins with
'Custom/' typically followed by segments for 'category' and 'label'.
(eg.'Custom/my_category/my_label').
'value' is either a numerical value to associate with the metric sample,
or an object representing multiple samples for the metric. If 'value' is
an object, it must include keys for 'count', 'total', 'min', 'max', and
...
```

#### <a name="apidoc.element.newrelic.api.prototype.setControllerName"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>setControllerName (name, action)](#apidoc.element.newrelic.api.prototype.setControllerName)
- description and source-code
```javascript
function setControllerName(name, action) {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/setControllerName'
  )
  metric.incrementCallCount()

  var transaction = this.agent.tracer.getTransaction()
  if (!transaction) {
    return logger.warn("No transaction found when setting controller to %s.", name)
  }

  if (!name) {
    if (transaction && transaction.url) {
      logger.error("Must include name in setControllerName call for URL %s.",
                   transaction.url)
    } else {
      logger.error("Must include name in setControllerName call.")
    }

    return
  }

  action = action || transaction.verb || 'GET'
  transaction.forceName = NAMES.CONTROLLER + '/' + name + '/' + action
}
```
- example usage
```shell
...
Name the current request. You can call this function anywhere within the
context of an HTTP request handler, at any time after handling of the request
has started, but before the request has finished. A good rule of thumb is that
if the request and response objects are in scope, you can set the name.

Explicitly calling 'newrelic.setTransactionName()' will override any names set
by Express, Restify or Hapi routes. Calls to 'newrelic.setTransactionName()' and
'newrelic.setControllerName()' will overwrite each other. The last call made
before the request ends wins.

**VERY IMPORTANT NOTE:** Do not include highly variable information like GUIDs,
numerical IDs, or timestamps in the request names you create. If your request
is slow enough to generate a transaction trace, that trace will contain the
original URL. If you enable parameter capture, the parameters will also be
attached to the trace. The request names are used to group requests for New
...
```

#### <a name="apidoc.element.newrelic.api.prototype.setIgnoreTransaction"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>setIgnoreTransaction (ignored)](#apidoc.element.newrelic.api.prototype.setIgnoreTransaction)
- description and source-code
```javascript
function setIgnoreTransaction(ignored) {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/setIgnoreTransaction'
  )
  metric.incrementCallCount()

  var transaction = this.agent.tracer.getTransaction()
  if (!transaction) {
    return logger.warn("No transaction found to ignore.")
  }

  transaction.forceIgnore = ignored
}
```
- example usage
```shell
...

Example of setting multiple custom parameters at once:

'''javascript
newrelic.addCustomParameters({test: 'value', test2: 'value2'});
'''

#### newrelic.setIgnoreTransaction(ignored)

Tell the module explicitly whether or not a given request should be ignored.
Allows you to explicitly filter out long-polling routes or requests you know
are going to be time-consuming in an uninteresting way, and also allows you
to gather metrics for requests that would otherwise be ignored. Note that
to prevent a transaction from being ignored with this function, you **must**
pass 'false' as the parameter – in this case 'null' or 'undefined' will be
...
```

#### <a name="apidoc.element.newrelic.api.prototype.setTransactionName"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>setTransactionName (name)](#apidoc.element.newrelic.api.prototype.setTransactionName)
- description and source-code
```javascript
function setTransactionName(name) {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/setTransactionName'
  )
  metric.incrementCallCount()

  var transaction = this.agent.tracer.getTransaction()
  if (!transaction) {
    return logger.warn("No transaction found when setting name to '%s'.", name)
  }

  if (!name) {
    if (transaction && transaction.url) {
      logger.error("Must include name in setTransactionName call for URL %s.",
                   transaction.url)
    } else {
      logger.error("Must include name in setTransactionName call.")
    }

    return
  }

  transaction.forceName = NAMES.CUSTOM + '/' + name
}
```
- example usage
```shell
...

is all you need. Please note that you still need to ensure that loading the New
Relic module is the first thing your application does, as it needs to bootstrap
itself before the rest of your application loads, but you can safely require
the module from multiple modules in your application – it will only initialize
itself once.

#### newrelic.setTransactionName(name)

Name the current request. You can call this function anywhere within the
context of an HTTP request handler, at any time after handling of the request
has started, but before the request has finished. A good rule of thumb is that
if the request and response objects are in scope, you can set the name.

Explicitly calling 'newrelic.setTransactionName()' will override any names set
...
```

#### <a name="apidoc.element.newrelic.api.prototype.shutdown"></a>[function <span class="apidocSignatureSpan">newrelic.api.prototype.</span>shutdown (options, cb)](#apidoc.element.newrelic.api.prototype.shutdown)
- description and source-code
```javascript
function shutdown(options, cb) {
  var metric = this.agent.metrics.getOrCreateMetric(
    NAMES.SUPPORTABILITY.API + '/shutdown'
  )
  metric.incrementCallCount()

  var callback = cb
  if (!callback) {
    if (typeof options === 'function') {
      callback = options
    } else {
      callback = function noop() {}
    }
  }

  var agent = this.agent

  function cb_harvest(error) {
    if (error) {
      logger.error(
        error,
        'An error occurred while running last harvest before shutdown.'
      )
    }
    agent.stop(callback)
  }

  if (options && options.collectPendingData && agent._state !== 'started') {
    if (typeof options.timeout === 'number') {
      var shutdownTimeout = setTimeout(function shutdownTimeout() {
        agent.stop(callback)
      }, options.timeout)
      // timer.unref only in 0.9+
      if (shutdownTimeout.unref) {
        shutdownTimeout.unref()
      }
    } else if (options.timeout) {
      logger.warn(
        'options.timeout should be of type "number". Got %s',
        typeof options.timeout
      )
    }

    agent.on('started', function shutdownHarvest() {
      agent.harvest(cb_harvest)
    })
    agent.on('errored', function logShutdownError(error) {
      agent.stop(callback)
      if (error) {
        logger.error(
          error,
          'The agent encountered an error after calling shutdown.'
        )
      }
    })
  } else if (options && options.collectPendingData) {
    agent.harvest(cb_harvest)
  } else {
    agent.stop(callback)
  }
}
```
- example usage
```shell
...
but you want all of the information about how many errors are coming out of the
app to be centrally managed, use this call. Unlike most of the calls here, this
function can be used outside of route handlers, but will have additional
context if called from within transaction scope. If custom parameters are
passed in on an object literal, they will be passed back to New Relic for
display.

#### newrelic.shutdown([options], callback)

Use this method to gracefully shut down the agent.  When called with
'options.collectPendingData' set to true, the agent will send any pending data to
the New Relic servers before shutting down.  This is useful when you want to shut down
the Node process and make sure that all transactions and/or errors are captured by
New Relic.
...
```



# <a name="apidoc.module.newrelic.aws_info"></a>[module newrelic.aws_info](#apidoc.module.newrelic.aws_info)

#### <a name="apidoc.element.newrelic.aws_info.aws_info"></a>[function <span class="apidocSignatureSpan">newrelic.</span>aws_info (agent, callback)](#apidoc.element.newrelic.aws_info.aws_info)
- description and source-code
```javascript
function fetchAWSInfo(agent, callback) {
  if (!agent.config.utilization || !agent.config.utilization.detect_aws) {
    return callback(null)
  }

  if (resultDict) {
    return callback(resultDict)
  }

  var awsQuery = module.exports._awsQuery

  awsQuery('instance-type', agent, function getInstanceType(type) {
    if (!type) return callback(null)
    awsQuery('instance-id', agent, function getInstanceId(id) {
      if (!id) return callback(null)
      awsQuery('placement/availability-zone', agent, function getZone(zone) {
        if (!zone) return callback(null)
        resultDict = {
          type: type,
          id: id,
          zone: zone
        }
        return callback(resultDict)
      })
    })
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.aws_info._awsQuery"></a>[function <span class="apidocSignatureSpan">newrelic.aws_info.</span>_awsQuery (key, agent, callback)](#apidoc.element.newrelic.aws_info._awsQuery)
- description and source-code
```javascript
function awsQuery(key, agent, callback) {
  var instanceHost = '169.254.169.254'
  var apiVersion = '2008-02-01'
  var url = ['http:/', instanceHost, apiVersion, 'meta-data', key].join('/')
  var req = http.get(url, function awsRequest(res) {
    res.pipe(concat(respond))
    function respond(data) {
      var valid = checkResponseString(data)
      if (!valid) {
        var awsError = agent.metrics.getOrCreateMetric(NAMES.UTILIZATION.AWS_ERROR)
        awsError.incrementCallCount()
        logger.debug('Response for attribute ' + key + ': %s'
          , data)
        data = null
      } else {
        data = data.toString('utf8')
      }

      agent.removeListener('errored', abortRequest)
      agent.removeListener('stopped', abortRequest)
      callback(data)
    }
  })
  req.setTimeout(1000, function awsTimeout() {
    logger.debug('Request for attribute %s timed out', key)
    callback(null)
  })
  req.on('error', function awsError(err) {
    logger.debug('Message for attribute %s: %s', key, err.message)
    callback(null)
  })

  agent.once('errored', abortRequest)
  agent.once('stopped', abortRequest)

  function abortRequest() {
    logger.debug('Abborting request for attribute %s', key)
    req.abort()
    agent.removeListener('errored', abortRequest)
    agent.removeListener('stopped', abortRequest)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.aws_info.clearCache"></a>[function <span class="apidocSignatureSpan">newrelic.aws_info.</span>clearCache ()](#apidoc.element.newrelic.aws_info.clearCache)
- description and source-code
```javascript
function clearAWSCache() {
  resultDict = null
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.newrelic.config"></a>[module newrelic.config](#apidoc.module.newrelic.config)

#### <a name="apidoc.element.newrelic.config.config"></a>[function <span class="apidocSignatureSpan">newrelic.</span>config (config)](#apidoc.element.newrelic.config.config)
- description and source-code
```javascript
function Config(config) {
  EventEmitter.call(this)

  // 1. start by cloning the defaults
  try {
    var basis = JSON.parse(stringifySync(DEFAULT_CONFIG))
    Object.keys(basis).forEach(function cb_forEach(key) {
      this[key] = basis[key]
    }, this)
  } catch (err) {
    logger.warn('Unable to clone the default config, %s: %s', DEFAULT_CONFIG_PATH, err)
  }

  if (config &&
      (process.env[ENV_MAPPING.ssl] === 'false' || config.ssl === false) &&
      process.env[ENV_MAPPING.port] === undefined && config.port === undefined ) {
    config.port = 80
  }

  // 2. initialize undocumented, internal-only default values

  // feature flags are mostly private settings for gating unreleased features
  // flags are set in the feature_flags.js file
  this.feature_flag = feature_flag.prerelease

  // set by environment
  this.newrelic_home = null
  // set by configuration file loader
  this.config_file_path = null
  // set by collector on handshake
  this.run_id = null
  this.application_id = null
  this.web_transactions_apdex = {}
  this.cross_process_id = null
  this.encoding_key = null
  this.obfuscatedId = null
  this.trusted_account_ids = null

  // how frequently harvester runs
  this.data_report_period = 60

  // this value is arbitrary
  this.max_trace_segments = 900

  // feature level of this account
  this.product_level = 0
  // product-level related
  this.collect_traces = true
  this.collect_errors = true

  // override options for utilization stats
  this.utilization.logical_processors = null
  this.utilization.total_ram_mib = null
  this.utilization.billing_hostname = null

  this.browser_monitoring.loader = 'rum'
  this.browser_monitoring.loader_version = ''

  // Settings to play nice with DLPs (see NODE-1044).
  this.compressed_content_encoding = "deflate"  // Deflate or gzip
  this.simple_compression = false               // Disables subcomponent compression
  this.put_for_data_send = false                // Changes http verb for harvest


  // 3. override defaults with values from the loaded / passed configuration
  this._fromPassed(config)

  // 3.5. special values (only Azure environment APP_POOL_ID for now)
  this._fromSpecial()

  // 4. override config with environment variables
  this._fromEnvironment()

  // 5. clean up anything that requires postprocessing
  this._canonicalize()

  // 6. put the version in the config
  this.version = require('../package.json').version

  // 7. apply high security overrides
  if (this.high_security === true) {
    this._applyHighSecurity()
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.config.getOrCreateInstance"></a>[function <span class="apidocSignatureSpan">newrelic.config.</span>getOrCreateInstance ()](#apidoc.element.newrelic.config.getOrCreateInstance)
- description and source-code
```javascript
function getOrCreateInstance() {
  if (_configInstance === null) {
    _configInstance = initialize()
  }
  return _configInstance
}
```
- example usage
```shell
...
  throw new Error(message)
}

logger.debug("Current working directory at module load is %s.", process.cwd())
logger.debug("Process title is %s.", process.title)
logger.debug("Application was invoked as %s.", process.argv.join(' '))

var config = require('./lib/config.js').getOrCreateInstance()

// Get the initialized logger as we likely have a bootstrap logger which
// just pipes to stdout.
logger = require('./lib/logger.js')

if (!config || !config.agent_enabled) {
  logger.info("Module not enabled in configuration; not starting.")
...
```

#### <a name="apidoc.element.newrelic.config.initialize"></a>[function <span class="apidocSignatureSpan">newrelic.config.</span>initialize (config)](#apidoc.element.newrelic.config.initialize)
- description and source-code
```javascript
function initialize(config) {
<span class="apidocCodeCommentSpan">  /* When the logger is required here, it bootstraps itself and then
   * injects itself into this module's closure via setLogger on the
   * instance of the logger it creates.
   */
</span>  logger = require('./logger.js')

  if (config) return new Config(config)

  if (isTruthular(process.env.NEW_RELIC_NO_CONFIG_FILE)) {
    config = new Config({})
    if (config.newrelic_home) delete config.newrelic_home
    return config
  }

  var filepath = _findConfigFile()
  if (!filepath) {
    _noConfigFile()
    return null
  }

  try {
    config = new Config(require(filepath).config)
    config.config_file_path = filepath
    logger.debug("Using configuration file %s.", filepath)

    config.validateFlags()

    return config
  } catch (error) {
    logger.error(error)

    throw new Error(
      "Unable to read configuration file " + filepath + ". A default\n" +
      "configuration file can be copied from " + DEFAULT_CONFIG_PATH + "\n" +
      "and renamed to 'newrelic.js' in the directory from which you'll be starting\n" +
      "your application."
    )
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.config.super_"></a>[function <span class="apidocSignatureSpan">newrelic.config.</span>super_ ()](#apidoc.element.newrelic.config.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.newrelic.config.prototype"></a>[module newrelic.config.prototype](#apidoc.module.newrelic.config.prototype)

#### <a name="apidoc.element.newrelic.config.prototype._alwaysUpdateIfChanged"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_alwaysUpdateIfChanged (json, key)](#apidoc.element.newrelic.config.prototype._alwaysUpdateIfChanged)
- description and source-code
```javascript
function _alwaysUpdateIfChanged(json, key) {
  var value = json[key]
  if (value !== null && value !== undefined && this[key] !== value) {
    if (Array.isArray(value) && Array.isArray(this[key])) {
      value.forEach(function cb_forEach(element) {
        if (this[key].indexOf(element) === -1) this[key].push(element)
      }, this)
    } else {
      this[key] = value
    }
    this.emit(key, value)
    logger.debug("Configuration of %s was changed to %s by New Relic.", key, value)
  }
}
```
- example usage
```shell
...
// handled by config.onConnect
case 'high_security':
  break

// always accept these settings
case 'cross_process_id':
case 'encoding_key':
  this._alwaysUpdateIfChanged(params, key)
  if (this.cross_process_id && this.encoding_key) {
    this.obfuscatedId = hashes.obfuscateNameUsingKey(this.cross_process_id,
                                                     this.encoding_key)
  }
  break

// always accept these settings
...
```

#### <a name="apidoc.element.newrelic.config.prototype._applyHighSecurity"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_applyHighSecurity ()](#apidoc.element.newrelic.config.prototype._applyHighSecurity)
- description and source-code
```javascript
function _applyHighSecurity() {
  var config = this
  checkNode('', this, HIGH_SECURITY_SETTINGS)

  function checkNode(base, target, settings) {
    Object.keys(settings).forEach(checkKey.bind(null, base, target, settings))
  }

  function checkKey(base, target, settings, key) {
    var hsValue = settings[key]


    if (hsValue && typeof hsValue === 'object') {
      if (typeof target[key] !== 'object') {
        logger.warn(
          'High Security Mode: %s should be an object, found %s',
          key,
          target[key]
        )
        target[key] = {}
      }

      return checkNode(base + key + '.', target[key], hsValue)
    }

    if (target[key] !== hsValue) {
      logger.warn('High Security Mode: %s was set to %s, coercing to %s',
                  key, target[key], hsValue)
      target[key] = hsValue
      config.emit(base + key, hsValue)
    }
  }
}
```
- example usage
```shell
...
 this._canonicalize()

 // 6. put the version in the config
 this.version = require('../package.json').version

 // 7. apply high security overrides
 if (this.high_security === true) {
   this._applyHighSecurity()
 }
}
util.inherits(Config, EventEmitter)

/**
* Because this module and logger depend on each other, the logger needs
* a way to inject the actual logger instance once it's constructed.
...
```

#### <a name="apidoc.element.newrelic.config.prototype._canonicalize"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_canonicalize ()](#apidoc.element.newrelic.config.prototype._canonicalize)
- description and source-code
```javascript
function _canonicalize() {
  var codes = this.error_collector && this.error_collector.ignore_status_codes
  if (codes) {
    this.error_collector.ignore_status_codes = codes.map(function cb_map(code) {
      return parseInt(code, 10)
    })
  }

  var logAliases = {
    'verbose': 'trace',
    'debugging': 'debug',
    'warning': 'warn',
    'err': 'error'
  }
  var level = this.logging.level
  this.logging.level = logAliases[level] || level
}
```
- example usage
```shell
...
// 3.5. special values (only Azure environment APP_POOL_ID for now)
this._fromSpecial()

// 4. override config with environment variables
this._fromEnvironment()

// 5. clean up anything that requires postprocessing
this._canonicalize()

// 6. put the version in the config
this.version = require('../package.json').version

// 7. apply high security overrides
if (this.high_security === true) {
  this._applyHighSecurity()
...
```

#### <a name="apidoc.element.newrelic.config.prototype._emitIfSet"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_emitIfSet (json, key)](#apidoc.element.newrelic.config.prototype._emitIfSet)
- description and source-code
```javascript
function _emitIfSet(json, key) {
  var value = json[key]
  if (value !== null && value !== undefined) this.emit(key, value)
}
```
- example usage
```shell
...
  break

// also accept these settings
case 'url_rules':
case 'metric_name_rules':
case 'transaction_name_rules':
case 'transaction_segment_terms':
  this._emitIfSet(params, key)
  break

// setting these can be disabled by ignore_server_configuration
case 'ssl':
case 'apdex_t':
case 'web_transactions_apdex':
case 'data_report_period':
...
```

#### <a name="apidoc.element.newrelic.config.prototype._fromEnvironment"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_fromEnvironment (metadata, data)](#apidoc.element.newrelic.config.prototype._fromEnvironment)
- description and source-code
```javascript
function _fromEnvironment(metadata, data) {
  if (!metadata) metadata = ENV_MAPPING
  if (!data) data = this

  Object.keys(metadata).forEach(function cb_forEach(value) {
    // if it's not in the config, it doesn't exist
    if (data[value] === undefined) return

    var node = metadata[value]
    if (typeof node === 'string') {
      var setting = process.env[node]
      if (setting) {
        if (LIST_VARS.indexOf(node) > -1) {
          data[value] = setting.split(',').map(function cb_map(k) {
            return k.trim()
          })
        } else if (OBJECT_LIST_VARS.indexOf(node) > -1) {
          data[value] = fromObjectList(setting)
        } else if (BOOLEAN_VARS.indexOf(node) > -1) {
          data[value] = isTruthular(setting)
        } else if (FLOAT_VARS.indexOf(node) > -1) {
          data[value] = parseFloat(setting, 10)
        } else if (INT_VARS.indexOf(node) > -1) {
          data[value] = parseInt(setting, 10)
        } else {
          data[value] = setting
        }
      }
    } else {
      // don't crash if the mapping has config keys the current config doesn't.
      if (!data[value]) data[value] = {}
      this._fromEnvironment(node, data[value])
    }
  }, this)
}
```
- example usage
```shell
...
// 3. override defaults with values from the loaded / passed configuration
this._fromPassed(config)

// 3.5. special values (only Azure environment APP_POOL_ID for now)
this._fromSpecial()

// 4. override config with environment variables
this._fromEnvironment()

// 5. clean up anything that requires postprocessing
this._canonicalize()

// 6. put the version in the config
this.version = require('../package.json').version
...
```

#### <a name="apidoc.element.newrelic.config.prototype._fromPassed"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_fromPassed (external, internal, arbitrary)](#apidoc.element.newrelic.config.prototype._fromPassed)
- description and source-code
```javascript
function _fromPassed(external, internal, arbitrary) {
  if (!external) return
  if (!internal) internal = this

  Object.keys(external).forEach(function cb_forEach(key) {
    // if it's not in the defaults, it doesn't exist
    if (!arbitrary && internal[key] === undefined) return

    try {
      var node = external[key]
    } catch (err) {
      logger.warn('Error thrown on access of user config for key: %s', key)
      return
    }

    if (Array.isArray(node)) {
      internal[key] = node
    } else if (typeof node === 'object') {
      // is top level and can have arbitrary keys
      if (internal === this && HAS_ARBITRARY_KEYS.indexOf(key) !== -1) {
        this._fromPassed(node, internal[key], true)
      } else {
        this._fromPassed(node, internal[key], false)
      }
    } else {
      internal[key] = node
    }
  }, this)
}
```
- example usage
```shell
...
// Settings to play nice with DLPs (see NODE-1044).
this.compressed_content_encoding = "deflate"  // Deflate or gzip
this.simple_compression = false               // Disables subcomponent compression
this.put_for_data_send = false                // Changes http verb for harvest


// 3. override defaults with values from the loaded / passed configuration
this._fromPassed(config)

// 3.5. special values (only Azure environment APP_POOL_ID for now)
this._fromSpecial()

// 4. override config with environment variables
this._fromEnvironment()
...
```

#### <a name="apidoc.element.newrelic.config.prototype._fromServer"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_fromServer (params, key)](#apidoc.element.newrelic.config.prototype._fromServer)
- description and source-code
```javascript
function _fromServer(params, key) {
  switch (key) {
    // handled by the connection
    case 'messages':
      break

    // *sigh* Xzibit, etc.
    case 'agent_config':
      this.onConnect(params[key], true)
      break

    // if it's undefined or null, so be it
    case 'agent_run_id':
      this.run_id = params.agent_run_id
      break

    // handled by config.onConnect
    case 'high_security':
      break

    // always accept these settings
    case 'cross_process_id':
    case 'encoding_key':
      this._alwaysUpdateIfChanged(params, key)
      if (this.cross_process_id && this.encoding_key) {
        this.obfuscatedId = hashes.obfuscateNameUsingKey(this.cross_process_id,
                                                         this.encoding_key)
      }
      break

    // always accept these settings
    case 'collect_traces':
    case 'collect_errors':
    case 'product_level':
    case 'application_id':
    case 'trusted_account_ids':
      this._alwaysUpdateIfChanged(params, key)
      break

    case 'collect_error_events':
      if (params.collect_error_events === false) {
        this._updateNestedIfChanged(
          params,
          this.error_collector,
          key,
          'capture_events'
        )
      }
      break

    // also accept these settings
    case 'url_rules':
    case 'metric_name_rules':
    case 'transaction_name_rules':
    case 'transaction_segment_terms':
      this._emitIfSet(params, key)
      break

    // setting these can be disabled by ignore_server_configuration
    case 'ssl':
    case 'apdex_t':
    case 'web_transactions_apdex':
    case 'data_report_period':
    case 'ignored_params':
      this._updateIfChanged(params, key)
      break
    case 'transaction_tracer.enabled':
      this._updateNestedIfChanged(
        params,
        this.transaction_tracer,
        'transaction_tracer.enabled',
        'enabled'
      )
      break
    case 'transaction_tracer.transaction_threshold':
      this._updateNestedIfChanged(
        params,
        this.transaction_tracer,
        'transaction_tracer.transaction_threshold',
        'transaction_threshold'
      )
      break
    case 'error_collector.enabled':
      this._updateNestedIfChanged(
        params,
        this.error_collector,
        'error_collector.enabled',
        'enabled'
      )
      break
    case 'error_collector.ignore_status_codes':
      this._updateNestedIfChanged(
        params,
        this.error_collector,
        'error_collector.ignore_status_codes',
        'ignore_status_codes'
      )
      this._canonicalize()
      break

    case 'error_collector.capture_events':
      this._updateNestedIfChanged(
        params,
        this.error_collector,
        'error_collector.capture_events',
        'capture_events'
      )
      break

    case 'error_collector.max_event_samples_stored':
      this._updateNestedIfChanged(
        params,
        this.error_collector,
        'error_collector.max_event_samples_stored',
        'max_event_samples_stored'
      )
      break

    case 'collect_analytics_events':
      // never enable from server-side
      // but we allow the server to disable
      if (params.collect_analytics_events === false)
        this.transaction_events.enabled = false
      break

    case 'collect_custom_events':
      // never enable from server-side
      // but we allow the server to disable
      if (params.collect_custom_events === false)
        this.custom_insights_events.enabled = false
      break

    case 'transaction_events.max_samples_stored':
      this._updateNestedIfChanged(
        params,
        this.transaction_events,
        key,
        'max_samples_stored'
      )
      break

    case 'transaction_events.max_samples_per_minute':
      this._updateNestedIfChanged(
        params,
        this.transaction_events,
        key,
        'max_samples_per_minute'
      )
      break

    case 'transaction_events.enabled':
      this._updateNestedIfChanged(
        params,
        this.transaction_events,
        key,
        'enabled'
      ) ...
```
- example usage
```shell
...
   this.agent_enabled = false
   this.emit('agent_enabled', false)
   return
 }
 if (Object.keys(json).length === 0) return

 Object.keys(json).forEach(function cb_forEach(key) {
   this._fromServer(json, key)
 }, this)

 this.emit('change', this)
}

/**
* The guts of the logic about how to deal with server-side configuration.
...
```

#### <a name="apidoc.element.newrelic.config.prototype._fromSpecial"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_fromSpecial ()](#apidoc.element.newrelic.config.prototype._fromSpecial)
- description and source-code
```javascript
function _fromSpecial() {
  var name = this.app_name
  if (name === null || name === undefined || name === '' ||
      (Array.isArray(name) && name.length === 0)) {
    var azureName = process.env[AZURE_APP_NAME]
    if (azureName) this.app_name = azureName.split(',')
  }
}
```
- example usage
```shell
...
this.put_for_data_send = false                // Changes http verb for harvest


// 3. override defaults with values from the loaded / passed configuration
this._fromPassed(config)

// 3.5. special values (only Azure environment APP_POOL_ID for now)
this._fromSpecial()

// 4. override config with environment variables
this._fromEnvironment()

// 5. clean up anything that requires postprocessing
this._canonicalize()
...
```

#### <a name="apidoc.element.newrelic.config.prototype._updateIfChanged"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_updateIfChanged (json, key)](#apidoc.element.newrelic.config.prototype._updateIfChanged)
- description and source-code
```javascript
function _updateIfChanged(json, key) {
  this._updateNestedIfChanged(json, this, key, key)
}
```
- example usage
```shell
...

// setting these can be disabled by ignore_server_configuration
case 'ssl':
case 'apdex_t':
case 'web_transactions_apdex':
case 'data_report_period':
case 'ignored_params':
  this._updateIfChanged(params, key)
  break
case 'transaction_tracer.enabled':
  this._updateNestedIfChanged(
    params,
    this.transaction_tracer,
    'transaction_tracer.enabled',
    'enabled'
...
```

#### <a name="apidoc.element.newrelic.config.prototype._updateNestedIfChanged"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_updateNestedIfChanged (remote, local, remoteKey, localKey)](#apidoc.element.newrelic.config.prototype._updateNestedIfChanged)
- description and source-code
```javascript
function _updateNestedIfChanged(remote, local, remoteKey, localKey) {
  if (this.ignore_server_configuration) return this.logDisabled(remote, remoteKey)
  // if high-sec mode is enabled, we do not accept server changes to high-sec
  if (this.high_security && HIGH_SECURITY_KEYS.indexOf(localKey) !== -1) {
    return this.logDisabled(remote, remoteKey)
  }
  return this._updateNestedIfChangedRaw(remote, local, remoteKey, localKey)
}
```
- example usage
```shell
...
case 'application_id':
case 'trusted_account_ids':
  this._alwaysUpdateIfChanged(params, key)
  break

case 'collect_error_events':
  if (params.collect_error_events === false) {
    this._updateNestedIfChanged(
      params,
      this.error_collector,
      key,
      'capture_events'
    )
  }
  break
...
```

#### <a name="apidoc.element.newrelic.config.prototype._updateNestedIfChangedRaw"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>_updateNestedIfChangedRaw ( remote, local, remoteKey, localKey)](#apidoc.element.newrelic.config.prototype._updateNestedIfChangedRaw)
- description and source-code
```javascript
function _updateNestedIfChangedRaw( remote, local, remoteKey, localKey) {
  var value = remote[remoteKey]
  if (value !== null && value !== undefined && local[localKey] !== value) {
    if (Array.isArray(value) && Array.isArray(local[localKey])) {
      value.forEach(function cb_forEach(element) {
        if (local[localKey].indexOf(element) === -1) local[localKey].push(element)
      })
    } else {
      local[localKey] = value
    }
    this.emit(remoteKey, value)
    logger.debug("Configuration of %s was changed to %s by New Relic.", remoteKey, value)
  }
}
```
- example usage
```shell
...
// and the api.getRUMHeader() method
case 'js_agent_file':
case 'js_agent_loader_file':
case 'beacon':
case 'error_beacon':
case 'browser_key':
case 'js_agent_loader':
  this._updateNestedIfChangedRaw(
    params,
    this.browser_monitoring,
    key,
    key
  )
  break
...
```

#### <a name="apidoc.element.newrelic.config.prototype.applications"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>applications ()](#apidoc.element.newrelic.config.prototype.applications)
- description and source-code
```javascript
function applications() {
  var apps = this.app_name

  if (Array.isArray(apps) && apps.length > 0) {
    return apps
  }

  if (apps && typeof apps === 'string') {
    return [apps]
  }

  return []
}
```
- example usage
```shell
...
 *
 * The agent must be a singleton, or else module loading will be patched
 * multiple times, with undefined results. New Relic's instrumentation
 * can't be enabled or disabled without an application restart.
 */
var Agent = require('./lib/agent.js')
agent = new Agent(config)
var appNames = agent.config.applications()

if (config.logging.diagnostics) {
  logger.warn(
    'Diagnostics logging is enabled, this may cause significant overhead.'
  )
}
...
```

#### <a name="apidoc.element.newrelic.config.prototype.clearDisplayHostCache"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>clearDisplayHostCache ()](#apidoc.element.newrelic.config.prototype.clearDisplayHostCache)
- description and source-code
```javascript
function clearDisplayHostCache() {
  this.getDisplayHost = getDisplayHost
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.config.prototype.clearHostnameCache"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>clearHostnameCache ()](#apidoc.element.newrelic.config.prototype.clearHostnameCache)
- description and source-code
```javascript
function clearHostnameCache() {
  this.getHostnameSafe = getHostnameSafe
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.config.prototype.getDisplayHost"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>getDisplayHost ()](#apidoc.element.newrelic.config.prototype.getDisplayHost)
- description and source-code
```javascript
function getDisplayHost() {
  var _displayHost
  this.getDisplayHost = function getCachedDisplayHost() {
    return _displayHost
  }
  if (this.process_host.display_name === '') {
    _displayHost = this.getHostnameSafe()
    return _displayHost
  }
  var stringBuffer = new Buffer(this.process_host.display_name, 'utf8')
  var numBytes = stringBuffer.length

  if (numBytes > 255) {
    logger.warn('Custom host display name must be less than 255 bytes')
    _displayHost = this.getHostnameSafe()
    return _displayHost
  }

  _displayHost = this.process_host.display_name
  return _displayHost
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.config.prototype.getHostnameSafe"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>getHostnameSafe ()](#apidoc.element.newrelic.config.prototype.getHostnameSafe)
- description and source-code
```javascript
function getHostnameSafe() {
  var _hostname
  this.getHostnameSafe = function getCachedHostname() {
    return _hostname
  }
  try {
    _hostname = os.hostname()
    return _hostname
  } catch (e) {
    var addresses = this.getIPAddresses()

    if (this.process_host.ipv_preference === '6' && addresses.ipv6) {
      _hostname = addresses.ipv6
    } else if (addresses.ipv4) {
      logger.info('Defaulting to ipv4 address for host name')
      _hostname = addresses.ipv4
    } else if (addresses.ipv6) {
      logger.info('Defaulting to ipv6 address for host name')
      _hostname = addresses.ipv6
    } else {
      logger.info('No hostname, ipv4, or ipv6 address found for machine')
      _hostname = 'UNKNOWN_BOX'
    }

    return _hostname
  }
}
```
- example usage
```shell
...

function getDisplayHost() {
var _displayHost
this.getDisplayHost = function getCachedDisplayHost() {
  return _displayHost
}
if (this.process_host.display_name === '') {
  _displayHost = this.getHostnameSafe()
  return _displayHost
}
var stringBuffer = new Buffer(this.process_host.display_name, 'utf8')
var numBytes = stringBuffer.length

if (numBytes > 255) {
  logger.warn('Custom host display name must be less than 255 bytes')
...
```

#### <a name="apidoc.element.newrelic.config.prototype.getIPAddresses"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>getIPAddresses ()](#apidoc.element.newrelic.config.prototype.getIPAddresses)
- description and source-code
```javascript
function getIPAddresses() {
  var addresses = {}
  var interfaces = os.networkInterfaces()

  for (var interfaceKey in interfaces) {
    if (interfaceKey.match(/^lo/)) continue

    var interfaceDescriptions = interfaces[interfaceKey]
    for (var i = 0; i < interfaceDescriptions.length; i++) {
      var description = interfaceDescriptions[i]
      var family = description.family.toLowerCase()
      addresses[family] = description.address
    }
  }
  return addresses
}
```
- example usage
```shell
...
  this.getHostnameSafe = function getCachedHostname() {
return _hostname
  }
  try {
_hostname = os.hostname()
return _hostname
  } catch (e) {
var addresses = this.getIPAddresses()

if (this.process_host.ipv_preference === '6' && addresses.ipv6) {
  _hostname = addresses.ipv6
} else if (addresses.ipv4) {
  logger.info('Defaulting to ipv4 address for host name')
  _hostname = addresses.ipv4
} else if (addresses.ipv6) {
...
```

#### <a name="apidoc.element.newrelic.config.prototype.logDisabled"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>logDisabled (json, key)](#apidoc.element.newrelic.config.prototype.logDisabled)
- description and source-code
```javascript
function logDisabled(json, key) {
  var value = json[key]
  if (value !== null && value !== undefined) {
    logger.debug(
      "Server-side configuration of %s is currently disabled by local configuration. " +
      "(Server sent value of %s.)",
      key,
      value
    )
  }
}
```
- example usage
```shell
...
 * @param {object} local     A portion of this configuration object.
 * @param {string} remoteKey The name sent by New Relic.
 * @param {string} localKey  The local name.
 */
Config.prototype._updateNestedIfChanged = _updateNestedIfChanged

function _updateNestedIfChanged(remote, local, remoteKey, localKey) {
  if (this.ignore_server_configuration) return this.logDisabled(remote, remoteKey)
  // if high-sec mode is enabled, we do not accept server changes to high-sec
  if (this.high_security && HIGH_SECURITY_KEYS.indexOf(localKey) !== -1) {
    return this.logDisabled(remote, remoteKey)
  }
  return this._updateNestedIfChangedRaw(remote, local, remoteKey, localKey)
}
...
```

#### <a name="apidoc.element.newrelic.config.prototype.logUnknown"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>logUnknown (json, key)](#apidoc.element.newrelic.config.prototype.logUnknown)
- description and source-code
```javascript
function logUnknown(json, key) {
  var value = json[key]
  logger.debug(
    "New Relic sent unknown configuration parameter %s with value %s.",
    key,
    value
  )
}
```
- example usage
```shell
...
   case 'transaction_tracer.record_sql':
   case 'slow_sql.enabled':
   case 'rum.load_episodes_file':
     this.logUnsupported(params, key)
     break

   default:
     this.logUnknown(params, key)
 }
}

/**
* Change a value sent by the collector if and only if it's different from the
* value we already have. Emit an event with the key name and the new value,
* and log that the value has changed.
...
```

#### <a name="apidoc.element.newrelic.config.prototype.logUnsupported"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>logUnsupported (json, key)](#apidoc.element.newrelic.config.prototype.logUnsupported)
- description and source-code
```javascript
function logUnsupported(json, key) {
  var flavor
  if (this.ignore_server_configuration) {
    flavor = "ignored"
  } else {
    flavor = "not supported by the Node.js agent"
  }

  var value = json[key]
  if (value !== null && value !== undefined) {
    logger.debug(
      "Server-side configuration of %s is currently %s. (Server sent value of %s.)",
      key,
      flavor,
      value
    )
    this.emit(key, value)
  }
}
```
- example usage
```shell
...
    case 'sampling_rate':
    case 'episodes_file':
    case 'episodes_url':
    case 'cross_application_tracing':
    case 'transaction_tracer.record_sql':
    case 'slow_sql.enabled':
    case 'rum.load_episodes_file':
      this.logUnsupported(params, key)
      break

    default:
      this.logUnknown(params, key)
  }
}
...
```

#### <a name="apidoc.element.newrelic.config.prototype.measureInternal"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>measureInternal (suffix, duration)](#apidoc.element.newrelic.config.prototype.measureInternal)
- description and source-code
```javascript
function measureInternal(suffix, duration) {
  if (this.debug.supportability) {
    var internal = this.debug.supportability
    internal.measureMilliseconds(NAMES.SUPPORTABILITY.PREFIX + suffix, null, duration)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.config.prototype.onConnect"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>onConnect (json, recursion)](#apidoc.element.newrelic.config.prototype.onConnect)
- description and source-code
```javascript
function onConnect(json, recursion) {
  json = json || {}
  if (this.high_security === true && recursion !== true && json.high_security !== true) {
    this.agent_enabled = false
    this.emit('agent_enabled', false)
    return
  }
  if (Object.keys(json).length === 0) return

  Object.keys(json).forEach(function cb_forEach(key) {
    this._fromServer(json, key)
  }, this)

  this.emit('change', this)
}
```
- example usage
```shell
...
* decoupled.
*
* @param {object} configuration New config JSON from the collector.
*/
Agent.prototype.reconfigure = function reconfigure(configuration) {
 if (!configuration) throw new TypeError("must pass configuration")

 this.config.onConnect(configuration)
}

/**
* Make it easier to determine what state the agent thinks it's in (needed
* for a few tests, but fragile).
*
* FIXME: remove the need for this
...
```

#### <a name="apidoc.element.newrelic.config.prototype.publicSettings"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>publicSettings ()](#apidoc.element.newrelic.config.prototype.publicSettings)
- description and source-code
```javascript
function publicSettings() {
  var settings = {}

  for (var key in this) {
    if (this.hasOwnProperty(key)) {
      var item = this[key]

      if (REDACT_BEFORE_SEND.indexOf(key) > -1) {
        item = '****'
      }

      if (REMOVE_BEFORE_SEND.indexOf(key) === -1) {
        settings[key] = item
      }
    }
  }

  // Agent-side setting is 'enable', but collector-side setting is
  // 'auto_instrument'. Send both values up.
  settings.browser_monitoring.auto_instrument = settings.browser_monitoring.enable

  // Remove simple circular references
  parse(stringifySync(settings), function cb_parse(err, settingsCopy) {
    if (err === null) {
      settings = flatten({}, '', settingsCopy)
    } else {
      logger.warn('Error while creating deep copy: %s', err)
    }
  })

  return settings
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.config.prototype.setLogger"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>setLogger (bootstrapped)](#apidoc.element.newrelic.config.prototype.setLogger)
- description and source-code
```javascript
function setLogger(bootstrapped) {
  logger = bootstrapped
}
```
- example usage
```shell
...
          /* eslint-enable no-console */
        })
    }
    module.exports.pipe(stream)
  }

  // now tell the config module to switch to the real logger
  config.setLogger(module.exports)
}
...
```

#### <a name="apidoc.element.newrelic.config.prototype.validateFlags"></a>[function <span class="apidocSignatureSpan">newrelic.config.prototype.</span>validateFlags ()](#apidoc.element.newrelic.config.prototype.validateFlags)
- description and source-code
```javascript
function validateFlags() {
  Object.keys(this.feature_flag).forEach(function cb_forEach(key) {
    if (feature_flag.released.indexOf(key) > -1) {
      logger.warn('Feature flag ' + key + ' has been released')
    }
    if (feature_flag.unreleased.indexOf(key) > -1) {
      logger.warn('Feature flag ' + key + ' has been deprecated')
    }
  })
}
```
- example usage
```shell
...
  }

  try {
config = new Config(require(filepath).config)
config.config_file_path = filepath
logger.debug("Using configuration file %s.", filepath)

config.validateFlags()

return config
  } catch (error) {
logger.error(error)

throw new Error(
  "Unable to read configuration file " + filepath + ". A default\n" +
...
```



# <a name="apidoc.module.newrelic.environment"></a>[module newrelic.environment](#apidoc.module.newrelic.environment)

#### <a name="apidoc.element.newrelic.environment.clearDispatcher"></a>[function <span class="apidocSignatureSpan">newrelic.environment.</span>clearDispatcher ()](#apidoc.element.newrelic.environment.clearDispatcher)
- description and source-code
```javascript
function clearDispatcher() {
  clearSetting('Dispatcher')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.environment.clearFramework"></a>[function <span class="apidocSignatureSpan">newrelic.environment.</span>clearFramework ()](#apidoc.element.newrelic.environment.clearFramework)
- description and source-code
```javascript
function clearFramework() {
  clearSetting('Framework')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.environment.get"></a>[function <span class="apidocSignatureSpan">newrelic.environment.</span>get (name)](#apidoc.element.newrelic.environment.get)
- description and source-code
```javascript
function getSetting(name) {
  return settings[name] || []
}
```
- example usage
```shell
...
'''javascript
var newrelic = require('newrelic');
var app = require('express')();

// In Express, this lets you call newrelic from within a template.
app.locals.newrelic = newrelic;

app.get('/user/:id', function (req, res) {
  res.render('user');
});
app.listen(process.env.PORT);
'''

*layout.jade:*
...
```

#### <a name="apidoc.element.newrelic.environment.listPackages"></a>[function <span class="apidocSignatureSpan">newrelic.environment.</span>listPackages (root, packages)](#apidoc.element.newrelic.environment.listPackages)
- description and source-code
```javascript
function listPackages(root, packages) {
  if (!packages) {
    packages = []
  }

  try {
    fs.readdirSync(root).forEach(function forEachReadDirSync(dir) {
      // Skip npm's binary directory where it stores executables.
      if (dir === '.bin') {
        return
      }

      var version = null
      try {
        var pck = path.resolve(root, dir, 'package.json')
        version = JSON.parse(fs.readFileSync(pck)).version
      } catch (e) {
        logger.debug('Could not load %s for environment scan', pck || dir)
      }

      packages.push([dir, version || '<unknown>'])
    })
  } catch (e) {
    logger.trace(e, 'Failed to list packages in %s', root)
  }

  return packages
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.environment.refresh"></a>[function <span class="apidocSignatureSpan">newrelic.environment.</span>refresh ()](#apidoc.element.newrelic.environment.refresh)
- description and source-code
```javascript
function refresh() {
  // gather persisted settings
  var framework = getSetting('Framework')
  var dispatcher = getSetting('Dispatcher')
  var packages = getSetting('Packages')
  var dependencies = getSetting('Dependencies')

  // clearing and rebuilding a global variable
  settings = {}
  // add persisted settings
  if (framework.length) {
    framework.forEach(function addFrameworks(fw) {
      addSetting('Framework', fw)
    })
  }

  if (dispatcher.length) {
    dispatcher.forEach(function addDispatchers(d) {
      addSetting('Dispatcher', d)
    })
  }

  gatherEnv()
  remapConfigSettings()

  if (packages.length && dependencies.length) {
    settings.Packages = packages
    settings.Dependencies = dependencies
  } else {
    findPackages()
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.environment.setDispatcher"></a>[function <span class="apidocSignatureSpan">newrelic.environment.</span>setDispatcher (dispatcher)](#apidoc.element.newrelic.environment.setDispatcher)
- description and source-code
```javascript
function setDispatcher(dispatcher) {
  addSetting('Dispatcher', dispatcher)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.environment.setFramework"></a>[function <span class="apidocSignatureSpan">newrelic.environment.</span>setFramework (framework)](#apidoc.element.newrelic.environment.setFramework)
- description and source-code
```javascript
function setFramework(framework) {
  addSetting('Framework', framework)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.environment.toJSON"></a>[function <span class="apidocSignatureSpan">newrelic.environment.</span>toJSON ()](#apidoc.element.newrelic.environment.toJSON)
- description and source-code
```javascript
function toJSON() {
  // TODO:  Do not refresh when JSON-ifying. This takes a _long_ time and blocks
  //        the event loop. Currently, removing this causes a couple of tests to
  //        fail (ironically from timing out).
  refresh()
  var items = []
  Object.keys(settings).forEach(function settingKeysForEach(key) {
    settings[key].forEach(function settingsValuesForEach(setting) {
      items.push([key, setting])
    })
  })

  return items
}
```
- example usage
```shell
...
// Send uninstrumented supportability metrics every harvest cycle
uninstrumented.createMetrics(this.metrics)

this._processCustomEvents()
this._processErrorEvents()

// wait to check until all the standard stuff has been added
if (this.metrics.toJSON().length < 1) {
  logger.debug("No metrics to send.")
  return process.nextTick(callback)
}

var metrics = this.metrics
var beginSeconds = metrics.started * FROM_MILLIS
var endSeconds = Date.now() * FROM_MILLIS
...
```



# <a name="apidoc.module.newrelic.reservoir"></a>[module newrelic.reservoir](#apidoc.module.newrelic.reservoir)

#### <a name="apidoc.element.newrelic.reservoir.reservoir"></a>[function <span class="apidocSignatureSpan">newrelic.</span>reservoir (limit)](#apidoc.element.newrelic.reservoir.reservoir)
- description and source-code
```javascript
function Reservoir(limit) {
  this.limit = limit || 10
  this.seen = 0
  this._data = []
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.newrelic.reservoir.prototype"></a>[module newrelic.reservoir.prototype](#apidoc.module.newrelic.reservoir.prototype)

#### <a name="apidoc.element.newrelic.reservoir.prototype.add"></a>[function <span class="apidocSignatureSpan">newrelic.reservoir.prototype.</span>add (item)](#apidoc.element.newrelic.reservoir.prototype.add)
- description and source-code
```javascript
function add(item) {
  if (this.seen < this.limit) {
    this._data.push(item)
  } else {
    // Take a number between 0 and n + 1, drop the element at that index
    // from the array. If the element to drop is the (n + 1)th, the new item is
    // not added, otherwise the new item replaces the item that was
    // dropped.
    // This is effectively the same as adding the new element to the
    // end, swapping the last element (the new one) with a random element in the list,
    // then dropping the last element (the potentially swapped one) in the list.
    var toReplace = Math.floor(Math.random() * (this.seen + 2))
    if (toReplace < this.limit) this._data[toReplace] = item
  }
  this.seen++
}
```
- example usage
```shell
...
 }

 var instrinics = {
   type: eventType,
   timestamp: Date.now()
 }

 this.agent.customEvents.add([instrinics, attributes])
}

/**
* Shuts down the agent.
*
* @param {object}  [options]                           object with shut down options
* @param {boolean} [options.collectPendingData=false]  If true, the agent will send any
...
```

#### <a name="apidoc.element.newrelic.reservoir.prototype.merge"></a>[function <span class="apidocSignatureSpan">newrelic.reservoir.prototype.</span>merge (items)](#apidoc.element.newrelic.reservoir.prototype.merge)
- description and source-code
```javascript
function merge(items) {
  if (!items || !items.length) return
  if (items === this._data) return
  for (var i = 0; i < items.length; i++) {
    this.add(items[i])
  }
}
```
- example usage
```shell
...

if (typeof value.totalExclusive === 'number') {
  stats.totalExclusive = value.totalExclusive
} else {
  stats.totalExclusive = value.total
}

metric.merge(stats)
}

API.prototype.incrementMetric = function incrementMetric(name, value) {
var metric = this.agent.metrics.getOrCreateMetric(
  NAMES.SUPPORTABILITY.API + '/incrementMetric'
)
metric.incrementCallCount()
...
```

#### <a name="apidoc.element.newrelic.reservoir.prototype.overflow"></a>[function <span class="apidocSignatureSpan">newrelic.reservoir.prototype.</span>overflow ()](#apidoc.element.newrelic.reservoir.prototype.overflow)
- description and source-code
```javascript
function overflow() {
  var diff = this.seen - this.limit
  return diff >= 0 ? diff : 0
}
```
- example usage
```shell
...
  // Bail out if there are no events
  if (this.customEventsPool.length === 0) {
return
  }

  if (this.config.custom_insights_events.enabled) {
// Record their values
var diff = this.customEvents.overflow()
dropped.incrementCallCount(diff)
seen.incrementCallCount(this.customEvents.seen)
sent.incrementCallCount(this.customEvents.seen - diff)

// Log any warnings about dropping events
if (diff) {
  logger.warn('Dropped %s custom events out of %s.', diff, this.customEvents.seen)
...
```

#### <a name="apidoc.element.newrelic.reservoir.prototype.setLimit"></a>[function <span class="apidocSignatureSpan">newrelic.reservoir.prototype.</span>setLimit (newLimit)](#apidoc.element.newrelic.reservoir.prototype.setLimit)
- description and source-code
```javascript
function setLimit(newLimit) {
  this.limit = newLimit
  if (this._data.length > newLimit) {
    this._data = this._data.slice(0, newLimit)
  }
}
```
- example usage
```shell
...
 * Builds all of the sub-properties of the agent that rely on configurations.
 */
Agent.prototype.reset = function reset() {
// Insights events.
if (!this.events) {
  this.events = new Reservoir()
}
this.events.setLimit(this.config.transaction_events.max_samples_per_minute)
if (!this.customEvents) {
  this.customEvents = new Reservoir()
}
this.customEvents.setLimit(this.config.custom_insights_events.max_samples_stored)

// Error tracing.
if (!this.errors) {
...
```

#### <a name="apidoc.element.newrelic.reservoir.prototype.toArray"></a>[function <span class="apidocSignatureSpan">newrelic.reservoir.prototype.</span>toArray ()](#apidoc.element.newrelic.reservoir.prototype.toArray)
- description and source-code
```javascript
function toArray() {
  return this._data
}
```
- example usage
```shell
...
/**
 * This function takes the custom events reservoir, gets stats on it for
 * metric purposes, then instantiates a new custom events reservoir. This is
 * so the stats are consistent with what actually gets pushed by the later
 * call to _sendCustomEvents.
 */
Agent.prototype._processCustomEvents = function _processCustomEvents() {
this.customEventsPool = this.customEvents.toArray()

// Create the metrics so they are at least set to 0
var dropped = this.metrics.getOrCreateMetric(NAMES.CUSTOM_EVENTS.DROPPED)
var seen = this.metrics.getOrCreateMetric(NAMES.CUSTOM_EVENTS.SEEN)
var sent = this.metrics.getOrCreateMetric(NAMES.CUSTOM_EVENTS.SENT)

// Bail out if there are no events
...
```



# <a name="apidoc.module.newrelic.sampler"></a>[module newrelic.sampler](#apidoc.module.newrelic.sampler)

#### <a name="apidoc.element.newrelic.sampler.checkEvents"></a>[function <span class="apidocSignatureSpan">newrelic.sampler.</span>checkEvents (agent)](#apidoc.element.newrelic.sampler.checkEvents)
- description and source-code
```javascript
function checkEvents(agent) {
  return function eventSampler() {
    var timer = new Timer()
    timer.begin()
    setTimeout(recordQueueTime.bind(null, agent, timer), 0)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.sampler.sampleCpu"></a>[function <span class="apidocSignatureSpan">newrelic.sampler.</span>sampleCpu (agent)](#apidoc.element.newrelic.sampler.sampleCpu)
- description and source-code
```javascript
function sampleCpu(agent) {
  var lastSample
  var recordCPU = generateCPUMetricRecorder(agent)
  return function cpuSampler() {
    var cpuSample = getCpuSample(lastSample)
    lastSample = getCpuSample()

    if (lastSample == null) {
      return
    }

    recordCPU(cpuSample.user / MICROS, cpuSample.system / MICROS)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.sampler.sampleGc"></a>[function <span class="apidocSignatureSpan">newrelic.sampler.</span>sampleGc (agent, nativeMetrics)](#apidoc.element.newrelic.sampler.sampleGc)
- description and source-code
```javascript
function sampleGc(agent, nativeMetrics) {
  // Hook into the stats event to accumulate total pause time and record per-run
  // pause time metric.
  nativeMetrics.on('gc', function onGCStatsEvent(stats) {
    var duration = stats.duration / NANOS
    recordValue(agent, NAMES.GC.PAUSE_TIME, duration)

    if (stats.type) {
      recordValue(agent, NAMES.GC.PREFIX + stats.type, duration)
    } else {
      logger.debug(stats, 'Unknown GC type %j', stats.typeId)
    }
  })

  return function gcSampler() {
    // NOOP?
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.sampler.sampleLoop"></a>[function <span class="apidocSignatureSpan">newrelic.sampler.</span>sampleLoop (agent, nativeMetrics)](#apidoc.element.newrelic.sampler.sampleLoop)
- description and source-code
```javascript
function sampleLoop(agent, nativeMetrics) {
  return function loopSampler() {
    var loopMetrics = nativeMetrics.getLoopMetrics()

    // convert from microseconds to seconds
    loopMetrics.usage.min = loopMetrics.usage.min / MICROS
    loopMetrics.usage.max = loopMetrics.usage.max / MICROS
    loopMetrics.usage.total = loopMetrics.usage.total / MICROS
    loopMetrics.usage.sumOfSquares = loopMetrics.usage.sumOfSquares / (MICROS * MICROS)

    recordCompleteMetric(agent, NAMES.LOOP.USAGE, loopMetrics.usage)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.sampler.sampleMemory"></a>[function <span class="apidocSignatureSpan">newrelic.sampler.</span>sampleMemory (agent)](#apidoc.element.newrelic.sampler.sampleMemory)
- description and source-code
```javascript
function sampleMemory(agent) {
  return function memorySampler() {
    try {
      var mem = process.memoryUsage()
      agent.metrics.measureBytes(NAMES.MEMORY.PHYSICAL, mem.rss)
      agent.metrics.measureBytes(NAMES.MEMORY.USED_HEAP, mem.heapUsed)
      agent.metrics.measureBytes(NAMES.MEMORY.MAX_HEAP, mem.heapTotal)
      agent.metrics.measureBytes(NAMES.MEMORY.FREE_HEAP, mem.heapTotal - mem.heapUsed)
      agent.metrics.measureBytes(NAMES.MEMORY.USED_NONHEAP, mem.rss - mem.heapTotal)
      logger.trace('Recorded memory:', mem)
    } catch (e) {
      logger.debug('Could not record memory usage', e)
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.sampler.start"></a>[function <span class="apidocSignatureSpan">newrelic.sampler.</span>start (agent)](#apidoc.element.newrelic.sampler.start)
- description and source-code
```javascript
function start(agent) {
  samplers.push(new Sampler(sampleMemory(agent), 5 * MILLIS))
  samplers.push(new Sampler(checkEvents(agent), SAMPLE_INTERVAL))
  var metricFeatureFlag = agent.config.feature_flag.native_metrics

  // This requires a native module which may have failed to build.
  if (!this.nativeMetrics) {
    if (metricFeatureFlag) {
      try {
        this.nativeMetrics = require('@newrelic/native-metrics')({
          timeout: SAMPLE_INTERVAL
        })
      } catch (err) {
        logger.info(
          {error: {message: err.message, stack: err.stack}},
          'Not adding native metric sampler.'
        )
        agent.metrics.getOrCreateMetric(
          NAMES.SUPPORTABILITY.DEPENDENCIES + '/NoNativeMetricsModule'
        ).incrementCallCount()
      }
    } else {
      logger.info('Feature flag for native metrics is false')
    }
  }

  if (this.nativeMetrics) {
    if (!this.nativeMetrics.bound) {
      this.nativeMetrics.bind(SAMPLE_INTERVAL)
    }

    // Add GC events if available.
    if (this.nativeMetrics.gcEnabled) {
      samplers.push(new Sampler(sampleGc(agent, this.nativeMetrics), SAMPLE_INTERVAL))
    }

    // Add loop metrics if available.
    if (this.nativeMetrics.loopEnabled) {
      samplers.push(new Sampler(sampleLoop(agent, this.nativeMetrics), SAMPLE_INTERVAL))
    }
  }

  // Add CPU sampling using the built-in data if available, otherwise pulling
  // from the native module.
  if (process.cpuUsage) { // introduced in 6.1.0
    samplers.push(new Sampler(sampleCpu(agent), SAMPLE_INTERVAL))
  } else if (this.nativeMetrics && this.nativeMetrics.usageEnabled) {
    samplers.push(
      new Sampler(sampleCpuNative(agent, this.nativeMetrics), SAMPLE_INTERVAL)
    )
  } else {
    logger.debug('Not adding CPU metric sampler.')
  }

  sampler.state = 'running'
}
```
- example usage
```shell
...
throw new Error(message)
      }

      var shimmer = require('./lib/shimmer.js')
      shimmer.patchModule(agent)
      shimmer.bootstrapInstrumentation(agent)

      agent.start(function cb_start(error) {
if (!error) {
  return logger.debug("New Relic for Node.js is connected to New Relic.")
}

var errorMessage = "New Relic for Node.js halted startup due to an error:"
logger.error(error, errorMessage)
...
```

#### <a name="apidoc.element.newrelic.sampler.stop"></a>[function <span class="apidocSignatureSpan">newrelic.sampler.</span>stop ()](#apidoc.element.newrelic.sampler.stop)
- description and source-code
```javascript
function stop() {
  samplers.forEach(function forEachSampler(s) {
    s.stop()
  })
  samplers = []
  sampler.state = 'stopped'
  if (this.nativeMetrics) {
    this.nativeMetrics.unbind()
    this.nativeMetrics.removeAllListeners()

    // Setting this.nativeMetrics to null allows us to config a new
    // nativeMetrics object after the first start call.
    this.nativeMetrics = null
  }
}
```
- example usage
```shell
...
function cb_harvest(error) {
  if (error) {
    logger.error(
      error,
      'An error occurred while running last harvest before shutdown.'
    )
  }
  agent.stop(callback)
}

if (options && options.collectPendingData && agent._state !== 'started') {
  if (typeof options.timeout === 'number') {
    var shutdownTimeout = setTimeout(function shutdownTimeout() {
      agent.stop(callback)
    }, options.timeout)
...
```



# <a name="apidoc.module.newrelic.shimmer"></a>[module newrelic.shimmer](#apidoc.module.newrelic.shimmer)

#### <a name="apidoc.element.newrelic.shimmer.bootstrapInstrumentation"></a>[function <span class="apidocSignatureSpan">newrelic.shimmer.</span>bootstrapInstrumentation (agent)](#apidoc.element.newrelic.shimmer.bootstrapInstrumentation)
- description and source-code
```javascript
function bootstrapInstrumentation(agent) {
  var globalsFilepath = path.join(__dirname, 'instrumentation', 'core', 'globals.js')
  instrument(agent, 'globals', globalsFilepath, global)

  Object.keys(CORE_INSTRUMENTATION).forEach(function cb_forEach(mojule) {
    var filename = CORE_INSTRUMENTATION[mojule]
    var filepath = path.join(__dirname, 'instrumentation/core', filename)
    var uninstrumented

    try {
      uninstrumented = require(mojule)
    } catch (err) {
      logger.trace(
        'Could not load core module %s got error %s',
        mojule,
        err
      )
    }

    instrument(agent, filename, filepath, uninstrumented, mojule)
  })
}
```
- example usage
```shell
...
          "NEW_RELIC_APP_NAME. Not starting!"
logger.error(message)
throw new Error(message)
      }

      var shimmer = require('./lib/shimmer.js')
      shimmer.patchModule(agent)
      shimmer.bootstrapInstrumentation(agent)

      agent.start(function cb_start(error) {
if (!error) {
  return logger.debug("New Relic for Node.js is connected to New Relic.")
}

var errorMessage = "New Relic for Node.js halted startup due to an error:"
...
```

#### <a name="apidoc.element.newrelic.shimmer.isWrapped"></a>[function <span class="apidocSignatureSpan">newrelic.shimmer.</span>isWrapped (fn)](#apidoc.element.newrelic.shimmer.isWrapped)
- description and source-code
```javascript
function isWrapped(fn) {
  return !!(fn && fn.__NR_original)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.shimmer.patchModule"></a>[function <span class="apidocSignatureSpan">newrelic.shimmer.</span>patchModule (agent)](#apidoc.element.newrelic.shimmer.patchModule)
- description and source-code
```javascript
function patchModule(agent) {
  logger.trace("Wrapping module loader.")
  var Module = require('module')

  shimmer.wrapMethod(Module, 'Module', '_load', function cb_wrapMethod(load) {
    return function cls_wrapMethod(file) {
      return _postLoad(agent, load.apply(this, arguments), file)
    }
  })
}
```
- example usage
```shell
...
            "Set app_name in your newrelic.js file or set environment variable\n" +
            "NEW_RELIC_APP_NAME. Not starting!"
  logger.error(message)
  throw new Error(message)
}

var shimmer = require('./lib/shimmer.js')
shimmer.patchModule(agent)
shimmer.bootstrapInstrumentation(agent)

agent.start(function cb_start(error) {
  if (!error) {
    return logger.debug("New Relic for Node.js is connected to New Relic.")
  }
...
```

#### <a name="apidoc.element.newrelic.shimmer.reinstrument"></a>[function <span class="apidocSignatureSpan">newrelic.shimmer.</span>reinstrument (agent, modulePath)](#apidoc.element.newrelic.shimmer.reinstrument)
- description and source-code
```javascript
function reinstrument(agent, modulePath) {
  return _postLoad(agent, require(modulePath), modulePath)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.shimmer.unpatchModule"></a>[function <span class="apidocSignatureSpan">newrelic.shimmer.</span>unpatchModule ()](#apidoc.element.newrelic.shimmer.unpatchModule)
- description and source-code
```javascript
function unpatchModule() {
  logger.trace("Unwrapping to previous module loader.")
  var Module = require('module')

  shimmer.unwrapMethod(Module, 'Module', '_load')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.shimmer.unwrapAll"></a>[function <span class="apidocSignatureSpan">newrelic.shimmer.</span>unwrapAll ()](#apidoc.element.newrelic.shimmer.unwrapAll)
- description and source-code
```javascript
function unwrapAll() {
  instrumented.forEach(function cb_forEach(wrapper) {
    wrapper.__NR_unwrap()
  })
  instrumented = []
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.shimmer.unwrapMethod"></a>[function <span class="apidocSignatureSpan">newrelic.shimmer.</span>unwrapMethod (nodule, noduleName, method)](#apidoc.element.newrelic.shimmer.unwrapMethod)
- description and source-code
```javascript
function unwrapMethod(nodule, noduleName, method) {
  if (!noduleName) noduleName = '[unknown]'
  if (!method) return logger.debug("Must include a method name to unwrap. " +
                                   "Called from: %s", new Error().stack)

  var fqmn = noduleName + '.' + method

  if (!nodule) return logger.debug("Can't unwrap %s from nonexistent object.",
                                   fqmn)
  var wrapped = nodule[method]

  // keep instrumented up to date
  var pos = instrumented.indexOf(wrapped)
  if (pos !== -1) instrumented.splice(pos, 1)

  if (!wrapped) return logger.debug("%s not defined, so not unwrapping.", fqmn)
  if (!wrapped.__NR_unwrap) return logger.debug("%s isn't unwrappable.", fqmn)

  wrapped.__NR_unwrap()
}
```
- example usage
```shell
...
})
  },

  unpatchModule: function unpatchModule() {
logger.trace("Unwrapping to previous module loader.")
var Module = require('module')

shimmer.unwrapMethod(Module, 'Module', '_load')
  },

  bootstrapInstrumentation: function bootstrapInstrumentation(agent) {
var globalsFilepath = path.join(__dirname, 'instrumentation', 'core', 'globals.js')
instrument(agent, 'globals', globalsFilepath, global)

Object.keys(CORE_INSTRUMENTATION).forEach(function cb_forEach(mojule) {
...
```

#### <a name="apidoc.element.newrelic.shimmer.wrapDeprecated"></a>[function <span class="apidocSignatureSpan">newrelic.shimmer.</span>wrapDeprecated (nodule, noduleName, property, options)](#apidoc.element.newrelic.shimmer.wrapDeprecated)
- description and source-code
```javascript
function wrapDeprecated(nodule, noduleName, property, options) {
  if (!property) {
    logger.warn(new Error(), "Must include a function name to wrap. Called from:")
    return
  }

  if (!noduleName) noduleName = '[unknown]'

  var fqmn = noduleName + '.' + property
  if (!nodule) {
    logger.debug("Can't wrap %s from nonexistent object.", fqmn)
    return
  }

  var original = nodule[property]
  if (!original) {
    logger.trace("%s not defined, so not wrapping.", fqmn)
    return
  }

  delete nodule[property]

  var descriptor = {
    configurable: true,
    enumerable: true
  }
  if (options.get) descriptor.get = options.get
  if (options.set) descriptor.set = options.set
  Object.defineProperty(nodule, property, descriptor)
  logger.trace("Instrumented %s.", fqmn)

  if (shimmer.debug) {
    instrumented.push({
      __NR_unwrap: function unwrapDeprecated() {
        delete nodule[property]
        nodule[property] = original
      }
    })
  }

  return original
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.shimmer.wrapMethod"></a>[function <span class="apidocSignatureSpan">newrelic.shimmer.</span>wrapMethod (nodule, noduleName, methods, wrapper)](#apidoc.element.newrelic.shimmer.wrapMethod)
- description and source-code
```javascript
function wrapMethod(nodule, noduleName, methods, wrapper) {
  if (!methods) {
    return logger.warn(new Error(),
                       "Must include a method name to wrap. Called from:")
  }

  if (!noduleName) noduleName = '[unknown]'
  if (!Array.isArray(methods)) methods = [methods]

  methods.forEach(function cb_forEach(method) {
    var fqmn = noduleName + '.' + method

    if (!nodule) return logger.debug("Can't wrap %s from nonexistent object.",
                                     fqmn)
    if (!wrapper) return logger.debug("Can't wrap %s without a wrapper generator.",
                                      fqmn)

    var original = nodule[method]

    if (!original) return logger.trace("%s not defined, so not wrapping.", fqmn)
    if (original.__NR_unwrap) return logger.debug("%s already wrapped by agent.", fqmn)

    var wrapped = wrapper(original, method)
    wrapped.__NR_original = original
    wrapped.__NR_unwrap = function __NR_unwrap() {
      nodule[method] = original
      logger.trace("Removed instrumentation from %s.", fqmn)
    }

    nodule[method] = wrapped
    if (shimmer.debug) instrumented.push(wrapped)
    logger.trace("Instrumented %s.", fqmn)
  })
}
```
- example usage
```shell
...
 * Patch the module.load function so that we see modules loading and
 * have an opportunity to patch them with instrumentation.
 */
patchModule: function patchModule(agent) {
  logger.trace("Wrapping module loader.")
  var Module = require('module')

  shimmer.wrapMethod(Module, 'Module', '_load', function cb_wrapMethod(load) {
    return function cls_wrapMethod(file) {
      return _postLoad(agent, load.apply(this, arguments), file)
    }
  })
},

unpatchModule: function unpatchModule() {
...
```



# <a name="apidoc.module.newrelic.stub_api"></a>[module newrelic.stub_api](#apidoc.module.newrelic.stub_api)

#### <a name="apidoc.element.newrelic.stub_api.stub_api"></a>[function <span class="apidocSignatureSpan">newrelic.</span>stub_api ()](#apidoc.element.newrelic.stub_api.stub_api)
- description and source-code
```javascript
function Stub() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.newrelic.stub_api.prototype"></a>[module newrelic.stub_api.prototype](#apidoc.module.newrelic.stub_api.prototype)

#### <a name="apidoc.element.newrelic.stub_api.prototype.addCustomParameter"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>addCustomParameter ()](#apidoc.element.newrelic.stub_api.prototype.addCustomParameter)
- description and source-code
```javascript
function addCustomParameter() {logger.debug('Not calling addCustomParameter because New Relic is disabled.');}
```
- example usage
```shell
...

Programmatic version of 'rules.ignore' above. Ignoring rules can not be removed
until the Node process is restarted. They can also be added via the module's
configuration. The pattern is mandatory.

### Other API calls

#### newrelic.addCustomParameter(name, value)

Set a custom parameter value to be attached to a transaction trace and/or error
in the New Relic UI. This must be called within the context of a transaction,
so it has a place to set the custom parameters.

#### newrelic.addCustomParameters(params)
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.addCustomParameters"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>addCustomParameters ()](#apidoc.element.newrelic.stub_api.prototype.addCustomParameters)
- description and source-code
```javascript
function addCustomParameters() {logger.debug('Not calling addCustomParameters because New Relic is disabled.');}
```
- example usage
```shell
...

#### newrelic.addCustomParameter(name, value)

Set a custom parameter value to be attached to a transaction trace and/or error
in the New Relic UI. This must be called within the context of a transaction,
so it has a place to set the custom parameters.

#### newrelic.addCustomParameters(params)

Set multiple custom parameter values to be attached to a transaction trace and/or
error in the New Relic UI. This must be called within the context of a transaction,
so it has a place to set the custom parameters.

Example of setting multiple custom parameters at once:
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.addIgnoringRule"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>addIgnoringRule ()](#apidoc.element.newrelic.stub_api.prototype.addIgnoringRule)
- description and source-code
```javascript
function addIgnoringRule() {logger.debug('Not calling addIgnoringRule because New Relic is disabled.');}
```
- example usage
```shell
...

#### newrelic.addNamingRule(pattern, name)

Programmatic version of 'rules.name' above. Naming rules can not be removed
until the Node process is restarted. They can also be added via the module's
configuration. Both parameters are mandatory.

#### newrelic.addIgnoringRule(pattern)

Programmatic version of 'rules.ignore' above. Ignoring rules can not be removed
until the Node process is restarted. They can also be added via the module's
configuration. The pattern is mandatory.

### Other API calls
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.addNamingRule"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>addNamingRule ()](#apidoc.element.newrelic.stub_api.prototype.addNamingRule)
- description and source-code
```javascript
function addNamingRule() {logger.debug('Not calling addNamingRule because New Relic is disabled.');}
```
- example usage
```shell
...
Can also be set via the environment variable 'NEW_RELIC_IGNORING_RULES', with
multiple rules passed in as a list of comma-delimited patterns:
'NEW_RELIC_IGNORING_RULES='^/socket\.io/\*/xhr-polling,ignore_me'' Note that
currently there is no way to escape commas in patterns.

### API for adding naming and ignoring rules

#### newrelic.addNamingRule(pattern, name)

Programmatic version of 'rules.name' above. Naming rules can not be removed
until the Node process is restarted. They can also be added via the module's
configuration. Both parameters are mandatory.

#### newrelic.addIgnoringRule(pattern)
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.createBackgroundTransaction"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>createBackgroundTransaction (name, group, callback)](#apidoc.element.newrelic.stub_api.prototype.createBackgroundTransaction)
- description and source-code
```javascript
function createBackgroundTransaction(name, group, callback) {
  logger.debug('Not calling createBackgroundTransaction because New Relic is disabled.')
  return (callback === undefined) ? group : callback
}
```
- example usage
```shell
...
independent transaction and any calls within the 'handle' will be bound to the
new web transaction.

Custom transactions **must** be ended manually by calling 'endTransaction()'.
Timing for custom transaction starts from when the returned wrapped function is
called until 'endTransaction()' is called.

#### newrelic.createBackgroundTransaction(name, [group], handle)

'name' is the name of the job. It should be pretty static, and not include job
ids or anything very specific to that run of the job. 'group' is optional, and
allows you to group types of jobs together. This should follow similar rules as
the 'name'. 'handle' is a function that encompases your background job. Both
custom and auto instrumentation will be captured as part of the transaction.
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.createTracer"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>createTracer (name, callback)](#apidoc.element.newrelic.stub_api.prototype.createTracer)
- description and source-code
```javascript
function createTracer(name, callback) {
  logger.debug('Not calling createTracer because New Relic is disabled.')
  return callback
}
```
- example usage
```shell
...
called until 'endTransaction()' is called.

#### newrelic.endTransaction()

This takes no arguments and must be called to end any custom transaction. It
will detect what kind of transaction was active and end it.

#### newrelic.createTracer(name, handle)

'name' is the name of the tracer. It will show up as a segment in your
transaction traces and create its own metric. 'handle' is the function to be
bound to the tracer.

Timing is from when 'createTracer' is called until the 'handle' done executing.
This should be called inside of a transaction to get data. If it is called
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.createWebTransaction"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>createWebTransaction (url, callback)](#apidoc.element.newrelic.stub_api.prototype.createWebTransaction)
- description and source-code
```javascript
function createWebTransaction(url, callback) {
  logger.debug('Not calling createWebTransaction because New Relic is disabled.')
  return callback
}
```
- example usage
```shell
...
varieties of socket servers, and background jobs. These are things that the
agent can't automatically instrument because without your knowledge of your
application, the agent can't tell when they should begin and end.

Read more at:
https://docs.newrelic.com/docs/agents/nodejs-agent/supported-features/nodejs-custom-instrumentation

#### newrelic.createWebTransaction(url, handle)

'url' is the name of the web transaction. It should be pretty static, not
including anything like user ids or any other data that is very specific to the
request. 'handle' is the function you'd like to wrap in the web transaction.
Both custom and auto instrumentation will be captured as part of the
transaction.
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.endTransaction"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>endTransaction ()](#apidoc.element.newrelic.stub_api.prototype.endTransaction)
- description and source-code
```javascript
function endTransaction() {logger.debug('Not calling endTransaction because New Relic is disabled.');}
```
- example usage
```shell
...
transaction and any calls within the 'handle' will be bound to the new,
independent background transaction.

Custom transactions **must** be ended manually by calling 'endTransaction()'.
Timing for custom transaction starts from when the returned wrapped function is
called until 'endTransaction()' is called.

#### newrelic.endTransaction()

This takes no arguments and must be called to end any custom transaction. It
will detect what kind of transaction was active and end it.

#### newrelic.createTracer(name, handle)

'name' is the name of the tracer. It will show up as a segment in your
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.getBrowserTimingHeader"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>getBrowserTimingHeader ()](#apidoc.element.newrelic.stub_api.prototype.getBrowserTimingHeader)
- description and source-code
```javascript
function getBrowserTimingHeader() {
  logger.debug('Not calling getBrowserTimingHeader because New Relic is disabled.')
  return ''
}
```
- example usage
```shell
...
times.

Headers must be manually injected, but no extra configuration is necessary to
enable browser timings.

### Basics

- Insert the result of 'newrelic.getBrowserTimingHeader()'
into your html page.
- The browser timing headers should be placed in the beginning of your '<head>' tag.
  - As an exception to the above, for maximum IE compatability, the results of 'getBrowserTimingHeader()'
should be placed *after* any 'X-UA-COMPATIBLE HTTP-EQUIV' meta tags.
- Do *not* cache the header, call it once for every request.

### Example
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.incrementMetric"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>incrementMetric ()](#apidoc.element.newrelic.stub_api.prototype.incrementMetric)
- description and source-code
```javascript
function incrementMetric() {logger.debug('Not calling incrementMetric because New Relic is disabled.');}
```
- example usage
```shell
...
'Custom/' typically followed by segments for 'category' and 'label'.
(eg.'Custom/my_category/my_label').
'value' is either a numerical value to associate with the metric sample,
or an object representing multiple samples for the metric. If 'value' is
an object, it must include keys for 'count', 'total', 'min', 'max', and
'sumOfSquares'.

#### newrelic.incrementMetric(name[, amount])

'name' is the metric name to record, it must be a string that beings with
'Custom/' typically followed by segments for 'category' and 'label'.
(eg.'Custom/my_category/my_label').
'amount' is optional, but must be an integer if provided.  'amount' is
the number of times to increment the metrics 'count', it defaults to 1.
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.noticeError"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>noticeError ()](#apidoc.element.newrelic.stub_api.prototype.noticeError)
- description and source-code
```javascript
function noticeError() {logger.debug('Not calling noticeError because New Relic is disabled.');}
```
- example usage
```shell
...
Allows you to explicitly filter out long-polling routes or requests you know
are going to be time-consuming in an uninteresting way, and also allows you
to gather metrics for requests that would otherwise be ignored. Note that
to prevent a transaction from being ignored with this function, you **must**
pass 'false' as the parameter – in this case 'null' or 'undefined' will be
ignored.

#### newrelic.noticeError(error, customParameters)

If your app is doing its own error handling with domains or try/catch clauses,
but you want all of the information about how many errors are coming out of the
app to be centrally managed, use this call. Unlike most of the calls here, this
function can be used outside of route handlers, but will have additional
context if called from within transaction scope. If custom parameters are
passed in on an object literal, they will be passed back to New Relic for
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.recordCustomEvent"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>recordCustomEvent ()](#apidoc.element.newrelic.stub_api.prototype.recordCustomEvent)
- description and source-code
```javascript
function recordCustomEvent() {logger.debug('Not calling recordCustomEvent because New Relic is disabled.');}
```
- example usage
```shell
...
},

/**
 * Custom Insights Events
 *
 * Custom insights events are JSON object that are sent to New Relic
 * Insights. You can tell the agent to send your custom events via the
 * 'newrelic.recordCustomEvent()' API. These events are sampled once the max
 * reservoir size is reached. You can tune this setting below.
 *
 * Read more here: http://newrelic.com/insights
 */
custom_insights_events: {
  /**
   * If this is disabled, the agent does not collect, nor try to send, custom
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.recordMetric"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>recordMetric ()](#apidoc.element.newrelic.stub_api.prototype.recordMetric)
- description and source-code
```javascript
function recordMetric() {logger.debug('Not calling recordMetric because New Relic is disabled.');}
```
- example usage
```shell
...
transaction traces and create its own metric. 'handle' is the function to be
bound to the tracer.

Timing is from when 'createTracer' is called until the 'handle' done executing.
This should be called inside of a transaction to get data. If it is called
outside of a transaction it will just pass through.

#### newrelic.recordMetric(name, value)

'name' is the metric name to record, it must be a string that begins with
'Custom/' typically followed by segments for 'category' and 'label'.
(eg.'Custom/my_category/my_label').
'value' is either a numerical value to associate with the metric sample,
or an object representing multiple samples for the metric. If 'value' is
an object, it must include keys for 'count', 'total', 'min', 'max', and
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.setControllerName"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>setControllerName ()](#apidoc.element.newrelic.stub_api.prototype.setControllerName)
- description and source-code
```javascript
function setControllerName() {logger.debug('Not calling setControllerName because New Relic is disabled.');}
```
- example usage
```shell
...
Name the current request. You can call this function anywhere within the
context of an HTTP request handler, at any time after handling of the request
has started, but before the request has finished. A good rule of thumb is that
if the request and response objects are in scope, you can set the name.

Explicitly calling 'newrelic.setTransactionName()' will override any names set
by Express, Restify or Hapi routes. Calls to 'newrelic.setTransactionName()' and
'newrelic.setControllerName()' will overwrite each other. The last call made
before the request ends wins.

**VERY IMPORTANT NOTE:** Do not include highly variable information like GUIDs,
numerical IDs, or timestamps in the request names you create. If your request
is slow enough to generate a transaction trace, that trace will contain the
original URL. If you enable parameter capture, the parameters will also be
attached to the trace. The request names are used to group requests for New
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.setIgnoreTransaction"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>setIgnoreTransaction ()](#apidoc.element.newrelic.stub_api.prototype.setIgnoreTransaction)
- description and source-code
```javascript
function setIgnoreTransaction() {logger.debug('Not calling setIgnoreTransaction because New Relic is disabled.');}
```
- example usage
```shell
...

Example of setting multiple custom parameters at once:

'''javascript
newrelic.addCustomParameters({test: 'value', test2: 'value2'});
'''

#### newrelic.setIgnoreTransaction(ignored)

Tell the module explicitly whether or not a given request should be ignored.
Allows you to explicitly filter out long-polling routes or requests you know
are going to be time-consuming in an uninteresting way, and also allows you
to gather metrics for requests that would otherwise be ignored. Note that
to prevent a transaction from being ignored with this function, you **must**
pass 'false' as the parameter – in this case 'null' or 'undefined' will be
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.setTransactionName"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>setTransactionName ()](#apidoc.element.newrelic.stub_api.prototype.setTransactionName)
- description and source-code
```javascript
function setTransactionName() {logger.debug('Not calling setTransactionName because New Relic is disabled.');}
```
- example usage
```shell
...

is all you need. Please note that you still need to ensure that loading the New
Relic module is the first thing your application does, as it needs to bootstrap
itself before the rest of your application loads, but you can safely require
the module from multiple modules in your application – it will only initialize
itself once.

#### newrelic.setTransactionName(name)

Name the current request. You can call this function anywhere within the
context of an HTTP request handler, at any time after handling of the request
has started, but before the request has finished. A good rule of thumb is that
if the request and response objects are in scope, you can set the name.

Explicitly calling 'newrelic.setTransactionName()' will override any names set
...
```

#### <a name="apidoc.element.newrelic.stub_api.prototype.shutdown"></a>[function <span class="apidocSignatureSpan">newrelic.stub_api.prototype.</span>shutdown (options, cb)](#apidoc.element.newrelic.stub_api.prototype.shutdown)
- description and source-code
```javascript
function shutdown(options, cb) {
  logger.debug('Not calling shutdown because New Relic is disabled.')

  var callback = cb
  if (!callback) {
    if (typeof options === 'function') {
      callback = options
    } else {
      callback = new Function()
    }
  }

  process.nextTick(callback)
}
```
- example usage
```shell
...
but you want all of the information about how many errors are coming out of the
app to be centrally managed, use this call. Unlike most of the calls here, this
function can be used outside of route handlers, but will have additional
context if called from within transaction scope. If custom parameters are
passed in on an object literal, they will be passed back to New Relic for
display.

#### newrelic.shutdown([options], callback)

Use this method to gracefully shut down the agent.  When called with
'options.collectPendingData' set to true, the agent will send any pending data to
the New Relic servers before shutting down.  This is useful when you want to shut down
the Node process and make sure that all transactions and/or errors are captured by
New Relic.
...
```



# <a name="apidoc.module.newrelic.system_info"></a>[module newrelic.system_info](#apidoc.module.newrelic.system_info)

#### <a name="apidoc.element.newrelic.system_info.system_info"></a>[function <span class="apidocSignatureSpan">newrelic.</span>system_info (agent, callback)](#apidoc.element.newrelic.system_info.system_info)
- description and source-code
```javascript
function fetchSystemInfo(agent, callback) {
  var config = agent.config
  var systemInfo = {
    processorArch: os.arch()
  }

  var utilizationConfig = {}
  if (config.utilization) {
    var configProcessors = config.utilization.logical_processors
    var configRam = config.utilization.total_ram_mib
    var configHostname = config.utilization.billing_hostname

    if (configProcessors) {
      var parsedConfigProcessors = parseFloat(configProcessors, 10)
      if (!isNaN(parsedConfigProcessors) && isInteger(parsedConfigProcessors)) {
        utilizationConfig.logical_processors = parsedConfigProcessors
      } else {
        logger.info(
          '%s supplied in config for utilization.logical_processors, expected a number',
          configProcessors
        )
      }
    }

    if (configRam) {
      var parsedConfigRam = parseFloat(configRam, 10)
      if (!isNaN(parsedConfigRam) && isInteger(parsedConfigRam)) {
        utilizationConfig.total_ram_mib = parsedConfigRam
      } else {
        logger.info(
          '%s supplied in config for utilization.total_ram_mib, expected a number',
          configRam
        )
      }
    }

    if (configHostname) {
      if (typeof configHostname === 'string') {
        utilizationConfig.hostname = configHostname
      } else {
        logger.info(
          '%s supplied in config for utilization.Hostname, expected a string',
          configHostname
        )
      }
    }

    if (Object.keys(utilizationConfig).length > 0) {
      systemInfo.config = utilizationConfig
    }
  }

  var tasksDone = 0
  var numTasks = 5
  function finishedResponse() {
    if (++tasksDone === numTasks) return callback(systemInfo)
  }

  module.exports._getProcessorStats(function getProcessCB(processorStats) {
    systemInfo.packages = processorStats.packages
    systemInfo.logicalProcessors = processorStats.logical
    systemInfo.cores = processorStats.cores
    finishedResponse()
  })
  module.exports._getMemoryStats(function getMemCB(memory) {
    systemInfo.memory = memory
    finishedResponse()
  })
  getKernelVersion(function getVersionCB(kernelVersion) {
    systemInfo.kernelVersion = kernelVersion
    finishedResponse()
  })
  module.exports._getDockerContainerId(agent, function getContainerId(containerId) {
    if (containerId) {
      systemInfo.docker = {
        id: containerId
      }
    }
    finishedResponse()
  })
  fetchAWSInfo(agent, function getAWSInfo(aws) {
    systemInfo.aws = aws
    finishedResponse()
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.system_info._getDockerContainerId"></a>[function <span class="apidocSignatureSpan">newrelic.system_info.</span>_getDockerContainerId (agent, callback)](#apidoc.element.newrelic.system_info._getDockerContainerId)
- description and source-code
```javascript
function getDockerContainerId(agent, callback) {
  if (!platform.match(/linux/i)) {
    logger.debug('Platform is not a flavor of linux, omitting docker info')
    callback(null)
  } else {
    readProc('/proc/self/cgroup', function getCGroup(data) {
      if (!data) callback(null)
      else callback(parseDockerInfo(agent, data))
    })
  }
}
```
- example usage
```shell
...
  systemInfo.memory = memory
  finishedResponse()
})
getKernelVersion(function getVersionCB(kernelVersion) {
  systemInfo.kernelVersion = kernelVersion
  finishedResponse()
})
module.exports._getDockerContainerId(agent, function getContainerId(containerId) {
  if (containerId) {
    systemInfo.docker = {
      id: containerId
    }
  }
  finishedResponse()
})
...
```

#### <a name="apidoc.element.newrelic.system_info._getMemoryStats"></a>[function <span class="apidocSignatureSpan">newrelic.system_info.</span>_getMemoryStats (callback)](#apidoc.element.newrelic.system_info._getMemoryStats)
- description and source-code
```javascript
function getMemoryStats(callback) {
  if (platform.match(/darwin/i)) {
    getSysctlValue(['hw.memsize'], function getMem(memory) {
      callback(parseInt(memory, 10) / (1024 * 1024))
    })
  } else if (platform.match(/bsd/i)) {
    getSysctlValue(['hw.realmem'], function getMem(memory) {
      callback(parseInt(memory, 10) / (1024 * 1024))
    })
  } else if (platform.match(/linux/i)) {
    readProc('/proc/meminfo', function parseProc(data) {
      callback(parseMemInfo(data))
    })
  } else {
    logger.debug('Unknown platform: ' + platform + ', could not retrieve memory info')
    callback(null)
  }
}
```
- example usage
```shell
...

module.exports._getProcessorStats(function getProcessCB(processorStats) {
  systemInfo.packages = processorStats.packages
  systemInfo.logicalProcessors = processorStats.logical
  systemInfo.cores = processorStats.cores
  finishedResponse()
})
module.exports._getMemoryStats(function getMemCB(memory) {
  systemInfo.memory = memory
  finishedResponse()
})
getKernelVersion(function getVersionCB(kernelVersion) {
  systemInfo.kernelVersion = kernelVersion
  finishedResponse()
})
...
```

#### <a name="apidoc.element.newrelic.system_info._getProcessorStats"></a>[function <span class="apidocSignatureSpan">newrelic.system_info.</span>_getProcessorStats (callback)](#apidoc.element.newrelic.system_info._getProcessorStats)
- description and source-code
```javascript
function getProcessorStats(callback) {
  var processorStats = {
    logical: null,
    cores: null,
    packages: null
  }

  if (platform.match(/darwin/i)) {
    getSysctlValue(['hw.packages'], function getPackages(packages) {
      getSysctlValue(['hw.physicalcpu_max', 'hw.physicalcpu'],
      function getCores(cores) {
        getSysctlValue(['hw.logicalcpu_max', 'hw.logicalcpu', 'hw.ncpu'],
        function getLogicalCpu(logical) {
          processorStats.logical = parseFloat(logical, 10)
          processorStats.cores = parseFloat(cores, 10)
          processorStats.packages = parseFloat(packages, 10)

          for (var key in processorStats) {
            if (!processorStats[key] || !isInteger(processorStats[key])) {
              processorStats[key] = null
            }
          }

          callback(processorStats)
        })
      })
    })
  } else if (platform.match(/bsd/i)) {
    getSysctlValue(['hw.ncpu'], function getLogicalCpu(logical) {
      processorStats.logical = logical
      callback(processorStats)
    })
  } else if (platform.match(/linux/i)) {
    readProc('/proc/cpuinfo', function parseProc(data) {
      callback(parseCpuInfo(data))
    })
  } else {
    logger.debug('Unknown platform: ' + platform + ', could not retrieve processor info')
    callback(processorStats)
  }
}
```
- example usage
```shell
...

var tasksDone = 0
var numTasks = 5
function finishedResponse() {
  if (++tasksDone === numTasks) return callback(systemInfo)
}

module.exports._getProcessorStats(function getProcessCB(processorStats) {
  systemInfo.packages = processorStats.packages
  systemInfo.logicalProcessors = processorStats.logical
  systemInfo.cores = processorStats.cores
  finishedResponse()
})
module.exports._getMemoryStats(function getMemCB(memory) {
  systemInfo.memory = memory
...
```



# <a name="apidoc.module.newrelic.timer"></a>[module newrelic.timer](#apidoc.module.newrelic.timer)

#### <a name="apidoc.element.newrelic.timer.timer"></a>[function <span class="apidocSignatureSpan">newrelic.</span>timer ()](#apidoc.element.newrelic.timer.timer)
- description and source-code
```javascript
function Timer() {
  this.state = PENDING
  this.touched = false
  this.duration = null
  this.hrDuration = null
  this.hrstart = null
  this.durationInMillis = null
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.newrelic.timer.prototype"></a>[module newrelic.timer.prototype](#apidoc.module.newrelic.timer.prototype)

#### <a name="apidoc.element.newrelic.timer.prototype.begin"></a>[function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>begin ()](#apidoc.element.newrelic.timer.prototype.begin)
- description and source-code
```javascript
function begin() {
  if (this.state > PENDING) return

  this.start = Date.now()
  // need to put a guard on this for compatibility with Node < 0.8
  if (process.hrtime) this.hrstart = process.hrtime()
  this.state = RUNNING
}
```
- example usage
```shell
...
  }
}
}

function checkEvents(agent) {
return function eventSampler() {
  var timer = new Timer()
  timer.begin()
  setTimeout(recordQueueTime.bind(null, agent, timer), 0)
}
}

function getCpuSample(lastSample) {
try {
  return process.cpuUsage(lastSample)
...
```

#### <a name="apidoc.element.newrelic.timer.prototype.end"></a>[function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>end ()](#apidoc.element.newrelic.timer.prototype.end)
- description and source-code
```javascript
function end() {
  if (this.state > RUNNING) return
  if (this.state === PENDING) this.begin()
  if (process.hrtime) this.hrDuration = process.hrtime(this.hrstart)
  this.touched = true
  this.duration = Date.now() - this.start
  this.state = STOPPED
}
```
- example usage
```shell
...
var tracer = this.agent.tracer
var tx = tracer.getTransaction()

if (tx) {
  if (tx.webSegment) {
    tx.setName(tx.url, 0)
    tx.webSegment.markAsWeb(tx.url)
    tx.webSegment.end()
  } else if (tx.bgSegment) {
    tx.bgSegment.end()
  }
  logger.debug('ending transaction with id: %s and name: %s', tx.id, tx.name)
  tx.end()
} else {
  logger.debug('endTransaction() called while not in a transaction.')
...
```

#### <a name="apidoc.element.newrelic.timer.prototype.endsAfter"></a>[function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>endsAfter (other)](#apidoc.element.newrelic.timer.prototype.endsAfter)
- description and source-code
```javascript
function compare(other) {
  return (this.getDurationInMillis() + this.start) >
    (other.getDurationInMillis() + other.start)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.timer.prototype.getDurationInMillis"></a>[function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>getDurationInMillis ()](#apidoc.element.newrelic.timer.prototype.getDurationInMillis)
- description and source-code
```javascript
function getDurationInMillis() {
  if (this.state === PENDING) return 0

  // only set by setDurationInMillis
  if (this.durationInMillis !== null && this.durationInMillis >= 0) {
    return this.durationInMillis
  }

  // prioritize .end() and .touch()
  if (this.hrDuration) {
    return hrToMillis(this.hrDuration)
  }

  if (this.duration) {
    return this.duration
  }

  if (process.hrtime) {
    return hrToMillis(process.hrtime(this.hrstart))
  }

  return Date.now() - this.start
}
```
- example usage
```shell
...

/* If we're in an unnamed transaction, add a friendly warning this is to
 * avoid people going crazy, trying to figure out why browser monitoring is
 * not working when they're missing a transaction name.
 */
if (!name) return _gracefail(3)

var time = trans.timer.getDurationInMillis()

/*
 * Only the first 13 chars of the license should be used for hashing with
 * the transaction name.
 */
var key = config.license_key.substr(0, 13)
var appid = config.application_id
...
```

#### <a name="apidoc.element.newrelic.timer.prototype.hasEnd"></a>[function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>hasEnd ()](#apidoc.element.newrelic.timer.prototype.hasEnd)
- description and source-code
```javascript
function hasEnd() {
  return !!this.hrDuration
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.timer.prototype.isActive"></a>[function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>isActive ()](#apidoc.element.newrelic.timer.prototype.isActive)
- description and source-code
```javascript
function isActive() {
  return this.state < STOPPED
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.timer.prototype.isRunning"></a>[function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>isRunning ()](#apidoc.element.newrelic.timer.prototype.isRunning)
- description and source-code
```javascript
function isRunning() {
  return this.state === RUNNING
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.timer.prototype.overwriteDurationInMillis"></a>[function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>overwriteDurationInMillis (duration)](#apidoc.element.newrelic.timer.prototype.overwriteDurationInMillis)
- description and source-code
```javascript
function overwriteDurationInMillis(duration) {
  this.touched = true
  this.durationInMillis = duration
  this.state = STOPPED
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.timer.prototype.setDurationInMillis"></a>[function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>setDurationInMillis (duration, start)](#apidoc.element.newrelic.timer.prototype.setDurationInMillis)
- description and source-code
```javascript
function setDurationInMillis(duration, start) {
  if (this.state > RUNNING) return
  if (this.state === PENDING)
  if (!start && start !== 0) this.begin()

  this.state = STOPPED
  this.durationInMillis = duration

  // this assignment is incorrect, process.hrtime doesn't time from epoch, which
  // is the assumption being made here.  since hrstart isn't used
  // anywhere except to calculate duration, and we are setting duration
  // this is fine.
  this.hrstart = [Math.floor(start / 1e3), start % 1e3 * 1e6]
  this.start = start
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.timer.prototype.softEnd"></a>[function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>softEnd ()](#apidoc.element.newrelic.timer.prototype.softEnd)
- description and source-code
```javascript
function softEnd() {
  if (this.state > RUNNING) return false
  if (this.state === PENDING) this.begin()

  this.state = STOPPED

  if (this.touched) return false
  if (process.hrtime) this.hrDuration = process.hrtime(this.hrstart)
  this.touched = true
  this.duration = Date.now() - this.start
  return true
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.timer.prototype.startedRelativeTo"></a>[function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>startedRelativeTo (other)](#apidoc.element.newrelic.timer.prototype.startedRelativeTo)
- description and source-code
```javascript
function startedRelativeTo(other) {
  if (this.hrstart && other.hrstart && process.hrtime) {
    var s = this.hrstart[0] - other.hrstart[0]
    var ns = this.hrstart[1] - other.hrstart[1]


    return hrToMillis([s, ns])
  }

  return this.start - other.start
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.timer.prototype.toRange"></a>[function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>toRange ()](#apidoc.element.newrelic.timer.prototype.toRange)
- description and source-code
```javascript
function toRange() {
  return [this.start, this.start + this.getDurationInMillis()]
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.newrelic.timer.prototype.touch"></a>[function <span class="apidocSignatureSpan">newrelic.timer.prototype.</span>touch ()](#apidoc.element.newrelic.timer.prototype.touch)
- description and source-code
```javascript
function touch() {
  this.touched = true
  if (this.state > RUNNING) return
  if (this.state === PENDING) this.begin()

  if (process.hrtime) this.hrDuration = process.hrtime(this.hrstart)
  this.duration = Date.now() - this.start
}
```
- example usage
```shell
...
if (this.state === PENDING) return 0

// only set by setDurationInMillis
if (this.durationInMillis !== null && this.durationInMillis >= 0) {
  return this.durationInMillis
}

// prioritize .end() and .touch()
if (this.hrDuration) {
  return hrToMillis(this.hrDuration)
}

if (this.duration) {
  return this.duration
}
...
```



# <a name="apidoc.module.newrelic.uninstrumented"></a>[module newrelic.uninstrumented](#apidoc.module.newrelic.uninstrumented)

#### <a name="apidoc.element.newrelic.uninstrumented.check"></a>[function <span class="apidocSignatureSpan">newrelic.uninstrumented.</span>check ()](#apidoc.element.newrelic.uninstrumented.check)
- description and source-code
```javascript
function check() {
  for (var filename in require.cache) {
    if (!require.cache.hasOwnProperty(filename)) {
      continue
    }
    var name = moduleNameFromFilename(filename)

    if (INSTRUMENTATIONS.indexOf(name) !== -1) {
      uninstrumented.push({name: name, filename: filename})
    }
  }

  logUninstrumented()
}
```
- example usage
```shell
...
// just to make clear what's going on
var TO_MILLIS = 1e3
var FROM_MILLIS = 1e-3

// Check for already loaded modules and warn about them. This must be executed
// only once, at the first require of this file, or else we have problems in
// unit tests.
uninstrumented.check()

/**
* There's a lot of stuff in this constructor, due to Agent acting as the
* orchestrator for New Relic within instrumented applications.
*
* This constructor can throw if, for some reason, the configuration isn't
* available. Don't try to recover here, because without configuration the
...
```

#### <a name="apidoc.element.newrelic.uninstrumented.createMetrics"></a>[function <span class="apidocSignatureSpan">newrelic.uninstrumented.</span>createMetrics (metrics)](#apidoc.element.newrelic.uninstrumented.createMetrics)
- description and source-code
```javascript
function createMetrics(metrics) {
  if (uninstrumented.length > 0) {
    metrics.getOrCreateMetric(NAMES.SUPPORTABILITY.UNINSTRUMENTED).incrementCallCount()
  }

  uninstrumented.forEach(function addMetrics(module) {
    metrics.getOrCreateMetric(
      NAMES.SUPPORTABILITY.UNINSTRUMENTED + '/' + module.name
    ).incrementCallCount()
  })
}
```
- example usage
```shell
...
}

if (this.config.debug.supportability) {
  this.metrics.merge(this.config.debug.supportability)
}

// Send uninstrumented supportability metrics every harvest cycle
uninstrumented.createMetrics(this.metrics)

this._processCustomEvents()
this._processErrorEvents()

// wait to check until all the standard stuff has been added
if (this.metrics.toJSON().length < 1) {
  logger.debug("No metrics to send.")
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
