```
oc new-project ci
oc new-app -n ci https://github.com/j1cken/nexus-ose.git --context-dir=nexus/nexus-container --strategy=docker --name=nexus
```
