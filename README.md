<p align="center">
<img width="150" alt="image" src="https://github.com/user-attachments/assets/921fe44d-7d78-427c-9a16-5e8dffa720e7">
</p>

## About 

Explyt with an AI agent for coding, testing, and debugging, understands the project structure and follows its style, integrates tests into the existing code base. Supports Java and Kotlin projects, including Spring-based applications.

Explyt improves code quality and makes test writing less time-consuming and more comfortable for developers. 

## Key features
- AI agent for coding, testing, and debugging
- MCP servers support
- Unit and integration tests generation for Java and Kotlin projects (with Spring)
- Increase test coverage
- Test generation from execution
- Test generation based on specification
- Flaky tests analysis
- Rules and Workflows

## Explyt helps you
- increase line coverage
- repair existing tests
- detect flaky tests
- generate inline code
- explain errors in console
- explain code fragments

## How does Explyt generate tests?

Explyt is not yet another wrapper for prompts to popular LLM providers. The tool consists of several stages, each refining the results of the previous one.

- The project environment and file context are collected, filtered, prioritized, and passed to the LLM model. This intelligent model finds the right prompt for the specific circumstance, such as Unit Test generation with JUnit 5 or Spring MockMVC tests.

- The template is generated with a fine-tuned AI model.

- The template is filled with mixed static and dynamic code analysis in the feedback loop. Static code analysis (and specifically symbolic execution) allows you to run code and find problems without actual code execution, while dynamic code analysis relies on running instrumented code.

Our benchmarking system constantly improves the quality of generated tests.

## Installation and usage

### Installation 

Explyt 4.2 with Go support is the latest version of the plugin.
You can download it from the page: https://explyt.ai/download

The [What's new in Explyt 4.2](https://explyt.ai/docs/explyt-test/features42) article contains a list of the new features with live demos.

### How to start

- Install the plugin
- Accept the terms of <a href="https://explyt.ai/docs/legal/policy/">User Agreement</a>
- Start using Explyt for free
- You can access language models either through Explyt servers (Personal plan) or by using your API keys (Community plan).

<img width="717" alt="image" src="https://github.com/user-attachments/assets/353b7b5d-7c26-484a-8938-ae6bae7784fb" />

![image_2025-03-27_19-36-46](https://github.com/user-attachments/assets/39e3f2a4-1980-4b10-b8de-64167543eb2a)

### Tips and tricks

In [this section](https://explyt.ai/docs/category/help), we share best practices and detailed tutorials to make your work with Explyt a great experience.

## Share your feedback

Please reach out for bugs, feature requests, and other issues via:

* submiting an issue <a href="https://github.com/explyt/explyt-test-issues/issues/new/choose">here</a>
* email support@explyt.com
