# orthanc-webhook
This repo implement a Orthanc with Python plugin extension that enables registration of webhooks for events.

# License Note
Licensing for Your Orthanc Python Plugin
Orthanc is licensed under GPLv3+. Crucially, the Orthanc documentation explicitly states:

"An Orthanc plugin cannot be licensed under a permissive license (MIT, BSD, Apache…) because it cannot run independently of the Orthanc SDK, which implies that the plugin and the Orthanc core form a single combined program, which in turn means that the plugin should be licensed under GPLv3 by copyleft contamination."

Furthermore, the official Orthanc Python plugin is licensed under the AGPLv3+. The documentation for the Python plugin reiterates:

"Pay attention to the fact that this plugin is licensed under the terms of the AGPL license. This has an important consequence: If you distribute Orthanc to clients together with one Python script, or if you put an Orthanc server equipped with one Python script on a Web portal, you must disclose the source code of your Python script to the Orthanc community under the terms of the AGPL license."

Therefore, if you have extended the Python plugin for Orthanc, you should use the AGPLv3+ license for your extended plugin.
