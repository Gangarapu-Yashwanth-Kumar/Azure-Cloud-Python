# Azure-Cloud-Python ☁️🐍

## Overview ✨
This repository provides a collection of practical code samples demonstrating how to interact with various Microsoft Azure cloud services using Python. It's designed to help developers understand and implement solutions for cloud-based data storage and intelligent document processing.

## Tech Stack Used 🛠️
* **Programming Language:** Python 🐍
* **Azure Services:**
    * Azure Blob Storage 📦 (for unstructured data storage)
    * Azure Document Intelligence (formerly Form Recognizer) 📄 (for intelligent document processing and data extraction)
* **Python Libraries:**
    * `azure-storage-blob`
    * `azure-identity`
    * `azure-ai-formrecognizer`
    * `pandas` (for data manipulation, as seen in Blob Storage examples)
* **Development Environment:** Jupyter Notebooks 📓

## Key Features & Responsibilities 🚀
* **Azure Blob Storage Management:**
    * Create, list, and delete containers.
    * Upload, download, and list various types of blobs (text, CSV, images).
    * Demonstrate efficient handling of unstructured data in the cloud.
* **Azure Document Intelligence Integration:**
    * Connect to Azure Document Intelligence services.
    * Analyze documents (e.g., invoices) to extract key-value pairs and structured information.
    * Showcase intelligent data extraction capabilities for automation.
* **Practical Examples:** Each notebook offers clear, runnable code examples to jumpstart your Azure Python projects.
* **Cloud Skill Enhancement:** Provides a hands-on approach to developing robust cloud applications.

## Learning Outcome 🎓
Upon exploring this repository, you will be able to:
* Confidently integrate Python applications with Azure Blob Storage for data management.
* Utilize Azure Document Intelligence to build intelligent automation workflows for document analysis.
* Understand best practices for authenticating and interacting with Azure services using Python.
* Gain practical experience in developing cloud-native Python solutions.

## Getting Started ▶️
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/Azure-Cloud-Python.git](https://github.com/your-username/Azure-Cloud-Python.git)
    ```
2.  **Install Dependencies:** Navigate to each notebook's directory and install the required Python packages as specified within the notebooks (e.g., `pip install azure-storage-blob azure-identity azure-ai-formrecognizer pandas`).
3.  **Azure Setup:** Ensure you have an active Azure subscription and the necessary Azure services (Blob Storage account, Document Intelligence service) configured with appropriate access keys/endpoints.
4.  **Run Notebooks:** Open the Jupyter notebooks (`.ipynb` files) in your preferred environment (e.g., Jupyter Lab, VS Code) and follow the instructions.

## Configuration 🔑
**Important:** To run these samples successfully, you must obtain the correct authentication keys and service URLs directly from your Azure account.
* **Azure Blob Storage:** Locate your Storage Account **Access Keys** and the **Blob Service URL** from your Azure portal.
* **Azure Document Intelligence:** Find your **Endpoint** and **Keys** from the Document Intelligence service overview in the Azure portal.
    * *Always keep your keys secure and never expose them publicly in your code or repositories.*

## Thank You 🙏
Thank you for checking out this repository! We hope these samples prove valuable in your Azure cloud development journey with Python. Your feedback and contributions are welcome.
