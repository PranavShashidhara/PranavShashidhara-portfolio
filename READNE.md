# Pranav Shashidhara — Personal Portfolio

Personal portfolio website for Pranav Shashidhara — MS Data Science @ UMD, ML Engineer, and former Technical Analyst at Oracle. Built as a single-file static HTML site, deployed via GitHub Pages.

## About

This portfolio covers:

- **Experience** — ML Engineering internship at UMD MTech Ventures (NSF I-Corps) and 3+ years as a Technical Analyst at Oracle
- **Projects** — LLMs, diffusion models, NLP, MLOps, big data, and distributed training
- **Skills** — PyTorch, XLM-RoBERTa, FSDP, AWS, PySpark, Docker, and more
- **Certifications** — AWS Solutions Architect Associate, Oracle SQL Certified Associate
- **Writing** — Technical articles published on Medium
- **Volunteering** — IEEE-SJCE and Oracle community programs

## Structure

```
portfolio/
├── index.html              # Entire site — single self-contained HTML file
└── PranavShashidhara.jpg   # Profile photo (referenced locally)
```

No build tools, no dependencies, no npm. Just open `index.html` in a browser or serve it with any static host.

## Running Locally

```bash
# Clone the repo
git clone https://github.com/PranavShashidhara/PranavShashidhara.github.io.git
cd PranavShashidhara.github.io

# Serve locally (Python 3)
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

> Opening `index.html` directly via `file://` may cause external links to be blocked by the browser. Always use a local server.

## Deployment

The site is deployed automatically via **GitHub Pages** from the `main` branch root.

To update:

```bash
git add .
git commit -m "update portfolio"
git push origin main
```

GitHub Pages will reflect changes within a minute or two.

## Featured Projects

| Project | Key Tech | Highlight |
|---|---|---|
| Segmentation-Guided Diffusion | PyTorch, U-Net, BraTS 2021 | FID 219→58, SSIM 0.26→0.72 |
| MediAssist AI | AWS Bedrock, RAG, BioGPT | 5–10x faster CPU inference |
| Multilingual Toxicity Classification | XLM-RoBERTa-Large, PyTorch DDP | 15+ languages, multi-task heads |
| Distributed LLM Orchestration (D-LOP) | FSDP, Llama 3.1 8B, Triton Kernels | Multi-GPU fine-tuning on RunPod |
| Movie Recommendation System | PySpark, Databricks, S3 | RMSE 0.917 on 100M Netflix records |
| Country Debt Default Prediction | LightGBM, Optuna, ADASYN | 99% accuracy, 97% macro F1 |
| End-to-End MLOps Pipeline | Docker, FastAPI, ONNX, CI/CD | Production-ready ML serving |
| HPC & CUDA Kernels | CUDA, Python, SLURM | Low-level GPU optimization |

## Tech Stack

- **Structure** — Pure HTML5, no frameworks
- **Fonts** — Syne, DM Sans, DM Mono (Google Fonts)
- **Styling** — Vanilla CSS with custom properties
- **Hosting** — GitHub Pages (static)

## Contact

- Email: [pshashid@umd.edu](mailto:pshashid@umd.edu)
- LinkedIn: [linkedin.com/in/pranav-shashidhara-8a614595](https://www.linkedin.com/in/pranav-shashidhara-8a614595/)
- GitHub: [github.com/PranavShashidhara](https://github.com/PranavShashidhara)
- Medium: [medium.com/@pranavmay22](https://medium.com/@pranavmay22)