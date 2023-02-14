# config-renovate

My [shareable](https://docs.renovatebot.com/config-presets/) config preset for [Renovate](https://github.com/renovatebot/renovate)

## Setup

1. Install and config [Renovate GitHub App](https://github.com/apps/renovate).
2. Add `renovate.json` to your repo, or add a `"renovate"` field in your `package.json`, with the following content:

   ```json
   {
     "extends": ["github>ocavue/config-renovate"]
   }
   ```
