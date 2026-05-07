---
layout: default
title: Permissions
description: Required VERSA permissions and purpose.
permalink: /permissions/
---

## Permissions Guide

### View Channels

Lets VERSA detect channels where commands are used.

### Send Messages

Required for command responses and moderation output.

### Embed Links

Used for richer moderation and log formatting.

### Read Message History

Used for context-aware moderation actions.

### Use Slash Commands

Required for `/` commands.

### Manage Messages

Used where moderation actions include message cleanup flows.

### Moderate Members

Required for timeout/restriction style moderation features.

### Ban Members

Required when ban/unban modules are enabled.

## Permission Checks

If commands fail in one channel but not another, compare:

1. **Server Settings → Roles → VERSA**
2. **Edit Channel → Permissions** overrides
