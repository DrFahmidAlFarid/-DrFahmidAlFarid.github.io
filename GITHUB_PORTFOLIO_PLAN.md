# GitHub Academic Portfolio Architecture

## Target structure: 7 core repositories

This portfolio is designed around research identity, reproducibility, and faculty/research visibility. It intentionally avoids creating one repository per publication unless a project has substantial standalone code.

### 1. DrFahmidAlFarid
**Role:** GitHub profile repository (special GitHub profile README).

Content:
- Academic identity and current position
- Research themes
- Selected recognition
- Academic profiles
- Featured projects/resources
- Website and contact links

**Action:** Rename/replace the legacy `Fahmid3358` repository with the exact GitHub username `DrFahmidAlFarid`.

---

### 2. DrFahmidAlFarid.github.io
**Role:** Central academic website and research-resource hub.

Content:
- Academic website
- Selected recent publications
- Code & Research Resources page
- Publication ↔ code/dataset index
- Links to all thematic repositories

This remains the authoritative navigation hub.

---

### 3. Smart-Farming-Computer-Vision
**Role:** Smart farming, precision agriculture and crop-disease AI.

Scope:
- Crop/leaf disease classification
- Lightweight CNN/Transformer models
- UAV/field vision
- Agricultural IoT
- Explainable plant-disease AI
- Public datasets and publication-linked resources

---

### 4. Medical-AI-XAI
**Role:** Medical imaging, clinical AI and explainability.

Scope:
- Medical image classification/segmentation
- Fundus/retinal AI
- MRI/radiograph analysis
- Grad-CAM, SHAP and interpretable AI
- Publication-linked code and datasets

---

### 5. Federated-Privacy-AI
**Role:** Federated learning, privacy-aware ML and collaborative AI.

Scope:
- Federated learning experiments
- Privacy-preserving medical AI
- FL + XAI
- Mixture-of-experts/federated architectures
- Reproducibility resources

This is separate from Medical-AI-XAI because federated/privacy methods extend beyond medical imaging.

---

### 6. Robotics-Computer-Vision
**Role:** Robotics, robot perception and intelligent automation.

Scope:
- ROS/ROS2
- NAO/BOTSBI research resources
- Robot vision
- Navigation/perception
- Human–robot interaction
- Vision-guided automation

Only institutionally/publicly shareable code should be published.

---

### 7. Industrial-AI-Fault-Diagnosis
**Role:** Industrial computer vision and intelligent fault diagnosis.

Scope:
- Wafer-map defect classification
- Bearing/fault diagnosis
- CNN/Transformer hybrid models
- Time-frequency representations
- Explainability and industrial condition monitoring

---

## What should NOT become separate repositories yet

These topics should remain indexed inside the relevant core repository until enough original code/resources justify a standalone project:

- Individual review papers
- Single notebooks
- Small teaching demonstrations
- One-off datasets hosted by third parties
- Co-author repositories without redistribution permission
- Individual publication codebases that are only links to another maintainer

## Repository quality standard

Every substantive research repository should eventually contain:

1. Clear README and research question
2. Associated publication title, authors and DOI
3. Ownership/contributor statement
4. Environment / requirements
5. Dataset acquisition instructions
6. Training and evaluation instructions
7. Results and sample outputs
8. License when redistribution rights are clear
9. CITATION.cff
10. Links to paper, dataset and academic website

## Visibility strategy

The strongest six repositories/projects should be pinned on the GitHub profile. The website remains the full portfolio; GitHub should emphasize reproducible research rather than publication count.

## Naming principle

Use stable descriptive names rather than paper acronyms for broad research repositories. Create a paper-specific repository only when the paper has substantial standalone original code, models, data or ongoing community value.
