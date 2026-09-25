# Jev Library

A curated directory of the Jev ecosystem — 1009 projects and 98 resources, organised by category.

Browse, search and filter it at **[jevlibrary.dev](https://jevlibrary.dev)**.

_Last updated: Sep 24, 2026._

## Contents

- [Official](#official) (19)
- [SDKs & clients](#sdks--clients) (84)
- [Integrations](#integrations) (42)
- [Agent tooling](#agent-tooling) (239)
- [Browser & computer use](#browser--computer-use) (99)
- [Applications](#applications) (135)
- [Games & simulations](#games--simulations) (69)
- [Demos & playgrounds](#demos--playgrounds) (100)
- [Benchmarks & research](#benchmarks--research) (204)
- [Other lists](#other-lists) (32)
- [Articles & threads](#articles--threads) (51)
- [Jev for marketing](#jev-for-marketing) (6)
- [Jev for robotics](#jev-for-robotics) (9)
- [Jev alternatives & open source](#jev-alternatives--open-source) (21)

## Official

Docs, SDKs, and resources from TypeSafe AI.

| Project | Description | Language | Stars |
| --- | --- | --- | ---: |
| [TypeSafe agent skills](https://github.com/typesafe-ai/skills) · [site](https://typesafe.ai) | Official agent skill for Claude Code, Codex, and compatible agents: primitives, patterns, and how to structure evaluations. |  | ⭐ 2.1k |
| [System One adapter (Python)](https://github.com/typesafe-ai/system-one-adapter-python) | Official drop-in TypeSafeClient replacement backed by OpenAI, Anthropic, and compatible LLM APIs, for comparing Jev against chat models. | Python | ⭐ 287 |
| [TypeSafe JavaScript SDK](https://github.com/typesafe-ai/typesafe-sdk-js) | Official TypeScript/JavaScript client with inferred answer types. npm install @typesafe-ai/sdk. | TypeScript | ⭐ 232 |
| [TypeSafe Python SDK](https://github.com/typesafe-ai/typesafe-sdk-python) · [site](https://docs.typesafe.ai/sdk/python) | Official sync and async Python client. pip install typesafe-sdk. | Python | ⭐ 220 |
| [@typesafeai on X](https://x.com/typesafeai) | Product and research updates. |  |  |
| [Cookbooks](https://docs.typesafe.ai/cookbooks/parallel_questions) | Reproducible recipes: parallel questions, reranking, guardrails, citation checks, extraction, hierarchical classification. |  |  |
| [Discord](https://discord.gg/typesafe) | Official TypeSafe server. Builder demos live in the Show and Tell channel. |  |  |
| [Documentation](https://docs.typesafe.ai) | Introduction, primitives, patterns, cookbooks, HTTP API, and SDK references. |  |  |
| [HTTP API reference](https://docs.typesafe.ai/api) | Request and response contract for POST /v1/systemone. |  |  |
| [Introducing System One Models and Jev](https://typesafe.ai/blog/introducing-system-one-models-and-jev) | Launch post: architecture, RLCD training, pricing, Doom and Wikiracing demos, FAQ. |  |  |
| [Jev 1.13 jaggedness](https://docs.typesafe.ai/model-jaggedness/jev-1.13) | Known failure modes of the current public model, documented by TypeSafe. |  |  |
| [Manifesto](https://typesafe.ai/manifesto) | The case for machine-native intelligence built for software, not conversation. |  |  |
| [Patterns](https://docs.typesafe.ai/patterns) | Speculative fan-out, confidence-gated routing, composite scoring, and intent routing. |  |  |
| [Playground](https://console.typesafe.ai/playground) | Paste a state, add questions, and see typed answers in the browser. |  |  |
| [Primitives](https://docs.typesafe.ai/primitives) | Choice, Score, and Noul: the three question types and what they return. |  |  |
| [Quick start](https://docs.typesafe.ai/introduction/quickstart) | Shortest path from an API key to a typed decision. |  |  |
| [Smart home demo](https://docs.typesafe.ai/demos/smart-home) | Official interactive demo of speculative fan-out: many questions in one call, code keeps the relevant answers. |  |  |
| [TypeSafe AI](https://typesafe.ai) | Company homepage, waitlist, and product overview. |  |  |
| [Workflow evals](https://evals.typesafe.ai) | Published eval methodology and per-model results for System One workflows. |  |  |

## SDKs & clients

Community clients for languages without an official SDK.

| Project | Description | Language | Stars |
| --- | --- | --- | ---: |
| [advocaat](https://github.com/pithings/advocaat) | A small, type-safe client for asking AI questions about your data, powered by TypeSafe Jev. | TypeScript | ⭐ 91 |
| [ruby_decision_model](https://github.com/obie/ruby_decision_model) | Ruby client for decision models such as Typesafe Jev | Ruby | ⭐ 50 |
| [spring-ai-typesafe](https://github.com/spring-ai-community/spring-ai-typesafe) · [site](https://spring-ai-community.github.io/spring-ai-typesafe) | A Java SDK for the TypeSafe AI JEV API, & Spring AI TypeSafe integrations. | Java | ⭐ 36 |
| [jev (dannote)](https://github.com/dannote/jev) | TypeSafe Jev for OTP: reply to Jev from a GenServer and pattern match on its answer | Elixir | ⭐ 32 |
| [jevalyn](https://github.com/Ray-Hughes/jevalyn) | The decision layer for your Rails app. A Rails-native wrapper around TypeSafe's Jev System One API: typed, calibrated decisions in your control flow. | Ruby | ⭐ 19 |
| [go-jev](https://github.com/mattn/go-jev) | Go SDK and CLI for TypeSafe Jev: typed decisions (yes/no, choice, score) from a model | Go | ⭐ 16 |
| [evoke](https://github.com/evoke-build/evoke) · [site](https://evoke.build) | Software, by reflex. A sentence becomes a call of a small program, chosen by Jev, TypeSafe AI's classifier, and run only when it is sure enough. Reflexes are recipes anyone can write, share and improve. A CLI you talk to, a package manager for reflexes from git, and a TypeScript SDK. | Rust | ⭐ 14 |
| [typesafe-sdk-go (atharvamhaske)](https://github.com/atharvamhaske/typesafe-sdk-go) · [site](https://typesafe-sdk-go.mintlify.site/) | unofficial go sdk for typesafe ai | Go | ⭐ 14 |
| [jevper](https://github.com/zhulinchng/jevper) | Jev-shaped (TypeSafe System One) classification wrapper over OpenAI-like clients: probabilities and confidence instead of prose | Python | ⭐ 12 |
| [typesafe-ai](https://github.com/Twister915/typesafe-ai) | Typed TypeSafe AI clients for Rust, with async and blocking backends and observable retries. | Rust | ⭐ 12 |
| [super-jev](https://github.com/Kevthetech143/super-jev) | A small, extensible decision-to-action harness for TypeSafe Jev | Python | ⭐ 11 |
| [swift-jev](https://github.com/d-date/swift-jev) | A Swift client for TypeSafe AI's Jev — typed judgements, not text | Swift | ⭐ 11 |
| [typesafe-sdk-go (Tangerg)](https://github.com/Tangerg/typesafe-sdk-go) | Go SDK for the TypeSafe AI API — typed questions in, probability distributions out. | Go | ⭐ 9 |
| [JevSwiftSDK](https://github.com/NSStudent/JevSwiftSDK) | An independent, type-safe Swift SDK for TypeSafe Jev, with async/await, batching, retries, and SPM support. | Swift | ⭐ 8 |
| [typesafe-dotnet-sdk](https://github.com/saibimajdi/typesafeai-dotnet-sdk) · [site](https://saibimajdi.github.io/typesafeai-dotnet-sdk/) | Community .NET SDK for the TypeSafe AI System One API — typed noul, choice, and score questions with structured, confidence-scored answers. Not affiliated with TypeSafe AI. | C# | ⭐ 8 |
| [zod-jev](https://github.com/jomatsu/zod-jev) | Zod validates the shape, Jev validates the meaning: semantic checks on request bodies become calibrated probabilities you threshold in code. | TypeScript | ⭐ 8 |
| [jev-dsl](https://github.com/inanna-malick/jev-dsl) | Agent-first Haskell DSL for TypeSafe's Jev judgment model: typed packets, inferred types, answers under the same labels | Haskell | ⭐ 7 |
| [jevgo (devbackend)](https://github.com/devbackend/jevgo) | Unofficial Go client for the TypeSafe AI System One API (Jev) — typed questions in, calibrated answers out. | Go | ⭐ 7 |
| [typesafe-sdk (joshmn)](https://github.com/joshmn/typesafe-sdk) | Ruby client for typesafe.ai | Ruby | ⭐ 7 |
| [scala-jev-sdk](https://github.com/ticofab/scala-jev-sdk) | Effect-agnostic Scala 3 client for the System One API that runs on any sttp backend (Future, cats-effect, ZIO, Monix, or blocking) with answers typed by question value. | Scala | ⭐ 6 |
| [jev-go](https://github.com/Stumble/jev-go) | Community Go SDK for TypeSafe AI Jev / System One | Go | ⭐ 5 |
| [jev4k](https://github.com/pambrose/jev4k) · [site](https://jev4k.com) | A Kotlin DSL and client for TypeSafe's Jev model | Kotlin | ⭐ 5 |
| [typesafe_sdk](https://github.com/nshkrdotcom/typesafe_sdk) | An idiomatic, type-safe Elixir port of the official TypeScript AI SDK (ai / ai-sdk) providing unified LLM integrations, streaming text and structured outputs, tool calling, and agentic workflows. Jev is their current flagship model and is the first System One model. | Elixir | ⭐ 5 |
| [typesafe-ai-rs](https://github.com/gilljon/typesafe-ai-rs) · [site](https://docs.rs/typesafe-ai-rs) | Independent async and blocking Rust SDK for the TypeSafe AI System One API | Rust | ⭐ 5 |
| [typesafe-sdk-java](https://github.com/Premo-Cloud/typesafe-sdk-java) · [site](https://docs.typesafe.ai) | Community Java client for the TypeSafe System One API (unofficial) | Java | ⭐ 5 |
| [jev-android](https://github.com/dougsong/jev-android) | A Kotlin Android SDK for UI automation powered by TypeSafe Jev, with an accessibility runtime and sample app. | Kotlin | ⭐ 4 |
| [jev-go (Gaurav-Gosain)](https://github.com/Gaurav-Gosain/jev-go) | Go client for TypeSafe's System One API and its model Jev: typed judgments and calibrated probabilities instead of generated text | Go | ⭐ 4 |
| [JevR](https://github.com/mountainMath/JevR) | R client for the TypeSafe Jev System One API | R | ⭐ 4 |
| [rust-sysone](https://github.com/zcoder-run/rust-sysone) | System One TypeSafe AI Rust Client (unofficial) | Rust | ⭐ 4 |
| [typesafe-ai-java](https://github.com/jamilxt/typesafe-ai-java) | Community-maintained Java SDK for the TypeSafe AI System One (Jev) API. Not an official TypeSafe product. | Java | ⭐ 4 |
| [zio-typesafe-ai](https://github.com/jamesward/zio-typesafe-ai) | Scala 3 / ZIO client for the System One API: typed end-to-end, several questions per round-trip via NamedTuple. | Scala | ⭐ 4 |
| [jev (virolea)](https://github.com/virolea/jev) | Ruby client for the typesafe AI Jev model | Ruby | ⭐ 3 |
| [jev-java](https://github.com/Olti1947/jev-java) | Idiomatic Java SDK for TypeSafe AI Jev System One decision engine | Java | ⭐ 3 |
| [jev-java (gudcks0305)](https://github.com/gudcks0305/jev-java) | Unofficial Java SDK for TypeSafe Jev and Vercel AI Gateway, with Spring Boot and WebClient support | Java | ⭐ 3 |
| [jod](https://github.com/mateonunez/jod) · [site](https://npmjs.com/package/@mateonunez/jod) | Semantic schemas over TypeSafe's Jev — validate the state locally, then project typed answers. | TypeScript | ⭐ 3 |
| [SystemOneDotNet](https://github.com/JabbaKadabra/SystemOneDotNet) | .NET client for TypeSafe System One (Jev) — typed questions in, typed answers with probabilities and confidence out. No prompt engineering, no output parsing. | C# | ⭐ 3 |
| [typesafe-jev-bridge](https://github.com/RevocGG/typesafe-jev-bridge) | Use the TypeSafe Jev decision model (System One) anywhere: zero-dependency OpenAI-compatible bridge for 9Router, Claude Code, Cursor, Cline & any OpenAI SDK. Typed yes/no, choice & score judgments via CLI or HTTP. | JavaScript | ⭐ 3 |
| [typesafe-sdk-cpp](https://github.com/pewriebontal/typesafe-sdk-cpp) | An unofficial CPP 20 SDK for the TypeSafe API | C++ | ⭐ 3 |
| [typesafe-sdk-dotnet](https://github.com/hardkoded/typesafe-sdk-dotnet) | Unofficial .NET port of the TypeSafe AI client SDK (typed questions & answers) | C# | ⭐ 3 |
| [typesafe-sdk-rust](https://github.com/codeitlikemiley/typesafe-sdk-rust) | Rust SDK for the TypeSafe AI API | Rust | ⭐ 3 |
| [typesafe-sdk-swift](https://github.com/InsaneArts/typesafe-sdk-swift) | Swift SDK for TypeSafe AI | Swift | ⭐ 3 |
| [ElBruno.AI.Jev](https://github.com/elbruno/ElBruno.AI.Jev) | Community .NET 10 SDK for official TypeSafe AI Jev typed decisions and Microsoft.Extensions.AI integrations. | C# | ⭐ 2 |
| [jev-docs](https://github.com/chenrui333/jev-docs) | Community-maintained history of Jev / TypeSafe System One APIs, SDKs, agent guidance, and engineering best practices. | Python | ⭐ 2 |
| [jev-net](https://github.com/brightshore/jev-net) · [site](https://www.nuget.org/packages/Jev.Net) | A lightweight .NET client for the TypeSafe AI API (System One / Jev). One dependency; a faithful port of the official Python SDK. | C# | ⭐ 2 |
| [jev-php-sdk](https://github.com/mzainzulifqar/jev-php-sdk) · [site](https://packagist.org/packages/mzainzulifqar/jev-php-sdk) | PHP SDK for TypeSafe's Jev: send text and typed questions, get typed answers with calibrated confidence. PHP 8.1+, works with any PSR-18 client, Laravel 8–13. | PHP | ⭐ 2 |
| [jev-sdk-java](https://github.com/luigivis/jev-sdk-java) | Type-safe Java 21 client for the TypeSafe AI Jev (System One) decision API | Java | ⭐ 2 |
| [jevclient](https://github.com/AboveColin/jevclient) · [site](https://pypi.org/project/jevclient/) | Async Python client for TypeSafe Jev. Typed questions in, probabilities and choices out, no prose to parse. | Python | ⭐ 2 |
| [jevgo](https://github.com/fgn/jevgo) | Go client for TypeSafe AI's System One API (Jev), with optional Langfuse instrumentation | Go | ⭐ 2 |
| [typesafe-ai-jev](https://github.com/kcb-swe-gh/typesafe-ai-jev) | Java 21 client for Jev, TypeSafe AI's structured decision model | Java | ⭐ 2 |
| [typesafe-go (zhirschtritt)](https://github.com/zhirschtritt/typesafe-go) | Idiomatic Go SDK for the TypeSafe AI API | Go | ⭐ 2 |
| [TypeSafeAI.Net](https://github.com/Hawxy/TypeSafeAI.Net) · [site](https://docs.typesafe.ai/) | .NET SDK for the TypeSafe AI platform | C# | ⭐ 2 |
| [decido](https://github.com/yairshy/decido) | Probabilistic decisions for Python. Use Jev or bring your own provider; crawl with Playwright. | Python | ⭐ 1 |
| [jev](https://github.com/anilsenay/jev) | Unofficial Go client for TypeSafe's System One API and its model, Jev. | Go | ⭐ 1 |
| [jev (kataras)](https://github.com/kataras/jev) · [site](https://docs.typesafe.ai/introduction) | A Go client for the TypeSafe AI's System One API and its model, Jev. | Go | ⭐ 1 |
| [jev-go (guillemus)](https://github.com/guillemus/jev-go) | Unofficial Go SDK for TypeSafe AI's Jev API | Go | ⭐ 1 |
| [jev-go (kyledickey)](https://github.com/kyledickey/jev-go) · [site](https://docs.typesafe.ai) | TypeSafe.ai Jev Go SDK | Go | ⭐ 1 |
| [jev-harness-router](https://github.com/JoacoMarc/jev-harness-router) · [site](https://www.npmjs.com/package/jev-harness-router) | Per-turn router for agent harnesses: one 350ms Jev call picks the model tier, effort, tools and skill, behind a hard deadline with a regex fallback. Claude Agent SDK adapter included. | TypeScript | ⭐ 1 |
| [qualm](https://github.com/qddegtya/qualm) | Typed decisions from a System One model. An uncertain answer is a different type from a confident one — and the compiler makes you handle it. | TypeScript | ⭐ 1 |
| [s1-rs](https://github.com/AbdelStark/s1-rs) | Typed System One layer for Rust (Choice/Score/Noul). | Rust | ⭐ 1 |
| [system-one (asynq-io)](https://github.com/asynq-io/system-one) · [site](https://asynq-io.github.io/system-one/) | Vendor-neutral SDK for typed decision-making (yes/no, choice, score) — hosted and local | Python | ⭐ 1 |
| [system-one-playground](https://github.com/DonaldMurillo/system-one-playground) · [site](https://donaldmurillo.github.io/system-one-playground/) | Readable scripting, semantic code checks, a Go System One client, and Studio. | Go | ⭐ 1 |
| [tinystruct-typesafe-sdk](https://github.com/tinystruct/tinystruct-typesafe-sdk) · [site](https://tinystruct.org) | A tinystruct-based TypeSafe SDK with JEV model. | Java | ⭐ 1 |
| [typesafe](https://github.com/mattneel/typesafe) | An idiomatic Elixir client for the TypeSafe AI API | Elixir | ⭐ 1 |
| [typesafe_sdk_ex](https://github.com/vinnie357/typesafe_sdk_ex) | Typesafe AI SDK in Elixir using Req | Elixir | ⭐ 1 |
| [typesafe-client](https://github.com/JedimEmO/typesafe-client) | Unofficial typed async Rust client for the TypeSafe System One API | Rust | ⭐ 1 |
| [typesafe-go (cole-gillespie)](https://github.com/cole-gillespie/typesafe-go) | unofficial go SDK for typesafe AI, with typed answers, retries, and context support | Go | ⭐ 1 |
| [typesafe-rs](https://github.com/AbdelStark/typesafe-rs) · [site](https://docs.rs/typesafe-rs/latest/typesafe_rs/) | Latency-first Rust SDK for TypeSafe System One. | Rust | ⭐ 1 |
| [typesafe-sdk (binnash)](https://github.com/binnash/typesafe-sdk) | PHP & Laravel SDK for TypeSafe AI's JEV Model series | PHP | ⭐ 1 |
| [typesafe-sdk-go (dwisiswant0)](https://github.com/dwisiswant0/typesafe-sdk-go) · [site](https://go.dw1.io/typesafe-sdk-go?godoc=1) | Go SDK for TypeSafe AI. | Go | ⭐ 1 |
| [typesafe-sdk-go (unimtx)](https://github.com/unimtx/typesafe-sdk-go) | Community Go SDK for the TypeSafe System One API with typed Choice, Score, and Noul questions plus retries, contexts, and structured errors. | Go | ⭐ 1 |
| [typesafe-sdk-ruby](https://github.com/afurm/typesafe-sdk-ruby) · [site](https://typesafe.ai) | Unofficial Ruby SDK for the TypeSafe AI API (Jev model) - typed questions, retries, and typed errors. Community port of typesafe-sdk-js. | Ruby | ⭐ 1 |
| [typesafe-sdk-rust (zchee)](https://github.com/zchee/typesafe-sdk-rust) · [site](https://docs.rs/typesafe-sdk-rust) | Unofficial async Rust SDK for the TypeSafe AI System One API: typed questions via #[derive(QuestionSet)], a port of typesafe-sdk-python. | Rust | ⭐ 1 |
| [TypeSafe.Jev](https://github.com/RavenValentin/TypeSafe.Jev) · [site](https://www.nuget.org/packages/TypeSafe.Jev) | Typed AI decisions for .NET: ask Jev (TypeSafe AI System One) yes/no, choice and score questions and get a C# enum with calibrated probabilities back. | C# | ⭐ 1 |
| [TypeSafeAI](https://github.com/tryAGI/TypeSafeAI) · [site](https://tryagi.github.io/TypeSafeAI/) | First-class, NativeAOT-ready .NET SDK for TypeSafe AI System One, generated with AutoSDK. | C# | ⭐ 1 |
| [typesafeai-go](https://github.com/chez-shanpu/typesafeai-go) | Go SDK for TypeSafe AI API https://docs.typesafe.ai/api | Go | ⭐ 1 |
| [hunch (steven-shoemaker)](https://github.com/steven-shoemaker/hunch) | Python library, with a TypeScript port, that turns Jev Choice, Score, and Noul questions into functions over lists and DataFrames: classify, score, check, where, extract, pick, rank, verify. | Python | ⭐ 0 |
| [kojev](https://github.com/ItisNoMatter/kojev) | Kotlin Multiplatform client for Jev that answers Choice and Score questions as your own enums. | Kotlin | ⭐ 0 |
| [kunobi-jev](https://github.com/kunobi-ninja/kunobi-jev) | Rust client for the TypeSafe System One API (Jev) | Rust | ⭐ 0 |
| [tinyjevclient](https://github.com/tinyhumansai/tinyjevclient) | An integration with jev by typesafe.ai in Rust | Rust | ⭐ 0 |
| [typesafe_ai (hfiguera)](https://github.com/hfiguera/typesafe_ai) | A supervised Mint client for the TypeSafe AI System One API | Elixir | ⭐ 0 |
| [typesafe_ai (typesend)](https://github.com/typesend/typesafe_ai) · [site](https://typesafe-api.hexdocs.pm/readme.html) | Unofficial Elixir SDK for the TypeSafe AI API | Elixir | ⭐ 0 |
| [typesafe-sdk-go](https://github.com/valksor/typesafe-sdk-go) | Unofficial Go SDK for the TypeSafe AI System One API — 1:1 parity with the official JS and Python SDKs. Not affiliated with TypeSafe AI. | Go | ⭐ 0 |
| [typesafe-sdk-php](https://github.com/valksor/typesafe-sdk-php) · [site](https://packagist.org/packages/valksor/typesafe-sdk-php) | Unofficial PHP SDK for the TypeSafe AI System One API — 1:1 parity with the official JS and Python SDKs. Not affiliated with TypeSafe AI. | PHP | ⭐ 0 |
| [typesafe.zig](https://github.com/mattneel/typesafe.zig) | An idiomatic Zig client for the TypeSafe AI API | Zig | ⭐ 0 |

## Integrations

Jev inside frameworks, gateways, and platforms.

| Project | Description | Language | Stars |
| --- | --- | --- | ---: |
| [eve](https://github.com/vercel/eve) · [site](https://eve.dev) | Vercel's open agent framework, which ships Jev as the default evaluation model in its experimental evaluate path. | TypeScript | ⭐ 5.3k |
| [ai-cli](https://github.com/vercel-labs/ai-cli) · [site](https://ai-cli.dev) | Vercel Labs terminal CLI that can run Jev as the evaluation model for its evaluate command. | TypeScript | ⭐ 813 |
| [pg-jev](https://github.com/realZachi/pg-jev) · [site](https://pgjev.com) | Ask your Postgres tables questions in plain language. A PostgreSQL extension powered by TypeSafe's Jev. | Shell | ⭐ 329 |
| [neo4jev](https://github.com/jexp/neo4jev) | Typesafe.ai System One Model Jev navigating a Neo4j graph by using a classifier over neighbouring relationships | Jupyter Notebook | ⭐ 129 |
| [jev-shell-history](https://github.com/mrnugget/jev-shell-history) | Fish-style zsh history autosuggestions ranked by Jev (TypeSafe) | TypeScript | ⭐ 108 |
| [pg_typesafe](https://github.com/giuliosmall/pg_typesafe) | Pre-alpha PostgreSQL extension for TypeSafe AI (Jev) categorical classification | C | ⭐ 82 |
| [jevmail](https://github.com/fazlerocks/jevmail) | Open-source AI email triage for Gmail. Sorts your inbox into Needs reply, Updates, Promos, Sales and Spam with Jev, TypeSafe AI's decision model, via Vercel AI Gateway. Read-only, runs locally, 1,000 emails in about a minute for 3 cents. | TypeScript | ⭐ 74 |
| [A home that understands](https://github.com/AboveColin/HA-Jev) | Turn the state of your home into typed decisions, sensors, and smarter automations. | Python | ⭐ 58 |
| [Loki](https://github.com/wundercorp/loki) · [site](https://loki.computer) | Self-improving agent harness with an optional TypeSafe Jev companion for typed Choice, Score, and Noul judgments. | Python | ⭐ 26 |
| [ruby_llm-typesafe](https://github.com/kieranklaassen/ruby_llm-typesafe) | TypeSafe structured-output provider for RubyLLM 2 | Ruby | ⭐ 18 |
| [jevql](https://github.com/kylemclaren/jevql) · [site](https://jevql.fly.dev/) | Semantic SQL for Postgres, powered by Jev | Go | ⭐ 12 |
| [jev-feels](https://github.com/Qew7/jev-feels) | Semantic decisions as ordinary Ruby — feels?, decide, score, Rails validations and pattern matching powered by Jev | Ruby | ⭐ 11 |
| [typesafe-jev-workflow](https://github.com/GiesN/typesafe-jev-workflow) | Async LangGraph workflow that gets a typed Jev Choice (invoice or general) and routes each inbound email to the matching handler. | Python | ⭐ 9 |
| [jevc](https://github.com/doronp/jevc) · [site](https://www.npmjs.com/package/jev-compiler) | Compile agent policy prose into deterministic verdict programs: narrow evidence questions for the model, the verdict computed in code. Install: npm i -g jev-compiler | TypeScript | ⭐ 6 |
| [a0-typesafe-ai](https://github.com/3clyp50/a0-typesafe-ai) | TypeSafe AI Jev judgments for Agent Zero, with typed tools and probability cards. | Python | ⭐ 5 |
| [typesafe-ui](https://github.com/TypeSafeAI/typesafe-ui) · [site](https://typesafe-ui.vercel.app) | shadcn-style reusable components and blocks for using TypeSafe AI. | TypeScript | ⭐ 5 |
| [llama-index-jev](https://github.com/WiktorB2004/llama-index-jev) | LlamaIndex reranker + router powered by TypeSafe Jev — typed scores/choices, cheaper than LLM-as-judge. | Python | ⭐ 4 |
| [typesafe-on-neon](https://github.com/andrelandgraf/safer-with-jev) | Neon Function proxy for the Neon AI Gateway with TypeSafe Jev routing. | TypeScript | ⭐ 4 |
| [jevmetrics](https://github.com/ishantanu/jevmetrics) | OpenTelemetry Collector connector that uses Jev to assess metric metadata and apply retention policies before export. | Go | ⭐ 3 |
| [langchain-loadout](https://github.com/deyna256/langchain-skill-router) · [site](https://pypi.org/project/langchain-loadout/) | Per-turn skill selection for LangChain and deepagents agents: a fast judge picks the few skills a turn needs, so a catalog of hundreds stays out of the prompt. | Python | ⭐ 3 |
| [laravel-typesafe-jev](https://github.com/Butochnikov/laravel-typesafe-jev) | Unofficial Laravel integration for TypeSafe Jev AI with typed responses, async requests, scoped dependency injection, and testing fakes. | PHP | ⭐ 3 |
| [n8n-nodes-jev](https://github.com/vibe-with-me-tools/n8n-nodes-jev) · [site](https://www.npmjs.com/package/n8n-nodes-jev) | Helper n8n community node for Jev by TypeSafe. Classify, route, and score text with questions you define, and get a probability for every answer so unsure items can go to review. | TypeScript | ⭐ 3 |
| [pydantic-jev-examples](https://github.com/adtyavrdhn/pydantic-jev-examples) | Pydantic AI capabilities made stronger with Jev: small runnable demos, one file each | Python | ⭐ 3 |
| [typesafe-ai-rails](https://github.com/GenieRobot/typesafe-ai-rails) | Community Rails integration on the typesafe-sdk gem: configuration, persisted usage and cost telemetry, and opt-in confidence policies. | Ruby | ⭐ 3 |
| [typesafe-assist](https://github.com/JanOstrowka/typesafe-assist) | Home Assistant Assist conversation agent powered by TypeSafe's Jev (System One) model | Python | ⭐ 3 |
| [demo-symfony-typesafe](https://github.com/yoanbernabeu/demo-symfony-typesafe) | Démo : trier des demandes de support avec Jev (TypeSafe) et Symfony AI. Messenger, Live Components, Turbo, kit shadcn de UX Toolkit. | PHP | ⭐ 2 |
| [hush](https://github.com/emreozyoruk/hush) | GitHub Action for issue triage that abstains: label, spam, needs-info and duplicate in one call, each applied only above a threshold you set, and nothing at all below it. | JavaScript | ⭐ 2 |
| [Jev4Mellea](https://github.com/SoundBlaster/Jev4Mellea) | Jev adapter to Mellea | Python | ⭐ 2 |
| [n8n-nodes-jev-classification](https://github.com/khmuhtadin/n8n-nodes-jev-classification) · [site](https://www.npmjs.com/package/n8n-nodes-jev-classification) | n8n community node for Jev by TypeSafe AI: classify, score and check text with calibrated probabilities. Parallel requests and multi-item batching. | TypeScript | ⭐ 2 |
| [n8n-nodes-typesafe-jev](https://github.com/n3ndor/n8n-nodes-typesafe-jev) | n8n community node for TypeSafe Jev structured AI decisions | TypeScript | ⭐ 2 |
| [jev-lens.nvim](https://github.com/rashedInt32/jev-lens.nvim) | Neovim popup for jev-lens verdicts: do I need to look, which files, and strip the debris. | Lua | ⭐ 1 |
| [judging-with-typesafe](https://github.com/carlsonchik/judging-with-typesafe) | Скилл для агентов Letta: суждения по критериям через TypeSafe System One (Jev) | Python | ⭐ 1 |
| [agentgateway Jev guardrail example](https://github.com/agentgateway/agentgateway/tree/main/examples/llm-guardrail-jev) | Jev as an LLM prompt guardrail inside the agentgateway proxy, with tracing and cost tracking. | TypeScript |  |
| [discern](https://github.com/doeixd/discern) · [site](https://www.npmjs.com/package/@doeixd/discern) | Uncertainty-aware control flow for Effect: Jev's Choice, Noul and Score answers become typed patterns with an explicit Uncertain branch, plus routable procedures, recording, replay, caching and call budgets. | TypeScript | ⭐ 0 |
| [Jev on Vercel AI Gateway](https://vercel.com/ai-gateway/models/jev) | Hosted typesafe-ai/jev for AI SDK evaluate calls, no TypeSafe waitlist required. |  |  |
| [jev-acp](https://github.com/formulahendry/jev-acp) | Use Jev's Choice, Score, and Noul decisions from ACP-compatible clients, with guided input, reusable templates, and probability displays. | TypeScript | ⭐ 0 |
| [jevtraces](https://github.com/ishantanu/jevtraces) | OpenTelemetry Collector processor that uses Jev to assess span operation metadata and annotate spans with diagnostic value, business criticality, and retention probabilities without dropping traces. | Go | ⭐ 0 |
| [Milvus Model](https://github.com/milvus-io/milvus-model) | Python reranker adapter that sends candidate documents as Jev Noul questions in one request, then sorts the returned scores and preserves original document indices. | Python | ⭐ 0 |
| [n8n-nodes-typesafe-ai](https://github.com/DomMonte/n8n-nodes-typesafe-ai) · [site](https://docs.typesafe.ai) | n8n community node for the TypeSafe AI System One API — typed yes/no, choice and score questions with calibrated probabilities | TypeScript | ⭐ 0 |
| [TrainLCD Jev rerank](https://github.com/TrainLCD/Functions/pull/33) | Pull request adding Jev to station-suggestion reranking in the TrainLCD transit app. | TypeScript |  |
| [Vercel AI SDK provider](https://ai-sdk.dev/providers/ai-sdk-providers/typesafe-ai) | @ai-sdk/typesafe-ai plus experimental_evaluate; use jev-latest as an evaluation model. |  |  |
| [voice_control](https://github.com/igorkasyanchuk/voice_control) · [site](https://youtu.be/Zz1Ibx8R7WI) | Rails engine for voice and typed commands: define actions in a Ruby DSL and Jev picks the matching command or page control, with your own authorization and signed, replay-protected execution. | Ruby | ⭐ 0 |

## Agent tooling

Gates, routers, reviewers, MCP servers, and skills for coding agents.

| Project | Description | Language | Stars |
| --- | --- | --- | ---: |
| [fast-jev-compaction](https://github.com/tamaratran/fast-jev-compaction) | Claude Code plugin that replaces the compaction summary with Jev decisions: every tool call and result is scored in one fast request, stale ones are dropped or truncated, everything kept stays verbatim. | TypeScript | ⭐ 6.7k |
| [jev-review (devagrawal09)](https://github.com/devagrawal09/jev-review) | A staged code-review workflow and local dashboard built with TypeSafe Jev. | TypeScript | ⭐ 586 |
| [foreman](https://github.com/thruwire/foreman) · [site](https://thruwire.ai) | Software Factory Foreman: an agent supervisor that uses Jev decisions to keep coding agents on task. | Python | ⭐ 540 |
| [jev-search](https://github.com/superagents-lab/jev-search) · [site](https://jev.s1.dev) | Search the web with TypeSafe's Jev: source selection, query understanding and relevance ranking. Built with Search1API. | TypeScript | ⭐ 446 |
| [jev-router (gargpratyush)](https://github.com/gargpratyush/jev-router) | Route to the cheapest model in claude code for your task using jev-router | JavaScript | ⭐ 377 |
| [jev-mcp (jkudish)](https://github.com/jkudish/jev-mcp) | Proof of concept MCP for Typesafe's new Jev AI model | JavaScript | ⭐ 320 |
| [TypeSafe MCP](https://github.com/itsmostafa/typesafe-mcp) | Bring typed Jev judgments to your coding assistant through a single MCP server. | Go | ⭐ 292 |
| [jev-codex-router](https://github.com/0xNatoshi/jev-codex-router) | Per-turn model & reasoning routing for Codex, driven by Jev (TypeSafe System One): picks the model, thinking depth and speed mode for every turn. | JavaScript | ⭐ 263 |
| [jev-review (NiazMorshed2007)](https://github.com/NiazMorshed2007/jev-review) | Local-first MCP plugin for continuous software-quality review by AI coding agents, powered by Jev. | TypeScript | ⭐ 218 |
| [JevHarness](https://github.com/TianyuCodings/JevHarness) · [site](https://jev-harness.tianyuchen99.chatgpt.site) | LLM-authored task-specific Jev harnesses with optional full-trajectory reward reflection and GEPA evolution. | Python | ⭐ 191 |
| [JevRouter](https://github.com/BillionsBobby/JevRouter) | A lightweight Jev-powered router for models, tools, and subagents | TypeScript | ⭐ 190 |
| [perch](https://github.com/lakeday-org/perch) · [site](https://perchscan.com/) | Open-source CLI that parses a repository into a method-level call graph, then asks Jev to flag likely defects and check project rules written in plain English. | JavaScript | ⭐ 171 |
| [jev-dsh-decision](https://github.com/Devin-AXIS/jev-dsh-decision) | Jev DSH 决策引擎｜面向 Agent Harness 的结构化决策插件。原生支持 DeepSeek Harness，通过 iPolloWork 支持 OpenCode、Codex Harness。 | JavaScript | ⭐ 163 |
| [jev-pruner](https://github.com/tamaratran/jev-pruner) | Claude Code plugin: trim long Bash output with TypeSafe Jev before the model sees it | TypeScript | ⭐ 144 |
| [pi-jev (y0usaf)](https://github.com/y0usaf/pi-jev) | TypeSafe Jev as a decision layer for the Pi coding agent: a measured tool-call gate plus jev_ask for typed, calibrated answers | TypeScript | ⭐ 144 |
| [pi-warden](https://github.com/DevMortimer/pi-warden) | Guardrails for Pi built on pi-typesafe that steer the agent instead of interrupting you: Jev judges irreversible and off-task tool calls, detects stuck loops, checks unverified done claims, flags slop | TypeScript | ⭐ 138 |
| [building-with-jev-skill](https://github.com/dbreunig/building-with-jev-skill) | A skill for writing and improving programs that call Jev, TypeSafe's System One model |  | ⭐ 131 |
| [jev-engineering-zh](https://github.com/yibie/jev-engineering-zh) | 《Jev 工程学：为 coding agent 而作》完整中文翻译 — 保留原结构与 7 张插图 |  | ⭐ 116 |
| [skillranker](https://github.com/Dicklesworthstone/skillranker) | Rust CLI powered by Jev from TypeSafe.ai that ranks agent skills for the next step using live session context. Includes Claude Code hooks, structured JSON, abstention, and local feedback. Requires a TypeSafe API key. | Rust | ⭐ 116 |
| [jev-code](https://github.com/devagrawal09/stanley-code) | Bounded TypeSafe Jev workflows for coding agents. | TypeScript | ⭐ 114 |
| [Supercov](https://github.com/supercorp-ai/supercov) · [site](https://supercov.com) | Code quality and test coverage for coding agents: Jev scores each source file so the agent knows what to fix first. | Rust | ⭐ 109 |
| [winnow](https://github.com/GhalebDweikat/winnow) | A calibrated context sieve for Claude Code: every tool result is judged by a System One model before it enters context. | Python | ⭐ 81 |
| [grok-bot-jev](https://github.com/Bodila51/grok-bot-jev) · [site](https://docs.typesafe.ai) | Connect TypeSafe Jev to Grok Bot as a cheap decision layer - usage gates, skill template, examples | Python | ⭐ 78 |
| [jev-lint](https://github.com/mizchi/jev-lint) | Natural-language linter combining ast-grep selectors with Jev verdicts to catch misleading names, stale comments, and tests that miss their stated behavior, with fixture-calibrated cutoffs and diff-aware review. | TypeScript | ⭐ 78 |
| [jgrep](https://github.com/keltokhy/jgrep) | grep, but the pattern is a description. Filters lines by meaning with TypeSafe's Jev decision model: ~200 ms and a thousandth of a cent per line. | Python | ⭐ 78 |
| [Canny](https://github.com/qkal/Canny) | Stops AI coding agents from claiming work is done without evidence. Deterministic hooks decide, TypeSafe's Jev advises. Append-only ledger, zero runtime dependencies. | TypeScript | ⭐ 76 |
| [Jev-Mem](https://github.com/libingzheren/Jev-Mem) | Jev-Mem: System-One Controlled Agentic Memory | Python | ⭐ 67 |
| [jeview](https://github.com/andududu/jeview) | An unofficial local visualizer for Jev (TypeSafe): a live view of every call your code makes. Not affiliated with TypeSafe AI. | JavaScript | ⭐ 48 |
| [jev-recruiter](https://github.com/skeptrunedev/jev-recruiter) | A Jev powered LinkedIn recruiting agent. Watch it browse relevant profiles, save links, and review evidence against your hiring brief. | Python | ⭐ 47 |
| [jev-seo](https://github.com/AkashPriyadarshii/jev-seo) · [site](https://akashpriyadarshii.github.io/jev-seo/) | 100% free ₹0 agent-first SEO & GEO CLI suite and MCP server in Rust replacing Semrush and OpenSEO via DuckDuckGo and TypeSafe Jev System One | Rust | ⭐ 47 |
| [hono-jev-router](https://github.com/yusukebe/hono-jev-router) | Route HTTP requests by meaning. A semantic router for Hono powered by Jev. | TypeScript | ⭐ 46 |
| [pi-jev (TheoOliveira)](https://github.com/TheoOliveira/pi-jev) | Semantic tool routing and typed System One decisions for the Pi coding agent using TypeSafe Jev | TypeScript | ⭐ 46 |
| [jev-mcp (burnigtm)](https://github.com/burnigtm/jev-mcp) | MCP server that puts TypeSafe Jev on the coding loop in Cursor, Codex, and any MCP client | TypeScript | ⭐ 43 |
| [ask-jev-skill](https://github.com/shantanugoel/ask-jev-skill) | Skill for Hermes, and other agents, to ask typesafe's jev | Python | ⭐ 39 |
| [jev-guard (klauswg)](https://github.com/klauswg/jev-guard) | Real-time risk triage gateway for exchange deposits and withdrawals — Jev (TypeSafe System One) handles triage only; adjudication stays in deterministic code. | Java | ⭐ 35 |
| [jev-recall](https://github.com/samdotmak/jev-recall) | Retrieve by relevance, not resemblance: filter an AI assistant's memories with TypeSafe's Jev | TypeScript | ⭐ 34 |
| [jev-guard](https://github.com/leepokai/jev-guard) | Prompt-injection and dangerous-action guard for coding agents (Claude Code, Codex, pi, ACP), powered by Jev | JavaScript | ⭐ 32 |
| [jev-skill-suggester](https://github.com/win4r/jev-skill-suggester) | 用 TypeSafe Jev 推荐已安装 Skill / Bounded installed-skill recommendations with TypeSafe Jev. Python CLI, Codex skill, bilingual docs and live examples. | Python | ⭐ 31 |
| [snifftest](https://github.com/DanRWilloughby/snifftest) · [site](https://www.npmjs.com/package/snifftest) | A prose linter that sniffs out AI writing tells. Zero dependencies, countable rules plus one judgment model. | TypeScript | ⭐ 29 |
| [jev-use](https://github.com/shitianfang/jev-use) · [site](https://www.npmjs.com/package/jev-use) | Claude Code / Codex / pi plugin that hands agent steps needing no text output to Jev (TypeSafe's judgment model) — measured p50 ~230 ms and ~$0.02 per 1,000 judgments, with typed escalation back to the LLM | JavaScript | ⭐ 25 |
| [yoshi](https://github.com/compozy/yoshi) | Context-pruning proxy for Claude Code and Codex: Jev judges which history is still needed, measured not claimed. POC here now, heading soon into https://github.com/compozy/compozy | TypeScript | ⭐ 25 |
| [is-malicious](https://github.com/luantak/is-malicious) | Scans a codebase for covert, deceptive, or data-stealing behavior with Jev, then reports suspicious files and line ranges before the user runs it. | TypeScript | ⭐ 23 |
| [pi-jev-auto-mode](https://github.com/jomatsu/pi-jev-auto-mode) | Jev (TypeSafe System One) backed auto mode for the Pi coding agent: semantically auto-approves bash, write, and edit tool calls and fails closed when a decision cannot be made. | TypeScript | ⭐ 23 |
| [jev-mcp (blakestone-x)](https://github.com/blakestone-x/jev-mcp) | MCP server for TypeSafe Jev: typed classify, score, check, match and screen for any agent, with confidence on every answer | Python | ⭐ 22 |
| [slop-grader](https://github.com/lukstei/slop-grader) · [site](https://www.npmjs.com/package/@lukstei/slop-grader) | Rule-based slop grader for text files powered by Jev: evaluates markdown against customizable rulesets, outputting violation flags and scores for an AI agent to auto-fix. | TypeScript | ⭐ 22 |
| [hermes-jev](https://github.com/keeltrace/hermes-nerve) | Typed System One decisions, ranking, verification, and an opt-in Hermes tool gate using TypeSafe Jev. | Python | ⭐ 21 |
| [jev-axi](https://github.com/shiftynick/jev-axi) · [site](https://www.npmjs.com/package/jev-axi) | Agent-ergonomic CLI for TypeSafe's Jev: fast calibrated judgments (pick, rate, check, rank, triage, guard) from the shell | TypeScript | ⭐ 21 |
| [jev-cli (Nasrallah-AL)](https://github.com/Nasrallah-AL/jev-cli) · [site](https://jevcli.vectorz.app/) | Command-line tool for TypeSafe's Jev AI model | TypeScript | ⭐ 21 |
| [jev-superpowers](https://github.com/AkashPriyadarshii/jev-superpowers) · [site](https://jev-superpowers.vercel.app) | Systematic software development framework for AI coding agents upgraded with TypeSafe Jev System One typed decisions | HTML | ⭐ 21 |
| [agent-chaperone](https://github.com/agent-chaperone/agent-chaperone) · [site](https://agentchaperone.dev) | Screens an AI agent's tool calls before they run and tool results before the agent reads them. An MCP proxy plus a hooks adapter for a client's built-in tools. | TypeScript | ⭐ 20 |
| [jev-code (rhighs)](https://github.com/rhighs/jev-code) | Interactive TypeScript coding CLI with typed routing, decision programs, and validated formal trees driven by Jev. | TypeScript | ⭐ 20 |
| [Cheshi](https://github.com/CheshiAI/Cheshi) | Jev-powered conversation memory: find past sessions and revisit decisions with original sources. A macOS workspace for OpenAI Codex. Manage AI conversations and agents, explore code with CodeGraph, and work with Git, Ghostty terminals, and Apple Notes in one app. | C | ⭐ 18 |
| [jev-belay](https://github.com/valentynkit/jev-belay) | Claude Code Stop hook that blocks an unverified done: reads the transcript for evidence, asks Jev once, fails open on everything else | JavaScript | ⭐ 18 |
| [jevwire](https://github.com/Brainwires/jevwire) | Jev decision layer for agents: MCP server, embeddable DecisionModel library, and an escalate-only Claude Code plugin (TypeSafe AI's Jev) | TypeScript | ⭐ 18 |
| [jev-agent-skill-router](https://github.com/GodsBoy/jev-agent-skill-router) | Typed, confidence-aware agent skill routing with TypeSafe Jev. | Python | ⭐ 17 |
| [jevcore](https://github.com/PerryLink/jevcore) | TypeSafe Jev for DeepSeek Harness, the Model Context Protocol, and plain Node: typed judgments instead of prose, offline by default. | TypeScript | ⭐ 17 |
| [JevLoop](https://github.com/zjunlp/JevLoop) | The agent loop where decisions don't cost a large language model call. Zero deps, runs offline, no API key needed. | TypeScript | ⭐ 17 |
| [muse-jev-playbook](https://github.com/Bodila51/muse-jev-playbook) | Jev decision layer for Muse: a fast, cheap TypeSafe AI gate before expensive agent work — confidence policy, recipes, reference router, honest measurement. | Python | ⭐ 16 |
| [jev (BorisLeMeec)](https://github.com/BorisLeMeec/jev) | A claude code plugin for jev | Go | ⭐ 15 |
| [jev-code (FrancoisChastel)](https://github.com/FrancoisChastel/jev-code) | Jev, TypeSafe's System One classifier, as a tool inside Claude Code, Codex, Pi, and OpenCode: typed classify, check, score, rank, and ask, plus one-command setup. | TypeScript | ⭐ 15 |
| [hermes-jev-approvals](https://github.com/anpicasso/hermes-jev-approvals) | PoC: TypeSafe Jev as the reviewer for Hermes Agent smart command approvals. 8.7x faster, 4.4x fewer prompts, measured on 153 real commands. Approvals only. | Python | ⭐ 14 |
| [patdown](https://github.com/tyler-dot-earth/patdown) | typesafe's jev as a "fuzzy linter". give your code an ocular patdown. | TypeScript | ⭐ 14 |
| [pi-jev-router (philippdubach)](https://github.com/philippdubach/pi-jev-router) | A minimal Pareto-optimal OpenRouter model router for pi, based on Jev | TypeScript | ⭐ 14 |
| [pi-jev-router](https://github.com/mejiasd3v/pi-jev-router) | Automatic model routing for Pi using TypeSafe's Jev through Vercel AI Gateway | JavaScript | ⭐ 13 |
| [typesafe-skill-router](https://github.com/DECRUX9812/typesafe-skill-router) | TypeSafe (Jev) skill routing for Hermes Agent: names the one skill worth loading, before the model call. Opt-in, stdlib only, ~$0.001 per routed turn. | Python | ⭐ 13 |
| [claude-jev (0x7067)](https://github.com/0x7067/claude-jev) | Claude Code plugin: Jev for rule checks, verbatim compaction, and prompt routing | Python | ⭐ 12 |
| [jev-router (prismhq)](https://github.com/prismhq/jev-router) | Open-source LLM router that uses TypeSafe's Jev to pick a model, on top of LiteLLM | Python | ⭐ 12 |
| [pi-jev](https://github.com/madeye/pi-jev) | Jev-assisted file retrieval and request caching for faster Pi workflows | TypeScript | ⭐ 12 |
| [jev-commit](https://github.com/valentynkit/jev-commit) | Pre-commit hook: one Jev call judges whether your commit message matches the staged diff, plus debug leftovers, unmentioned work, and a credential check. | Python | ⭐ 11 |
| [JevLint](https://github.com/iamtoomas/JevLint) | Configurable semantic linting powered by Jev, with file-level NOUL judgments and a magic-strings plugin. | TypeScript | ⭐ 11 |
| [pi-fast-jev-compaction](https://github.com/joelhooks/pi-fast-jev-compaction) | Pi extension: verbatim context compaction with TypeSafe Jev decisions | TypeScript | ⭐ 11 |
| [pi-quiet-ask](https://github.com/HyunjunJeon/pi-quiet-ask) | TypeSafe Jev as the pi coding agent's quiet decision layer | TypeScript | ⭐ 11 |
| [clean-code-review](https://github.com/frostney/clean-code-review) · [site](https://clean-code-review.vercel.app) | Every code file in a pull request, judged against Uncle Bob's Clean Code by TypeSafe's Jev, then reviewed by Luna. Built on eve and Next.js. | TypeScript | ⭐ 10 |
| [jev-recipes](https://github.com/agencyenterprise/jev-recipes) | 80+ composable TypeScript recipes powered by Jev for AI agents, retrieval, answer verification, and conversation workflows. | TypeScript | ⭐ 10 |
| [Augustus](https://github.com/24601/Augustus) · [site](https://24601.github.io/Augustus/) | Independent agent skill for finding, building, evaluating, and improving decision-model systems with composition rules, evaluation harnesses, and bounded prompt/program optimization; TypeSafe Jev is the default hosted exemplar. | Python | ⭐ 9 |
| [jevcache (kushals256)](https://github.com/kushals256/jevcache) · [site](https://www.npmjs.com/package/@kushalicious/jevcache) | Skip expensive LLM calls when TypeSafe Jev says same intent. OpenAI-compatible local cache proxy — npx @kushalicious/jevcache | TypeScript | ⭐ 9 |
| [jevymarket](https://github.com/markusbug/jevymarket) | Polymarket trading bot driven by Jev (TypeSafe AI) via OpenRouter | Python | ⭐ 9 |
| [pi-jev-sentinel](https://github.com/harshwasan/jev-sentinel) | Pi coding-agent extension: TypeSafe Jev checks for tool calls, tool outputs and replies (prompt injection, approvals, secret scrubbing, task pinning) | TypeScript | ⭐ 9 |
| [jev-harness (TypeSafeAI)](https://github.com/TypeSafeAI/jev-harness) · [site](https://jev.guru) | A custom coding harness for TypeSafe AI's Jev: an LLM proposes, Jev answers narrow questions, code decides, every step leaves a receipt. | TypeScript | ⭐ 8 |
| [jev-router](https://github.com/rajdhakad9826/jev-router) | Cost-aware LLM router that picks the cheapest model capable of handling a query, using TypeSafe's Jev for fast classification instead of an LLM call. | TypeScript | ⭐ 8 |
| [jevscape](https://github.com/Skyvern-AI/jevscape) | RuneBench harness for TypeSafe's Jev: bounded action catalog, tick-mode controller and a live dashboard | TypeScript | ⭐ 8 |
| [omp-jev-compaction](https://github.com/jerryfane/omp-jev-compaction) | Verbatim Jev-scored context reduction for omp, over TypeSafe or OpenRouter | TypeScript | ⭐ 8 |
| [pi-jev (iefnaf)](https://github.com/iefnaf/pi-jev) | Pi extension suite powered by Jev: selective context compaction and model routing | TypeScript | ⭐ 8 |
| [diffjury](https://github.com/raihankhan-rk/diffjury) | DiffJury — TypeSafe Jev PR risk router + code review coach | TypeScript | ⭐ 7 |
| [Jev Auto Router](https://github.com/miniLV/Jev-Auto-Router) · [site](https://minilv.github.io/2026/08/03/codex-auto-router/) | Per-call GPT model routing for Codex: Jev chooses model and effort, a local Responses proxy keeps the tool loop intact, then independent verification and Router Compass check whether the task still passed. | TypeScript | ⭐ 7 |
| [jev-guard (muratcakmak)](https://github.com/muratcakmak/jev-guard) | Probability-scored guardrails for Claude Code: deny rule-breaking edits and unasked-for deploys, route your docs into each prompt, and check the final answer against the turn's own evidence. | TypeScript | ⭐ 7 |
| [jev-mcp (arunav25)](https://github.com/arunav25/jev-mcp) | Connect JEV to MCP clients and compare its judgments against general-purpose LLMs using shared datasets and measurable accuracy. | JavaScript | ⭐ 7 |
| [jev-mcp (rashedInt32)](https://github.com/rashedInt32/jev-mcp) · [site](https://www.npmjs.com/package/jev-mcp) | MCP server exposing TypeSafe Jev as typed, calibrated judgment tools: classify, score, check, batched ask. Ships as a Claude Code plugin. | TypeScript | ⭐ 7 |
| [jev-pref](https://github.com/doeixd/jev-pref) | Turn your AGENTS.md preferences into a fast, Jev-powered AI linter. | JavaScript | ⭐ 7 |
| [pi-heed](https://github.com/Nyarlathoteppppp/pi-heed) | Runtime constraints for the pi coding agent: checks every side-effecting tool call against what you said, before it runs. Powered by TypeSafe Jev. | TypeScript | ⭐ 7 |
| [bicameral](https://github.com/AbdelStark/bicameral) | Hybrid coding harness: System 2 writes, System 1 (Jev) runs reflexes. | TypeScript | ⭐ 6 |
| [jev-canvas](https://github.com/gaborishka/jev-canvas) | Draw on a tldraw canvas with your voice and a pointing finger. Jev (TypeSafe System One) decides action, target and place in ~350 ms per spoken word. | JavaScript | ⭐ 6 |
| [jev-spec](https://github.com/nozomi-koborinai/jev-spec) · [site](https://www.npmjs.com/package/jev-spec) | ⚡ Catch spec drift on every commit: check your code against your Markdown specs with TypeSafe AI's Jev model. | TypeScript | ⭐ 6 |
| [jevtest (joshhu)](https://github.com/joshhu/jevtest) | 情緒測謊器：嘴上說「好」，心裡真的好嗎？用 TypeSafe Jev（System One 模型）透過 OpenRouter 即時判斷，並與一般 LLM 對照 | HTML | ⭐ 6 |
| [reflex-gate](https://github.com/jagsan-cyber/reflex-gate) | Local Jev / System One–compatible gateway — not TypeSafe’s Jev. Fast, privacy-first, offline. | Go | ⭐ 6 |
| [riff](https://github.com/scale-venture-partners/riff) | A small, fast prose linter: ruff-style rule codes for writing, backed by TypeSafe's Jev model | Python | ⭐ 6 |
| [deepseek-harness-jev-pre-compaction](https://github.com/wjw66/deepseek-harness-jev-pre-compaction) | A pre-compaction advisor for DeepSeek Harness. Runs before the standard `compaction-basic` backend, using TypeSafe JEV to safely prune low-value tool results from model context. Original session events stay in the append-only log; only the model-visible view is replaced with compact markers or archive pointers to reduce context bloat. | TypeScript | ⭐ 5 |
| [dsh-jev](https://github.com/zhangxaochen/dsh-jev) | Jev (System One decision model) plugin suite for DeepSeek Harness (dsh) | TypeScript | ⭐ 5 |
| [dsh-jev-tools](https://github.com/HorusJiang/dsh-jev-tools) · [site](https://www.npmjs.com/package/dsh-jev-tools) | Jev judgment, not generation: prune long tool output, screen fetched pages for injected instructions, and gate completion claims inside DeepSeek Harness. | TypeScript | ⭐ 5 |
| [fast-dev-compaction](https://github.com/leonaaardob/fast-dev-compaction) | Codex plugin: verbatim Jev-guided context restoration around session compaction. Port of tamaratran/fast-jev-compaction to Codex lifecycle hooks. | TypeScript | ⭐ 5 |
| [hermes-jev-plugin](https://github.com/ajensenwaud/hermes-jev-plugin) | TypeSafe Jev (System One) decision tools for Hermes Agent: jev_check / jev_route / jev_score / jev_evaluate | Python | ⭐ 5 |
| [jev-for-all](https://github.com/emirbartu/jev-for-all) | Jev for every agentic development workflow — the System One decision model wired into whatever harness an agent codes in: OpenCode today, Claude Code and Hermes adapters next. | TypeScript | ⭐ 5 |
| [jev-skill-gate](https://github.com/ShivamPansuriya/jev-skill-gate) | Cut Claude Code's skill manifest by ~75% with TypeSafe Jev. Scores every installed skill for relevance and hides the rest via skillOverrides — 12,750 → 3,185 tokens on a 217-skill install, for $0.0009 a session. | JavaScript | ⭐ 5 |
| [jev-usecases](https://github.com/kenhuangus/jev-usecases) | Production TypeSafe Jev (System One) use-case harnesses with confidence-gated decision logic | Python | ⭐ 5 |
| [jevriel](https://github.com/thehan-co/jevriel) | Give your AI JEV wings. A skill and plugin to build with TypeSafe Jev, upgrade LLM-only workflows and measure the result. | JavaScript | ⭐ 5 |
| [nitro](https://github.com/daniel-farina/nitro) | Grok Build with TypeSafe Jev routing tool selection once per turn: 22 to 40% cheaper on the same tasks | Rust | ⭐ 5 |
| [pi-jev-context-curator](https://github.com/Shashank-H/pi-jev-context-curator) | A Jev based context curator for pi | TypeScript | ⭐ 5 |
| [stingray](https://github.com/Nanako0129/stingray) | A Claude Code Stop hook for the turn that ends half-done — nothing done, an announced action never carried out, a promise to watch CI with nothing running — or in the wrong language. Every judgement is made by TypeSafe Jev. | Shell | ⭐ 5 |
| [jcm-router](https://github.com/adarshmishra07/jcm-router) | Local proxy that picks the Claude model and effort per message using TypeSafe Jev. Routes subagents, leaves your cached main chat alone. | TypeScript | ⭐ 4 |
| [jev-codex-bridge](https://github.com/ansidium/jev-codex-bridge) | Model and reasoning routing for Codex Desktop and CLI, with a Windows service and validated updates | JavaScript | ⭐ 4 |
| [jev-cookbook (paramjeetn)](https://github.com/paramjeetn/jev-cookbook) | The complete cookbook for Jev by TypeSafe AI — 120+ use cases, 10 runnable examples, 4 composition patterns, and first-principles theory for the world's first System One AI model. | Python | ⭐ 4 |
| [jev-enforce](https://github.com/erkamyaman/jev-enforce) · [site](https://www.npmjs.com/package/jev-enforce) | 📏 Claude Code plugin that makes Claude follow your CLAUDE.md: every reply and edit checked by TypeSafe Jev ✅ | TypeScript | ⭐ 4 |
| [jev-model-router (satviksinha)](https://github.com/satviksinha/jev-model-router) | Model router for Claude Code using Jev | TypeScript | ⭐ 4 |
| [jevelry](https://github.com/backant-io/jevelry) | Use Jev everywhere to make & track decisions | TypeScript | ⭐ 4 |
| [jevgate](https://github.com/Tech-Byte-Frontier/jevgate) | File-scoped maintainability review with TypeSafe Jev | Rust | ⭐ 4 |
| [pijev](https://github.com/tonyzdev/pijev) | PiJev: a terminal coding agent with Jev in the loop — Jev ranks the repository's files before the first call, picks skills and triages failures; your coding model writes the code. Built on Pi. | TypeScript | ⭐ 4 |
| [prompt2jev](https://github.com/sumleo/prompt2jev) | Agent skill and CLI that turn natural language, an LLM prompt, or the code that runs one into a TypeSafe Jev decision: typed state, Choice/Score/Noul questions, and a runnable script | Python | ⭐ 4 |
| [slidepilot](https://github.com/harshil1712/slidepilot) | Voice-driven semantic auto-advance for Slidev, powered by Cloudflare Agents and TypeSafe AI Jev | TypeScript | ⭐ 4 |
| [taste-lint](https://github.com/mblode/taste-lint) · [site](https://taste-lint.blode.md) | CLI that uses Jev to catch AI slop in UI, copy, and agent instructions before ship (probabilities on semantic taste checks). | TypeScript | ⭐ 4 |
| [tink-route](https://github.com/jon-devlapaz/tink-route) | Dynamic, confidence-aware Agent Skill routing with TypeSafe Jev and Tink | Python | ⭐ 4 |
| [windows-save-token-jev-setup](https://github.com/455-dIAO/windows-save-token-jev-setup) | Windows Codex Skill：通过 npx 或 Git 安装，安全配置 save-token-jev 的 PreCompact/SessionStart Hooks，并提供信任、原生压缩与旧内容隔离验证。 | PowerShell | ⭐ 4 |
| [construct-auto-classifier](https://github.com/godspede/construct-auto-classifier) · [site](https://famelos.com/jev/auto-classifier-certification/) | Effect-based safety gate for AI coding agents' shell commands (OpenCode, Antigravity): fast structural rules, then TypeSafe's Jev or a chat model judges what a command does. Certified with Jev at zero dangerous commands allowed. | TypeScript | ⭐ 3 |
| [dsh-jev-prune](https://github.com/yangyu666/dsh-jev-prune) | Jev-judged context compaction for DeepSeek Harness: semantic tool-result pruning + deterministic receipt compaction | JavaScript | ⭐ 3 |
| [jev-assist](https://github.com/glud123/jev-assist) | Don't burn your expensive main model on grep-and-guess grunt work — let jev rank the whole repo, and save the main model for reading the right files and writing the right code. | JavaScript | ⭐ 3 |
| [jev-claw](https://github.com/trietphan/jev-claw) | Typed model routing for OpenClaw agents, powered by TypeSafe Jev | JavaScript | ⭐ 3 |
| [jev-codex-pilot](https://github.com/Charlyhno-eng/jev-codex-pilot) | A Codex overlay incorporating JEV to make the best decisions regarding model selection and depth of reasoning. All while automating the process via an automated Kanban system. | TypeScript | ⭐ 3 |
| [jev-judgment](https://github.com/HyunjunJeon/jev-judgment) | Agent Skill: send closed coding-agent judgments to TypeSafe Jev | Python | ⭐ 3 |
| [jev-mailroom](https://github.com/selcukusta/jev-mailroom) | Email triage PoC: reads a mailbox over IMAP and classifies each message by what it is and what it's about, using TypeSafe System One (Jev) — 11 questions in a single call, decided in Python. | Python | ⭐ 3 |
| [jev-pilot](https://github.com/h0j5bz0adh0-stack/jev-pilot) | Fast System-1 Decision, Arbitration & Safety Engine for Autonomous AI Agents (Powered by TypeSafe Jev) | Python | ⭐ 3 |
| [jev-predict-skill](https://github.com/DanielKillenberger/jev-predict-skill) | Predict another skill's next closed decision with TypeSafe Jev — without running that skill. | HTML | ⭐ 3 |
| [jev-shield](https://github.com/caiovicentino/jev-shield) | Semantic MCP firewall powered by Jev — screens every tool call, tool result, and tool description with calibrated System One verification. 94% block recall, 0 false positives, ~$0.00002/check. | JavaScript | ⭐ 3 |
| [jev-smart-router](https://github.com/rmosleydb/jev-smart-router) | JEV Smart Router — a Databricks App that uses TypeSafe JEV to pick which model answers each message, then runs inference on the chosen Databricks Foundation Model API endpoint. | Python | ⭐ 3 |
| [jev-triage (boldbug1)](https://github.com/boldbug1/jev-triage) | Message triage CLI in Go, built on the Jev decision model from TypeSafe AI. Categorizes messages, scores urgency, and flags low-confidence ones for human review. | Go | ⭐ 3 |
| [jevex](https://github.com/jvsteiner/jevex) | Minimal agent loop where Jev directs control flow and a LangChain chat model writes argument values and the final response. | Python | ⭐ 3 |
| [jevkit](https://github.com/ariel-frischer/jevkit) | Fast Rust CLI for TypeSafe Jev: typed decisions, offline linting before you pay | Rust | ⭐ 3 |
| [jevsume](https://github.com/unownone/jevsume) | ATS-friendly resume review powered by Jev (TypeSafe System One). The frontend extracts resume text the way a parser would, then a Cloudflare Worker runs typed JEV questions and composes a JevScore. | TypeScript | ⭐ 3 |
| [limpet](https://github.com/noplan-inc/limpet) | A Stop hook that stops your coding agent from stopping too early. Plain-language rules, judged by jev. | Python | ⭐ 3 |
| [mastra-jev-moderation](https://github.com/CodeAlive-AI/mastra-jev-moderation) | Input moderation for Mastra agents on TypeSafe Jev — one file | TypeScript | ⭐ 3 |
| [pi-jev-compaction](https://github.com/nourhelmi/pi-jev-compaction) | Automatic Jev context clearing for Pi. Keep the conversation, prune stale tool output, retrieve originals without rerunning commands. | TypeScript | ⭐ 3 |
| [pi-thinking-router-jev](https://github.com/Wh0rigin/pi-thinking-router-jev) | pi-thinking-router-jev —— pi 的自适应 Thinking Level Router。在任务起点、推理型失败与稳定窗口咨询 jev 决策模型（未配置时本地 规则兜底），动态选择 low/medium/high/xhigh 推理档位：简单改动降档、复杂 debug 升级、失败可升级、稳定可降级。含防抖钳制 、失败安全回退与 JSONL 决策日志，不切换模型、零侵入 agent loop。 | TypeScript | ⭐ 3 |
| [pi-typesafe-jev](https://github.com/legacybridge-tech/pi-typesafe-jev) | A pi extension that exposes TypeSafe (Jev, System One) judgments as five pi tools, so a model can make narrow semantic judgments while your code and your users keep control of thresholds, weights, and actions. | TypeScript | ⭐ 3 |
| [reflex (kaustav1996)](https://github.com/kaustav1996/reflex) | A coding agent and personal assistant with System One reflexes (TypeSafe Jev) on top of the Pi coding agent | TypeScript | ⭐ 3 |
| [tiershift](https://github.com/iamvatsalpatel/tiershift) | Shift every LLM call to the cheapest model that can handle it. Routing decided by TypeSafe Jev in ~180 ms. No training data. Policy in plain YAML. TypeScript and Python. | TypeScript | ⭐ 3 |
| [todo-jev](https://github.com/maker-KK/todo-jev) | ⚡ Ultra-fast, low-cost intelligent task classifier and 3-tier routing engine powered by TypeSafe Jev (System One) | Python | ⭐ 3 |
| [typesafe-cli (geilt)](https://github.com/geilt/typesafe-cli) | CLI and agent skill for TypeSafe System One (Jev): typed Choice, Score, and Noul judgments. | Python | ⭐ 3 |
| [typesafe-mod](https://github.com/BeLazy167/typesafe-mod) | Claude Code mod that routes decisions to TypeSafe's Jev model: ranks installed skills per prompt, and answers the agent's own this-or-that questions when confident. | TypeScript | ⭐ 3 |
| [actiongate-jev](https://github.com/omkarghugarkar007/actiongate-jev) | Runtime authorization and guardrails for AI-agent tool calls with deterministic policy and TypeSafe Jev via OpenRouter. | TypeScript | ⭐ 2 |
| [ailerix](https://github.com/tylerjharden/ailerix) · [site](https://ailerix.vercel.app) | Type-safe model router. Jev (System One) banks each request to a typed catalog route. | TypeScript | ⭐ 2 |
| [auto-mode-for-paseo](https://github.com/obetomuniz/auto-mode-for-paseo) | A Paseo provider that uses TypeSafe Jev to route each Codex turn. | TypeScript | ⭐ 2 |
| [claude-jev-plugin](https://github.com/dr-dimitru/claude-jev-plugin) | TypeSafe Jev semantic guardrails for Claude Code | TypeScript | ⭐ 2 |
| [clear-head](https://github.com/VladyslavHontar/clear-head) | Claude Code Stop hook that checks an AI assistant's claims against what it actually read this session, using TypeSafe's Jev as the judge | Python | ⭐ 2 |
| [decisions-judge-mcp](https://github.com/clouatre-labs/decisions-judge-mcp) | Typed decisions for AI agents as an MCP tool: yes/no probability (noul), choice, and score in one fast request. Backed by the TypeSafe System One model. | JavaScript | ⭐ 2 |
| [dgui-hypermem](https://github.com/ctaxnagomi/dgui-hypermem) · [site](https://huggingface.co/datasets/ctaxnagomi/DGUI_HYPERMEM-JEV) | DGUI-HyperMem (DeckerGUI HyperMemory) - self-hosted hybrid memory MCP server on Cloudflare Workers with a JEV (Choice/Noul/Score) reasoning layer and a HuggingFace training-brain flywheel. | TypeScript | ⭐ 2 |
| [dsh-completion-supervisor](https://github.com/LXBWOW/dsh-completion-supervisor) | Checks whether a coding agent completion claim is actually true: deterministic evidence gathered in code, one batched Jev assessment, and a pure policy. DSH plugin. | JavaScript | ⭐ 2 |
| [dsh-context-curator](https://github.com/LXBWOW/dsh-context-curator) | DSH-native context compaction that keeps text verbatim: scores every tool call and result with Jev, drops only the stale ones, and falls back to DSH native summary when unsure. | JavaScript | ⭐ 2 |
| [dsh-jev-adapter](https://github.com/BetterZflyee/dsh-jev-adapter) | Use the Jev (System One) decision-model paradigm with any OpenAI-compatible LLM — no TypeSafe key required. A jev_decide tool for DeepSeek Harness (dsh). | JavaScript | ⭐ 2 |
| [dsh-plugin-jev-effort-selector](https://github.com/justhalfbit/dsh-plugin-jev-effort-selector) | DeepSeek Harness (DSH) 推理等级自动选择插件：由 Jev System One 模型判断每条消息值多少思考量，按模型声明的等级自动推导档位，上下文信封让「继续」这类追问继承话题深度，低置信度向上取，任何失败都静默沿用原等级。 \| Jev-driven reasoning effort per message: per-model ladders derived from what each model advertises, a fixed-size context envelope so follow-ups inherit topic depth, ties break upward, silent fallback on every failure path. | JavaScript | ⭐ 2 |
| [dsh-teacher-consult](https://github.com/LXBWOW/dsh-teacher-consult) | GPT teacher consults for DSH: stateless one-shot codex teachers behind a hard per-task consult budget, a read-only sandbox and a deterministic prefilter. | JavaScript | ⭐ 2 |
| [git-jev-stage](https://github.com/ibrahemid/git-jev-stage) | Select Git changes for staging with a plain-language description. | TypeScript | ⭐ 2 |
| [Jev_steer_or_queue](https://github.com/Larkspur-Wang/Jev_steer_or_queue) | Let TypeSafe Jev decide whether a message you send mid-turn should steer, queue, or interrupt your coding agent. Claude Code plugin; Codex CLI in testing. | Python | ⭐ 2 |
| [jev-agent-hooks](https://github.com/onlyjq04/jev-agent-hooks) | TypeSafe Jev hooks for Claude Code, Codex and pi: per-turn skill suggestion and subagent model routing | JavaScript | ⭐ 2 |
| [jev-architect (BenjaminPolge)](https://github.com/BenjaminPolge/jev-architect) | Makes Claude Code and Codex ask whether a step needs a generative LLM at all — or whether it belongs on Jev, TypeSafe's System One model. Architecture arbitrage before the code is written. |  | ⭐ 2 |
| [jev-builder-loop](https://github.com/rainbowpuffpuff/jev-builder-loop) | Grok skill: Jev as a judgment sensor in a builder-agent loop (priors × probabilities → next act) | Python | ⭐ 2 |
| [Jev-chooses-a-LLM](https://github.com/Bodila51/Jev-chooses-a-LLM) | Jev Router for Cursor - TypeSafe Jev picks COST/BALANCED/INTELLIGENCE, Cursor executes | TypeScript | ⭐ 2 |
| [jev-claude-code](https://github.com/DarioFontanel/jev-claude-code) | Prompt Claude Code: tre sistemi costruiti su Jev di TypeSafe — routing del modello, compattazione del contesto e code review |  | ⭐ 2 |
| [jev-codex-router-skill](https://github.com/455-dIAO/jev-codex-router-skill) | Portable Codex Skill for Jev model and reasoning-effort routing, with safe installation and Chinese usage guides | Python | ⭐ 2 |
| [jev-decisions](https://github.com/bojansandhaus/jev-decisions) · [site](https://openrouter.ai/typesafe/jev-1.13) | Safety checks for Hermes and other AI agents before they act, ask for approval, or verify a change. | Python | ⭐ 2 |
| [jev-dingtalk](https://github.com/ikashana/jev-dingtalk) | 钉钉信息 Jev 分拣器（jev-dingtalk）：把钉钉邮件与聊天分拣成 Now / Today / Queue / Ignore 清单——谁在等回复、谁需要人看一眼。dws 取数、Jev 分类、报告本地渲染，可直接作为 Agent 技能使用。\| DingTalk mail & chat triage with Jev. | Python | ⭐ 2 |
| [jev-engineering](https://github.com/eugeniughelbur/jev-engineering) · [site](https://eugeniughelbur.github.io/jev-engineering/) | Decision layer for coding agents: deterministic rules before any model call, then one Jev request, as a Claude Code PreToolUse hook, an MCP server, a loopback service and a team policy that personal overrides can tighten but not loosen. Ships the 300-call injection kit behind its own numbers. | Python | ⭐ 2 |
| [jev-git](https://github.com/AkashPriyadarshii/jev-git) · [site](https://typesafe.ai) | Sub-second Git pre-commit & pre-push semantic reflex gate powered by TypeSafe AI Jev | Rust | ⭐ 2 |
| [jev-layer](https://github.com/typakon4/jev-layer) · [site](https://www.npmjs.com/package/jev-layer) | Portable System-1 decision layer for agent harnesses with host-owned routing, receipts, replay, and fail-open integrations. | JavaScript | ⭐ 2 |
| [jev-mcp](https://github.com/rajasekharponakala/jev-mcp) · [site](https://docs.typesafe.ai/) | MCP server wrapping TypeSafe's Jev System One models — typed noul/choice/score judgments for AI agents | Python | ⭐ 2 |
| [jev-mcp (freepik-company)](https://github.com/freepik-company/jev-mcp) | MCP server for typed decisions with Jev / System One via OpenRouter or TypeSafe | Go | ⭐ 2 |
| [jev-mcp (Songokou1983)](https://github.com/Songokou1983/jev-mcp) | Local MCP server exposing TypeSafe Jev (System One decision model) as native Claude Code / Codex tools | Python | ⭐ 2 |
| [jev-model-router](https://github.com/az9713/jev-model-router) · [site](https://az9713.github.io/jev-model-router/) | Jev (TypeSafe) model router on the Vercel AI Gateway | JavaScript | ⭐ 2 |
| [jev-model-router (lucianfialho)](https://github.com/lucianfialho/jev-model-router) | Cost-optimized OpenRouter model router using TypeSafe's Jev, with a live full-catalog scorer instead of a hardcoded model list | Python | ⭐ 2 |
| [jev-router (AABBAASS1)](https://github.com/AABBAASS1/jev-router) | Route any task to the right AI agent in under 1 second using Jev (TypeSafe System One). Supports Claude, ChatGPT, Cursor, and Antigravity with auto-launch on macOS, Windows, and Linux. | Python | ⭐ 2 |
| [jev-router.nvim](https://github.com/Mawfyy/jev-router.nvim) | An intent router for Neovim that classifies AI commands with Jev (TypeSafe's System One model) via the OpenRouter Decisions API, then routes execution to the matching handler. | Lua | ⭐ 2 |
| [jev-rust-review](https://github.com/kindintelligence/jev-rust-review) | Rust-aware code review for Claude Code and coding agents, powered by TypeSafe Jev | Rust | ⭐ 2 |
| [jev-scout](https://github.com/AkashPriyadarshii/jev-scout) · [site](https://akashpriyadarshii.github.io/jev-scout/) | Zero-hallucination open-source repo and crate scout powered by TypeSafe AI Jev System One scoring | Rust | ⭐ 2 |
| [jev-skill-selection](https://github.com/redreamality/jev-skill-selection) | Pre-message hook: use TypeSafe Jev to keep/drop skills and shrink agent context | Python | ⭐ 2 |
| [jev-skillful](https://github.com/bestagentkits/jev-skillful) | Per-prompt capability router for coding agents: resolves installed skills, MCP servers, agents and commands against your prompt via TypeSafe Jev, and measures whether the injection actually helps. | TypeScript | ⭐ 2 |
| [jev-skills](https://github.com/eran-broder/jev-skills) | Skills without the context tax. Claude Code and Codex plugin: TypeSafe's Jev decides on every turn which skills the model sees. Always-on context cost: 0 tokens. | TypeScript | ⭐ 2 |
| [jev-system-architect](https://github.com/samtay32/jev-system-architect) | System-architecture skill for TypeSafe AI Jev/System One — find fuzzy semantic judgment and turn it into small Choice/Score/Noul primitives. |  | ⭐ 2 |
| [jev-workbench](https://github.com/molis-ai/jev-workbench) | Build versioned judgment functions on TypeSafe's Jev once, then call the same published version from your backend over HTTP and from coding agents over MCP. The vendor key stays on your machine. | TypeScript | ⭐ 2 |
| [jevmem](https://github.com/Avinash-jetwani/jevmem) · [site](https://www.npmjs.com/package/jevmem) | Jev decides. The LLM writes one line. Your project never forgets. Jev-powered memory layer for AI coding tools. | TypeScript | ⭐ 2 |
| [JevPromptCoach](https://github.com/CrowdLinker/JevPromptCoach) | Claude Code plugin that scores how well you prompt a coding agent, and shows whether your habits are improving. Runs on TypeSafe's Jev model. Zero added latency. | TypeScript | ⭐ 2 |
| [jevprune](https://github.com/ibrahemid/jevprune) | Filter command output for coding agents using a task description. | TypeScript | ⭐ 2 |
| [opencode-context-pruner](https://github.com/hoshinodis/opencode-context-pruner) | Continuous verbatim context pruning for OpenCode, powered by TypeSafe Jev. Port of fast-jev-compaction adapted to OpenCode's context hook. | TypeScript | ⭐ 2 |
| [pi-fast-jev-compaction (KamilPostrozny)](https://github.com/KamilPostrozny/pi-fast-jev-compaction) | Fast JEV compaction extension for pi | TypeScript | ⭐ 2 |
| [pi-jev-context](https://github.com/kevinpita/pi-jev-context) | Reversible context pruning for Pi, powered by TypeSafe Jev. Keep useful context without deleting session history. | TypeScript | ⭐ 2 |
| [routeKit](https://github.com/rajdhakad9826/routeKit) | Agent-native LLM model router built with JEV by TypeSafe.ai. Dynamically selects the most suitable model based on task complexity, reasoning requirements, and tool usage. | TypeScript | ⭐ 2 |
| [skill-router](https://github.com/lomeshdutta/skill-router) | Tell Claude Code which installed skill a session needs, using Jev (TypeSafe AI) for the decision and skills.sh for discovery. | Python | ⭐ 2 |
| [skillfeed](https://github.com/iikareem/skillfeed) · [site](https://skillfeed-xi.vercel.app) | A tech reading feed ranked to your skills — powered by TypeSafe Jev | TypeScript | ⭐ 2 |
| [typesafe-as-a-judge](https://github.com/E-FL/typesafe-as-a-judge) | Unofficial community MCP plugin for Codex and Claude Code using TypeSafe Jev for bounded routing, ranking, extraction, verification, and escalation | JavaScript | ⭐ 2 |
| [typesafe-migration-guard](https://github.com/opaielsheikh/typesafe-migration-guard) | Automated database migration safety reviewer powered by TypeSafe AI (Jev System One model) | TypeScript | ⭐ 2 |
| [wellposed](https://github.com/suraj-phanindra/wellposed) · [site](https://www.npmjs.com/package/wellposed) | Lints Jev requests before they are sent: offline checks for missing none-of-the-above options and broken state paths, then Jev itself for what structure cannot decide. | JavaScript | ⭐ 2 |
| [Antigravity-mcp-semantic-search-with-TypeSafeAi](https://github.com/greenyamao/Antigravity-mcp-semantic-search-with-TypeSafeAi) | Fast semantic code search & diff sanity auditor for AI coding assistants (Antigravity, Cursor, Claude Code) powered by TypeSafe System One. | Python | ⭐ 1 |
| [ask-jev](https://github.com/omni-/ask-jev) | Utilizing Jev, the RLCD-type model provided by TypeSafe AI, to independently and cheaply judge agentic coding sessions. | PowerShell | ⭐ 1 |
| [athena-jev](https://github.com/MartinesEmanuel/athena-jev) · [site](https://athena-jev.vercel.app/) | ATHENA gives coding agents reflexes - an open-source cognitive control layer powered by TypeSafe Jev. | TypeScript | ⭐ 1 |
| [codex-jev-preflight](https://github.com/wellkilo/codex-jev-preflight) · [site](https://wellkilo.github.io/codex-jev-preflight/) | Fail-open Codex UserPromptSubmit hook that injects TypeSafe Jev pre-task routing metadata. | Python | ⭐ 1 |
| [gojev](https://github.com/taigrr/gojev) | Go harness for Jev/Kev decision models: TypeSafe, Vercel AI Gateway, and in-process Kev via llama.cpp | Go | ⭐ 1 |
| [hermes-jev-router](https://github.com/ussyverse/hermes-jev-router) | Experimental Hermes plugin: Jev-assisted model routing plans with budget and capability constraints. API access pending. | Python | ⭐ 1 |
| [instruct-jev](https://github.com/ctaxnagomi/instruct-jev) · [site](https://huggingface.co/datasets/ctaxnagomi/INSTRUCT_JEV) | INSTRUCT_JEV - TypeSafe AI Jev / System One instruction corpus (choice/noul/score), compiled by DeckerGUI. 119 rows. Mirrored on HuggingFace. | Python | ⭐ 1 |
| [jev-firewall](https://github.com/Koushik890/jev-firewall) · [site](https://www.npmjs.com/package/jev-firewall) | Real-time firewall for AI coding agents: a PreToolUse hook checks every Claude Code / Codex tool call with deterministic shell-aware rules, and unmatched actions go to Jev for a calibrated allow/ask/block that fails closed. | TypeScript | ⭐ 1 |
| [jev-mcp (benballintyn)](https://github.com/benballintyn/jev-mcp) | MCP server giving coding agents typed, calibrated judgments from TypeSafe's Jev model |  | ⭐ 1 |
| [jev-model-router (Mandrilsquad1441)](https://github.com/Mandrilsquad1441/jev-model-router) | Pick the best AI model and reasoning effort for any task in ~1s. Plugin for Claude Code, Claude Desktop and Codex, powered by TypeSafe's Jev decision model and live OpenRouter pricing. Balance intelligence, speed and cost, or choose your priority. | TypeScript | ⭐ 1 |
| [jev-organize](https://github.com/nexibeo/jev-organize) · [site](https://nexibeo.com) | Throw in a pile of company files and get them classified and organized by department, type, sensitivity, date, counterparty and PII, with an index for AI agents. Powered by TypeSafe's Jev on OpenRouter (17¢ per 1,000 files). Zero-dependency Node CLI + Claude skill + Codex agent. | JavaScript | ⭐ 1 |
| [jev-routing](https://github.com/nekowasabi/jev-routing) | Go Jev harness for Claude Code, Codex, and Grok Build. No npx. Not an MCP server. | Go | ⭐ 1 |
| [jev-subtitle-translator](https://github.com/GeekLinkDev/jev-subtitle-translator) · [site](https://geeklink.dev/subtitle-translator/) | Translate SRT subtitles with structured LLM output and check every translation with Jev. | Python | ⭐ 1 |
| [jev-triage](https://github.com/cephalization/jev-triage) | Uses typeful jev, zero sync to pull and sync large repositories for issue triage | TypeScript | ⭐ 1 |
| [jev-wrapped](https://github.com/gaborishka/jev-wrapped) · [site](https://wrapped.ivanhabor.com) | Telegram channel X-ray: Jev judges a year of posts, you get a card. One Cloudflare Worker. | JavaScript | ⭐ 1 |
| [jevgrep](https://github.com/allebee/jevgrep) · [site](https://pypi.org/project/jevgrep-cli/) | grep by meaning: pipe in any text, ask a yes/no question in plain English, get only the matching lines. Works behind tail -f, about $0.004 per 1,000 lines, powered by TypeSafe's Jev. | Python | ⭐ 1 |
| [jevskill](https://github.com/lazniak/jevskill) | Teach your coding agent to stop burning context. Jev (System One) via OpenRouter or TypeSafe: 325ms, 0.000013 USD per decision. A/B tested 99.3% fewer input tokens with accuracy up. Ships a reversible reduce and a ledger that learns when Jev pays off. | Python | ⭐ 1 |
| [jevXagent](https://github.com/j1s4nn/jevXagent) | When Jev meets LLM — Transparent proxy that makes AI coding agents 3× faster and 80% cheaper. Cut response times from 2.4s to 890ms with Line J architecture. | Python | ⭐ 1 |
| [magic-jev](https://github.com/acharyaanusha/magic-jev) | A Magic 8 Ball for pull requests: click the ball and it answers "should I approve this?" with one of the 20 classic phrases, chosen by Jev from the PR's real signals in about 200 ms. | TypeScript | ⭐ 1 |
| [omp-typesafe](https://github.com/siddicky/omp-typesafe) | TypeSafe AI (Jev) adversarial reviewer and typesafe_ask tool for the omp coding agent | TypeScript | ⭐ 1 |
| [stepwarden](https://github.com/getexcited/stepwarden) | Every tool call your agent makes, checked before it runs. A Claude Code plugin that uses TypeSafe AI's Jev to verify each pending tool call against the session plan, then allows it, asks you, or blocks it. Proof of concept | TypeScript | ⭐ 1 |
| [agent-gate-loop](https://github.com/Ripwords/agent-gate-loop) | Reusable GitHub Action: agent fix loop gated by checks, an AI reviewer, and TypeSafe Jev | TypeScript | ⭐ 0 |
| [agent-handoff-gate](https://github.com/zsoXi/agent-handoff-gate) | Experimental protocol for evidence-aware agent handoffs, with Jev-assisted review before results reach the lead agent. | Python | ⭐ 0 |
| [check-risk](https://github.com/moezubair/check-risk) | A CLI and GitHub Action that assesses code-change risk using deterministic rules and TypeSafe Jev, recommending checks and reviewers before merge. | TypeScript | ⭐ 0 |
| [codex-jev-router](https://github.com/suenot/codex-jev-router) | Use Jev Choice and Noul decisions to select Codex subagent model and reasoning tiers, with local compatible backends and a Sol fallback. | JavaScript | ⭐ 0 |
| [DGP (Decision Graph Protocol)](https://github.com/numerous-com/dgp) · [site](https://numerous.com) | Experimental decision protocol whose Jev adapter evaluates framed evidence with typed choices, while application code validates permissions and commits simulated demo actions. | Python | ⭐ 0 |
| [frost](https://github.com/marcus/frost) · [site](https://haplab.com) | A flexible and configurable CLI model router using TypeSafe Jev. | Go | ⭐ 0 |
| [jev-gates](https://github.com/rashedInt32/jev-gates) | Six hook gates for Claude Code that catch broken rules, out-of-scope edits, unfinished asks, and false claims, each judged by Jev against a fixed checklist and one piece of evidence. | JavaScript | ⭐ 0 |
| [jev-judge](https://github.com/ohmyjiro/jev-judge) | Dependency-free CLI and Codex skill that send local state to Jev for batched typed judgments and return answers without echoing the state. | Python | ⭐ 0 |
| [jev-review (thiago-ss)](https://github.com/thiago-ss/jev-review) | Autonomous Jev pull-request review with typed decisions, calibrated approval gates, and trusted-owner escalation | Python | ⭐ 0 |
| [Jevonian](https://github.com/xinyao27/jevonian) · [site](https://www.npmjs.com/package/jevonian) | Local OpenAI-compatible proxy that sits between a coding agent and its providers and asks Jev, per turn, which routed model and thinking level should serve it. | TypeScript | ⭐ 0 |
| [jevr](https://github.com/romeromarcelo/jev-retrieval) · [site](https://crates.io/crates/jevr) | Semantic code and document search CLI for coding agents: a stateless BM25 pass recalls candidate files, Jev Nouls verify each one window-by-window against the query, and one listwise Choice reranks the survivors into grep-style path:line output with calibrated relevance scores. | Rust | ⭐ 0 |
| [omp-jevens-classifier](https://github.com/STRML/omp-jevens-classifier) | Jev-powered model-judged permission gate for OMP (TypeSafe System One) | TypeScript | ⭐ 0 |
| [pi-agent-foreman](https://github.com/alexshpunt/pi-agent-foreman) · [site](https://pi.dev/packages/pi-agent-foreman) | Send Pi agents back to work when they stop before the job is done. | TypeScript | ⭐ 0 |
| [pi-jev-code](https://github.com/KamilPostrozny/pi-jev-code) | Single-agent Pi coding coprocessor with Jev semantic gates, baseline-to-current diff review, and append-only observability telemetry. | TypeScript | ⭐ 0 |
| [pi-typesafe](https://github.com/twilwa/pi-typesafe) | Pi coding-agent extension built on the TypeSafe AI System One API (Jev) | TypeScript | ⭐ 0 |
| [switchboard](https://github.com/aniruddh-krovvidi/switchboard) | Guardrail + model router for LLM gateways on TypeSafe's Jev (System One model), with an independent accuracy/calibration/latency evaluation. Stdlib Python. | Python | ⭐ 0 |
| [Switchboard (ruban-24)](https://github.com/ruban-24/switchboard) | Routes Claude Code and Codex conversations by using Jev to assess a new task, applying local confidence rules to select a model and reasoning effort, and pinning that route through follow-ups, tool calls, and resume to avoid unnecessary prompt-cache disruption. | TypeScript | ⭐ 0 |
| [typesafe-demo-mcp](https://github.com/bestagentkits/typesafe-demo-mcp) | MCP server exposing TypeSafe System One judgments (noul, choice, score) as agent tools | TypeScript | ⭐ 0 |
| [typesafeai-review](https://github.com/rbalch/typesafeai-review) | Using Typesafe.AI to generate diff reviews. | Python | ⭐ 0 |
| [yardsort](https://github.com/joaoh82/yardsort) · [site](https://yardsort.sh) | Desktop app that runs terminal coding agents in parallel git worktrees, with Jev judging each changed file against what the workspace was asked to do. | Rust | ⭐ 0 |
| [zcode-jev](https://github.com/Zahrannnn/zcode-jev) | Typed judgment layer for coding agents — gates from PRD to ship. Jev-ready, provider-agnostic. | TypeScript | ⭐ 0 |

## Browser & computer use

Browser, desktop, and mobile automation with Jev choosing the action.

| Project | Description | Language | Stars |
| --- | --- | --- | ---: |
| [Jev Ultrafast](https://github.com/browser-use/jev-ultrafast) · [site](https://browser-use.com) | A browser agent that turns a single goal into a sequence of lightning-fast actions. | Python | ⭐ 19.5k |
| [jev-chat-jarvis](https://github.com/jev-chat/jev-chat-jarvis) | 装在手机上的对话副驾：在微信 / QQ / X / 飞书里读懂对方、给出候选回复、一键填入输入框，发不发由你。非侵入，只读屏幕，不 hook 不改包。 | Kotlin | ⭐ 5.6k |
| [typesafe-computer-use](https://github.com/awlevin/typesafe-computer-use) | Computer use for about $0.0002 a step: OCR the screen, classify the next action with TypeSafe, click. macOS. | Python | ⭐ 937 |
| [hermes-jev-skills](https://github.com/kerpopule/hermes-jev-skills) | Jev-powered model routing, memory, compaction, skill selection, computer and browser use for Hermes agents (also Claude Code and Codex) | Python | ⭐ 726 |
| [jev-browser-use](https://github.com/wy-coliney/jev-browser-use) | 5–10x faster browser operations: Jev clicks, Codex thinks and verifies. Built at EZCollegeApp. | JavaScript | ⭐ 453 |
| [Mobile Jev](https://github.com/droidrun/mobile-jev) | An Android agent powered by Jev decisions, with a live studio to watch every step. | JavaScript | ⭐ 380 |
| [jev-chat-jarvis-mac](https://github.com/jev-chat/jev-chat-jarvis-mac) | 微信消息意图识别悬浮窗（macOS）：看屏 + 本地小模型判断意图和风险，再按话术生成回复候选。纯只读、不注入微信。 | Python | ⭐ 346 |
| [jev-voice-browser](https://github.com/moritzkremb/jev-voice-browser) | Control a real browser by voice. Jev (TypeSafe System One) decides intent + target in ~300 ms per spoken word; Playwright acts — often before you finish the sentence. | JavaScript | ⭐ 271 |
| [jev-browser](https://github.com/jkudish/jev-browser) | Browser use using Typesafe's Jev model | JavaScript | ⭐ 257 |
| [unclutter](https://github.com/kitze/unclutter) | WXT browser extension: Jev-powered page clutter removal with reusable template rules. | TypeScript | ⭐ 227 |
| [jev-browser (openqa-cn)](https://github.com/openqa-cn/jev-browser) | Jev Browser — indexed browser automation. Jev chooses the control, Playwright acts. A CodexQA skill. | TypeScript | ⭐ 103 |
| [jev-browser (Ying-Kai-Liao)](https://github.com/Ying-Kai-Liao/jev-browser) | Browser automation where an LLM plans and Jev (Typesafe System One) decides. Library, CLI and MCP server. | JavaScript | ⭐ 82 |
| [typesafe-adblock](https://github.com/realZachi/typesafe-adblock) | 🧹 Fun project: a Chrome extension that asks a tiny AI decision model (TypeSafe Jev) "is this DOM element an ad?" and pops it off the page. BYOK, no backend, not a real ad blocker. | JavaScript | ⭐ 74 |
| [JevIntent](https://github.com/Nisaka520/JevIntent) | 微信（FkWeChat 插件）：长按消息分析意图 / 情绪 / 回复姿态，只在本机弹提示，对方无感知 | Java | ⭐ 54 |
| [Jev Social](https://github.com/socai-io/jev-social) · [site](https://socai-io.github.io/jev-social/) | Local Instagram, TikTok, and LinkedIn research where Jev chooses bounded socai browser operations and streams captured evidence into cited reports. | JavaScript | ⭐ 53 |
| [vibecheck](https://github.com/RafalWilinski/vibecheck) | Chrome extension: vibe-check your X posts with TypeSafe's Jev before you hit Post | JavaScript | ⭐ 47 |
| [Jevbridge](https://github.com/tacticocc/Jevbridge) | ACP and MCP adapter that bridges TypeSafe Jev with any LLM — computer use and typed decisions alongside Codex, Claude, Grok, and OpenCode. | TypeScript | ⭐ 41 |
| [jev-cua](https://github.com/ronadin2002/jev-cua) | Voice and text control for macOS. One floating bar, live UI action selection with Jev, and a continuous observe–act–verify loop. | Swift | ⭐ 34 |
| [jev-reviewer](https://github.com/choxos/jev-reviewer) · [site](https://jevreviewer.xera.ac) | Data extraction for systematic reviews, quoted from the papers. Ask a trial report and its supplements your extraction form or a RoB 2, ROBINS-I, QUADAS-2 or TIDieR template; Jev points at the lines, every answer is a verbatim quote with its page, you check it and export the table. Files stay in your browser. | JavaScript | ⭐ 33 |
| [jev-browser (vlad-terin)](https://github.com/vlad-terin/jev-browser) | Jev-powered element selection for your agent’s existing computer-use tools | JavaScript | ⭐ 31 |
| [jev-kit](https://github.com/jonathanavis96/jev-kit) | Everything you need to run TypeSafe's Jev with Claude Code: a tool-call guard, tier guard, file search, browser agent, review, belay, compaction and installers. | Python | ⭐ 25 |
| [jev-cookbook](https://github.com/nexibeo/jev-cookbook) · [site](https://nexibeo.com) | Practical, tested recipes for TypeSafe's Jev decision model on OpenRouter: support triage, database indexing, file organizing, tagging, taxonomies, dedupe, PII detection, extraction, search re-ranking and a browser agent. | JavaScript | ⭐ 22 |
| [jev-for-chrome](https://github.com/chy4pro/jev-for-chrome) | Jev for Chrome: drives the tab you are looking at with TypeSafe Jev, a sub-second decision model. Community port of browser-use/jev-ultrafast, not affiliated with TypeSafe. | TypeScript | ⭐ 21 |
| [jot](https://github.com/runta-dev/jot) | The first general-purpose System One agent for Jev | TypeScript | ⭐ 19 |
| [live-jev](https://github.com/vinilana/live-jev) | 2D autonomous car simulation in the browser, driven by TypeSafe's Jev decision model | JavaScript | ⭐ 17 |
| [x-scanner](https://github.com/oso95/x-scanner) | Chrome extension that labels every post you scroll past on X with typed Jev judgments and a live cost counter | TypeScript | ⭐ 17 |
| [jev-test-filter](https://github.com/mizchi/jev-test-filter) | Score every test against a git diff with Jev, and emit the filter arguments vitest, node:test, Playwright, cargo test and go test already understand | TypeScript | ⭐ 16 |
| [jev-ego](https://github.com/romaluev/jev-ego) | TypeScript browser agent for ego lite: Jev Ultrafast indexed actions, TypeSafe Jev decisions, persistent observe/act CLI. No Chrome or Playwright. | TypeScript | ⭐ 15 |
| [jev-ultrafast-mcp](https://github.com/jiawei686/jev-ultrafast-mcp) · [site](https://pypi.org/project/jev-ultrafast-mcp/) | Hand the browser work off: an MCP server where a decision model drives the page for your agent, so a flow costs one tool call instead of a turn per click. Ref-based element tables, code-checked assertions, zero-model macro replay. Speaks CDP to your Chrome. | Python | ⭐ 15 |
| [lkclean](https://github.com/stefw/lkclean) | Chrome extension that cleans up your LinkedIn feed: hides engagement bait, self-promo and off-topic posts using Jev, TypeSafe AI's typed classification model — and explains every decision. | TypeScript | ⭐ 15 |
| [sift (bohutang)](https://github.com/bohutang/sift) · [site](https://typesafe.ai) | Chrome extension that labels every post on X (Substance · Humor · Chit-chat · Promo · Junk · AI-written) with TypeSafe Jev, and hides the ones you don't want. | JavaScript | ⭐ 11 |
| [xtags](https://github.com/manifoldor/xtags) | 在 X 的时间线上，给每条帖子标出它想让你干什么。判断来自 Jev，一个只返回概率、不生成文本的模型。 | JavaScript | ⭐ 11 |
| [jev-agent-browser](https://github.com/forvela/jev-agent-browser) | Fast, bounded browser agents powered by Jev and agent-browser — typed actions, research, classification, and safe orchestration. | JavaScript | ⭐ 10 |
| [JevBystander](https://github.com/Nisaka520/JevBystander) · [site](https://nisaka520.github.io/JevBystander/) | 安卓无障碍版微信判读：只读屏、只弹 3 条 Toast（意图 / 情绪 / 着急 / 建议），不生成回复文案、不发送 · 零第三方依赖，APK 861 KB | Kotlin | ⭐ 9 |
| [JevGuide](https://github.com/Nisaka520/JevGuide) · [site](https://nisaka520.github.io/JevGuide/) | 弦外之音 —— 微信聊天里的关系进展助手：读屏（无障碍树 / 截屏视觉）→ Jev 判读 + 攻略度 → 聊天模型出 3 条候选回复，攻略度常驻挂在屏幕上。不改微信、不发消息、不注入点击。 | Kotlin | ⭐ 9 |
| [aside-jev](https://github.com/himomohi/aside-jev) | Aside agents decide with TypeSafe Jev (System One: Choice/Score/Noul). Not a Cua binding — Jev is the model, Aside is the browser runtime. | Python | ⭐ 8 |
| [AskJev](https://github.com/ranjan2829/AskJev) · [site](https://docs.typesafe.ai/introduction) | AskJev — Jev autopilot for any website + guard on irreversible clicks (TypeSafe System One, not Claude) | TypeScript | ⭐ 8 |
| [keys-MiniMax-Code-CLI-Browser-Scroll-Context-Enhancement-Pack-with-Jev-Ultrafast-Integration](https://github.com/drowzeys/keys-mcode-continuous-context-browser-decision-enhancement-pack) | Validated enhancement pack for MiniMax Code CLI on arm64 DGX Spark + local GLM-5.3-EXL3: TUI scrollbar + context-meter patches, compaction repair for local vLLM, Jev Ultrafast + Playwright MCP browser integration, real usage ledger. | Python | ⭐ 8 |
| [ego-jev](https://github.com/ZephyrDeng/ego-jev) · [site](https://skills.sh/ZephyrDeng/ego-jev) | Jev (TypeSafe System One) inner loop for ego-browser — one ~0.4s typed decision per DOM step instead of an LLM turn. Agent skill for ego lite. | JavaScript | ⭐ 7 |
| [jev-browser (tontoko)](https://github.com/tontoko/jev-browser) | One grounded Jev/Playwright core: typed SDK, persistent CLI, and MCP server with native browser operations and deterministic assertions. | JavaScript | ⭐ 7 |
| [jev-weekend-shopping-chrome](https://github.com/littlewindy123/jev-weekend-shopping-chrome) | 把对双休的支持，带进每一次购物。逛淘宝、京东时，JEV 实时猜测商品背后的工作制，疑似非双休直接盖上 PASS。原页生效，边逛边选。 | JavaScript | ⭐ 7 |
| [jev-block-android-ad](https://github.com/ufec/jev-block-android-ad) | JevNoiseGate filters unwanted notifications and SMS on Android. Rather than matching keywords, an LLM decides what's noise — and only what it explicitly flags is blocked. Verification codes are matched on-device and never uploaded; anything uncertain passes through. | Kotlin | ⭐ 6 |
| [jev-yt-time-saver](https://github.com/jaibhasin/jev-yt-time-saver) | A Chrome extension that covers distracting YouTube videos with Jev. Show anyway whenever you want. | JavaScript | ⭐ 6 |
| [midscene-jev-runner](https://github.com/KiritoKing/midscene-jev-runner) | Community-maintained JEV runner integration for Midscene Test | TypeScript | ⭐ 6 |
| [jev-chat-windows](https://github.com/caizili999/jev-chat-windows) | Windows 微信回复助手（非官方修改版）：本地离线 OCR 读屏 + 模型起草候选回复 + 一键填入微信输入框，可选自动发送。不 hook、不注入、不读微信数据库。 | Python | ⭐ 5 |
| [JevOnly](https://github.com/buluoray/JevOnly) | Pure Jev that can "type" and drive towards task completion. | Python | ⭐ 5 |
| [computer_use](https://github.com/paulsmith/computer-use-jev) | macOS computer use driven by Jev (TypeSafe System One) as the decision maker | Go | ⭐ 4 |
| [ego-jev (jiangkoumo)](https://github.com/jiangkoumo/ego-jev) | Drive the ego lite browser with Jev (TypeSafe System One): one indexed element table in, one operation + target out, single process. ~2x faster than a per-step LLM loop in our measurements. | JavaScript | ⭐ 4 |
| [jev-browser (vinilana)](https://github.com/vinilana/jev-browser) | Hybrid browser harness: an LLM turns goals into verifiable subgoals, Jev chooses each action and DOM field, Playwright acts. | TypeScript | ⭐ 4 |
| [jev-mail](https://github.com/muhammedilyasy/jev-mail) | Chrome extension that triages Gmail with TypeSafe's Jev model: category, priority, spam % and reply % on every email. | JavaScript | ⭐ 4 |
| [jev-mobile](https://github.com/Friedjof/jev-mobile) | Fast structured Android control loops with TypeSafe Jev and Mobile MCP | Python | ⭐ 4 |
| [jev-ra](https://github.com/brnyxx/jev-ra) · [site](https://brnyxx.github.io/jev-ra/) | Browser use for coding agents, 3-5x faster than browser-use. MCP server + CLI; TypeSafe Jev decides every step in ~300 ms. | Python | ⭐ 4 |
| [jev-shield (vmendes90)](https://github.com/vmendes90/jev-shield) | Privacy-first Chrome extension that semantically blocks native ads, sponsored feed cards, and video ads using TypeSafe Jev | TypeScript | ⭐ 4 |
| [jev-skip](https://github.com/valentynkit/jev-skip) | Browser extension that reads the YouTube caption track and paints a per-segment sponsor probability on the seek bar before the intro ends, with no crowd database. | TypeScript | ⭐ 4 |
| [jev-wingman](https://github.com/1104480426-hash/jev-wingman) | 基于 Jev 的聊天决策辅助，不挑 App（QQ / 微信 / 飞书皆可）· An on-device chat co-pilot that returns typed verdicts instead of prose, built on Jev | Java | ⭐ 4 |
| [macos-computer-use-kit](https://github.com/Sur-Cai/macos-computer-use-kit) · [site](https://pypi.org/project/macos-computer-use-kit/) | AX-first computer use for AI agents on macOS with optional Jev (TypeSafe System One) semantic guards: calibrated target/input judgments before an irreversible action, decisions kept in code. Accessibility-tree targeting, window-scoped input, clipboard-safe paste, read-back verification. Ships a pip CLI, a pi package and a DeepSeek Harness plugin. | Python | ⭐ 4 |
| [otto](https://github.com/NobleSpartan6/otto) | Open-source native computer use for macOS and Windows: TypeSafe Jev, local OCR, and selective planning. | TypeScript | ⭐ 4 |
| [slop-filter](https://github.com/adamnroman/slop-filter) | Chrome extension that hides AI-generated posts and comments on X, LinkedIn, and Reddit. Scored by TypeSafe Jev. | JavaScript | ⭐ 4 |
| [agent-fastpath](https://github.com/abhishekswe/agent-fastpath) · [site](https://www.npmjs.com/package/agent-fastpath) | Jev MCP server: a decision layer for coding agents, built on TypeSafe Jev (System One model). Ship gates, risk checks, file triage that keeps files out of context, and a safe headless browser, with calibrated confidence. For Claude Code, Codex, Cursor. | TypeScript | ⭐ 3 |
| [CUA-JEV](https://github.com/ZJU-REAL/CUA-JEV) · [site](https://zjureal.com/CUA-JEV/) | Jev for Computer Use | Python | ⭐ 3 |
| [jev-browse](https://github.com/kyrylosyzonenko/jev-browse) | Drives a real browser with Jev making every decision and Vercel's agent-browser performing every action, with a benchmark. | JavaScript | ⭐ 3 |
| [jev-browse (0x7067)](https://github.com/0x7067/jev-browse) | Browser automation with Jev (TypeSafe) as decision model | JavaScript | ⭐ 3 |
| [jev-browser-control](https://github.com/nexibeo/jev-browser-control) · [site](https://jevbrowsercontrol.com) | Let Claude code, chatgpt codex or control your own Chrome. Chrome extension + MCP server: Jev, TypeSafe's decision model, picks each click in ~0.5 s for a fraction of a cent. MIT, bring your own OpenRouter key. | JavaScript | ⭐ 3 |
| [jev-builder](https://github.com/collapseindex/jev-builder) · [site](https://collapseindex.github.io/jev-builder/) | A browser form for building requests to TypeSafe's Jev: pick a template, fill in the blanks, copy the request. No JSON, no install, runs locally. | JavaScript | ⭐ 3 |
| [jev-frontend-qa](https://github.com/Nainish-Rai/jev-frontend-qa) | Evidence-driven frontend QA built on Jev Ultrafast and Browser Harness, with a synthetic todo demo. | Python | ⭐ 3 |
| [jev-windows-voice](https://github.com/mstf-svndk/jev-windows-voice) | Türkçe ve İngilizce doğal konuşmayla Windows 10/11 bilgisayar kontrolü: OpenAI Realtime, local Whisper, Jev, UI Automation ve Playwright. | JavaScript | ⭐ 3 |
| [tweet-911](https://github.com/elliothux/tweet-911) | Real-time AI / solicitation / parrot-bot scores for X posts and replies. Chrome extension + Workers API on open-compute, judged by TypeSafe Jev. | TypeScript | ⭐ 3 |
| [wev](https://github.com/alanhuangyoo/wev) | Local, open-weights decision model for browser agents: a drop-in for System One / Jev requests | Python | ⭐ 3 |
| [barrunto](https://github.com/elpumberto/barrunto) | A Chrome extension that brings TypeSafe's Jev to X.com to analyze posts as you browse | TypeScript | ⭐ 2 |
| [jev-adblock](https://github.com/fazlerocks/jev-adblock) | Open-source AI ad blocker for Chrome. No filter lists: TypeSafe AI's Jev model decides what is an ad. Bring your own key. | TypeScript | ⭐ 2 |
| [jev-browser-skill](https://github.com/zurfyx/jev-browser-skill) · [site](https://jev-browser.vercel.app) | Let Jev, TypeSafe's ~100ms decision model, drive your browser. A plug-and-play skill for Claude Code and Codex. | JavaScript | ⭐ 2 |
| [jev-browser-skill (ChenYCL)](https://github.com/ChenYCL/jev-browser-skill) | Browser use & computer use for coding agents, powered by TypeSafe Jev: calibrated judgments from a System One model, control loop in code. ego lite / Chrome / Safari · CLI + MCP | JavaScript | ⭐ 2 |
| [jev-linkedin-slop-filter](https://github.com/Arpit-Khandelwal/jev-linkedin-slop-filter) | Slams a BAIT, CORP or BRAG stamp onto LinkedIn engagement-bait, judged live by Jev (TypeSafe System One). | JavaScript | ⭐ 2 |
| [jevarena](https://github.com/raihankhan-rk/jevarena) | JevArena — two Jev agents duel in click-only browser games (Browser Use + TypeSafe Jev) | TypeScript | ⭐ 2 |
| [jevbrief](https://github.com/Parthkomalwad/jevbrief) | Clean, traceable state briefings for TypeSafe's Jev model | Python | ⭐ 2 |
| [jevcumber](https://github.com/RubyBrewsday/jevcumber) · [site](https://jevcumber.dev) | Write Cucumber tests with just the .feature file. No step definitions — Jev (TypeSafe AI) resolves each Gherkin step and Playwright runs it. | TypeScript | ⭐ 2 |
| [turbo](https://github.com/sightmap/jev-turbo) | Jev-powered semantic browser use | Go | ⭐ 2 |
| [Winnow](https://github.com/ThinkyMiner/Winnow) · [site](https://winnow-seven.vercel.app) | Know before you click. A Chrome extension that reads articles and YouTube videos ahead of you and says read, skim, save, or skip — with a confidence, tuned to your goals. Open source, MV3, powered by Jev. | TypeScript | ⭐ 2 |
| [almond-fastloop](https://github.com/eriestra/almond-fastloop) | Almond-fastloop: Almond's browser computer-use rig (Chrome DevTools + TypeSafe Jev), and the Browser Use Olympics benchmark it is measured on. | HTML | ⭐ 1 |
| [Cerebellum-2B](https://github.com/mkeco/Cerebellum-2B) · [site](https://huggingface.co/mkeco/Cerebellum-2B-BF16) | Non-Autoregressive AI Agent Decision Model. Open-source SOTA alternative to TypeSafe Jev. O(1) Tool Routing & DOM Automation on Qwen3.5-2B . | Python | ⭐ 1 |
| [Footwork](https://github.com/Tom-R-Main/Footwork) | A verified browser agent: a cheap Jev guard (evidence-checked completions, a destructive gate) in front of any LLM browser driver, with Jev taking the mechanical steps in dual mode. Built on browser-use; every number pre-registered and measured. | Python | ⭐ 1 |
| [hunch](https://github.com/HAR5HA-7663/hunch) | ⚡ Browser agent that acts on a hunch: Jev (TypeSafe System One) picks every click in ~150 ms, an LLM is only needed when confidence drops. Zero-dependency Python on top of agent-browser. | Python | ⭐ 1 |
| [jev-fill-pdf](https://github.com/takumi-golf/jev-fill-pdf) · [site](https://ilove-ai.net/fill) | Fill Japanese PDF forms (申請書・届出書) in one click with Jev by TypeSafe AI. Labels go to Jev, your values never leave the browser. OCR for image-only forms, works with 国税庁 forms. Built on pdf-lib / pdf.js / tesseract.js via Vercel AI Gateway. | HTML | ⭐ 1 |
| [jev-playwright-mcp](https://github.com/krw82/jev-playwright-mcp) | Jev-augmented Playwright MCP proxy — page-state triage, prompt-injection shielding, goal-based snapshot pruning, risky-action gating. Drop-in wrapper around @playwright/mcp for any coding agent. | TypeScript | ⭐ 1 |
| [jev-xianhui](https://github.com/jeffyuysw/jev-xianhui) · [site](https://xianhui.xzaigf.dpdns.org) | 先回｜消息优先级助手 Windows + Android双端工具 JEV规则引擎 + AI自动判定消息优先级 | Kotlin | ⭐ 1 |
| [jev-xianhui-windows](https://github.com/jeffyuysw/jev-xianhui-windows) · [site](https://xianhui.xzaigf.dpdns.org) | 先回｜消息优先级助手 Windows + Android双端工具 JEV规则引擎 + AI自动判定消息优先级 | Python | ⭐ 1 |
| [jevplayground](https://github.com/terryds/jevplayground) · [site](https://jevplayground.terrydjony.com) | Browser-only playground for Jev (TypeSafe AI's decision model) via Vercel AI Gateway | HTML | ⭐ 1 |
| [plotveil](https://github.com/Dearest/plotveil) · [site](https://plotveil.app) | A quiet spoiler blocker for YouTube comments. One typed Jev (TypeSafe System One) Noul decision per comment; covered while checked, still covered if the check fails. | TypeScript | ⭐ 1 |
| [psearch](https://github.com/komikat/psearch) | Parallel web search for terminals and agents, with local Chromium and Jev-guided exploration. | Python | ⭐ 1 |
| [tweet-radar](https://github.com/kelaocai/tweet-radar) · [site](https://kelaocai.github.io/tweet-radar/) | Jev / TypeSafe AI 驱动的 X 信息筛选：按你的规则发现值得读的帖子。开源判断规则库 + 免费 Chrome 扩展。Filter X with your own criteria. | JavaScript | ⭐ 1 |
| [WindowsJev](https://github.com/Teylersf/WindowsJev) | Token-efficient Windows automation and durable research MCP server for Codex and Claude Code, powered by TypeSafe Jev. | C# | ⭐ 1 |
| [browser-use-olympics](https://github.com/eriestra/browser-use-olympics) | Browser Use Olympics by Almond: one prompt, five events, one clock. Plus fast loop, a ~200-line browser computer-use agent (Chrome DevTools + TypeSafe Jev). | HTML | ⭐ 0 |
| [jev-browser (KesavanKing)](https://github.com/KesavanKing/jev-browser) | Local browser automation UI that uses TypeSafe Jev to choose bounded page actions and a text model only for field values. | Python | ⭐ 0 |
| [jev-browser (MahmoudAdelbghany)](https://github.com/MahmoudAdelbghany/jev-browser) | Jev-powered browser MCP for LLM agents — ~300ms decisions, no LLM tokens in the loop. Benchmark vs Playwright MCP included. | JavaScript | ⭐ 0 |
| [jev-page-verdict](https://github.com/torumitsutake/jev-page-verdict) | Chrome extension that asks Jev whether the page you are on is selling something or reporting first-hand experience, and marks Google results with verdicts it already has or snippet-only estimates, leaving low-confidence ones undecided. | JavaScript | ⭐ 0 |
| [jev-reach](https://github.com/rashedInt32/jev-reach) | chrome-devtools-mcp plus one tool: Jev walks the browser to the right spot, then your agent makes a single devtools call there. | TypeScript | ⭐ 0 |
| [JevTest](https://github.com/CorieW/JevTest) · [site](https://jevtest.dev) | Bounded exploratory browser testing with Jev, deterministic assertions, and replayable evidence. | TypeScript | ⭐ 0 |
| [sift](https://github.com/tylergibbs1/sift) | Chrome extension that re-ranks Google results with TypeSafe Jev and folds away sales pages and SEO filler. | TypeScript | ⭐ 0 |
| [sloppy-jevs-extension](https://github.com/neddes/sloppy-jevs-extension) | Open-source Chrome extension that filters AI-generated prose and ads with Jev | JavaScript | ⭐ 0 |

## Applications

Products, tools, and pipelines that call Jev.

| Project | Description | Language | Stars |
| --- | --- | --- | ---: |
| [Jev Trader](https://github.com/jarrodwatts/jev-trader) · [site](https://jev-trader.vercel.app/) | One trading decision every Monad block. An experiment in real-time market intelligence. | TypeScript | ⭐ 2.2k |
| [simple-jev](https://github.com/featherless-ai/simple-jev) | Turn any open model into a classifier/jev endpoint | Python | ⭐ 507 |
| [JevRev](https://github.com/Alex314618-create/JevRev) | An LLM + Jev workflow. Boost your vertebrate brain with a spine inside. | TypeScript | ⭐ 304 |
| [LLM2Jev](https://github.com/Yinsongxu/LLM2Jev) | Adapt local language models into Jev-compatible structured decision engines with Choice, Score, and Noul outputs powered by prefill-only binary inference. | Python | ⭐ 300 |
| [jev-align (Sutro)](https://github.com/sutro-sh/jev-align) · [site](https://pypi.org/project/jev-align/) | Active-learning CLI that uses human labels and GEPA to improve Jev decision definitions | Python | ⭐ 284 |
| [jeff](https://github.com/logan-markewich/jeff) | A self-hosted drop-in replacement for TypeSafe's jev, powered by GliFormer. | Python | ⭐ 238 |
| [notra](https://github.com/usenotra/notra) · [site](https://www.usenotra.com/) | Marketing analytics platform whose feature flag routes brand-visibility classifiers off an LLM and onto Jev boolean decisions. | TypeScript | ⭐ 215 |
| [jev-semgrep](https://github.com/uehaj/jev-semgrep) | grep by meaning, across languages. TypeSafe Jev scores every line against a meaning; combine meanings with AND/OR/NOT. 意味で探す grep。日本語で英語を、英語で日本語を検索できる | JavaScript | ⭐ 134 |
| [jev-trade](https://github.com/aowang-ai/jev-trade) · [site](https://jev-trade.com) | Live Jev trader on Hyperliquid | TypeScript | ⭐ 131 |
| [typesafe_register](https://github.com/Futureppo/typesafe_register) | typesafe.ai注册机，极致优化，无限jev | Python | ⭐ 120 |
| [jev-voice](https://github.com/kevinbadi/jev-voice) | Talk to your Mac. Local whisper.cpp + one Jev (TypeSafe) call per command + macOS automation. | Python | ⭐ 86 |
| [jev-leftpad](https://github.com/f/jev-leftpad) | Left-pad strings with TypeSafe AI's Jev. For reasons. | JavaScript | ⭐ 84 |
| [jevmeter](https://github.com/ChetasLua/jevmeter) | Put a live Jev (TypeSafe) meter on any video: every sentence scored, rendered as a 16:9 edit | Python | ⭐ 82 |
| [blink](https://github.com/ellipsis-dev/blink) | Codebase search powered by Jev from @typesafe-ai | TypeScript | ⭐ 72 |
| [Jev-Case](https://github.com/Hiwoniu/Jev-Case) | 收集全网优秀 case 的收藏库 \| A curated collection of excellent cases from across the web | TypeScript | ⭐ 65 |
| [OpenDecision](https://github.com/deepanwadhwa/OpenDecision) | OpenDecision is an open-source semantic decision engine like typesafe's jev. | Python | ⭐ 56 |
| [semdecide](https://github.com/sharziki/semdecide) | Typed semantic decisions for Unix pipelines and CI, powered by TypeSafe AI Jev. | Python | ⭐ 55 |
| [Valen](https://github.com/Liuziyu77/Valen) | Train a Jev-like multimodal model by yourself. System One Model, now with vision. | Python | ⭐ 51 |
| [Jev-Moderation-Bot](https://github.com/brainstormity/Jev-Moderation-Bot) | Real-time Discord moderation bot: Jev evaluates messages and metadata in parallel to catch phishing, spam, and social engineering with a progressive escalation ladder. | Python | ⭐ 45 |
| [jev-foundation-models](https://github.com/peterfriese/jev-foundation-models) | A lightweight, native Swift 6 bridge integrating TypeSafe AI's Jev System One decision model into Apple's Foundation Models framework. | Swift | ⭐ 42 |
| [laya-server (1Panel-dev)](https://github.com/1Panel-dev/laya-server) | A self-hosted API and web interface for Laya’s structured decision models, compatible with the TypeSafe Jev API format. | TypeScript | ⭐ 41 |
| [jevify (fidecastro)](https://github.com/fidecastro/jevify) | Supersimple way to serve LLMs as a Jev-like endpoint | Python | ⭐ 37 |
| [commit-miner](https://github.com/devanshbatham/commit-miner) | Classify Git commit diffs and messages with Jev. Bug fixes, security fixes/CWEs, and change types. | Rust | ⭐ 36 |
| [jev-suite](https://github.com/klauswg/jev-suite) | Four decision-quality tools on Jev (TypeSafe System One): Jev answers structured questions, deterministic code keeps the final say. | Java | ⭐ 36 |
| [jev-edge](https://github.com/kiwi0719/jev-edge) | Typed-judgment admission control at the traffic edge: three-layer prompt-injection and abuse filter for nginx/OpenResty, powered by TypeSafe Jev. Fail-open, cached, hot-reloadable. | Lua | ⭐ 34 |
| [Jev-Trades](https://github.com/zadescoxp/Jev-Trades) · [site](https://jevtrades.zadescoxp.com) | Trading bot with the all new TypeSafe AI's first system one model named as Jev | Python | ⭐ 30 |
| [refgarden](https://github.com/AlbionaHoti/refgarden) | A spatial reference explorer for creators. Local Jev query choices, metadata highlights and source-linked collections. | TypeScript | ⭐ 30 |
| [Jev-Quantum](https://github.com/karminski/Jev-Quantum) | 亚微秒级 System-1 模型，准确率服从高斯分布 | Rust | ⭐ 28 |
| [Jev-Register-Tool](https://github.com/2951461586/Jev-Register-Tool) | TypeSafe（Jev / System One）申请 → 确认邮件 → 获批 → 注册 → 建 API Key 全链路工具，纯 HTTP 无浏览器 | Python | ⭐ 26 |
| [dohnuts](https://github.com/PsiACE/dohnuts) · [site](https://dohnuts.ai/) | Dohnuts builds small multimodal models for direct decisions. -> System One model | Python | ⭐ 25 |
| [jgrep (kyu1204)](https://github.com/kyu1204/jgrep) | grep for what code does, not what it's called. Semantic code search powered by TypeSafe Jev. | TypeScript | ⭐ 25 |
| [jev-mac-voice](https://github.com/brudarko/jev-mac-voice) | English full-duplex voice control for macOS with OpenAI Realtime, native Accessibility, and Jev. | JavaScript | ⭐ 20 |
| [jev-reranker](https://github.com/hotchpotch/jev-reranker) | Jev-powered relevance filtering and reranking for RAG in Python. | Python | ⭐ 20 |
| [invalidate](https://github.com/chopratejas/invalidate) | The invalidation layer for AI memory. Every fact gets a lease; new evidence ends it. Built on TypeSafe Jev. | Python | ⭐ 18 |
| [jev-gmail-ai-spam-filter-and-labeling](https://github.com/ilyamk/jev-gmail-ai-spam-filter-and-labeling) | Self-hosted AI email classifier for Gmail powered by Jev. Create custom labels, organize your inbox, and filter spam with confidence and cost controls. | JavaScript | ⭐ 17 |
| [jevocks](https://github.com/unicodeveloper/jevocks) · [site](https://jevinik.up.railway.app) | Everyday Stocks Status with Jev | TypeScript | ⭐ 17 |
| [jev-mail-classifier](https://github.com/parth-kp/jev-mail-classifier) | Classify your inbox with Jev (TypeSafe's System One model) — tag, move, flag, and notify, all config-driven. | Python | ⭐ 16 |
| [jevyoumean](https://github.com/syumai/jevyoumean) | Semantic "Did you mean?" for any CLI — wraps commands and uses TypeSafe's Jev to match subcommand typos by intent, not edit distance. | Go | ⭐ 14 |
| [systemANE](https://github.com/kerryrm/systemANE) | Using Apple's Neural Engine as a fast and free local "System One" Decision Engine (macOS 27) - "Honey, we have Jev at home" | Python | ⭐ 14 |
| [jev-cli (tumf)](https://github.com/tumf/jev-cli) · [site](https://docs.typesafe.ai/introduction) | Small dependency-free CLI for TypeSafe Jev | Python | ⭐ 13 |
| [llm-typesafe](https://github.com/simonw/llm-typesafe) | LLM plugin for accessing Jev and other TypeSafe AI models | Python | ⭐ 13 |
| [wechat-jev-assistant](https://github.com/yushen100/wechat-jev-assistant) | Windows 微信对话分析助手：本地读取、脱敏、TypeSafe Jev 判断与加密历史 | Python | ⭐ 13 |
| [goutoujunshi-jev-chat](https://github.com/shengjidaguai-china/goutoujunshi-jev-chat) | 狗头军师 Chat：Mac 微信读屏、关系分析与回复草稿悬浮窗 | Python | ⭐ 12 |
| [jev_antispam_bot](https://github.com/backmeupplz/jev_antispam_bot) | Minimal grammY Telegram anti-spam bot powered by TypeSafe Jev | TypeScript | ⭐ 11 |
| [jev-rerank](https://github.com/hev/reranker) | Use Jev (TypeSafe's System One model) as a calibrated reranker: one call, up to 30 documents, a probability per document. Apache-2.0. | Python | ⭐ 11 |
| [jevlogs](https://github.com/reachjalil/jevlogs) | Open-source Jev log triage for OpenTelemetry. Score the signal before expensive LLM analysis. | JavaScript | ⭐ 11 |
| [jev-rs](https://github.com/yijunyu/jev-rs) | System One judgments (noul/choice/score) from any LLM in one prefill — a Rust, Jev-compatible /v1/systemone engine | Rust | ⭐ 10 |
| [hearth-jev-rental-search](https://github.com/Nancy-Chauhan/hearth-jev-rental-search) | Autonomous multi-source rental search powered by TypeSafe Jev | JavaScript | ⭐ 9 |
| [jev-chat-jarvis-ios](https://github.com/jev-chat/jev-chat-jarvis-ios) | iPhone 键盘版：一个自定义键盘打通所有聊天 App——长按复制对方消息，键盘上出意图、风险与候选回复，点一下进输入框。只读剪贴板，源码形式（需自行用 Xcode 编译安装）。 | Swift | ⭐ 9 |
| [jevflow](https://github.com/Mawfyy/jevflow) | Probabilistic AI decisions as composable backend primitives — typed judgments (noul/score/choice), deterministic thresholds, and explainable workflows. Powered by TypeSafe's Jev, provider-agnostic. | TypeScript | ⭐ 9 |
| [lejudge-jev-jepa](https://github.com/AbdelStark/lejudge-jev-jepa) | Natural-language constraints for JEPA world-model planning, judged by a decision model instead of an LLM. | Python | ⭐ 9 |
| [twitter-jev-guard](https://github.com/qs-lll/twitter-jev-guard) | 使用 TypeSafe Jev 在 X/Twitter 时间线上识别低质量、垃圾和广告帖子，并在文字区域显示醒目的半透明水印。 | JavaScript | ⭐ 9 |
| [jev-minesweeper](https://github.com/comoc/jev-minesweeper) | TypeSafe Jev (System One) にブラウザ上のマインスイーパーを解かせるデモ | JavaScript | ⭐ 8 |
| [jev-tree](https://github.com/reachjalil/jev-tree) · [site](https://reachjalil.github.io/jev-tree/) | Recursive Jev choice over a taxonomy. Select from more than 255 options without breaking TypeSafe Jev's choice cap. | TypeScript | ⭐ 8 |
| [semantic-live-caption](https://github.com/limboinf/semantic-live-caption) | 听写纸 · Real-time speech captions with live semantic annotation (key points / emotion / intent) — Confucius4-R2T2 + TypeSafe Jev + DeepSeek | HTML | ⭐ 8 |
| [citation-verifier](https://github.com/MarissaFamularo/citation-verifier) · [site](https://verify.papertrellis.com) | Check whether each cited paper supports the sentence citing it. Claude proves the quote, TypeSafe's Jev scores it, a human decides. | JavaScript | ⭐ 7 |
| [every](https://github.com/sufianetaouil/every) | Ask a yes/no question of every function in a codebase. Ranked answers in seconds, for cents. Grep whose pattern is a question, powered by TypeSafe Jev. | Python | ⭐ 7 |
| [jev_jsonschema](https://github.com/Kiln-AI/jev_jsonschema) | Run a JSON Schema through TypeSafe's Jev API, and get JSON back. | Python | ⭐ 7 |
| [jevstudio](https://github.com/inteligenciamilgrau/jevstudio) | Jev Studio para criar programas usando Jev da TypeSafe | Python | ⭐ 7 |
| [one-system](https://github.com/rawwerks/one-system) | Use local and hosted classifiers aka decision models aka Jev-like models, all through a single TypeSafe API | TypeScript | ⭐ 7 |
| [verdict](https://github.com/khimaros/verdict) | turn any llama-server into a jev system one endpoint | Python | ⭐ 7 |
| [jev-chat-windows-deepseek-jev](https://github.com/Aimark-dai/jev-chat-windows-deepseek-jev) | Windows 微信回复助手：DeepSeek 官方生成话术，TypeSafe JEV 官方判断排序，支持可取消的 3 秒自动发送。 | Python | ⭐ 6 |
| [jev-dimabsa](https://github.com/ZhangYiqun018/jev-dimabsa) | TypeSafe Jev baseline for DimABSA (SemEval-2026 Task 3) subtask 1: zero-shot and 3-shot valence-arousal regression | Python | ⭐ 6 |
| [typesafe-jev](https://github.com/gtaras7/typesafe-jev) | Screen a folder of CVs with the TypeSafe Jev decision model: typed judgments, an editable policy, free re-scoring. | TypeScript | ⭐ 6 |
| [ai-elo-ranker](https://github.com/opaielsheikh/ai-elo-ranker) | High-speed recursive AI Elo tournament engine powered by Jev and Swiss matchmaking | Python | ⭐ 5 |
| [hearim](https://github.com/ziozzang/hearim) | hearim (헤아림) — Jev-compatible multi-backend System One gateway in Go | Go | ⭐ 5 |
| [Jev_Ontology](https://github.com/dagfinndybvig/Jev_Ontology) | Trying to combine Jev with ontology | Python | ⭐ 5 |
| [jev-docs-zh](https://github.com/Bald0Wang/jev-docs-zh) | Jev 模型（TypeSafe AI）官方使用文档的中文翻译 \| Unofficial Chinese translation of the official Jev (TypeSafe AI) docs — https://docs.typesafe.ai | Python | ⭐ 5 |
| [jev.nvim](https://github.com/valentynkit/jev.nvim) | Neovim plugin that asks the buffer a plain-language question: Treesitter splits it into functions, Jev scores each one, and answers land in quickfix ranked by probability. | Lua | ⭐ 5 |
| [jevsql](https://github.com/EugeneBoondock/jevsql) | SQL with natural-language predicates, powered by TypeSafe's Jev. Filter, rank, classify and score rows by meaning — batched, cached and cost-guarded. | JavaScript | ⭐ 5 |
| [lichen](https://github.com/Mushroom-Systems/lichen) | A local, API-compatible replacement for Jev, TypeSafe's System One model | Python | ⭐ 5 |
| [llm-to-jev](https://github.com/alexwestco/llm-to-jev) | Convert LLM prompts to Jev prompts | JavaScript | ⭐ 5 |
| [pagegrade](https://github.com/kitze/pagegrade) | Grade page sections for clarity, writing and on-page SEO. WXT + TypeSafe AI Jev. | TypeScript | ⭐ 5 |
| [ai-provider-for-jev](https://github.com/soderlind/ai-provider-for-jev) | Connect WordPress to TypeSafe's Jev System One model for structured decisions (choice, score, noul). | PHP | ⭐ 4 |
| [askgrep](https://github.com/fajarhide/askgrep) | grep for the questions you cannot write as a pattern. Reads every function instead of sampling a few. Powered by Jev, TypeSafe AI's System One model. | Rust | ⭐ 4 |
| [dohnuts.cpp](https://github.com/DreamBlooms/dohnuts.cpp) | The same decisions, on CPU. System One model that can run on your Personal Computer. | C++ | ⭐ 4 |
| [jev-document-classification](https://github.com/Charlyhno-eng/jev-document-classification) | JEV Document Classification enables the rapid and cost-effective classification of text-based documents using AI, leveraging TypeSafe's "System One" model. | TypeScript | ⭐ 4 |
| [jev-grug](https://github.com/mkotlikov/jev-grug) | Helping JEV speak <3 | TypeScript | ⭐ 4 |
| [jev-pr-labeler](https://github.com/1jehuang/jev-pr-labeler) | Semantic GitHub PR labels using Jev's typed decisions, with conceptual scope instead of line counts | Python | ⭐ 4 |
| [jev-voice-control](https://github.com/chris-wozniczek/jev-voice-control) · [site](https://chris-wozniczek.github.io/jev-voice-control/) | Control your Mac by voice. Speech → Jev (TypeSafe AI System One model) typed decisions → macOS actions. Menu-bar Swift app. | Swift | ⭐ 4 |
| [jevclip](https://github.com/cclank/jevclip) | Jev-powered video highlights and cited summaries from subtitles and scripts | Python | ⭐ 4 |
| [jevify (Mintzs)](https://github.com/Mintzs/jevify) | An optimized inference engine to turn LLMs into Jev-like machines: optimized for quick, lightweight, and accurate decision-making, classification, and scoring | Python | ⭐ 4 |
| [jevseek](https://github.com/blingdivinity/jevseek) | DeepSeek proposes the next token, TypeSafe's Jev chooses it: a decision model used as a sampler | Python | ⭐ 4 |
| [jlink](https://github.com/keltokhy/jlink) | Links records under a plain-English match rule using Jev Noul pair judgments, with local candidate blocking and match resolution. | Python | ⭐ 4 |
| [nlgrep](https://github.com/YehuiTang0316/jev-nlgrep) | TypeScript CLI that finds code, docs, logs, and text by natural-language conditions using Jev Noul judgments, with probability thresholds, source lines, and cached results. | TypeScript | ⭐ 4 |
| [traderai](https://github.com/amanadhav/traderai) | Self-hosted AI trading intelligence platform - scoring engine, two-model AI analyst (Claude + TypeSafe Jev), risk engine, discipline guardian, backtester, React dashboard | Python | ⭐ 4 |
| [typesafe-cli (y0usaf)](https://github.com/y0usaf/typesafe-cli) | Ask Jev typed questions from the shell: noul, choice, and score answers as numbers, not prose | TypeScript | ⭐ 4 |
| [everything-about-jev](https://github.com/qingshungLI/everything-about-jev) | tell you everything about jev,TypeSafe AI's System One model for typed decisions. | Python | ⭐ 3 |
| [go-system-one](https://github.com/rcarmo/go-system-one) | when a gopher met Jev | Go | ⭐ 3 |
| [jev-accounts-hub](https://github.com/antTing/jev-accounts-hub) | A multi-account manager and API gateway for TypeSafe / Jev. 一个用于 TypeSafe / Jev 的多账户管理器和 API 网关。交流群：1102910606 | Go | ⭐ 3 |
| [jev-cli](https://github.com/jtsang4/jev-cli) | CLI for TypeSafe AI's Jev evaluation model — typed questions in, structured JSON answers out | TypeScript | ⭐ 3 |
| [jev-helper](https://github.com/ra2web/jev-helper) | A helper which use JEV to play ra2web(WannaFire Version)[王二火大] | JavaScript | ⭐ 3 |
| [jev-lm (uhhfeef)](https://github.com/uhhfeef/jev-lm) | A character-level language model built on Jev, a System One classifier | Python | ⭐ 3 |
| [jev-reranker (shinpr)](https://github.com/shinpr/jev-reranker) | Rerank, filter, and compress JSON search results with TypeSafe AI's Jev. | Rust | ⭐ 3 |
| [jev-resume-disqualifier](https://github.com/AiPersonacademy/jev-resume-disqualifier) | Jev Resume Disqualifier: Sub-25ms automated resume knockout engine powered by TypeSafe Jev System One decision intelligence. Eliminates 80% of unqualified applicants with deterministic date math & EEOC-safe rejection notices. | Python | ⭐ 3 |
| [jselect](https://github.com/keltokhy/jselect) | Selects source-linked evidence within a token budget using Jev Noul relevance judgments and local diversity-aware selection. | Python | ⭐ 3 |
| [RSI-Jev-Slay-the-Spire-2](https://github.com/yzxoi/RSI-Jev-Slay-the-Spire-2) | https://v.douyin.com/iJtUdfsywHU/ | Python | ⭐ 3 |
| [smart-switch](https://github.com/reycn/smart-switch) | Reimagined window switcher for macOS using frontier artificial intelligence. Predicted by TypeSafe's Jev model | Swift | ⭐ 3 |
| [systemone-lite](https://github.com/fritzprix/systemone-lite) | Toy local System One–style decision API (Jev-shaped). Not affiliated with TypeSafe. | Python | ⭐ 3 |
| [typesafe-go](https://github.com/sd109/typesafe-go) | A collection of typesafe.ai API utilities | Go | ⭐ 3 |
| [AOS_GLM_language](https://github.com/ThePikey/AOS_GLM_language) | Sovereign 0-VRAM & 0-LLM Deterministic Reality Engine & TypeSafe Jev Replacement with VSA Hypervectors, Golay G_24 QEC, Clifford Cℓ(8,0) Bivector Wedge Gates, Poincare Geodesics, and Cellular Sheaf Cohomology | Python | ⭐ 2 |
| [bili-hardcore-jev](https://github.com/yanglei070-ux/bili-hardcore-jev) | 用 JEV（TypeSafe System One 判断模型）自动完成 B 站「硬核会员试炼」的单文件 Python 脚本：手机只扫码登录一次，100 题在电脑上自动答完，零第三方依赖。 | Python | ⭐ 2 |
| [btc-jev-signal](https://github.com/WebGrga/btc-jev-signal) | Experimental multi-horizon BTC signal generator using TypeSafe Jev probabilities and Binance market data. | TypeScript | ⭐ 2 |
| [discoprint](https://github.com/lirantal/discoprint) | Classify an artist's discography by theme, mood, and lyrical complexity with Jev (TypeSafe AI), and view it as a colorful terminal dashboard | JavaScript | ⭐ 2 |
| [emoji-jev](https://github.com/colinmcdermott/emoji-jev) | Emoji autocomplete at the speed of typing. TypeSafe AI Jev on a Whop-hosted TanStack Start app. | TypeScript | ⭐ 2 |
| [haogan](https://github.com/zhengge6/haogan) | 好感度分析：把一段双人聊天读成情绪、意图和好感信号。贴进微信记录，标签标在气泡上。Jev 判断，MIT。 | TypeScript | ⭐ 2 |
| [heyreach-jev-bot](https://github.com/matthew004-web/heyreach-jev-bot) | Signal-based LinkedIn outbound scoring for HeyReach, running on Jev (TypeSafe System One). | Python | ⭐ 2 |
| [jev-A-share-trader](https://github.com/Eric-Zhou-0302/jev-A-share-trader) | Local A-share technical analysis using Jev Choice and Noul questions to assess direction and volatility across two horizons, with evidence for Buy/Hold/Sell assessments and no order execution. | Python | ⭐ 2 |
| [jev-audio-beeper](https://github.com/santos-sanz/jev-audio-beeper) | Low-latency audio censorship POC using Jev typed decisions and ffmpeg. | TypeScript | ⭐ 2 |
| [Jev-AV](https://github.com/newuser7171/antivirus) | Antivirus scanner and real-time defense sentinel: extracts structural features from executables, scripts, and documents (entropy, hashes, strings, PE imports) and has Jev judge whether each is malicious. | Python | ⭐ 2 |
| [jev-crush](https://github.com/zhengge6/jev-crush) | jev-crush：把一段双人聊天读成情绪、意图和好感信号。贴进微信记录，标签标在气泡上。Jev 判断，MIT。 | TypeScript | ⭐ 2 |
| [jev-cvss](https://github.com/Red5d/jev-cvss) | Fast CVSS scoring from vulnerability descriptions using Typesafe Jev | Python | ⭐ 2 |
| [jev-trade-cc](https://github.com/michaelpersonal/jev-trade-cc) | Jev Can Trade Stocks — a point-in-time O'Neil momentum backtest where TypeSafe's System One model picks the entries and judges the exits | Python | ⭐ 2 |
| [jev-x](https://github.com/vladzima/jev-x) | Cut the noise on your X timeline: Jev (TypeSafe System One) scores posts on firsthand experience, promo, bait, depth, and relevance; your sliders decide what gets dimmed or collapsed. | JavaScript | ⭐ 2 |
| [jevibe-check](https://github.com/sriganesh/jevibe-check) | A live tone labeler for Bluesky posts and drafts, using TypeSafe's Jev API. | JavaScript | ⭐ 2 |
| [JevTicktRouter](https://github.com/GhrezaKh74/JevTicktRouter) | A .NET 10 and React 19 application for fast, structured AI-powered ticket triage using TypeSafe Jev. | C# | ⭐ 2 |
| [jevtree](https://github.com/qzqdz/jevtree) | LLM-authored decision SOP generator for Jev System One model | Python | ⭐ 2 |
| [laya-server](https://github.com/pjt3591oo/laya-server) | typesafe ai > systemone > jev | Python | ⭐ 2 |
| [llm2jev](https://github.com/tic-top/llm2jev) | Any chat model, any engine (SGLang, vLLM, transformers) as a Jev-compatible probability decision service: one prefill, one label token | Python | ⭐ 2 |
| [typesafe-docs](https://github.com/thiagoadril/typesafe-docs) | System One Models & Jev documentation. typesafe.ai documentation extracted in .md format for LLMs. Used to train LLMs. |  | ⭐ 2 |
| [commentcop](https://github.com/ntedvs/commentcop) | Put your code comments on trial. Powered by Jev. | TypeScript | ⭐ 1 |
| [draftpulse](https://github.com/pekth/draftpulse) | Experimental: live X draft viral scorer powered by TypeSafe Jev | TypeScript | ⭐ 1 |
| [Jackalope](https://github.com/Jackalope-Dev/jackalope) · [site](https://jackalope.dev) | Desktop GUI for agentic coding that routes tasks across local agents and accounts, with Jev picking the best agent per task, running basic code-review checks, and supplying context. | Rust | ⭐ 1 |
| [jev-logtriage](https://github.com/jyatesdotdev/jev-logtriage) · [site](https://pypi.org/project/jev-logtriage/) | Jev scores collapsed log batches; code maps answers to suppress, watch, review, notify, or page. Nothing is executed. | Python | ⭐ 1 |
| [jevegis](https://github.com/0xArx/jevegis) · [site](https://jevegis.vercel.app) | Guardrails for LLM apps in one API call. Prompt injection, jailbreaks, leaks, unsafe content. Built on TypeSafe Jev. MIT. | TypeScript | ⭐ 1 |
| [dmx.to](https://dmx.to) | X client with Jev smart rules that filter the timeline by usefulness, type, and topic. |  |  |
| [Jev Classifier](https://jevclassifier.vercel.app) | Local Telegram channel JSON analyzer for intent, quality, sentiment, and speaker tone. |  |  |
| [jev-resume-analyzer](https://github.com/awun8191/jev-resume-analyzer) | CV diagnostics and job alignment with TypeSafe Jev, React and FastAPI | Python | ⭐ 0 |
| [mimicry](https://github.com/jxucoder/mimicry) | Rewrite AI drafts in your own voice with a bounded TypeSafe feedback loop. | Python | ⭐ 0 |
| [pkg-gate](https://github.com/hemanth/pkg-gate) · [site](https://hemanth.github.io/pkg-gate/) | Pre-install security gate for npm lifecycle scripts using TypeSafe System One. | JavaScript | ⭐ 0 |
| [s1s](https://github.com/cpaczek/s1s) · [site](https://s1s.iar.dev) | System One Search: navigate and trace code with TypeSafe judgments and repository evidence | TypeScript | ⭐ 0 |
| [scam-shield](https://github.com/ShupingR/scam-shield) · [site](https://scam-shield-seven-ecru.vercel.app) | Scam text message filter powered by TypeSafe's Jev model | TypeScript | ⭐ 0 |
| [transcript-scorecard](https://github.com/brandonbryant12/transcript-scorecard) | ACME live support-call scoring demo with TypeSafe AI, Effect, SQLite, React, Vite, and Turborepo | TypeScript | ⭐ 0 |
| [typesafe-comment](https://github.com/Hexdigest123/typesafe-comment) | Small Python package that uses typesafe.ai to evaluate code comments on certain heuristics | Python | ⭐ 0 |
| [typesafe-triage-guard](https://github.com/shivam2003-dev/typesafe-triage-guard) | Three composable judgment pipelines on TypeSafe's Jev: support-ticket triage, observability alert triage, and a deploy-risk gate. | Python | ⭐ 0 |

## Games & simulations

Games and simulations with Jev making the moves.

| Project | Description | Language | Stars |
| --- | --- | --- | ---: |
| [Jev plays Mario](https://github.com/fhshaik/typesafe-mario) | Less talking. More jumping. Watch Jev navigate Super Mario Bros. from game state. | Python | ⭐ 383 |
| [RoboJEV](https://github.com/lykycy123/RoboJEV) · [site](https://lykycy123.github.io/RoboJEV/) | Two-stage JEV control of a Franka Panda in MuJoCo | Python | ⭐ 42 |
| [clash-jev](https://github.com/bytelabs-oss/clash-jev) · [site](https://bytelabs-oss.github.io/clash-jev/) | A Clash Royale bot with no trained policy: Jev (TypeSafe System One) makes every decision from the live game state | Python | ⭐ 32 |
| [PlayJev](https://github.com/OmniJev/PlayJev) · [site](https://omnijev.github.io/PlayJev/) | Play ten browser games from the screen with a 0.8B open model that returns a probability over the game's legal moves in one forward pass, no text generated. | JavaScript | ⭐ 32 |
| [OneVOneJev](https://github.com/emrickgarrett/OneVOneJev) | 1v1 Jev quickscope arena — Three.js + TypeSafe System One | TypeScript | ⭐ 31 |
| [tsai-sc](https://github.com/phyous/tsai-sc) | TypeSafe Jev controls original StarCraft shareware through keyboard and mouse with recorded action probabilities. | Python | ⭐ 24 |
| [typesafe-snake](https://github.com/sorrycc/typesafe-snake) | Snake auto-played by TypeSafe's Jev model: one System One choice per tick, legal moves and facts generated in code | TypeScript | ⭐ 22 |
| [jev-reflex-autonomy-lab](https://github.com/khordoo/jev-reflex-autonomy-lab) · [site](https://jev-reflex-autonomy-lab.vercel.app) | Multi-drone autonomy lab demonstrating TypeSafe Jev reflex decisions with optional System 2 strategy guidance. | TypeScript | ⭐ 17 |
| [jev-tetris (trungdq88)](https://github.com/trungdq88/jev-tetris) · [site](https://jev-tetris.vercel.app) | Jev play Tetris in real-time against other AI models | JavaScript | ⭐ 15 |
| [jev-doom-agent](https://github.com/lukaske/jev-doom-agent) | A browser-native Doom agent experiment with structured spatial state, composable AI controls, live decision telemetry, and a Chocolate Doom WebAssembly runtime. | TypeScript | ⭐ 14 |
| [mario-jev](https://github.com/shantanugoel/mario-jev) | Python prototype that plays NES Super Mario Bros. from structured RAM observations, with Jev answering focused movement and jump questions. | Python | ⭐ 13 |
| [jev-askable-arm](https://github.com/TarunTomar122/jev-askable-arm) | Zero-shot English goals on a sim Franka. Jev chains hardcoded primitives. | Python | ⭐ 11 |
| [gg-friggin-ez](https://github.com/ItisShikhar/gg-friggin-ez) · [site](https://itisshikhar.github.io/gg-friggin-ez/) | Fast, drop-in profanity and toxicity screener for Node.js, powered by TypeSafe AI Jev. Catches leetspeak, character spacing, and romanized profanity across languages including Kannada, Telugu, Tamil, Hindi, and Bengali. ~50-500ms latency. | TypeScript | ⭐ 7 |
| [heist-one](https://github.com/AbdelStark/heist-one) | Observable browser stealth game: Jev makes typed guard judgments while deterministic code owns the world. | TypeScript | ⭐ 7 |
| [jev-grand-prix](https://github.com/enoyola/jev-grand-prix) | An F1 racing game where TypeSafe's Jev picks the racing line and the pedals, and learns each corner's limit between laps | JavaScript | ⭐ 7 |
| [hundred](https://github.com/jammaru/jev-lab) | 100 AI NPCs live in a tiny town. Jev chooses the next action; the world writes the story. | TypeScript | ⭐ 6 |
| [jev-harness (ismaelsoilet)](https://github.com/ismaelsoilet/jev-harness) · [site](https://pypi.org/project/jev-harness/) | Zero-dependency System One decision harness: 5 semantic gates saving frontier AI agent tokens on trivial errors & doom loops. Python + TypeScript + Rust. MCP-compatible. | Python | ⭐ 6 |
| [jev-plays-pokemon-red](https://github.com/valentynkit/jev-plays-pokemon-red) | Pokemon Red on PyBoy where code owns the route and the arithmetic, Jev only picks at branches, and every battle turn's faint prediction is scored by Brier against RAM state. | Python | ⭐ 6 |
| [amigos-jev](https://github.com/amigos-robot/amigos-jev) | a free multi-modal jev API for everyone |  | ⭐ 5 |
| [agi-jev-containment](https://github.com/carlosedm10/agi-jev-containment) | AGI JEV Detection — local AI agent monitor: chain-level malicious-agent detection (TypeSafe Jev + Sentinel), escalate-only L1–L5 containment, Neo4j forensics, AngryRobot dashboard. HackSpain 2026. | Python | ⭐ 4 |
| [jev-arena-nanojev](https://github.com/liao96312/jev-arena-nanojev) | 完全本地的 NanoJev 网格决策游戏实验场，支持中文 Pygame、多关卡与 GTX 1660S 训练 | Python | ⭐ 4 |
| [rubikjev](https://github.com/0xtrou/rubikjev) · [site](https://rubikjev.solo.engineer) | Challenge the Jev's intelligence in Rubik Cube puzzles | TypeScript | ⭐ 4 |
| [jev-2048-selenium](https://github.com/AMMIROSOH/jev-2048-selenium) | Selenium 2048 player powered by expectimax search and TypeSafe Jev, with portrait FFmpeg recording. | Python | ⭐ 3 |
| [jev-gomoku (XieChengYuan)](https://github.com/XieChengYuan/jev-gomoku) · [site](https://xiechengyuan.github.io/jev-gomoku/) | 弈瞬：双 Jev 五子棋九宫格输入实验台，逐手查看模型决策，支持真实对局回放与实时对战。 | JavaScript | ⭐ 3 |
| [jevtown](https://github.com/gaborishka/jevtown) · [site](https://jevtown.ivanhabor.com) | Jevtown: a social network where people write and 10,000 AI personas react | JavaScript | ⭐ 3 |
| [rpg-jev](https://github.com/lmvdz/rpg-jev) | A living-world RPG whose NPCs are decided by TypeSafe's Jev judge model; code owns rules, numbers and state. | TypeScript | ⭐ 3 |
| [system-one-chess](https://github.com/dperezcabrera/system-one-chess) | Chess against Jev, TypeSafe AI's System One model, through OpenRouter. Built with the pico framework. | Python | ⭐ 3 |
| [Agent-JEV-Tetris](https://github.com/Yasserbhb/Agent-JEV-Tetris) | using the new model JEV to play the game tetris | HTML | ⭐ 2 |
| [component-charades](https://github.com/southleft/component-charades) · [site](https://component-charades.vercel.app) | A Taboo-style parlour game for design systems, refereed by Jev (TypeSafe System One model) | TypeScript | ⭐ 2 |
| [DoomSat](https://github.com/Devonance/DoomSat) | F´ flight software → CCSDS/Yamcs → Open MCT, with jev (System One) and Claude Sonnet 5 (System Two) driving Doom over that real mission stack. | Python | ⭐ 2 |
| [HACKSPAIN-2026](https://github.com/CarlosCaoLopez/HACKSPAIN-2026) · [site](https://taiafox-ph-five.vercel.app/) | Taiafox filters a hundred incoming messages down to the three that matter, coordinates responders by voice, and re-plans in under a second when the fire turns. | Python | ⭐ 2 |
| [jev-play-ping-pong](https://github.com/Icohen007/jev-play-ping-pong) · [site](https://indispensable-lingonberry-hot.julius.site/) | Jev plays browser table tennis in real time: structured telemetry, typed decisions, ordinary Chrome inputs, and auditable evidence. | JavaScript | ⭐ 2 |
| [jev2048 (erhanmeydan)](https://github.com/erhanmeydan/jev2048) | TypeSafe'in Jev karar modeli gerçek bir online 2048 sitesinde oynuyor — hamle başına tek API çağrısı, tek anahtar. | Python | ⭐ 2 |
| [jevball](https://github.com/atarikcaliskan/jevball) · [site](https://jevball.online) | 22 Jev models, one ball: a 3D football match where every player is its own Jev (TypeSafe AI System One) decision. Watch, or take over the number 9. | JavaScript | ⭐ 2 |
| [Slither-Me-Jev](https://github.com/tanayvasishtha/Slither-Me-Jev) | 8 AI snakes, 1 human, 1 arena. Every snake is driven live by TypeSafe's Jev, making all decisions in real time | JavaScript | ⭐ 2 |
| [snake-jev](https://github.com/siroccomask/snake-jev) | Snake controlled by parallel Jev assessments, with one API call per game tick. | Python | ⭐ 2 |
| [tsai-civ2](https://github.com/phyous/tsai-civ2) | TypeSafe Jev plays original Civilization II in a browser, with live action probabilities. Experimental full-game harness. | Python | ⭐ 2 |
| [jev-snake](https://github.com/iammusham/jev-snake) | An experimental Snake environment where the game engine owns deterministic rules and TypeSafe AI's Jev makes the movement decision from structured state on every tick. | Python | ⭐ 1 |
| [jev-snake (lalitsonawane)](https://github.com/lalitsonawane/jev-snake) · [site](https://jev-snake-theta.vercel.app) | Snake autoplay powered by TypeSafe Jev (System One) | TypeScript | ⭐ 1 |
| [jev-t-rex-runner](https://github.com/joshlarsen/jev-t-rex-runner) · [site](https://devfolioco.github.io/t-rex-runner-game/) | Chrome dino game played by Typesafe AI Jev model | JavaScript | ⭐ 1 |
| [jev2048](https://github.com/KyleKreuter/jev2048) | Let Jev (TypeSafeAI) solve 2048 | TypeScript | ⭐ 1 |
| [typesafe-chess](https://github.com/TholeG/typesafe-chess) | Chess where both players are TypeSafe's Jev model: every move is a typed Choice decision | JavaScript | ⭐ 1 |
| [typesafe-minecraft-demo](https://github.com/ellistev/typesafe-minecraft-demo) | A Minecraft Java player controlled by TypeSafe AI, with live decisions, Canadian flag building, and a side-by-side dashboard. | JavaScript | ⭐ 1 |
| [beatjev](https://github.com/lambertsj/beatjev) · [site](https://beatjev2it.jlamberts86.workers.dev) | Browser game: try to beat Jev at spotting a spam message. | JavaScript | ⭐ 0 |
| [casse-brique-typesafe](https://github.com/Para-FR/casse-brique-typesafe) | A Next.js brick breaker whose paddle is controlled in real time by TypeSafe AI's Jev model. Built with Claude Code. | TypeScript | ⭐ 0 |
| [chess-jev](https://chess-jev.loomens.com) | 3D chess where Jev plays both sides, or you jump in. |  |  |
| [Coffee Under Fire](https://github.com/joaoh82/coffee-under-fire) · [site](https://coffee.yardsort.sh/) | A browser coffee-delivery arena shooter where TypeSafe AI’s Jev model chooses NPC actions through typed Choice questions. | TypeScript | ⭐ 0 |
| [cyber-breach-jev](https://github.com/rchovatiya88/cyber-breach-jev) | Cyber-Breach: The Jev Protocol - A tactical cyberpunk arena combat game powered by TypeSafe AI Jev System One decision model | JavaScript | ⭐ 0 |
| [Game Plan](https://game-plan.adriaansendennis.workers.dev/play) | Small game that tests how Jev handles unknown input. |  |  |
| [Hollow Creek](https://hollow-creek-sigma.vercel.app) | Village NPCs that judge you each tick, deciding what to do and how they feel, instead of chatting. |  |  |
| [Jev Arcade](https://jev-arcade.vercel.app/duel) | Krunker-style 1v1 FPS where Jev decides move, aim, ADS, fire, and jump at about 9 Hz. |  |  |
| [Jev board games](https://jevboardgames.everpaper.app/) | Playable board games driven by Jev decisions. |  |  |
| [Jev Pac-Man](https://jev-pacman.ephraimduncan.com) | The maze as JSON; Jev picks the turn at each junction in real time. |  |  |
| [Jev Tetris](https://jev-omega.vercel.app) | Jev picks rotation and column from holes, stack height, and bumpiness. |  |  |
| [jev-bfs](https://github.com/komikat/jev-bfs) | Wikipedia link races with direct Jev ranking and a live terminal display. | Python | ⭐ 0 |
| [jev-games](https://github.com/shantanugoel/jev-games) | Visual Jev lab for multiple games and emulator platforms | Python | ⭐ 0 |
| [jev-gomoku](https://github.com/mizchi/jev-gomoku) | MoonBit client for Jev plus a Jev-vs-Jev gomoku match, with timing logs. | MoonBit | ⭐ 0 |
| [jev-tetris](https://github.com/MachineLearning-Nerd/jev-tetris) | A visual TypeSafe demo where Jev chooses verified Tetris placements. | Python | ⭐ 0 |
| [jev.mods](https://github.com/Hardel-DW/jev.mods) | Minecraft mod where Jev tries to finish the game from scratch without a scripted route. | Java | ⭐ 0 |
| [last-exit](https://github.com/0x963D/last-exit) · [site](https://gate.fade.tools) | A cyberpunk border encounter powered by TypeSafe Jev. Bluff the guard. Inspect the receipts. | JavaScript | ⭐ 0 |
| [pdoom-protocol](https://github.com/onionminionops-beep/pdoom-protocol) | USER + JEV: P(DOOM) PROTOCOL — co-op platform shooter where TypeSafe Jev plays alongside you | TypeScript | ⭐ 0 |
| [pong-jev](https://github.com/safzanpirani/pong-jev) | TypeSafe's Jev plays Atari Pong. One typed Choice question per frame, no coordinates sent to the model. | TypeScript | ⭐ 0 |
| [ps2-ai-agent](https://github.com/opaielsheikh/ps2-ai-agent) | Autonomous PlayStation 2 AI Agent with real-time visual telemetry HUD powered by TypeSafe Jev System One | Python | ⭐ 0 |
| [river-oaks](https://github.com/BunsDev/river-oaks) · [site](https://river-oaks-one.vercel.app) | NPCs of River Oaks Houston, Texas using Jev to power NPCs | JavaScript | ⭐ 0 |
| [river-run-typesafe](https://github.com/ashaazami/river-run-typesafe) | River shooter game in Python, inspired by Atari's River Raid, played by a TypeSafe AI pilot | Python | ⭐ 0 |
| [shady-town](https://github.com/tpaulshippy/shady-town) | Shady Town: social-deduction party game for the living room TV, moderated by TypeSafe Jev | Ruby | ⭐ 0 |
| [siege](https://github.com/vnmoorthy/siege) · [site](https://vnmoorthy.github.io/siege/) | SIEGE: 200 people vs one agent. A typed action gate (TypeSafe System One) that learns from every breach, evaluated by W&B Weave, hardened by a defender loop. Built at CoreWeave Hacks: Agent Loops 2026. | TypeScript | ⭐ 0 |
| [terrarium](https://github.com/TheGali/terrarium) | A sandbox where a TypeSafe System One model presses the controls of a small creature. Code runs the world. | JavaScript | ⭐ 0 |
| [typesafe-3d-chess](https://github.com/malDuffin/typesafe-3d-chess) | 3D chess powered by TypeSafe AI (Jev). AI vs AI by default, or play either side. Multiple difficulty levels. | TypeScript | ⭐ 0 |

## Demos & playgrounds

Live demos and playgrounds.

| Project | Description | Language | Stars |
| --- | --- | --- | ---: |
| [shapeshift](https://github.com/anishfn/shapeshift) · [site](https://shapeshiftui.vercel.app) | An input that becomes what you mean: one text box that morphs into the right UI as you type. Powered by TypeSafe Jev, works offline. | TypeScript | ⭐ 491 |
| [killmyidea](https://github.com/monteduro/killmyidea) · [site](https://killmyidea.stemonte.io) | Describe your startup idea. Jev decides: kill it, fix it or ship it. | TypeScript | ⭐ 159 |
| [jevcache](https://github.com/hyperspaceai/jevcache) · [site](https://jevcache.sh) | A decision cache for TypeSafe Jev-class models — memoize decisions so repeats are free, deterministic, and shareable. One 2 MB binary. |  | ⭐ 72 |
| [jev-spring-boot-starter](https://github.com/danvega/jev-spring-boot-starter) | A simple Spring Boot 4 starter for TypeSafe Jev using Spring MVC and RestClient | Java | ⭐ 37 |
| [stuntd](https://github.com/bladedevoff/stuntd) | Local proxy that learns your app's typed LLM decisions and answers them with a Laya head. Jev and OpenAI compatible. | Python | ⭐ 21 |
| [typesafe-ai-playground (BunsDev)](https://github.com/TypeSafeAI/typesafe-playground) · [site](https://jev.works) | Community TypeSafe AI playground: 110 use cases, games, dilemmas and model challenges, with editable prompts, A/B comparisons and a mobile-friendly UI. | TypeScript | ⭐ 20 |
| [snap](https://github.com/emnlmn/snap) | Typed decisions from unstructured state: one forward pass, zero generated text. Local, deterministic, Jev-compatible. Not affiliated with typesafe.ai. | Rust | ⭐ 17 |
| [jevframe](https://github.com/ktaletsk/jevframe) · [site](https://pypi.org/project/jevframe/) | Semantic AI for pandas and Polars: classify text, analyze sentiment, and score DataFrame rows with natural-language questions and full probabilities using TypeSafe Jev. | Python | ⭐ 14 |
| [jev-me](https://github.com/jon-devlapaz/jev-me) | A grill-me style interrogation of your idea, with Jev doing the grilling. | Python | ⭐ 13 |
| [jev-ultralightspeed](https://github.com/collapseindex/jev-ultralightspeed) · [site](https://www.collapseindex.org/) | BRRRRRRRRRRRRRRRRRRRRRR | Python | ⭐ 12 |
| [flue-jev-demo](https://github.com/matthewp/flue-jev-demo) | Flue agent routing with TypeSafe Jev through Cloudflare AI Gateway | TypeScript | ⭐ 9 |
| [Instinct](https://github.com/joevidev/ui-generator-instinct-jev) · [site](https://ui-generator-instinct-jev.vercel.app) | Instinct: describe a case in free text and Jev picks the UI from a fixed catalog without generating a line of code or copy. | TypeScript | ⭐ 7 |
| [jev-system-one](https://github.com/haseeb-heaven/jev-system-one) | A polished OpenAI + TypeSafe Jev terminal interface for answers with transparent decision reports | Python | ⭐ 5 |
| [jevguide](https://github.com/2456868764/jevguide) · [site](https://jev.guide) | Curated Jev showcases from X, organized by category with media previews and direct source links. |  | ⭐ 5 |
| [jevmoji](https://github.com/cheeaun/jevmoji) · [site](https://jevmoji.cheeaun.workers.dev) | Type anything. Get related emojis scored 0–3 with Jev. | JavaScript | ⭐ 5 |
| [jevsearch](https://github.com/kylemclaren/jevsearch) · [site](https://jevsearch.fly.dev) | Site search that understands the question. Ranked by TypeSafe's Jev model. | TypeScript | ⭐ 5 |
| [typesafe-poc](https://github.com/eminetto/typesafe-poc) | Prova de Conceito do Jev, modelo da typesafe.ai | Go | ⭐ 5 |
| [jev-ai](https://github.com/codaaiteam/jev-ai) · [site](https://jevtypesafeai.com) | Jev AI quickstart & FAQ — TypeSafe AI's System One model. Try it free: jevtypesafeai.com |  | ⭐ 4 |
| [jev-compaction](https://github.com/Waxmell114514/jev-compaction) · [site](https://waxmell114514.github.io/jev-compaction/) | A context compactor that can only score, never write — so an agent's memory can't hold a fact the transcript never contained. Working demo, runs offline. | Python | ⭐ 4 |
| [jev-resume-match](https://github.com/hamidfarmani/jev-resume-match) | Score how well a resume matches a job description using Jev (TypeSafe AI). Next.js app that returns typed, explainable match scores instead of generated text. | TypeScript | ⭐ 4 |
| [jev-trip](https://github.com/liaoyuhua/jev-trip) · [site](https://jev-trip.vercel.app) | Two Minds, One Trip. https://jev-trip.vercel.app/ | TypeScript | ⭐ 4 |
| [jeveryword](https://github.com/jkrup/jeveryword) · [site](https://jeveryword.vercel.app) | Text extraction with Jev: field extraction, PII detection and exact quotes, built on TypeSafe's Jev. | JavaScript | ⭐ 4 |
| [jevseo](https://github.com/epergaboni/jevseo) · [site](https://jevseo.epergaboni.com/) | Typed SEO, AEO and GEO judgments powered by Jev, a System One decision model. Code owns the rules, the model owns the meaning. | TypeScript | ⭐ 4 |
| [jev-ids](https://github.com/jev-ids/jev-ids) · [site](https://jev-ids.github.io) | Blazing-Fast Token-Efficient Intrusion Detection System (IDS) based on TypeSafe's Jev | Python | ⭐ 3 |
| [jev-notion](https://github.com/jeffloo886/jev-notion) | 🚀 Blazing-fast native macOS menu bar companion for Notion. Pure Swift & SwiftUI (<3MB), 8 languages. | TypeScript | ⭐ 3 |
| [read-with-jev](https://github.com/carlaiau/read-with-jev) · [site](https://www.readwithjev.com) | A Demo of using JEV to classify various attributes of a book, and present that to the reader to augment the reading experience | TypeScript | ⭐ 3 |
| [Should AI Kill Us All?](https://github.com/hellogumbo/should-ai-kill-us-all) · [site](https://shouldaikillusall.com) | Live verdict page: feeds Jev the day’s Florida Man, odd-news, politics and world headlines and asks all three primitives whether AI should kill us all, refreshed every ten minutes. | JavaScript | ⭐ 3 |
| [typesafe-ai-playground](https://github.com/nickthompson480/typesafe-ai-playground) | Community TypeSafe AI playground: 110 use cases, games, dilemmas and model challenges, with editable prompts, A/B comparisons and a mobile-friendly UI. | JavaScript | ⭐ 3 |
| [werr](https://github.com/pCwOrM/werr) · [site](https://pcworm.github.io/werr/) | Zero-memory System-1 decision engine & TypeSafe Jev wire-compatible runtime powered by Mandelbrot wave dynamics (JevBench #1). | Python | ⭐ 3 |
| [ai-type-safe-platform](https://github.com/symfony/ai-type-safe-platform) · [site](https://symfony.com/packages/ai-type-safe-platform) | TypeSafe platform bridge for Symfony AI | PHP | ⭐ 2 |
| [ask-jev-ai](https://github.com/waynesutton/ask-jev-ai) · [site](https://www.askjev.ai/) | A public wall where anyone asks a question in three to fifteen words and Jev, TypeSafe's judgment model, answers yes, no, or it depends in about 100 milliseconds. Every judged ask lands on the wall in realtime, with a running count toward one million, showing cost. | JavaScript | ⭐ 2 |
| [chat2jev](https://github.com/Chandler-Sun/chat2jev) · [site](https://chat2jev.myai.family) | Convert legacy chat completion API request to Typesafe jev API | TypeScript | ⭐ 2 |
| [clarity-judge](https://github.com/TypeSafeAI/clarity-judge) · [site](https://judge.jev.works) | Multi-axis writing quality checker powered by TypeSafe AI's Jev model. Separate named checks, each with its own verdict and confidence. | TypeScript | ⭐ 2 |
| [got-jev](https://github.com/phureewat29/jev-got) · [site](https://jev.phureewat.com) | Jev (TypeSafe AI) PoC through Game of Thrones | TypeScript | ⭐ 2 |
| [intelliprompter](https://github.com/finetuningsingh/intelliprompter) · [site](https://finetuningsingh.github.io/intelliprompter/) | A teleprompter of talking points that checks each one off as you cover it, using TypeSafe's Jev Score questions | HTML | ⭐ 2 |
| [jev_fsd](https://github.com/BrendanH18/jev_fsd) | JEV AI Model Demo with FSD | JavaScript | ⭐ 2 |
| [jev-cloud-quiz](https://github.com/minorun365/jev-cloud-quiz) · [site](https://dxtmc35dbmyei.cloudfront.net/) | 三大クラウドの機能名を、TypeSafe AI の System One モデル Jev が確率つきで判定するデモ | TypeScript | ⭐ 2 |
| [jev-connector](https://github.com/juanlentino/jev-connector) | WordPress connector for the TypeSafe System One API (Jev): typed questions, confidence-scored answers, core Connectors API key management | PHP | ⭐ 2 |
| [jev-information-extraction](https://github.com/abhishekmamdapure/jev-information-extraction) · [site](https://jev-information-extraction-fibby-prod-telegram.up.railway.app/) | Parsing the PDF and extracting the relevant information | Python | ⭐ 2 |
| [jev-pii-checker](https://github.com/coo-quack/jev-pii-checker) · [site](https://coo-quack.github.io/jev-pii-checker/) | CLI that finds PII in text with TypeSafe Jev: presence, sensitivity, and located spans | TypeScript | ⭐ 2 |
| [jev-starter (YanfLIZi56)](https://github.com/YanfLIZi56/jev-starter) | Visually configure Jev questions, test them live, export ready-to-use code. | Vue | ⭐ 2 |
| [jevpdf](https://github.com/kylemclaren/jevpdf) · [site](https://jevpdf.fly.dev) | Ask a PDF in your own words and watch the matching lines light up. React + pdf.js + TypeSafe Jev. | TypeScript | ⭐ 2 |
| [jfind](https://github.com/religa/jfind) · [site](https://pypi.org/project/jfind-cli/) | Find files by describing them in plain English: find(1) with a semantic --like predicate, answered by TypeSafe.ai's jev model | Python | ⭐ 2 |
| [laya-serve](https://github.com/stiermid/laya-serve) · [site](https://stiermid.github.io/laya-serve/) | Jev-compatible HTTP server for Laya System One decision models | Python | ⭐ 2 |
| [Postmark](https://github.com/silky-x0/Postmark) · [site](https://postmark-rho.vercel.app/) | A working Demo that acts as classifier to classify linkedin post which inside uses jev by Typesafe.ai | TypeScript | ⭐ 2 |
| [tempo-jev-demo](https://github.com/mychaelangelo/tempo-jev-demo) | A natural-language task workspace comparing performance across AI models (TypeSafe's Jev, GPT-5.6 Luna, and Gemini 3.8 Flash) | TypeScript | ⭐ 2 |
| [toolgate](https://github.com/ndolinschi/toolgate) · [site](https://toolgate.vercel.app) | Agent tool/MCP call gate — allow / ask_human / deny via TypeSafe Jev | TypeScript | ⭐ 2 |
| [typesafe-ai-jev-example](https://github.com/ItBayMax/typesafe-ai-jev-example) | Hands-on demos for TypeSafe's Jev (System One) model: six runnable examples and four field notes. Runs offline with no API key; samples/ holds real measured output from jev-1.13.0. | Python | ⭐ 2 |
| [typesafe-ai-playground (markjaquith)](https://github.com/markjaquith/typesafe-ai-playground) | A playground for experiments around Jev, TypeSafe's System One model. | Rust | ⭐ 2 |
| [typesafe-arena](https://github.com/DeepBlueDynamics/typesafe-arena) | A playground for TypeSafeAI's Jev Model | Rust | ⭐ 2 |
| [gpt-vs-jev](https://github.com/TanayPadar/gpt-vs-jev) · [site](https://gptvsjev.vercel.app) | Compare GPT generated language with JEV structured Noul decisions on the same input. | TypeScript | ⭐ 1 |
| [guard-jev](https://github.com/NorbertBodziony/guard-jev) · [site](https://guard-jev.vercel.app) | Comment-moderation playground: paste a comment, Jev decides what to do with it. | TypeScript | ⭐ 1 |
| [harden-jev-decides](https://github.com/tylerjharden/harden-jev-decides) | JEV picks which stream idea becomes the live MVP. TypeSafe System One decision board. | TypeScript | ⭐ 1 |
| [human-compiler](https://github.com/asfarsadewa/human-compiler) · [site](https://human-compiler.asfarlab.fun) | A compiler for human language. Paste text, get diagnostics. Measured by TypeSafe Jev. | TypeScript | ⭐ 1 |
| [jev (zeke)](https://github.com/zeke/jev) · [site](https://jev-triage-playground.ziki.workers.dev) | Research notes and an interactive Cloudflare Worker demo for Jev, TypeSafe AI's structured decision model | TypeScript | ⭐ 1 |
| [jev_projects](https://github.com/X0EF/jev_projects) · [site](https://jev-projects.vercel.app) | list of projects that use typesafe's jev | JavaScript | ⭐ 1 |
| [jev-boe-demo](https://github.com/Tatuck/jev-boe-demo) · [site](https://tatuck.github.io/jev-boe-demo/) | Daily demo applying TypeSafe's Jev model to Spain's official gazette (BOE). | TypeScript | ⭐ 1 |
| [jev-demo](https://github.com/PenglongHuang/jev-demo) · [site](http://118.196.50.229/jev/) | TypeSafe Jev（System One 决策模型）零依赖网页体验台：浏览器操作 / 意图识别 / Agent 上下文裁剪三大预设场景，发送状态与类型化问题，拿到带校准概率的结构化答案 | JavaScript | ⭐ 1 |
| [jev-hooks](https://github.com/microchipgnu/jev-hooks) · [site](https://jev-hooks-demo.microchipgnu.workers.dev/docs/) | Compose typed Jev judgments as reactive semantic state in React and backend programs | TypeScript | ⭐ 1 |
| [JEV-language](https://github.com/Nolane-x/JEV-language) · [site](https://nolane-x.github.io/JEV-language/) | Give your Jev language | TypeScript | ⭐ 1 |
| [jev-paper-judge](https://github.com/JacobLinCool/jev-paper-judge) · [site](https://jev-paper-judge.jacob.workers.dev) | Feedback on your paper in seconds. | TypeScript | ⭐ 1 |
| [jev-playground (Little-Planet-Labs)](https://github.com/Little-Planet-Labs/jev-playground) · [site](https://jev-playground-zeta.vercel.app) | A small Next.js app for experimenting with TypeSafe AI's Jev model (System One) | TypeScript | ⭐ 1 |
| [jev-playground (wustep)](https://github.com/wustep/jev-playground) · [site](https://jev-playground.vercel.app) | Can a System One model steer music? Jev picks the plan (enums only); code renders sheet, audio and MIDI. | TypeScript | ⭐ 1 |
| [jev-practice-speed](https://github.com/tubone24/jev-practice-speed) · [site](https://jev-speed.tubone24.workers.dev/) | A WebGL demo where you play the card game Speed against a CPU whose brain is TypeSafe AI's Jev. The whole point of the app is to measure and show Jev's decision speed and decision accuracy in real time. | JavaScript | ⭐ 1 |
| [jev-should-i-apply](https://github.com/cardotrejos/jev-should-i-apply) | Typesafe/Jev public X demo |  | ⭐ 1 |
| [jevcode](https://github.com/miounet11/jevcode) · [site](https://www.jevcode.ai) | JevCode — Jev (TypeSafe System One) 技术解决方案与最佳实践 · https://www.jevcode.ai | TypeScript | ⭐ 1 |
| [jevpolicy](https://github.com/Sanoy24/jevpolicy) | JevPolicy is an open-source TypeScript decision runtime that turns probabilistic judgments from Jev, accessed through Vercel AI Gateway, into versioned, deterministic, replayable, observable application decisions. | TypeScript | ⭐ 1 |
| [jevs-sprint-planning](https://github.com/notque/jevs-sprint-planning) · [site](https://jevs-sprint-planning.vercel.app) | Four AI developers run a software sprint, each powered by TypeSafe's Jev model. Watch them claim tickets, code, review, deploy, and fight fires — with live probability bars, latency, and cost per decision. Bring your own API key or play demo mode free. | TypeScript | ⭐ 1 |
| [jevtrafficsim](https://github.com/skcache/jevtrafficsim) · [site](https://jevtrafficsim.vercel.app) | TypeSafe AI's first model Jev takes on an entire city's traffic | TypeScript | ⭐ 1 |
| [typesafe-showcase](https://github.com/Ashadeepa/typesafe-showcase) · [site](https://typesafe-showcase.vercel.app) | Next.js UI showing off TypeSafe's System One model (Jev) — parallel Noul judgments and a Choice-based citation checker, deployable to Vercel | TypeScript | ⭐ 1 |
| [cartshield](https://github.com/ndolinschi/cartshield) · [site](https://cartshield.vercel.app) | CartShield — SMB checkout fraud disposition via TypeSafe Jev | TypeScript | ⭐ 0 |
| [Crowdcheck](https://crowdcheck-ai.vercel.app/) | Test a post against 10,000 synthetic personas before you publish it. |  |  |
| [extremely-specific-council](https://github.com/cbetz/extremely-specific-council) · [site](https://extremely-specific-council-five.vercel.app) | Twelve members. Zero qualifications. A playful TypeSafe AI council with animated votes, inspectable decisions, and shareable verdicts. | TypeScript | ⭐ 0 |
| [Formatho Jev Playground](https://www.formatho.com/tools/jev-playground) | Browser-based request builder for the System One API: compose state plus typed Noul, Choice, and Score questions. Mock mode runs locally without an API key; Live mode requires your TypeSafe key and calls api.typesafe.ai directly. Generates typesafe_sdk Python. Includes companion Jev Suitability Test. |  |  |
| [harnessjudge](https://github.com/ndolinschi/harnessjudge) · [site](https://harnessjudge.vercel.app) | Judge agent steps — ok / retry / escalate / stop via TypeSafe Jev | TypeScript | ⭐ 0 |
| [hiresignal](https://github.com/ndolinschi/hiresignal) · [site](https://hiresignal-opal.vercel.app) | HireSignal — resume first-pass fit+interview via TypeSafe Jev | TypeScript | ⭐ 0 |
| [Jev Gamecast](https://github.com/narulaskaran/jev-data-questions) · [site](https://jev-gamecast.vercel.app) | Jev Gamecast: replay-first React app that asks Jev typed questions about live sports data. | TypeScript | ⭐ 0 |
| [Jev mood demo](https://jev-demo.vercel.app) | Talk nicely or nastily over time; structured state tracks the mood. |  |  |
| [Jev Room](https://jev-room.moe136231.chatgpt.site) | One sentence becomes six room settings. Jev chooses, the app renders. |  |  |
| [jev-ad-preflight](https://github.com/cardotrejos/jev-ad-preflight) | Typesafe/Jev public X demo |  | ⭐ 0 |
| [jev-board-lab](https://github.com/WebGrga/jev-board-lab) | Interactive explorer and Jev question workspace for Jev Board datasets. | JavaScript | ⭐ 0 |
| [jev-bun1](https://github.com/heiwa4126/jev-bun1) | TypeSafe の Jev を TypeScript SDK で使ってみる最初の 1 歩 | TypeScript | ⭐ 0 |
| [jev-demos](https://github.com/Bud-ro/jev-demos) | Demos to test the effectiveness of TypeSafe's "Jev" System One Model | Dart | ⭐ 0 |
| [jev-dev](https://github.com/n-yokomachi/jev-dev) | 同じ発言を jev と LLM の両方に判定させ、感情の変動値のズレと応答速度を1画面で見比べるデモ（affectus + Vercel AI Gateway） | TypeScript | ⭐ 0 |
| [jev-user-jury](https://github.com/cardotrejos/jev-user-jury) | Typesafe/Jev public X demo |  | ⭐ 0 |
| [jevplay](https://github.com/ndolinschi/jevplay) · [site](https://jevplay.vercel.app) | TypeSafe Jev playground — custom Choice/Score/Noul builder with live distributions | TypeScript | ⭐ 0 |
| [Job Risk Analyzer](https://github.com/WeSecureYou/Jev-test) · [site](https://jev-test.vercel.app) | Job Risk Analyzer: CLI and REST API that uses Jev to score an occupation's exposure to AI-driven layoffs and its resilience. | TypeScript | ⭐ 0 |
| [lanebreak](https://github.com/ndolinschi/lanebreak) · [site](https://lanebreak.vercel.app) | LaneBreak — support ticket priority+routing via TypeSafe Jev | TypeScript | ⭐ 0 |
| [Magic Jev Ball](https://github.com/mikecann/magic-jev-ball) · [site](https://magic-jev.mikecann.app) | A 3D Magic 8 Ball you shake and let go, where Jev answers your question as a Choice over the 20 classic answers and the page shows its probability for each one, running on Convex through the Convex AI Gateway. | TypeScript | ⭐ 0 |
| [mcpmatch](https://github.com/ndolinschi/mcpmatch) · [site](https://mcpmatch.vercel.app) | Match user goals to MCP catalog (two-stage) via TypeSafe Jev | TypeScript | ⭐ 0 |
| [Probably](https://github.com/JordiParraCrespo/typesafe-ai-trading-showcase) · [site](https://typesafe-ai-trading-showcase.vercel.app) | Probably: live BTC, ETH, and XRP prices with a shared TypeSafe buy-or-wait demonstration. No trades placed. | TypeScript | ⭐ 0 |
| [pulselane](https://github.com/ndolinschi/pulselane) · [site](https://pulselane-topaz.vercel.app) | PulseLane — clinic triage decisions via TypeSafe Jev | TypeScript | ⭐ 0 |
| [Search with Jev and Milvus](https://github.com/milvus-io/bootcamp/tree/master/bootcamp/RAG/search_with_jev) | Nine runnable notebooks combine Gemini embeddings and Milvus retrieval with Jev judgments for reranking, filtering, search stopping, routing, cache reuse, curation, guardrails, and evaluation. |  |  |
| [Search-Function-Test](https://github.com/Shifros/Search-Function-Test) · [site](https://search-function-test.vercel.app) | A test project based on Jev AI, the goal is to build a search function for a blog/article website that has 100s of articles to search from, So the user can actually use the search as chat to question anything and find related answers/articles | JavaScript | ⭐ 0 |
| [spendbrake](https://github.com/ndolinschi/spendbrake) · [site](https://spendbrake.vercel.app) | Agent budget brake — continue / downgrade_model / stop via TypeSafe Jev | TypeScript | ⭐ 0 |
| [swarmrouter](https://github.com/ndolinschi/swarmrouter) · [site](https://swarmrouter.vercel.app) | Route tasks to research/code/browser/support/writer agents via TypeSafe Jev | TypeScript | ⭐ 0 |
| [trustgate](https://github.com/ndolinschi/trustgate) · [site](https://trustgate-mu.vercel.app) | TrustGate — indie media T&S gate via TypeSafe Jev | TypeScript | ⭐ 0 |
| [TypeSafe Typewriter](https://typesafe-demo.val.run/) | Val Town demo where 16 typed judgments update live as you type. |  |  |
| [typesafe-image-diffusion](https://github.com/Wizhill05/typesafe-image-diffusion) | Diffusion-style pixel art out of a classifier: 256 parallel per-pixel Jev questions plus refinement passes. | HTML | ⭐ 0 |
| [Yes / No](https://yesno.coderai.dev) | Free, no-signup Noul demo. Ask a question, get yes, no, or maybe, with web search when needed. |  |  |

## Benchmarks & research

Benchmarks, evals, calibration studies, and open replicas.

| Project | Description | Language | Stars |
| --- | --- | --- | ---: |
| [NanoJev](https://github.com/TianyuCodings/NanoJev) | A nano replica of Jev: parallel decisions, dynamic candidates, and an end-to-end training pipeline. | Python | ⭐ 2.2k |
| [jevlike](https://github.com/vinnylarouge/jevlike) | Train a small model that chooses among a changing list of text options, one probability per option in a single pass. Includes Doom, chess, and Wikispeedia demos. | Python | ⭐ 1.3k |
| [openjev](https://github.com/razorback16/openjev) · [site](https://codiv.ai) | Open, Jev-compatible System One decision server on DiffusionGemma | Python | ⭐ 386 |
| [decider](https://github.com/Mapika/decider) | One-pass typed decisions with calibrated probabilities (System One style model), fine-tuned from Qwen3.5-2B | Python | ⭐ 351 |
| [agent-jev](https://github.com/malevrigns/agent-jev) | AgentJev-0.6B - a fast 'System One' decision model for AI Agents: feed it any unstructured state (diffs, traces, logs) and structured questions, get calibrated probability distributions back in one ~50ms forward pass. Zero output-token decoding. | Python | ⭐ 286 |
| [jev-visual](https://github.com/hr98w/jev-visual) | An educational Jev-like visual inference experiment on Apple Silicon: shared context, direct candidate scoring, and local visual demos. | Python | ⭐ 271 |
| [reflex](https://github.com/kshetrajna12/reflex) | A small open decision model: state + typed questions -> calibrated probabilities. A Jev / System One re-creation on Qwen3.5. | Python | ⭐ 133 |
| [jevbench](https://github.com/fstandhartinger/jevbench) | JevBench v1 - a benchmark for Jev-class typed decision models: smart, cheap, fast, reliable, open. | Python | ⭐ 114 |
| [jev-eval-agent](https://github.com/vinilana/jev-eval-agent) | Personal-assistant agent built on Vercel's eve with 100 mocked tools, measuring how many steps it takes when Jev picks the tool versus the LLM. | HTML | ⭐ 105 |
| [jev-as-a-judge](https://github.com/danielgshea/jev-as-a-judge) | Using Jev as an evaluator. | Python | ⭐ 83 |
| [jevals](https://github.com/openlayer-ai/jevals) | Agent evals and guardrails in one request. Built on Jev, Kev and Laya. | Python | ⭐ 82 |
| [jevfire](https://github.com/kikoncuo/jevfire) · [site](https://kikoncuo.github.io/jevfire/) | JEV-inspired parallel decisions for CUDA LLMs. One context, many decisions. vLLM API, game-agent examples, and reproducible benchmarks. | JavaScript | ⭐ 64 |
| [jevmlx](https://github.com/bnsd55/jevmlx) | Jev-style parallel constrained decisions for any MLX model on Apple Silicon. Typed, schema-valid JSON in one forward pass. | Python | ⭐ 60 |
| [jev-dataops](https://github.com/RenaGao/jev-dataops) · [site](https://jev-dataops.vercel.app) | An open-source JEV-powered workbench for streaming data selection, quality evaluation, automatic LoRA training and held-out model evaluation. | Python | ⭐ 55 |
| [mini-jev](https://github.com/r-ms/mini-jev) | mini-Jev: what a Jev-style typed-decision interface looks like on a frozen Qwen3-4B — read the option letter's logits instead of generating JSON. Preregistered experiment, results, teaching bench. | Python | ⭐ 53 |
| [jev-curate](https://github.com/AkashPriyadarshii/jev-curate) · [site](https://crates.io/crates/jev-curate) | High-throughput synthetic & pretraining dataset sifter powered by TypeSafe AI Jev (api.typesafe.ai). Stream, filter, and score Parquet & JSONL datasets at 1,500+ rows/sec using System One typed decisions (Choice, Score, Noul). | Rust | ⭐ 50 |
| [system-one (iamaamir)](https://github.com/iamaamir/system-one) · [site](https://iamaamir.github.io/system-one/) | Provider-neutral System One runtime for TypeScript and Pi | TypeScript | ⭐ 48 |
| [LitJev](https://github.com/zhengxuyu/litjev) | A reproduction of Jev that turns any Qwen model into a fast decision model, serving the same /v1/systemone schema (Choice, Score, Noul) with no training and no generated answer text. | Python | ⭐ 43 |
| [TypeAR](https://github.com/TypeLLM/TypeLLM) · [site](https://typear.ai/) | Type-safe one-decision-per-token decoding engine for autoregressive LLMs, inspired by Jev. | Python | ⭐ 40 |
| [typesafe-ai-benchmark](https://github.com/iammrduncan/typesafe-ai-benchmark) · [site](https://hackersintheloop.org/) | This is a LLM Gateway that mimics typesafe ai structured output. Like an imposter Jev. | TypeScript | ⭐ 38 |
| [JevForge](https://github.com/zwliJay/jev-forge) · [site](https://jev-forge.vercel.app) | End-to-end Jev-style structured-decision stack for auditable data construction, Qwen3.5-0.8B training, fixed Mind2Web and OOD evaluation, preliminary RLCD, local serving, and interactive replay. | Python | ⭐ 35 |
| [Jev_apps](https://github.com/JackZeng/Jev_apps) | 看看 Jev 能做什么：用中英文讲清热门应用、工作原理和各自优缺点。Explore Jev apps with plain-language examples, explanations, and comparisons. | Python | ⭐ 33 |
| [system-one](https://github.com/sgoedecke/system-one) | Batched single-token choice inference for open language models, compatible with TypeSafe | Python | ⭐ 33 |
| [laya-vs-jev-arena](https://github.com/PromptEngineer48/laya-vs-jev-arena) | Laya (open source, local) vs TypeSafe Jev (API): two AI models race in Snake and fight in a Mortal-Kombat-style arena. Every move is a real model decision. | JavaScript | ⭐ 29 |
| [jevify](https://github.com/altryne/jevify) · [site](https://thursdai.news) | An agent skill to discover TypeSafe Jev opportunities, design typed questions, and learn from recent community experiments. | Python | ⭐ 27 |
| [jev-capability-atlas](https://github.com/Zaious/jev-capability-atlas) | Independent, evidence-based map of when TypeSafe's Jev actually holds up vs. breaks down — real API-call receipts, not a leaderboard. 中文為主的雙語 repo。 | Python | ⭐ 26 |
| [jevgpt](https://github.com/Bewinxed/jevgpt) | A chatbot built on a model that cannot generate text (TypeSafe AI's Jev, driven autoregressively) | TypeScript | ⭐ 26 |
| [jev-cli (shaharia-lab)](https://github.com/shaharia-lab/jev-cli) | Command-line tool for TypeSafe AI's Jev model. Ask yes/no, multiple-choice and rubric questions about any text and get calibrated probabilities back. Answers become exit codes for shells and CI, JSON for scripts, and MCP tools for AI agents. | Rust | ⭐ 25 |
| [jev-judge-mcp](https://github.com/PyModel/jev-judge-mcp) | Typed judgment tools for MCP agents. TypeSafe's Jev model as verify, screen, find, classify, rerank, decide, compare, extract, review, gate, and score: the model judges, policy decides auto, review, or escalate. | Python | ⭐ 24 |
| [jev-column-race](https://github.com/goodrahstar/jev-column-race) · [site](https://jev-column-race.vercel.app) | Jev vs Gemini 3.8 Flash: labelling 1,000 app reviews, 4.1× faster and 7× cheaper | JavaScript | ⭐ 23 |
| [jev-on-a-laptop](https://github.com/rorshopping/jev-on-a-laptop) | Unofficial study: Jev-style parallel typed decisions on stock 1.5B-8B models on an Apple Silicon laptop. Benchmarks, research notes, and a Hugging Face Space demo. | Python | ⭐ 23 |
| [laya-jev-GraphRAG](https://github.com/bodepudimuneendra-netizen/laya-jev-GraphRAG) | Agentic GraphRAG engine using swappable System One decision models (local Laya / cloud Jev). Features a complete 4-phase pipeline (Ingestion, Pre-Retrieval, Traversal, Post-Retrieval) and evaluation across Neo4j, Memgraph, Apache AGE, and Kùzu driven by a custom A* traversal algorithm. | Python | ⭐ 22 |
| [open-jev](https://github.com/kyegomez/open-jev) · [site](https://discord.gg/3keGBK9Pvr) | an open-source, from-first-principles reconstruction of the ideas behind TypeSafe AI's Jev, written in pytorch | Python | ⭐ 21 |
| [jev-agent-design-with-topk-logits-choices](https://github.com/6Mikao9/jev-agent-design-with-topk-logits-choices) | Research design for a Jev-native agent system: tool integration, speculative parameter proposals, external helper logits Top-k proposals with Jev-controlled fallback ,decision-aware hierarchical memory, and dependency-aware replanning.Feature:Jev naturallanguage conversation prototype using external helper logits and dynamic Top-k token selection. | Python | ⭐ 20 |
| [jsort](https://github.com/keltokhy/jsort) | sort by meaning: order lines along a plain-English dimension, from pairwise comparisons judged by TypeSafe's Jev model | Python | ⭐ 19 |
| [jev-benchmarks](https://github.com/AbdelStark/jev-benchmarks) | Probability-aware evaluation for typed decision models: calibration, selective risk, latency, and reproducible benchmarks. | Python | ⭐ 17 |
| [jeval](https://github.com/rlaope/jeval) | Measures what your Jev classifier's confidence is really worth, and sets the human hand-off line from what a mistake costs. | Python | ⭐ 16 |
| [jev-studio](https://github.com/utk2103/jev-studio) | if you're experimenting with jev it will be easier from here | Python | ⭐ 15 |
| [open-spark-jev](https://github.com/abhishek085/open-spark-jev) | Open-source, local decision models inspired by TypeSafe’s Jev and System One - built on Qwen3 for NVIDIA DGX Spark. | Python | ⭐ 15 |
| [jev-harness](https://github.com/AntonioCoppe/jev-harness) | Decision harness for TypeSafe Jev — confidence gates, shadow mode, recipes, and evals. Claude CLI 48.9s → Jev 1.3s on the same row-filter job. | TypeScript | ⭐ 14 |
| [jev-rag-benchmark](https://github.com/erendikmenn/jev-rag-benchmark) | Reproducible benchmark for measuring Jev reranking quality, latency, and cost in RAG | Python | ⭐ 14 |
| [jevbetter](https://github.com/olanotolu/jevbetter) | A stronger one-pass scorer over a variable list of text options: hashed n-gram encoder, rival-aware attention, gated head, temperature scaling, benchmarked against jevlike. | Python | ⭐ 14 |
| [jev_stock](https://github.com/sosopop/jev_stock) | An experimental JEV-powered framework for forecasting short-term stock price direction from structured market data. | Python | ⭐ 13 |
| [JevAny](https://github.com/weitianxin/JevAny) · [site](https://huggingface.co/collections/tianxinwei/jevany-adaptive-decision-systems-6ab2c941bcecb4d2c61d1326) | Calibration-aware reinforcement learning for adaptive decision systems | Python | ⭐ 11 |
| [jevcal](https://github.com/abhixhek/jevcal) | Stop guessing confidence thresholds: calibrate, threshold, and drift-check typed decision models (TypeSafe Jev) against an LLM teacher. | Python | ⭐ 10 |
| [AnyDecisionModel](https://github.com/mattt/AnyDecisionModel) | A Swift package for typed decisions from language models (probabilities, choices, and scores), with support for local MLX models and the TypeSafe Jev API. | Swift | ⭐ 9 |
| [edgejev](https://github.com/yzfly/edgejev) · [site](https://pypi.org/project/edgejev/) | 离线可用的本地类型化决策：4 核 CPU 单题 15.6ms。Local & offline Jev / System One inference on CPU — ONNX + INT8, no torch at runtime. 支持 laya / kev / PlayJev | Python | ⭐ 9 |
| [jev_project_context](https://github.com/poiuyjie/jev_project_context) | Evidence-first long-term experiment memory skill for AI coding agents, with optional Jev decision-model layers | Python | ⭐ 9 |
| [jevmory](https://github.com/romiluz13/jevmory) | Coding-agent memory where every fact is a verbatim quote graded by TypeSafe Jev's calibrated confidence. Local-first, SQLite receipts, zero dependencies. | Python | ⭐ 9 |
| [hermes-and-jev-play-minecraft](https://github.com/teknium1/hermes-and-jev-play-minecraft) | Hermes Agent plans, Jev (TypeSafe) picks bounded actions, Mineflayer executes: Minecraft with no screenshots or keypresses from a model. Includes the reproduction of rmalde/minecraft-agent's Ender Dragon run. | JavaScript | ⭐ 8 |
| [jev.nu](https://github.com/cablehead/jev.nu) | Nushell module for the TypeSafe System One API: typed decisions with calibrated probabilities | Nushell | ⭐ 8 |
| [trade-jev](https://github.com/justinhe16/trade-jev) | Backtest Jev (TypeSafe) as a BUY/SELL/HOLD trader on NQ L10 order-book data | Python | ⭐ 8 |
| [typesafe-local](https://github.com/aabolfazl/typesafe-local) | Inspired by TypeSafe Ai, Ask a local LLM typed questions, get calibrated probabilities instead of text. Structured output without generation or parsing. MLX / Apple Silicon. | Python | ⭐ 8 |
| [JEV-Paper-Radar](https://github.com/Eliot5566/JEV-Paper-Radar) · [site](https://eliot5566.github.io/JEV-Paper-Radar/) | Let Jev read every new arXiv paper each morning and surface the few you should read. Plain-English interests, calibrated probabilities, ~$0.06/day, fork and go. | Python | ⭐ 7 |
| [jev-rerank-bench](https://github.com/anessbelbati/jev-rerank-bench) · [site](https://anessbelbati.com/blog/i-gave-jev-a-rerankers-job) | Can a decision model beat dedicated rerankers? TypeSafe Jev vs Cohere Rerank 4 vs ZeroEntropy zerank-2 vs a chat-model baseline: 14 datasets, every raw API response, bootstrap ranges on every gap. | Python | ⭐ 7 |
| [laya-browser-agent](https://github.com/ChenneyZhuang/laya-browser-agent) | Local, open-source Jev alternative: browser agent decisions with Laya (System One model) on your own machine. No cloud, no API key. Playwright/CDP, MCP-friendly. | Python | ⭐ 7 |
| [nanojev-arena](https://github.com/caijinchun/nanojev-arena) | NanoJev Snake Arena: 1v4 human-vs-AI battleship + 100-agent swarm simulator. Local demo of Jev System-One model (open-source mini replica). | HTML | ⭐ 7 |
| [pi-jev-context (Nyarlathoteppppp)](https://github.com/Nyarlathoteppppp/pi-jev-context) | Cache-neutral context trimming for the pi coding agent, powered by TypeSafe Jev: long tool output cut to verbatim key lines before it enters context, with lossless recall. Measured, with pre-registered benchmarks. | TypeScript | ⭐ 7 |
| [poorjev](https://github.com/rupeshpoojary9/poorjev) | Open-source, local Jev alternative: a System One decision layer with provably calibrated confidence (ECE 0.170→0.071). Typed decisions, runs offline, no API key, no waitlist. | Python | ⭐ 7 |
| [daf-jev](https://github.com/docxology/daf-jev) | daf-jev: composable Python toolkit for TypeSafe's Jev (System One) decision API — question builders, confidence gates, evaluator, calibration, CLI, MCP server, agent skill | Python | ⭐ 6 |
| [jev-architect](https://github.com/karanb192/jev-architect) · [site](https://jev-architect.karanbansal.in/) | Find, design, and evaluate TypeSafe Jev decision loops. | HTML | ⭐ 6 |
| [jev-benchmark](https://github.com/wondertwins/jev-benchmark) | Benchmarks and a playground for TypeSafe's Jev (System One) model: chess, and who-is-the-player-talking-to for speech-to-text game NPCs | Python | ⭐ 6 |
| [jev-korean-benchmark](https://github.com/mahlernim/jev-korean-benchmark) · [site](https://ahn-lab.org/jev-korean-benchmark/) | Reproducible early-access evaluation of Jev on Korean understanding and medical text, with runtime and cost evidence | Python | ⭐ 6 |
| [jev-lm](https://github.com/y0usaf/jev-lm) | A word-level language model whose output layer is Jev: n-gram drafter, Noul chunk verification, bits-per-token eval | TypeScript | ⭐ 6 |
| [jev-ood-calibration](https://github.com/scienthoon/jev-ood-calibration) | Independent calibration test of TypeSafe's Jev on a task it cannot have seen: 900 rule-generated support tickets (choice / score / boolean) plus 3 public benchmarks via Vercel AI Gateway. Raw responses, ECE with noise floor, temperature refit, per-type sign of miscalibration. Reproducible for ~$0.06. | Python | ⭐ 6 |
| [jev-search (larguesa)](https://github.com/larguesa/jev-search) | Experimental semantic line search with TypeSafe Jev via OpenRouter. Python CLI with no runtime dependencies. | Python | ⭐ 6 |
| [jev-search-rerank-eval](https://github.com/zhuyansen/jev-search-rerank-eval) | Does a TypeSafe Jev rerank beat embedding search? Graded relevance eval (9,831 pairs, 164 zh/en queries) over the Agent Skills Hub catalog, with the judge-circularity bias measured. | Python | ⭐ 6 |
| [learn-jev-end-to-end](https://github.com/harshithsunku/learn-jev-end-to-end) · [site](https://harshithsunku.github.io/learn-jev-end-to-end/) | Learn Jev end to end: a free hands-on course. Build 13 AI agent use cases with a fast brain (Jev) and a slow brain (LLM). One OpenRouter key. | Jupyter Notebook | ⭐ 6 |
| [mcts-agent](https://github.com/lhemerly/mcts-agent) | Discriminative Monte Carlo Tree Search using TypeSafe Jev System One Primitives and Gemini | Python | ⭐ 6 |
| [claude-jev](https://github.com/buchmark/claude-jev) | Claude Code plugin that scores review findings, debug hypotheses and design options with TypeSafe's Jev — calibrated probabilities instead of one more opinion. | TypeScript | ⭐ 5 |
| [jev-2048](https://github.com/ARCJ137442/jev-2048) · [site](https://jev-2048-ultra.vercel.app) | An instrumented 2048 web lab where every move is a Jev (TypeSafe AI System One) Choice, with no heuristic fallback \| 用 Jev 决策模型驱动每一步的 2048 网页实验台，概率、置信度、延迟与成本全部摊开可见，且刻意不做启发式兜底 | TypeScript | ⭐ 5 |
| [jev-agent-authorization](https://github.com/kinde-starter-kits/jev-agent-authorization) · [site](https://jev-gatehouse.vercel.app) | Jev agent authorization for MCP tool calls: Kinde identity and permissions plus Jev's typed, calibrated decisions, checked server-side before every call runs | TypeScript | ⭐ 5 |
| [jev-little-airways](https://github.com/lbotinelly/jev-little-airways) | A show-and-tell capability study for Jev, TypeSafe's System One decision model. | HTML | ⭐ 5 |
| [jev-phishing-bench](https://github.com/anisselbd/jev-phishing-bench) | Jev (TypeSafe) vs Claude Haiku 4.5 on 2 000 phishing emails: accuracy, calibration, latency, cost. Reproducible benchmark. | Python | ⭐ 5 |
| [jevbench (dhruvmehra)](https://github.com/dhruvmehra/jevbench) | Benchmark TypeSafe JEV against LLMs, fine-tuned BERT, Laya and zero-shot NLI on text classification: accuracy, calibration, latency, throughput, cost | Python | ⭐ 5 |
| [jevchess](https://github.com/choxos/jevchess) · [site](https://jevchess.xera.ac) | Jev, TypeSafe's System One model, plays chess against any OpenRouter LLM, Stockfish and you. One-page web app with live moves, Jev's move probabilities, saved games and win rates. | JavaScript | ⭐ 5 |
| [LegalForecastBench](https://github.com/johnhughes3/LegalForecastBench) | LegalForecast-MTD benchmark alpha and official evaluation workflows | Python | ⭐ 5 |
| [OpenJev](https://github.com/xingwudao/OpenJev) | OpenJev: an independent Jev-inspired System One decision API based on TypeSafe.ai concepts. Choice, score and noul primitives, local mock server, Python and TypeScript SDKs. Real inference planned; not affiliated with TypeSafe AI. | Python | ⭐ 5 |
| [jev-align](https://github.com/caiovicentino/jev-align) | Calibrated alignment verifier for LLM responses and agent plans — powered by Jev | JavaScript | ⭐ 4 |
| [jev-bot](https://github.com/nssmd/jev-bot) | Self-hosted Jev decision workbench and Feishu bot: automatic choices, probabilities, and experimental word/character writing. | JavaScript | ⭐ 4 |
| [jev-chat](https://github.com/adhyaay-karnwal/jev-chat) | A chatbot from typed Jev decisions: hierarchical speculative decoding over System One probabilities. | Python | ⭐ 4 |
| [jev-codes](https://github.com/Kushwho/jev-codes) · [site](https://npx@kushwho/jev-codes) | Audit your git diff against YAML coding-standards packs using TypeSafe's Jev model, from a CLI or your AI agent's command/skill. | TypeScript | ⭐ 4 |
| [jev-model-tokengate](https://github.com/Thanh-Mathieu95/jev-model-tokengate) | An OpenAI-compatible proxy that sits between your LLM and your users. It evaluates each sliding window of tokens while the response is still streaming and cuts the stream before a violating token can reach the screen. | JavaScript | ⭐ 4 |
| [jev-oas-sentinel](https://github.com/ShuhanSun/jev-oas-sentinel) | Catch breaking API behavior hidden in OpenAPI prose with deterministic checks and TypeSafe JEV System One semantic review. | Python | ⭐ 4 |
| [jev-realtime-trading](https://github.com/rthomas24/jev-realtime-trading) | Paper trading agents on a live tape, decided every second by TypeSafe's Jev (System One). Electron desktop app. | TypeScript | ⭐ 4 |
| [jev-reward-model-evaluation](https://github.com/goya4140/jev-reward-model-evaluation) · [site](https://goya4140.github.io/jev-reward-model-evaluation/) | Jev 1.13 reward-model evaluation across 8 benchmark tracks, with an interactive report and 54-row SOTA comparison | Python | ⭐ 4 |
| [jevarena (chenmingtang830)](https://github.com/chenmingtang830/jevarena) · [site](https://jevarena-lab.vercel.app) | Open-source BYOK arena for Jev and other AI judges. Find failures, compare quality, cost, and latency. | TypeScript | ⭐ 4 |
| [jevloop](https://github.com/parkavenue9639/jevloop) | A Python agent runtime powered by TypeSafe Jev: guarded tool execution, isolated Docker sandboxes, and side-by-side LLM comparisons. | Python | ⭐ 4 |
| [OpenJev (GPT-AGI)](https://github.com/GPT-AGI/OpenJev) | Jev-compatible System 开源Jev | Python | ⭐ 4 |
| [qwen-rlcd](https://github.com/shamazharikh/qwen-rlcd) | Jev-style calibrated decision model (Choice/Score/Noul) on Qwen3.5-0.8B | Python | ⭐ 4 |
| [reflexbench](https://github.com/brida-ai/reflexbench) · [site](https://www.brida.ai/blog/reflexbench-v1-system-one-models) | ReflexBench — open benchmark and evaluation harness for System One models and typed decision engines | Python | ⭐ 4 |
| [sysone-bench](https://github.com/instax-dutta/sysone-bench) | First independent head-to-head benchmark of System One decision models (Laya vs Jev) on byte-identical inputs | Python | ⭐ 4 |
| [typesafe-ai-go](https://github.com/kisshan13/typesafe-ai-go) | Community-maintained Go SDK for the TypeSafe AI System One evaluation API, with typed questions, fluent builders, retries, and examples. | Go | ⭐ 4 |
| [cairn-jev-lab](https://github.com/Cairn-ink/cairn-jev-lab) · [site](https://lab.cairn.ink/) | Test what your AI should remember. An experimental, source-aware memory admission evaluator powered by Jev, with editable cases and inspectable results. | JavaScript | ⭐ 3 |
| [cu-Jev](https://github.com/dtunai/cu-Jev) · [site](https://dtunai.blog/blog/introducing-cu-jev) | cuda-Jev — a CUDA-native Jev System One decision inference engine. Jev compatible API, examples, and reproducible benchmarks. | C | ⭐ 3 |
| [ego-jev-ultrafast](https://github.com/shikaizhong-design/ego-jev-ultrafast) | Jev drives your Ego Lite browser: one typed-choice request per step. Single-file, zero-dependency port of browser-use/jev-ultrafast with multi-model benchmarks and extra guardrails. Unofficial. | JavaScript | ⭐ 3 |
| [jet](https://github.com/arczhi/jet) | A TypeSafe-native (Jev) coding agent built on Recursive LLM Context Decomposition (RLCD), with a native macOS client | Python | ⭐ 3 |
| [Jev](https://github.com/cobusgreyling/Jev) · [site](https://docs.typesafe.ai/) | Unofficial TypeSafe Jev showcase — System One decisions, not chat. | Python | ⭐ 3 |
| [jev-as-quant](https://github.com/jiayylu/jev-as-quant) | Typed System-1 decisions (Laya/Jev) as the judgment layer of a quant research stack, with Claude as System 2. Requirements → design → code → experiments. | Python | ⭐ 3 |
| [jev-behavior-study](https://github.com/RINNECODER/jev-behavior-study) | Independent Jev 1.13.0 behavior study: report, controlled prompt experiments, raw results, and offline verification. | Python | ⭐ 3 |
| [jev-benchmark (YidiDev)](https://github.com/YidiDev/jev-benchmark) | Rubric-Based Zero-Shot Classification Benchmark: Jev vs Claude Haiku 4.5 vs OpenJev on rubric-conditioned classification, chained decision execution, and exam grading -- with full price tracking. | Python | ⭐ 3 |
| [jev-exploration](https://github.com/SamuelSacco/jev-exploration) | Jev (TypeSafe) exploratory thread: claim audit, live demos, and runnable code | Python | ⭐ 3 |
| [jev-flash-router](https://github.com/Ravinder82/jev-flash-router) | open-sourced jev-flash-router: an MCP server for TypeSafe's new Jev model. AI coding agents waste hundreds of reasoning tokens just deciding which file to edit, which route to pick, or whether a diff breaks tests. Jev evaluates state and outputs calibrated probabilities. Works with Cursor, Windsurf, & Claude Code | TypeScript | ⭐ 3 |
| [jev-for-engineers](https://github.com/Foadsf/jev-for-engineers) | Eight minimal working examples of TypeSafe's Jev (a System One model) applied to mechanical and electrical engineering: CAD/CAE/CAM routing, FEM result triage, DFM screening, BOM alignment, hallucination-proof extraction. Zero dependencies. | Python | ⭐ 3 |
| [jev-gate](https://github.com/MongLong0214/jev-gate) | Not every coding task needs your best model. Experimental Jev-powered model routing for Claude Code — V3 prototype runs today, V4 routes at the task boundary. | TypeScript | ⭐ 3 |
| [jev-guardrails](https://github.com/deepansh-saxena/jev-guardrails) | Comparing LLM-as-judge vs TypeSafe Jev for agent guardrails: same rules, same agent, measured on cost, latency, calibration and coverage. | Python | ⭐ 3 |
| [jev-sec-bench](https://github.com/Gaurav-Gosain/jev-sec-bench) | Blind security benchmarks for Jev, TypeSafe's System One model: prompt injection and vulnerable code detection, built on jev-go | Go | ⭐ 3 |
| [jev-storyboard-lab](https://github.com/jimmyliao/jev-storyboard-lab) | Google ADK vs Microsoft Agent Framework for structured-output agents, with TypeSafe Jev as a vendor-neutral QC gate | Python | ⭐ 3 |
| [jev-ui](https://github.com/etweisberg/jev-ui) · [site](https://docs.jev-ui.dev/) | React components that resolve which component to render, how to order a list, and whether to show an affordance — from calibrated judgments returned by TypeSafe's Jev. | TypeScript | ⭐ 3 |
| [jev-web-analyzer](https://github.com/replynodes/jev-web-analyzer) · [site](https://replynodes.com/jev-web-analyzer) | See what Jev thinks about your SaaS website — powered by ReplyNodes web context and Vercel AI Gateway. | TypeScript | ⭐ 3 |
| [jevtest](https://github.com/realZachi/jevtest) · [site](https://www.npmjs.com/package/jevtest) | Semantic test matchers for Vitest and Jest, powered by TypeSafe's Jev model. Write expectations in plain English, get calibrated probabilities back. | TypeScript | ⭐ 3 |
| [new-api-plugin-typesafe](https://github.com/FFatTiger/new-api-plugin-typesafe) | TypeSafe AI System One (Jev) task plugin for QuantumNous/new-api — native /v1/systemone, synchronous evaluation, token billing | JavaScript | ⭐ 3 |
| [ORIGIN-CIVILIZATION](https://github.com/JacquesGariepy/ORIGIN-CIVILIZATION) | AI life-and-civilization simulation: TypeSafe Jev makes every decision (typed, probabilistic, auditable); LLMs plan — OpenAI-compatible APIs, local models (Ollama, LM Studio), Claude Code, Codex. | HTML | ⭐ 3 |
| [rh-guard](https://github.com/24601/rh-guard) · [site](https://24601.github.io/rh-guard/) | Reward-hack radar for coding agents: structural denies + TypeSafe Jev System One sidecar for Claude Code & Cursor hooks | TypeScript | ⭐ 3 |
| [tenbin](https://github.com/simota/tenbin) | MCP server and agent skill for the TypeSafe AI System One API (Jev): decompose a judgment into Choice / Score / Noul questions, lint them, measure on labelled data, and put calibrated thresholds in code | TypeScript | ⭐ 3 |
| [tinyjev](https://github.com/ankit-aglawe/tinyjev) · [site](https://huggingface.co/AnkitAI/tinyjev-0.6b) | A tiny jev-like model that answers Choice, Score and Noul questions in one forward pass and returns calibrated probabilities. MLX or PyTorch, fully offline, System One compatible. | Python | ⭐ 3 |
| [typesafe-jev-calibrate-for-code-review](https://github.com/Selmar/typesafe-jev-calibrate-for-code-review) | About calibrating Jev for code reviews | Python | ⭐ 3 |
| [bes-kelime-jev](https://github.com/mahmut-gundogdu/bes-kelime-jev) · [site](https://5-kelime-ismail-jev.vercel.app) | Ne yazarsanız yazın, beş kelimeden biriyle cevap veren sohbet botu. Kelimeyi TypeSafe AI'ın Jev evaluation modeli seçer. | TypeScript | ⭐ 2 |
| [calibre](https://github.com/FirasSX914/Janus) | Calibration and confidence-based routing measured on Banking77: 80.2% accuracy at $0.103 per 500 decisions | Python | ⭐ 2 |
| [dsh-jev-decide](https://github.com/nanami-0713/dsh-jev-decide) | DSH plugin: register TypeSafe Jev (System One decision model) as an agent tool — jev_decide returns calibrated probabilities (noul/choice/score) for routing/triage/guardrail judgments, no text generation. 把 TypeSafe Jev 决策模型注册为 DSH agent 工具 | JavaScript | ⭐ 2 |
| [jev-agent-failure-benchmark](https://github.com/TokenTrim/jev-agent-failure-benchmark) | Benchmarking Jev (Typesafe.ai) against a strong LLM on the Who&When Pro agent-failure-attribution benchmark (text subset). | Python | ⭐ 2 |
| [jev-aita](https://github.com/dchristopoulos/jev-aita) | Benchmark of TypeSafe's Jev against Sonnet 5, GPT-5 nano and local LLMs on 770 Reddit AITA verdicts: Brier scores, latency and cost | Python | ⭐ 2 |
| [jev-bot (bl888m)](https://github.com/bl888m/jev-bot) · [site](https://x.com/bl888m_eth) | JEV-powered market decision bot for stocks, crypto and memes. State in, BUY/SELL/HOLD/AVOID out, paper by default | Python | ⭐ 2 |
| [jev-chess](https://github.com/hemanth/jev-chess) · [site](https://h3manth.com/fun/jev-chess/) | Chess moves, evaluations, persona opponents, and game classification with TypeSafe AI System One | TypeScript | ⭐ 2 |
| [jev-deepresearch](https://github.com/tashfeenahmed/jev-deepresearch) | Deep research crawl where Jev (a System One model) makes every per-page decision and an LLM only plans and writes | JavaScript | ⭐ 2 |
| [jev-dllm](https://github.com/zhouzihao11/jev-dllm) | Shared Yes/No decision adaptation with diffusion language models | Python | ⭐ 2 |
| [jev-freeform](https://github.com/kesku/jev-freeform) | An observable raw-character chat experiment powered entirely by TypeSafe Jev Choice | JavaScript | ⭐ 2 |
| [jev-mcp-server](https://github.com/wangkuangkuang/jev-mcp-server) | MCP server for Jev (TypeSafe System One): the three official question types — choice, score, noul — plus batch classify. Calibrated probabilities, ~0.5s, <$0.001/call. | Python | ⭐ 2 |
| [jev-mode](https://github.com/ddfeyes/jev-mode) | I kept watching coding agents burn context on decisions that aren't hard - triage 400 tickets, tag 600 files, route to one of six teams. jev-mode moves those verdicts to a typed-judgment model. I A/B'd it: 78% fewer tokens, 16x less work-attributable input, accuracy 96.1% vs 93.7%. Python, no deps, MIT. | Python | ⭐ 2 |
| [jev-research-eval](https://github.com/jgridifier/jev-research-eval) | Reproducible Jev Ultrafast research-browser eval harness + field note (QC’d cases, suite runner, report generator). Not investment advice. | HTML | ⭐ 2 |
| [jev-reviews](https://github.com/halfspin-qc/jev-reviews) | TypeSafe AI - Jev - first look and experiment with its API + Google reviews experiments | Astro | ⭐ 2 |
| [jev-routing-experiment](https://github.com/TokenTrim/jev-routing-experiment) | Benchmarking TypeSafe's Jev decision model as a cost-efficient LLM router on RouterArena | Python | ⭐ 2 |
| [jev-spam-eval](https://github.com/bitnovus/jev-spam-eval) | Zero-shot spam filtering with TypeSafe Jev Noul questions, compared with TF-IDF baselines | Jupyter Notebook | ⭐ 2 |
| [jev-starter](https://github.com/hamakyo/jev-starter) | Typed, policy-driven decision workflows on top of TypeSafe AI Jev: confidence routing, fallbacks, evaluation, and RAG patterns for TypeScript apps. | TypeScript | ⭐ 2 |
| [jev-system-one-reference](https://github.com/sebastianbennis/jev-system-one-reference) | Independent Jev / System One reference with API examples, implementation guidance and reusable prompts for engineers and coding assistants. |  | ⭐ 2 |
| [jev-x-kit](https://github.com/Kadihx/jev-x-kit) | Offline $0 decision layer for coding agents: Choice/Score/Noul primitives, BELKI confidence gatekeeper, ultra-planning, red-teaming, research and RLVR self-improvement -- as an MCP server + CLI + Claude Code skill. | TypeScript | ⭐ 2 |
| [jevalyzer](https://github.com/killerz3/jevalyzer) · [site](https://folio.kz3.dev/p/jevalyzer) | Grade the agent sessions already on your disk. Claude Code, Codex, opencode, Gemini CLI and Antigravity, scored with Jev for cents. | TypeScript | ⭐ 2 |
| [jevbus](https://github.com/zkjoie/jevbus) | A streaming event bus whose routing, subscription and consumption are decided by a probabilistic judge. The reference judge is TypeSafe AI's Jev (System One) model: send it a payload and a set of typed questions, get back calibrated probabilities instead of prose. | Rust | ⭐ 2 |
| [jevshield](https://github.com/lgy1027/jevshield) | Sub-100ms security gate for AI agent tool calls, powered by TypeSafe's Jev (System-1) decision model. Single-request Choice/Noul/Score evaluation, dual-factor blocking matrix, calibrated-confidence routing, fail-closed parsing, zero-config local fallback. LangChain-ready. | Python | ⭐ 2 |
| [metask-jev](https://github.com/metask-ai/metask-jev) | Metask-Jev: calibrated typed-decision models (Jev-class). Single forward pass, candidate-logit readout. metask-jev-4b beats Bespoke Nimble-9B and Jev on JevBench. | Python | ⭐ 2 |
| [open_system_one](https://github.com/Readyaddy/open_system_one) | Creating system one model just like jev. with different experimentation | Python | ⭐ 2 |
| [openpave-jev](https://github.com/cnrai/openpave-jev) | PAVE skill for non-autoregressive decision models (Jev / Laya / TypeSafe): typed Choice, Score and Noul answers with calibrated probabilities | JavaScript | ⭐ 2 |
| [polymarket-btc-5m-agent](https://github.com/BrunooMoniz/polymarket-btc-5m-agent) | Agente de trading para o mercado BTC Up/Down de 5 minutos da Polymarket: modelo em código, Jev (TypeSafe System One) como portão, ordens maker, calibração e shadows em paper | Python | ⭐ 2 |
| [pytest-jev](https://github.com/allebee/pytest-jev) · [site](https://pypi.org/project/pytest-jev/) | Semantic assertions for pytest: test what your LLM app's output means, judged by TypeSafe's Jev. | Python | ⭐ 2 |
| [research_desk](https://github.com/0xnairb/research_desk) | TypeSafe Jev demonstration for new analyzation — experimenting with Jev for fast analysis of news and tickers | Python | ⭐ 2 |
| [ruby_llm-providers-typesafe](https://github.com/javiergradiche/ruby_llm-providers-typesafe) · [site](https://rubygems.org/gems/ruby_llm-providers-typesafe) | TypeSafe System One models (Jev) for RubyLLM: typed judgments, evaluations and reranking. | Ruby | ⭐ 2 |
| [siftr](https://github.com/Bentlybro/siftr) | Fast, cheap judgment for AI coding agents: semantic search, focused reads and list picking in ~2s. CLI + MCP server on TypeSafe Jev. Benchmarked on SWE-bench. | Python | ⭐ 2 |
| [toolgate (RiskAverseTech)](https://github.com/RiskAverseTech/toolgate) | Open auto mode for AI agents — a calibrated tool-call firewall powered by TypeSafe Jev. Ships as a Claude Code hook | TypeScript | ⭐ 2 |
| [typesafe-chess (Dimesio)](https://github.com/Dimesio/typesafe-chess) | FUn little experiment with Typesafe AI Jev Model playing chess against stockfish :) | JavaScript | ⭐ 2 |
| [typesafe-jev-mcp](https://github.com/anasbekheit/typesafe-jev-mcp) · [site](https://crates.io/crates/typesafe-jev-mcp) | MCP server exposing TypeSafe's Jev model as a typed evaluate tool. | Rust | ⭐ 2 |
| [watfile](https://github.com/jexp/watfile) · [site](https://pypi.org/project/watfile/) | Text/PDF - File categorization and sorting with Typesafe AI Jev or local calibrated decision model | Python | ⭐ 2 |
| [zerosweep](https://github.com/sysadarsh/zerosweep) · [site](https://sysadarsh-zerosweep.vercel.app/) | Autonomous System-One Triage Engine & Benchmark powered by TypeSafe AI (Jev). 75ms inference, $0 output tokens, and RLCD epistemic safety gates. | TypeScript | ⭐ 2 |
| [can-jev-play](https://github.com/carlaiau/can-jev-play) · [site](https://www.canjevplay.com) | Can Jev infer whether a bet is worthwhile from its payout table, and do recent wins or losses sway that choice | TypeScript | ⭐ 1 |
| [decide](https://github.com/gopaljigaur/decide) · [site](https://pypi.org/project/pydecide/) | One client for every decision model: Choice, Score and Noul over Jev, OpenRouter, laya, MLX, CrossEncoders and LLM fallback | Python | ⭐ 1 |
| [decisionbridge](https://github.com/grishahq/decisionbridge) | A Jev-inspired decision interface for existing LLMs. Explicit choices, scores, calibration, and review thresholds. | HTML | ⭐ 1 |
| [dsh-jev-verify](https://github.com/xienda/dsh-jev-verify) · [site](https://www.npmjs.com/package/dsh-jev-verify) | Jev (TypeSafe System One) decision tools + live verification benchmark for DeepSeek Harness: jev_decision (choice/score/noul) and jev_verify, honest by design. | JavaScript | ⭐ 1 |
| [jev-benchmark (themsquared)](https://github.com/themsquared/jev-benchmark) · [site](https://webofmike.com/jev-benchmark/) | Reproducible benchmark for TypeSafe AI's Jev on agent tool-call risk classification: accuracy, latency, and whether the confidence score is worth routing on. | Python | ⭐ 1 |
| [jev-carryforward](https://github.com/Dharundp6/jev-carryforward) · [site](https://www.npmjs.com/package/carryforward) | What your last session knew, scored against what this one is doing. MCP server: a per-project ledger written as things happen, recalled per task with TypeSafe's Jev evaluation model via Vercel AI Gateway. | TypeScript | ⭐ 1 |
| [jev-filter](https://github.com/apixly-ai/jev-filter) · [site](https://apixly-ai.github.io/jev-filter/) | Semantic filtering for AI tool results. Native npm CLI, caller-controlled context, batching, and reproducible benchmarks. | Python | ⭐ 1 |
| [jev-labs](https://github.com/copyleftdev/jev-labs) · [site](https://youtu.be/C_l8FI1oddE) | Never confidently wrong: a TLA+-verified consensus kernel around TypeSafe's Jev, run through 1,680 chaos-tested pharmacy decisions with zero wrong verdicts. Film, code, and every captured call. | Python | ⭐ 1 |
| [Jev-Research-Index](https://github.com/AgenticAPP-Web/Jev-Research-Index) · [site](https://agenticapp-web.github.io/Jev-Research-Index/) | Jev Research Index is a bilingual catalogue of papers, software projects, interviews, public analyses, demonstrations, and social-media material related to Jev, the TypeSafe AI System One typed probabilistic decision model. | JavaScript | ⭐ 1 |
| [jev-secret-detection](https://github.com/teyhouse/jev-secret-detection) | Measures how well TypeSafe's RLCD-Jev model spots real secret credentials in file snippets | Python | ⭐ 1 |
| [jev-synergy-screening](https://github.com/PistachioAIHQ/jev-synergy-screening) | Jev (TypeSafe System One) × ASReview SYNERGY abstract screening demo — Choice/Noul vs gold labels | Python | ⭐ 1 |
| [jev-zig-cli](https://github.com/SupratimSircar05/jev-zig-cli) · [site](https://supratimsircar05.github.io/jev-zig-cli/) | Unofficial Jev-powered Zig terminal agent with deterministic policy gates and encrypted audit trails. | Zig | ⭐ 1 |
| [jevals-data](https://github.com/Jevals/jevals-data) · [site](https://jevals.com) | Independent benchmark data for TypeSafe's Jev (System One model) vs LLMs: accuracy, calibration, cost. Boards + per-decision logs, CC-BY-4.0 |  | ⭐ 1 |
| [kyotsu-ai-bench](https://github.com/shibadogcap/kyotsu-ai-bench) | AI benchmark on Japan's 2026 Common Test: Jev vs luna-none vs luna-low (static dashboard) | HTML | ⭐ 1 |
| [LetJevDecide](https://github.com/choxos/LetJevDecide) · [site](https://choxos.github.io/LetJevDecide/) | Ask a yes or no question. Let Jev, or a fair coin, decide. | JavaScript | ⭐ 1 |
| [MEDJEV](https://github.com/PAI-CUHK/MEDJEV) · [site](https://pai-cuhk.github.io/MEDJEV/) | Independent JEV-inspired System One-style typed decision research for clinical evidence, biomedical NLP, calibrated probabilities, and sleep signals | Python | ⭐ 1 |
| [modelsystem](https://github.com/fabricioctelles/modelsystem) · [site](https://modelsystem.one) | Curated catalog of System One / Decision Models — contributions for modelsystem.one |  | ⭐ 1 |
| [openjev-experiments](https://github.com/zefir1990/openjev-experiments) · [site](https://demensdeum.com) | Experiments with openjev, an open Jev-style option-logit runner, on local models. | Python | ⭐ 1 |
| [openjev-multimodal](https://github.com/jev-skills/openjev-multimodal) · [site](https://jev-skills.github.io/openjev-multimodal/) | Local multimodal decisions on your Mac. Jev-compatible typed probabilities with Qwen, llama.cpp and Metal. | Python | ⭐ 1 |
| [openpoke-meets-jev](https://github.com/0xShin0221/openpoke-meets-jev) | Fork of OpenPoke where the yes/no decisions go to Jev instead of Claude Sonnet, with a same-inputs A/B against the replaced LLM decision and a 43,776-request adversarial run on the injection gate. | Python | ⭐ 1 |
| [padflow-jev-evals](https://github.com/zsavage8/padflow-jev-evals) | Typed-decision benchmark from PadFlow (land development SaaS): schemas, anonymized labeled rows, and a runner for confidence-calibrated models like TypeSafe Jev. | Python | ⭐ 1 |
| [PocketJev](https://github.com/NullPo-jp/PocketJev) | On-device iPhone visual decision tool using MLX and Qwen3-VL direct option logits. | Swift | ⭐ 1 |
| [rerank-bench-jev](https://github.com/denser-org/rerank-bench-jev) · [site](https://denser.ai) | Production reranker benchmark: TypeSafe Jev vs Qwen3-Reranker-0.6B on BEIR SciFact and NFCorpus — nDCG@10, cost/query and p50/p95 latency. Quality is indistinguishable; Jev is ~2x faster, Qwen ~4x cheaper. From the team at denser.ai | Python | ⭐ 1 |
| [RISC-jeV](https://github.com/i2cjak/RISC-jeV) | I tortured Jev into being a RISC-V CPU. | Python | ⭐ 1 |
| [system-one-router](https://github.com/mmornati/system-one-router) · [site](https://mmornati.github.io/system-one-router/) | A fast System One decision model (Jev or local Laya) picks which LLM answers each prompt: OpenAI-compatible Go gateway + decision benchmark | Go | ⭐ 1 |
| [system-one-security-triage](https://github.com/Robertzu43/system-one-security-triage) · [site](https://system-one-security-triage.rzuniga-9b4.workers.dev/) | Recorded comparison of Jev, Terra, and Opus on 100 synthetic security-triage cases, five passes each, with a static inspectable dashboard | TypeScript | ⭐ 1 |
| [typesafe-vs-deepseek](https://github.com/markfive-proto/typesafe-vs-deepseek) · [site](https://typesafe-vs-deepseek.vercel.app) | TypeSafe (Jev) vs DeepSeek-flash: side-by-side speed/token/cost/accuracy comparison across invoice extraction, email classification, and reranking | Python | ⭐ 1 |
| [what-is-jev](https://github.com/g0runmezadam/what-is-jev) · [site](https://jev.com.tr) | Independent, source-linked research on TypeSafe AI's Jev (System One), with 947 rubric-scored public repositories, recurring patterns, datasets, and bilingual documentation. | Python | ⭐ 1 |
| [yc-jev-bench](https://github.com/PPRAMANIK62/yc-jev-bench) · [site](https://ycsearch.purbayan.me) | Can Jev replace an LLM reranker? A benchmark of TypeSafe's Jev vs Claude Haiku and BGE on natural-language search over all 6,245 YC companies, with a live search demo. | TypeScript | ⭐ 1 |
| [Convex Decision Evals](https://github.com/get-convex/convex-evals) · [site](https://www.convex.dev/evals/decision) | Leaderboard that puts Jev and 14 LLMs through 108 four-option multiple-choice questions about the Convex backend platform, comparing accuracy, latency, and cost, with a per-answer explorer showing Jev probabilities. | TypeScript | ⭐ 0 |
| [FinancialPredictionJev](https://github.com/thodoh1/FinancialPredictionJev) | Using Jev to test how well it predicts financial markets(just like most llms as of september 2026, it doesnt do that good) | Python | ⭐ 0 |
| [Jev Does Not Play Dice](https://github.com/KantaHayashiAI/jev-does-not-play-dice) · [site](https://kantahayashiai.github.io/posts/jev-does-not-play-dice/) | Independent calibration evaluation of Jev on fair random draws with known probabilities and synthetic forecast documents, with recorded outputs and offline recomputation. | JavaScript | ⭐ 0 |
| [jev-alpha-bench](https://github.com/Gaurav-Gosain/jev-alpha-bench) | Does Jev predict stock returns from news? It reads the news well; there is no tradeable alpha. Three arms separate reading from recall. | Go | ⭐ 0 |
| [jev-anotacao-sentencas](https://github.com/lab-dados/jev-anotacao-sentencas) · [site](https://lab-dados.github.io/jev-anotacao-sentencas/) | Jev (TypeSafe) vs. Gemini 3.8 Flash vs. GPT-5.6 Luna na anotação estruturada de sentenças do TJSP: qualidade, tempo e custo | Python | ⭐ 0 |
| [jev-deferred-crispification](https://github.com/dnakhoa/jev-deferred-crispification) | Position paper: the Hidden-Markov and fuzzy primitives missing from TypeSafe AI's Jev and System-One decision models. Two lemmas, one principle (Deferred Crispification), one architecture (BSF-S1). | TeX | ⭐ 0 |
| [jev-headline-bench](https://github.com/Gaurav-Gosain/jev-headline-bench) | Can Jev pick the winner of a real headline A/B test? 64.5% across 10,984 Upworthy randomized experiments, 74.7% when the difference was decisive. | Go | ⭐ 0 |
| [jev-jp-address](https://github.com/smasato/jev-jp-address) | Jev (TypeSafe) 性能評価プロジェクト — 日本郵便 KEN_ALL をマスタに、AI SDK 経由の Jev が住所のあいまい一致にどこまで使えるかを検証 | TypeScript | ⭐ 0 |
| [jev-lab](https://github.com/Menny1337/jev-lab) | TypeScript experiments, evaluations, and latency benchmarks for TypeSafe's Jev model | TypeScript | ⭐ 0 |
| [jev-pick-and-place-study](https://github.com/tryaksh/jev-pick-and-place-study) | A small reproducible MuJoCo pilot comparing Jev, Claude Haiku, and reactive rules for pick-and-place. | Python | ⭐ 0 |
| [jev-playground (hegargarcia)](https://github.com/hegargarcia/jev-playground) | Benchmarks Jev against other evaluation models in games with explicit states, legal actions, and measurable outcomes. | TypeScript | ⭐ 0 |
| [jev-report](https://github.com/HackSing/jev-report) | 发明 RLHF 的人，这次做了个不会说话的模型：Jev 独立研究报告。52 页 PDF + 50 条中文实测复现包 + 143 条可回溯数据表 | Python | ⭐ 0 |
| [jev-shadcn-lint-eval](https://github.com/blas0/jev-shadcn-lint-eval) | A small second eval for shadcn-ui/lint that uses TypeSafe's Jev to judge the linter's own output. | JavaScript | ⭐ 0 |
| [jev-trace-classifier](https://github.com/sypherin/jev-trace-classifier) | Application of TypeSafe Jev (noul judgment primitive) on the collusion.wiki corpus: agent vs human page authorship, head-to-head vs local Qwen3.8-Flash-Next | Python | ⭐ 0 |
| [minojev](https://github.com/zeredy879/minojev) · [site](https://zeredy879.github.io/minojev/) | Independent Jev-style replica with head training: a frozen Qwen3-1.7B backbone plus a small trained decision head returns calibrated Choice/Boolean/Score distributions in one forward pass, with committed datasets and a same-backbone generation benchmark. | Python | ⭐ 0 |
| [misereru-slide-jev](https://github.com/myokoym/misereru-slide-jev) · [site](https://myokoym.github.io/misereru-slide-jev/) | Ongoing Japanese research deck on Jev and System One models, maintained as Markdown slides. | JavaScript | ⭐ 0 |
| [Parallel Constrained Decoding (Qwen2.5-1B-RLCD)](https://huggingface.co/spaces/drinkmoonshine/parallel-constrained-decoding) | Hugging Face Space exploring open-source parallel constrained decoding as an alternative to Jev. |  |  |
| [shade-arena-jev-monitor](https://github.com/nican2018/shade-arena-jev-monitor) | Evaluating TypeSafe's Jev as a fast monitor and action gate for agent sabotage in SHADE-Arena, compared with Gemini 2.5 Flash/Pro. | Python | ⭐ 0 |
| [snbt-jev-bench](https://github.com/misaalya/snbt-jev-bench) | Jev on Indonesia's SNBT 2025 university entrance exam, whose papers are never released: 159 questions reconstructed from memory by volunteers, 156 of them scored, every response published. | Python | ⭐ 0 |
| [system-one-adapter-rust](https://github.com/codeitlikemiley/system-one-adapter-rust) | Rust port of TypeSafe system-one-adapter (LLM-backed system_one evaluations) | Rust | ⭐ 0 |
| [thaiexam-jev-charts](https://github.com/vehas/thaiexam-jev-charts) | Charts: TypeSafe Jev evaluated on Thai standardized exams vs 110 other models | HTML | ⭐ 0 |
| [Typesafe_chess_eval](https://github.com/AliceRoselia/Typesafe_chess_eval) | An evaluation of typesafe AI chess. As it turns out, the AI isn't doing really well even though chess is not a particularly open-ended game. Still, it's only a prototype and this probably wasn't optimzied for games. | Python | ⭐ 0 |
| [typesafe-oracles](https://github.com/trophee-bot/typesafe-oracles) | Evaluating TypeSafe's System One primitives (Choice/Score/Noul) — where a typed oracle beats an LLM call | JavaScript | ⭐ 0 |

## Other lists

Other curated lists.

| Project | Description | Language | Stars |
| --- | --- | --- | ---: |
| [awesome-jev (yibie)](https://github.com/yibie/awesome-jev) | A curated list of public projects, integrations, and discussions built on Jev — TypeSafe AI's System One model for typed decisions. | Python | ⭐ 1.6k |
| [awesome-jev (heyjunpenn)](https://github.com/heyjunpenn/awesome-jev) · [site](https://jevbest.com/) | A verified, community-maintained catalog of 485 open-source projects built with Jev. | Astro | ⭐ 788 |
| [awesome-jev-tools](https://github.com/v-modal/awesome-jev-tools) | A curated list of tools built for Jev — TypeSafe AI's System One model for typed decisions. |  | ⭐ 703 |
| [awesome-typesafe](https://github.com/AbdelStark/awesome-typesafe-jev) · [site](https://abdelstark.github.io/awesome-typesafe/) | Curated list of official resources and community projects for TypeSafe, System One models, and Jev, with a GitHub Pages site. | HTML | ⭐ 503 |
| [awesome-jev-projects](https://github.com/logicrw/awesome-jev-projects) · [site](https://logicrw.github.io/awesome-jev-projects/) | Awesome Jev: source-backed open-source ecosystem radar, plain-language project discovery, and automatic GitHub sync | JavaScript | ⭐ 473 |
| [jev-skill](https://github.com/wuyoscar/jev-skill) | An awesome collection of Jev use cases, workflows, and agent skills. | Python | ⭐ 471 |
| [awesome-jev](https://github.com/cobanov/awesome-jev) | A curated, source-backed list of projects built with Jev, TypeSafe AI's System One model for typed decisions. |  | ⭐ 382 |
| [awesome-jev (AnotiaWang)](https://github.com/AnotiaWang/awesome-jev) | A curated list of awesome Jev / TypeSafe System One applications, libraries, and resources. |  | ⭐ 342 |
| [awesome-jev (OmniJev)](https://github.com/OmniJev/awesome-jev-gallery) · [site](https://omnijev.github.io/awesome-jev/) | Papers, open reproductions and independent evaluations behind System One models and Jev. | JavaScript | ⭐ 286 |
| [awesome-jev (kydlikebtc)](https://github.com/kydlikebtc/awesome-jev) · [site](https://kydlikebtc.github.io/awesome-jev/) | 805 verified examples of Jev — TypeSafe AI's System One decision model — indexed by the decision each one makes, not the blog that mentioned it. Every cited call site is re-read by CI each week. Bilingual EN/中文, JSON schema, and a cross-platform compatibility table. | Python | ⭐ 270 |
| [awesome-jev (fatwang2)](https://github.com/fatwang2/awesome-jev) | A source-backed Jev project directory with a reusable Jev-only GitHub review workflow. | JavaScript | ⭐ 204 |
| [awesome-jev (Amal-David)](https://github.com/Amal-David/awesome-jev) | Jev demos, projects, SDKs and skills, with source links and a curated X gallery. | Python | ⭐ 177 |
| [awesome-jev-use-cases](https://github.com/walidboulanouar/awesome-jev-use-cases) · [site](https://ayautomate.com/jev-builds) | Awesome list of TypeSafe AI Jev use cases: 74 demos ranked by likes, 150+ GitHub repos, limits, cost and API examples. CC0, sponsored by AY Automate. |  | ⭐ 146 |
| [awesome-jev-typesafe](https://github.com/valentynkit/awesome-jev-typesafe) · [site](https://awesomejev.vercel.app) | Typed decisions with TypeSafe's Jev, the first System One model | JavaScript | ⭐ 132 |
| [awesome-jev (kraayenjon)](https://github.com/kraayenjon/awesome-jev) · [site](https://madewithjev.com) | A curated list of Jev use cases, projects, SDKs, and resources. Jev is TypeSafe AI's System One model for fast, typed decisions in software — Choice, Score, and Noul with calibrated probabilities. |  | ⭐ 130 |
| [awesome-jev (AppitStudio)](https://github.com/AppitStudio/awesome-jev) | Curated Jev resources and runnable examples for typed AI decisions. | Python | ⭐ 83 |
| [awesome-jev-zh](https://github.com/yzfly/awesome-jev-zh) · [site](https://code.jiangshu.ai/awesome-jev-zh/) | Jev / TypeSafe System One 中文精选列表：官方资料、SDK、爆款应用、Agent 工具、开源复现与独立评测，附中文上手指南，每日自动收录 GitHub 热门项目。 | HTML | ⭐ 70 |
| [awesome-jev (BeatAPI)](https://github.com/BeatAPI/awesome-jev) · [site](https://beatapi.io/awesome-jev) | We only curate source-reviewed JEV-related projects with 100+ GitHub stars — integrations, tools, open models, and experiments. Live gallery: beatapi.io/awesome-jev | JavaScript | ⭐ 55 |
| [awesome-jev-live](https://github.com/wh000wh000/awesome-jev-live) · [site](https://wh000wh000.github.io/awesome-jev-live/) | Awesome Jev — evidence-graded index of TypeSafe System One: SDKs, MCP tools, agents, apps and open models. 20 languages, rebuilt every 2 hours. | Python | ⭐ 23 |
| [jev-hub](https://github.com/mizzlelover/jev-hub) · [site](https://mizzlelover.github.io/jev-hub/) | JEV HUB · X 上关于 TypeSafe AI「系统一模型」Jev 的长文与演示视频聚合（保留原链与作者）｜ 谁是专家 出品 | CSS | ⭐ 23 |
| [jev-radar](https://github.com/everyinfra/jev-radar) | 📡 全网最全 · The world's most comprehensive tracker of the Jev (TypeSafe AI System One) ecosystem — 220+ documented cases · 108 confidence-graded entries · verified & rescanned every 3 hours · API access guide included |  | ⭐ 22 |
| [awesome-jev-usecases (aliaihub)](https://github.com/aliaihub/awesome-jev-usecases) | Evidence-backed use cases, patterns, and guidance for building with Jev, TypeSafe AI's System One model. Every claim is labeled and sourced. |  | ⭐ 18 |
| [awesome-jev-usecases](https://github.com/anandi1989/awesome-jev-usecases) · [site](https://anandi1989.github.io/awesome-jev-usecases/) | Evidence-backed index of real-world Jev (TypeSafe AI System One) use cases: repos, patterns, benchmarks, and measured results |  | ⭐ 17 |
| [awesome-jev (Frank-ZY-Dou)](https://github.com/Frank-ZY-Dou/awesome-jev) | Public examples of Jev used for robot control, 3D modeling and adjacent control tasks, with sources and archived media |  | ⭐ 14 |
| [awesome-jev (tanxarx)](https://github.com/tanxarx/awesome-jev) | All things awesome related to Jev |  | ⭐ 13 |
| [awesome-jev (MrJev)](https://github.com/MrJev/awesome-jev) · [site](https://mrjev.com/projects/) | Selective list behind a 10-star bar, with hands-on reviews at mrjev.com recording what each tool sends and where. | Python | ⭐ 10 |
| [awesome-jev (ckaraca)](https://github.com/ckaraca/awesome-jev) · [site](https://docs.typesafe.ai/) | A curated list of tools, integrations, and experiments built on Jev, TypeSafe AI's System One model for fast, typed decisions. | Python | ⭐ 9 |
| [fable-jev](https://github.com/imMamdouhaboammar/fable-jev) | ⚡ Sub-100ms cognitive reflexes for autonomous coding agents. Powered by TypeSafe AI's Jev & get-fable. | TypeScript | ⭐ 9 |
| [awesome-jev (daftAI2026)](https://github.com/daftAI2026/awesome-jev) · [site](https://awesomejev.cc) | TypeSafe System One / Jev community directory — GitHub projects & posts around typed decisions (typesafe.ai) | TypeScript | ⭐ 6 |
| [awesome-jev (onmyway133)](https://github.com/onmyway133/awesome-jev) · [site](https://onmyway133.com) | Awesome projects built with Jev from Typesafe AI |  | ⭐ 6 |
| [awesome-jev (Li-Evan)](https://github.com/Li-Evan/awesome-jev) · [site](https://li-evan.github.io/awesome-jev/) | The most complete gallery of what people build with Jev, TypeSafe's System One model: 3,400+ projects, demos, and write-ups by scenario, each with its original link, image, and description. | HTML | ⭐ 5 |
| [awesome-jev-robustness](https://github.com/Yifan-Lan/awesome-jev-robustness) | Tests, calibration audits and failure-mode studies of Jev (TypeSafe System One): jaggedness, consistency, injection, abstention. |  | ⭐ 5 |

## Articles & threads

Coverage, write-ups, and X threads.

| Resource | Description |
| --- | --- |
| [AI that does not talk](https://ziplyne.agency/blog/ai-that-doesnt-talk-typesafe-jev-guide) | Practical guide: playground, Python and JS SDKs, raw HTTP, and the agent skill. |
| [AIAvatarKit turn-end gate](https://x.com/uezochan/status/2100608556823388486) | Voice-dialog turn-end detection using Jev scores after speech. |
| [AINews: Jev, a System One Model that only decides](https://www.latent.space/p/ainews-jev-a-system-one-model-that) | Latent Space's launch-day roundup: over 100x faster and 200x cheaper than small frontier LLMs. |
| [Browser Use + Jev](https://x.com/gregpr07/status/2100411066966749359) | Gregor Zunic's flight-search demo with a dynamic DOM action space. |
| [Computer use built on Jev](https://x.com/awlevin/status/2100262612428894676) | Aaron Levin: 155x cheaper than Opus 5, about 20x faster, and it generalizes across operating systems. |
| [ConsoleChaosRacing driven by Jev](https://x.com/Maoku/status/2100611986358927627) | Racing UI wired to Jev driving decisions. |
| [DuckDB Jev classifier](https://x.com/hamiltonulmer/status/2100370557405667768) | DuckDB extension that classifies rows in CSV, Parquet, or DuckDB tables with Jev, about 10 seconds per 1,000 rows. |
| [Early Jev tools roundup](https://x.com/0xLogicrw/status/2100478725393686556) | Thread cataloguing the first wave of Jev tools: MCP servers, routers, reviewers, and browser agents. |
| [Ground Truth news-framing extension](https://x.com/jagenaujagenau/status/2100622352333574460) | Browser extension that classifies an article's framing, type, topic, and loaded language with Jev. |
| [Hacker News launch thread](https://news.ycombinator.com/item?id=49717558) | 1,800-point thread debating whether typed decisions replace LLM calls for classification, routing, and scoring. |
| [He says he co-invented ChatGPT. His new AI will not write a word](https://dev.to/gabrielanhaia/he-says-he-co-invented-chatgpt-his-new-ai-jev-wont-write-a-word-e3c) | dev.to walkthrough of the Vercel AI SDK evaluate integration. |
| [Hide posts on X with natural language](https://x.com/marcelpociot/status/2100520134481735729) | Marcel Pociot's browser extension that collapses posts based on a Jev judgment. |
| [Hook panel A/B tester](https://x.com/Vybhav/status/2100609472750047263) | Near-real-time scoring of TikTok and Instagram hooks against about 100 personas. |
| [Internal classifier field note](https://x.com/identityTorn/status/2100475121324728615) | Matched-precision comparison against a private fine-tuned classifier. |
| [Jev as an agent safety monitor](https://x.com/isNickMa/status/2100566407524344225) | Test report using Jev to check each agent action first: most attacks caught, almost no false blocks. |
| [Jev gomoku harness](https://x.com/VacekvVita/status/2100609341145465325) | Local tactics shrink 225 moves to about 40 candidates, then Jev picks among tiered options. |
| [Jev in 34 seconds](https://x.com/dwhitedesign/status/2100368024649769384) | Short video explainer of how Jev's typed-decision loop works. |
| [Jev in a Grammarly-style Mac app](https://x.com/nielsmouthaan/status/2100543809465577665) | Desktop writing app using Jev for fast structured writing judgments. |
| [Jev in Search: Three Practical Evaluations](https://zc277584121.github.io/rag/2026/09/22/jev-search-deep-evaluation.html) | Independent experiments on search stopping, memory reranking, and multi-hop relation selection, with implementation links and limitations including private data, unequal sample counts, and a simulated speed illustration. |
| [Jev plays Minecraft (r/accelerate)](https://reddit.com/r/accelerate/comments/1whk9oy/new_typesafe_ai_jev_model_playing_minecraft_wip/) | Work-in-progress demo of Jev driving Minecraft, including fleeing zombies at night. |
| [Jev Typewriter launch](https://x.com/stevekrouse/status/2100287368221659289) | Steve Krouse's playable 16-judgment demo and video. |
| [Jev vs Mistral and Gemini for event validation](https://nearhere.events/blog/typesafe-jev-mistral-gemini-event-validation) | Head-to-head test at validating local event listings, with cost and latency. |
| [Jev vs Qwen on Cerebras](https://x.com/iamMrDuncan/status/2100467548298899918) | Video comparison against a structured-output LLM baseline. |
| [jev 同士に五目並べで対戦させた](https://zenn.dev/mizchi/articles/jev-plays-gomoku) | Jev vs Jev gomoku with source and timing logs. |
| [jev-rabbit PR review bot](https://x.com/thekitze/status/2100616530275029139) | Work-in-progress PR reviewer with plain-English Jev rules. |
| [Jev: System One models explained](https://www.theneuron.ai/explainer-articles/typesafe-jev-system-one-models-explained/) | The Neuron's explainer on AI decisions without a chatbot. |
| [Jev: System One models explained (DataCamp)](https://www.datacamp.com/blog/system-one-models-jev) | Third-party write-up of the System One primitives, pricing, and vendor workflow evals. |
| [Jev: The Language Model That Will Not Talk](https://anthonymaio.substack.com/p/jev-the-language-model-that-wont) | Anthony Maio's essay on what a model that cannot generate text is for. |
| [Kalshi prediction-market bot](https://x.com/stablebun/status/2100614911898390589) | Jev trades 15-minute and 1-hour BTC, ETH, and SOL markets on Kalshi. |
| [Launch thread by Diogo Almeida](https://x.com/CompleteSkeptic/status/2099925682726002904) | TypeSafe's founder on why RLCD-trained decision models are a shorter path to value than chat models. |
| [Mini-Vibe Check: Jev judged everything I have written in 0.7 seconds](https://every.to/also-true-for-humans/mini-vibe-check-typesafe-s-jev-judged-everything-i-ve-written-in-0-7-seconds) | Every's Mike Taylor runs his whole archive through Jev. |
| [Model router built with Jev](https://x.com/ephraimduncan/status/2100454070536351824) | Ephraim Duncan's demo where Jev decides which model should serve a request. |
| [Model router CLI](https://x.com/nidhisinghattri/status/2100617830890885415) | Task plus subscription list in, Jev picks which model or agent should handle it. |
| [One judge call vs twelve dimension scores](https://agentjournal.dev/blog/llm-judge-vs-feature-extraction/) | One direct Jev question per row against 12–14 Jev-scored dimensions with locally fitted weights on three classification tasks: 5,477 test rows, 25,174 Jev calls, $1.43. Decomposition wins on Japanese NLI (0.9076 vs 0.8373) but flags about 25× more hard benign rows as attacks (37.2% vs 1.5%). |
| [OpenCode browser use powered by Jev](https://x.com/thdxr/status/2100288951978164647) | Preview of fast browser use with Jev and OpenCode's browser CLI. |
| [SEO audit cost study driven by Jev triage](https://boringtoolskit.com/blog/seo-audit-cost-2026/) | Technical SEO audit cost study from Boring Tools Kit where Jev ranks striking-distance fixes and content gaps by calibrated probability. |
| [skillbox + Jev skill routing](https://x.com/thekitze/status/2100556122570792999) | MCP skill router where Jev picks the relevant skills instead of a long agent search. |
| [Spanish AEPD corpus test](https://x.com/juanmacias/status/2100463494629925048) | Jev versus a hand-built regex on 544 public data-protection resolutions: 98.2% agreement for about five cents. |
| [Stagehand + Jev browser use](https://x.com/kylejeong/status/2100622054945095934) | Observe the accessibility tree, Jev chooses the next action, Stagehand executes. |
| [StarCraft Brood War WASM MCP demo](https://x.com/literallydenis/status/2100622868878868603) | Brood War in WASM exposed as an MCP server, with Jev playing and still losing to a Zerg rush. |
| [Support ticket classifier](https://x.com/ifahimreza/status/2100616988746023102) | Jev labels category, urgency, and human-versus-auto handling for support tickets. |
| [Tabletop MMORPG action mapper](https://x.com/Jon_iy/status/2100397782322364792) | Eval of Jev turning free-text player intent into typed server actions: 96% agreement, 317 ms median. |
| [Typed decisions, not chat](https://warmersun.com/jev/) | Independent walkthrough separating TypeSafe's published claims from public evidence. |
| [TypeSafe AI debuts model for machines that plays Doom](https://www.theregister.com/ai-and-ml/2026/09/16/typesafe-ai-debuts-model-for-machines-that-plays-doom/5296711) | The Register on the launch, the Doom demo, and the $40M seed round. |
| [TypeSafe Jev: the first decision-only model class](https://www.developersdigest.tech/blog/typesafe-jev-system-one-models-release-guide-2026) | Release-week technical roundup: API, evals, adapter, and skill. |
| [TypeSafeのJevを正しく驚く](https://zenn.dev/nwn/articles/824026c76116e0) | Japanese walkthrough of what Jev is and is not. |
| [Vercel fx: Jev as a command safety reviewer](https://x.com/rauchg/status/2100307962262872105) | Guillermo Rauch: Jev reviews every fx command, faster and more accurate than a chat model. |
| [Verdict (Open-jev) launch thread](https://x.com/heman10x/status/2100836659533336676) | Hemant Kumar on his 151M ModernBERT reproduction: 0.83% adaptive calibration error, 3.0% of predictions flip when the option list is reversed, 35.6ms on CPU, with the failed use cases reported alongside the wins. |
| [ViZDoom Jev agent](https://x.com/kmad/status/2100339921714323624) | Two decision channels on ViZDoom, navigation at 5 Hz and combat at 12 Hz, with an 18-kill test run. |
| [What is Jev?](https://mohammedshehu.com/jev-typesafe-ai/) | Short practical intro with a Python ticket-triage example. |
| [Wiki-link clicker demo](https://x.com/mark1nhu/status/2100620075090792490) | Page-level demo where Jev picks which candidate link to click toward a goal. |

## Jev for marketing

Content, ads, brand visibility, and growth experiments.

| Project | Description | Language | Stars |
| --- | --- | --- | ---: |
| [notra](https://github.com/usenotra/notra) · [site](https://www.usenotra.com/) | Marketing analytics platform whose feature flag routes brand-visibility classifiers off an LLM and onto Jev boolean decisions. | TypeScript | ⭐ 215 |
| [jev-seo](https://github.com/AkashPriyadarshii/jev-seo) · [site](https://akashpriyadarshii.github.io/jev-seo/) | 100% free ₹0 agent-first SEO & GEO CLI suite and MCP server in Rust replacing Semrush and OpenSEO via DuckDuckGo and TypeSafe Jev System One | Rust | ⭐ 47 |
| [draftpulse](https://github.com/pekth/draftpulse) | Experimental: live X draft viral scorer powered by TypeSafe Jev | TypeScript | ⭐ 1 |
| [Finding what makes content work](https://x.com/iannuttall/status/2100668908227162567) | An author-reported experiment using Jev to classify past X posts by topic, hook, and tone, then compare those attributes with engagement. A content-research experiment, not a standalone app or a guarantee of growth. |  |  |
| [StealAds · ad intelligence](https://x.com/TheMattBerman/status/2100654891756589230) | A demonstrated Jev workflow for breaking down competitor ads by hook, format, offer, CTA, and landing-page fit. The creator announced plans to bring the workflow to StealAds and MCP; current availability has not been verified. |  |  |
| [SuperX · post scoring](https://superx.so) | A reported Jev workflow that evaluates draft X posts across multiple questions, helping creators compare and refine their writing before publishing. |  |  |

## Jev for robotics

Explore simulated robot arms, drones, rovers, and driving experiments using typed Jev decisions. These are research demos, not real-world deployment claims.

| Project | Description | Language | Stars |
| --- | --- | --- | ---: |
| [embodied-jev](https://github.com/FBddcz/embodied-jev) | EmbodiedJev: MuJoCo robot decision workbench with MiniCPM5-2B, Jev and compatible model APIs | Python | ⭐ 221 |
| [jev-drone](https://github.com/RomanSlack/jev-drone) · [site](https://jev-drone.vercel.app) | Camera-only autonomous drone in MuJoCo with a small judgment model (TypeSafe Jev) in the loop at 2.5Hz | Python | ⭐ 170 |
| [jev-libero](https://github.com/Dimweaker/jev-libero) · [site](https://dimweaker.github.io/jev-libero/) | Fine-grained robot control with Jev, physics previews, and configurable LIBERO tasks. | Python | ⭐ 64 |
| [Jev Driving Lab](https://github.com/kavehmz/typesafe-playground) | Interactive experiments from support routing to a 3D driving simulation: structured sensor state in, typed steer, brake, and overtake decisions out. | JavaScript | ⭐ 13 |
| [jev-autopilot](https://github.com/arielweinberger/jev-autopilot) | This demo uses Jev from TypeSafe AI to autonomously fly a drone in a random city from point A to point B, avoiding obstacles along the way. A trip costs $0.01. | TypeScript | ⭐ 10 |
| [rover-claude-jev-demo](https://github.com/Devonance/rover-claude-jev-demo) | Just a weekend project with Claude as system two, and Jev as system One. | JavaScript | ⭐ 2 |
| [Jev robot control](https://github.com/openroboto-ai/jev-robot-control) | A MuJoCo xArm7 pick-and-place experiment. Jev selects an intent and bounded Cartesian directions; the shared controller applies motion and checks physical feedback. The published comparison is one recorded trial per controller, not a success-rate benchmark. | Python | ⭐ 0 |
| [Jev vs LLM robot arm](https://github.com/FazalAAli/jev-robotics-demo) | A simulated Franka arm stacks cubes in MuJoCo. Code previews candidate moves in physics; Jev chooses a move and judges grasp, release, and completion. The README reports one recorded run for each controller. | Python | ⭐ 0 |
| [roverlab](https://github.com/juancamiloqhz/roverlab) | A 3D planetary rover sandbox for experimenting with autonomous decisions using TypeSafe AI. | TypeScript | ⭐ 0 |

## Jev alternatives & open source

Independent projects exploring Jev-style typed decisions with open models or local and self-hosted runtimes. Maturity, licensing, and reported results vary by project.

| Project | Description | Language | Stars |
| --- | --- | --- | ---: |
| [SemIf](https://github.com/TheoLeeCJ/SemIf-OpenJev) · [site](https://openjev.com) | Semantic ifs from open models, on a 3090 at home. Independent; not affiliated with Jev or TypeSafe. | Python | ⭐ 4.2k |
| [von](https://github.com/wfzyx/von) | The open-source System One decision model. Sub-15ms, non-autoregressive, local drop-in alternative to TypeSafe Jev. | Python | ⭐ 610 |
| [AnyJev](https://github.com/nokia-applied-research/AnyJev) · [site](https://pypi.org/project/anyjev/) | Turn any LLM into a Jev-style decision model: typed decisions, real probabilities, no training. (continue updating) | Python | ⭐ 440 |
| [openJev-verdict-2.0](https://github.com/Heman10x-NGU/openJev-verdict-2.0) · [site](https://heman10x-ngu.github.io/openJev-verdict-2.0/) | Calibrated 151M Non-Autoregressive Decision Engine beating TypeSafe Jev & Laya on LocalLLaMA/typed-decisions (77.10% acc, 0.0636 Brier, 0.0144 ECE) | Python | ⭐ 283 |
| [open-jev (daseinlabs)](https://github.com/daseinlabs/open-jev) | One-pass option scoring with a local Gemma 3 4B on Apple silicon via MLX, inspired by jevlike, with a Doom demo. | Python | ⭐ 107 |
| [Verdict-open-jev](https://github.com/Heman10x-NGU/Verdict-open-jev) · [site](https://huggingface.co/heman10x/rlcd-modernbert-151m) | Non-autoregressive decision engine on ModernBERT (151M) with calibrated uncertainty (RLCD), TypeSafe AI Jev benchmark audit, and in-browser WebGPU playground | Python | ⭐ 94 |
| [jevk5](https://github.com/allebee/jevk5) · [site](https://huggingface.co/alibiserikbay/JevK5) | JevK5: open-weight alternative to TypeSafe Jev. Typed decisions with probabilities in one forward pass; Apache-2.0 weights and code. | Python | ⭐ 64 |
| [open-alternative-jev](https://github.com/ikermoel/open-alternative-jev) · [site](https://huggingface.co/spaces/IkerMoel/open-alternative-jev) | Open alternative to Jev: typed, calibrated decisions from any open-weights LLM in one forward pass (HF + vLLM), with benchmarks | Python | ⭐ 53 |
| [open-jev-typed-decision-engine](https://github.com/intikhab49/open-jev-typed-decision-engine) | Open reproduction of TypeSafe Jev: a 150M typed decision engine (noul/choice/score in one non-autoregressive pass, calibrated confidence). 0.697 vs Jev's 0.727, 2.5x better calibrated, 4x faster, free. Trains on a Colab T4 in 30 min. | Python | ⭐ 43 |
| [open-jev (JoshuaSP)](https://github.com/JoshuaSP/open-jev) | Typed JSON inference with DiffusionGemma, with Every and Jev benchmark results | Python | ⭐ 39 |
| [jev_local](https://github.com/Argos1111/jev_local) | Replicating Jev with a local LLM | Python | ⭐ 35 |
| [system-one-open](https://github.com/mithalouni/system-one-open) | Open replica of TypeSafe's Jev: typed calibrated decisions in one forward pass, on Gemma 4 E2B / Gemma 3 270M (Modal) | Python | ⭐ 35 |
| [openjev (zhihz)](https://github.com/zhihz/openjev) | Local bilingual probability decisions from context, questions, and candidate answers. Independent research preview inspired by TypeSafe Jev. | Python | ⭐ 33 |
| [sys1](https://github.com/alvarobartt/sys1) | System One compatible API for open decision models, e.g. Laya, written in Rust. | Rust | ⭐ 31 |
| [OpenJev (zhangcy122)](https://github.com/zhangcy122/OpenJev) | OpenJev: Open-source alternative to TypeSafe Jev. Typed probabilistic decision API (Choice, Noul, Score) powered by open LLMs & constrained logprob calibration. | HTML | ⭐ 26 |
| [openvons](https://github.com/genai-craft/openvons) · [site](https://genai-craft.com) | openvons (open-Jev): 有限選択肢に確率で答える判断層 — テキスト / 画像 / 日本語音声コマンド | Python | ⭐ 13 |
| [local-jev](https://github.com/amithgc/local-jev) | A local, offline System One server compatible with TypeSafe's Jev API. It answers typed yes/no, category and score questions with small open models. | Python | ⭐ 8 |
| [Kev](https://github.com/arjun988/Kev) · [site](https://kev-notjev.vercel.app/) | Open-source System One decision engine. Typed choice / score / noul with calibrated probabilities. Self-host with Ollama or any OpenAI-compatible model. Apache-2.0. | TypeScript | ⭐ 7 |
| [system-one-gemma](https://github.com/akash-kamat/system-one-gemma) | Open-source Jev-style System One decision model. Gemma 3 270M with a scoring head — fast, calibrated decisions in a single forward pass. No text generation. Inspired by TypeSafe.ai's Jev. | Python | ⭐ 4 |
| [ollaya](https://github.com/ollaya-dev/ollaya) · [site](https://ollaya.cobanov.dev) | Run open decision models locally — pull, run and serve Laya and other open Jev alternatives behind a TypeSafe-compatible API. | Rust | ⭐ 1 |
| [system-one (mpuig)](https://github.com/mpuig/system-one) · [site](https://mpuig.github.io/system-one/) | An open-source System One decision model — Kahneman's term for the fast, automatic judgment faculty. Calibrated choice/score/noul probabilities in one forward pass on small fine-tuned open models. Local on Apple Silicon (MLX), Jev-compatible API, audited experiment log. | Python | ⭐ 1 |

## Contributing

Know a project that belongs here? Submit it at [jevlibrary.dev](https://jevlibrary.dev) or open an issue / pull request.
