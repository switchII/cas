---
layout: default
title: CAS - Mongo Service Registry
category: Services
---

{% include variables.html %}

# Mongo Service Registry

This registry uses a [MongoDb](https://www.mongodb.org/) instance to load and persist service definitions.
Support is enabled by adding the following module into the overlay:

{% include casmodule.html group="org.apereo.cas" module="cas-server-support-mongo-service-registry" %}

## Configuration

This implementation auto-configures most of the internal details.
To see the relevant list of CAS properties, please [review this guide](../configuration/Configuration-Properties.html#mongodb-service-registry).

## Auto Initialization

Upon startup and configuration permitting, the registry is able to auto initialize itself from default JSON service definitions available to CAS. See [this guide](AutoInitialization-Service-Management.html) for more info.
