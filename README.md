# TraceNow 

TraceNow is a 100% scoped ServiceNow data migration application. It allows administrators to safely extract, queue, and seamlessly import complex record payloads (including their deep-related hierarchies and sys_attachments) across environments.

### Key Features
* **Ghost Origin Architecture:** Bypasses core platform scope restrictions during XML imports natively from the client-side, requiring zero Global Script Includes.
* **Flawless History Preservation:** Maintains exact `sys_id`s, Incident Numbers, and historical audit logs during migration.
* **Interactive Dashboard:** Real-time queue monitoring, export polling, and migration history tracking.

### Deployment
To deploy TraceNow to a new instance:
1. Navigate to **Studio** > **Import From Source Control**.
2. Paste this repository URL and provide your credentials.
3. ServiceNow will automatically build the application in your environment.
