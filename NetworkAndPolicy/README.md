# This is a combined deployment list of network (flannel) and network policy (calico)
## The configuration of the file can be found in the canal.yaml file net-conf.json | ** Modify the basic configuration

### for example
#### 
    net-conf.json: |
    {
      "Network": "10.244.0.0/16",
        "Backend": {
        "Type": "vxlan",
        "Directrouting": true
        }
    }
