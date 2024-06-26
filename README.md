# thinkpromt_test_v1
# Test ThinkPrompt Project

This project is designed to demonstrate various file processing tasks, including working with PDF, DOCX, and PPTX files. Below are the structure of the project and instructions on how to set it up and use it.

## Getting Started

### Prerequisites

Make sure you have Python installed. You can install the required packages using the `requirements.txt` file.

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/TuanAnhDevIT/thinkpromt_test_v1.git
    cd test_thinkprompt
    ```

2. **Create a virtual environment:**

    ```bash
    python -m venv myenv
    source myenv/bin/activate  # On Windows use `myenv\Scripts\activate`
    ```

3. **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

### Usage

#### Notebooks

The project includes three Jupyter notebooks for different file processing tasks. You can find these notebooks in the `notebook` directory:

- `working_with_doc.ipynb`: For working with DOCX files.
- `working_with_ppt.ipynb`: For working with PPTX files.
- `working_with_pdf.ipynb`: For working with PDF files.

To run these notebooks, follow these steps:

1. **Start Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```

2. **Open the desired notebook** from the `notebook` directory and run the cells to process the files.

### Data Import and Export

- Place your input files (PDF, DOCX, PPTX) in the `data_import` directory.
- Processed files will be saved in the `data_export` directory.

### .gitignore

The `.gitignore` file includes patterns to exclude from version control. This typically includes environment directories, temporary files, and other unnecessary files.

### Notes

- Ensure you activate your virtual environment each time you work on the project to use the correct dependencies.
- Modify the notebooks as necessary to fit your specific use case or processing requirements.

### Contributing

If you would like to contribute to this project, please fork the repository and create a pull request with your changes.

### License

This project is licensed under the MIT License. See the LICENSE file for details.
