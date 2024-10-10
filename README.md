<img width="150" alt="image" src="https://github.com/user-attachments/assets/1948e02a-885e-4659-8f97-50b64b006539">

## About 

Explyt Test is your teammate who generates clear tests. Based on the latest AI research with post-processing of world-leading static and dynamic code analysis techniques.

## What makes Explyt Test unique?

Explyt Test is not yet another wrapper for prompts to popular LLM providers. The tool consists of several stages, each refining the results of the previous one.

First, the project environment and file context are collected, filtered, prioritized, and passed to the LLM model. This intelligent model finds the right prompt for the specific circumstance, such as Unit Test generation with JUnit 5 or Spring MockMVC tests.

Second, the template is generated with a fine-tuned AI model.

Next, the template is filled with mixed static and dynamic code analysis in the feedback loop. Static code analysis (and specifically symbolic execution) allows you to run code and find problems without actual code execution, while dynamic code analysis relies on running instrumented code.

Our benchmarking system constantly improves the quality of generated tests.

## Installation and usage

### Installation 

We have the first EAP release of Explyt Test. In can be requested on https://explyt.com/eap/ 

You can also get the free API key with some credits there.

### How to start

Open the general plugin Settings page. Here you need to specify LLM provider and model you are going to use and enter the API key. 

![image_2024-09-11_17-25-03](https://github.com/user-attachments/assets/fb730a47-5df4-4f59-8205-79bac34b472f)

### Usage

See <a href="https://github.com/explyt/explyt-test-issues/blob/main/User%20Guide.md">User Guide</a> for details.


## Share your feedback

Please reach out for bugs, feature requests, and other issues via:

* filing an issue <a href="https://github.com/explyt/explyt-test-issues/issues/new/choose">here</a>
* Telegram <a href="https://t.me/explyttest">group</a> for early adopters
* email info@explyt.com
