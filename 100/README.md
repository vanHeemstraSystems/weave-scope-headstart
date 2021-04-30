# 100 - Key Feature

- ***Drill down Views***: For an app which is running in Kubernetes, Scope displays Pods, Replica Sets, Deployments, and related Services on clusters. So for containerized microservices running in the cloud, you can view Processes, Containers, Orchestrators, and Hosts.

- ***Real time Contextual metrics***: By clicking on a node you can get detailed panel with additional metrics on the node. From the detailed panel, you can drilldown on processes inside your container to the hosts that your containers run on.

- ***Troubleshoot / Manage Containers***: On clicking of a container, pod or host, you can view the controls pane from there you can pause, restart, stop and delete without having to leave the Scope browser window. If further troubleshooting is required, terminal windows can be launched from any container or host so that you can interact with your app and run any UNIX command to diagnose issues.

- ***Search***: Weave supports simple operands so that for example, you can find processes consuming a certain amount memory or nodes using too much CPU.

- ***Filtering options***: Nodes can be filtered by CPU and Memory usage so that you can easily find containers using the most resources. If you are running an app in Kubernetes then your app can be filtered by namespace and by container state whether running or stopped or contained and uncontained.

- ***Graphic / Table Mode***: Views can be presented in Graphic as well as Table Mode. Graphical mode is more useful in cases where you want to have a quick visual overview of your app. Table mode is for viewing data like resources being consumed by processes, containers, and hosts etc.
