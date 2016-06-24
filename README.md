![Simplicit&eacute; Software](http://www.simplicitesoftware.com/logos/logo250.png)

---

NodeRED web frontend demo
=========================

This project is a web frontend demo written in NodeRED using the Simplicit&eacute;&reg; Node.js API
and Simplicit&eacute;&reg; NodeRED nodes to access to a Simplicit&eacute;&reg;
backend instance.

Deploy
------

Load the demo configuration into a Simplicit&eacute;&reg; instance
by uploading :

1. The platform demo app `http://www.simplicitesoftware.com/resources/modules/demo-app.zip`
and data `http://www.simplicitesoftware.com/resources/modules/demo-data.zip`
2. The messaging demo `http://www.simplicitesoftware.com/resources/modules/bluemix-demo.zip`

Adjust the `manifest.yml` to your needs and deploy the app:

```
cf push <app name>
```

Once deployed, load the flows located in the `flows` folder and adjust the nodes
configuration to point to the Simplcit&eacute;&reg; instance.

Enjoy !

Undeploy
--------

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
