# Google Cloud Storage Interaction Notebook

## Overview

This Jupyter Notebook demonstrates how to interact with Google Cloud Storage (GCS) using Python. The notebook covers tasks such as establishing a connection with GCS, accessing a specific bucket, and retrieving files from the storage.

## Features

- **Google Cloud Storage Integration**: 
  - Connect to GCS using a service account.
  - Access and list files within a specific GCS bucket.
  - Check the existence of specific files within the bucket.

## Requirements

- Python 3.8+
- Jupyter Notebook
- Google Cloud SDK and a valid service account key in JSON format

## Setup

1. **Clone the repository** (if applicable) or download the notebook.

    ```bash
    git clone https://github.com/yourusername/gcs-interaction-notebook.git
    cd gcs-interaction-notebook
    ```

2. **Install dependencies**:

    ```bash
    pip install google-cloud-storage pandas
    ```

3. **Set up Google Cloud credentials**:

    - Ensure you have a `key.json` file, which is your service account key.
    - This file should be placed in the same directory as the notebook or update the path accordingly in the notebook.

4. **Run the notebook**:

    Open the notebook in Jupyter and run the cells to interact with your Google Cloud Storage.

## Key Sections

- **Connecting to GCS**:
  - Establish a connection using the service account key.
  
- **Accessing a Bucket**:
  - Retrieve a specific GCS bucket using its name.

- **File Operations**:
  - Check for the presence of a file (`customer.csv`) in the bucket and confirm its existence.

## Customization

- Update the `bucket_name` and file paths according to your GCS configuration.
- Modify the operations to fit your use case, such as uploading files or handling different file types.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please contact [your-email@example.com](mailto:your-email@example.com).
