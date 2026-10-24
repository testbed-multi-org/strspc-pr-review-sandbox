# strspc-pr-review-sandbox

Synthetic e2e sandbox for [`SteerSpec/strspc-pr-review`](https://github.com/SteerSpec/strspc-pr-review).
The `e2e/pr-auto-approve/run.sh` harness opens throwaway PRs here and checks the bot's decisions.
Copilot reviews are simulated by the harness reviewer (`test-copilot-logins`), so no real Copilot
review is spent. Nothing in this repo is meant to be merged or reused.
