<img width="150" alt="image" src="https://github.com/user-attachments/assets/1948e02a-885e-4659-8f97-50b64b006539">

## About 

Explyt Test is your teammate who generates clear and useful tests. Based on the latest AI research with post-processing of world-leading static and dynamic code analysis techniques.

## What makes Explyt Test unique?

Explyt Test is not yet another wrapper for prompts to popular LLM providers. The tool consists of several stages, each refining the results of the previous one.

First, the project environment and file context are collected, filtered, prioritized, and passed to the LLM model. This intelligent model finds the right prompt for the specific circumstance, such as Unit Test generation with JUnit 5 or Spring MockMVC tests.

Second, the template is generated with a fine-tuned AI model.

Next, the template is filled with mixed static and dynamic code analysis in the feedback loop. Static code analysis (and specifically symbolic execution) allows you to run code and find problems without actual code execution, while dynamic code analysis relies on running instrumented code.

Our benchmarking system constantly improves the quality of generated tests.

## Installation and usage

### Installation 

Explyt Test plugin will be distributed via JetBrains Marketplace and as a part of <a href="https://plugins.jetbrains.com/plugin/23273-spring-explyt">Spring Explyt</a> plugin. 

For now, request a file `explyt-test.zip` to install it. Process the installation using the <a href="https://www.jetbrains.com/help/idea/managing-plugins.html#install_plugin_from_disk">manual</a> after that.

### How to start

Open the general plugin Settings page. Here you need to specify LLM provider and model you are going to use and enter the API key. 

We recommend using `DeepSeek-Coder-V2` or `GPT-4o mini` models. Sending requests to other models may be much **more expensive**. However, they provide better test quality sometimes.

<img width="949" alt="image" src="https://github.com/user-attachments/assets/c28ce9e9-4592-40bb-a6af-e632a14c4a84">

### Usage

See <a href="https://github.com/explyt/explyt-test-issues/blob/main/USAGE_GUIDE.md">Usage Guide</a> for details.


## Share your feedback

Please reach out for bugs, feature requests, and other issues via:

* filing an issue <a href="https://github.com/explyt/explyt-test-issues/issues/new/choose">here</a>
* Telegram <a href="https://t.me/explyttest">group</a> for early adopters
* email info@explyt.com
