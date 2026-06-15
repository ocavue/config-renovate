# config-renovate

My [shareable](https://docs.renovatebot.com/config-presets/) [Renovate](https://github.com/renovatebot/renovate) preset.

## Setup

1. Install the [Renovate GitHub App](https://github.com/apps/renovate).
2. Add `renovate.json` to your repo:

   ```json
   { "extends": ["github>ocavue/config-renovate"] }
   ```

3. Approve updates from the **Dependency Dashboard** issue Renovate opens.

## What you get

- **Approval-gated.** Updates wait for your tick on the Dependency Dashboard.
- **Batched.** Patch, minor, and digest updates land in one PR.
- **Isolated majors.** Each major update gets its own PR.
- **Stability windows.** Minor waits 1 day, major 7 days.
- **Noise control.** Packages that release constantly are throttled to about one update a month.

## Sponsors

<p align="center"><a href="https://github.com/sponsors/ocavue"><img src="https://cdn.jsdelivr.net/gh/ocavue/sponsors/sponsorkit/sponsors.svg" alt="My Sponsors"></a></p>

## License

MIT
