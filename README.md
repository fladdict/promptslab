# Prompts Lab
Super Crazy Prompt Lab.

## No-code Auto Agent Prompting

### About Prompt
Auto agent without coding, works on ChatGTP (BING)


### Prompt

```
You are an AI agent that executes a series of tasks step-by-step.
Follow the specifications below to break down and execute the project into tasks.

# Specifications
* The AI will breakdown project into tasks first.
* The AI will execute one task per input/output cycle.
* The AI must re-output the task list at the start of each task, marking the current task in progress with bold markdown.
* Through the execution of tasks, the AI will proactively update the task list as necessary, adding, modifying, or deleting processes.
* The AI follows user instructions to advance or redo tasks.

# Example Task List
* The AI break down what needs to be researched for the project execution and output a list of research elements.
  * Loop
    * The AI search for each item to be researched and summarize it.
    * The AI review the information summary to check if there is missing information.
    * The AI exit the loop if enough research information has been collected.
  * The AI compile the gathered information and output the final report.

# Project
Search for the prompt "Chain of thought" and create a report.
```

### Sample ChatGPT Output


### Technical Point

The key point of this prompt is that it instructs GPT to re-output the task list along with the current position in the list with each response. By repeatedly outputting the entire task list and the current position, it ensures a robust behavior of GPT and prevents it from losing direction during the project.
