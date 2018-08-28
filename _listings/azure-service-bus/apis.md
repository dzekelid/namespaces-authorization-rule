---
name: Azure Service Bus
x-slug: azure-service-bus
description: Depend on Azure Service Bus when you need highly-reliable cloud messaging
  service between applications and services, even when one or more is offline. Available
  in every Azure region, this fully-managed service eliminates the burdens of server
  management and licensing. Asynchronous operations give you flexible, brokered messaging
  between client and server, along with structured first-in, first-out (FIFO) messaging,
  and publish/subscribe capabilities&mdash;excellent for tasks like order processing.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Namespaces Authorization Rule
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/namespaces-authorization-rule/master/_listings/azure-service-bus/apis.md
specificationVersion: "0.14"
apis:
- name: ServiceBusManagementClient - Namespaces Create Or Update Authorization Rule
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulename-put
  description: Creates or updates an authorization rule for a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Messages, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/namespaces-authorization-rule/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulename-put-openapi.md
- name: ServiceBusManagementClient - Namespaces Delete Authorization Rule
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulename-delete
  description: Deletes a namespace authorization rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Messages, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/namespaces-authorization-rule/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/namespaces-authorization-rule/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulename-delete-openapi.md
- name: ServiceBusManagementClient - Namespaces Get Authorization Rule
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulename-get
  description: Gets an authorization rule for a namespace by rule name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com//
  tags: Microsoft, Stack Network, API Service Provider, API Provider, Messages, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/namespaces-authorization-rule/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/namespaces-authorization-rule/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrulesauthorizationrulename-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.search.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.service.bus.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/service-bus/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/service-bus/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/service-bus/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/service-bus/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---