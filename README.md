<h1 align="center">
	💠 Awesome Devins
	<p align="center">
		<a href="https://discord.gg/U7KEcGErtQ" target="_blank">
			<img src="https://img.shields.io/static/v1?label=Join&message=%20discord!&color=mediumslateblue">
		</a>
		<a href="https://twitter.com/e2b" target="_blank">
			<img src="https://img.shields.io/twitter/follow/e2b.svg?logo=twitter">
		</a>
	</p>
</h1>
<h3 align="center">
  Try out E2B's <a href="https://e2b.dev/docs?ref=awesome-sdks">cloud runtime</a> for AI agents
</h3>


<h5 align="center">👉 <a href="https://forms.gle/UXQFCogLYrPFvfoUA">Submit new product here</a></h5>

<img src="assets/landscape-latest.png" width="100%" alt="Chart of AI Agents Landscape" />

Welcome to our list of AI agents that are inspired by release of Devin. See the 🌟 [complete list of AI agents on GitHub](https://e2b.dev/ai-agents) or in [web UI](https://e2b.dev/ai-agents).

The list is done according to our best knowledge, although definitely not comprehensive. Check out also <a href="https://github.com/e2b-dev/awesome-sdks-for-ai-agents">the Awesome List of SDKs for AI Agents</a>.
Discussion and feedback appreciated! :heart:

Have anything to add? Create a pull request or fill in this [form](https://forms.gle/UXQFCogLYrPFvfoUA). Please keep the alphabetical order and in the correct category.

<!---
## Who's behind this?
This list is made by the team behind [e2b](https://github.com/e2b-dev/e2b). E2b is building AWS for AI agents. We help developers to deploy, test, and monitor AI agents. E2b is agnostic to your tech stack and aims to work with any tooling for building AI agents.
--->

## Want to use E2B with your AI product?
Contact us at [hello@e2b.dev](mailto:hello@e2b.dev) or [on Discord](https://discord.gg/35NF4Y8WSE). Follow us on [X (Twitter)](https://twitter.com/e2b_dev)

We are open-source and you can get started with E2B [here](https://e2b.dev/docs?ref=awesome-sdks).


<!---
## Join the community
- Follow us on [Twitter](https://twitter.com/e2b)
- [Join Twitter community](https://twitter.com/i/communities/1670204079619055616) for AI agents
- [Join our Discord](https://discord.gg/U7KEcGErtQ)

Feel free to reach out to us at [hello@e2b.](mailto:hello@e2b.).
--->


# Open-source "Devins"

## [Anterion](https://github.com/MiscellaneousStuff/anterion)
Open-source software engineer

<details>

![Image](https://avatars.githubusercontent.com/u/14856541?s=64&v=4)
### Category
Coding, general purpose

### Description
- Anterion Agent extends the capabilities of SWE-agent to plan and execute open-ended engineering tasks.
- Frontend is inspired by OpenDevin


### Links
- [GitHub](https://github.com/MiscellaneousStuff/anterion)
- [Discord](https://discord.com/invite/nbY6njCuxh)
- [YouTube demo](https://www.youtube.com/watch?v=J-KZNFVcAxU&ab_channel=Anterion)
- [YouTube review](https://www.youtube.com/watch?v=wgtZbw1yEtE&ab_channel=Prepdrive)


</details>

## [AutoCodeRover](https://github.com/nus-apr/auto-code-rover)
Autonomous Program Improvement

<details>

![Image](https://private-user-images.githubusercontent.com/48704330/322199117-e10c3270-442c-4673-8656-735c892dfb66.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMyMjY3NjcsIm5iZiI6MTcxMzIyNjQ2NywicGF0aCI6Ii80ODcwNDMzMC8zMjIxOTkxMTctZTEwYzMyNzAtNDQyYy00NjczLTg2NTYtNzM1Yzg5MmRmYjY2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE2VDAwMTQyN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTM5NzY5NGUyYWUyMTZjYjk0MzZlMGY0NmIwMjBhZTA1NDAyYzE4NjFhZDExMDhjYzQ4Mjc3ZTc4OTE4NDYwZWEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.Y7mGAqtPaVKWShBVUOzSALad08wyJ5ZFj28_Q_HeVlY)
### Category
Coding, general purpose

### Description
- This agent is based on a paper "AutoCodeRover: Autonomous Program Improvement".
- It combines LLMs with analysis and debugging capabilities to prioritize patch locations ultimately leading to a patch.
- Resolves ~16% of issues of SWE-bench (total 2294 GitHub issues) and ~22% issues of SWE-bench lite (total 300 GitHub issues).
- AutoCodeRover works in two stages:
  - Context retrieval: The LLM is provided with code search APIs to navigate the codebase and collect relevant context.
  - Patch generation: The LLM tries to write a patch, based on retrieved context.
- AutoCodeRover has two unique features:
  - Code search APIs are Program Structure Aware. Instead of searching over files by plain string matching, AutoCodeRover searches for relevant code context (methods/classes) in the abstract syntax tree.
  - When a test suite is available, AutoCodeRover can take advantage of test cases to achieve an even higher repair rate, by performing statistical fault localization.

### Links
- [GitHub](https://github.com/nus-apr/auto-code-rover)
- [Paper](https://arxiv.org/abs/2404.05427)

</details>

## [AutoDev](https://github.com/unit-mesh/auto-dev)
Open-source Devin alternative

<details>

![Image](https://github.com/unit-mesh/auto-dev/raw/master/plugin/src/main/resources/META-INF/pluginIcon.svg)

### Category
Coding, general purpose

### Description
- AutoDev has multilingual support
- Languages support: Java, Kotlin, JavaScript/TypeScript, Rust, Python, Golang, C/C++/OC, or others…



### Links
- [GitHub](https://github.com/unit-mesh/auto-dev)
- [Documentation](https://ide.unitmesh.cc/)

</details>

## [Codel](https://github.com/semanser/codel?tab=readme-ov-file)
Fully autonomous AI agent

<details>

![Image](https://github.com/semanser/codel/raw/main/.github/demo.png)
### Category
Coding, general purpose

### Description
- Fully autonomous AI Agent that can perform complicated tasks and projects using terminal, browser, and editor
- Everything is running in a sandboxed Docker environment.
- It can fetch latest information from the web (tutorials, docs, etc.) if needed.
- Has a built-in text editor for previewing all files
- All the history commands and outputs are saved in the PostgreSQL database.
- The simplest way to start Codel is to use a pre-built Docker image


### Links
- [GitHub](https://github.com/semanser/codel?tab=readme-ov-file)
- [Discord](https://discord.com/invite/uMaGSHNjzc)

</details>

## [Devika](https://github.com/stitionai/devika)
Agentic AI Software Engineer

<details>

![Image](https://github.com/stitionai/devika/raw/main/.assets/devika-screenshot.png)
### Category
Coding, general purpose

### Description
- Devika supports Claude 3, GPT-4, GPT-3.5, and Local LLMs via Ollama
- GitHub stars: 14.4k
- Devika is an Agentic AI Software Engineer that can understand high-level human instructions, break them down into steps, research relevant information, and write code to achieve the given objective.
- Devika aims to be a competitive open-source alternative to Devin by Cognition AI.
- Its architecture has a Code Writing Module that generates code based on the plan, research findings, and user requirements. Supports multiple programming languages. It also has a Browser Interaction Module that enables Devika to navigate websites, extract information, and interact with web elements as needed.
- To enable focused research and information gathering, Devika employs keyword extraction techniques.


### Links
- [GitHub](https://github.com/stitionai/devika)

</details>

## [Devon](https://github.com/entropy-research/Devon)
Open-source Devin alternative

<details>

![Image](https://avatars.githubusercontent.com/u/163390653?s=200&v=4)
### Category
Coding, general purpose

### Description
- Open-source alternative to Devin by Entropy research
- GitHub stars: 150
- Devon is an open-source SWE Agent that aims to help software engineers with the development and maintenance of software.
- It doesn’t provide an extensive description, but as features it mentions reliable multi file editing or use of tools such as git
- Devon is built with Python


### Links
- [GitHub](https://github.com/entropy-research/Devon)

</details>

## [MetaGPT](https://github.com/geekan/MetaGPT)
Agent framework returning Design, Tasks, or Repo

<details>

 ![image](https://github.com/geekan/MetaGPT/raw/main/docs/resources/MetaGPT-new-log.png)

### Category
Multi-agent, Coding, Build your own

### Description
MetaGPT is a multi-agent framework
MetaGPT has existed longer than other Devin alternatives, but after the release of Devin, the MetaGPT team aims to replace most of the Devin capabilities.
MetaGPT allows the assignment of different roles to GPTs to form a collaborative software entity for complex tasks.
You can use this multi-agent framework in your own scenario to build your own application.
Internally, MetaGPT includes agents with roles of product managers, architects, project managers, and engineers.
It provides the entire process of a software company along with carefully orchestrated SOPs. Code = SOP(Team) is the core philosophy.


### Links
- [GitHub](https://github.com/geekan/MetaGPT)
- [Discord](https://discord.com/invite/4WdszVjv)
- [Twitter](https://twitter.com/DeepWisdom2019)
- [Paper - MetaGPT: Meta Programming for Multi-Agent Collaborative Framework](https://arxiv.org/abs/2308.00352)

</details>

## [⭐ OpenDevin](https://github.com/OpenDevin/OpenDevin)
OpenDevin: Code Less, Make More

<details>

![Image](https://github.com/OpenDevin/OpenDevin/raw/main/logo.png)
### Category
Coding, general purpose

### Description
-  The OpenDevin project aims to replicate the original Devin model.
-  By engaging the open-source community, we aim to tackle the challenges faced by Code LLMs in practical scenarios, producing works that significantly contribute to the community and pave the way for future advancements.
- OpenDevin does code execution via Docker, but there is a work in progress with adding an option to execute code in the sandboxed environment
- It has over 20.7k stars
The key technologies used in the project include FastAPI, uvicorn, LiteLLM, Docker, Ruff, MyPy, LlamaIndex, and React.


### Links
- [GitHub](https://github.com/OpenDevin/OpenDevin)
- [Demo video](https://www.youtube.com/watch?v=g6-DpvBlTWY&ab_channel=GitWit)
- [Discord](https://discord.com/invite/mBuDGRzzES)
- [Slack](https://opendevin.slack.com/join/shared_invite/zt-2etftj1dd-X1fDL2PYIVpsmJZkqEYANw#/shared-invite/email)

</details>

## [Plandex](https://github.com/plandex-ai/plandex)
Terminal-based AI coding engine for complex tasks

<details>

![Image](https://github.com/plandex-ai/plandex/raw/main/images/plandex-logo-dark.png)

### Category
Coding, general purpose

### Description
- Plandex uses long-running agents to complete tasks that span multiple files and require many steps.
- It breaks up large tasks into smaller subtasks, then implements each one, continuing until it finishes the job.
- It helps you churn through your backlog, work with unfamiliar technologies, get unstuck, and spend less time on the boring stuff.


### Links
- [GitHub](https://github.com/plandex-ai/plandex)

</details>

## [SWE Agent](https://github.com/princeton-nlp/SWE-agent)
Open-source Devin alternative

<details>

![Image](https://github.com/princeton-nlp/SWE-agent/raw/main/assets/swe-agent-banner.png)

### Category
Coding, general purpose

### Description
- This Devin alternative scores 12.3% on the FULL swe benchmark
- SWE-agent works by interacting with a specialized terminal, which allows it to:
	- 🔍 Open, scroll and search through files
	- ✍️ Edit specific lines w/ automatic syntax check
	- 🧪 Write and execute tests
- This custom-built interface is critical for good performance. Simply connecting an LM to a vanilla bash terminal does not work well.
- ["Our key insight is that LMs require carefully designed agent-computer interfaces (similar to how humans like  good UI design). E.g. When the LM messes up indentation, our editor prevents it and gives feedback."](https://x.com/jyangballin/status/1775114448513958134)
- SWE-agent was released by the Princeton NLP team.
- What makes SWE-agent special is that it performs almost as well as Devin on the SWE-bench.
- It is important to say that the performance [varies](https://www.swebench.com/) based on the model used by the agent.
- The changes and innovations in SWE-agent compared to Devin are:
  - The code in SWE Agent is executed locally via Docker.
  - It uses “Agent-Computer Interface” (ACI) - constraining the interface makes the agent easier to use for LMs. Only a few commants are allowed: run code, look for code, edit code and submit changes to GitHub.
- Any code the agent writes goes through a syntax check (linter) before being submitted. If the syntax is incorrect, the agent gets feedback and is forced to redo the code.
- The agent can only read 100 lines of code at a time, rather than the entire file. This makes it easier for the language model to understand the code.


### Links
- [GitHub](https://github.com/princeton-nlp/SWE-agent)
- [Web](https://swe-agent.com/)
- [Demo](https://swe-agent.com/demo)
- [Discord](https://discord.com/invite/AVEFbBn2rH)


</details>

<br>


# Closed-source "Devins"

## [Devin](https://www.cognition-labs.com/introducing-devin)
The first AI software engineer

<details>

![image](https://assets-global.website-files.com/65cf071d26e52092bc212f6e/65ed4622397bb038560f1ef3_cropped-p-500.png)

### Category
General purpose, Coding


### Description
Devin is in early phase now, but according to demo, it has the following capabilities:
- Can learn how to use unfamiliar technologies.
- Can build and deploy apps end to end.
- Can autonomously find and fix bugs in codebases.


### Links
- [Blog post](https://www.cognition-labs.com/introducing-devin)
- [X (Twitter)](https://twitter.com/cognition_labs)

</details>

## [Fume](https://www.fumedev.com/)
AI Software Engineer to 10x efficiency

<details>

![image](https://www.fumedev.com/images/fume_white.svg)

### Category
General purpose, Coding

### Description
Fume is an expert on everything your engineers need. It can help your engineers to solve any problem, or take the driver seat and automate solutions end-to-end.
- Slack integration
- Automated Code Changes
- Step-by-Step Guidance
- Private & Secure
- SotA and Public

### Links
- [Docs](https://docs.fumedev.com/introduction)
- [Founder's X (Twitter)](https://twitter.com/aegucer)
</details>


## Want to use E2B with your AI product?
Contact us at [hello@e2b.dev](mailto:hello@e2b.dev) or [on discord](https://discord.gg/35NF4Y8WSE).

We are open-source and you can get started with E2B [here](https://e2b.dev/docs?ref=awesome-sdks).

<img src="/assets/footer.png" width="100%" alt="SDKs Repo Visual" />


## Join the community
- Follow us on [X ](https://twitter.com/e2b)
- [Hit us up on discord](https://discord.gg/35NF4Y8WSE)
- Feel free to reach out to us at [hello@e2b.dev](mailto:hello@e2b.dev).
