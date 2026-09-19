<div align="center">

<img src="assets/about.png" alt="Anirudh Sharma" width="720">

</div>

&nbsp;

I'm a machine learning engineer who likes being close to the metal — training models, wiring up agents, and building the unglamorous data plumbing that makes any of it work in production. I came to AI through mathematics and never really left; the parts I enjoy most are where a clean idea survives contact with messy real-world data.

Right now I'm building LLM-agent automation at a nonprofit, and I just finished my M.S. at Stevens, where my research was on making tool-using agents actually reliable. My portfolio is a terminal you can poke around in: **[anirudhksharma.com](https://www.anirudhksharma.com)**.

&nbsp;

### What I've been building

**FraudSight AI** — an agentic pipeline that reads images and PDFs for AI-generated artifacts and document forgery. A vision agent does the forensic pass (physics that doesn't add up, "melting" structure, off fonts), then three models — Qwen-VL-Plus, DeepSeek R1, GLM 4.6 — vote on the verdict. 72% accuracy on real claims, and a routing trick that cut token cost by half to three-quarters.

**Agent reliability research at Stevens** — I worked on ShoppingBench ([arXiv:2508.04266](https://arxiv.org/abs/2508.04266)), a 2.5M-product agent benchmark. Forcing strictly-typed tool schemas onto Qwen-2.5-72B took its format score from 0.47 to 0.72 and killed 100% of the parameter hallucinations, at the cost of some retry friction I measured in an ablation. Shipped a Streamlit dashboard so the trade-offs were visible, not just in a table.

**Diabetic retinopathy classification** — EfficientNet-B0 on 143K retinal images (~22 GB), 87% balanced accuracy. The interesting part was the infra: a PySpark Random Forest baseline across a small cluster cut training time by more than half.

**Adversarial robustness** — FGSM attacks on CIFAR-10, watching a CNN fall from 78.6% to ~2.3% accuracy under a tiny perturbation, then clawing robustness back with min-max adversarial training. A good lesson in the gap between benchmark accuracy and worst-case behavior.

Wildlife side project in progress: re-identifying individual jaguars from camera-trap photos for a Kaggle conservation challenge.

&nbsp;

### The stack I reach for

Python and C++ for the work, PyTorch and TensorFlow for models, PySpark / Pandas / Polars when the data outgrows one machine. AWS and Azure for infra, FastAPI when something needs to be served, Elasticsearch and Postgres for storage, and MCP lately for wiring agents into real tools. **AWS Certified Machine Learning Engineer – Associate.**

&nbsp;

### Elsewhere

[Portfolio](https://www.anirudhksharma.com) · [LinkedIn](https://www.linkedin.com/in/anirudh-sharma-650b93252/) · [Medium](https://medium.com/@anirudhksharma02) · anirudhksharma02@gmail.com
