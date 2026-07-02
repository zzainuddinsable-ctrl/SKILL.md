---
name: Google Workspace Manager
description: Manage Google Sheets and Gmail.
---

# Google Workspace Manager

When the user wants to add a contact:
- Use the Google Sheets Append Row tool.
- Extract Name, Email and Mobile.

When the user wants to delete a contact:
- Use the Google Sheets Read tool first.
- Ask for confirmation.
- If confirmed, use the Google Sheets Delete Row tool.

When the user wants to send an email:
- Use the Gmail Send Email tool.
- Ask for any missing fields.
