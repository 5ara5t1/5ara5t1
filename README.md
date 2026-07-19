# Bryce Fitzgerald

Infrastructure engineer gone down the stack — 4.5 years of production
infrastructure and observability, now doing GPU and LLM inference performance
work in public. B.S. Physics (Photonics & Lasers), SIUE, 2026.

**Focus:** inference performance along the memory and data-movement stack —
kernels, attention/KV-cache, serving systems. From shared-memory tiling to
cluster-level cache-aware routing, it's one problem: compute is cheap, bytes
are not.

Edwardsville, Illinois — relocating for the right team (SF Bay Area, Seattle,
Austin, NYC).

## Now

**[sgemm-worklog](https://github.com/5ara5t1/sgemm-worklog)** — stepwise
SGEMM on Turing (RTX 2070 Super): naive → coalesced → shared-memory tiling →
register blocking → vectorized loads → double buffering → tensor cores. Every
step benchmarked against cuBLAS and profiled with Nsight Compute. Progress is
live on main.

## Next, in order

1. FlashAttention forward from scratch (fp16, tensor cores), benchmarked
   against PyTorch SDPA
2. Single-GPU paged-KV serving engine in C++/CUDA — continuous batching,
   prefix reuse, first-class metrics endpoint — benchmarked against vLLM,
   with a written gap analysis
3. Go serving load generator — streaming TTFT/TPOT percentiles, Poisson
   arrivals, multi-turn trace replay
4. Upstream: vLLM / llm-d benchmark and perf-tooling contributions

## Experience

**Engineer 1, Software Enablement — Infrastructure & Observability** —
Abercrombie & Fitch, October 2023 – May 2026. On the Digital Engineering
observability team running monitoring and alerting across ~500 production
services (Splunk, Dynatrace, SolarWinds, ServiceNow, OCI, Azure). Personally
built the integration wiring OCI database alerts into automated ServiceNow
incident creation; owned the SolarWinds Orion deployment end-to-end.

**ML Infrastructure Engineer** — C.H. Robinson, May 2022 – May 2023 (remote).
Stood up ML data-platform infrastructure on Azure: Kubernetes (AKS) with Helm,
Terraform and Atlantis for infrastructure-as-code, Azure DevOps for CI/CD.
Operated Airflow orchestration (Astronomer) supporting data discovery and
exploration workflows, with Snowflake and other databases for storage and
analytics. Platform monitoring with Prometheus and Grafana.

**Big Data Engineer** — Techolution, October 2021 – May 2022 (remote).
Designed and operated 10+ asynchronous data processing pipelines on GCP
(Apache Beam, Cloud Dataflow) for a Fortune 500 client.

**Research Assistant** — Southern Illinois University Edwardsville, August
2021 – January 2022. Parallelized a hybrid genetic/swarm metaheuristic
optimization package (MATLAB) on the university's distributed HPC cluster;
automated benchmarking against 21 trial functions.

## Education

B.S. Physics, Specialization in Photonics and Lasers — Southern Illinois
University Edwardsville, 2022–2026. Completed concurrently with the full-time
roles above.

## Contact

brycefitzgerald.careers@gmail.com ·
[LinkedIn](https://www.linkedin.com/in/bryce-fitzgerald)
