<div align="center">

# Hi, I'm Akash Santra 👋

Software Developer • Open Source Contributor • Backend & Systems • Machine Learning

[LinkedIn](https://www.linkedin.com/in/akash-santra-5823b42a6/) • [Twitter/X](https://x.com/akashsantra999) • [Email](mailto:santraakash999@gmail.com)

</div>

---

## About Me

I’m Akash, a developer focused on backend systems, machine learning, developer tools, and open source.

* Contributing to large-scale open source projects like Strapi and Mastra
* Interested in backend architecture, APIs, infrastructure, and ML systems
* Learning AI systems, LLM tooling, and distributed systems
* Ask me about Node.js, JavaScript, PostgreSQL, MongoDB, MySQL, and open source workflows
* Goal: Become a strong systems and software engineer

---

## Featured Projects

### PASO – AI-Powered Real-Time Chat App

[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com/Akash504-ai/paso-chat-app)
[![Live Demo](https://img.shields.io/badge/Live-Demo-green)](https://chat-app-sooty-mu.vercel.app/)

* Real-time chat with Socket.io (1-1 + group chat)
* AI chatbot integration (Groq API)
* ML-based moderation (toxicity + spam detection)
* Voice/video calling (ZegoCloud)
* Full admin dashboard with analytics

### Nexus – AI Resume Analyzer & Interview Platform

[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com/Akash504-ai/Resume-Analysis)
[![Live Demo](https://img.shields.io/badge/Live-Demo-green)](https://resume-analysis-gray-five.vercel.app/)

* Resume parsing with NLP + ML scoring
* Skill gap detection and job recommendations
* AI-generated interview questions (LLM-based)
* Dashboard with analytics and progress tracking
* Real-time chat + community features

---

## Open Source Contributions

### Featured Pull Requests

* Cal.com — Fixed negative wait time bug in rate limit error messages (production user-facing fix) ([#28765](https://github.com/calcom/cal.com/pull/28765#event-24269288514))
* Haystack (deepset-ai) — Fixed NVIDIA structured output handling & migrated to response_format schema ([#3058](https://github.com/deepset-ai/haystack-core-integrations/pull/3058#issuecomment-4152892721))
* Strapi — Fixed OpenAPI plugin route prefix handling ([#25616](https://github.com/strapi/strapi/pull/25616))
* Mastra — Fixed e2e test hang by adding timeout to dev server startup ([#14955](https://github.com/mastra-ai/mastra/pull/14955))
* Mastra — Fixed invalid JSON escape handling in PostgreSQL ([#14692](https://github.com/mastra-ai/mastra/pull/14692))
* Mastra — Added contiguous trimming mode to TokenLimiterProcessor ([#14801](https://github.com/mastra-ai/mastra/pull/14801))
* Mastra — Added minMessages option to delay title generation ([#14778](https://github.com/mastra-ai/mastra/pull/14778#event-24082273644))
* conda-forge — Fixed multiple UnicodeDecodeError issues on Windows by enforcing UTF-8 encoding in documentation tooling (cross-platform reliability) ([#2800](https://github.com/conda-forge/conda-forge.github.io/pull/2800), [#2799](https://github.com/conda-forge/conda-forge.github.io/pull/2799))
* GeomScale (volesti) — Improved build and run documentation ([#376](https://github.com/GeomScale/volesti/pull/376))

---

## Contribution Highlights

#### Cal.com — Production Systems / API Reliability

* Fixed negative wait time bug in rate limit error messages (user-facing production issue)
* Ensured safe handling of edge cases where reset timestamps are in the past
* Improved API correctness and overall user experience in rate limiting logic

#### Haystack (deepset-ai) — AI / LLM Systems

* Fixed incorrect structured output handling in NVIDIA integration
* Migrated deprecated guided_json → response_format (aligned with latest API standards)
* Debugged real-world API vs test inconsistencies (critical reliability fix)
* Ensured compatibility across sync and async execution paths
* Passed full NVIDIA integration test suite (180+ tests)

#### Mastra — Feature + Backend Systems

* Added contiguous trimming mode to TokenLimiterProcessor to preserve a clean suffix of conversation history under token constraints
* Introduced configurable minMessages threshold for context-aware title generation
* Prevented premature/generic titles in agent workflows and reduced unnecessary LLM calls (token savings)
* Fixed PostgreSQL jsonb failures caused by invalid escape sequences
* Implemented safe sanitization for invalid escapes and null characters
* Added tests to ensure reliability across processing and database layers
* Fixed e2e test reliability issue where dev server startup could hang indefinitely by introducing timeout safeguards and improved process handling

#### Strapi — API / Backend Fix

* Fixed incorrect OpenAPI path generation for plugin routes
* Handled router.prefix and config.prefix edge cases
* Prevented broken API documentation in plugin-based setups
* Added unit tests and passed 90+ CI checks

#### conda-forge — Cross-Platform Reliability

* Fixed UnicodeDecodeError caused by Windows default cp1252 encoding when reading UTF-8 JSON files
* Enforced explicit UTF-8 decoding to ensure consistent behavior across operating systems

#### GeomScale / volesti — Developer Experience

* Improved developer onboarding and documentation clarity
* Refactored CMake workflow using out-of-source builds
* Simplified build and execution process for examples

---

## Contribution Areas

* Backend systems and API design
* AI tooling and LLM workflows
* Database reliability (PostgreSQL, JSON handling)
* Testing and edge-case handling
* Developer experience improvements

---

## Tech Stack

| Category       | Technologies                                                                 |
| -------------- | ---------------------------------------------------------------------------- |
| Languages      | JavaScript, Python, C++, C                                                   |
| Frontend       | React, Tailwind CSS, HTML, CSS                                               |
| Backend        | Node.js, Express, REST APIs                                                  |
| Databases      | PostgreSQL, MongoDB, Firebase                                                |
| Deployment     | Render, Vercel                                                               |
| ML / AI        | FastAPI, Hugging Face, Scikit-learn, Pandas, NumPy                           |
| ML Concepts    | Supervised Learning, Classification, Model Tuning, Ensemble Learning, NLP    |
| NLP            | Bag of Words, TF-IDF                                                         |
| Tools          | Git, Docker, GitHub Actions                                                  |

## Current Focus

* Scaling open source contributions
* Backend and infrastructure deep dive
* Exploring AI and system design

---

⭐ If you like my work, consider following or checking out my repositories
