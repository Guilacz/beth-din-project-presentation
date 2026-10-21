# Beth Din Mishkanot Yaakov
### Bilingual Website & Case Management Platform

Developed independently for **Beth Din Mishkanot Yaakov**, a rabbinical court actively using the platform.

A complete web application combining a bilingual public website with dedicated workspaces for clients, judges, and administrators — supporting case submission, document sharing, payments, and day-to-day administration.

**[Visit the live website →](https://bethdinmishkanotyaakov.netlify.app/)**

## Screenshots

### Homepage — Hebrew interface

<img width="1902" height="902" alt="Capture d&#39;écran 2026-10-21 164630" src="https://github.com/user-attachments/assets/9ef686fc-8439-4901-9dff-9218d4091480" />

### Administration Dashboard

<img width="1901" height="905" alt="image" src="https://github.com/user-attachments/assets/417a42ae-1d0a-4b82-bc0e-94e78d542622" />

### Case Tracking
*Demonstration case using fictional data.*

<img width="1890" height="898" alt="image" src="https://github.com/user-attachments/assets/8f117a7e-665d-465e-b12c-2bc9ca247d5d" />


## My Role

As the sole developer, I built the platform end to end: interface design, frontend development, database structure, authentication, access policies, backend workflows, payment integration, testing, and deployment.

## Key Features

- **Bilingual experience:** English and Hebrew, with language switching and responsive layouts supporting both left-to-right and right-to-left reading.
- **Dedicated portals:** separate dashboards for clients, judges , and administrators.
- **Case management:** online submissions, approval workflows, judge assignments, and status tracking.
- **Case collaboration:** document uploads, shared discussions, unread indicators, and notifications.
- **Payments:** Nedarim integration with server-side payment confirmation.
- **Content administration:** management of articles, Q&A, published stories, and contact messages.

## Engineering Highlights

### Access Control
PostgreSQL Row Level Security policies and server-side authorization restrict access according to user roles and participation in each case.

### Payment Processing
HMAC signature verification validates payment callbacks, while a payment ledger helps prevent duplicate processing.

### English & Hebrew Support
Shared translation modules and layout adaptations provide a consistent bilingual experience across public pages and authenticated dashboards.

### Testing
Node.js tests cover payment logic and application workflows. Isolated PostgreSQL fixtures test selected database access policies.

## Tech Stack

| Area | Technologies |
| --- | --- |
| Frontend | HTML, CSS, Vanilla JavaScript |
| Authentication & Data | Supabase Auth, PostgreSQL, Supabase Storage |
| Server-side Logic | Supabase Edge Functions, TypeScript |
| Payments | Nedarim |
| Testing | Node.js Test Runner, PGlite |
| Hosting | Netlify |

## Source Code

This repository presents the project and its features. The source code is maintained in a private repository.

Code review access can be arranged on request for recruitment purposes.

## Contact

You can find me on [GitHub — Guilacz](https://github.com/Guilacz).
