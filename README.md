![Simplicité Software](https://platform.simplicite.io/logos/logo250-grey.png)
***

NodeRED web frontend demo
=========================

This project is a web front-end demo written in [NodeRED](http://nodered.org/)
the [Simplicité&reg; node.js&reg; &amp; browser JavaScript API](https://www.npmjs.com/package/simplicite)
and [Simplicité&reg; NodeRED nodes](https://www.npmjs.com/package/node-red-contrib-simplicite)
to access to a Simplicité&reg; back-end instance.

Prerequisites
-------------

To use this full-stack demo you need to have:

- a Simplicité&reg; back-end instance
- a NodeRED front-end configured with the Simplicité&reg; nodes

On the **back-end** you need to import the demo application configuration by loading
the `Demo` module `http://www.simplicitesoftware.com/resources/modules/demo-app-x.y.xml`
and its sample data `http://www.simplicitesoftware.com/resources/modules/demo-data-x.y-xml`
(where `x.y` is your instance's version, e.g. `4.0`).

On the **front-end** you need to import the Demo flows provided in the `demo.json` file.

License
=======

Copyright 2014-2024 Simplicité Software

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at:

[](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
