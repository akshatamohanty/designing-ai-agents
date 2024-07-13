# Designing AI Agents

This repository is a collection of concepts, notes, research papers, articles, design patterns, tools, and examples useful for building AI agents.

🚜👷🚧🏗️ Note: This repo is under active development. Things will move around a lot.

# About agents

AI Agents are software programs capable of:
- Interacting with their environment
- Collecting data
- Planning
- Making decisions based on data
- Performing predetermined goals
- Autonomously

## Architectural patterns
- [GenAI architectural patterns](https://www.linkedin.com/pulse/generative-ai-architectural-patterns-debmalya-biswas-hlvye/)
- [Navigating Complexity: Orchestrated Problem Solving with Multi-Agent LLMs](https://arxiv.org/html/2402.16713v1)
- [3 Patterns in Agent Design](https://alexsniffin.medium.com/three-ai-design-patterns-of-autonomous-agents-8372b9402f7c)
- [Design Patterns with Autogen](https://www.deeplearning.ai/short-courses/ai-agentic-design-patterns-with-autogen/)


## Architectural types

### Simple Reflex Agents
- Simple reflex agents respond directly to stimuli from the environment without considering the history of the world.

### Model-based Reflex Agents
- Model-based reflex agents use a model of the world to handle partially observable environments.

### Goal-based Agents
- Goal-based agents act to achieve specific goals.

### Utility-based Agents
- Utility-based agents aim to maximize their performance measure through a utility function.

### Learning Agents
- Learning agents have the ability to improve their performance over time based on experience.

### ReAct Agent (Reason + Action)
- Combines reasoning and action to improve decision-making processes in AI agents.

### Task-Planner Agent
- Uses task planning to break down complex goals into manageable tasks for the agent to execute.

### Multi-Agent Orchestration
- Coordinates multiple agents to work together towards common goals, enhancing their collective performance.

### Examples Agents
- [Awesome AI Agents](https://github.com/e2b-dev/awesome-ai-agents)

### General Resources
- [Attention is All You Need](https://arxiv.org/abs/1706.03762)
- [GPT-3: Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)
- [State of GPT by Microsoft](https://www.youtube.com/watch?v=bZQun8Y4L2A&t=65s)
- [Busy Executive's Guide on LLMs](https://www.youtube.com/watch?v=zjkBMFhNj_g&t=179s&pp=ygUTYW5kcmVqIGthcnBhdGh5IGxsbQ%3D%3D)

## Components of Agents

- Agent Personas and Goals: Developing and defining different agent personas and their objectives to tailor their behavior.
- Decision Making and Planning
  - [Prompting Best Practices](https://www.promptingguide.ai/)
- Automated Planning and Scheduling
  - [Automated Planning and Scheduling](https://en.wikipedia.org/wiki/Automated_planning_and_scheduling)
- Learning and Adaptation
  - Concepts and techniques for enabling AI agents to learn and adapt to new environments and challenges.
  - [Cooperative Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2007.02761)
  - [One-Shot Learning with Memory-Augmented Neural Networks](https://arxiv.org/abs/1605.06065)
  - [Zero-Shot Learning: A Comprehensive Evaluation of the Good, the Bad and the Ugly](https://arxiv.org/abs/1707.00600)
- Multi-agent Systems and Coordination
- Interactions
  - Best practices and techniques for designing interactions between AI agents and humans.
  - Techniques for processing and managing inputs and outputs for AI agents.
  - Reflection (Reflexion)
- Hallucinations
  - Grounding
      - [Grounding with Google AI](https://cloud.google.com/blog/products/ai-machine-learning/rag-and-grounding-on-vertex-ai)
- Deployments, scalability and Performance
  - LangChain with Reasoning Engine
- Security and Privacy


## Other Resources
- [Startup School](https://www.startupschool.org/courses/gen-ai): Gen AI - Building AI Agents
