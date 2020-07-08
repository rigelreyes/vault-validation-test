Validation Testing Framework for vault built in ansible.

Checks API entrypoints for Status 200 on:
- Init
- Seal
- Tokens
- Metrics
- Audit

A tester and a telemetry policies should be added first with a token, or use root token for the requests but that is not recommended.