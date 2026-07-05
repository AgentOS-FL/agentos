# AgentOS Technical Architecture v1.0

## 1. Product Category

AgentOS is the AI Operating System for Real Estate.

It is not a CRM. CRM, IDX, marketing, transactions, communications, and documents are capabilities inside the operating system.

---

## 2. Core Architecture

AgentOS is built around four layers:

1. Experience Layer
2. Intelligence Layer
3. Nexus Platform Layer
4. Data Layer

---

## 3. Experience Layer

Includes:

- Web application
- Future mobile application
- Home Workspace
- Contact Workspace
- Property Workspace
- Listing Workspace
- Transaction Workspace
- Command
- Attention Center

---

## 4. Intelligence Layer

Includes:

- Ava
- Agent Intelligence Engine
- Opportunity Engine
- Recommendation Engine
- Memory Engine
- Explainability Engine
- Content Engine

Ava is limited to:
- Real estate
- Agent success
- Marketing

---

## 5. Nexus Platform Layer

Nexus is the AgentOS kernel.

Includes:

- Identity
- Permissions
- Business Graph
- Knowledge Graph
- Event Bus
- Timeline
- Search
- AI Gateway
- Integration Layer

---

## 6. Data Layer

Primary source of truth:

- PostgreSQL

Supporting services:

- Redis
- OpenSearch
- Object storage

---

## 7. Core Business Objects

- Person
- Property
- Listing
- Transaction
- Document
- Opportunity
- Mission
- Action
- Event
- Organization

---

## 8. Engineering Rules

- API-first
- Event-driven
- PostgreSQL is the source of truth
- Ava never bypasses Nexus
- Workspaces never talk directly to each other
- Services publish events
- Business logic never lives only in the UI
- Every recommendation must be explainable
- Every feature must create more opportunity

---

## 9. MVP Focus

MVP includes:

- Nexus foundation
- Ava Morning Brief
- Home Workspace
- Contact Workspace
- Business Graph
- Event Bus
- Command
- Attention Center

---

## 10. First Build Slice

Daily Success Loop:

1. Operator logs in
2. Home Workspace loads
3. Ava generates Morning Brief
4. Top Plays appear
5. Operator opens Contact
6. Operator logs communication
7. Event is created
8. Timeline updates
9. Business Graph updates
10. Ava updates future recommendations
