# [Command] _networkcloud trunkednetwork list_

List trunked networks in the provided resource group or subscription.

## Versions

### [2022-12-12-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrY2xvdWQvdHJ1bmtlZG5ldHdvcmtz/2022-12-12-preview.xml) **Experimental**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.networkcloud/trunkednetworks 2022-12-12-preview -->
<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.networkcloud/trunkednetworks 2022-12-12-preview -->

#### examples

- List trunked networks for subscription
    ```bash
        networkcloud trunkednetwork list
    ```

- List trunked networks for resource group
    ```bash
        networkcloud trunkednetwork list --resource-group "resourceGroupName"
    ```
