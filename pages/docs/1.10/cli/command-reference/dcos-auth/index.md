---
layout: layout.pug
title: dcos auth
menuWeight: 1
excerpt:
featureMaturity:
enterprise: false
navigationTitle:  dcos auth
---

# Description
This command manages DC/OS identity and access.

# Usage

```bash
dcos auth 
```

# Options

| Name, shorthand | Default | Description |
navigationTitle:  dcos auth
|---------|-------------|-------------|
| `--help, h`   |             |  Print usage. |
| `--info`   |             |  Print a short description of this subcommand. |
| `--version, v`   |             | Print version information. |

# Child commands

| Command | Description |
navigationTitle:  dcos auth
|---------|-------------|
|[dcos auth list-providers](/docs/1.10/cli/command-reference/dcos-auth/dcos-auth-list-providers/) | List configured authentication providers for your DC/OS cluster. |  
| [dcos auth login](/docs/1.10/cli/command-reference/dcos-auth/dcos-auth-login/)   |   Log in to DC/OS authentication.  |  
| [dcos auth logout](/docs/1.10/cli/command-reference/dcos-auth/dcos-auth-logout/)   |  Log out of DC/OS authentication.  |  