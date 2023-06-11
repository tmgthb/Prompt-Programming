# PROMPT PROGRAMMING

Prompt programming techniques enable using Large Language Models (LLMs) to build Autonomous agents through:
- use of LLMs chains,
- use of LLM workflows with or without external memory / tools / APIs.

Not all papers are specifically written about Prompt engineering, yet specific concepts in these papers are interesting from Prompt programming perspective.

---

## 8th June 2023
[ToolAlpaca: Generalized Tool Learning for Language Models with 3000 Simulated Cases](https://arxiv.org/pdf/2306.05301.pdf)

- Builds multi-agent simulation environment to generate dataset of using many real world apis. 
- Small models can achieve comparable performance to larger models on tool usage.

---

## 5th June 2023
[SELFEVOLVE: A Code Evolution Framework via Large Language Models](https://arxiv.org/pdf/2306.02907.pdf)

- Generates intermediate code based on input prompt. 
- Use LLM to act as expert programmer to debug the generated code by receiving errors from Python interpreter.

---

## 3th June 2023
[Prompt Sapper: LLM-Empowered Software Engineering Infrastructure for AI-Native Services](https://arxiv.org/pdf/2306.02230.pdf)

- Human AI collaborative intelligence methodology & technical practices, where the idea is not to have "full Auto-GPT" from user input to direct resolution by LLM, but rather human reviews steps between.
- Useer inputs objective, LLM asks clarification. Use then  User adds clarifications and LLM constructs AI chain for human to review. Finally LLM executes the AI chain with user acceptabnce tests.

---

## 3th June 2023
[Auto-GPT for Online Decision Making: Benchmarks and
Additional Opinions](https://arxiv.org/pdf/2306.02224.pdf)

- Auto-GPTs outperforms supervised state-of-the-art Imitiation Learning (IL) models with GPT4 in WebShop- and ALFWorld-benchmarks in unknown external environments.
- Additional opinions algorithm improves performance, which takes into account additional opinions from external expert models.

---

## 24th May 2023
[Gorilla: Large Language Model Connected with Massive APIs](https://arxiv.org/abs/2305.15334)

- Gorilla is a retrieve-aware finetuned LLaMA-7B model for API calls using self-instruct to generate Instruction-API pairs. 


---

## 17th May 2023
[Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/abs/2305.10601)

- Tree of Thoughts (ToT)-technique makes decisions using multiple different reasoning paths, self-evaluating choices to decide next action with ability to look back/forward for global decisions.

---

## 11th April 2023

[Teaching Large Language Models to Self-Debug](https://arxiv.org/abs/2304.05128)

- The model generates new code together with code explanation. The code is then executed and this executed code is sent back as feedback together with the code explanation. This feedback

---

## 7th of April 2023
[ChatPipe: Orchestrating Data Preparation Program by Optimizing Human-ChatGPT Interactions](https://arxiv.org/abs/2304.03540)

- ChatPipe - Iterative, data preparation program with ChatGPT using 1. Operation Recommendation, 2.   Program generation, 3. Version management. 
- Recommends next data preparation opration. Easily roll-back to previous program for version control.

---

## 6th April 2023
[Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442)

- Enable believable human behavior: observation, planning, and reflection.
- An agent wants to throw a Valentine’s Day party. The agents autonomously spread invitations, make new acquaintances, ask each other out on dates to the party, and coordinate to show up for the party together at the right time. 
- [GPTeam](https://github.com/101dotxyz/GPTeam) is inspired by this approach.

---

## 31 March 2023
[CAMEL: Communicative Agents for "Mind" Exploration of Large Scale Language Model Society](https://arxiv.org/abs/2303.17760)

- CAMEL attempts to facilitate autonomous cooperation among communicative agents through role-playing framework.
- The approach manages complete tasks with minimal human input.

---

## 30th of March 2023
[HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in HuggingFace](https://arxiv.org/abs/2303.17580)

- A LLM (such as ChatGPT) accesses HuggingFace community to look AI models to complete the given task. 
- It can read multi modalities by outsourcing tasks like image recognition to the specific image model. 

[DERA: Enhancing Large Language Model Completions with Dialog-Enabled Resolving Agents](https://arxiv.org/abs/2303.17071)

- Dialog-eEabled Resolving Agents (DERA) uses two roles: Researcher and Decider to perform discussion between these two agents.
- Researcher role processes information and Decider role uses judgement.

---

## 29th of March 2023
[TaskMatrix.AI: Completing Tasks by Connecting Foundation Models with Millions of APIs](https://arxiv.org/abs/2303.16434)

- Multimodal conversational foundation model (MCFM). MCFM generates a textual solution outline, then API selector chooses most relevant API from collection of APIs (with API name, parameter list, description, usage example and example when combining it with another API). 
- MCFM generates action code using recommended API and the API call is executed. Finally, output is provided back to developer.

---

## 28th March 2023 
[Task-driven Autonomous Agent Utilizing GPT-4, Pinecone, and LangChain for Diverse Applications](https://yoheinakajima.com/task-driven-autonomous-agent-utilizing-gpt-4-pinecone-and-langchain-for-diverse-applications/)

- Task-driven autonomous agent, with vector database and Langchain. BabyGPT includes: Execution, creation and prioritization
- Takes objective, pulls an item from task queue and moves it to execution agent with access to memory. 

---

## 20th March 2023
[Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366)

- Reflexion agents reflect on task feedback, use it from memory to make better decisions and new attempts.


---



# PROMPT ENGINEERING
Prompt engineering techniques are here considered "traditional" in sense of helping to to outperform vanilla LLM prompt, as their code idea. These Prompt engineering techniques are useful and popular. Therefore it is good to be familiar with them, too. This list is "an additional reading" to Prompt Programming, rather than a complete list of Prompt engineering.

---
## 6th October 2022
[ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)

- Enhancing Chain of Thought through task solving with one/two-examples ofg "Action:"-information together with "Thought:"-information

## 21 March 2022
[Self-Consistency Improves Chain of Thought Reasoning in Language Models](https://arxiv.org/abs/2203.11171)

- Self-cconsistency by sampling diverse set of reasoning paths.

---

## 28th January 2022
[Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)

- Chain of THought (CoT) examples help perform complex reasoning. 


[]()
---
