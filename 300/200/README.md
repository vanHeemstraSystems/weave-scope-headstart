# 200 - Install Weave Scope to Kubernetes

On your Kubernetes cluster, run the following command:

```
$ kubectl create -f "https://cloud.weave.works/launch/k8s/weavescope.yaml"
```

Above command downloads a Scope image from Dockerhub and launches a probe onto every node as well as a single Scope app.

Now that deployment is created, lets check the deployment information using kubectl get pods command:

```
$ kubectl get pods -n weave
```

Once all of the Pods as up and running, use kubectl expose pod command to the expose the services to the outside world.

```
... more
```
