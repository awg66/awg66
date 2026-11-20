### Hi, I'm Alex 👋

Senior Machine Learning Engineer on Workday's AI Platform team in New York. I build the internal developer platform that Workday teams use to build, deploy and run AI agents in production, and the platform behind Custom Agents for Workday Extend AI customers.

Before agents, I built ML inference frameworks for Workday Financials and spent several years as an engineer and technical architect on Workday Student. Cornell CS.

#### 🧰 What I work on
- **Agent platform:** a Python SDK ("Workday LangChain") that wraps LangChain primitives and routes them through Workday's LLM gateway, retrieval service and internal tooling
- **Agent infrastructure:** LangGraph, LangSmith and Agent Server, with A2A and MCP support built in
- **ML inference:** created Workday's Synchronous and Asynchronous Inference Frameworks for Financials

#### 📜 Patents
- **Generative AI Assistant for a Low-Code Platform** · [US 12,792,842 B2](https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/12792842) (issued Nov 2026)

#### 🔬 Research
- **[Deep Manifold Traversal Background Subtraction](papers/deep-manifold-traversal-background-subtraction.pdf)** · Cornell MEng, advised by Kilian Weinberger. Reframed background subtraction for static cameras as a label-changing problem, using Deep Manifold Traversal (VGG features + MMD) to generate a scene's background directly from webcam data, then isolate the foreground. Evaluated on the AMOS webcam archive, with a time-window filter on target images that noticeably improved background quality.

#### 🎥 Talks & features
- [How Workday Builds Agent Prototypes in Under a Day with LangChain](https://www.youtube.com/watch?v=xM_BhmEyKAY): video interview with the LangChain team
- [How Workday Built an Enterprise-Scale AI Agent Platform with LangGraph and LangSmith](https://www.langchain.com/blog/how-workday-built-an-enterprise-scale-ai-agent-platform-with-langgraph-and-langsmith): LangChain case study on taking agent prototypes from 4 to 5 months to under a day

#### 🔧 Open source
18 accepted issues across the LangChain ecosystem (langchain, langgraph, deepagents, langchain-aws, langchain-google, langchain-mcp-adapters), mostly found while running agents in production at scale. A few highlights:
- **langgraph:** [`with_config` silently ignored `recursion_limit` when it matched the default, so an earlier bound limit survived](https://github.com/langchain-ai/langgraph/issues/9416)
- **deepagents:** [summary-model call wasn't covered by `ContextOverflowError` recovery](https://github.com/langchain-ai/deepagents/issues/6861)
- **deepagents:** [offloaded tool results advertised paths `execute` couldn't use when the sandbox backend remapped them](https://github.com/langchain-ai/deepagents/issues/6960)
- **langchain:** [`SummarizationMiddleware` retried the identical request after `ContextOverflowError`](https://github.com/langchain-ai/langchain/issues/41155)
- **langchain-aws:** tool-choice support for Bedrock models ([Claude with thinking](https://github.com/langchain-ai/langchain-aws/issues/647), [Claude Fable](https://github.com/langchain-ai/langchain-aws/issues/1273), [DeepSeek v3.2](https://github.com/langchain-ai/langchain-aws/issues/1270), [gpt-oss](https://github.com/langchain-ai/langchain-aws/issues/1278))

[See all accepted issues →](https://github.com/search?q=author%3Aawg66+org%3Alangchain-ai+is%3Aissue+reason%3Acompleted&type=issues)

Also added [deepagents-cli support to rulesync](https://github.com/dyoshikawa/rulesync/pull/1359).

#### 📫 Find me
[LinkedIn](https://www.linkedin.com/in/alexander-gatto-3010616b/)
