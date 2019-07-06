# grafana-docker


### reset password for grafana in okd,kubernetes

For OKD

1. select project
```
oc proejct <NAMESPACE>
```
2. se
```bash
oc get pods | grep grafana
```

3. describe pod and find where pod run
```bash
oc describe <podname>
```

4. go to node and find hot to run grafana
```bash
ps uax | grep grafana
```



