# SeaGeo: A Dataset for Vision-Guided Georeferencing of UAV Sea-Surface Imagery

SeaGeo is a dataset of UAV-acquired sea-surface imagery accompanied by navigation and inertial sensor measurements. It is intended to support research on vision-guided georeferencing and related computer vision tasks in maritime environments.

The dataset is associated with the research paper **"Vision-guided Georeferencing of UAV Sea Surface Imagery."**

![SeaGeo Dataset Overview](ADD_IMAGE_OR_GIF_URL_HERE)

## Summary of SeaGeo

1. **Dataset overview:** SeaGeo contains RGB imagery and video sequences acquired by an unmanned aerial vehicle (UAV) over a sea-surface environment.

2. **Data acquisition:** The dataset was collected at Ariyamaan Beach, Rameshwaram, India, using a UAV equipped with an RGB camera and navigation sensors.

3. **Sensor measurements:** The dataset includes GPS telemetry and inertial measurement unit (IMU) data to support research involving image georeferencing and sensor-assisted visual analysis.

4. **Image characteristics:** The dataset includes UAV imagery of the sea surface. Details such as image resolution, frame rate, acquisition altitude, camera settings, and total dataset size are provided in the dataset documentation [TO BE COMPLETED].

5. **Georeferencing research:** SeaGeo supports the investigation of vision-guided georeferencing methods for sea-surface imagery, where conventional ground-control-based approaches may be difficult to apply.

6. **Potential applications:** The dataset can support research in UAV image georeferencing, feature matching, image registration, sea-surface image mosaicking, visual localization, and related computer vision applications.

## Dataset Contents

SeaGeo contains the following data modalities:

- **RGB imagery and video:** UAV-acquired visual observations of the sea surface.
- **GPS telemetry:** Navigation measurements recorded during data acquisition.
- **IMU measurements:** Inertial sensor data associated with UAV operation.

### Dataset Specifications

| Property | Description |
|---|---|
| Dataset name | SeaGeo |
| Data domain | UAV sea-surface imagery |
| Collection location | Ariyamaan Beach, Rameshwaram, India |
| Imaging modality | RGB |
| Data format | Images and/or video sequences [CONFIRM FORMATS] |
| Navigation data | GPS telemetry |
| Inertial data | IMU measurements |
| Image resolution | [TO BE SPECIFIED] |
| Video frame rate | [TO BE SPECIFIED] |
| Number of images/videos | [TO BE SPECIFIED] |
| Acquisition altitude | [TO BE SPECIFIED] |
| Sensor synchronization | [TO BE SPECIFIED] |
| Coordinate reference system | [TO BE SPECIFIED] |

## Research Paper

The dataset is associated with the following research work:

**Title:** Vision-guided Georeferencing of UAV Sea Surface Imagery

**Authors:** [AUTHOR LIST TO BE SPECIFIED]

**Publication venue:** [CONFERENCE OR JOURNAL TO BE SPECIFIED]

**Publication year:** [YEAR TO BE SPECIFIED]

**Paper link:** [PUBLICATION URL OR DOI, IF AVAILABLE]

## How to Access the Dataset

SeaGeo is available **upon request**.

To request access:

1. Review the dataset access requirements: [DATASET ACCESS POLICY OR AGREEMENT URL].
2. Submit a request using the following form or contact: [REQUEST FORM URL OR CONTACT EMAIL].
3. Follow the instructions provided to obtain access to the dataset.

**Access procedure:** [SPECIFY WHETHER APPROVAL, A SIGNED AGREEMENT, OR OTHER REQUIREMENTS APPLY.]

## Intended Applications

SeaGeo is intended to facilitate research on computer vision for UAV-based maritime observation, particularly in environments where reliable image georeferencing is challenging.

Potential research applications include:

- **Vision-guided georeferencing:** Estimating geographic image positions using visual correspondences and geometric transformations.
- **Feature matching and image registration:** Evaluating local and learned feature-matching approaches on sea-surface imagery.
- **Image mosaicking:** Investigating the alignment and integration of multiple UAV images.
- **Visual localization:** Studying image-based localization in maritime environments.
- **Sensor-assisted vision:** Exploring methods that combine visual information with GPS and IMU measurements.

The suitability of the dataset for each application depends on the availability of the relevant metadata, reference measurements, and annotations.

## Code and Implementation

The code associated with the proposed georeferencing method is available at:

**GitHub repository:** https://github.com/DeepakSrivastava26/SeaGeo

Implementation details, dependencies, and instructions for reproducing the experiments should be documented in the repository's code and usage documentation.

**Environment setup:** [TO BE SPECIFIED]

**Usage instructions:** [TO BE SPECIFIED]

## Acknowledgements

[ADD FUNDING AGENCIES, PROJECT NUMBERS, INSTITUTIONAL SUPPORT, AND ACKNOWLEDGEMENTS FOR DATA COLLECTION.]

## Citation

If you use SeaGeo in your research, please cite the associated publication once its bibliographic details are finalized.

```bibtex
@InProceedings{SeaGeo,
    author    = {[AUTHOR NAMES]},
    title     = {Vision-guided Georeferencing of UAV Sea Surface Imagery},
    booktitle = {[CONFERENCE NAME]},
    year      = {[YEAR]},
    pages     = {[PAGE RANGE]}
}
```

[Replace the placeholders with the final publication metadata. If the work is not yet published, use the appropriate preprint or manuscript citation.]

## License and Terms of Use

**License:** To be determined.

Dataset access is currently handled upon request. The applicable terms of use, redistribution permissions, and licensing conditions will be specified by the dataset maintainers.

Until a license is established, users should not assume that the dataset may be redistributed or used without restrictions.

## Contact

For questions about SeaGeo, dataset access, or the associated research, contact:

- **Maintainer:** Deepak Srivastava [CONFIRM CONTACT DETAILS]
- **Institution:** Indian Institute of Technology Madras [CONFIRM INSTITUTIONAL DETAILS]
- **Email:** [CONTACT EMAIL]
- **Repository:** https://github.com/DeepakSrivastava26/SeaGeo
