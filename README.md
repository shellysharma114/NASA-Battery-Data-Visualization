# NASA-Battery-Data-Visualization

## Steps to Execute the Program

### 1. Clone the Repository
Clone this repository to your local machine:
```bash
git clone <repository-url>
cd <repository-folder>
```

### 2. Set Up the Environment
Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Linux/Mac
venv\Scripts\activate     # On Windows
```


### 3. Prepare the Dataset
Download the NASA Battery Dataset and organize it as follows:
```
project-folder/
├── cleaned_dataset/
│   ├── metadata.csv
│   ├── data/
│   │   ├── file1.csv
│   │   ├── file2.csv
│   │   └── ...
```

### 4. Run the Jupyter Notebook
Launch Jupyter Notebook and execute the program:
```bash
jupyter notebook
```
1. Open the `.ipynb` file in the repository.
2. Run each cell sequentially.

### 5. Visualize the Results
View the interactive graphs for:
- Resistance analysis (**Re** and **Rct**) by battery ID.
- Impedance change over time for each battery.

---
