# unie-mobilendo-lab2-optimization-actions-classifier
 4G/5G Mobile Network optimizer

 ## Project Structure
```bash
.
├── datasets/
│ └── network_cells_labeled_actions.parquet (dataset)
│ └── license # CC BY 4 (dataset)
├── src/ 
│ └── Classifier for cell optimization actions.ipynb
├── requirements.txt
├── LICENSE # MIT License (code)
└── README.md
```

## Copyright and License

- **© 2026 Jaime Rodríguez Membrive**
- **Notebook**: MIT License

Developed and tested on:

- **Python ≥ 3.11**  
- **Dependencies:** see requirements.txt file

## Quick start

```bash
## Create and activate environment
python3 -m venv venv
source venv/bin/activate      # macOS/Linux
venv\Scripts\activate         # Windows

# Install dependencies
pip install -r requirements.txt  

# Run notebook
jupyter notebook "src/Classifier for cell optimization actions.ipynb"
```

**Disclaimer**: Provided *as is*, for academic use only.