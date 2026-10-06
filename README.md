# Awesome-Application-Performance-Monitoring-Apm 📊 🔍

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Application Performance Monitoring APM Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Application-Performance-Monitoring-Apm"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Application-Performance-Monitoring-Apm?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Application-Performance-Monitoring-Apm/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Application-Performance-Monitoring-Apm?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Application-Performance-Monitoring-Apm/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Application-Performance-Monitoring-Apm?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Application Performance Monitoring (APM) & Observability Ecosystem ⚡

**Curated List of Commercial APM Platforms & Open-Source Observability Alternatives**  
*Focused on Distributed Tracing, Code-Level Profiling, Error Tracking, Real User Monitoring (RUM), eBPF Profiling & Self-Hosted Telemetry Pipelines* 🚀  

**Last updated: October 2026** 📅

---

### 📌 SEO & Industry Overview 🔍
Welcome to the definitive curated directory of **application performance monitoring (APM) tools**, **distributed tracing backends**, **OpenTelemetry collector pipelines**, and **cloud-native observability frameworks**. Modern microservice architectures demand end-to-end telemetry across metrics, logs, traces, and continuous profiling. Whether you are evaluating enterprise SaaS solutions (*Datadog APM*, *New Relic*, *Dynatrace*, *Splunk Observability*) or deploying self-hosted open-source stacks (*SigNoz*, *Grafana Tempo*, *Jaeger*, *Apache SkyWalking*, *OpenObserve*), this repository provides comprehensive pricing comparisons, market valuations, and star counts.

---

## 📑 Table of Contents 📖
- [🏢 SaaS & Commercial APM Platforms](#-saas--commercial-apm-platforms)
- [🔓 Open-Source Observability Projects](#-open-source-observability-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📈 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer & Security](#%EF%B8%8F-disclaimer--security)

---

## 🏢 SaaS / Commercial APM Platforms 💼

> **Market Insights & Industry Dynamics:** 📊  
> The global Application Performance Monitoring (APM) and Observability market is estimated at **$5.5 Billion to $6.2 Billion in 2026** and projected to exceed **$12.5 Billion by 2032** (growing at a CAGR of ~11.8%). The market is **moderately concentrated** at the top tier among major full-stack telemetry providers (Datadog, Dynatrace, Cisco/Splunk/AppDynamics, AWS), while remaining **fragmented** in specialized developer-first verticals (error tracking, high-cardinality event analytics, and LLM tracing).

*Sorted by Company Valuation / Market Capitalization (Descending)* 📉

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap 💰 | Standard Edition Starting Price 🏷️ | Free Tier / Free Trial Limits 🎁 | Description & Core Features 📝 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[AWS Application Signals](https://aws.amazon.com/cloudwatch/)** ☁️ | Amazon Inc. | **~$2.0 Trillion** | Pay-as-you-go ($0.35/alarm/month, $0.05/1K metric requests, $0.50/GB ingested traces) | **Free Tier: 10 custom metrics, 5 GB log ingest, 1M trace requests/month forever** | **AWS-native APM** — Part of CloudWatch. Application Signals automatically instruments services, tracks SLOs, and correlates with AWS infrastructure resources. 🛠️ |
| **[AppDynamics](https://www.appdynamics.com/)** 🎯 | Cisco Systems Inc. | **~$200 Billion** | $60/month per CPU core (Infrastructure Monitoring Edition); $90/month per APM CPU core | **15-day free trial (up to 5 agents)**; no permanent free tier | **Enterprise APM** — Business transaction monitoring, code-level diagnostics, network visibility, and full-stack observability. Part of Cisco's enterprise security & visibility portfolio. 🏢 |
| **[Splunk APM](https://www.splunk.com/en_us/products/observability-cloud.html)** 📈 | Cisco Systems Inc. | **~$200 Billion** | $75/host/month (End-to-End edition, unmetered ingest); $60/host/month (App + Infra) | **14-day free trial (unlimited features, up to 15 hosts)**; no permanent free tier | **Streaming analytics APM** — Built on SignalFx and Omnition acquisitions. Per-host pricing with **unmetered telemetry ingest** — cost stays flat as log/trace volume grows. Real-time streaming analytics. ⚡ |
| **[Instana](https://www.ibm.com/products/instana)** ⚡ | IBM Corp. | **~$200 Billion** | $21.20/MVS/month (SaaS, annual); $385.20/MVS/year (Self-Hosted); $0.03/MVS-hour (PayPerUse) | **14-day free trial (full features, unlimited agents)**; no permanent free tier | **Automated APM & Observability** — 1-second monitoring granularity, automated discovery, 300+ technology integrations. Unlimited users included. Fair use: 325 GB data ingest per Standard SaaS MVS. 🤖 |
| **[Datadog APM](https://www.datadoghq.com/product/apm/)** 🐶 | Datadog Inc. | **~$40 Billion** | $31/host/month (APM & Continuous Profiler); $35/host/month (Pro); $40/host/month (Enterprise) | **14-day free trial (unlimited hosts and features)**; no permanent free tier | **Full-stack observability leader** — Distributed tracing, code profiling ($2/additional container beyond 4/host). Indexed spans: $1.70/million after 5M included. Ingested spans: $0.10/GB after 750 GB included. 📊 |
| **[Dynatrace](https://www.dynatrace.com/)** 🔮 | Dynatrace Inc. | **~$15 Billion** | $0.04/hour per host (Infrastructure); $0.01/memory-GiB-hour (Full-Stack APM) | **15-day free trial (1K host-hours included)**; no permanent free tier | **Causal AI for root cause** — Davis AI combines topology mapping with causal root-cause analysis. Commitment-based annual pricing with rate-card drawdown. No overage penalties. 🧠 |
| **[Elastic APM](https://www.elastic.co/apm/)** 🔍 | Elastic N.V. | **~$10 Billion** | $99/month (Standard, 120 GB RAM capacity, 2-zone reference); $114/month (Gold); $131/month (Platinum) | **14-day free trial (Elastic Cloud hosted)**; Free self-managed tier for basic Elastic Stack features | **OpenTelemetry-native APM** — Distributed tracing, metrics, and logs integrated into Elastic Stack. Deployment capacity (GB RAM/hour) is largest billing component. Full EDOT distribution support. 🔎 |
| **[New Relic](https://newrelic.com/)** 🚀 | New Relic Inc. | **~$5 Billion** | $99/user/month (Standard); $349/user/month (Pro, annual billing) + $0.40/GB ingested data | **Free Tier: 100 GB/month ingested data + 1 full-platform user forever** | **Consumption-based full-stack** — $0.40/GB standard data ingest, $0.60/GB Data Plus (HIPAA/FedRAMP compliant). 25+ language agents, 700+ integrations. No per-host charges. 📈 |
| **[Honeycomb](https://www.honeycomb.io/)** 🍯 | Honeycomb.io Inc. | **~$1.5 Billion** (Private) | Pro Plan: from $130/month (includes 1.5 Billion events/month); $3.00 per additional million events | **Free Tier: 20 Million events/month + 100 Million metrics data points forever** | **Event-based observability** — High-cardinality debugging, BubbleUp automated anomaly analysis, OpenTelemetry-native telemetry backend. Includes Time Series Metrics & Honeycomb Intelligence. 🐝 |
| **[Sentry](https://sentry.io/)** 🎯 | Functional Software Inc. | **~$1.0 Billion** (Private) | $26/month (Team plan, 50K errors/month); $80/month (Business plan, SSO & 90-day insights) | **Free Developer Tier: 5,000 errors/month, 10K transactions/month, 1 user forever** | **Developer-first error tracking + APM** — Five metered categories (errors, spans, replays, logs, attachments) each with separate quota. Seer AI debugging: $40/month per active code contributor. 🛠️ |

---

## 🔓 Open-Source Observability Projects 🌐

*Sorted by GitHub Stars Count (Descending)* 🌟

- **[Grafana Loki](https://github.com/grafana/loki)** [![Stars](https://img.shields.io/github/stars/grafana/loki?style=social&color=white)](https://github.com/grafana/loki/stargazers)  
  **Like Prometheus, but for logs**, AGPL-3.0 licensed. ~26k+ stars. Cost-efficient log aggregation system that indexes metadata rather than full payload text. Deeply integrated with Grafana and Tempo for full-stack telemetry correlation. 📝

- **[Apache SkyWalking](https://github.com/apache/skywalking)** [![Stars](https://img.shields.io/github/stars/apache/skywalking?style=social&color=white)](https://github.com/apache/skywalking/stargazers)  
  **Observability platform for distributed systems**, Apache-2.0 licensed. ~24k+ stars. APM, service mesh telemetry, eBPF profiling, and metrics aggregation. Built for cloud-native, microservices, and Kubernetes architectures. 🌌

- **[SigNoz](https://github.com/SigNoz/signoz)** [![Stars](https://img.shields.io/github/stars/SigNoz/signoz?style=social&color=white)](https://github.com/SigNoz/signoz/stargazers)  
  **Open-source Datadog alternative with OpenTelemetry-native APM**, Apache-2.0 licensed. ~22k+ stars. Unified logs, traces, and metrics in a single pane of glass. ClickHouse-powered backend for high-cardinality telemetry. Self-hosted or SigNoz Cloud. 📊

- **[Jaeger](https://github.com/jaegertracing/jaeger)** [![Stars](https://img.shields.io/github/stars/jaegertracing/jaeger?style=social&color=white)](https://github.com/jaegertracing/jaeger/stargazers)  
  **Distributed tracing platform originally created by Uber**, Apache-2.0 licensed. ~21k+ stars. End-to-end distributed tracing, root cause analysis, and service dependency mapping. CNCF graduated project. 🕵️

- **[Haystack](https://github.com/deepset-ai/haystack)** [![Stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=social&color=white)](https://github.com/deepset-ai/haystack/stargazers)  
  **AI orchestration & pipeline observability framework**, Apache-2.0 licensed. ~20k+ stars. Provides end-to-end tracing and performance monitoring for LLM pipelines and semantic search applications. 🔍

- **[Prometheus](https://github.com/prometheus/prometheus)** [![Stars](https://img.shields.io/github/stars/prometheus/prometheus?style=social&color=white)](https://github.com/prometheus/prometheus/stargazers)  
  **Systems monitoring and alerting toolkit**, Apache-2.0 licensed. ~55k+ stars. CNCF core project featuring time-series metrics collection, PromQL query language, and powerful alert management for APM pipelines. 🔥

- **[Pinpoint](https://github.com/pinpoint-apm/pinpoint)** [![Stars](https://img.shields.io/github/stars/pinpoint-apm/pinpoint?style=social&color=white)](https://github.com/pinpoint-apm/pinpoint/stargazers)  
  **APM for large-scale distributed systems**, Apache-2.0 licensed. ~13k+ stars. Java/PHP/Python agent-based monitoring with near-zero overhead. Interactive call stack visualization, real-time server topology maps, and active thread monitoring. 📍

- **[OpenObserve](https://github.com/openobserve/openobserve)** [![Stars](https://img.shields.io/github/stars/openobserve/openobserve?style=social&color=white)](https://github.com/openobserve/openobserve/stargazers)  
  **Cloud-native observability platform written in Rust**, Apache-2.0 licensed. ~12k+ stars. Unified logs, metrics, traces, and RUM in a single binary. Delivers up to 140x lower storage costs than traditional Elasticsearch setups. 🌊

- **[OpenTelemetry Collector](https://github.com/open-telemetry/opentelemetry-collector)** [![Stars](https://img.shields.io/github/stars/open-telemetry/opentelemetry-collector?style=social&color=white)](https://github.com/open-telemetry/opentelemetry-collector/stargazers)  
  **Vendor-neutral telemetry processing engine**, Apache-2.0 licensed. ~7k+ stars for Collector; 100+ language SDK libraries. CNCF industry standard for receiving, processing, and exporting telemetry data. 🔭

- **[Grafana Tempo](https://github.com/grafana/tempo)** [![Stars](https://img.shields.io/github/stars/grafana/tempo?style=social&color=white)](https://github.com/grafana/tempo/stargazers)  
  **High-scale distributed tracing backend**, AGPL-3.0 licensed. ~5k+ stars. Extremely cost-effective trace storage requiring only object storage (S3/GCS). Seamless integration with Grafana dashboarding and TraceQL querying. 📈

- **[Traceloop OpenLLMetry](https://github.com/traceloop/openllmetry)** [![Stars](https://img.shields.io/github/stars/traceloop/openllmetry?style=social&color=white)](https://github.com/traceloop/openllmetry/stargazers)  
  **OpenTelemetry-based observability for LLM applications**, Apache-2.0 licensed. ~5k+ stars. Tracing, prompt evaluation, and cost tracking for AI applications using OpenAI, Anthropic, LangChain, and LlamaIndex. 🤖

- **[Uptrace](https://github.com/uptrace/uptrace)** [![Stars](https://img.shields.io/github/stars/uptrace/uptrace?style=social&color=white)](https://github.com/uptrace/uptrace/stargazers)  
  **Open-source APM powered by OpenTelemetry & ClickHouse**, BSD-2-Clause licensed. ~3k+ stars. Unified distributed tracing, metrics, and log analysis platform with Prometheus and Zipkin ingestion support. 📉

- **[Glances](https://github.com/nicolargo/glances)** [![Stars](https://img.shields.io/github/stars/nicolargo/glances?style=social&color=white)](https://github.com/nicolargo/glances/stargazers)  
  **An Open Source Python-based cross-platform system monitoring tool**, LGPL-3.0 licensed. ~26k+ stars. Real-time CPU, memory, disk, network, and process performance monitoring with Web GUI and RESTful API. 💻

- **[Zipkin](https://github.com/openzipkin/zipkin)** [![Stars](https://img.shields.io/github/stars/openzipkin/zipkin?style=social&color=white)](https://github.com/openzipkin/zipkin/stargazers)  
  **Distributed tracing system**, Apache-2.0 licensed. ~16k+ stars. Helps gather timing data needed to troubleshoot latency problems in microservice architectures. Original pioneer of open distributed tracing. ⏱️

- **[Hypertrace](https://github.com/hypertrace/hypertrace)** [![Stars](https://img.shields.io/github/stars/hypertrace/hypertrace?style=social&color=white)](https://github.com/hypertrace/hypertrace/stargazers)  
  **Observability platform for cloud-native apps & microservices**, Apache-2.0 licensed. ~1.5k+ stars. Distributed tracing, service dependency graphs, and trace-to-log correlation built on OpenTelemetry. 🔗

- **[SkyWalking Rover](https://github.com/apache/skywalking-rover)** [![Stars](https://img.shields.io/github/stars/apache/skywalking-rover?style=social&color=white)](https://github.com/apache/skywalking-rover/stargazers)  
  **eBPF-based continuous profiler & network monitor for SkyWalking**, Apache-2.0 licensed. ~500+ stars. Low-overhead kernel-level CPU profiling and network latency monitoring for Linux environments. 🛰️

---

## 🛠️ How to Contribute 🤝

Contributions are welcome! Follow these steps to submit new APM platforms or open-source observability software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact star count badge, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Application-Performance-Monitoring-Apm&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Application-Performance-Monitoring-Apm&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship 💖

If you find this Application Performance Monitoring (APM) directory useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow developers, SREs, and DevOps engineers.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer & Security 🔒

- This is a **community-curated** directory — not an exhaustive list or direct commercial endorsement. ℹ️
- APM platforms ingest sensitive production telemetry (headers, SQL queries, user payloads). **Review data retention, masking rules, sampling rates, and privacy compliance (GDPR/HIPAA)** before committing data. 🔒
- Open-source APM solutions (SigNoz, OpenTelemetry, Jaeger, Grafana Tempo) provide self-hosted ownership and complete vendor neutrality, but enterprise-grade SLA guarantees, managed scaling, and 24/7 support remain primarily commercial offerings. 📊

---

<p align="center">
  <b>Made with ❤️ for developers, SREs, and open-source observability advocates.</b>
</p>
# Awesome-Application-Performance-Monitoring-Apm

# Awesome-Application-Performance-Monitoring-Apm 📊 🔍

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Application Performance Monitoring APM Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Application-Performance-Monitoring-Apm"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Application-Performance-Monitoring-Apm?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Application-Performance-Monitoring-Apm/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Application-Performance-Monitoring-Apm?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Application-Performance-Monitoring-Apm/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Application-Performance-Monitoring-Apm?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Application Performance Monitoring (APM) Ecosystem

**Curated List of Commercial APM Platforms & Open-Source Observability Alternatives**  
*Focused on Distributed Tracing, Code-Level Profiling, Error Tracking, Real User Monitoring & Self-Hosted Telemetry Pipelines*  

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary
Welcome to the ultimate curated directory of **application performance monitoring platforms**, **distributed tracing backends**, and **open-source observability frameworks**. Whether you are looking for enterprise-grade commercial solutions (such as *Datadog APM*, *New Relic*, *Dynatrace*, and *Elastic APM*), or self-hostable open-source alternatives (like *SigNoz*, *OpenTelemetry*, *Grafana Tempo*, and *Jaeger*), this list covers category leaders, OpenTelemetry-native pipelines, and privacy-respecting telemetry solutions.

---

## 📑 Table of Contents
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

The global APM market is expected to grow from **$10.2 billion in 2026 to $22.5 billion by 2033**, a 12.4% CAGR, driven by AI-native APM, OpenTelemetry adoption, and cloud-native architectures . Pricing models vary dramatically: Datadog charges per host ($31/month for APM, $35 for Pro, $40 for Enterprise) plus indexed spans ($1.70 per million after 5M included) , New Relic charges per user ($99-$349/month) plus per GB ingested ($0.40/GB after 100 GB free) , Dynatrace uses an annual commitment model with rate-card pricing ($0.04/hour per host) , Splunk Observability Cloud charges per host with unmetered ingest ($75/host/month for End-to-End edition) , Honeycomb bills per event ($3.00 per million events on Pro tier) , Instana charges per Managed Virtual Server ($21.20/MVS/month SaaS, $385.20/MVS/year self-hosted) , and Sentry meters across five categories with errors, spans, replays, logs, and attachments each having separate quotas and overage rates .

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Datadog APM](https://www.datadoghq.com/product/apm/)** 🐶 | Datadog Inc. | ~$40 Billion | $31/host/month (APM); $35 (Pro); $40 (Enterprise) | **14-day free trial**; no permanent free tier | **Full-stack observability with APM** — Distributed tracing, code profiling, continuous profiler ($2/additional container beyond 4/host). Indexed spans: $1.70/million after 5M included. Ingested spans: $0.10/GB after 750 GB included . |
| **[New Relic](https://newrelic.com/)** 🚀 | New Relic Inc. | ~$5 Billion | $99/user/month (Standard); $349/user/month (Pro, annual) | **Free tier: 100 GB/month ingest + 1 full platform user** | **Consumption-based full-stack** — $0.40/GB standard, $0.60/GB Data Plus (HIPAA/FedRAMP). 25+ language agents, 700+ integrations. No per-host fees . |
| **[Dynatrace](https://www.dynatrace.com/)** 🔮 | Dynatrace | ~$15 Billion | $0.04/hour per host (Infrastructure); $0.01/memory-GiB-hour (Full-Stack) | **15-day free trial**; no permanent free tier | **Causal AI for root cause** — Davis AI combines topology graph with causal analysis. Commitment-based annual pricing with rate-card drawdown. No overage premiums . |
| **[AppDynamics](https://www.appdynamics.com/)** 🎯 | Cisco (Acquired 2017) | ~$200 Billion (Cisco) | Enterprise: $5,093.99/license (term); Premium: $8,409.99/license | No free tier; enterprise sales-quoted | **Enterprise APM** — Business transaction monitoring, code-level diagnostics, infrastructure visibility. Part of Cisco's full-stack observability portfolio . |
| **[Elastic APM](https://www.elastic.co/apm/)** 🔍 | Elastic N.V. | ~$10 Billion | Standard: $99/month (120 GB, 2-zone reference); Gold: $114; Platinum: $131; Enterprise: $184 | **14-day free trial**; free tier for some features | **OpenTelemetry-native APM** — Distributed tracing, metrics, logs integrated into Elastic Stack. Deployment capacity (GB RAM/hour) is largest billing component. EDOT (Elastic Distribution for OpenTelemetry) supported . |
| **[Splunk APM](https://www.splunk.com/en_us/products/observability-cloud.html)** 📈 | Cisco (Acquired Splunk) | ~$200 Billion (Cisco) | End-to-End: $75/host/month (unmetered ingest); App+Infra: $60/host/month | **Free up to 15 hosts** | **Streaming analytics APM** — Built on SignalFx and Omnition acquisitions. Per-host pricing with **unmetered telemetry ingest** — cost stays flat as logs/traces grow. Real-time streaming analytics . |
| **[Honeycomb](https://www.honeycomb.io/)** 🍯 | Honeycomb.io | Private | Pro: from $130/month (1.5B events included); $3.00/million events | **Free: up to 20M events/month, 100M metrics data points** | **Event-based observability** — High-cardinality debugging, BubbleUp analysis, OpenTelemetry-native. 2026 Pro pricing includes Time Series Metrics and Honeycomb Intelligence . |
| **[Instana](https://www.ibm.com/products/instana)** ⚡ | IBM | ~$200 Billion | SaaS: from $21.20/MVS/month; Self-Hosted: from $385.20/MVS/year; PayPerUse: $0.03/MVS-hour | **14-day free trial** | **Automated APM** — 1-second monitoring granularity, automatic discovery, 300+ technologies. Unlimited users. Fair use: 325 GB data ingest per Standard SaaS MVS . |
| **[Sentry](https://sentry.io/)** 🎯 | Sentry | Private | Team: $26/month (50K errors); Business: $80/month (SSO, 90-day insights) | **Free Developer: 5K errors/month, 1 user** | **Developer-first error tracking + APM** — Five metered categories (errors, spans, replays, logs, attachments) each with own quota. Seer AI debugging: $40/month per active code contributor . |
| **[AWS Application Signals](https://aws.amazon.com/cloudwatch/)** ☁️ | Amazon | ~$2.0 Trillion | CloudWatch: pay-as-you-go for metrics, logs, traces | **Free tier: limited CloudWatch metrics and alarms** | **AWS-native APM** — Part of CloudWatch. Application Signals automatically instruments services, tracks SLOs, and correlates with AWS resources. |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub_Stars_Count (Descending)* 🌟

- **[SigNoz](https://github.com/SigNoz/signoz)** [![Stars](https://img.shields.io/github/stars/SigNoz/signoz?style=social&color=white)](https://github.com/SigNoz/signoz/stargazers)  
  **Open-source Datadog alternative with OpenTelemetry-native APM**, Apache-2.0 licensed. ~22k+ stars. Unified logs, traces, and metrics in a single pane. ClickHouse-powered for high-cardinality data. Built-in dashboards, alerts, and exception tracking. Thoughtworks Technology Radar: Trial — reduces infrastructure resource consumption and overall observability costs without compromising performance. Self-hosted or SigNoz Cloud.  📊

- **[Jaeger](https://github.com/jaegertracing/jaeger)** [![Stars](https://img.shields.io/github/stars/jaegertracing/jaeger?style=social&color=white)](https://github.com/jaegertracing/jaeger/stargazers)  
  **Distributed tracing platform by Uber**, Apache-2.0 licensed. ~21k+ stars. End-to-end distributed tracing, root cause analysis, service dependency analysis. OpenTelemetry-native. CNCF graduated project.  🕵️

- **[OpenTelemetry](https://github.com/open-telemetry/opentelemetry-collector)** [![Stars](https://img.shields.io/github/stars/open-telemetry/opentelemetry-collector?style=social&color=white)](https://github.com/open-telemetry/opentelemetry-collector/stargazers)  
  **Vendor-neutral observability framework**, Apache-2.0 licensed. ~7k+ stars for Collector; 100+ instrumentation libraries across languages. The emerging standard for telemetry collection. Supported natively by Datadog, New Relic, Dynatrace, Elastic, Splunk, Honeycomb, and Instana.  🔭

- **[Grafana Tempo](https://github.com/grafana/tempo)** [![Stars](https://img.shields.io/github/stars/grafana/tempo?style=social&color=white)](https://github.com/grafana/tempo/stargazers)  
  **High-scale distributed tracing backend**, AGPL-3.0 licensed. ~5k+ stars. Cost-efficient trace storage that only requires object storage. Deep integration with Grafana, Loki, and Prometheus. TraceQL query language.  📈

- **[Grafana Loki](https://github.com/grafana/loki)** [![Stars](https://img.shields.io/github/stars/grafana/loki?style=social&color=white)](https://github.com/grafana/loki/stargazers)  
  **Log aggregation system**, AGPL-3.0 licensed. ~26k+ stars. Like Prometheus but for logs. Indexes only metadata for cost efficiency. Integrated with Grafana for unified observability.  📝

- **[Apache SkyWalking](https://github.com/apache/skywalking)** [![Stars](https://img.shields.io/github/stars/apache/skywalking?style=social&color=white)](https://github.com/apache/skywalking/stargazers)  
  **Observability platform for distributed systems**, Apache-2.0 licensed. ~24k+ stars. APM, service mesh telemetry, eBPF profiling, and metrics aggregation. Designed for cloud-native, microservices, and containerized architectures. CNCF graduated project.  🌌

- **[Pinpoint](https://github.com/pinpoint-apm/pinpoint)** [![Stars](https://img.shields.io/github/stars/pinpoint-apm/pinpoint?style=social&color=white)](https://github.com/pinpoint-apm/pinpoint/stargazers)  
  **APM for large-scale distributed systems**, Apache-2.0 licensed. ~13k+ stars. Java/PHP/Python agent-based monitoring with minimal performance impact. Call stack visualization, server map, and real-time active thread monitoring.  📍

- **[Uptrace](https://github.com/uptrace/uptrace)** [![Stars](https://img.shields.io/github/stars/uptrace/uptrace?style=social&color=white)](https://github.com/uptrace/uptrace/stargazers)  
  **Open-source APM with OpenTelemetry**, BSD-2-Clause licensed. ~3k+ stars. Distributed tracing, metrics, and logs in a unified platform. ClickHouse-based. Processes **billions of spans on a single server** at 10x lower cost. 50+ pre-built dashboards, Grafana compatibility.  📉

- **[Hypertrace](https://github.com/hypertrace/hypertrace)** [![Stars](https://img.shields.io/github/stars/hypertrace/hypertrace?style=social&color=white)](https://github.com/hypertrace/hypertrace/stargazers)  
  **Observability platform for cloud-native apps**, Apache-2.0 licensed. ~1.5k+ stars. Distributed tracing, service graph, and trace-to-log correlation. Built on OpenTelemetry and Jaeger.  🔗

- **[OpenObserve](https://github.com/openobserve/openobserve)** [![Stars](https://img.shields.io/github/stars/openobserve/openobserve?style=social&color=white)](https://github.com/openobserve/openobserve/stargazers)  
  **Cloud-native observability platform**, Apache-2.0 licensed. ~12k+ stars. Logs, metrics, traces, and RUM in one platform. **140x lower storage costs than Elasticsearch**. Rust-based, single binary.  🌊

- **[SkyWalking Rover](https://github.com/apache/skywalking-rover)** [![Stars](https://img.shields.io/github/stars/apache/skywalking-rover?style=social&color=white)](https://github.com/apache/skywalking-rover/stargazers)  
  **eBPF-based profiling for SkyWalking**, Apache-2.0 licensed. ~500+ stars. Continuous profiling with eBPF, network monitoring, and process-level observability.  🛰️

- **[Traceloop OpenLLMetry](https://github.com/traceloop/openllmetry)** [![Stars](https://img.shields.io/github/stars/traceloop/openllmetry?style=social&color=white)](https://github.com/traceloop/openllmetry/stargazers)  
  **OpenTelemetry-based observability for LLM applications**, Apache-2.0 licensed. ~5k+ stars. Tracing, metrics, and evaluation for AI/LLM applications. Vendor-neutral instrumentation for OpenAI, Anthropic, LangChain, and more.  🤖

- **[Coroot](https://github.com/coroot/coroot)** [![Stars](https://img.shields.io/github/stars/coroot/coroot?style=social&color=white)](https://github.com/coroot/coroot/stargazers)  
  **Open-source observability with zero instrumentation**, Apache-2.0 licensed. ~5k+ stars. eBPF-based metrics, logs, traces, profiles, and continuous profiling. Automatically detects anomalies and root causes. The only open-source tool combining metrics, logs, traces, and profiling with pre-built dashboards.  🎯

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new APM platforms or open-source observability software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Application-Performance-Monitoring-Apm&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Application-Performance-Monitoring-Apm&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this application performance monitoring repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow developers, SREs, and DevOps engineers.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- APM platforms ingest sensitive production telemetry. **Review data retention, sampling, and privacy policies** before committing. Datadog's indexed span retention defaults to 15 days , while Splunk's per-host pricing includes unmetered ingest but crossover points vary by workload . 🔒
- Open-source APM solutions (SigNoz, OpenTelemetry, Jaeger, Grafana Tempo, Coroot) provide self-hosted ownership and vendor neutrality, but enterprise-grade SLA guarantees, managed scaling, and vendor support remain primarily commercial offerings. 📊

---

<p align="center">
  <b>Made with ❤️ for developers, SREs, and open-source observability advocates.</b>
</p>
