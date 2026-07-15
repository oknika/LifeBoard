# LifeBoard Architecture

## Vision

LifeBoard is an offline-first personal desktop application.

The application should remain fully functional without an internet connection.

Synchronization with a remote PostgreSQL server is an optional capability, allowing multiple devices to share the same data in the future.

---

## Core Principles

- Offline First
- Modular Architecture
- Maintainable Code
- Clean Separation of Responsibilities
- Long-term Evolution

---

## Planned Clients

- Windows Desktop (WPF) ✅
- Mobile (Future)
- Web (Future)

---

## Synchronization Strategy

Local database

↓

Synchronization

↓

Remote PostgreSQL (VPS)
