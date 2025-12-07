# 30 Full-Stack Projects: React + NestJS + PostgreSQL
## Beginner to Expert Learning Path

---

## 🟢 Beginner (Projects 1-10)
*Focus: Basic CRUD, REST communication, simple components, TypeORM basics*

### 1. Task Checklist
**Build:** Simple todo list with add, complete, delete
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| useState, forms, lists | Single module, controller, service | One table: tasks |
**Learn:** Full request cycle from UI → API → DB and back

### 2. Contact Manager
**Build:** Store names, emails, phone numbers with search
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Controlled inputs, filtering | DTOs, validation pipes | Contacts table with constraints |
**Learn:** Input validation on both frontend and backend

### 3. Expense Logger
**Build:** Log expenses with category, amount, date
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Date inputs, number formatting | Query parameters for filtering | DATE type, aggregations |
**Learn:** Working with dates and basic SQL aggregations

### 4. Bookmark Manager
**Build:** Save URLs with titles, tags, and favicon fetch
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Link previews, tag chips | HttpModule for fetching metadata | Array columns for tags |
**Learn:** External HTTP calls from NestJS

### 5. Note-Taking App
**Build:** Create, edit, delete notes with rich text
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| React-Quill or TipTap editor | TEXT columns, CRUD endpoints | Full-text content storage |
**Learn:** Handling rich text/HTML content safely

### 6. Poll/Survey Creator
**Build:** Create polls, vote, see results
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Radio buttons, bar charts | Increment vote counts | Polls → Options relationship |
**Learn:** First one-to-many relationship

### 7. Recipe Box
**Build:** Store recipes with ingredients and steps
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Dynamic form arrays | Nested DTOs | JSON columns for ingredients |
**Learn:** Storing structured JSON in Postgres

### 8. Habit Tracker
**Build:** Track daily habits with streak counting
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Calendar grid, streak display | Date-based queries | Habit logs with dates |
**Learn:** Complex date queries and grouping

### 9. Flashcard Study App
**Build:** Create decks, flip cards, track progress
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Card flip animations, state | Nested resources (decks/cards) | Parent-child relationships |
**Learn:** Nested REST resources and cascade operations

### 10. Personal Budget Dashboard
**Build:** Income vs expenses with monthly breakdown
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Recharts for visualization | Aggregation endpoints | GROUP BY month queries |
**Learn:** Building dashboard APIs with aggregated data

---

## 🟡 Intermediate (Projects 11-20)
*Focus: Authentication, relationships, file uploads, state management*

### 11. User Authentication System
**Build:** Register, login, logout, password reset
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Auth context, protected routes | Passport.js, JWT, Guards | Users table, hashed passwords |
**Learn:** Complete auth flow with JWT tokens

### 12. Blog Platform
**Build:** Posts, comments, likes with user ownership
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| React Router, markdown preview | Relations, auth guards | Users → Posts → Comments |
**Learn:** Multi-level relationships and ownership

### 13. File Storage Service
**Build:** Upload, organize, and download files
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Drag-drop upload, progress bars | Multer, streaming responses | File metadata storage |
**Learn:** Binary file handling and storage strategies

### 14. Team Task Board
**Build:** Kanban board with drag-and-drop
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| react-beautiful-dnd, optimistic updates | PATCH for position updates | Order column, board → columns → tasks |
**Learn:** Ordering logic and optimistic UI updates

### 15. Event Calendar
**Build:** Create events, recurring events, reminders
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| FullCalendar or custom grid | RRule for recurrence | TIMESTAMP WITH TIME ZONE |
**Learn:** Time zones and recurring event patterns

### 16. Inventory Management
**Build:** Products, stock levels, low-stock alerts
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Tables with sorting/filtering | TypeORM query builder | Transactions for stock updates |
**Learn:** Database transactions and data integrity

### 17. Multi-User Chat App
**Build:** Rooms, real-time messages, online status
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Socket.io-client, message list | WebSocket gateway | Messages table, user presence |
**Learn:** WebSockets and real-time communication

### 18. Social Media Feed
**Build:** Posts, follows, personalized feed
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Infinite scroll, like animations | Complex feed queries | Self-referential follows table |
**Learn:** Many-to-many relationships and feed algorithms

### 19. E-Commerce Storefront
**Build:** Products, cart, wishlist, checkout flow
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Cart context, checkout wizard | Order processing logic | Products, Orders, OrderItems |
**Learn:** Multi-step transactions and order management

### 20. Issue Tracker
**Build:** Projects, issues, assignments, status workflow
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Filter panels, status badges | State machine for status | ENUM types, activity logs |
**Learn:** Workflow/state management and audit trails

---

## 🟠 Advanced (Projects 21-26)
*Focus: Caching, queues, testing, permissions, performance*

### 21. Learning Management System
**Build:** Courses, lessons, quizzes, progress tracking
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Video player, progress bars | Role guards (student/instructor) | Enrollment, progress tables |
**Learn:** Role-based access control (RBAC)

### 22. Appointment Booking System
**Build:** Availability slots, booking, confirmations
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Time slot picker, conflict UI | Pessimistic locking for slots | Availability, bookings, conflicts |
**Learn:** Concurrency handling and locking strategies

### 23. Real-Time Analytics Dashboard
**Build:** Live metrics, charts, data streaming
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| SSE/WebSocket charts, auto-refresh | Server-Sent Events, aggregation | TimescaleDB or time-series patterns |
**Learn:** Time-series data and streaming updates

### 24. Job Queue System
**Build:** Background jobs with retry, status tracking
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Job status UI, retry buttons | Bull queue, job processors | Job status persistence |
**Learn:** Background processing with Bull/Redis

### 25. API Gateway with Caching
**Build:** Aggregate external APIs, cache results
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Loading skeletons, cache indicators | Redis caching, cache invalidation | Cache metadata storage |
**Learn:** Caching strategies and cache invalidation

### 26. Fully Tested Application
**Build:** Refactor project 19 or 20 with complete test coverage
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Jest + React Testing Library | Jest + Supertest, e2e tests | Test database, fixtures |
**Learn:** Testing strategies across the full stack

---

## 🔴 Expert (Projects 27-30)
*Focus: Scalability, microservices, deployment, production patterns*

### 27. Multi-Tenant SaaS Platform
**Build:** Organizations, members, isolated data, billing
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Org switcher, member management | Tenant middleware, scoped queries | Row-level security or schema separation |
**Learn:** Multi-tenancy patterns and data isolation

### 28. Microservices E-Commerce
**Build:** Decompose project 19 into services
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| Unified UI, service aggregation | User, Product, Order, Payment services | Database per service |
**Additional:** RabbitMQ/Kafka for events, API Gateway
**Learn:** Service decomposition and event-driven architecture

### 29. Real-Time Collaboration Tool
**Build:** Collaborative document editing (like Notion)
| React | NestJS | PostgreSQL |
|-------|--------|------------|
| CRDT/OT for sync, presence cursors | WebSocket rooms, conflict resolution | Document versions, operations log |
**Learn:** Collaborative editing algorithms and conflict resolution

### 30. Production-Ready Starter Template
**Build:** Complete boilerplate with all best practices

**React Features:**
- TypeScript strict mode
- React Query for server state
- Zustand/Redux for client state
- Route-based code splitting
- Error boundaries
- Storybook component library

**NestJS Features:**
- Modular architecture
- JWT + Refresh tokens + OAuth2
- RBAC with CASL
- Request validation and transformation
- Swagger documentation
- Health checks and graceful shutdown
- Structured logging (Pino)
- Rate limiting

**PostgreSQL Features:**
- TypeORM with migrations
- Soft deletes
- Audit columns (created_at, updated_at, deleted_at)
- Database seeding
- Connection pooling

**DevOps:**
- Docker + docker-compose
- CI/CD pipeline (GitHub Actions)
- Environment configuration
- Prometheus metrics
- Sentry error tracking

---

## Concept Progression Map

```
Level        React                    NestJS                   PostgreSQL
─────────────────────────────────────────────────────────────────────────────
Beginner     useState, useEffect      Modules, Controllers     Single tables
             Forms, Lists             Services, DTOs           Basic queries
             
Intermediate React Router             Guards, Pipes            Relationships
             Context API              WebSockets               Transactions
             State libraries          File uploads             JSON columns
             
Advanced     Real-time UI             Queues, Caching          Locking
             Testing                  Testing, RBAC            Time-series
             Performance              Background jobs          Optimization
             
Expert       Code splitting           Microservices            Multi-tenancy
             Collaboration            Event-driven             Replication
             Design systems           API Gateway              Sharding
```

---

## Recommended Development Flow

1. **Database First** — Design schema, run migrations
2. **API Second** — Build endpoints, test with Swagger
3. **UI Last** — Connect React to working API

---

## Tips for Full-Stack Learning

1. **Use TypeScript everywhere** — shared types between React and NestJS
2. **Generate API clients** — use OpenAPI generator from NestJS Swagger
3. **Containerize early** — docker-compose from project 5 onwards
4. **Version your API** — `/api/v1/` from the start
5. **Handle errors consistently** — error boundaries (React) + exception filters (NestJS)
6. **Log everything** — structured logging helps debugging
7. **Deploy incrementally** — Vercel (React) + Railway/Render (NestJS + Postgres)
