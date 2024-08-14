# AutoGen AI Blog Post Writer

## Overview

This script uses the AutoGen library to generate a concise and engaging blog post about Artificial Intelligence. It utilizes multiple AI agents to write, review, and refine the content.

## Requirements

* AutoGen library
* Python 3.x
* OpenAI API key (optional)

## Usage

1. Install the required libraries: `pip install autogen`
2. Run the script: `python main.py # here you will provide arguments bydefault it uses ollama, with llama3`

## Command Line Arguments

* `--model`: Specify the AI model to use (default: `llama3`)
* `--api_key`: Specify the OpenAI API key (default: `ollama`)
* `--base_url`: Specify the base URL for the AI model (default: `http://localhost:11434/v1`)

## How it Works

1. The script defines a task to write a blog post about Artificial Intelligence.
2. The `Writer` agent generates an initial draft of the blog post.
3. The `Critic` agent reviews the draft and provides feedback.
4. Four nested agents (`SEO Reviewer`, `Legal Reviewer`, `Ethics Reviewer`, and `Meta Reviewer`) review the draft and provide suggestions.
5. The `Critic` agent aggregates the feedback and refines the blog post.
6. The final blog post is printed to the console.

## Output

The script generates a concise and engaging blog post about Artificial Intelligence.

