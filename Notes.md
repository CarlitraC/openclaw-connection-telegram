# OpenClaw–Telegram Integration
**Project:** Connect OpenClaw to Telegram and enable Google Apps through Zapier MCP.

### Project Overview

This guide outlines the steps required to connect an OpenClaw agent to Telegram, install and test OpenClaw skills, and integrate Google Workspace applications, such as Google Calendar and Google Drive, through Zapier MCP.

The goal is to enable users to interact with the OpenClaw agent directly from Telegram, allowing it to process requests, ask clarifying questions, execute actions using connected tools, and return responses through Telegram.

### Implementation Steps

**Step A · Verify VPS and OpenClaw Gateway Status**

- Confirm that the VPS is running and has at least 2 GB of RAM.
- Verify that OpenClaw and its Gateway are installed.
- Ensure the Gateway is enabled and running correctly.

**Step B · Create a Telegram Bot and Connect It to OpenClaw**

- Create a Telegram bot using BotFather.
- Configure the bot credentials in OpenClaw.
- Establish and verify the connection between Telegram and the OpenClaw Gateway.
- Test basic message exchanges.

**Step C · Install and Test an OpenClaw Skill**

- Explore available OpenClaw skills.
- Install and configure the Weather skill.
- Send a weather-related request through Telegram.
- Verify that OpenClaw executes the skill and returns the results through Telegram.

**Step D · Connect Zapier MCP and Enable Google Workspace Tools**

- Configure the Zapier MCP integration in OpenClaw.
- Enable Google Calendar and Google Drive tools through Zapier.
- Authenticate the required Google accounts.
- Verify that OpenClaw can discover and invoke the enabled tools.
- Test basic operations using Google Calendar and Google Drive.

**Step E · Execute an End-to-End Workflow from a Mobile Device**

Validate the complete workflow using Telegram on a mobile phone:

1. **User request:** Send a request to the OpenClaw agent through Telegram.
2. **Agent clarification:** The agent asks follow-up questions when additional information is required.
3. **Tool selection:** The agent identifies the appropriate Google Workspace tool through Zapier MCP.
4. **Agent execution:** The agent performs the requested action using the connected tool.
5. **Agent response:** The agent confirms the outcome and returns the results through Telegram.

### Expected Outcome

By the end of this project, OpenClaw should be able to:

- Receive and respond to Telegram messages.
- Execute installed OpenClaw skills.
- Access Google Calendar and Google Drive through Zapier MCP.
- Ask users for clarification before executing actions when necessary.
- Complete tool-based workflows initiated from a mobile device.
- Return execution results and confirmations directly through Telegram.

### Project Success Criteria

**The integration is considered successful when a user can initiate a request from Telegram, have OpenClaw process it using an appropriate skill or Google Workspace tool, and receive confirmation of the completed action—all without leaving Telegram.**

