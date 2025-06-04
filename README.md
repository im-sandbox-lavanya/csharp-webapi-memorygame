## Fundamentals of testing

In this module we will explore the fundamentals of testing and see how Copilot can help us
explore the different types of testing.

Let's see what Copilot knows about testing.

```markdown
What are the different types of testing?
```

<details>
<summary><strong>View Response</strong></summary>
<blockquote>

Testing can be broadly categorized into several types, each serving a distinct purpose in
the software development lifecycle. Here are some of the key types:

**Unit Testing**: Tests individual units or components of a software to ensure that each
part functions correctly in isolation.

**Integration Testing**: Checks if different modules or services used by your application
interact with each other correctly.

**Functional Testing**: Verifies that each feature of the software operates in conformance
with the requirement specification.

... output truncated ...

</blockquote>
</details>

```markdown
Tell me about unit testing
```

<details>
<summary><strong>View Response</strong></summary>
<blockquote>

Unit testing is a software testing method where individual units or components of a
software are tested in isolation from the rest of the application. The primary goal of
unit testing is to validate that each unit of the software performs as designed. A unit is
the smallest testable part of any software and often corresponds to a single function,
method, procedure, module, or object.

### Key Characteristics of Unit Testing

- **Isolation**: Unit tests are performed in isolation from other units or components,
  often using mock objects or stubs to simulate interactions between units.
- **Automation**: Unit tests are typically automated, meaning they can be run quickly and
  frequently without manual intervention.
- **Documentation**: They serve as a form of documentation that describes what the code is
  supposed to do.
- **Development Methodology**: Often associated with agile development methodologies, but
  can be used in any development process.

### Benefits of Unit Testing

- **Early Bug Detection**: Bugs are detected early in the development cycle, making them
  less expensive to fix.
- **Facilitates Change**: It makes it safer and easier to refactor code or upgrade system
  libraries because it quickly indicates if the change in one part breaks another part.
- **Simplifies Integration**: By ensuring that each unit works correctly in isolation,
  integration of these units becomes less error-prone.
- **Design Feedback**: Writing tests can provide feedback on the design of the system; if
  a unit is hard to test, it may also be hard to use.
- **Documentation**: Provides documentation on how a particular piece of the application
  should behave.

... output truncated ...

</blockquote>
</details>

```markdown
Tell me about automated testing
```

<details>
<summary><strong>View Response</strong></summary>
<blockquote>

Automated testing is a method in software testing where testing tools and scripts are used
to execute tests on the software automatically, without manual intervention. This approach
is used to run tests repetitively over time, ensuring that the software being tested
behaves as expected.

### Key Characteristics of Automated Testing

- **Speed and Efficiency**: Automated tests can be run quickly and repeatedly, which is
  much faster than manual testing.
- **Reusability**: Test scripts are reusable across different versions of the software,
  even if there are changes in the source code.
- **Consistency**: Ensures that tests are performed consistently every time they are run,
  eliminating human error.
- **Coverage**: Enables testing of a large number of test cases in a short amount of time,
  improving the overall quality of the software.
- **Integration**: Can be integrated into the software development pipeline, allowing for
  continuous testing during development phases.

### Types of Automated Testing

1. **Unit Testing**: Tests individual units or components of the software in isolation.
2. **Integration Testing**: Tests the integration or interfaces between components, or
   between different systems.
3. **Functional Testing**: Tests the software against the functional
   requirements/specifications.
4. **Regression Testing**: Ensures that new code changes do not adversely affect existing
   functionalities.
5. **Performance Testing**: Tests the software’s performance under certain conditions.
6. **Load Testing**: Checks how the system behaves under a heavy load of users or data
   processing.

### Tools for Automated Testing

- **Selenium**: A portable framework for testing web applications.
- **JUnit/NUnit/pytest**: Tools for unit testing in Java, .NET, and Python respectively.
- **Cucumber**: Supports Behavior-Driven Development (BDD), allowing specification of
  application behavior in plain language.
- **Apache JMeter**: Designed for load testing and can be used to test performance both on
  static and dynamic resources.
- **TestComplete**: A functional automated testing platform developed by SmartBear
  Software.

... output truncated ...

</blockquote>
</details>

```markdown
What are some of the benefits and challenges of automated testing?
```

<details>
<summary><strong>View Response</strong></summary>
<blockquote>

Automated testing offers numerous benefits to the software development process, but it
also comes with its own set of challenges. Understanding these can help teams make
informed decisions about implementing automated testing strategies.

### Benefits of Automated Testing

1. **Increased Efficiency**: Automation can execute tests much faster than humans,
   allowing for more tests to be run in less time.
2. **Reusability of Test Scripts**: Once created, test scripts can be reused across
   different versions of the software, saving time and effort in the long run.
3. **Improved Accuracy**: Automated tests eliminate the risk of human error, ensuring that
   tests are performed exactly the same way every time.
4. **Enhanced Coverage**: Automation makes it feasible to run a large number of tests,
   including complex scenarios, which might be impractical to perform manually.
5. **Cost Reduction**: Although there's an initial investment, automated testing can
   reduce the cost of testing over time, especially for long-term projects.
6. **Continuous Integration and Delivery**: Automated tests can be integrated into the
   CI/CD pipeline, enabling continuous testing and faster feedback loops.
7. **Better Use of Resources**: Automating repetitive tasks frees up QA engineers to focus
   on more complex testing and other high-value work.

### Challenges of Automated Testing

1. **Initial Setup Cost and Time**: Setting up an automated testing environment requires a
   significant investment in tools, training, and script development.
2. **Maintenance of Test Scripts**: As the application evolves, test scripts need to be
   regularly updated, which can be time-consuming.
3. **Learning Curve**: Teams may need to learn new tools and scripting languages, which
   can delay the initial implementation of automated testing.
4. **Tool Selection**: Choosing the right tools that fit the project's needs can be
   challenging, especially given the wide variety of tools available.
5. **False Positives and Negatives**: Automated tests can sometimes produce false
   positives (reporting a failure when the feature works) or false negatives (failing to
   detect an actual issue), which require manual investigation.
6. **Limited to Test Coverage**: Automated tests can only check conditions that they are
   programmed to test. They might miss issues that would be obvious to a human tester.
7. **Complexity in Testing User Interfaces**: Automated UI testing can be particularly
   challenging due to dynamic content, responsiveness, and cross-browser compatibility
   issues.

Despite these challenges, the benefits of automated testing often outweigh the drawbacks,
especially for large projects and in organizations that adopt agile methodologies. Careful
planning, tool selection, and ongoing maintenance can mitigate many of the challenges
associated with automated testing.

</blockquote>
</details>

```markdown
How can I get started with unit testing?
```

<details>
<summary><strong>View Response</strong></summary>
<blockquote>

Getting started with unit testing involves several key steps, from understanding the
basics to integrating unit tests into your development workflow. Here's a step-by-step
guide to help you begin:

### 1. Understand the Basics of Unit Testing

- **Learn what unit testing is**: Understand that unit testing involves testing individual
  components or functions of your software in isolation to ensure they work as expected.
- **Know the benefits**: Recognize how unit testing can improve code quality, facilitate
  refactoring, and catch bugs early in the development cycle.

### 2. Choose a Unit Testing Framework

- **Research frameworks**: Look into unit testing frameworks that are compatible with the
  programming language you are using. Some popular ones include JUnit (Java), NUnit
  (.NET), pytest (Python), and Jest (JavaScript).
- **Consider your project's needs**: Choose a framework that fits your project's
  requirements, considering factors like documentation, community support, and integration
  capabilities.

### 3. Set Up Your Testing Environment

- **Install the testing framework**: Follow the documentation of the chosen framework to
  set it up in your development environment.
- **Configure your IDE**: Most Integrated Development Environments (IDEs) support unit
  testing. Configure your IDE to run and debug tests easily.

### 4. Write Your First Test

- **Identify a simple function to test**: Start with a straightforward function or
  component that has a clear expected outcome.
- **Write the test case**: Create a test case that calls the function with specific inputs
  and asserts the expected output. Follow the Arrange-Act-Assert (AAA) pattern for
  structuring your test.
- **Run the test**: Use your testing framework's tools to run the test and see the
  results. Initially, the test might fail, which is part of the process.

... output truncated ...

</blockquote>
</details>

> Copilot remembers the context of the conversation and can provide additional information
> based on the previous prompts. Feel free to ask follow-up questions to explore the topic
> further.

```markdown
What is test coverage?
```

<details>
<summary><strong>View Response</strong></summary>
<blockquote>

Test coverage is a metric used to measure the extent to which a software's source code is
executed when a particular test suite runs. It provides an indication of how much of the
codebase is tested, which can help in identifying parts of the application that have not
been tested and may contain undetected bugs. Test coverage is often expressed as a
percentage, representing the ratio of the number of lines of code executed by tests to the
total number of lines of code in the software.

Here's a breakdown of the concept:

1. **Line Coverage**: Measures the percentage of lines of code that are executed during
   testing. If a program has 100 lines of code and tests execute 80 of these, the line
   coverage is 80%.

2. **Function Coverage**: Measures the percentage of functions or methods that are called
   during testing. If a program contains 50 functions and tests call 40 of them, the
   function coverage is 80%.

3. **Branch Coverage**: Measures the percentage of branches of control structures (like
   if-else statements) that are executed. For example, if there are 20 if-else conditions
   and tests execute both branches of 15 of them, the branch coverage is 75%.

4. **Statement Coverage**: Similar to line coverage, but focuses on the execution of
   individual statements within the code.

5. **Condition Coverage**: Measures how many of the boolean sub-expressions of each
   control structure (like each condition within an if statement) have been evaluated to
   both true and false.

6. **Path Coverage**: Measures the percentage of unique paths through the code that have
   been executed. This is more comprehensive than branch coverage, as it considers every
   possible route through a given part of the code, including loops and recursive calls.

Test coverage is a useful tool for improving software quality, but it's important to note
that high test coverage does not guarantee the absence of bugs. It is possible to have
100% test coverage and still have undetected issues, especially if the tests do not
adequately assert the correctness of the code's behavior. Therefore, while striving for
high test coverage is beneficial, it should be complemented with other quality assurance
practices like code reviews, integration testing, and manual testing to ensure a robust
software product.

</blockquote>
</details>

```markdown
When should I use unit tests vs automated tests?
```

<details>
<summary><strong>View Response</strong></summary>
<blockquote>

The terms "unit tests" and "automated tests" often cause confusion, primarily because unit
tests are a subset of automated tests. Understanding when to use each involves recognizing
the different types of automated tests and their purposes in the software development
lifecycle. Here's a breakdown to clarify:

### Automated Tests

Automated tests refer to any testing process where software tools execute pre-scripted
tests on a software application before it is released into production. Automated testing
includes several levels, such as:

- **Unit Tests**: Focus on individual components or functions of the software, testing
  them in isolation to ensure they work as expected.
- **Integration Tests**: Verify that different modules or services used by your
  application interact correctly.
- **Functional Tests**: Assess the system's functionality against the requirements, often
  involving the entire application and focusing on user scenarios.
- **End-to-End Tests (E2E)**: Simulate real user scenarios from start to finish, ensuring
  the system behaves as intended in a production-like environment.
- **Performance Tests**: Evaluate the system's behavior under a particular load, measuring
  response times, throughput rates, and resource utilization levels.

### When to Use Unit Tests

- **Early in Development**: Unit tests are best used early and often in the development
  process. They help developers ensure that individual components work correctly before
  integrating them into the larger system.
- **For Isolated Testing**: When you need to test a specific function or component in
  isolation, without dependencies on external systems or modules.
- **For Regression Testing**: Unit tests are excellent for quickly checking that changes
  in the code have not broken existing functionality.
- **Continuous Integration/Continuous Deployment (CI/CD)**: Unit tests are typically fast
  to run, making them ideal for CI/CD pipelines where quick feedback is essential.

### When to Use Other Automated Tests

- **Integration Tests**: When you need to test how different parts of the application work
  together. This is crucial after unit testing, to ensure that modules interact correctly.
- **Functional and E2E Tests**: After the application is functionally complete or for
  specific milestones, to verify that the entire application behaves as expected from the
  user's perspective.
- **Performance Tests**: Before release, especially for applications expected to handle
  high loads or have specific performance requirements. Also useful periodically to detect
  performance regressions.
- **When Testing Real User Flows**: Automated tests that simulate real user scenarios
  (like E2E tests) are crucial for verifying that the application meets its requirements
  in a production-like environment.

### Conclusion

- Use **unit tests** for low-level testing of individual components, throughout the
  development process, to ensure reliability and facilitate refactoring.
- Use **other automated tests** (integration, functional, E2E, performance) at various
  stages of development to validate interactions between components, adherence to
  functional requirements, and performance under load.

Balancing different types of automated testing based on the project phase and specific
requirements is key to a comprehensive testing strategy that ensures high-quality
software.

</blockquote>
</details>

As we can see, Copilot understands different kinds of testing and can provide information
on how to get started with testing in different languages.

In the next module, we will explore creating unit tests and measuring our test coverage.

## Module 2: Creating unit tests

1. Create unit tests for GameData.cs
2. Create unit tests for Routes.cs 
3. Create unit tests for Leaderboard.cs
4. Create unit tests for Game.cs
5. Generate unit tests for saving leaderboard with mock testing 
6. Measure test coverage with Coverlet
7. Generate a report with ReportGenerator
8. Explore the report and identify areas for improvement
9. Write integration tests for the project
