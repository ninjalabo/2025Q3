# Simple OpenAI Function Calling (Nbdev Workflow)

## Overview

This accesses your preference on using [Python](https://www.python.org/), the [OpenAI API](https://platform.openai.com/docs/api-reference), and the [nbdev](https://nbdev.fast.ai/) workflow. Complete the task entirely in Jupyter notebooks using the nbdev workflow and host your project on a given [GitHub](https://github.com/) repository. Keep your development efficiently concise. Here's our internal Nbdev [Tutorial](https://youtu.be/y-V3XDPyUws?si=KHaiofRfeiYqseAD).

I believe your technical preferences matter significantly, and I don't wish to waste your time with something you may not enjoy. Please proceed only if you're comfortable and interested in the nbdev workflow, as it has a unique approach to notebook-based Python development.

## Instructions

### 0. Clone privately
* Please git clone this repo *privately* and share with GH account, `doyu`.

### 1. GitHub Issues

* Concisely outline each step of your development process as individual [GitHub issues](https://docs.github.com/en/issues).
* Resolve each issue explicitly, linking the solution directly to the relevant git commit.
* Ensure your solutions pass [GitHub Actions](https://docs.github.com/en/actions) successfully.
* Use GitHub issue comments for further communication (E.g. questions, clarifications).

### 2. Development Environment

* Set up an [nbdev environment](https://nbdev.fast.ai/getting_started.html) to manage your notebook-based Python code effectively.

### 3. Implementation

* Define and implement at least one simple Python function (examples: basic arithmetic operations, mock data retrieval).
* Integrate this function with OpenAI's [Function Calling](https://platform.openai.com/docs/api-reference/chat/create#chat-create-function_call) (FC) API:

  * Formulate a clear prompt instructing the OpenAI API to invoke your function.
  * Properly handle the API response, execute the function, and document the interaction clearly within your notebook.

### 4. Testing

* Include relevant tests within your notebook to confirm that your function behaves as expected.

### 5. Documentation

* Thoroughly document your development workflow within the notebook, adhering to [nbdev best practices](https://nbdev.fast.ai/tutorials/tutorial.html). Include clear explanations of your code, tests, and results.

## Bonus (Optional)

* Briefly explore and implement an additional, related feature or extension to demonstrate creativity and further exploration interest.

Good luck!
