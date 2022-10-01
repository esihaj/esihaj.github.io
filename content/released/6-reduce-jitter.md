---
title: "Reducing System Jitter"
date: 2022-09-30T22:43:04-07:00
weight: 6
draft: false
---
"CPU isolation and thread affinity are  powerful tools that can help reduce runtime jitter introduced by the OS scheduler. Linux tracing tools such as perf_events are invaluable for inspecting the state of running processes when determining sources of jitter. For low-latency applications, orders-of-magnitude reductions in jitter can be achieved by applying these techniques."
From [Mark Price's Personal Blog] (https://epickrram.blogspot.com/2015/09/reducing-system-jitter.html)
He was part of the LMAX Exchange team. His blog contains a multitude of greate performance oriented posts.
- {{< tag latency >}}
