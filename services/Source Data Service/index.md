---
name: Source Data Service
summary: |
  Event handler for Quote Events
owners:
    - ahamp
repository:
  language: Flogo
  url: https://eu.integration.cloud.tibco.com/applications/details/flows/5tok4udog36l2pky3vfcdin7g74nb2p4?applicationType=flogo
---

Flogo event handler that takes quote events fed into Kafka topic pricing.quote.request
This service splits the event data into two sub events for downstream services.

<NodeGraph />