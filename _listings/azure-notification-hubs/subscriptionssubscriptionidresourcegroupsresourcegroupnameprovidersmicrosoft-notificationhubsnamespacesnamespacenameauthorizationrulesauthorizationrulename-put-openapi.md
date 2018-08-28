---
swagger: "2.0"
x-collection-name: Azure Notification Hubs
x-complete: 0
info:
  title: Azure Notification Hubs API Namespaces Create Or Update Authorization Rule
  description: Creates an authorization rule for a namespace
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/AuthorizationRules/{authorizationRuleName}
  : put:
      summary: Namespaces Create Or Update Authorization Rule
      description: Creates an authorization rule for a namespace
      operationId: Namespaces_CreateOrUpdateAuthorizationRule
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrulesauthorizationrulename-put
      parameters:
      - in: path
        name: authorizationRuleName
        description: Aauthorization Rule Name
      - in: path
        name: namespaceName
        description: The namespace name
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The shared access authorization rule
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Namespaces Authorization Rule
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---