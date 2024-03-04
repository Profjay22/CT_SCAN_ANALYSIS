
# DICOM Image Analysis Tool

## Overview
This tool is designed to analyze DICOM (Digital Imaging and Communications in Medicine) images, specifically focusing on medical images of lung scans. It provides various functionalities for loading DICOM images, processing them, and extracting relevant information such as lung area and volume.

## Features
- **DICOM Image Loading:** Load DICOM images from a specified folder.
- **Visualization:** Visualize DICOM images and their segmented lung regions.
- **Lung Area Calculation:** Calculate the area of lung regions in DICOM images.
- **Lung Volume Calculation:** Calculate the volume of lungs in DICOM images.
- **Histogram Analysis:** Analyze pixel intensity distributions in DICOM images.

## Installation
1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/profjay22/CT_SCAN_ANALYSIS.git
    ```

2. Navigate to the project directory:

    ```bash
    cd GD5302_C1
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Place your DICOM images in the `data` folder.
2. Run the main script `main.py`:

    ```bash
    python main.py
    ```

3. Follow the prompts to perform various analyses on the DICOM images.

## Example
To load and visualize DICOM images from the `data/PatientA` folder, run the following command:

```bash
python main.py --folder data/PatientA
```


## Acknowledgements
- This project utilizes the [pydicom](https://pydicom.github.io/pydicom/) library for DICOM image processing.

## Contact
For any inquiries or support, please contact (ja235@standrews.ac.uk).

