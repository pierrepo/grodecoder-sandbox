# grodecoder-sandbox

## Installation
Clone the project:  
```bash
git clone https://github.com/pierrepo/grodecoder-sandbox.git
cd grodecoder-sandbox
```

Create and activate a conda environment:
```bash
conda env create -f environment.yml
conda activate grodecoder-sandbox-env
```

## Usage 
Run the NoteBook ```lipide.ipynb```.  
This NoteBook that analyzes the database LipidMap (https://www.lipidmaps.org/databases/lmsd/overview). It download the data, if it not already exist. It extracts information that can be used to identify lipids in the GRO and PDB files.
