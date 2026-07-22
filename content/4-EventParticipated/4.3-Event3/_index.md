---
title: "Event 3"
date: 2026-05-23
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

# Summary Report: “AWS First Cloud AI Journey — Community Day”

### Event Information
| | |
|---|---|
| **Event Name** | AWS First Cloud AI Journey — Community Day |
| **Date** | 23/05/2026 |
| **Location** | 26th Floor, Bitexco Financial Tower, 2 Hai Trieu Street, Ben Nghe Ward, District 1, Ho Chi Minh City |
| **Organizer** | AWS Study Group |
| **Role** | Participant / Intern |

### Event Objectives

- Capture practical lessons from five featured sessions on context engineering, GenAI auditing, CloudFront cost control, hackathon delivery, deterministic LLM settings, and multi-agent AI.
- Reflect on how GenAI, DevOps, platform engineering, and cloud security connect in real AWS projects.
- Consolidate the key technical and business insights that can be applied to my own learning and to LingoRise.
- Record the direct feedback and networking opportunities gained from cloud experts and mentors during the event.

### Speakers

- **Tinh Truong** – Platform Engineer, GoTymeX
- **Pham Nguyen Hai Anh** – Cloud Consultant at G-AsiaPacific Vietnam, AWS Community Builder - Security
- **Nguyen Tuan Thinh** – DevOps Engineer, First Cloud AI Journey
- **Team VIB** – GenAI and software engineering team at VIB
- **Duc Dao** – Solution Architect, Cloud Kinetics
- **Vy Lam** – Senior Business Systems Analyst, VPBank

### Key Highlights

#### Context Is Everything — Making AI Actually Work for You

Presented by **Tinh Truong** (Platform Engineer, GoTymeX), this session focused on the central importance of context when working with large language models (LLMs).

- AI fails when context is missing: even strong models produce vague and unrealistic output if the input is too minimal.
- Context is the full set of information that helps AI understand the "task behind the task."
- High-quality context includes your goal, your situation, your constraints, and relevant evidence.
- A common mistake is the "Internet Puller" problem, where users paste too many unrelated documents, screenshots, and notes into one prompt.
- Too much unrelated context can bury important information, reduce accuracy, and increase token cost.
- The "Second AI Brain" idea showed how memory and context retrieval can support continuous learning and better answers.

#### GenAI-Powered Auto Audit for AWS Workload

Presented by **Pham Nguyen Hai Anh** (Cloud Consultant at G-AsiaPacific Vietnam, AWS Community Builder - Security), this session introduced a GenAI-based automation solution for system auditing and addressed common business pain points.

- Business users often struggle with manual data search across disconnected sources, deep analysis that depends on specialists, and repetitive work that wastes time.
- Amazon Q Business (Quick Suite) was explained as a multi-purpose operating model covering Insights, BI & Automation, data source integration, and security/control.
- The platform can connect to more than 40 enterprise data sources such as Google Workspace, S3, and databases, while still enforcing access control and compliance filtering.
- The PM Assistant use case showed how a virtual assistant can generate meeting minutes from audio, send updates, and schedule the next meeting automatically.
- The session also demonstrated how LLMs can scan AWS architectures, compare them against security standards, and detect vulnerabilities.

#### From Edge to Origin: CloudFront as Your Foundation

Presented by **Nguyen Tuan Thinh** (DevOps Engineer, First Cloud AI Journey), this session explored Amazon CloudFront as a foundational delivery layer while analyzing financial risks related to cloud CDN costs.

- CloudFront works as the first checkpoint for caching and distributing static and dynamic assets from global Edge Locations, which reduces latency.
- The pay-as-you-go model can be difficult to forecast because traffic changes frequently.
- Traffic spikes from viral usage or DDoS attacks can push CDN bills far beyond control.
- The talk highlighted the financial risk of unexpectedly large cloud bills for founders and startups.
- Recommended practices included CloudWatch Billing Alerts, AWS WAF, and TTL optimization to improve cache hit ratio.

#### 36 hrs with LotusHacks: Building UTMorpho from Idea to Reality

Presented by **Team VIB** (representing the GenAI and software engineering team at VIB), this session shared the intense real-world experience of joining the 36-hour LotusHacks hackathon to build and launch **UTMorpho**.

- The team started from a blank "Hour 0" mindset and used early observations from the event to define the problem they wanted to solve.
- Their 36-hour sprint followed a structured flow: Setup & Alignment, First Slice, Build the core, The hard middle, Integration & Polish, and Submit & Pitch.
- The session emphasized how to define an MVP quickly, establish API boundaries early, and keep the team aligned under pressure.
- A major lesson was to manage technical debt flexibly, move quickly with prototypes, and focus deeply on solving one problem instead of trying to build too many features.

#### Non-Determinism of 'Deterministic' LLM Settings

Presented by **Duc Dao** (Solution Architect - Cloud Kinetics), this session explored token selection in LLMs, sampling settings, and why Temperature = 0 does not always guarantee perfectly deterministic output in practice.

- LLMs generate text token by token by computing logits, applying softmax, and choosing the next token from the resulting probability distribution.
- Temperature controls how spread out the distribution is, and Temperature = 0 should theoretically choose the highest-probability token every time.
- In practice, GPU parallel processing can still introduce tiny floating-point differences because addition is not associative.
- API-layer effects such as system load, server balancing, and hardware differences can also change output slightly.
- The session recommended strict JSON schema validation, stronger prompt constraints, seed parameters, and backend parsers that handle exceptions gracefully.

#### Enterprise-Grade Multi-Agent System: The Case of Startup Credit Scoring

Presented by **Vy Lam** (Senior Business Systems Analyst, VPBank), this session analyzed the systemic barriers in startup credit assessment and how a Multi-Agent AI model can address the weaknesses of a Single-Agent approach.

- Traditional banks often require 3+ years of financial reports, collateral assets, and stable revenue, while startups may only have 6-18 months of history.
- Startups often depend more on intellectual property and growth indicators, so rigid approval models can exclude them even when they have strong potential.
- A single AI agent for credit approval suffers from context limits, dilution of specialization, lack of checks and balances, and a single point of failure.
- The proposed Multi-Agent model acts as a virtual credit committee with specialized agents for financial analysis, technology/IP due diligence, and risk auditing.
- The enterprise security model was described through five layers: Perimeter, VPC network, Identity, Application, and Data.

### Key Takeaways

#### Context Engineering

- Clean and selective context is essential for good AI output.
- Context turns a vague request into a solvable problem.
- The combination of context and memory is what makes a second AI brain useful in practice.

#### GenAI and Automation

- GenAI can reduce repetitive work by automating note-taking, data retrieval, and system auditing.
- Business workflows become more practical when the AI layer is connected to real enterprise data sources.

#### Cloud Architecture and Cost Control

- CloudFront is effective for lowering latency, but CDN usage must be monitored carefully.
- Billing alerts, WAF protection, and TTL tuning are important operational safeguards.
- Cloud cost surprises can become a serious business risk if no controls are in place.

#### Hackathon Delivery

- Fast prototyping and clear MVP scope are critical under extreme time pressure.
- Integration issues are normal in the hard middle of a sprint, so teams need to stay aligned.
- Focusing on one valuable problem is better than chasing too many features.

#### Deterministic LLM Behavior

- Temperature = 0 does not guarantee perfect determinism in real GPU-based systems.
- Backend validation and parser fallbacks are necessary when model output format can vary.
- Strong schema checks and prompt constraints reduce downstream failures.

#### Multi-Agent AI and Enterprise Security

- Splitting complex AI work into specialized agents is more robust than forcing everything into one model.
- Enterprise AI systems need layered security controls across network, identity, application, and data boundaries.
- Prompt injection defense and rate limiting are important for safe deployment.

### Applying to Work

- Use clean and selective context when working with AI-assisted coding or prompt design.
- Keep LingoRise split into separate flows for exam generation and Writing essay scoring.
- Continue using the extractJsonObject() fallback parser to handle malformed JSON from LLM output.
- Apply API boundary checks, prompt-injection defense, and rate limiting to protect future features.
- Use CloudFront OAC, billing alerts, and TTL tuning to improve security and cost predictability for cloud assets.
- Build enterprise features with a multi-agent mindset when the task is too complex for a single AI step.

### Event Experience

Participating in the **AWS First Cloud AI Journey — Community Day** event gave me a broad view of how cloud, GenAI, and security ideas connect in real projects.

#### Learning from real-world sessions

- The context-engineering talk reinforced that AI answers improve when the prompt is precise and well-scoped.
- The GenAI auto-audit session showed how enterprise workflows can be automated with AI and connected data sources.
- The CloudFront session clarified the tradeoff between easy scaling and unpredictable cost growth.

#### Practical lessons

- The LotusHacks talk showed how to move from idea to prototype quickly under pressure.
- The deterministic LLM session confirmed why strict validation and fallback parsing matter in production systems.
- The multi-agent credit scoring talk highlighted the value of decomposition, specialization, and layered security.

#### Lessons Learned

- Context quality directly affects AI output quality.
- Enterprise AI should be designed as a set of coordinated components, not a single oversized model.
- Security, cost control, and reliability must be considered together in cloud systems.
- A clear delivery process makes it easier to ship meaningful work under pressure.

#### Some Event Photos

![](/images/event/event3-1.jpg)

> Overall, this event expanded my understanding of context engineering, GenAI automation, cloud CDN cost control, hackathon execution, deterministic LLM behavior, and multi-agent AI design. It also gave me practical guidance that I can apply to my future learning and to the continued development of LingoRise.
