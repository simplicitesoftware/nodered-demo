![Simplicit&eacute; Software](http://www.simplicitesoftware.com/logos/logo250.png)

---

NodeRED web frontend demo
=========================

This project is a web front-end demo written in [NodeRED](http://nodered.org/) using the [Simplicit&eacute;&reg; Node.js API](https://github.com/simplicitesoftware/nodejs-api)
and [Simplicit&eacute;&reg; NodeRED nodes](https://github.com/simplicitesoftware/nodered-nodes)
to access to a Simplicit&eacute;&reg; back-end instance.

Back-end prerequisites
----------------------

To use this front-end demo you need to havea running Simplicit&eacute;&reg; back-end instance. 

On this instance you need to load the demo application configuration by creating and uploading the `Demo` module `http://www.simplicitesoftware.com/resources/modules/demo-app-x.y.xml`
and its sample data `http://www.simplicitesoftware.com/resources/modules/demo-data-x.y-xml` (where `x.y` is your instance's version).

Run locally
-----------

```
npm install --production
node red.js
```

Run on CloudFoundry
-------------------

### Deploy

Adjust the `manifest.yml` to your needs and deploy the app:

```
cf push <app name>
```

Once deployed, load the flows located in the `flows` folder and adjust the nodes
configuration to point to the Simplcit&eacute;&reg; instance.

### Undeploy

Undeploy the app:

```
cf delete <app name>
```

License
=======

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at:

[](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
