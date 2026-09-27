## Aakash Chandra

**Staff / Principal Security Engineer · AI & Agentic Security · AI/ML Platform Security**

I have 12+ years in security engineering and architecture. The last several have gone into securing AI systems in production: model and data pipelines, retrieval, hosted inference, and now autonomous agents that call tools on people's behalf. My focus is controls that hold even when the model does not behave. That means deterministic authorization at the tool boundary, tenant isolation that is enforced at retrieval time rather than hoped for, and detection that can explain itself to an analyst.

San Francisco Bay Area · [LinkedIn](https://www.linkedin.com/in/aakash-chandra-787a0486/) · aakashchandra.ai369@gmail.com

---

### Featured projects

These are new, original, public reference implementations. Each one has working code, synthetic data, tests, and CI, and each states its assumptions and limits plainly.

| Project | What it demonstrates |
|---|---|
| [**agentwatch**](https://github.com/achandra-security/agentwatch) | Behavioral detection for AI agent telemetry: explainable rules for cross-tenant access, unapproved irreversible actions, injection-to-exfiltration sequences, delegation abuse, and workload identity mismatch, with SIEM-ready output for Falcon LogScale and Splunk |
| [**mcp-audit**](https://github.com/achandra-security/mcp-audit) | An offline security assessment engine for Model Context Protocol server configurations. It checks tool privilege scope, OAuth issuer and audience validation, PKCE, token pass-through, RFC 8707 resource indicators, confused-deputy setups, tool poisoning and shadowing, and destructive-tool approval gates. Output is text, JSON, or SARIF |
| [**agent-authorization-reference**](https://github.com/achandra-security/agent-authorization-reference) | Zero Trust authorization at the agent tool-invocation boundary: deny by default, delegated scopes narrowed through a token exchange modelled on RFC 8693, tenant isolation, short-lived credentials, human approval bound to the exact request, and an audit event for every decision. It shows that a model asking for an action is never the thing that authorizes it |

---

### What I work on

- **AI/ML platform security:** model, retrieval, inference, and data pipeline security; retrieval-time ACL enforcement and vector database tenant isolation; multi-tenant hosted inference, including prefix-cache isolation; model supply chain (serialization risk, safetensors, provenance)
- **Agentic AI and MCP security:** agent identity, delegation, and authorization; prompt injection defense and provenance; agent execution isolation; MCP server and tool assessment; secure-by-design standards for agentic systems
- **AI red teaming and evaluation:** assessment methodology for agents and LLM applications, and automated adversarial regression testing
- **AI governance, made technical:** controls aligned with NIST AI RMF and ISO/IEC 42001 that are implemented in the platform, not only written into policy
- **Foundations:** cloud security (AWS, Azure), identity and Zero Trust (Okta, IAM and identity governance), network security (Palo Alto Networks), and detection engineering (CrowdStrike Falcon LogScale)

### Experience

**Denali Therapeutics** · Cybersecurity Engineer · Feb 2026 to present

Enterprise security and agentic AI security architecture. My work covers agent security assessment methodology; agent identity, delegation, and authorization; and secure-by-design standards for agentic systems. It also includes prompt injection defense, agent execution isolation, Falcon LogScale SIEM modernization, Okta identity security, vulnerability management, and AI-assisted SOC operations.

**Gilead Sciences** · AI/ML platform security

Platform-wide security for AI/ML models, retrieval, inference, and data pipelines. I enforced ACLs at retrieval time and isolated vector database tenants, with dedicated cross-tenant retrieval testing. My remit also covered model supply chain security and multi-tenant inference isolation, and I shipped AI-powered security agents to production. I ran 40+ AI red team assessments over two years, backed by automated adversarial regression testing. I provided technical leadership for five security engineers and detection specialists.

Earlier roles: Ultragenyx Pharmaceutical, San Francisco International Airport, 4C's of Alameda County.

### Independent research

Ongoing independent research in AI security, agent identity, multi-agent trust boundaries, human oversight, and security architecture for autonomous systems. This research is separate from my employers' production systems.

### Certifications

CISM · PCNSE · AWS Certified Solutions Architect – Professional

In progress: CISSP · CCSP · AWS Certified Security – Specialty
