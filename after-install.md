# Hermes Agent installation

This repository is a portable Agent Plugins v1 package for Hermes Agent.

Install from the GitHub repository:

```bash
hermes plugins install ali2000hos/persian-writing --enable
```

The package provides the `persian-writing` skill. Confirm that the plugin is active:

```bash
hermes plugins list
```

The package is installed with full local-plugin trust. Its skill contains
writing guidance and local, standard-library Python scripts; it does not add
network services, credentials, or MCP servers.

For a non-activating install, use `--no-enable` and later run:

```bash
hermes plugins enable persian-writing
```
