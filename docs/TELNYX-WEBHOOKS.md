# Telnyx Webhook Architecture

Suggested server route: `/api/webhooks/telnyx`

Events can represent call initiation, ringing, answer, hangup, recordings, messages, and operational state. The exact event names and verification process must follow the current official Telnyx documentation used by the application.

## Safety

- Keep signing secrets and API keys server-side.
- Validate webhook authenticity before processing events.
- Log event identifiers without logging secrets.
- Make handlers idempotent where possible.
- Separate public website code from provider credentials.
