# azuresamples-eventgrid-functionapp


``` powershell
az group create -n 'hossein-sandbox-01' -l 'canada central'

az ad sp create-for-rbac --name 'hossein-github-app-01' --role contributor --scopes /subscriptions/a95df0af-4791-4677-93bc-228ce088d09e/resourceGroups/hossein-sandbox-01 --sdk-auth
```

``` json
{
  "clientId": "",
  "clientSecret": "",
  "subscriptionId": "",
  "tenantId": "",
  "activeDirectoryEndpointUrl": "https://login.microsoftonline.com",
  "resourceManagerEndpointUrl": "https://management.azure.com/",
  "activeDirectoryGraphResourceId": "https://graph.windows.net/",
  "sqlManagementEndpointUrl": "https://management.core.windows.net:8443/",
  "galleryEndpointUrl": "https://gallery.azure.com/",
  "managementEndpointUrl": "https://management.core.windows.net/"
}
```