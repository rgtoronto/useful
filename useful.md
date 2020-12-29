#### How to register node to red hat:
```
subscription-manager clean
subscription-manager refresh
subscription-manager register
subscription-manager list --available --all
subscription-manager attach --pool=8a85f99a75fb07cc01764d89f9756403
subscription-manager repos
subscription-manager repos --enable rhel-7-server-rhscon-2-installer-rpms
```
