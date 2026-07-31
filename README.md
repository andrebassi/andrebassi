## André Bassi

**AI/LLM Engineer & Platform Engineer** — RAG, agentes e LLMOps em produção · Kubernetes multi-cloud AWS·GCP·Azure · Go · Rust · Python

> **Construo a camada onde a IA roda em produção.**
>
> São 27 anos em infraestrutura — comecei em 1999 com ASP e PHP num servidor NT zumbindo do
> lado da mesa — e os últimos três dedicados a LLM em produção.

📍 Barueri, São Paulo · remoto · [andrebassi.com.br](https://andrebassi.com.br) · [linkedin.com/in/andrebassi](https://linkedin.com/in/andrebassi) · contato@andrebassi.com.br

---

## Atuação

```yaml
apiVersion: engineering/v1
kind: Profile
metadata:
  name: andre-bassi
  location: Barueri, São Paulo, Brasil
spec:
  role: Consultor · Platform & AI Engineering
  experiencia: 27 anos (desde 1999)
  competencias_principais:
    - Large Language Models (LLM)
    - Kubernetes
    - Platform Engineer
    - Geração aumentada de recuperação (RAG)
    - SRE
  linguagens: [Go, Rust, Python]
  clouds: [AWS, GCP, Azure, OCI]
  aberto_a:
    - Staff / Principal Platform Engineer
    - AI Infrastructure
    - Cloud Architect
```

**MLOps e LLMOps** — pipelines RAG end-to-end com busca híbrida, re-ranking e pgvector; agentes
e multiagentes com LangChain/LangGraph; servidores MCP; avaliação, versionamento de prompt,
tracing de inferência e guardrails. Model serving com vLLM, NVIDIA Triton e NIM, runtime ONNX,
MLflow, Kubeflow e Ray — sobre workloads GPU, de GPU em nuvem sob demanda a Jetson Orin NX
embarcado, com offload camada a camada entre CPU e GPU. Integração com OpenAI, Anthropic
(Claude), Amazon Bedrock e Vertex AI.

**Plataforma e operação** — Kubernetes multi-cloud em produção (EKS, GKE, AKS, OCI, Talos),
Docker, Helm, Istio como service mesh, Kong como API Gateway, KEDA, GitOps com ArgoCD, CI/CD em
GitHub Actions e GitLab CI, IaC em Terraform e Pulumi. Observabilidade fim a fim — métricas,
logs e tracing distribuído com OpenTelemetry, Prometheus e Grafana. Redes, balanceamento de
carga, alta disponibilidade multi-região, RBAC, secrets management e políticas de segurança em
cloud. FinOps: custo medido por unidade de trabalho, não por fatura. Governança, auditoria e
LGPD em ambiente bancário e enterprise.

---

## O que construí, com os números medidos

| Projeto | O que é | Números | Stack |
|---|---|---|---|
| **[edgeProxy](https://github.com/andrebassi/edgeproxy)** · [docs](https://edgeproxy-docs.runner.codes/) | Proxy TCP/HTTP de edge. Geo-routing (MaxMind + Anycast), replicação SQLite via SWIM + QUIC, OpenTelemetry nativo, multi-PoP (GRU · IAD · SIN · FRA) | Substitui `nginx + haproxy + lua` por um binário de **~3 MB de RSS**, **p99 sub-milissegundo** no L4. **490+ testes** | Rust |
| **[Runner Codes](https://github.com/andrebassi/runner-codes)** · [runner.codes](https://runner.codes/) | Sandbox para código gerado por LLM em microVMs Firecracker. MCP-ready: o modelo escreve, o runner executa, o humano valida | **~125 ms** de cold-boot, **40+ runtimes** prontos. Open source sob **MPL-2.0** | Go · Firecracker · KVM |
| **[infra-operator](https://github.com/andrebassi/aws-infra-operator)** · [docs](https://infra-operator.runner.codes/) | Operator que declara recursos AWS (EKS, RDS, S3, IAM, VPC, Route53) como CRDs nativos | Reconciliação contínua, drift detection e rollback automático — IaC dentro do control loop | Go · Kubernetes |
| **AudioFlow** · [audioflow.pro](https://audioflow.pro) | SaaS em produção que transcreve áudio do WhatsApp com IA, sem depender da API oficial da Meta | **R$ 0,0072 de IA por minuto** processado, sustentando **94–97% de margem bruta**. Postmortem público do billing que cobrou **12× a mais** | Go hexagonal · Temporal · Next.js · Supabase |
| **Booster K1** · [deep-dive](https://andrebassi.com.br/2026.5/k1/) | Cérebro de voz de um humanoide de 22 graus de liberdade, embarcado | RAG de eventos de **93,5% → 100% de recall** num Jetson Orin NX de **8 GB** | Go hexagonal · Jetson Orin NX |
| **[AutoDJ](https://github.com/andrebassi/autodj)** · [autodj.andrebassi.com.br](https://autodj.andrebassi.com.br) | Tocador que mixa como DJ e anda sozinho — o áudio toca **no navegador**, o Go só mantém a agenda e decide a próxima faixa | BPM medido por `ffmpeg`/`aubio`, separação de voz por IA (Demucs) a **~US$ 0,001 por faixa**. **MIT** | Go · Next.js · Web Audio · Demucs |

---

## Stack

**Platform & Orchestration** `Kubernetes` · `Istio` · `Kong` · `KEDA` · `ArgoCD` · `Helm` · `Cilium` · `Talos`

**AI / LLM Infrastructure** `RAG` · `pgvector` · `LangChain` · `LangGraph` · `MCP` · `vLLM` · `NVIDIA Triton` · `NIM` · `ONNX` · `MLflow` · `Kubeflow` · `Ray` · `Bedrock` · `Vertex AI`

**Infrastructure as Code** `Terraform` · `Pulumi` · `Ansible` · `Crossplane`

**Observability & SRE** `OpenTelemetry` · `Prometheus` · `Grafana` · `FinOps`

**Languages** `Go` · `Rust` · `Python` · `Shell`

**Clouds** `AWS` · `GCP` · `Azure` · `OCI`

---

<details>
<summary><strong>🇺🇸 English</strong></summary>

<br>

**AI/LLM Engineer & Platform Engineer** — production RAG, agents and LLMOps · multi-cloud
Kubernetes AWS·GCP·Azure · Go · Rust · Python

> **I build the layer where AI runs in production.**
>
> 27 years in infrastructure — I started in 1999 with ASP and PHP on an NT server humming next
> to my desk — and the last three focused on LLMs in production.

**MLOps and LLMOps** — end-to-end RAG pipelines with hybrid search, re-ranking and pgvector;
agents and multi-agent systems with LangChain/LangGraph; MCP servers; evaluation, prompt
versioning, inference tracing and guardrails. Model serving with vLLM, NVIDIA Triton and NIM,
ONNX runtime, MLflow, Kubeflow and Ray — on GPU workloads, from on-demand cloud GPU to an
embedded Jetson Orin NX, with layer-by-layer offload between CPU and GPU.

**Platform and operations** — multi-cloud Kubernetes in production (EKS, GKE, AKS, OCI, Talos),
Docker, Helm, Istio as service mesh, Kong as API Gateway, KEDA, GitOps with ArgoCD, CI/CD on
GitHub Actions and GitLab CI, IaC in Terraform and Pulumi. End-to-end observability with
OpenTelemetry, Prometheus and Grafana. Networking, load balancing, multi-region high
availability, RBAC, secrets management and cloud security policies. FinOps: cost measured per
unit of work, not per invoice.

| Project | What it is | Measured | Stack |
|---|---|---|---|
| **[edgeProxy](https://github.com/andrebassi/edgeproxy)** | Edge TCP/HTTP proxy. Geo-routing (MaxMind + Anycast), SQLite replication over SWIM + QUIC, native OpenTelemetry, multi-PoP | Replaces `nginx + haproxy + lua` with a single **~3 MB RSS** binary, **sub-millisecond p99** at L4. **490+ tests** | Rust |
| **[Runner Codes](https://github.com/andrebassi/runner-codes)** | Sandbox for LLM-generated code on Firecracker microVMs. MCP-ready | **~125 ms** cold-boot, **40+ ready runtimes**. Open source under **MPL-2.0** | Go · Firecracker |
| **[infra-operator](https://github.com/andrebassi/aws-infra-operator)** | Go operator declaring AWS resources (EKS, RDS, S3, IAM, VPC, Route53) as native CRDs | Continuous reconciliation, drift detection and automatic rollback | Go · Kubernetes |
| **AudioFlow** · [audioflow.pro](https://audioflow.pro) | Production SaaS transcribing WhatsApp audio with AI | **R$ 0.0072 of AI per minute** processed, **94–97% gross margin**. Public postmortem of the billing bug that overcharged **12×** | Go · Temporal · Next.js |
| **Booster K1** · [deep-dive](https://andrebassi.com.br/2026.5/k1/) | Voice brain of a 22-degrees-of-freedom humanoid robot | Event RAG from **93.5% → 100% recall** on an 8 GB Jetson Orin NX | Go · Jetson Orin NX |
| **[AutoDJ](https://github.com/andrebassi/autodj)** | Autonomous DJ player — audio plays **in the browser**, Go only keeps the schedule | BPM via `ffmpeg`/`aubio`, AI voice separation (Demucs) at **~US$ 0.001 per track**. **MIT** | Go · Next.js · Web Audio |

Open to **Staff/Principal Platform Engineer**, **AI Infrastructure** and **Cloud Architect**
roles — remote or hybrid in São Paulo.

</details>

---

Aberto a **Staff/Principal Platform Engineer**, **AI Infrastructure** e **Cloud Architect** —
remoto ou híbrido em São Paulo.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/andrebassi)
[![Website](https://img.shields.io/badge/andrebassi.com.br-000?style=flat&logo=safari&logoColor=white)](https://andrebassi.com.br)
[![Email](https://img.shields.io/badge/contato-D14836?style=flat&logo=gmail&logoColor=white)](mailto:contato@andrebassi.com.br)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=flat&logo=twitter&logoColor=white)](https://twitter.com/andrebassi)
