---
title: About user-defined actions
excerpt: Write custom functions and procedures, and schedule them to run periodically
keywords: [actions]
tags: [user-defined actions, background jobs, scheduled jobs, automation framework]
---

# About user-defined actions

With user-defined actions, you can write custom functions and procedures, and
schedule them to run periodically. TimescaleDB natively includes some
job-scheduling policies, such as:

*   [Continuous aggregate policies][caggs] to automatically refresh continuous
    aggregates
*   [Compression policies][compressing] to compress historical data
*   [Retention policies][retention] to drop historical data
*   [Reordering policies][reordering] to reorder data within chunks

If these don't cover your use case, or if you want to expand upon the native
policy features, you can write a user-defined action. Actions can be written in
the language of your choice.

[caggs]: /timescaledb/:currentVersion:/how-to-guides/continuous-aggregates/refresh-policies/
[compressing]: /timescaledb/:currentVersion:/how-to-guides/compression/about-compression/
[reordering]: /api/:currentVersion:/hypertable/add_reorder_policy/
[retention]: /timescaledb/:currentVersion:/how-to-guides/data-retention/create-a-retention-policy/
