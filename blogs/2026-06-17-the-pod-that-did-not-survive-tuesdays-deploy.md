---
title: "The pod that did not survive Tuesday's deploy"
url: "https://pydantic.dev/articles/logfire-kubernetes-view"
date: "2026-06-17"
author: "Bill Easton"
feed_url: "https://pydantic.dev/articles"
---
A Vercel AI SDK chatbot deployed to Google Kubernetes Engine throws 500 errors on 8% of requests after a Tuesday deploy. Using Pydantic Logfire's new Kubernetes observability view, developers identify a pod stuck in an out-of-memory restart loop caused by a tokenizer dependency that doubled memory usage in the new image.
