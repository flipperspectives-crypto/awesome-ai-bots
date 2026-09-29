# Awesome AI Bots

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ehaywarde/awesome-ai-bots/blob/main/CONTRIBUTING.md)

A curated list of the best AI bots, autonomous agents, and conversational AIs — from coding assistants and research agents to creative companions and productivity automatons.

> **What counts as an "AI bot"?** Anything agentic enough to act on your behalf with minimal supervision: autonomous agents that plan and execute tasks, coding assistants that edit your repo, research bots that browse and synthesize, creative companions that generate content, and productivity bots that manage your workflow.

- [Autonomous Agents](#autonomous-agents)
- [Coding Assistants](#coding-assistants)
- [Research & Data Bots](#research--data-bots)
- [Creative & Writing Bots](#creative--writing-bots)
- [Productivity & Workflow](#productivity--workflow)
- [Open-Source Frameworks](#open-source-frameworks)
- [Chatbots & Conversational AIs](#chatbots--conversational-ais)
- [Contributing](#contributing)
- [License](#license)

---

## Autonomous Agents

Agents that can plan, reason, and take multi-step actions in an environment with little supervision.

| Bot | Type | Open Source | Description |
| --- | ---- | ----------- | ----------- |
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | Task automation | ✅ | Autonomous agent that breaks down goals into sub-tasks and executes them using LLMs and tools. |
| [BabyAGI](https://github.com/yoheinakajima/babyagi) | Task automation | ✅ | Minimal autonomous agent that creates, prioritizes, and executes tasks using OpenAI APIs. |
| [LangChain Agent](https://python.langchain.com/docs/modules/agents/) | Framework | ✅ | Pluggable agent framework with tool use, memory, and chains for building autonomous agents. |
| [OpenAgent](https://github.com/LAION-AI/Open-Assistant) | Conversational | ✅ | Open-source alternative to ChatGPT with a growing ecosystem of agent tools. |
| [HuggingGPT](https://github.com/microsoft/JARVIS) | Task automation | ✅ | Microsoft's agent that uses ChatGPT to plan and execute tasks via Hugging Face tools. |
| [Muse](https://ai.meta.com/muse/) | Personal agent | ❌ | Meta's personal AI agent that browses the web, connects to apps, and completes multi-step tasks (email, travel, shopping) with your direction and oversight. |
| [Dots](https://openai.com) | Computer-use agent | ❌ | OpenAI's computer-use agent built on its latest model; runs on a cloud computer to navigate apps and websites like a human. |
| [Grok Bot](https://x.ai/bot) | Team agent | ❌ | xAI's always-on AI teammates that have their own computer, work inside tools & apps, and keep working 24/7. |

## Coding Assistants

AI bots that write, edit, and navigate code.

| Bot | Type | Open Source | Description |
| --- | ---- | ----------- | ----------- |
| [GitHub Copilot](https://github.com/features/copilot) | Pair programmer | ❌ | AI pair programmer that suggests code and entire functions inline. |
| [Cursor](https://cursor.sh) | IDE agent | ❌ | AI-first code editor with deep repo knowledge and agentic editing. |
| [Claude Code](https://claude.ai/code) | Agentic CLI | ❌ | Anthropic's agentic coding assistant that can make edits, run tests, and create PRs. |
| [OpenAI Codex](https://github.com/openai/codex) | CLI agent | ✅ | Open-source CLI agent from OpenAI that can run code, tests, and navigate repos. |
| [Amazon Q Developer](https://aws.amazon.com/q/developer/) | IDE agent | ❌ | AWS's coding assistant with repo context and multi-file editing. |
| [Gemini CLI](https://docs.google.com/gemini-cli) | CLI agent | ❌ | Google's agentic CLI for coding tasks using Gemini models. |

## Research & Data Bots

Bots that browse the web, analyze data, and synthesize findings.

| Bot | Type | Open Source | Description |
| --- | ---- | ----------- | ----------- |
| [Perplexity.ai](https://perplexity.ai) | Answer bot | ❌ | AI-powered research assistant with web search and citation. |
| [Elicit](https://elicit.org) | Research bot | ❌ | AI research assistant that finds and summarizes academic papers. |
| [ChatGPT with Browsing](https://chat.openai.com) | Conversational | ❌ | ChatGPT with web browsing and data analysis capabilities. |
| [Claude with Computer Use](https://claude.ai) | Agentic | ❌ | Anthropic's Claude that can use a computer (browser, apps) to complete tasks. |
| [Operator](https://www.anthropic.com/assistant/operators) | Agentic | ❌ | Anthropic's agent that automates tasks in a web browser. |

## Creative & Writing Bots

AI companions for writing, art, and creative work.

| Bot | Type | Open Source | Description |
| --- | ---- | ----------- | ----------- |
| [ChatGPT](https://chat.openai.com) | Conversational | ❌ | General-purpose conversational and creative AI by OpenAI. |
| [Claude](https://claude.ai) | Conversational | ❌ | Conversational AI by Anthropic focused on helpfulness and safety. |
| [Gemini](https://gemini.google.com) | Conversational | ❌ | Google's multimodal AI assistant for chat, images, and coding. |
| [Midjourney](https://midjourney.com) | Creative | ❌ | AI image generation bot accessible via Discord. |
| [Suno AI](https://suno.ai) | Music | ❌ | AI music generation bot for creating songs from text. |

## Productivity & Workflow

Bots that automate repetitive tasks and manage workflows.

| Bot | Type | Open Source | Description |
| --- | ---- | ----------- | ----------- |
| [Gong AI](https://www.gong.io) | Meeting assistant | ❌ | AI that records, transcribes, and analyzes sales calls. |
| [Otter.ai](https://otter.ai) | Transcription | ❌ | AI-powered transcription and note-taking bot. |
| [Notion AI](https://www.notion.so/ai) | Workspace assistant | ❌ | AI assistant integrated into Notion for writing, summarizing, and organizing. |
| [Slack AI](https://slack.com/features/slack-ai) | Team assistant | ❌ | AI features built into Slack for summaries, search, and automation. |
| [Zapier AI](https://zapier.com/app/agent) | Automation | ❌ | No-code automation bot with AI-powered workflows. |

## Open-Source Frameworks

Frameworks for building your own AI bots and agents.

| Bot | Type | Open Source | Description |
| --- | ---- | ----------- | ----------- |
| [LangChain](https://github.com/langchain-ai/langchain) | Framework | ✅ | Framework for building applications with LLMs — supports agents, chains, and memory. |
| [LlamaIndex](https://github.com/run-llamalabs/LlamaIndex) | Framework | ✅ | Data orchestration framework for connecting LLMs with custom data sources. |
| [AutoGen](https://github.com/microsoft/autogen) | Framework | ✅ | Microsoft's framework for creating multi-agent conversational AI systems. |
| [CrewAI](https://github.com/joaolafciosilva/crewai) | Framework | ✅ | Framework for orchestrating role-playing AI agents with delegation and task execution. |
| [OpenHands](https://github.com/BerriAI/openhands) | Agent | ✅ | Open-source AI coding agent with multi-turn reasoning and tool use. |

## Chatbots & Conversational AIs

Simple conversational bots and chat interfaces.

| Bot | Type | Open Source | Description |
| --- | ---- | ----------- | ----------- |
| [Ollama](https://ollama.com) | Local chat | ✅ | Run LLMs locally with a simple chat interface. |
| [Chatbot UI](https://github.com/mckaywrig/ChatBot) | Chat UI | ✅ | Open-source ChatGPT interface built with Next.js and React. |
| [Flowise](https://github.com/HausDev1/CheatSheet) | Chatflow builder | ✅ | Drag-and-drop UI for building LLM flows and chatbots. |
| [Grok](https://grok.com) | Conversational | ❌ | xAI's AI chatbot with real-time X search, voice, image/video generation, and coding help. |
| [Meta AI](https://ai.meta.com) | Conversational | ❌ | Meta's assistant available across Facebook, Instagram, WhatsApp, and web — answers questions and generates images. |
| [DeepSeek](https://chat.deepseek.com) | Conversational | ❌ | DeepSeek's assistant with multilingual chat, reasoning, and coding support. |
| [Poe](https://poe.com) | Multi-bot hub | ❌ | Hub granting access to many AI models (Claude, GPT, Gemini, Llama) and specialized bots. |
| [Pi](https://heypi.com) | Conversational | ❌ | Inflection's personal AI focused on supportive, conversational interactions. |

---

## Contributing

Contributions are welcome! See our [Contributing Guide](CONTRIBUTING.md) for details.

To add a bot:

1. Fork the repo
2. Create a branch (`git checkout -b add/bot-name`)
3. Add your entry to the relevant table in alphabetical order
4. Run `git add . && git commit -m "Add <Bot Name>"`
5. Push and open a PR

### Guidelines

- Only include bots with a clear public presence (website, docs, or repo).
- Use the existing table format.
- Prefer direct links to official sites/repos.

## License

[CC0 1.0](LICENSE) — This list is dedicated to the public domain.
