# Testing React Apps
***Automated Testing***

- What is “Testing”? and Why?
- Understanding Unit Tests
- Testing React Components & Building Blocks

**What is “Testing”?**

- **Manual Testing**

Write Code → Preview & Test in Browser → Improve Code → Repeat

Very important: You see what your users will see

***Error-prone:*** It’s hard to always test all possible combinations & scenarios

- **Automated Testing**

Write code that automatically tests your code

You test the individual building blocks of your app

Requires extra knowledge (→ how to write tests) but allows you to test all building blocks of your app

**Different Kinds Of Automated Tests**

- **Unit Tests**

Test the ***individual*** ***building blocks*** (functions, components) in ***isolation***

Projects typically contain dozens or hundreds of unit tests

***The most common / important kind of test***

- **Integration Tests**

Test the ***combination*** of multiple building blocks

Projects typically contain  couple of integration tests

***Also important, but focus on unit tests in most cases***

- **End-to-End (E2E) Tests**

Test complete scenarios & user flows in your app (as the user would experience them)

Projects typically contain only a few E2E tests

***Important but can also be done manually (partially)***

**What Should You Test?**

**What?**

Test the different app building blocks

***Unit test:*** The smallest building blocks that make up your app

**+**

**How?**

Test success and error cases, also test rare (but possible) results

**Required Tools & Setup**

We need a tool or running our tests and asserting the results → ***Jest***

[Jest](https://jestjs.io/)

**+**

We need a tool for “simulating” (rendering) our React app / components **→** ***React Testing Library***

[React Testing Library | Testing Library](https://testing-library.com/docs/react-testing-library/intro/)

Both tools are already set up for you when using create-react-app

**Writing Tests — The Three “A”s**

***Arrange***: Set up the test data, test conditions and test environment

***Act***: Run logic that should be tested (e.g., execute function)

***Assert***: Compare execution results with expected results

[ARIA in HTML](https://www.w3.org/TR/html-aria/#docconformance)

https://github.com/testing-library/react-hooks-testing-library

[Introduction | React Hooks Testing Library](https://react-hooks-testing-library.com/)
