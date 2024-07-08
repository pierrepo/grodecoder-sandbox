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
Run the NoteBook ```parse_MAD.ipynb``` or the script ```scrap_MAD.py```.  
This NoteBook (or script) that analyzes the database MAD (https://mad.ibcp.fr/explore). It download the data, if it not already exist. It extracts information that can be used to identify lipids in the GRO and PDB files and save it into a CSV file.  
  
Run the NoteBook ```parse_CHARMMGUI.ipynb``` or the script ```scrap_charmm_gui_CSML.py```.
This NoteBook web scraping all the lipid from CHARMM-GUI (https://www.charmm-gui.org/?doc=archive&lib=lipid) and save it into a CSV file. 
