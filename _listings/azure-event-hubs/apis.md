---
name: Azure Event Hubs
x-slug: azure-event-hubs
description: Azure Event Hubs is a hyper-scale telemetry ingestion service that collects,
  transforms, and stores millions of events. As a distributed streaming platform,
  it gives you low latency and configurable time retention, which enables you to ingress
  massive amounts of telemetry into the cloud and read the data from multiple applications
  using publish-subscribe semantics.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-event-hubs-stream.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Namespaces Authorization Rule
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/namespaces-authorization-rule/master/_listings/azure-event-hubs/apis.md
specificationVersion: "0.14"
apis:
- name: EventHubManagementClient - Namespaces Create Or Update Authorization Rule
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-eventhubnamespacesnamespacenameauthorizationrulesauthorizationrulename-put
  description: Creates or updates an AuthorizationRule for a Namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-event-hubs-stream.png
  humanURL: https://azure.microsoft.com/en-us/services/event-hubs/
  baseURL: ://management.azure.com//
  tags: Microsoft, Jobs, Orchestration, Stack Network, API Service Provider, API Provider,
    SDIO Competition, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/namespaces-authorization-rule/master/_listings/azure-event-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-eventhubnamespacesnamespacenameauthorizationrulesauthorizationrulename-put-openapi.md
- name: EventHubManagementClient - Namespaces Delete Authorization Rule
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-eventhubnamespacesnamespacenameauthorizationrulesauthorizationrulename-delete
  description: Deletes an AuthorizationRule for a Namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-event-hubs-stream.png
  humanURL: https://azure.microsoft.com/en-us/services/event-hubs/
  baseURL: ://management.azure.com//
  tags: Microsoft, Jobs, Orchestration, Stack Network, API Service Provider, API Provider,
    SDIO Competition, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/namespaces-authorization-rule/master/_listings/azure-event-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-eventhubnamespacesnamespacenameauthorizationrulesauthorizationrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/namespaces-authorization-rule/master/_listings/azure-event-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-eventhubnamespacesnamespacenameauthorizationrulesauthorizationrulename-delete-openapi.md
- name: EventHubManagementClient - Namespaces Get Authorization Rule
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-eventhubnamespacesnamespacenameauthorizationrulesauthorizationrulename-get
  description: Gets an AuthorizationRule for a Namespace by rule name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-event-hubs-stream.png
  humanURL: https://azure.microsoft.com/en-us/services/event-hubs/
  baseURL: ://management.azure.com//
  tags: Microsoft, Jobs, Orchestration, Stack Network, API Service Provider, API Provider,
    SDIO Competition, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/namespaces-authorization-rule/master/_listings/azure-event-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-eventhubnamespacesnamespacenameauthorizationrulesauthorizationrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/namespaces-authorization-rule/master/_listings/azure-event-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-eventhubnamespacesnamespacenameauthorizationrulesauthorizationrulename-get-openapi.md
x-common:
- type: x-hacker-news-search
  url: Azure Event Hubs
- type: x-api-gallery
  url: http://azure.documentdb.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.event.hubs.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/event-hubs/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/event-hubs/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/event-hubs/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/event-hubs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---