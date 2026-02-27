# VOC-IRLeak Annotation Guidelines

## Overview

This document outlines the annotation guidelines for the VOC-IRLeak dataset. **Note**: Annotation work is currently in progress, and this document describes the planned annotation protocol.

## Annotation Tasks

The VOC-IRLeak dataset is designed to support two main computer vision tasks:

1. **Semantic Segmentation**: Pixel-level segmentation of gas leakage regions
2. **Object Detection**: Bounding box annotation for gas leakage detection

## Annotation Object Definition

### What to Annotate

**Gas Leakage Regions**: Visible gas leakage plumes in infrared video frames. The annotation should include:

- **Visible Gas Plumes**: Regions where gas leakage is clearly visible in the infrared imagery
- **Gas Source Location**: The origin point of the gas leakage (if visible)
- **Gas Diffusion Areas**: Areas where gas has diffused and is visible in the thermal image

### Annotation Criteria

1. **Visibility Threshold**: Only annotate gas leakage regions that are clearly visible in the infrared imagery
2. **Temporal Consistency**: Maintain consistency across video frames for the same leakage event
3. **Boundary Definition**: Include the entire visible gas plume, including semi-transparent edges where gas concentration is lower

## Annotation Format

### Planned Formats

#### 1. Semantic Segmentation

- **Format**: PNG mask files or COCO segmentation format
- **Pixel Values**: 
  - Background: 0
  - Gas leakage region: 1 (or class ID)
- **File Naming**: `{video_name}_{frame_number}_mask.png`

#### 2. Object Detection

- **Format**: COCO JSON format or YOLO format
- **Bounding Boxes**: Axis-aligned bounding boxes (x, y, width, height)
- **Classes**: Single class "gas_leakage" (or multiple classes if different gas types are distinguished)

#### 3. Instance Segmentation (Future)

- **Format**: COCO instance segmentation format
- **Polygon Annotations**: Precise polygon boundaries for each gas leakage instance
- **Instance IDs**: Unique identifier for each gas leakage instance

## Annotation Tools

### Recommended Tools

1. **LabelMe**: For polygon and bounding box annotation
2. **CVAT**: For video annotation with temporal consistency
3. **COCO Annotator**: For COCO format annotations
4. **VGG Image Annotator (VIA)**: For flexible annotation formats

### Annotation Workflow

1. **Frame Selection**: Select representative frames from video sequences
2. **Initial Annotation**: Annotate key frames manually
3. **Interpolation**: Use temporal interpolation for intermediate frames (if supported by tool)
4. **Quality Control**: Review annotations for consistency and accuracy
5. **Validation**: Cross-validation by multiple annotators (if applicable)

## Annotation Status

### Current Status

- **Raw Video Data**: ✅ Available on Zenodo
- **Segmentation Annotations**: ⏳ In progress / Planned
- **Object Detection Annotations**: ⏳ In progress / Planned

### Future Updates

Annotation data will be released in future dataset versions. If you need annotation data for your research, please contact the authors:

- **Email**: haoyangs078@163.com

## Contact

For questions about annotation guidelines or annotation data availability:

- **Email**: haoyangs078@163.com
- **GitHub Issues**: [https://github.com/haoyangs078-code/VOC-IRLeak/issues](https://github.com/haoyangs078-code/VOC-IRLeak/issues)

---

**Last Updated**: 2026

**Note**: This document will be updated as annotation work progresses and annotation data becomes available.

