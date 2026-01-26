# HyperCOD

## 📖 Paper
The paper "HyperCOD: The First Challenging Benchmark and Baseline for Hyperspectral Camouflaged Object Detection" has been accepted at AAAI 2026. Paper now is available at https://arxiv.org/abs/2601.03736.

### Abstract

RGB-based camouflaged object detection struggles in real-world scenarios where color and texture cues are ambiguous. While hyperspectral image offers a powerful alternative by capturing fine-grained spectral signatures, progress in hyperspectral camouflaged object detection (HCOD) has been critically hampered by the absence of a dedicated, large-scale benchmark. To spur innovation, we introduce HyperCOD, the first challenging benchmark for HCOD. Comprising 350 high-resolution hyperspectral images, It features complex real-world scenarios with minimal objects, intricate shapes, severe occlusions, and dynamic lighting to challenge current models.
The advent of foundation models like the Segment Anything Model (SAM) presents a compelling opportunity. To adapt the Segment Anything Model (SAM) for HCOD, we propose HyperSpectral Camouflage-aware SAM (HSC-SAM). HSC-SAM ingeniously reformulates the hyperspectral image by decoupling it into a spatial map fed to SAM's image encoder and a spectral saliency map that serves as an adaptive prompt. This translation effectively bridges the modality gap. Extensive experiments show that HSC-SAM sets a new state-of-the-art on HyperCOD and generalizes robustly to other public HSI datasets. The HyperCOD dataset and our HSC-SAM baseline provide a robust foundation to foster future research in this emerging area.

## 📊 Dataset
### Overview
Our HyperCOD dataset comprises 350 high-quality hyperspectral images, each containing 200 spectral bands spanning 400–1000 nm with a spatial resolution of 1240 × 1680 pixels. The dataset is partitioned into a training set (280 samples) and a testing set (70 samples) at a 4:1 ratio.

### Download
The dataset can be downloaded from:  https://pan.baidu.com/s/1Tm0uJpoSvOzMP20UQOSVQQ?pwd=tftf

### Statistics
- **Total Images**: 350
- **Spectral Bands**: 200
- **Resolution**: 1240 × 1680
- **Annotation Types**: pixel-level masks
- **Challenges**: Minimal Objects (MO), Complex Shapes (CS), Dynamic Lighting (DL), Object Occlusion (OO), Cluttered Backgrounds (CB)
