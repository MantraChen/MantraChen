<div align="center">

```
██╗  ██╗ ██████╗ ██╗    ██╗██╗███████╗    ███████╗██╗   ██╗███╗   ██╗
██║  ██║██╔═══██╗██║    ██║██║██╔════╝    ██╔════╝██║   ██║████╗  ██║
███████║██║   ██║██║ █╗ ██║██║█████╗      ███████╗██║   ██║██╔██╗ ██║
██╔══██║██║   ██║██║███╗██║██║██╔══╝      ╚════██║██║   ██║██║╚██╗██║
██║  ██║╚██████╔╝╚███╔███╔╝██║███████╗    ███████║╚██████╔╝██║ ╚████║
╚═╝  ╚═╝ ╚═════╝  ╚══╝╚══╝ ╚═╝╚══════╝   ╚══════╝ ╚═════╝ ╚═╝  ╚═══╝
```

**Chief Technology Officer @ Kinepara**

*Kernel Security · Adversarial Systems · Algorithmic Engineering*

[![Email](https://img.shields.io/badge/CTO%40Kinepara.ai-000000?style=flat-square&logo=gmail&logoColor=white)](mailto:CTO@Kinepara.ai)
[![GitHub](https://img.shields.io/badge/MantraChen-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/MantraChen)
![Profile Views](https://komarev.com/ghpvc/?username=MantraChen&style=flat-square&color=red)

</div>

---

## Research & Engineering Focus

> I approach systems engineering as the disciplined intersection of **algorithmic rigor**, **kernel-level security**, and **adversarial resilience** — where correctness is a prerequisite, not an afterthought.

<br>

###  Concurrent & Cache-Conscious Data Structures

- Implementing **wait-free** and **lock-free** primitives (Ring Buffers, Skip Lists, Hazard Pointers) under strict atomic memory ordering
- Mitigating **ABA problems**, eliminating **false sharing**, and optimizing working-set locality via van Emde Boas layouts and CSR compression
- Reducing amortized complexity from $\mathcal{O}(n \log n)$ to $\mathcal{O}(n)$ through radix-based decomposition and cache-oblivious traversal strategies

<br>

###  Kernel Security & Low-Level Exploitation

- Researching privilege escalation vectors: **TOCTOU races**, **use-after-free** in kernel object lifecycles, and improper **capability / namespace isolation**
- Hardening kernel subsystems via **seccomp-BPF** policy design, **LSM hook** instrumentation, and mitigating **speculative execution** side-channels (Spectre/Meltdown variants)
- Analyzing **syscall interception** and **DKOM (Direct Kernel Object Manipulation)** as both attack surfaces and detection primitives

<br>

###  Anti-Cheat & Adversarial Systems

- Designing kernel-mode integrity monitors leveraging **PatchGuard**-equivalent callback chains and **SSDT hook** detection
- Applying **Bloom Filters** and **Count-Min Sketches** for high-throughput behavioral stream analysis under strict latency budgets
- Modeling cheat detection as an adversarial classification problem — balancing **false positive rate** against evasion resistance under a game-theoretic threat model $\mathcal{G} = \langle \mathcal{A}, \mathcal{D}, \mathcal{U} \rangle$
- Leveraging **hypervisor-assisted introspection** (VMI) for tamper-evident memory scanning beneath the OS trust boundary

<br>

###  Graph & Combinatorial Algorithms

- Optimizing flow, matching, and shortest-path algorithms for latency-critical detection pipelines
- Applying **DP over DAGs** and number-theoretic primitives to integrity verification and signature schemes

---

## Competitive Programming

| Competition | Distinction | Domain |
|:---|:---|:---|
| **National (NOI)** |  Medalist (Top Tier) | Advanced Data Structures & Algorithms |
| **Collegiate (ICPC/CCPC)** |  Regional Medalist | Combinatorics & Optimization |
| **Provincial** |  Multiple First Prizes | Heuristic Search & Number Theory |

---

## Engineering Philosophy

> *Reliability is not an accident.*

```rust
fn architecture() -> Result<System, Entropy> {
    match design {
        Design::FirstPrinciples => Ok(Scalability),
        Design::AdHoc          => Err(TechnicalDebt),
    }
}
```

Type systems and formal reasoning over runtime checks. Correctness by construction.

---

## Open To

```
Deep technical discourse on:
  ├── Systems Programming
  ├── Kernel Security Research
  └── Adversarial / Anti-Cheat Engineering
```

<div align="center">

*"Talk is cheap. Show me the code."* — Linus Torvalds

</div>
