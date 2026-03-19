
<div align="center">

# TracerAD

**TracerAD: Training-Free Few-Shot 3D Anomaly Detection for Novel PET Tracers**  
*MICCAI 2026 (Under Review)*

</div>

**Authors:** Haolin Huang*, Junlei Wu*, Jiaying Lu, Zhenrong Shen, Xinyu Wang, Chuantao Zuo, Qian Wang†  
**Research field:** Medical Imaging, Deep Learning

## Abstract
The deployment of PET tracers faces a cold-start dilemma in two common scenarios: when a novel tracer enters early clinical use with scarce healthy controls (HCs) and no diagnostic labels, and when an established tracer is introduced at a new site or resource-limited region where normative references have yet to be accumulated. Existing anomaly detection methods require large training cohorts or operate only on two-dimensional slices, failing to address the joint demands of extreme data scarcity and volumetric reasoning. We propose TracerAD, a training-free few-shot framework for three-dimensional brain PET anomaly detection that requires only a handful of HC scans and no model training. TracerAD extracts frozen vision foundation model features from registered brain volumes and detects pathological deviations at three spatial scales: coordinate-level focal detection (SAFD), atlas-constrained regional matching (RCSM), and graph-based inter-regional metabolic reasoning (TAMR), producing a clinically interpretable 3D anomaly heatmap. Evaluated on an amyloid PET dataset from the Alzheimer's Disease Neuroimaging Initiative (ADNI) under 1- to 10-shot settings, TracerAD achieves competitive detection performance without any training or fine-tuning, offering a practical tool for accelerating PET tracer deployment across diverse clinical settings.

---

**Code coming soon.**
