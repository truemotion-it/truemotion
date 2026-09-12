# Voice Architecture

Truemotion separates the public website, application logic, provider layer, and credentials.

```text
Public Website
     ↓
Application Backend
     ↓
Voice API / SIP / Webhooks
     ↓
Communications Provider
     ↓
PSTN / SIP Destinations
```

Provider credentials belong only in server-side secrets.
