# [Command] _networkcloud virtualmachine attach-volume_

Attach volume to the provided virtual machine.

## Versions

### [2022-12-12-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrY2xvdWQvdmlydHVhbG1hY2hpbmVzL3t9L2F0dGFjaHZvbHVtZQ==/2022-12-12-preview.xml) **Experimental**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.networkcloud/virtualmachines/{}/attachvolume 2022-12-12-preview -->

#### examples

- Attach volume to virtual machine
    ```bash
        networkcloud virtualmachine attach-volume --resource-group "resourceGroupName" --volume-id "/subscriptions/subscriptionId/resourceGroups/resourceGroupName/providers/Microsoft.NetworkCloud/volumes/volumeName" --name "virtualMachineName"
    ```
