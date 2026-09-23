> 一番下に日本語版もあります

# Hi, I'm Kota Kawagoe 👋
**AI Agent Researcher / Software Engineer** — Bridging the gap between **Art/Design (UI/UX)** and **Backend Logic**.

At Keio University Graduate School of Media and Governance, I research and develop AI agents.

My current focus is less on LLMs themselves and more on the foundational technologies that connect LLMs to real applications. I work on how agents select Memory / Skill / Tool / Agent resources, execute them safely, maintain state and context, and recover from failures.

Alongside research, I build, launch, and operate web services including ChatCore-AI. I develop the backend, frontend, and infrastructure needed to run AI features reliably in production.

**Vision**: I aim to implement AI agents in society to foster a world where human communication flourishes. I want AI to be woven naturally into everyday life — present in the robots and displays we pass simply by walking through the city. By delegating daily tasks to AI, I want to create a society where people can truly focus on meaningful, face-to-face interactions.

- **Focus**: Object Routing, AI Agent Infrastructure, Multi-Agent Systems, RAG, Browser Agents, UI/UX.
- **Location**: Japan | **Languages**: Japanese (Native) / English

## 🔬 Current Research

### Object Routing

I study Object Routing: selecting a set of task-relevant, executable resources from large catalogs of Memory, Skills, Tools, and Agents.

Beyond candidate retrieval, I evaluate the selection pipeline across dependency resolution, conflict handling, permission checks, decisions to abstain or request elevated permissions, and hierarchical routing. I am implementing this research in **Marmo-Core**, a kernel for routing and safely executing agent resources.

## 🎓 Research Achievements

For my undergraduate thesis, I developed a multi-agent system integrating specialist agents for browser use, RAG, scheduling, and IoT.

By combining long-term and short-term memory, I improved the system's evaluation score by approximately **1.7×**. I presented this work at **NCSP'26** in Honolulu, USA.

My current master's research extends this work to AI-agent resource routing and safe execution infrastructure.

## 🔗 Links
- **Resume**: [https://github.com/kota-kawa/resume](https://github.com/kota-kawa/resume)
- **Portfolio**: [https://project-kk.com/](https://project-kk.com/)
- **LinkedIn**: [https://www.linkedin.com/in/kota-kawa/](https://www.linkedin.com/in/kota-kawa/)
- **Email**: [kota7kawagoe@gmail.com](mailto:kota7kawagoe@gmail.com)

## 🌐 Live Services
Direct access to my currently active applications and platforms.

- **[ChatCore-AI](https://chatcore-ai.com/)** — *Production AI chat platform with multi-model streaming and web tools.*
- **[FS-QR]** (https://fs-qr.net/) — *File Sharing & QR Code Generator.*

## ⭐ Highlights
1) **[Browser-Agent](https://github.com/kota-kawa/Browser-Agent)** — *Control the web with natural language.*
   - **Overview**: A browser automation agent with a FastAPI web interface. Executes tasks via natural language instructions with real-time monitoring via noVNC.
   - **Performance**: WebArena Shopping task success rate: 32.6%.
   - **Technologies**: Python, FastAPI, TypeScript, Docker.

2) **[ChatCore-AI](https://github.com/kota-kawa/ChatCore-AI)** ([Live](https://chatcore-ai.com/)) — *Production AI chat platform.*
   - **Overview**: Built with FastAPI and Next.js, this live platform supports streaming responses from multiple LLMs, web research and tool use, Tasks and Skills, persistent context, prompt sharing, and generative UI. It also includes Redis-backed session management, usage and cost controls, SSE recovery, tests, and CI/CD, with ongoing improvements for production operation.
   - **Technologies**: Python, FastAPI, Next.js, React, TypeScript, PostgreSQL, Redis, Docker, Nginx, GitHub Actions, OpenAI, Anthropic, Groq.

3) **[Marmo-Core](https://github.com/kota-kawa/Marmo-Core)** — *(Lightweight AI-Agent Kernel)*
   - **Overview**: A lightweight Python kernel for registering, retrieving, selecting, and safely executing AI-agent resources. It provides policy-gated execution, audit trails, human approval, recovery, a CLI, and integrations with OpenAI-compatible and Anthropic models.
   - **Technologies**: Python, LLMs, retrieval, policy and security, CLI, JSON resource definitions.

## 🎓 Education
- **Keio University, Graduate School of Media and Governance**
    - Master's Program in Cyber Informatics
    - Kanagawa, Japan | April 2026 – Present
- **Kanagawa Institute of Technology** (KAIT)
    - Faculty of Information Technology
    - Department of Information Network and Communication
- **University of North Alabama** — Exchange Program Completed
    - Alabama, USA | May 2023 – May 2024

## 🧰 Tech Stack

| Category | Technologies |
|---|---|
| Programming Languages | Python, TypeScript, SQL |
| Web / Application Frameworks | FastAPI, React, Next.js, Tailwind CSS, PostgreSQL, Redis |
| AI / LLM Engineering | RAG, Multi-Agent Systems, LangChain, LangGraph, browser-use |
| Infrastructure | Docker, AWS (EC2, VPC, Systems Manager), Linux, Nginx, Git, GitHub Actions, pytest |
| IoT / Hardware | NVIDIA Jetson Orin Nano, Raspberry Pi 4/Pico W |
| AI Tools | Codex, Claude Code, NotebookLM, Antigravity, Gemini, ChatGPT, Claude |

## 🗓️ Now
- **Researching / Building**: Implementing my Object Routing research in Marmo-Core, a safe execution kernel for Memory, Skill, Tool, and Agent resources.

_Last updated: 2026-09-23_

<details>
  <summary>日本語版（Japanese Version）</summary>

# こんにちは、川越 航太 (Kota Kawagoe) です 👋
**AI Agent Researcher / Software Engineer** — **Art/Design (UI/UX)** と **バックエンドロジック**。

慶應義塾大学大学院 政策・メディア研究科で、AIエージェントに関する研究・開発を行っています。

現在は、LLMそのものよりも、LLMと実際のアプリケーションをつなぐ基盤技術に重点を置いています。エージェントが必要なMemory / Skill / Tool / Agentをどのように選択するか、安全に実行するか、状態やコンテキストをどのように維持するか、障害からどのように回復するかといったテーマに取り組んでいます。

研究だけでなく、ChatCore-AIをはじめとしたWebサービスを実際に公開・運用し、AI機能を本番環境で安定して動かすためのバックエンド・フロントエンド・インフラまで一貫して開発しています。

**Vision**: AIエージェントの社会実装を通じて、人同士のコミュニケーションがより促進される豊かな社会の実現を目指しています。街を歩けばロボットやディスプレイなど、AIが当たり前のように生活に溶け込んでいる——そんな社会を作りたいと考えています。「日常のタスクをAIに委ね、人が対面でのコミュニケーションに集中できる社会」を実現することが私の目標です。

- **専門領域**: Object Routing, AIエージェント基盤, マルチエージェントシステム, RAG, Browser Agent, UI/UX Design.
- **拠点**: 日本 | **言語**: 日本語（母国語）/ 英語

## 🔬 現在の研究

### Object Routing

大規模なMemory / Skill / Tool / Agentのカタログから、タスクに適合し、実行可能なリソース集合を選択するObject Routingを研究しています。

候補検索にとどまらず、依存関係や競合の処理、権限の判定、棄権や権限昇格要求の判断、階層ルーティングまで含めた選択パイプライン全体を評価しています。この研究成果を、エージェント用リソースのルーティングと安全な実行を担う **Marmo-Core** に実装しています。

## 🎓 研究実績

学部の卒業研究では、Browser、RAG、Scheduler、IoTなどの専門エージェントを統合したマルチエージェントシステムを開発しました。

長期・短期メモリを組み合わせ、システムの評価スコアを約 **1.7倍** に改善しました。この研究成果を **NCSP'26**（米国・ホノルル）で発表しました。

現在の修士研究では卒業研究を発展させ、AIエージェントのリソースルーティングと安全な実行基盤を研究しています。

## 🔗 リンク
- **Resume**: [https://github.com/kota-kawa/resume](https://github.com/kota-kawa/resume)
- **Portfolio**: [https://project-kk.com/](https://project-kk.com/)
- **LinkedIn**: [https://www.linkedin.com/in/kota-kawa/](https://www.linkedin.com/in/kota-kawa/)
- **Email**: [kota7kawagoe@gmail.com](mailto:kota7kawagoe@gmail.com)

## 🌐 稼働中のサービス
現在実際にアクセスして利用可能なサービスです。

- **[ChatCore-AI](https://chatcore-ai.com/)** — *複数LLMのストリーミングとWebツールに対応した本番運用AIチャットプラットフォーム。*
- **[FS-QR]** (https://fs-qr.net/) — *ファイル共有 & QR。*

## ⭐ 代表作
1) **[Browser-Agent](https://github.com/kota-kawa/Browser-Agent)** — *自然言語でWebを操作する*
   - **概要**: FastAPIベースのWebインターフェースを持つブラウザ自動操作エージェント。自然言語の指示でタスクを実行し、noVNCでリアルタイム監視が可能。
   - **性能**: WebArena Shoppingタスク成功率: 32.6%。
   - **使用技術**: Python, FastAPI, TypeScript, Docker.

2) **[ChatCore-AI](https://github.com/kota-kawa/ChatCore-AI)** ([Live](https://chatcore-ai.com/)) — *本番運用中のAIチャットプラットフォーム*
   - **概要**: FastAPIとNext.jsで構築し、公開・運用しているAIチャットプラットフォーム。複数LLMのストリーミング応答、Web調査とツール利用、Task / Skill、永続コンテキスト、プロンプト共有、生成UIを実装。Redisによるセッション管理、利用量・コスト制御、SSEストリームの障害復旧に加え、テストとCI/CDも整備し、本番運用を継続的に改善。
   - **使用技術**: Python, FastAPI, Next.js, React, TypeScript, PostgreSQL, Redis, Docker, Nginx, GitHub Actions, OpenAI / Anthropic / Groq.

3) **[Marmo-Core](https://github.com/kota-kawa/Marmo-Core)** — *（軽量AIエージェント・カーネル）*
   - **概要**: AIエージェント用リソースの登録・検索・選択・安全な実行を担う軽量なPythonカーネル。ポリシーによる実行制御、監査ログ、人による承認、リカバリ、CLI、OpenAI互換およびAnthropicモデルとの連携を提供。
   - **使用技術**: Python, LLM, Retrieval, Policy / Security, CLI, JSONリソース定義.

## 🎓 学歴
- **慶應義塾大学大学院** 湘南藤沢キャンパス（SFC）
    - 政策・メディア研究科 サイバーインフォマティクス専攻 修士課程
    - 神奈川県 | 2026年4月 – 現在
- **神奈川工科大学**
    - 情報学部 情報ネットワーク・コミュニケーション学科
- **University of North Alabama** — 交換留学プログラム修了
    - アラバマ州, 米国 | 2023年5月 – 2024年5月

## 🧰 技術スタック

| カテゴリ | 技術 |
|---|---|
| プログラミング言語 | Python, TypeScript, SQL |
| Web / アプリケーション基盤 | FastAPI, React, Next.js, Tailwind CSS, PostgreSQL, Redis |
| AI / LLM エンジニアリング | RAG, Multi-Agent Systems, LangChain, LangGraph, browser-use |
| インフラ | Docker, AWS (EC2, VPC, Systems Manager), Linux, Nginx, Git, GitHub Actions, pytest |
| IoT / ハードウェア | NVIDIA Jetson Orin Nano, Raspberry Pi 4/Pico W |
| AI ツール | Codex, Claude Code, NotebookLM, Antigravity, Gemini, ChatGPT, Claude |

## 🗓️ 現在
- **研究・開発**: Object Routingの研究成果を、Memory / Skill / Tool / Agentのルーティングと安全な実行を担うMarmo-Coreに実装しています。

_Last updated: 2026-09-23_

</details>
