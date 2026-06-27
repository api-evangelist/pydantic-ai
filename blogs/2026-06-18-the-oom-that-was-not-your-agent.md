---
title: "The OOM that was not your agent"
url: "https://pydantic.dev/articles/logfire-hosts-view"
date: "2026-06-18"
author: "Bill Easton"
feed_url: "https://pydantic.dev/articles"
---
This article describes how Pydantic Logfire's new host metrics view helped diagnose an out-of-memory error in a document classifier agent. The issue was not the agent itself but a Postgres vacuum running simultaneously on the same server, consuming memory and disk I/O starting at midnight.
