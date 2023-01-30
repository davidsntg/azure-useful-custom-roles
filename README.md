
## Application Gateway - Get Backend Status Role

```json
{
    "id": "/subscriptions/TO_REPLACE/providers/Microsoft.Authorization/roleDefinitions/TO_REPLACE",
    "properties": {
        "roleName": "Custom Role - Application Gateway - Get Backend Status Role",
        "description": "",
        "assignableScopes": [
            "/providers/Microsoft.Management/managementGroups/TO_REPLACE"
        ],
        "permissions": [
            {
                "actions": [
                    "Microsoft.Network/applicationGateways/read",
                    "Microsoft.Network/applicationGateways/backendhealth/action",
                    "Microsoft.Network/applicationGateways/getBackendHealthOnDemand/action"
                ],
                "notActions": [],
                "dataActions": [],
                "notDataActions": []
            }
        ]
    }
}
```

## Service Bus - Namespaces Read

```json
{
    "id": "/subscriptions/TO_REPLACE/providers/Microsoft.Authorization/roleDefinitions/TO_REPLACE",
    "properties": {
        "roleName": "Custom Role - Service Bus - Namespaces Read",
        "description": "",
        "assignableScopes": [
            "/providers/Microsoft.Management/managementGroups/TO_REPLACE"
        ],
        "permissions": [
            {
                "actions": [
                    "Microsoft.ServiceBus/namespaces/read"
                ],
                "notActions": [],
                "dataActions": [],
                "notDataActions": []
            }
        ]
    }
}
```

## Service Bus Explorer on Topics and Queues

```json
{
    "id": "/subscriptions/TO_REPLACE/providers/Microsoft.Authorization/roleDefinitions/TO_REPLACE",
    "properties": {
        "roleName": "Custom Role - Service Bus Explorer on Topics and Queues",
        "description": "",
        "assignableScopes": [
            "/providers/Microsoft.Management/managementGroups/TO_REPLACE"
        ],
        "permissions": [
            {
                "actions": [
                    "Microsoft.ServiceBus/*"
                ],
                "notActions": [
                    "Microsoft.ServiceBus/*/delete",
                    "Microsoft.ServiceBus/*/write",
                    "Microsoft.ServiceBus/*/action"
                ],
                "dataActions": [
                    "Microsoft.ServiceBus/*"
                ],
                "notDataActions": []
            }
        ]
    }
}
```
