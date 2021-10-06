# Voiceflow Renovate config

## Usage

To use this preset in a repository, add the following `renovate.json` file to the repository root:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>voiceflow/renovate-config"]
}
```

This may be extended and modified to the needs of your repository with any of the configuration options specified in the [Renovate docs](https://docs.renovatebot.com/configuration-options/).

### Per-team presets

There are also per-team presets which are preferred to the generic one when possible.

#### Creator

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>voiceflow/renovate-config:creator"]
}
```

#### Integrations

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>voiceflow/renovate-config:integrations"]
}
```

#### Infrastructure

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>voiceflow/renovate-config:infrastructure"]
}
```
