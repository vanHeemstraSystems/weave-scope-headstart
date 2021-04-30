# 100 - Install Weave Scope to Docker

Based on "Monitor Docker Containers and Kubernetes using Weave Scope" at https://computingforgeeks.com/monitor-docker-containers-and-kubernetes-using-weave-scope/

Weave Scope is a monitoring tool for Docker and Kubernetes clusters. It allows you to monitor your on-premise Docker host as well as Kubernetes cluster in realtime.

You can visualize the utilization of your containers or your cluster on a web dashboard.

Weave Scope can also be used to manage your docker containers which includes operations such as start,stop containers. You can also access the container shell from Weave Scope.

Run the following commands on a docker host to install Weave Scope:

```
sudo curl -L git.io/scope -o /usr/local/bin/scope
sudo chmod a+x /usr/local/bin/scope
```

Launch Weave Scope:

```$ scope launch```

You can now access Weave Scope on:

```http://[SERVER-IP]:4040```

The dashboard will show the containers running on your host and there are several other options to manage and/or monitor your host:

[ image goes here ]

To manage your containers, click one one of them, you will be presented with an interface where you can view the metrics of the container and also do various operations on the container such as start,stop, pause etc. You can also execute the container’s shell as shown below:

[ image goes here ]

General metrics are available at the Table tab:

[ image goes here ]
