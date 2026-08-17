# Awesome Temporal with stars

[<img src="temporal.png" align="right" width="200">](https://temporal.io/)

> A curated list of awesome Temporal libraries and resources, from both Temporal Technologies and the community. Community links are not endorsed, affiliated, or maintained by Temporal Technologies Inc. Pull requests welcome!

Temporal is a [durable execution system](https://youtu.be/W0Ygep6iCJY?t=609). It makes code fault-tolerant and simple.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

## Contents

* [Related awesome lists](#related-awesome-lists)
* [Communities](#communities)
* [Libraries](#libraries)
* [Tools](#tools)
  * [Terraform Providers](#terraform-providers)
* [Frameworks](#frameworks)
* [Samples](#samples)
* [Training Courses](#training-courses)
* [Videos](#videos)
  * [Why Temporal](#why-temporal)
  * [Using Temporal](#using-temporal)
* [Podcasts](#podcasts)
* [Blog posts](#blog-posts)
  * [Why Temporal](#why-temporal-1)
  * [Using Temporal](#using-temporal-1)
* [Go](#go)
  * [Samples](#samples-1)
  * [Libraries](#libraries-1)
  * [Tutorials](#tutorials)
  * [Blog posts](#blog-posts-1)
  * [Videos](#videos-1)
* [TypeScript](#typescript)
  * [Samples](#samples-2)
  * [Libraries](#libraries-2)
  * [Tutorials](#tutorials-1)
  * [Blog posts](#blog-posts-2)
  * [Videos](#videos-2)
* [Java](#java)
  * [Samples](#samples-3)
  * [Libraries](#libraries-3)
  * [Tutorials](#tutorials-2)
  * [Blog posts](#blog-posts-3)
  * [Videos](#videos-3)
* [Python](#python)
  * [Samples](#samples-4)
  * [Libraries](#libraries-4)
  * [Tutorials](#tutorials-3)
  * [Blog posts](#blog-posts-4)
  * [Videos](#videos-4)
* [.NET](#net)
  * [Samples](#samples-5)
  * [Libraries](#libraries-5)
  * [Tutorials](#tutorials-4)
  * [Blog posts](#blog-posts-5)
  * [Videos](#videos-5)
* [PHP](#php)
  * [Samples](#samples-6)
  * [Libraries](#libraries-6)
  * [Tutorials](#tutorials-5)
  * [Blog posts](#blog-posts-6)
  * [Videos](#videos-6)
* [Ruby](#ruby)
  * [Samples](#samples-7)
  * [Libraries](#libraries-7)
  * [Tutorials](#tutorials-6)
  * [Blog posts](#blog-posts-7)
* [Rust](#rust)
* [Clojure](#clojure)
* [Elixir](#elixir)
* [Erlang](#erlang)
* [Haskell](#haskell)
* [Built with Temporal](#built-with-temporal)
* [Credits](#credits)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Related awesome lists

* [All lists](https://github.com/sindresorhus/awesome) ⭐ 496,753 | 🐛 100 | 📅 2026-06-30
* [Microservices](https://github.com/mfornos/awesome-microservices#readme) ⭐ 14,481 | 🐛 20 | 📅 2026-06-10
* [Distributed systems](https://github.com/madd86/awesome-system-design) ⭐ 12,420 | 🐛 19 | 📅 2026-02-27
* [Software architecture](https://github.com/simskij/awesome-software-architecture#readme) ⭐ 2,864 | 🐛 1 | 📅 2026-04-19
* [Queues](https://github.com/tonyhb/awesome-queues-jobs-and-tasks/) ⭐ 17 | 🐛 1 | 📅 2023-03-22
* Languages we have SDKs in:
  * [Python](https://github.com/vinta/awesome-python#readme) ⭐ 314,389 | 🐛 15 | 🌐 Python | 📅 2026-08-16
  * [Go](https://github.com/avelino/awesome-go#readme) ⭐ 181,277 | 🐛 212 | 🌐 Go | 📅 2026-08-16
  * [Node](https://github.com/sindresorhus/awesome-nodejs#readme) ⭐ 66,539 | 🐛 26 | 📅 2026-05-03
  * [Rust](https://github.com/rust-unofficial/awesome-rust#readme) ⭐ 58,863 | 🐛 7 | 🌐 Rust | 📅 2026-08-17
  * [Java](https://github.com/akullpp/awesome-java#readme) ⭐ 48,755 | 🐛 7 | 📅 2026-08-17
  * [JavaScript](https://github.com/sorrycc/awesome-javascript#readme) ⭐ 35,019 | 🐛 28 | 📅 2026-08-17
  * [PHP](https://github.com/ziadoz/awesome-php#readme) ⭐ 32,652 | 🐛 83 | 📅 2026-07-13
  * [.NET](https://github.com/quozd/awesome-dotnet#readme) ⭐ 21,560 | 🐛 138 | 📅 2026-03-26
  * [Ruby](https://github.com/markets/awesome-ruby#readme) ⭐ 14,140 | 🐛 8 | 📅 2026-08-13
* Databases we support:
  * [Postgres](https://github.com/dhamaniasad/awesome-postgres#readme) ⭐ 12,048 | 🐛 66 | 📅 2026-05-21
  * [MySQL](https://github.com/shlomi-noach/awesome-mysql#readme) ⭐ 2,604 | 🐛 21 | 🌐 Python | 📅 2026-07-14
  * [Cassandra](https://github.com/Anant/awesome-cassandra#readme) ⚠️ Archived

## Communities

* [Slack](https://t.mp/slack)
* [Forum](https://community.temporal.io/)
* [r/Temporal](https://www.reddit.com/r/Temporal/)
* [Stack Overflow](https://stackoverflow.com/questions/tagged/temporal-workflow+or+temporal-typescript)

## Libraries

* [`tsurdilo/swtemporal`](https://github.com/tsurdilo/swtemporal) ⭐ 99 | 🐛 4 | 🌐 JavaScript | 📅 2023-09-28 - Use the [Serverless Workflow DSL](https://serverlessworkflow.io/).

## Tools

* [`alexandrevilain/temporal-operator`](https://github.com/alexandrevilain/temporal-operator) ⭐ 228 | 🐛 65 | 🌐 Go | 📅 2026-03-29 - Kubernetes operator to deploy and manage Temporal Clusters.
* [`rross/temporal-cloud-run`](https://github.com/rross/temporal-cloud-run) ⭐ 28 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-19 - Pulumi scripts for creating and configuring a Google Cloud Project and using Cloud Build to deploy a Temporal worker and the Open Telemetry Connector in Cloud Run
* [`northpowered/temporal-rest-executor`](https://github.com/northpowered/temporal-rest-executor) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2023-09-28 - Simple REST server (with Swagger UI) to execute any activity/workflow in Temporal namespace. Useful for development and I\&T.
* [`Krishnachaitanyakc/temporal-postgres-visibility`](https://github.com/Krishnachaitanyakc/temporal-postgres-visibility) ⭐ 0 | 🐛 0 | 🌐 PLpgSQL | 📅 2026-07-11 - Reduces PostgreSQL Visibility index bloat by converting unused Search Attribute indexes on `executions_visibility` to partial indexes, with a REINDEX and autovacuum runbook.
* [`tempo`](https://miketoscano.com/tempo/) - Tempo is an app available for iOS, Android, and Linux for monitoring, searching, debugging, and managing Temporal Workflows, schedules, and batch operations.

### Terraform Providers

* [`platacard/terraform-provider-temporal`](https://github.com/platacard/terraform-provider-temporal) ⭐ 35 | 🐛 10 | 🌐 Go | 📅 2026-08-13 - Terraform provider to manage Temporal Server resources.
* [`temporalio/terraform-provider-temporalcloud`](https://github.com/temporalio/terraform-provider-temporalcloud) ⭐ 25 | 🐛 30 | 🌐 Go | 📅 2026-08-13 - Terraform Provider for Temporal Cloud

## Frameworks

* [iWF](https://github.com/indeedeng/iwf) ⭐ 656 | 🐛 79 | 🌐 Go | 📅 2026-07-12 - DSL workflow framework built on Temporal.
* [Output](https://github.com/growthxai/output) ⭐ 431 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-17 - AI Agents & Workflows with versioned prompts, evals, tracing, and credentials in one TypeScript framework built on Temporal.
* [awaithumans](https://github.com/awaithumans/awaithumans) ⭐ 22 | 🐛 11 | 🌐 Python | 📅 2026-08-11 - HITL primitive for AI agents. One function call (`await_human` / `awaitHuman`) suspends the workflow until a real person reviews via Slack, email, or a built-in dashboard, then resumes with the typed response. The Temporal adapter uses signals to park the workflow while it waits — durable across worker restarts. Python + TypeScript SDKs, Apache 2.0.

## Samples

Multi-language or language-agnostic samples. (For samples in a specific lang, see the Samples subsection of the lang's section.)

* [`temporalio/temporal-polyglot`](https://github.com/temporalio/temporal-polyglot) ⭐ 53 | 🐛 7 | 🌐 PHP | 📅 2026-07-28 - Workflows in one lang signaling Workflows or starting Activities written in other langs.
* [`temporalio/temporal-pendulum`](https://github.com/temporalio/temporal-pendulum) ⭐ 18 | 🐛 8 | 🌐 Java | 📅 2026-02-05 - Switch between equivalent Workflows written in Go, Java, TS, and PHP.

## Training Courses

* [Temporal 101: Introducing the Temporal Platform](https://learn.temporal.io/courses/temporal_101/)
* [Temporal 102: Exploring Durable Execution](https://learn.temporal.io/courses/temporal_102/)
* [Crafting an Error Handling Strategy](https://learn.temporal.io/courses/errstrat/)
* [Versioning Workflows](https://learn.temporal.io/courses/versioning/)
* [Interacting with Workflows](https://learn.temporal.io/courses/interacting_with_workflows/)
* [Introduction to Temporal Cloud](https://learn.temporal.io/courses/intro_to_temporal_cloud/)

## Videos

### Why Temporal

* [Replay Keynote](https://www.youtube.com/watch?v=W0Ygep6iCJY) - Durable execution, Nexus, and Cloud.
* [Glovo: Fault tolerant distributed microservices with Temporal](https://youtu.be/6lSuDRRFgyY)
* [TheDevConf: Fault Tolerant, Distributed Microservices Orchestration with Temporal](https://www.youtube.com/watch?v=6T6zVZHU7_Q) - The problem Temporal solves and how it works ([slides](https://temporal-intro-and-demo.netlify.app/)).
* [State of Affairs or Affairs of State](https://www.youtube.com/watch?v=2P_aXee2qh4) - Stateless vs stateful architecture and why Temporal.
* [Designing a Workflow Engine from First Principles](https://temporal.io/blog/workflow-engine-principles/) - The internal system design of Temporal Server and how it solves consistency and scaling issues with workflow engines.
* [Sidekiq, Outbox, SAGAs and Best Practices for Distributed Transactions!](https://www.youtube.com/watch?v=Rr4DnHmy6eE)

### Using Temporal

* [A Guided Tour of Temporal’s New Web UI](https://www.youtube.com/watch?v=iCT4mml8mdM)
* [Time Travel Tests! Testing Async Workflows, Signals, and Queries with Temporal](https://www.youtube.com/watch?v=-GKxFDQSlEU)
* [Temporal Service and Application Architecture](https://youtu.be/r5bnp5bQHI4)
* [How to get workflow failure info using Temporal SDKs](https://www.youtube.com/watch?v=0QuWgqwmr-s)
* [Keeping Workflow Developers Afloat](https://www.youtube.com/watch?v=yeoawVIn060)
* [Temporal @ Datadog](https://www.youtube.com/watch?v=LxgkAoTSI8Q)
* [Workflow versioning](https://www.youtube.com/watch?v=kkP899WxgzY)
* [Polyglot Microservices Orchestration](https://www.youtube.com/watch?v=LSXP_o6sTic)

## Podcasts

* [Flagsmith](https://flagsmith.com/podcast/temporal-w-co-founder-and-ceo-maxim-fateev-and-head-of-product-ryland-goldstein/) - Maxim & Ryland explain Temporal and answer questions (50 min, Jun 19, 2022).
* [Stack Overflow Podcast: Run your microservices in no-fail mode](https://twitter.com/StackOverflow/status/1536740460789739520) - Maxim & Dominik explain Temporal (22 min, Jun 14, 2022).
* [Serverless Chats Podcast: Self-Provisioning Runtimes](https://www.serverlesschats.com/124/) - swyx presents Temporal as a self-provisioning runtime (1h, Feb 14, 2022).
* [Break Things on Purpose (Gremlin): Origin story, Choreography vs Orchestration, and Tips](https://temporal.io/blog/gremlin-podcast) - Maxim & Samar share the Temporal origin story (21 min, Oct 5, 2021).
* [JS Party: Temporal is like React for the backend](https://changelog.com/jsparty/208)

## Blog posts

### Why Temporal

* [Temporal - the iPhone of System Design](https://www.swyx.io/why-temporal)
* [Stack Overflow Blog: The macro problem with microservices](https://stackoverflow.blog/2020/11/23/the-macro-problem-with-microservices/)
* [Snap Engineering: Build a Reliable System in a Microservices World](https://eng.snap.com/build_a_reliable_system_in_a_microservices_world_at_snap)
* [Dealing with failure](https://temporal.io/blog/dealing-with-failure) - RPCs vs queues vs workflows.
* [Inversion of Execution](https://temporal.io/blog/sergey-inversion-of-execution)

### Using Temporal

* [A Practical Approach to Temporal Architecture](https://mikhail.io/2020/10/practical-approach-to-temporal-architecture/)
* [Introduction to Temporal Workflows](https://temporal.io/blog/dominik-workflow-part-1)
* [Failure Handling in Practice](https://temporal.io/blog/failure-handling-in-practice)
* [The 4 Types of Activity Timeouts](https://temporal.io/blog/activity-timeouts)
* [What does "Long Running" really mean?](https://temporal.io/blog/long-running)
* [Productionizing Workers](https://temporal.io/blog/workers-in-production)
* [Defining Workflows](https://temporal.io/blog/defining-workflows) - Using DSLs vs code to define workflows.
* [Tips and Tricks for Temporal Developer Productivity](https://temporal.io/blog/temporal-tips-tricks-1)
* [Easily Manage Workflows at Scale with Temporal.io and Astra DB](https://www.datastax.com/blog/easily-manage-workflows-at-scale-with-temporal-io-and-astra-db)
* [Why Rust powers Temporal's new Core SDK](https://temporal.io/blog/why-rust-powers-core-sdk)

## Go

* [Go SDK](https://github.com/temporalio/sdk-go) ⭐ 947 | 🐛 233 | 🌐 Go | 📅 2026-08-14
* [Go SDK docs](https://t.mp/go)
* [Go SDK API reference](https://t.mp/go-api)

### Samples

* [`temporalio/samples-go`](https://github.com/temporalio/samples-go) ⭐ 748 | 🐛 52 | 🌐 Go | 📅 2026-08-06
* [Benthos PoC](https://github.com/disintegrator/benthos-temporal-poc) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2023-01-27 - Start a workflow from a Benthos message.
* [Background Check app](https://learn.temporal.io/examples/go/background-checks/)

### Libraries

* [agenticenv/agent-sdk-go](https://github.com/agenticenv/agent-sdk-go) ⭐ 47 | 🐛 2 | 🌐 Go | 📅 2026-08-17 - Temporal-first framework for building durable, production-grade AI agents in Go with native tools, MCP, human-in-the-loop approvals, and sub-agent delegation.
* [`Courtsite/temporal-go-helpers`](https://github.com/Courtsite/temporal-go-helpers) ⭐ 40 | 🐛 1 | 🌐 Go | 📅 2025-12-31 - Collection of helpers: saga, receive Signal with timeout, drain channel.
* [`hatchet-dev/hatchet-workflows`](https://github.com/hatchet-dev/hatchet-workflows) ⚠️ Archived - YAML DSL workflows.
* [`vikstrous/tempts`](https://github.com/vikstrous/tempts) ⭐ 21 | 🐛 3 | 🌐 Go | 📅 2026-04-17 - Opinionated and type-safe wrappers for the Go SDK.
* [`cito-oss/tempo`](https://github.com/cito-oss/tempo) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2026-05-18 - Run distributed Go-like tests using Temporal.
* [`saga420/temporal-encryption-converter`](https://github.com/saga420/temporal-encryption-converter) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2023-07-13 - The Temporal Encryption Converter is a Go package that provides secure communication and context propagation for the Temporal workflow engine, employing AES256\_GCM\_PBKDF2\_Curve25519 and XChaCha20\_Poly1305\_PBKDF2\_Curve25519 encryption algorithms and ZLib compression.
* [`zboralski/codecserver`](https://github.com/zboralski/codecserver) - Data Converter and Codec Server that uses Transit Secrets Engine from HashiCorp Vault.

### Tutorials

* [Getting started](https://learn.temporal.io/getting_started/go/dev_environment/)
* [eCommerce app](https://learn.temporal.io/tutorials/go/ecommerce/)

### Blog posts

* [Media processing workflows](https://temporal.io/blog/media-processing-workflows)
* [Writing a Workflow, Simulating Failures, Retries, and Testing](https://www.jcheng.org/post/workflow-orchestration-1.2/)
* [Passing Context with Temporal​](https://spiralscout.com/blog/passing-context-with-temporal)

### Videos

* [Intro to Temporal with Go SDK](https://www.youtube.com/watch?v=-KWutSkFda8)
* [Intro Workshop with Go](https://www.youtube.com/watch?v=UwdGmdTO3Ts)

## TypeScript

* [TypeScript SDK](https://github.com/temporalio/sdk-typescript) ⭐ 896 | 🐛 220 | 🌐 TypeScript | 📅 2026-08-17
* [TypeScript SDK docs](https://t.mp/ts)
* [TypeScript SDK API reference](https://t.mp/ts-api)

### Samples

* [`temporalio/samples-typescript`](https://github.com/temporalio/samples-typescript) ⭐ 462 | 🐛 63 | 🌐 TypeScript | 📅 2026-08-14

### Libraries

* [Cognosis AI Platform](https://github.com/cognosisai/platform) ⭐ 176 | 🐛 3 | 🌐 TypeScript | 📅 2023-02-04 - Template for large language model applications.
* [`lorensr/temporal-time-utils`](https://github.com/lorensr/temporal-time-utils) ⭐ 21 | 🐛 4 | 🌐 TypeScript | 📅 2022-09-09 - `sleepUntil` and `UpdatableTimer`.

### Tutorials

* [Getting started](https://learn.temporal.io/getting_started/typescript/dev_environment/)
* [Next.js](https://learn.temporal.io/tutorials/typescript/nextjs/)
* [Subscriptions](https://learn.temporal.io/tutorials/typescript/subscriptions/) - Write a Workflow that models a user's subscription, periodically charging them for your service.
* [Create a Slack bot](https://learn.temporal.io/tutorials/typescript/chatbot/)

### Blog posts

* [Building Reliable Distributed Systems in Node](https://temporal.io/blog/building-reliable-distributed-systems-in-node)
* [How Durable Execution Works](https://temporal.io/blog/building-reliable-distributed-systems-in-node-js-part-2)
* [Temporal for VS Code](https://temporal.io/blog/temporal-for-vs-code)
* [How to Use Node.js Temporal Workflows to Batch Process Operations](https://www.bitovi.com/blog/how-to-use-node.js-temporal-workflows-for-batch-processing)
* [Using Temporal as a Node.js Task Queue](https://temporal.io/blog/using-temporal-as-a-node-task-queue)
* [Caching API Requests with Long-Lived Workflows](https://temporal.io/blog/caching-api-requests-with-long-lived-workflows)
* [Express middleware that creates a REST API for your Workflows](https://temporal.io/blog/temporal-rest)
* [1.0.0 release of the Temporal TypeScript SDK](https://temporal.io/blog/typescript-1-0-0)
* [How we use V8 isolates to enforce Workflow determinism](https://temporal.io/blog/intro-to-isolated-vm)

### Videos

* [Glovo: Fault tolerant distributed microservices with Temporal](https://youtu.be/6lSuDRRFgyY)
* [Building Reliable Distributed Systems](https://www.youtube.com/watch?v=fZHL1k5iEmA) ([slides](https://docs.google.com/presentation/d/1x0ETmVVJcbluTSnJGo8F2sNL1GKJPwOh-2s53x_UKLg/))
* [Complete Intro to Temporal Workshop](https://www.youtube.com/watch?v=CeHSmv8oF_4)
* [Slack Bot Tutorial](https://youtu.be/hGIhc6m2keQ)

## Java

* [Java SDK](https://github.com/temporalio/sdk-java) ⭐ 428 | 🐛 276 | 🌐 Java | 📅 2026-08-13
* [Java SDK docs](https://t.mp/java)
* [Java SDK API reference](https://t.mp/java-api)

### Samples

* [`temporalio/samples-java`](https://github.com/temporalio/samples-java) ⭐ 258 | 🐛 44 | 🌐 Java | 📅 2026-08-12
* [`tsurdilo/temporal-springboot-demo`](https://github.com/tsurdilo/temporal-springboot-demo) ⭐ 47 | 🐛 0 | 🌐 Java | 📅 2026-01-02 - Spring Boot integration.

### Libraries

### Tutorials

* [Getting started](https://learn.temporal.io/getting_started/java/dev_environment/)

### Blog posts

### Videos

* [Intro to Temporal with Java SDK](https://youtu.be/1RY2lWSuJaA)
* [Java SDK Workshop](https://youtu.be/VoSiIwkvuX0)

## Python

* [Python SDK](https://github.com/temporalio/sdk-python) ⭐ 1,164 | 🐛 103 | 🌐 Python | 📅 2026-08-14
* [Python SDK docs](https://t.mp/py)
* [Python SDK API reference](https://t.mp/py-api)

### Samples

* [`temporalio/samples-python`](https://github.com/temporalio/samples-python) ⭐ 366 | 🐛 75 | 🌐 Python | 📅 2026-08-14
* [`aybruhm/ai-video-generation-poc-with-temporal`](https://github.com/aybruhm/ai-video-generation-poc-with-temporal) ⭐ 0 | 🐛 2 | 🌐 Python | 📅 2026-05-01 - A proof-of-concept for orchestrating an AI video generation pipeline (AI Provider → S3 → token deduction → DB) using Temporal workflows and activities with FastAPI.

### Libraries

* [`northpowered/temporal-boost`](https://github.com/northpowered/temporal-boost) ⭐ 44 | 🐛 1 | 🌐 Python | 📅 2025-11-01 - SDK-based framework for more comfortable development with Temporal. FastAPI-style workers, autogenerating documentation, logging and tracing and other.
* [Batch Orchestra](https://github.com/drewhoskins/batch-orchestra) ⭐ 23 | 🐛 7 | 🌐 Python | 📅 2026-08-14 - An easy-to-adopt library for scalable, reliable batch processing.  It features pagination, parallelism, and extended retries.

### Tutorials

### Blog posts

### Videos

* [Python SDK First Look](https://www.youtube.com/watch?v=jZgtiGgEK6A)

## .NET

* [.NET SDK](https://github.com/temporalio/sdk-dotnet) ⭐ 565 | 🐛 68 | 🌐 C# | 📅 2026-08-14
* [.NET SDK docs](https://dotnet.temporal.io/)

### Samples

* [`temporalio/samples-dotnet`](https://github.com/temporalio/samples-dotnet) ⭐ 113 | 🐛 23 | 🌐 C# | 📅 2026-08-14

### Libraries

* [Temporalio.Graphs](https://github.com/oleg-shilo/Temporalio.Graphs) ⭐ 33 | 🐛 0 | 🌐 C# | 📅 2025-02-26 - A NuGet package that can be used to generate a complete WF graph (DAG visualization) by running the WF in the mocked-run mode either during the build or at runtime.
* [InfinityFlow.Aspire.Temporal](https://github.com/InfinityFlowApp/aspire-temporal) ⭐ 30 | 🐛 12 | 🌐 C# | 📅 2026-06-15 - A [.NET Aspire](https://learn.microsoft.com/en-us/dotnet/aspire) package to work with `temporal` and start a dev server.

### Tutorials

### Blog posts

### Videos

## PHP

* [PHP SDK](https://github.com/temporalio/sdk-php) ⭐ 416 | 🐛 43 | 🌐 PHP | 📅 2026-08-17
* [PHP SDK docs](https://t.mp/php)
* [PHP SDK API reference](https://php.temporal.io)

### Samples

* [`temporalio/samples-php`](https://github.com/temporalio/samples-php) ⭐ 124 | 🐛 14 | 🌐 PHP | 📅 2026-06-13

### Libraries

* [RoadRunner](https://github.com/roadrunner-server/roadrunner) ⭐ 8,500 | 🐛 63 | 🌐 Go | 📅 2026-08-14 - PHP application server and process manager.

### Tutorials

* [Getting started](https://learn.temporal.io/getting_started/php/dev_environment/)
* [Saga](https://learn.temporal.io/tutorials/php/booking_saga/) - Write a saga Workflow.
* [Subscriptions](https://learn.temporal.io/tutorials/php/subscriptions/) - Write a Workflow that models a user's subscription, periodically charging them for your service.

### Blog posts

### Videos

* [Create Your First Workflow](https://youtu.be/goulj2CRNOY)
* [PHPKonf 2021: Fault tolerant workflow orchestration on PHP](https://www.youtube.com/watch?v=pdxHkIqX62A)

## Ruby

* [Ruby SDK](https://github.com/temporalio/sdk-ruby) ⭐ 202 | 🐛 35 | 🌐 Ruby | 📅 2026-08-14
* [Ruby SDK API reference](https://ruby.temporal.io)

### Samples

* [`temporalio/samples-ruby`](https://github.com/temporalio/samples-ruby) ⭐ 14 | 🐛 28 | 🌐 Ruby | 📅 2026-07-31

### Libraries

### Tutorials

### Blog posts

## Rust

* [Rust SDK](https://github.com/temporalio/sdk-rust) ⭐ 505 | 🐛 104 | 🌐 Rust | 📅 2026-08-14 - Currently in Public Preview.
* [`temporalio-sdk` crate](https://crates.io/crates/temporalio-sdk)
* [Rust SDK API reference](https://docs.rs/temporalio-sdk)

## Clojure

* [Clojure SDK](https://github.com/manetu/temporal-clojure-sdk) ⭐ 101 | 🐛 4 | 🌐 Clojure | 📅 2026-08-11

## Elixir

* [SDK GitHub repository](https://github.com/andrzej-mag/temporal_sdk) ⭐ 17 | 🐛 0 | 🌐 Erlang | 📅 2026-07-06
* [Samples GitHub repository](https://github.com/andrzej-mag/temporal_sdk_samples) ⭐ 3 | 🐛 0 | 🌐 Erlang | 📅 2026-06-18
* [SDK hex.pm package](https://hex.pm/packages/temporal_sdk)
* [SDK hexdocs documentation](https://hexdocs.pm/temporal_sdk)
* [Samples hexdocs documentation](https://hexdocs.pm/temporal_sdk_samples)

## Erlang

* [SDK GitHub repository](https://github.com/andrzej-mag/temporal_sdk) ⭐ 17 | 🐛 0 | 🌐 Erlang | 📅 2026-07-06
* [Samples GitHub repository](https://github.com/andrzej-mag/temporal_sdk_samples) ⭐ 3 | 🐛 0 | 🌐 Erlang | 📅 2026-06-18
* [SDK hex.pm package](https://hex.pm/packages/temporal_sdk)
* [SDK hexdocs documentation](https://hexdocs.pm/temporal_sdk)
* [Samples hexdocs documentation](https://hexdocs.pm/temporal_sdk_samples)

## Haskell

* [Haskell SDK](https://github.com/MercuryTechnologies/hs-temporal-sdk) ⭐ 69 | 🐛 39 | 🌐 Haskell | 📅 2026-08-14
* [Haskell SDK Cookbook](https://github.com/MercuryTechnologies/hs-temporal-cookbook) ⭐ 5 | 🐛 0 | 🌐 Haskell | 📅 2026-02-23

## Built with Temporal

* [Julep: Modern, Scalable, Resilient AI workflows](https://github.com/julep-ai/julep) ⭐ 6,596 | 🐛 3 | 🌐 Python | 📅 2026-08-06
* [Workflow Builder](https://github.com/synergycodes/workflowbuilder) ⭐ 332 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-17 - Embeddable, data-driven visual workflow editor SDK for React (Apache 2.0). The execution engine is swappable by design and proven with Temporal, giving you a working end-to-end reference for durable AI orchestration.
* [Open Responses: Self-hosted alternative to OpenAI's Responses API that works with any model](https://github.com/julep-ai/open-responses) ⭐ 228 | 🐛 4 | 🌐 Go | 📅 2025-04-02
* [Cron Atlas](https://github.com/pmbanugo/cron-atlas) ⭐ 72 | 🐛 4 | 🌐 TypeScript | 📅 2024-04-03 - Hit an HTTP endpoint on a schedule
* [Automating Temporal: A Full View of the Netflix Temporal Platform](https://community.temporal.io/t/automating-temporal-a-full-view-of-the-netflix-temporal-platform/13624) by @robzienert
* [Building a better Mouse Trap – web crawling with Temporal](https://javapro.io/2024/10/03/building-a-better-mouse-trap-web-crawling-with-temporal/) by @spoole167
* [PeerDB data synchronization](https://blog.peerdb.io/using-temporal-to-scale-data-synchronization-at-peerdb)

## Credits

We welcome contributions! See [`contributing.md`](contributing.md).

🙏 Thank you to:

* [All those who have contributed](https://github.com/temporalio/awesome-temporal/graphs/contributors) ⭐ 454 | 🐛 0 | 📅 2026-08-12
* [`firdaus`](https://github.com/firdaus) for [`firdaus/awesome-cadence-temporal-workflow`](https://github.com/firdaus/awesome-cadence-temporal-workflow) ⭐ 84 | 🐛 1 | 📅 2021-05-03

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-17._
