# 200 - How it works

Weave Scope consists of two components: the app and the probe.The probe is responsible for gathering information about the host on which it is running. This information is sent to the app in the form of a report. The app processes reports from the probe into various visualizations (ex.Topologies).

[ -- image here -- ]

Scope app can be run as standalone mode or as hosted Cloud offering.In standalone mode,when running Scope in a cluster, each probe sends its reports to a dedicated app. The app merges the reports from its probe into a comprehensive report that is sent to the browser.

Scope can also be used to feed reports to Weave Cloud. With Weave Cloud offering, you can centrally manage and share access to your Scope user interface. In this configuration, the probe is run locally and the apps are hosted on the cloud.
