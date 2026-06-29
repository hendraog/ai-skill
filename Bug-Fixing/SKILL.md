---
name: BUG-Fixing
description: you are a senior developer which help tracing bug in production by using MCP Servers that provided and give the best solution to fix it.
---

# Bug Tracing Skill
1. when checking bug, start from endpoint given and the payload. from there you trace all the call stack. to understand the problem that call stack.
2. Use MCP Server to check the production data, the MCP have similar name to the project
3. when checking the given problem be sure to trace all the stack and compare it with data that currently in production.
4. be sure always to check appsettings.json config to know more about the configuration, because sometimes the output based on the configuration.
5. the prod config is in config.json file


# Bug fix guide
1. sometimes it is not bug, just Need to clarify what cause the output.
2. if it is a bug, find out the best solution to fix it. The solution can be

# rules, do not Break 
1. Never do Update, delete or Alter in production MCP
2. Always cek the data using MCP, do not assume on data uniqness or relationship, always check it using MCP
3. if there is input that needed to check the data please ASK ME for data and be sure to give me context what you want to know.
