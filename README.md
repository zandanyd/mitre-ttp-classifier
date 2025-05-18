# MITRE TTP Classifier from Cybersecurity Blogs

This project fine-tunes a SciBERT-based model to automatically detect MITRE ATT&CK techniques from sentences extracted from threat intelligence blogs.  
It is based on and extends the [TRAM project](https://github.com/center-for-threat-informed-defense/tram) by the Center for Threat-Informed Defense.

---

## 🔍 Overview

The goal is to assist cybersecurity analysts by surfacing relevant MITRE TTPs from long-form blog content, using a contextual multi-label classification model.

---

## 📚 Dataset

- Total samples: 19,178 sentences  
- Labeled samples: 4,070 with one or more MITRE techniques  
- Format: JSON file with `text`, `labels`, and optional `probabilities`
