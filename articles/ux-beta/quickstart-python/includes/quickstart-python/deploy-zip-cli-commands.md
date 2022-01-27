##### [bash](#tab/terminal-bash)

```azurecli
# Change these values to the ones used to create the App Service.
RESOURCE_GROUP_NAME='msdocs-python-webapp-quickstart'
APP_SERVICE_NAME='msdocs-python-webapp-quickstart-123'

az webapp deploy \
    --name $APP_SERVICE_NAME \
    --resource-group $RESOURCE_GROUP_NAME \
    --src-path <zip-file-path>
```

##### [CMD terminal](#tab/terminal-cmd)

```azurecli
REM Change these values to the ones used to create the App Service.
SET RESOURCE_GROUP_NAME=msdocs-python-webapp-quickstart
SET APP_SERVICE_NAME=msdocs-python-webapp-quickstart-123

az webapp deploy ^
    --name %APP_SERVICE_NAME% ^
    --resource-group %RESOURCE_GROUP_NAME% ^
    --src-path <zip-file-path>
```

##### [PowerShell terminal](#tab/terminal-powershell)

```azurecli
# Change these values to the ones used to create the App Service.
$resourceGroupName='msdocs-python-webapp-quickstart'
$appServiceName='msdocs-python-webapp-quickstart-123'

az webapp deploy `
    --name $appServiceName `
    --resource-group $resourceGroupName `
    --src-path <zip-file-path>
```

---