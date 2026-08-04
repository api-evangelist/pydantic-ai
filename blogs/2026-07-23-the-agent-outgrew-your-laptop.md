---
title: "The agent outgrew your laptop"
url: "https://pydantic.dev/articles/harness-modal"
date: "2026-07-23"
author: "Bill Easton"
feed_url: "https://pydantic.dev/feed.xml"
---
Harness Week, day four: the basic version of the CVE-bump agent runs on your laptop's shell in fifteen lines and works fine on one service. The fastest path from working to production is the harness's ModalSandbox capability — gVisor-isolated sub-second containers per task, five hundred in parallel if that's what the plan takes.
