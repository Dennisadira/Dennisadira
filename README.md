## Adira Denis Muhando

Head of Technology at **Kifiya Financial Technology**. I build the AI/ML layer of production lending platforms for African markets — credit scoring, LLM-powered qualitative analysis, fraud detection on AI-generated KYC documents, AML transaction monitoring.

10+ years across financial platforms in Africa. Previously led 9 engineers at **Safaricom Ethiopia** on a national-scale biometric identity platform (10M+ activations in 6 months), architected the multi-modal biometric platform at **Compulynx for Kenya Commercial Bank**, and spent 4+ years at **Eclectics** shipping banking-transaction systems across 21 African countries.

### What I work on

- **ML credit scoring** — bank-statement feature extraction → trained model → calibrated risk scores over REST. LLM layer reasons about borrower context where numbers fall short.
- **KYC document fraud detection** — classifies submitted IDs as genuine vs. AI-generated via stamp detection, document structure, visual artifacts, metadata consistency.
- **AML transaction monitoring** — velocity, structuring, and counterparty-pattern anomaly detection on event-driven pipelines.
- **Biometric identity** — face, fingerprint, and contactless fingerprint acquisition with multi-provider matching and government-database verification.

### Open source

- [`mudler/LocalAI#9411`](https://github.com/mudler/LocalAI/pull/9411) — `fix(backend-monitor)`: accept `model` as a query parameter so the endpoint is Swagger/OpenAPI-compatible. **Merged.**
- [`mark3labs/mcp-go#808`](https://github.com/mark3labs/mcp-go/pull/808) — OAuth: extract the RFC 9728 Protected Resource Metadata URL from `WWW-Authenticate`, with origin validation and §3.3/§7.3 resource-binding checks. Closed after the maintainer consolidated concurrent efforts; origin-validation and resource-binding approach called out for upstream inclusion.

### Selected public projects

- [**AthenaIntelligentLMS**](https://github.com/aktechkenya/AthenaIntelligentLMS) — intelligent lending platform: 11 Spring Boot services, React UI, RabbitMQ, PostgreSQL.
- [**AthenaCreditScore**](https://github.com/aktech-io/AthenaCreditScore) — AI credit-scoring platform for African SMEs: LightGBM + rule scorecard + LLM overlay (TransUnion + Metropol CRBs).
- [**spring-monitoring-demo**](https://github.com/aktechkenya/spring-monitoring-demo) — Spring Boot + Prometheus/Grafana observability reference.

### Stack

Python · Java · Go · PostgreSQL · Redis · Kafka · RabbitMQ · GCP · OCI · Kubernetes · Terraform

### Contact

[LinkedIn](https://www.linkedin.com/in/dennis-adira/) · dennisadira@gmail.com · Nairobi, Kenya
