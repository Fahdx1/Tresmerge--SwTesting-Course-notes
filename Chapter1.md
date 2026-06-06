# Software Testing Course 

---

##  TL;DR

| Topic | Key Concept |
|---|---|
| **Fundamentals** | Why & how testing works; types of tests |
| **Testing Pyramid** | Unit → Integration → E2E hierarchy |
| **Unit Testing** | Isolated, fast, implementation-focused |
| **Integration Testing** | Tests component interactions |
| **End-to-End Testing** | Full user flow simulation |
| **Automation Testing** | Primary focus; demonstrates real business value |
| **TDD** | Write tests first, then code |
| **BDD** | Human-readable tests; bridges technical & non-technical |
| **Mocking** | Fake dependencies for cleaner, isolated tests |
| **Performance Testing** | Load/stress testing with JMeter |
| **SLAs** | Define thresholds; prevent failures proactively |

---

## Foundations

### Fundamentals of Software Testing
what it means, why it matters, and how it fits into software development. It also surveys the major **classifications and types** of tests so you have a mental map before diving deeper.

- Why is testing essential in software development?
- How is testing performed in practice?
- What are the different **types and classifications** of tests?

---

### The Testing Pyramid
 **Testing Pyramid** — a model that organizes tests by scope, speed, and cost. It explains why the bulk of tests should sit at the lowest level and why fewer tests exist at higher levels.

```
         ┌─────────────┐
         │  End-to-End │   ← Fewest, slowest, most expensive
         ├─────────────────┤
         │   Integration   │
         ├─────────────────────┤
         │       Unit Tests      │   ← Most, fastest, cheapest
         └─────────────────────┘
```

---

## Core Testing Levels

### Three Levels of Testing

The curriculum walks through all three main levels with progressively wider scope:

- **Unit Testing** — Tests a single function or component *in isolation*. Strong practical focus with real implementation examples.
- **Integration Testing** — Tests how multiple components interact with each other.
- **End-to-End (E2E) Testing** — Tests a full user flow through the entire system, simulating real-world usage.

---

## Automation & Methodology

### Manual vs Automation Testing

Difference between **manual testing** and **automation testing**, with a deliberate emphasis on automation.

> 💡 **Key Insight:** Automation testing is not an "extra" — it is a core engineering practice that saves time and prevents regressions. Many companies incorrectly view it as optional.

---

### TDD — Test-Driven Development
 how to **write tests before writing code**. Tests define the expected behavior, and the code is then written to make those tests pass.

- Enforces better design from the start
- Reduces bugs introduced during development
- Flow: *Write test → See it fail → Write code → See it pass → Refactor*

---

### BDD — Behavior-Driven Development
- Bridges the gap between **developers, testers, and non-technical stakeholders**
- Tests are expressed in **plain, human-readable language**
- Makes requirements and expected behavior explicit and shared

---

### Mocking for Better Code Quality

**Mocking** is a technique for replacing real dependencies (databases, APIs, external services) with controlled fake versions during tests.
- Isolates the unit under test from external systems
- Makes tests faster, more reliable, and easier to maintain
- Leads to **cleaner, more modular code**
---

## Performance & Reliability

### Performance Testing with JMeter

how an application behaves **under load and pressure**.
- Simulates high-traffic and stress scenarios
- Measures **response times, throughput, and bottlenecks**
- **JMeter** is introduced as one of the most widely used industry tools for performance testing

---

### System Requirements & SLAs

define **system requirements** and establish **Service Level Agreements (SLAs)** — formal commitments about performance and availability thresholds.

- Helps **predict and prevent failure scenarios** before they reach production
- SLAs set clear expectations for uptime, response time, and reliability

> ⚠️ **Instructor Note:** Defining SLAs is acknowledged as a challenging task, but a critical one for production-ready systems.

