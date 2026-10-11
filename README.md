# Audio Classification Project Archive

Empty repository at the start of this refinement.


## Rebuild the reading edition

```bash
python -m pip install -r requirements-research.txt
python scripts/build_research_site.py
```

This renders saved notebook outputs without rerunning model training or external APIs. To refresh findings, run the analysis commands above first, update `reports/research-findings.md`, and rebuild.

<!-- research-edition:start -->
## Research edition

[Research report and final visual results](research/report.md) · [Browser-ready notebook catalogue](research/notebooks.html)

Archive only. No implementation, dataset, experiment or result metric is available. This repository is not presented as a completed research study.


The `research/` folder contains a professional static reading edition. The Pages workflow deploys it after GitHub Pages is enabled with **GitHub Actions** as the publishing source. Intended URL: `https://adeen1607.github.io/ML-AUDIO_CLASSIFICATION/`. Deployment status must be checked in Actions before treating that address as live.

<!-- research-edition:end -->
