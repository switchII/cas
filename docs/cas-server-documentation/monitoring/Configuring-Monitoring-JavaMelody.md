---
layout: default
title: CAS - JavaMelody Monitoring
category: Monitoring & Statistics
---

{% include variables.html %}

# JavaMelody Monitoring

Use [JavaMelody](https://github.com/javamelody/javamelody) is to monitor CAS in QA and production environments.

Support is added by including the following dependency in the WAR overlay:

{% include casmodule.html group="org.apereo.cas" module="cas-server-support-javamelody" %}

JavaMelody monitoring is by default exposed at `${context-path}/monitoring` where `${context-path}` is typically set to `/cas`.

## Configuration

To see the relevant list of CAS properties, please [review this guide](../configuration/Configuration-Properties.html#javamelody).
