---
name: User
version: 0.0.1
summary: |
  New User Event 
producers:
    - Source Data Service
consumers:
    - Streaming Analytics Service
    - User Data
owners:
    - ahamp
---


### Details

This event comes from the event source handler.

It contains all the data about a user... some of this data is encrypted and need to be decrypted via a RSA private key

Kafka Topic:  event.user.data

<NodeGraph title="Consumer / Producer Diagram" />

<Schema />