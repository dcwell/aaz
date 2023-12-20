# [Command] _apic workspace delete_

Delete specified workspace.

## Versions

### [2024-03-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5hcGljZW50ZXIvc2VydmljZXMve30vd29ya3NwYWNlcy97fQ==/2024-03-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.apicenter/services/{}/workspaces/{} 2024-03-01 -->

#### examples

- Delete workspace
    ```bash
        apic workspace delete -g api-center-test -s contoso --name devdiv
    ```