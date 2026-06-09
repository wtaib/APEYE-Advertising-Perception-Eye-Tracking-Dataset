# APEYE: Advertising Perception Eye-Tracking Dataset

## Overview

APEYE (Advertising Perception Eye-Tracking Dataset) is a public dataset designed to support research on visual attention, advertisement effectiveness, eye-tracking analysis, and AI-assisted advertisement design.

The dataset was collected through a controlled webcam-based eye-tracking experiment involving 50 participants who viewed advertisements under five experimental conditions:

* A: Original advertisements
* B: Generic MLLM-enhanced advertisements
* C: Perception-aware Qwen 2.5 advertisements
* D: Perception-aware GPT-4o advertisements
* E: Perception-aware Gemini 1.5 Pro advertisements

The dataset contains gaze coordinates, fixation events, saccades, AOI annotations, and perceptual features extracted from advertisements.

---

## Dataset Contents

### Eye-Tracking Data

* Raw gaze coordinates (x, y)
* Timestamps
* Fixation duration
* Saccade trajectories
* Participant identifiers
* Advertisement identifiers

### AOI Metrics

For each advertisement and participant:

* Visual Attention Index (VAI%)
* Time To First Fixation (TTFF)
* Time To First Gaze (TTFG)
* Dwell Time
* Fixation Count
* Gaze Count
* K-Coefficient

### Advertisement Features

* Saliency maps
* Contrast measurements
* CTA bounding boxes
* Color hierarchy annotations
* AOI coordinates

---

## Experimental Design

* Participants: 50
* Product categories:

  * Food
  * Beverages
  * Fashion
  * Makeup
* Base advertisements: 10
* Conditions: 5
* Total stimuli: 50 advertisements

Each participant viewed only one version of each advertisement to eliminate memory and carryover effects.

---

## Directory Structure

```text
APEYE/
│
├── data/
│   ├── raw_gaze/
│   ├── fixations/
│   ├── saccades/
│   ├── aoi_metrics/
│   └── advertisement_features/
│
├── stimuli/
│   ├── original/
│   ├── generic/
│   ├── qwen/
│   ├── gpt4o/
│   └── gemini/
│
├── annotations/
│   ├── headline_aoi/
│   ├── product_aoi/
│   └── cta_aoi/
│
├── figures/
│
├── paper/
│
└── README.md
```

---

## Citation

If you use APEYE in your research, please cite:

```bibtex
@dataset{apeye2026,
  title={APEYE: Advertising Perception Eye-Tracking Dataset},
  author={Taib, Walid and Bruno, Alessandro and collaborators},
  year={2026},
  publisher={GitHub},
  url={https://github.com/walidtaib44/APEYE}
}
```

---

## License

This dataset is released under the CC BY 4.0 License.

---

## Contact

Walid Taib

AI Researcher, CNR-ISASI, Italy

GitHub: https://github.com/walidtaib44
