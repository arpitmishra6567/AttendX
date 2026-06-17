# AttendX Architecture

AttendX uses a clean full-stack structure:

- **frontend/**: Next.js + React UI for attendance workflows, analytics, and dashboards.
- **backend/**: Node.js/Express APIs for authentication, attendance events, and reporting.
- **Database**: PostgreSQL for persistent attendance and user data.

## Data Flow
1. Frontend sends authenticated requests to backend APIs.
2. Backend validates request/auth context and applies business rules.
3. Backend reads/writes PostgreSQL and returns typed responses.
4. Frontend renders updates in dashboards and reports.
