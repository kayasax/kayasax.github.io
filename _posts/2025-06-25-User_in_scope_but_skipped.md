---
layout: post
title: Users are skipped in Cross Tenant Sync
subtitle: There's lots to learn!
gh-badge: [star, fork, follow]
tags: [CTS]
comments: true
mathjax: true
author: Loïc
---

There is limitation in Cross Tenant Sync: users that are SMS sign-in enabled will be skipped with error `"Filter external users.alternativeSecurityIds EQUALS 'None'"`
Ref: https://learn.microsoft.com/en-us/entra/identity/multi-tenant-organizations/cross-tenant-synchronization-configure?pivots=same-cloud-synchronization#symptom---users-are-skipped-because-sms-sign-in-is-enabled-on-the-user
