# Marker-Based Motion Analysis with Deep Learning

## Overview

In physical therapy, precise evaluation and monitoring of shoulder movements are essential for developing effective rehabilitation strategies. This study aims to enhance these capabilities by employing image processing techniques for pose detection and estimation. Utilizing a dataset comprising video recordings of seven healthy individuals undergoing the Functional Impairment Test-Hand, Neck/Shoulder/Arm (FIT-HaNSA)—a benchmark test for assessing shoulder girdle functionality, this project compares two state-of-the-art models dedicated to upper limb pose detection. These methodologies are benchmarked against Dartfish, the industry-standard marker-based motion analysis software, to evaluate their effectiveness in accurately detecting and estimating shoulder motion. This comparative analysis aims to identify the most efficient model, with the ultimate goal of enhancing diagnostic and therapeutic approaches in physical therapy.

## Dataset

### Data Collection
The dataset comprises pre-recorded video footage of seven healthy individuals under 40 performing the Functional Impairment Test-Hand, Neck, and Shoulder Arm (FIT-HaNSA) at the McFarlane Hand & Upper Limb Center located at St. Joseph in London, Ontario. The videos were taken from posterior views to ensure a comprehensive capture of the shoulder’s range of motion, mainly focusing on abduction (upward lateral) and adduction (downward lateral) movements.

**Note:** The dataset cannot be uploaded here due to privacy and permission constraints. For access to the data, please contact the institution.

## Methodology

This study evaluates and compares the effectiveness of MediaPipe and YOLOv8 models against the established Dartfish software for pose detection and motion analysis in upper limb assessments. Through a series of experimental setups, each technology is assessed based on its precision and reliability in capturing and analyzing complex motion dynamics.

## Outputs

### Key Outputs
1. **Excel File**: The angles calculated from the keypoints detected by YOLOv8 are saved in an Excel file named `P1.xlsx`.
2. **Annotated Image**: An image annotated with keypoints and lines between keypoints is saved as `annotated_P1.jpg`.

## Usage

1. **Clone the Repository**:
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2. **Run the Code**:
    Ensure you have the necessary dependencies installed and the dataset available in the specified directory. Run the provided scripts to process the video, extract keypoints, calculate angles, and save the outputs.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- The participants of the FIT-HaNSA test at the McFarlane Hand & Upper Limb Center.
- The developers of Dartfish, MediaPipe, and YOLOv8 for providing the tools and frameworks used in this study.
