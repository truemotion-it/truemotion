# Telnyx Setup Guide

This guide prepares the account and application structure without bypassing Telnyx verification.

1. Open the official Telnyx Mission Control Portal.
2. Sign in or create the business account through the official Telnyx flow.
3. Complete any identity or account-level verification requested by Telnyx.
4. Create API credentials in the official portal.
5. Store API credentials only in server-side secrets or a local .env file excluded from Git.
6. Configure a voice application or SIP connection as required by the real use case.
7. Configure webhook endpoints on a server you control.
8. Verify webhook authenticity using the provider's current documented mechanism.
9. Purchase or configure phone numbers only after account approval and regulatory requirements are satisfied.
10. Test calls in a controlled environment before production use.

Never place Telnyx API keys, passwords, GitHub tokens, or private account emails in public HTML, JavaScript, README files, or repositories.
