---
title: Programming
---

## Background
I'm a senior engineer specializing in knowledge graph systems, data pipelines, and AI agents. I design and build systems that make complex information legible and queryable — from graph-based data models to agentic workflows that reason over structured knowledge.

I began my career in the arts and media, working at fine arts galleries, an independent record label, live theatre, then a media distribution company. I started learning to code to [Automate the Boring Stuff](https://automatetheboringstuff.com/), which quickly led to a career as a software engineer, then data engineer, then technical lead. Ten years later, I'm building AI agents, graph APIs, and context stores in production.

## Programming Resume
- [View My Resume](https://github.com/nharsch/resume/blob/master/programming-resume.md)
- [Download My Resume](https://github.com/nharsch/resume/raw/master/NigelHarsch-resume-programming.pdf)

## My Skillset

### Core Strengths
- **Knowledge Graph Systems** - Graph data modeling, ontologies, Neo4j, property graphs, semantic search
- **AI Agents & Context Engineering** - MCP servers, agentic workflows, RAG pipelines, context stores
- **Data Pipelines & Architecture** - ETL design, event streaming, data warehouse, schema ownership
- **Technical Leadership** - Feature scoping, cross-functional communication, client ↔ engineering translation

### Proficiencies
- Graph / Data: Neo4j, PostgreSQL, Datascript, Kafka, Kinesis, SQS
- AI / Agents: MCP servers, Anthropic API, Pathom graph API, agentic workflows, LLMs
- Clojure/ClojureScript - HoneySQL, Ring, Reagent, Reframe, Pathom, Specter, Shadow-cljs
- Python - Django ecosystem (Oscar, Wagtail, DRF), data processing, automation
- JavaScript/Node - React, Redux, Next.js
- AWS - Lambda, ECS, RDS, S3, infrastructure design
- DevOps - Terraform, Docker, Kubernetes, CI/CD (GitLab/GitHub Actions)

## Projects
- **Redmine Viz**
  - Remote MCP server over Redmine/Plan.io: stateless Lambda backed by a Pathom graph API
  - Agents query tickets, projects, and members in a single round trip — eliminating N+1 tool calls and token bloat
  - Built with Clojure, Pathom, AWS Lambda
- **PERT Canvas**: [demo](https://nigelharsch.com/pert-canvas) - [repo](https://github.com/nharsch/pert-canvas)
  - Visualize project tasks as a live dependency graph, inspired by [PERT Charts](https://www.wikipedia.com/en/articles/Program_evaluation_and_review_technique)
  - Built with ClojureScript and [React Flow](https://reactflow.dev/)
- **JSON Schema Form Builder**: [demo](https://cedar-pine-consulting.github.io/json-form-builder/) - [repo](https://github.com/Cedar-Pine-Consulting/json-form-builder)
  - Drag and drop visual form builder on top of [RJSF](https://github.com/rjsf-team/react-jsonschema-form)
  - Built for a nonprofit client via Cedar Pine Consulting
- **[Mkdocs Semantic Search](https://github.com/nharsch/mkdocs-semantic-search/tree/main)**
  - Semantic search for [mkdocs-material](https://squidfunk.github.io/mkdocs-material/) using [transformers.js](https://huggingface.co/docs/transformers.js/en/index)

## Writing
{% for post in site.blog %}
- [{{ post.title | default: post.name | remove: '.md' }}]({{ post.url }})
{% endfor %}
- [Agile Talk](/where-agile-comes-from-talk)

## Interests
Since I have a background in audio production, I tend to think of data problems in terms of _signal flow_ — sources, transforms, sinks, feedback loops. This mental model maps cleanly onto knowledge graphs (nodes as signal, edges as flow), event sourcing (the log as the canonical signal), and context engineering (what reaches the model = what you mixed in).

I'm also a big fan of Clojure and the Clojure community.

I also make [music](/music)

### Currently Learning / Exploring
- Knowledge Graphs & Ontologies — Neo4j, property graph modeling, Graphiti
- Context Engineering — durable agent memory, graph-based context stores, temporal reasoning
- Graph Query Languages — Cypher, Datalog, Pathom
- [Rama](https://redplanetlabs.com/learn-rama) — stream processing and incremental computation
- Local First Web Apps — [Instant DB](https://www.instantdb.com/), [Ink and Switch](https://www.inkandswitch.com/)

### Favorite Books and Talks
- [Simple Made Easy](https://www.youtube.com/watch?v=SxdOUGdseq4&t=3307s)
- [Programming With Hand Tools](https://www.youtube.com/watch?v=ShEez0JkOFw)
- [The Future of Programming](https://www.youtube.com/watch?v=kWS1i2tivi8)
- [The Web After Tomorrow](https://tonsky.me/blog/the-web-after-tomorrow/)
- [Data and Reality](https://www.amazon.com/Data-Reality-Perspective-Perceiving-Information/dp/1935504215)
- [Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/)
- [SICP](https://mitp-content-server.mit.edu/books/content/sectbyfn/books_pres_0/6515/sicp.zip/index.html) — [my exercises in ClojureScript](https://github.com/nharsch/SICP)
- [The Little Schemer](https://mitpress.mit.edu/9780262560993/the-little-schemer/)
- [The Nature of Order](https://en.wikipedia.org/wiki/The_Nature_of_Order)
- [The Art of Learning](https://www.joshwaitzkin.com/the-art-of-learning)
- [The Nature of Code](https://natureofcode.com/) — [my exercises in ClojureScript/Quil](https://github.com/nharsch/nature_of_code)
- [The Dream Machine](https://press.stripe.com/the-dream-machine)
