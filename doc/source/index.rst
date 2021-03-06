..
      Copyright 2016 Huawei Technologies India Pvt Limited.

      Licensed under the Apache License, Version 2.0 (the "License"); you may
      not use this file except in compliance with the License. You may obtain
      a copy of the License at

          http://www.apache.org/licenses/LICENSE-2.0

      Unless required by applicable law or agreed to in writing, software
      distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
      WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
      License for the specific language governing permissions and limitations
      under the License.


      Convention for heading levels in Neutron devref:
      =======  Heading 0 (reserved for the title in a document)
      -------  Heading 1
      ~~~~~~~  Heading 2
      +++++++  Heading 3
      '''''''  Heading 4
      (Avoid deeper levels because they do not render well.)

Welcome to neutron-dynamic-routing's documentation!
===================================================
.. include:: ../../README.rst


===============
Developer Guide
===============
In the Developer Guide, you will find information on neutron-dynamic-routing
lower level programming APIs. There are sections that cover the core pieces
of neutron-dynamic-routing, including its api, command-lines, database,
system-design, alembic-migration etc. There are also subsections that describe
specific drivers inside neutron-dynamic-routing. Finally, the developer guide
includes information about testing and supported functionalities as well. This
documentation is generated by the Sphinx toolkit and lives in the source
tree.

Programming HowTos and Tutorials
--------------------------------
.. toctree::
    :maxdepth: 2

    installation
    usage
    contributing

Design
------
.. toctree::
   :maxdepth: 2

   design/system-design
   design/api
   design/command-lines
   design/agent-scheduler
   design/drivers

Functionality
-------------
.. toctree::
   :maxdepth: 2

   functionality/bgp-speaker
   functionality/route-advertisement

Others 
------
.. toctree::
   :maxdepth: 2

   others/alembic_migration
   others/testing

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
