# Manual vs Automated Software Testing
---
## TL;DR
- Manual testing is straightforward to start but becomes a bottleneck as the codebase grows.
- Automated testing requires an upfront investment but delivers **speed, consistency, and confidence** at scale.
- Beyond just finding bugs, automated testing actively **improves how code is written**.
- If code is hard to test, that is not a testing problem — it is a **code design problem**.

---

## What is Software Testing?

Software testing is the process of verifying that an application **works as expected** and produces the **accurate results** the developer intended. There are two primary ways to do this: **manual testing** and **automated testing**.

---

## Manual Testing

performing actions tby myself to verify that every feature works correctly.

- **Time-consuming by nature.** Every time a new feature is added, the tester must launch the app, log in, and navigate through multiple steps just to reach and test that one feature.
- **Does not scale well.** As the application grows, the tester must re-test everything repeatedly to make sure nothing has broken — the workload keeps increasing.
- **Limited impact on code quality.** Manual testing can uncover bugs, but it does not push developers to write better or more structured code.

---

## Automated Testing

Writing code that tests the application's code — letting the machine do the checking.

- **Faster than manual testing.** Since tests run on a machine, they execute far more quickly than a human navigating through an app.
- **Provides confidence during changes.** When adding new features or refactoring, automated tests confirm that existing business logic has not broken — this is known as **regression testing**.
- **Improves code quality.** Writing tests pushes developers toward more **modular, well-structured code** — for example, using parameters instead of global variables to make functions easier to test.
- **Acts as a code quality signal.** If a piece of code is too difficult to test, that is a clear sign it needs to be rewritten in a simpler, cleaner way.

---

## Effort and Cost Over Time

| | Manual Testing | Automated Testing |
|---|---|---|
| **Initial effort** | Low | Higher (writing test cases takes time upfront) |
| **Effort over time** | Increases linearly with app size | Stays relatively flat after initial investment |
| **Reusability** | None — every check is repeated manually | Tests are written once and reused throughout the app's life |
| **Long-term value** | Low — same high effort every time | High — repetitive checks run automatically at no extra cost |

> The core trade-off: automated testing costs more time upfront, but pays back significantly over the lifetime of the application.

---
