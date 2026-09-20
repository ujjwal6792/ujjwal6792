# Ujjwal Sharma

**Senior Software Engineer · Software Architect**

I design and build distributed systems, backend platforms, and operational software — from system models and API contracts through implementation, infrastructure, and the applications built on top of them.

My current work is focused on **distributed networks, digital public infrastructure, offline-first systems, backend architecture, identity & trust, and field operations**.

## Selected work

### [Signals DPG](https://github.com/Blue-Dots-Economy/signals-dpg)

**Architecture · System Design · Implementation Lead**

Architected and implemented the foundations of an extensible, governed network stack designed for independently operated participants and instances to interoperate.

My work includes:

* Network, Domain, Item, and Action abstractions
* schema and configuration-driven platform behaviour
* inter-instance communication and lifecycle flows
* network governance and participant models
* reusable architecture across multiple domain-specific networks

### [Notification Service](https://github.com/Blue-Dots-Economy/notification-service)

**Architecture · Design · Implementation**

Designed and built shared notification infrastructure used across platform applications.

The system provides:

* provider-independent email, SMS, WhatsApp, and social delivery
* Redis-backed asynchronous processing
* priority queues
* retries and exponential backoff
* dead-letter handling
* request deduplication
* signed service requests
* provider discovery and operational metrics

### Ritideck / Ritiflow

**Founder · Software Architect**

Building a field-operations platform designed for real-world environments where connectivity, device trust, deployment constraints, and operational reliability matter.

Architecture includes:

* offline-first field execution and reconciliation
* encrypted local data and signed operational evidence
* trusted Android installations and device integrity signals
* background location and route execution
* geofenced and dynamic-QR attendance
* configurable forms and proof-of-work capture
* self-hosted and SaaS deployment models
* self-hosted OpenStreetMap, OSRM, and Nominatim infrastructure

### [pg-studio](https://github.com/ujjwal6792/pg-studio)

**Creator · Rust**

A Rust CLI and terminal UI for running Drizzle Studio independently of an existing Drizzle project.

Supports:

`PostgreSQL` · `SQLite` · `Cloudflare D1` · `Turso` · `MySQL`

with SSH tunnelling, native OS keychain storage, multi-project management, database backup/restore, and automated Drizzle configuration.

### [ESP32-S3 Wireless KVM](https://github.com/ujjwal6792/ESP32-S3-Wireless-KVM)

**Creator · C++ / ESP32**

A four-device wireless KVM built around the ESP32-S3 that turns a wired USB keyboard into a multi-device Bluetooth keyboard with device switching and hardware-level macros.

## Engineering focus

| Area               | Technologies & Topics                                                                                         |
| ------------------ | ------------------------------------------------------------------------------------------------------------- |
| **Backend**        | TypeScript, Node.js, Fastify, PostgreSQL, Redis, Drizzle ORM, Better Auth                                     |
| **Systems**        | Rust, Axum, Tokio, SQLite                                                                                     |
| **Frontend**       | React, Vite, Tailwind CSS, shadcn/ui, Svelte, Astro                                                           |
| **Mobile**         | Expo, React Native                                                                                            |
| **Infrastructure** | Docker, AWS, Cloudflare, Nginx                                                                                |
| **Architecture**   | Distributed systems, governed networks, offline-first design, REST/OpenAPI, identity & trust, device security |

## What I work on

I am particularly interested in engineering problems where application code is only one part of the system:

* designing service and domain boundaries that can evolve without constant rewrites
* building interoperable network architectures instead of single-instance applications
* designing software that continues operating with unreliable or absent connectivity
* authentication, cryptographic signing, installation trust, and device-integrity systems
* backend platforms built around PostgreSQL and Redis
* operational software that connects digital systems with physical-world workflows
* developer tooling that removes repetitive infrastructure and engineering work

---

Most of my professional work lives across organization repositories. The projects above describe the areas where I have had direct architecture, design, implementation, or technical-lead responsibility.
