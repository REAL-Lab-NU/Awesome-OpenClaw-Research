# CITE-Only References for OpenClaw Survey

Papers that should be cited in the survey but are NOT in the awesome-list repo (not directly about OpenClaw).

Generated from deep-summary related work mining (April 2026).

---

## Trust & Safety — Agent Security Foundations

| Title | ID/Venue | Why cite | Survey section |
|:------|:---------|:---------|:--------------|
| Morris II: A Self-Propagating Adversarial Prompt Injection | 2024 | Direct predecessor to ClawWorm; toy email-assistant worm | sec:trust (attacks) |
| AgentDojo: Evaluating Prompt Injection Attacks and Defenses | NeurIPS 2024 (2406.15544) | Core benchmark used by VeriGrey, PASB, and others | sec:trust, sec:benchmarks |
| Agent Security Bench (ASB): Formalizing Attacks and Defenses | ICLR 2025 | Foundational benchmark that PASB extends | sec:trust (benchmarks) |
| InjecAgent: Benchmarking Indirect Prompt Injections | Zhan et al. 2024 | First systematic indirect prompt injection benchmark | sec:trust (attacks) |
| Agentpoison: Red-Teaming via Poisoning Memory | NeurIPS 2024 | First memory poisoning benchmark for LLM agents | sec:trust (attacks) |
| AGrail: A Lifelong Agent Guardrail | 2502.11448 | Lifecycle-aware defense architecture | sec:trust (defenses) |
| Progent: Programmable Privilege Control for LLM Agents | 2504.11703 | Dynamic policy language for per-agent tool restrictions | sec:trust (defenses) |
| StruQ: Defending Against Prompt Injection with Structured Queries | 2402.06363 | Structural isolation for prompt injection | sec:trust (defenses) |
| SecAlign: Defending via Preference Optimization | CCS 2025 | Model-level alignment defense | sec:trust (defenses) |
| LLMail-Inject: Adaptive Prompt Injection Attacks | 2506.09956 | Primary benchmark for privilege separation evaluation | sec:trust (benchmarks) |
| System-level Defense via Information Flow Control | 2409.19091 | IFC reasoning for structural defense | sec:trust (defenses) |
| DataSentinel: Game-Theoretic Prompt Injection Detection | 2504.11358 | Detection method for prompt injection | sec:trust (defenses) |
| PromptArmor: Simple yet Effective Defenses | 2507.15219 | Detection-based prompt injection defense | sec:trust (defenses) |
| A-MemGuard: Proactive Defense for Agent Memory | 2510.02373 | Continuous memory protection | sec:trust (defenses) |
| BlindGuard: Safeguarding Multi-Agent Under Unknown Attacks | 2508.08127 | Runtime intent verification | sec:trust (defenses) |
| AgentDoG: Diagnostic Guardrail Framework for AI Agent Safety | 2601.18491 | Trajectory judge used in safety audits | sec:trust (evaluation) |
| LPS-Bench: Safety Awareness of Computer-Use Agents | 2602.03255 | Primary benchmark source for trajectory audits | sec:benchmarks |
| AgenTRIM: Tool Risk Mitigation for Agentic AI | 2601.12449 | Tool risk mitigation framework | sec:trust (defenses) |
| BackdoorAgent: Backdoor Attacks on LLM-based Agents | 2601.04566 | Backdoor attacks on agents | sec:trust (attacks) |

## Trust & Safety — Attack Techniques

| Title | ID/Venue | Why cite | Survey section |
|:------|:---------|:---------|:--------------|
| STAC: When Innocent Tools Form Dangerous Chains | 2509.25624 | Sequential tool attack chains >90% success | sec:trust (attacks) |
| Mind the GAP: Text Safety ≠ Tool-Call Safety | 2602.16943 | Conditional GAP rates up to 79.3% | sec:trust (attacks) |
| MCPDiFF: Understanding MCP Behavior Under Misleading Descriptions | 2602.03580 | ~13% undocumented high-risk operations in MCP | sec:trust (attacks) |
| MalTool: Systematic Study of Malicious Tools | Wang et al. 2026b | 6,487 malicious tools; baseline for SkillFortify | sec:trust (attacks) |
| Beyond Max Tokens: Resource Amplification via Tool Chains | 2601.10955 | First token-drain attack paper; baseline for Clawdrain | sec:trust (attacks) |
| Excessive Reasoning Attack on Reasoning LLMs | 2506.14374 | Reasoning amplification vulnerability | sec:trust (attacks) |
| Breaking Agents: Malfunction Amplification | ACL 2025 | Agent malfunction amplification formalization | sec:trust (attacks) |
| MemoryGraft: Persistent Compromise via Poisoned Experience | 2512.16962 | Memory poisoning in LLM agents | sec:trust (attacks) |
| Context Manipulation Attacks on Web Agents | 2506.17318 | Memory corruption in web agents | sec:trust (attacks) |
| Memory Poisoning Attack and Defense on LLM-Agents | 2601.05504 | Systematic memory poisoning taxonomy | sec:trust (attacks) |
| The Dark Side of LLMs: Agent-based Attacks for Computer Takeover | 2507.06850 | Agent code execution attack surface | sec:trust (attacks) |
| Automating Agent Hijacking via Structural Template Injection | 2602.16958 | Decision-stage intent drift and goal hijacking | sec:trust (attacks) |
| Refusal Training Degrades LLM Safety in Tool-Use Settings | Adonis et al. | Safety degradation in tool-using agents | sec:trust (discussion) |

## Trust & Safety — Industry/Ecosystem Reports

| Title | ID/Venue | Why cite | Survey section |
|:------|:---------|:---------|:--------------|
| SoK: Agentic Skills in the Wild (ClawHavoc) | Zhang et al. 2026 | Documents ClawHavoc campaign (1,200+ malicious skills) | sec:trust (supply chain) |
| Agent Skills in the Wild: Large-Scale Empirical Study | Park et al. 2026 | 42,447 skills scanned; 26.1% vulnerability rate | sec:platform (skills) |
| "Do Not Mention This to the User": Detecting Malicious Skills | Anonymous 2026 | Empirical malicious skill detection study | sec:trust (supply chain) |
| Exploring Emerging Threats of the Agent Skill Ecosystem (Snyk) | Beurer-Kellner et al. 2026 | 36% prompt injection rate in skill supply chain | sec:trust (industry) |
| Agent skills in the wild: Security vulnerabilities at scale | 2601.10338 | 31K skills security analysis | sec:platform (skills) |
| Trinity Defense Architecture | 2602.09947 | "Lethal Trifecta" identification | sec:trust (defenses) |

## Platform & Ecosystem — Multi-Agent Frameworks (High-frequency citations)

| Title | ID/Venue | Why cite | Survey section |
|:------|:---------|:---------|:--------------|
| CAMEL: Communicative Agents for "Mind" Exploration | 2303.17760 | Foundational multi-agent framework; cited by 3+ papers | sec:background |
| MetaGPT | 2308.00352 | Multi-agent collaborative framework; cited by 3+ papers | sec:background |
| AutoGen | 2308.08155 | Multi-agent framework; cited by 3+ papers as MAS baseline | sec:background |
| Ferrarotti et al. (2026) — Interactionist Paradigm for Generative AI Collective Behavior | Unknown | Methodological framework adopted by 3+ Moltbook papers | sec:application (moltbook) |

## Trust & Safety — Additional Defenses & Red-teaming (v2 finds)

| Title | ID/Venue | Why cite | Survey section |
|:------|:---------|:---------|:--------------|
| PCAS: Deterministic Policy Enforcement via Datalog Reference Monitor | 2602.16708 | Independent convergence with OAP on pre-action authorization; 48%→93% policy compliance | sec:trust (defenses) |
| Agents of Chaos | 2602.20021 | Key red-teaming: 6 autonomous agents over 14 days leaked SSNs, destroyed infrastructure | sec:trust (motivation) |
| LlamaFirewall | Unknown | Open-source guardrail system; closest comparison to PRISM | sec:trust (defenses) |
| Safiron: Foundational Guardrail | 2510.09781 | Guardian model via synthetic risky trajectories + GRPO RL | sec:trust (defenses) |
| BadAgent | ACL 2024 | Persistent backdoors in LLM agents; predecessor to ClawWorm | sec:trust (attacks) |

## Platform & Ecosystem — RL and Agent Frameworks

| Title | ID/Venue | Why cite | Survey section |
|:------|:---------|:---------|:--------------|
| ReAct: Synergizing Reasoning and Acting | 2210.03629 | Core reasoning-and-acting framework | sec:background |
| Toolformer: Language Models Can Teach Themselves to Use Tools | 2302.04761 | Foundational tool-use self-training | sec:background |
| Generative Agents: Interactive Simulacra of Human Behavior | 2303.08774 | Foundational 25-agent study; precursor to Moltbook | sec:background |
| Voyager: Open-Ended Embodied Agent with LLMs | 2305.16291 | LLM-agent architecture with long-horizon behavior | sec:background |
| AgentBench: Evaluating LLMs as Agents | 2308.03688 | Major benchmark for LLM agent capability | sec:benchmarks |
| RLAnything: Forge Environment, Policy, and Reward Model | wang2026rlanything | Step-wise PRM evidence; referenced by OpenClaw-RL | sec:platform |
| AgentCompress: Task-Aware Compression for Agent Interactions | 2601.05191 | Compression technique for agent interactions | sec:platform |

## Application & Society — Moltbook Social Science Foundations

| Title | ID/Venue | Why cite | Survey section |
|:------|:---------|:---------|:--------------|
| Conformity and social impact on AI agents | 2601.05384 | AI conformity via Social Impact Theory | sec:application (moltbook) |
| AI agents can coordinate beyond human scale | 2409.02822 | Coordination beyond human limits | sec:application (moltbook) |
| Multi-agent risks from advanced AI | 2502.14143 | Comprehensive multi-agent risks framework | sec:application (moltbook) |
| Emergent social conventions and collective bias in LLM populations | Science Advances | Emergent biases in LLM populations | sec:application (moltbook) |
| How malicious AI swarms can threaten democracy | Science 391(6783) | Coordinated manipulation vulnerabilities | sec:application (moltbook) |
| Characterizing LLM-Driven Social Network: Chirper.ai | 2504.10286 | Pre-Moltbook agent-native platform comparison | sec:application (moltbook) |
| Project Sid: Many-agent simulations toward AI civilization | 2411.00114 | Large-scale multi-agent simulation | sec:application (moltbook) |
| A comprehensive survey of self-evolving AI agents | 2508.07407 | Self-evolution taxonomy | sec:application (moltbook) |
| Bots Increase Exposure to Negative Content | Stella et al. 2018 | Classic social bot detection methodology | sec:application (moltbook) |
| A Decade of Social Bot Detection | Cresci 2020 | Comprehensive bot detection review | sec:application (moltbook) |
| Social Learning in LLM-Based Multi-Agent Systems | Gupta et al. 2025 | LLM agents produce cooperation outputs | sec:application (moltbook) |
| Emergence of Norms in LLM Multi-Agent Systems | Ren et al. 2024 | Multi-agent norm formation framework | sec:application (moltbook) |
| Cultural Evolution in LLM Societies | Vallinder et al. 2024 | Cultural evolution in AI societies | sec:application (moltbook) |
| Do Large Language Models Learn Socially? | Larooij et al. 2025 | Critiques anthropomorphization of LLM social behavior | sec:application (moltbook) |

## Application & Society — Governance & Propaganda

| Title | ID/Venue | Why cite | Survey section |
|:------|:---------|:---------|:--------------|
| VASTU: Value-Aligned Social Toolkit for Content Curation | 2601.12491 | Governance framework for agent community moderation | sec:application (moltbook) |
| MoMoE: Mixture of Moderation Experts | EMNLP 2025 | AI-assisted moderation for agent communities | sec:application (moltbook) |
| Risk Analysis for Governed LLM-based Multi-Agent Systems | 2508.05687 | Risk analysis framework for multi-agent governance | sec:application (moltbook) |
| When agents persuade: Propaganda generation and mitigation | Jose et al. 2026 | LLM propaganda generation; foundational for Moltbook propaganda study | sec:application (moltbook) |
| Defending Against Social Engineering in the Age of LLMs | 2406.12263 | Social engineering defense; relevant to Moltbook 31.9% finding | sec:application (moltbook) |

## Application & Society — Robotics

| Title | ID/Venue | Why cite | Survey section |
|:------|:---------|:---------|:--------------|
| Agentic AI for Robot Control: Flexible but Still Fragile | 2602.13081 | LLM robot control fragility analysis | sec:application (robotics) |
| ROSA: LLM-ROS Agent Framework (NASA JPL) | Royce et al. 2025 | ROSClaw's direct baseline comparator | sec:application (robotics) |
| SayCan: Grounding Language in Robotic Affordances | Ahn et al. 2022 | Foundational affordance grounding | sec:application (robotics) |
| pi0.5: Vision-Language-Action Model | Black et al. 2026 | RoboClaw's core VLA policy backbone | sec:application (robotics) |

## Application & Society — Scientific Research

| Title | ID/Venue | Why cite | Survey section |
|:------|:---------|:---------|:--------------|
| Coscientist: Autonomous Multi-Agent for Scientific Discovery | Boiko et al. 2023 | Tier 1 single-agent scientific architecture baseline | sec:application (science) |
| The AI Scientist: Fully Automated Scientific Discovery | Lu et al. 2024 | Monolithic pipeline ceiling | sec:application (science) |
| The AI Scientist-v2 | Yamada et al. 2025 | First AI-generated paper accepted at peer-reviewed workshop | sec:application (science) |
| Google AI Co-Scientist (Gemini 2.0) | Gottweis et al. 2025 | Tier 2 architectural ceiling case | sec:application (science) |

## Application & Society — Education

| Title | ID/Venue | Why cite | Survey section |
|:------|:---------|:---------|:--------------|
| Illich, "Deschooling Society" (1971) | Book | "Learning web" theory extended to AI agents | sec:application (education) |
| Grand Challenges for Learning@Scale in the Generative AI Era | Piech 2025 | L@S research agenda for AI agents in education | sec:application (education) |

## Related "Claw" Systems (Not OpenClaw, but relevant context)

| Title | ID/Venue | Why cite | Survey section |
|:------|:---------|:---------|:--------------|
| EvoClaw: Evaluating AI Agents on Continuous Software Evolution | 2603.13428 | Independent benchmark for agent code evolution; "-Claw" ecosystem context | sec:discussion |
| MCP-Atlas: Large-Scale Benchmark for MCP Tool-Use | 2602.00933 | 36 real MCP servers, 1000 tasks; relevant to OpenClaw's MCP usage | sec:benchmarks |
| Toward Personalized LLM-Powered Agents | 2602.22680 | General personalization survey; context for OpenClaw-RL personalization | sec:platform |
| EduClaw: Scaling Laws for Educational AI Agents | 2603.11709 | Independent educational agent platform; comparison point for OpenClaw education papers | sec:application (education) |
| ScienceClaw + INFINITE: Autonomous Agents Coordinating Discovery | 2603.14312 | Independent scientific agent framework; comparison point for ClawdLab | sec:application (science) |

## General Surveys (Background/Positioning)

| Title | ID/Venue | Why cite | Survey section |
|:------|:---------|:---------|:--------------|
| Large Language Model Based Multi-Agents: A Survey | 2402.01680 | Foundational multi-agent survey | sec:background |
| The Rise and Potential of LLM Based Agents: A Survey | Xi et al. 2025 | General LLM agent survey | sec:background |
| AI Agents Under Threat: Survey of Key Security Challenges | ACM CS 57:7 | Comprehensive AI agent security survey | sec:background |

---

## Summary

| Category | Count |
|:---------|:-----:|
| Trust & Safety — Foundations | 19 |
| Trust & Safety — Attacks | 13 |
| Trust & Safety — Industry | 6 |
| Platform — RL/Frameworks | 7 |
| Application — Moltbook Social | 14 |
| Application — Governance | 5 |
| Application — Robotics | 4 |
| Application — Science | 4 |
| Application — Education | 2 |
| General Surveys | 3 |
| **Total** | **77** |
