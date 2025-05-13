
# FMI Project README

## How to Prepare the Code Execution Environment

1. Install Python (version 3.7 or higher is recommended).
2. Set up a virtual environment for managing dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

---

## Prerequisite Packages and Libraries

Install the required Python libraries using the following command:
```bash
pip install numpy nibabel matplotlib scipy
```

---

## How to Run the Code

1. Open a terminal or command prompt.
2. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Load the `SignalSynth_code.ipynb` file in the Jupyter Notebook interface.
4. Execute the cells sequentially by clicking "Run" for each cell or selecting "Run All" from the menu.

---

## How to Run the Code with Various Datasets

1. **Dataset Requirements**:
   - Input files must be neuroimaging datasets in `.nii` or `.nii.gz` format.
   - Ensure data dimensions align with the code logic and processing methods.

2. **Specifying the Dataset Path**:
   - Locate the code cell where the dataset is loaded (typically using NiBabel).
   - Replace the path with your dataset's path:
     ```python
     data_path = "/path/to/your/dataset.nii.gz"
     ```

3. **Restrictions**:
   - Input datasets must be compatible with NiBabel.
   - Files should have valid header information for successful parsing.
   - Processing large datasets requires sufficient computational resources.

---
