## Osama Wehbi

PhD candidate in Computer Engineering at Polytechnique Montréal, specialising in AI security, adversarial machine learning and federated learning security.

My doctoral research, *Detecting and Mitigating Backdoor Attacks in Federated Learning*, develops defences across the whole federated learning lifecycle: pre-training sanitisation of poisoned data, in-training detection and suppression of malicious clients, and post-training removal of backdoors from deployed models without retraining. Alongside this I work on decentralised trust and reputation for federated systems, game-theoretic security mechanisms, and the security of LLM applications and AI agents.

Previously a research assistant at Mohamed bin Zayed University of Artificial Intelligence (MBZUAI), working on trustworthy and secure federated learning for IoT and smart cities, and a part-time faculty member at the Lebanese American University, where I completed my MS in Computer Science.

### Focus areas

- **Backdoor and poisoning defences in federated learning**: pre-, in- and post-training mitigation, representation cleansing and unlearning
- **Trustworthy federated learning**: mutual trust and reputation, client selection, free-rider and malicious participant detection, fairness under non-IID data
- **Game-theoretic security**: matching and minimax formulations for robust aggregation and incentive design
- **AI and LLM security**: prompt injection, guardrails, agent and tool-use security, Model Context Protocol (MCP) server security
- **AI for security operations**: detection, triage and incident response grounded in MITRE ATT&CK and NIST guidance

### Featured projects

| Project | Description |
| --- | --- |
| [mcp-vet](https://github.com/OsamaWehbi/mcp-vet) | Security scanner for MCP servers: detects tool poisoning, hidden Unicode instructions, over-permissioned tools, data exfiltration paths, rug pulls and tool shadowing. Rules mapped to the OWASP Top 10 for LLM Applications, with SARIF output and a GitHub Action. Python. |
| [SecureAIOps](https://github.com/OsamaWehbi/SecureAIOps) | Agentic SOC copilot with a guarded multi-agent graph, AI firewall, MITRE ATT&CK mapping, explainable risk scoring and policy-grounded RAG. Python, LangGraph, FastAPI. |

### Selected publications

**Backdoor defences in federated learning**

- **SCRUB-FL: Sanitizing and Cleansing Representations via Unlearning of Backdoors.** O. Wehbi et al. *arXiv:2606.22700*, 2026. [Paper](https://arxiv.org/abs/2606.22700)
- **FL-PBM: Pre-Training Backdoor Mitigation for Federated Learning.** O. Wehbi et al. *arXiv:2603.28673*, 2026. [Paper](https://arxiv.org/abs/2603.28673)
- **Mitigating Backdoor Attacks in Federated Learning Using PPA and MiniMax Game Theory.** O. Wehbi et al. *arXiv:2603.28652*, 2026. [Paper](https://arxiv.org/abs/2603.28652)
- **Mitigating One-to-N Backdoor Attacks in Federated Learning.** O. Wehbi et al. *IEEE FLICS*, 2026. [Paper](https://doi.org/10.1109/FLICS70075.2026.11621963)

**Trust and client selection in federated learning**

- **Enhancing Mutual Trustworthiness in Federated Learning for Data-Rich Smart Cities.** O. Wehbi et al. *IEEE Internet of Things Journal*, 2025. [Paper](https://ieeexplore.ieee.org/document/10709870)
- **FedMint: Intelligent Bilateral Client Selection in Federated Learning With Newcomer IoT Devices.** O. Wehbi et al. *IEEE Internet of Things Journal*, 2023.
- **Towards Mutual Trust-Based Matching for Federated Learning Client Selection.** O. Wehbi et al. *IEEE IWCMC*, 2023.
- **Towards Bilateral Client Selection in Federated Learning Using Matching Game Theory.** O. Wehbi et al. *IEEE GLOBECOM*, 2022.

**Co-authored**

- **Detecting Free-Riders in Federated Learning Using an Ensemble of Similarity Distance Metrics.** S. Arisdakessian et al. *IEEE ICSC*, 2024. Best Paper Award.

Full list, including work on fairness, federated learning marketplaces, hierarchical FL for healthcare and the metaverse, on [Google Scholar](https://scholar.google.com/citations?user=6AMEO3cAAAAJ).

### Recognition and service

- Best Paper Award, Intelligent Cybersecurity Conference (ICSC 2024)
- Session Chair, IEEE IWCMC 2023
- Peer reviewer, *IEEE Transactions on Services Computing* and *IEEE Transactions on Network and Service Management*

### Tools

Python, PyTorch, TensorFlow, scikit-learn, FedML, PySyft, LangChain, LangGraph, FastAPI, Docker, Kubernetes, Linux, Elastic Stack

### Contact

- [LinkedIn](https://www.linkedin.com/in/osama-wehbi/) · [Google Scholar](https://scholar.google.com/citations?user=6AMEO3cAAAAJ)
- For security issues in my projects, please use each repository's private vulnerability reporting rather than public issues.
