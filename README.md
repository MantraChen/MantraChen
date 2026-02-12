# HowieSun

**Chief Technology Officer @ Kinepara | Systems Researcher**
*Focusing on High-Performance Computing and Kernel Security.*

---

### $\mathcal{1}$ / Research & Engineering Focus

My work bridges the gap between **theoretical algorithms** and **production-grade infrastructure**. I specialize in designing deterministic systems within non-deterministic environments, prioritizing memory safety and instruction-level parallelism.

* **Systems Architecture**: $\text{Rust} \times \text{C++20}$. Expertise in zero-cost abstractions, lock-free concurrency, and SIMD/AVX optimization.
* **Adversarial Engineering**: Kernel-level behavioral analysis, heuristic detection models, and obfuscation techniques against reverse engineering.
* **Computational Perception**: Implementing real-time 3D reconstruction pipelines and sensor fusion algorithms on heterogenous hardware (RISC-V/ARM).

### $\mathcal{2}$ / Research & Engineering Focus

I perceive systems engineering as the rigorous application of advanced data structures to manage **complexity** and **concurrency**. My research focuses on designing cache-oblivious algorithms and specialized memory layouts.

* **Concurrent Data Structures**:
    * Implementing **Wait-free** and **Lock-free** synchronization primitives (e.g., Ring Buffers, Skip Lists) using atomic memory ordering.
    * Mitigating **ABA problems** and optimizing for **False Sharing** in multi-core environments.

* **Spatial & Geometric Indexing** *(Relevant to Computer Vision/MoCap)*:
    * Accelerating ray-tracing and collision detection via **BVH (Bounding Volume Hierarchies)** and **KD-Trees**.
    * Optimizing spatial hashing for sparse volume data in $\mathbb{R}^3$ space.

* **Succinct & Probabilistic Structures** *(Relevant to Security/Anti-Cheat)*:
    * Leveraging **Bloom Filters** and **Count-Min Sketches** for high-throughput, memory-constrained stream processing.
    * Designing **Intrusive Containers** to minimize memory fragmentation and pointer chasing.

* **Asymptotic Optimization**:
    * Reducing amortized time complexity from $\mathcal{O}(n \log n)$ to $\mathcal{O}(n)$ through radix-based approaches and data locality optimizations.

### $\mathcal{3}$ / Algorithmic Excellence

*Background in competitive programming with a focus on Graph Theory, Computational Geometry, and Dynamic Programming.*

| **Competition Level** | **Distinction** | **Domain** |
| :--- | :--- | :--- |
| **National (NOI)** | **Medalist** (Top Tier) | Advanced Data Structures & Algorithms |
| **Collegiate (ICPC/CCPC)** | **Regional Medalist** | Combinatorics & Optimization |
| **Provincial** | **Multiple First Prizes** | Heuristic Search & Number Theory |

### $\mathcal{4}$ / Engineering Philosophy

I advocate for code correctness through type systems and formal reasoning rather than extensive runtime checks.

```rust
// "Reliability is not an accident."
fn architecture() -> Result<System, Entropy> {
    match design {
        Design::FirstPrinciples => Ok(Scalability),
        Design::AdHoc => Err(TechnicalDebt),
    }
}
```
### $\mathcal{5}$ / Connect

Open to deep technical discourse regarding **systems programming**, **security research**, and **embedded vision**.

* **PGP / Email:** `CTO@Kinepara.ai`
* **GitHub:** `github.com/MantraChen`

---

*“Talk is cheap. Show me the code.”* — Linus Torvalds
