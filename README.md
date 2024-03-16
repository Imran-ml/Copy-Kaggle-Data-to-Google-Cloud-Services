# Copy Kaggle data to Google Cloud Services

## Table of Contents

- [Introduction](#introduction)
- [Environment Setup](#environment-setup)
- [Installation Instructions](#installation-instructions)
- [Resources](#resources)
- [License](#license)
- [Conclusion](#conclusion)
- [About Author](#about-author)

## Introduction

Welcome to my repository! Here, I have shared a comprehensive notebook designed to guide you through the process of transferring data from Kaggle to Google Cloud Services. Whether you're looking to perform large-scale data analysis, machine learning, or simply want to take advantage of the cloud's computing capabilities, this guide will provide you with step-by-step instructions to make the data transfer as seamless as possible. Dive in to explore how you can leverage the best of both platforms for your projects!

## Environment Setup

**Prerequisites**: Ensure Python 3.6 or newer is installed on your system.

1. **Create a Virtual Environment**:
    - Install `virtualenv` if you prefer it over the built-in `venv` (optional):
        ```bash
        pip install virtualenv
        ```
    - Create the environment:
        - With `venv` (Python 3.3+):
            ```bash
            python -m venv env
            ```
        - Or, with `virtualenv`:
            ```bash
            virtualenv env
            ```
    - Activate the environment:
        - Windows: `env\Scripts\activate`
        - Unix/MacOS: `source env/bin/activate`
    - To deactivate: `deactivate`

2. **Dependencies**:
    Ensure all dependencies are listed in `requirements.txt`. Install them using:
    ```bash
    pip install -r requirements.txt
    ```

## Installation Instructions

To use this project, clone the repository and set up the environment as follows:

1. **Clone the Repository**:
    ```bash
    https://github.com/Imran-ml/Copy-Kaggle-Data-to-Google-Cloud-Services.git
    ```
2. **Setup the Environment**:
    - Navigate to the project directory and activate the virtual environment.
    - Install the dependencies from `requirements.txt`.

### Before copy the data, you need to the following steps first:
- Create a new Kaggle Notebook. To do this, click <> **Notebooks** on the left sidebar and click + **New Notebook**
- Add a reference in your Notebook to the Kaggle data. To do this, click **Add data** you will see on your right side up
- In the window that appears, select the Competition Data tab, find the ABC data, and click the **Add button**
- Grant Kaggle access to your Google Cloud Storage service. To do this, select **Google Cloud Services** from the **Add-ons** menu
- In the window that will appear, tick **Cloud Storage** and then click the **Link Account** button


## Resources

- **Kaggle Notebook**: [View Notebook](https://www.kaggle.com/code/muhammadimran112233/copy-kaggle-data-to-google-cloud-services)
- **Dataset**: [View Dataset](https://www.kaggle.com/datasets/gpreda/reddit-vaccine-myths)

## License

This project is made available under the MIT License.

## Conclusion

In conclusion, this notebook has provided a detailed walkthrough on transferring Kaggle datasets to Google Cloud Services, aimed at enhancing your data projects with the scalability and efficiency of cloud computing. I hope you find this guide valuable for seamlessly integrating these powerful platforms into your workflow.

## About Author

- **Name**: Muhammad Imran Zaman
- **Email**: [imranzaman.ml@gmail.com](mailto:imranzaman.ml@gmail.com)
- **Professional Links**:
    - Kaggle: [Profile](https://www.kaggle.com/muhammadimran112233)
    - LinkedIn: [Profile](linkedin.com/in/muhammad-imran-zaman)
    - Google Scholar: [Profile](https://scholar.google.com/citations?user=ulVFpy8AAAAJ&hl=en)
    - YouTube: [Channel](https://www.youtube.com/@consolioo)
- **Project Repository**: [GitHub Repo](https://github.com/Imran-ml/Copy-Kaggle-Data-to-Google-Cloud-Services.git)
