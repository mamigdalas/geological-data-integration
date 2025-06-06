# Geological Data Integration for Subsurface Characterization

This repository contains the code and resources for a conceptual project demonstrating the integration of multimodal geological data (text reports, core images, and well logs) for enhanced subsurface characterization using machine learning.

## Project Overview
The workflow covers:
1.  **Text Data Processing:** Extracting key information from geological reports (conceptual using NER).
2.  **Image Analysis:** Conceptually processing core photos for facies classification (e.g., Sandstone/Carbonate).
3.  **Well Log Data Analysis:** Loading, visualizing, and engineering features from synthetic well log data.
4.  **Multimodal Data Integration:** Combining information from all sources into a unified dataset.
5.  **Machine Learning:** Developing a conceptual ML model for lithology prediction based on the integrated data.

## Data
* `data/synthetic_well_log_1.csv`: Synthetic well log data used for demonstration.
* `mini_reports/`: Example mini reports (conceptual text data).
* `images/`: Placeholder for core images and generated plots.

## Setup and Running the Code
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/geological-data-integration.git](https://github.com/YourUsername/geological-data-integration.git)
    cd geological-data-integration
    ```
2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    # On Windows:
    .\venv\Scripts\activate
    # On Linux/macOS:
    source venv/bin/activate
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Run the main script:**
    ```bash
    python main.py
    ```
## Dependencies
See `requirements.txt` for a list of Python packages.

## Author
Emmanouil Amygdalas / mamigdalas