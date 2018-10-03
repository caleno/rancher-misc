# rancher-misc
Misc files and experience for setting up rancher

# Apply firewalld rules example
```firewall-cmd --zone="trusted" --permanent --add-source="xxx.xxx.xxx.xxx/32"```

```firewall-cmd --zone="trusted" --permanent --add-service="rancher-worker"```

```firewall-cmd --reload```
