# Hi, I'm Prakash Saini 👋

### HPC & AI Inference Engineer

I build **GPU-accelerated, distributed systems for scientific computing and AI inference**: MPI solvers that scale across hundreds of ranks, CUDA and Triton kernels tuned against hardware limits, and LLM and model-serving stacks measured on latency, throughput, and cost.

Currently at **QubitSolve**, engineering a hybrid quantum-classical CFD platform on **AWS ParallelCluster, Slurm, MPI, and NVIDIA GPUs**, plus its inference layer (vLLM, TensorRT, Triton Inference Server). Before that, I built high-availability backend and event-streaming systems at **HPE** and **Nokia**.

---

## ⚡ Highlights

- **HPC scaling:** cut a lattice Boltzmann CFD timestep from **184 s to 0.16 s (~1,150x)**, with a hierarchical MPI decomposition scaling **145.7x at 243 ranks**
- **GPU kernels:** custom **CUDA C and Triton kernels at ~480-505 MLUPS on an NVIDIA L40S** (~12x CuPy, 36-38% of peak DRAM bandwidth), profiled with Nsight Compute and Nsight Systems
- **LLM inference:** benchmarked **vLLM and SGLang** on Qwen3-8B. FP8 KV cache doubled KV capacity for **1.59x throughput** with zero preemptions at 128 concurrent requests, and prefix caching delivered **2.6x** on shared prompts
- **Model serving:** deployed a PyTorch CFD surrogate on **Triton Inference Server with FP16 TensorRT** (batch-64 engine latency 7.90 → 2.87 ms); rejected INT8 after rollout-error validation
- **Reliability at load:** held **99.9% availability and sub-200 ms p95** through 10x rollout bursts on an HPE GreenLake control plane
- **Research:** co-author, *"Toward Quantum Advantage in Computational Fluid Dynamics: A Variational Lattice Boltzmann Approach,"* accepted to **AIAA SciTech 2027**

---

## 🛠️ Tech Stack

**Languages**  
Python · C · C++ · Go · Bash

**HPC & Parallel Computing**  
MPI · Slurm · AWS ParallelCluster · NCCL · strong scaling · checkpoint/restart · Qiskit Aer · cuQuantum/cuStateVec

**GPU & Kernels**  
CUDA C · Triton kernels · Nsight Compute · Nsight Systems · CuPy · PyTorch

**AI Inference & Serving**  
vLLM · SGLang · TensorRT · Triton Inference Server · FP8 quantization · KV-cache management · prefix caching · continuous batching · tensor parallelism

**Distributed Systems & Cloud**  
Kafka · FastAPI · PostgreSQL · Redis · AWS · Docker · Kubernetes · Terraform · GitHub Actions

**Observability & Performance**  
Prometheus · Grafana · OpenTelemetry · Nsight profiling · benchmarking

---

## 🔬 Areas I Work On

- **High-Performance Computing:** MPI decomposition, scaling studies, Slurm workload modeling, and cluster automation on AWS
- **GPU Performance:** kernel fusion, occupancy and memory-bandwidth tuning, GPU-resident execution, multi-GPU communication
- **AI Inference:** LLM serving engines, quantization (FP8/FP16/INT8), KV-cache capacity, batching, and latency/throughput trade-offs
- **Model Serving:** TensorRT engine builds, Triton Inference Server, accuracy gates before deployment
- **Distributed Systems:** high-availability control planes, Kafka pipelines, SLOs, and incident response

---

## 📚 Engineering & Open Source

- [Distributed Systems](https://github.com/Prakash-sa/dragonglass-redis)
- [Backend & Real-Time Systems](https://github.com/Prakash-sa/ride-matching-go)
- [AI & RAG Systems](https://github.com/Prakash-sa/local-rag)
- [System Design](https://github.com/Prakash-sa/system-design-ultimatum)
- [Low-Level Design](https://github.com/Prakash-sa/low-level-design-ultimatum)
- [Algorithms & Data Structures](https://github.com/Prakash-sa/Competitive-Programming)

Explore my [repositories](https://github.com/Prakash-sa?tab=repositories) or the pinned projects below.

---

## 🤝 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sainiprakash525/)
