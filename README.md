# agent-factory
Collection of agents creation tools, each of which allows for the creation of distinct types of AI agents.

<div align="center">
  <!-- <a href="https://www.youtube.com/"> -->
    <!-- <img alt="AI Agents Masterclass" src="https://i.imgur.com/8Gr2pBA.png"> -->
    <h1 align="center">AI Agent Factory</h1>
  <!-- </a> -->
</div>

<p align="center">
Currently, the most crucial area for developers to invest their efforts is in Artificial Intelligence. 
However, there's a significant gap - the majority of developers aren't exploring AI agents, which holds 
the key to maximizing AI's potential. That's precisely why I've established this AI Agents Factory. 

My goal is to demonstrate how you can harness AI agents to revolutionize business operations and 
develop robust applications, drawing from my extensive experience in successful implementations.

</p>

<p align="center" style="margin-top: 25px">
  <a href="#what-are-ai-agents"><strong>What are AI Agents?</strong></a> ·
  <a href="#how-this-repo-works"><strong>How this Repo Works</strong></a> ·
  <a href="#instructions-to-follow-along"><strong>Instructions to Follow Along</strong></a>
</p>
<br/>

## What are AI Agents?

At their core, AI agents are Large Language Models (LLMs) enhanced with the capability to engage with external systems.

Their applications are vast - from composing emails and managing CRM appointments to handling task management systems. 
The possibilities are truly limitless, and I'm excited to help you explore the full scope of what's possible!

What makes AI agents particularly remarkable is their ability to deliver powerful results with minimal coding requirements. 
Yet, this simplicity doesn't limit their potential - there's enormous opportunity to develop sophisticated systems 
that orchestrate multiple agents working in harmony to achieve extraordinary outcomes. This is the exciting journey 
we'll embark on throughout this masterclass, and I'm thrilled to guide you through it!


<!-- Below is a very basic diagram just to get an idea of what an AI agent looks like:

<div align="center" style="margin-top: 25px;margin-bottom:25px">
<img width="700" alt="Trainers Ally LangGraph graph" src="https://i.imgur.com/ChRoV8W.png">
</div> -->

<br/>

## Repo Usage Instructions

<!-- Any folder that starts with a number is for a masterclass video. The other folders are for other content
on my YouTube channel. The other content goes very well with the masterclass series (think of it as
supplemental material) which is why it is here too! -->

<!-- The code in each folder will be exactly what is used/created in the accompanying masterclass video. -->

<!-- <br/> -->

Start with [/1-first-agent/](/1-first-agent) for the first scenario in the masterclass where we create our very first AI agent.

The below instructions assume you already have Git, Python, and Pip installed. If you do not, you can install
[Python + Pip from here](https://www.python.org/downloads/) and [Git from here](https://git-scm.com/).

First clone this GitHub repository, open up a terminal,
and change your directory to the folder for the current scenario you are watching (example: start with [/1-first-agent/](/1-first-agent)).

The below instructions work on any OS - Windows, Linux, or Mac.

You will need to use the environment variables defined in the .env.example file in the folder (example for the first one: [`1-first-agent/.env.example`](/1-first-agent/.env.example)) to set up your API keys and other configuration. Turn the .env.example file into a `.env` file, and supply the necessary environment variables.

After setting up the .env file, run the below commands to create a Python virtual environment and install the necessary Python packages to run the code. 

Creating a virtual environment is optional but recommended. Make sure to run the pip install for each use case.

```bash
python -m venv agent-factory

# On Windows:
.\agent-factory\Scripts\activate

# On MacOS/Linux: 
source agent-factory/bin/activate

cd 1-first-agent (or whichever folder)
pip install -r requirements.txt
```

Then, you can execute the code in the folder with:

```bash
python [script name].py
```
