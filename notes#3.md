# The Testing Pyramid & Testing Tools

## TL;DR

Tools we gonna use in testing with x in y :

| Type            | When to Use                               | Recommended Tools     |
| --------------- | ----------------------------------------- | --------------------- |
| **Unit**        | Isolated logic, algorithms, calculations  | Jest, Vitest, Jasmine |
| **Integration** | API interactions, component communication | Jest, Vitest, Mocha   |
| **E2E**         | Real user flows, full scenario validation | Cypress, Playwright   |
| **Performance** | Load testing, stress testing              | JMeter                |


## The Testing Pyramid

<img src="https://testgrid.io/blog/wp-content/uploads/2025/01/testing-pyramid.png" alt="Description of image" width="500" height="300">


## When to Use Each Type

- **Unit Testing** : best for isolated, self-contained logic like complex calculations or algorithms
- **Integration Testing** : reach for this when you are working with APIs or testing how different parts of the system interact with each other.
- **E2E Testing** : use this to validate real user scenarios, the kind of flows an actual client would go through in your application
