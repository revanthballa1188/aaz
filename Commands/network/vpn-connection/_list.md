# [Command] _network vpn-connection list_

List all VPN connections.

## Versions

### [2022-01-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2Nvbm5lY3Rpb25z/2022-01-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/connections 2022-01-01 -->

#### examples

- List all VPN connections in a resource group.
    ```bash
        network vpn-connection list -g MyResourceGroup
    ```

- List all VPN connections in a virtual network gateway.
    ```bash
        network vpn-connection list -g MyResourceGroup --vnet-gateway MyVnetGateway
    ```