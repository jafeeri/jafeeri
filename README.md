# Ali Mehdi Jafeeri

I build LLM systems that are allowed to run in production, and the security tools that try to break them.

Two of mine already do: a pair of bots on a client's server that check and post job listings across Kuwait, Bahrain, Qatar and Oman every day. Getting a model to do that without quietly inventing things is most of the real work, and it's the part I care about.

Most of what's here started the same way, from a tool I wanted that didn't exist yet. ROPForge writes its own ROP exploit chains in Rust and clears ROP Emporium 8 for 8. My invoice pipeline hands a document to a human before it will auto-approve a total it can't verify. The safety gateway drops prompt injection and PII before they reach the model. I spend more time on evals, guardrails and failure modes than on the happy path, because that is the difference between a demo and something you can put real traffic through.

Final-year Electrical Engineering, NUST SEECS. Open to remote AI engineering and security roles.

📍 Islamabad, Pakistan &nbsp;·&nbsp; 📫 alimehdijafeeri@proton.me &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/syed-ali-mehdi-eb7)

---

### 🤖 AI / LLM Engineering
- **[invoice-processing-system](https://github.com/jafeeri/invoice-processing-system)** — vision-LLM invoice extraction with arithmetic validation and human-in-the-loop triage. Anything that fails validation is never auto-accepted.
- **[sales-research-agent](https://github.com/jafeeri/sales-research-agent)** — a ReAct agent that researches a company and returns a source-cited brief, with every claim traceable.
- **[codebase-intelligence-copilot](https://github.com/jafeeri/codebase-intelligence-copilot)** — RAG over a code repository that answers in plain English and cites the exact file and line (recall@5 = 0.92).
- **[llm-eval-bench](https://github.com/jafeeri/llm-eval-bench)** — an evaluation harness that gates CI, so a quality regression fails the build.
- **[ai-prod-monitor](https://github.com/jafeeri/ai-prod-monitor)** — online LLM observability: traces, token cost, a sampled LLM judge, and drift alerts.

### 🛡️ LLM Security & Red-Teaming
- **[ai-safety-gateway](https://github.com/jafeeri/ai-safety-gateway)** — a drop-in proxy that puts prompt-injection, PII, and output guardrails in front of any LLM.
- **[prompt-injection-detector](https://github.com/jafeeri/prompt-injection-detector)** · **[jailbreak-eval-suite](https://github.com/jafeeri/jailbreak-eval-suite)** · **[persona-adoption-attacks](https://github.com/jafeeri/persona-adoption-attacks)** · **[llm-guardrail-fuzzer](https://github.com/jafeeri/llm-guardrail-fuzzer)** · **[Crescendo-attack-detector](https://github.com/jafeeri/Crescendo-attack-detector)** — a toolkit for measuring and breaking LLM guardrails.

### 🔓 Security & Exploitation
- **[ropforge](https://github.com/jafeeri/ropforge)** — a Rust tool that automatically assembles working ROP exploit chains for x86-64 ELF. ROP Emporium 8/8, roughly 40x faster than angrop. Research paper in progress.
- **[wannacry-malware-analysis](https://github.com/jafeeri/wannacry-malware-analysis)** · **[redline-stealer-analysis](https://github.com/jafeeri/redline-stealer-analysis)** · **[plugx-korplug-analysis](https://github.com/jafeeri/plugx-korplug-analysis)** — full static, dynamic, and reverse-engineering write-ups of real malware.
- **[network-traffic-analyzer](https://github.com/jafeeri/network-traffic-analyzer)** · **[syn-port-scanner](https://github.com/jafeeri/syn-port-scanner)** · **[traceroute-tool](https://github.com/jafeeri/traceroute-tool)** · **[ping-sweep-os-fingerprint](https://github.com/jafeeri/ping-sweep-os-fingerprint)** · **[arp-spoof-detector](https://github.com/jafeeri/arp-spoof-detector)** · **[steganography-tool](https://github.com/jafeeri/steganography-tool)** — a from-scratch network and offensive-security toolkit.

### 📡 Research
- **[nimbus-sdvn-fog](https://github.com/jafeeri/nimbus-sdvn-fog)** — a UAV-hosted SDN controller for mmWave vehicular networks in fog (conference paper).

---

**Tech:** Python · Rust · C / C++ · TypeScript · LLM apps (RAG, agents, evals, guardrails) · Claude &amp; OpenAI APIs · scapy · Ghidra · Linux
