# Anirudh Sharma

Machine learning engineer. I build models, the agents that use them, and the data pipelines underneath. Just finished my M.S. at Stevens and I'm currently doing LLM-agent automation at a nonprofit.

Portfolio (it's a terminal you can type into): [anirudhksharma.com](https://www.anirudhksharma.com)

### Projects

**FraudSight AI.** Agentic pipeline that checks images and PDFs for AI-generated artifacts and document forgery. A vision agent does the forensic pass, then Qwen-VL-Plus, DeepSeek R1, and GLM 4.6 vote on the result. 72% accuracy on real claims; prompt routing cut token cost 50-75%.

**Agent reliability (Stevens research).** Worked on ShoppingBench, a 2.5M-product agent benchmark ([arXiv:2508.04266](https://arxiv.org/abs/2508.04266)). Adding strictly-typed tool schemas raised Qwen-2.5-72B's format score from 0.47 to 0.72 and removed all parameter hallucinations, at the cost of extra retries I traced in an ablation. Built a Streamlit dashboard to compare runs.

**Diabetic retinopathy.** EfficientNet-B0 on 143K retinal images (~22 GB), 87% balanced accuracy. A PySpark Random Forest baseline on a small cluster cut training time by more than half.

**Adversarial robustness.** FGSM attacks on CIFAR-10. A CNN dropped from 78.6% to about 2.3% accuracy under a small perturbation; min-max adversarial training got most of it back.

**Jaguar re-ID (in progress).** Matching individual jaguars across camera-trap photos for a Kaggle conservation challenge.

### Stack

Python, C++. PyTorch and TensorFlow. PySpark, Pandas, Polars when data outgrows one box. AWS, Azure, FastAPI, Postgres, Elasticsearch. MCP for agent tooling lately. AWS Certified Machine Learning Engineer, Associate.

### Links

[Portfolio](https://www.anirudhksharma.com) · [LinkedIn](https://www.linkedin.com/in/anirudh-sharma-650b93252/) · [Medium](https://medium.com/@anirudhksharma02) · anirudhksharma02@gmail.com
