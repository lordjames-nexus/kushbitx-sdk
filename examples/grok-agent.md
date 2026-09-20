# Example: xAI Grok agent (read-only)

Working integration for [issue #1](https://github.com/kushBitxHQ/kushbitx-sdk/issues/1).

- Repo: https://github.com/lordjames-nexus/kushbitx-grok-agent
- Framework: xAI Grok function-calling (`https://api.x.ai/v1`)
- SDK: `@kushbitx/sdk@0.1.0` from npm
- Tools (exactly three, read-only):
  1. `kushbitx_preview_token`
  2. `kushbitx_evaluate_spend` (advisory SpendGuard)
  3. `kushbitx_get_payment_challenge` (unsigned HTTP 402)
- Live evidence: https://github.com/lordjames-nexus/kushbitx-grok-agent/blob/main/evidence/run-output.txt
- Tests: `npm test` in that repo (CI on `main`)

No signing, payment, keys, recovery, or policy mutation.
