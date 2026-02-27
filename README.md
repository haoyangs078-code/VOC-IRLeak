# VOC-IRLeak Dataset v1.0

## 📌 Important Notice

**This GitHub repository contains documentation and metadata only. The actual dataset (video files) is hosted on Zenodo. Please download the dataset from Zenodo using the DOI link provided below.**

- **Dataset Download**: [Zenodo (DOI: 10.5281/zenodo.18780694)](https://doi.org/10.5281/zenodo.18780694)
- **GitHub Repository**: This repository provides documentation, citation information, and dataset metadata

## 📋 Dataset Overview

VOC-IRLeak is an infrared video dataset designed for VOCs (Volatile Organic Compounds) gas leakage detection. This dataset provides raw infrared video sequences for training and evaluating gas leakage detection and source localization algorithms.

### Purpose

This dataset is designed to support research and development in:
- Gas leakage detection using infrared imaging
- Source localization of gas leaks
- Anomaly detection in industrial environments
- Computer vision applications for environmental monitoring
- Industrial safety monitoring systems

### Data Collection

**Acquisition Equipment:**
- **Model**: GL1000i infrared camera
- **Working Band**: 3.2 - 3.5 μm (mid-wave infrared)
- **Detector Array**: 320×256 pixels (standard cooled detector)
- **Output Resolution**: 1920×1080 pixels
- **Frame Rate**: 30 frames per second (fps)
- **Video Format**: MP4

**Collection Environment:**
- **Scenarios**: Industrial and experimental environments
- **Gas Type**: Methane (CH₄) with composition of 99% CH₄ and 1% H₂
- **Applicable Gas Types**: This dataset is primarily focused on methane detection, but the methodology and data format are applicable to other VOCs that exhibit absorption characteristics in the 3.2-3.5 μm wavelength range
- **Leakage Conditions**: Various leakage scenarios including different flow rates, distances, and environmental conditions

### Dataset Characteristics

- **Video Format**: MP4
- **Resolution**: 1920×1080 pixels
- **Frame Rate**: 30 fps
- **Content**: Raw infrared video sequences showing gas leakage events

---

## ⚠️ Citation Requirement

**If you use this dataset in your research, you MUST cite both the dataset and the associated paper:**

### 📌 How to Cite in Your Paper

**In your paper's reference section, please include BOTH citations:**

1. **Primary Citation (Paper)** - Cite the associated paper in your main references:
   - This is the **primary citation** that should appear in your paper's reference list
   - DOI: `10.1016/j.measurement.2025.119085`

2. **Dataset Citation** - Also cite the dataset (can be in data availability section or footnotes):
   - DOI: `10.5281/zenodo.18780694`

### 1. Paper Citation (Primary)

```bibtex
@article{shen2026source,
  author = {Shen, H. and Xu, L. and Dong, S. and Xu, Q. and Yu, H. and Wang, M. and Li, F.},
  title = {Source localization of infrared gas leakage based on YOLOv8 and Gaussian diffusion models},
  journal = {Measurement},
  volume = {258},
  pages = {119085},
  year = {2026},
  doi = {10.1016/j.measurement.2025.119085},
  url = {https://doi.org/10.1016/j.measurement.2025.119085}
}
```

**Plain text format:**
> Shen, H., Xu, L., Dong, S., Xu, Q., Yu, H., Wang, M., & Li, F. (2026). Source localization of infrared gas leakage based on YOLOv8 and Gaussian diffusion models. *Measurement*, 258, 119085. https://doi.org/10.1016/j.measurement.2025.119085

### 2. Dataset Citation

```bibtex
@dataset{shen2026vocirleak,
  author = {Shen, H. and Xu, L. and Dong, S. and Xu, Q. and Yu, H. and Wang, M. and Li, F.},
  title = {VOC-IRLeak: Infrared Video Dataset for VOCs Gas Leakage Detection},
  year = {2026},
  publisher = {Zenodo},
  doi = {10.5281/zenodo.18780694},
  url = {https://doi.org/10.5281/zenodo.18780694}
}
```

**Plain text format:**
> Shen, H., Xu, L., Dong, S., Xu, Q., Yu, H., Wang, M., & Li, F. (2026). VOC-IRLeak: Infrared Video Dataset for VOCs Gas Leakage Detection [Data set]. Zenodo. https://doi.org/10.5281/zenodo.18780694

**Important Notes:**
- The **paper citation** (DOI: 10.1016/j.measurement.2025.119085) should be included in your paper's main reference list
- The **dataset citation** (DOI: 10.5281/zenodo.18780694) should also be included, typically in a "Data Availability" section or as a footnote
- Failure to cite both the dataset and the associated paper constitutes academic misconduct

---

## 📊 Dataset Information

- **Version**: 1.0
- **License**: CC BY 4.0 (Creative Commons Attribution 4.0 International)
- **Format**: Raw infrared video sequences (MP4 format)
- **Purpose**: VOCs gas leakage detection and source localization
- **Dataset DOI**: https://doi.org/10.5281/zenodo.18780694

### ⚠️ Important Notice on Dataset Scope

**Due to equipment copyright and other restrictions, this dataset represents only a subset of the original dataset used in the associated paper. The dataset may be updated periodically in the future. Please check the GitHub repository or Zenodo page for the latest version.**

---

## 📝 Segmentation Annotation Availability

**Segmentation annotation data may be provided in the future.** If you need segmentation annotations for your research, please contact the authors via email: **haoyangs078@163.com**

We will consider providing annotation data based on research needs and availability.

---

## 🔗 Additional Resources

- **GitHub Repository**: https://github.com/haoyangs078-code/VOC-IRLeak
- **Dataset DOI**: https://doi.org/10.5281/zenodo.18780694
- **Paper DOI**: https://doi.org/10.1016/j.measurement.2025.119085

---

## 📧 Contact

For questions or issues regarding this dataset, please contact:

**Email**: haoyangs078@163.com

---

## 📄 License and Usage Terms

### License: CC BY 4.0

This dataset is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

### Citation Requirements

When using this dataset, you **must cite both**:

1. **Dataset DOI**: `10.5281/zenodo.18780694`
2. **Associated Paper DOI**: `10.1016/j.measurement.2025.119085`

See the [Citation Requirement](#-citation-requirement) section above for detailed citation formats.

For the full license text, please see the `LICENSE.md` file included in this dataset or visit: https://creativecommons.org/licenses/by/4.0/

---

## ⚖️ Ethics and Privacy

- All data in this dataset were collected from industrial/experimental environments
- No personal privacy information is included
- Users should comply with local laws and regulations when using this dataset
- This dataset is intended for research purposes only

---

## 📝 Usage Notes

- This dataset is provided for research purposes
- **Important**: When using this dataset, you must cite both the dataset and the associated paper (see Citation Requirement section above)
  - The **paper citation** (DOI: 10.1016/j.measurement.2025.119085) should appear in your paper's main reference list
  - The **dataset citation** (DOI: 10.5281/zenodo.18780694) should also be included, typically in a "Data Availability" section
- This dataset is a subset of the original dataset used in the paper; future updates may be released
- For questions or technical support, please contact the maintainers via email

---

## 🙏 Acknowledgments

We thank all contributors and reviewers who helped improve this dataset.

---

**Last Updated**: 2026

**License File**: See `LICENSE.md` for the complete CC BY 4.0 license text.

