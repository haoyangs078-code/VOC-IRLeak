# VOC-IRLeak Dataset Card

## Dataset Summary

**VOC-IRLeak** is a high-quality infrared video dataset designed for VOCs (Volatile Organic Compounds) gas leakage detection. The dataset provides raw infrared video sequences captured using a GL1000i infrared camera, specifically designed for training and evaluating gas leakage detection and source localization algorithms.

- **Dataset Type**: Video dataset (infrared imaging)
- **Task Categories**: Object detection, semantic segmentation, instance segmentation
- **Language**: N/A (visual data)
- **License**: CC BY 4.0
- **Version**: 1.0
- **Dataset DOI**: [10.5281/zenodo.18780694](https://doi.org/10.5281/zenodo.18780694)

## Dataset Structure

### Data Format

- **Video Format**: MP4
- **Resolution**: 1920×1080 pixels
- **Frame Rate**: 30 frames per second (fps)
- **Content**: Raw infrared video sequences showing gas leakage events

### Data Organization

**Note**: The actual dataset files are hosted on Zenodo. This GitHub repository contains documentation and metadata only.

The dataset structure on Zenodo includes:
- Raw infrared video files (MP4 format)
- Video sequences captured under various leakage scenarios
- **Video Duration**: The dataset contains several videos with durations ranging from 10 to 40 seconds

### Annotation Status

- **Current Status**: Raw video data available
- **Segmentation Annotations**: Not yet available (may be provided in the future)
- **Object Detection Annotations**: Not yet available (may be provided in the future)

For annotation requests, please contact the authors via email: **haoyangs078@163.com**

## Data Collection

### Acquisition Equipment

- **Camera Model**: GL1000i infrared camera
- **Working Band**: 3.2 - 3.5 μm (mid-wave infrared)
- **Detector Array**: 320×256 pixels (standard cooled detector)
- **Output Resolution**: 1920×1080 pixels
- **Frame Rate**: 30 fps
- **Video Format**: MP4

### Collection Environment

- **Scenarios**: Industrial and experimental environments
- **Gas Type**: Methane (CH₄) with composition of 99% CH₄ and 1% H₂
- **Applicable Gas Types**: Primarily focused on methane detection, but applicable to other VOCs that exhibit absorption characteristics in the 3.2-3.5 μm wavelength range
- **Leakage Conditions**: Various leakage scenarios including different flow rates, distances, and environmental conditions

## Intended Use

### Primary Use Cases

- Gas leakage detection using infrared imaging
- Source localization of gas leaks
- Anomaly detection in industrial environments
- Computer vision applications for environmental monitoring
- Industrial safety monitoring systems

### Tasks Supported

- **Object Detection**: Detecting gas leakage regions in infrared video frames
- **Semantic Segmentation**: Pixel-level segmentation of gas leakage areas
- **Instance Segmentation**: Instance-level segmentation of multiple leakage sources
- **Video Analysis**: Temporal analysis of gas leakage events

## Limitations and Bias

### Known Limitations

1. **Dataset Scope**: Due to equipment copyright and other restrictions, this dataset represents only a subset of the original dataset used in the associated paper. The dataset may be updated periodically in the future.

2. **Gas Type**: The dataset is primarily focused on methane detection. While the methodology may be applicable to other VOCs, direct applicability to other gas types may require validation.

3. **Environmental Conditions**: Data collection was conducted in specific industrial and experimental environments. Performance in other environments may vary.

4. **Annotation Availability**: Currently, only raw video data is available. Segmentation and detection annotations are not yet provided.

### Potential Biases

- **Environmental Bias**: Data collected in specific industrial/experimental settings may not fully represent all real-world scenarios
- **Gas Concentration Bias**: Leakage scenarios may not cover the full range of possible gas concentrations
- **Temporal Bias**: Video sequences may not capture all phases of gas leakage events

## Data Preprocessing

### Raw Data

The dataset provides raw infrared video sequences without preprocessing. Users may need to:

- Extract frames from video sequences
- Apply normalization or enhancement techniques as needed
- Handle temporal alignment for video-based methods

### Future Annotations

When annotations become available, they may include:
- Segmentation masks (pixel-level annotations)
- Bounding boxes (object detection annotations)
- Temporal annotations (frame-level labels)

## Maintenance

### Dataset Updates

- **Version 1.0** (Current): Initial release with raw video data
- **Future Updates**: May include annotation data, additional video sequences, or expanded scenarios

### Maintenance Contact

For questions, issues, or update requests:
- **Email**: haoyangs078@163.com
- **GitHub Repository**: [https://github.com/haoyangs078-code/VOC-IRLeak](https://github.com/haoyangs078-code/VOC-IRLeak)

## Citation

**Important**: If you use this dataset in your research, you **MUST cite both** the dataset and the associated paper.

### Paper Citation (Primary)

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

### Dataset Citation

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

## Additional Resources

- **Dataset Download**: [Zenodo (DOI: 10.5281/zenodo.18780694)](https://doi.org/10.5281/zenodo.18780694)
- **GitHub Repository**: [https://github.com/haoyangs078-code/VOC-IRLeak](https://github.com/haoyangs078-code/VOC-IRLeak)
- **Paper DOI**: [10.1016/j.measurement.2025.119085](https://doi.org/10.1016/j.measurement.2025.119085)
- **License**: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

---

**Last Updated**: 2026

