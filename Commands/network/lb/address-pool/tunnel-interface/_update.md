# [Command] _network lb address-pool tunnel-interface update_

Update one tunnel interface of load balance tunnel interface pool.

## Versions

### [2022-05-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2xvYWRiYWxhbmNlcnMve30vYmFja2VuZGFkZHJlc3Nwb29scy97fQ==/2022-05-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/loadbalancers/{}/backendaddresspools/{} 2022-05-01 properties.tunnelInterfaces[] -->

#### examples

- update one tunnel interface of load balance tunnel interface pool.
    ```bash
        network lb address-pool tunnel-interface update -g MyResourceGroup --lb-name MyLb --address-pool MyAddressPool --type external --protocol vxlan --identifier 901 --port 10000 --index 0
    ```
