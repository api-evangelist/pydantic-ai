---
title: "Durable execution in Pydantic AI agents with AWS Lambda Durability"
url: "https://pydantic.dev/articles/harness-aws-lambda"
date: "2026-09-09"
author: "Laís Carvalho"
feed_url: "https://pydantic.dev/feed.xml"
---
AWSLambdaDurability checkpoints every model request, tool call, and MCP call as an AWS Lambda durable step. An invocation that times out or gets retried resumes from the last completed step instead of paying twice for work the agent already did.
