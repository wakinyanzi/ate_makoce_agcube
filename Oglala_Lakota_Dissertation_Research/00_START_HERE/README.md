# Environmental Data Cube for Oglala Lakota
## Dissertation Research Archive — Start Here

### Purpose

This archive preserves completed dissertation research,
environmental datasets, geospatial files, Jupyter notebooks,
validation results, figures, and community atlas materials.

The research focuses on agricultural sustainability and
environmental assessment of lands on the Pine Ridge Indian
Reservation.

### Folder Guide

- `00_START_HERE` — Opening instructions
- `01_Research_Documentation` — Research documentation,
  data sovereignty guidance, glossary, and license
- `02_Source_Data` — Original source and reference datasets
- `03_Parcel_and_GIS` — Parcel and geographic boundaries
- `04_Environmental_Data_Cube` — Environmental NetCDF datasets
- `05_Jupyter_Notebooks` — Dissertation research notebooks
- `06_Analysis_Results` — Completed analyses and validation
- `07_Dissertation_Figures` — Curated dissertation figures
- `08_Community_Atlas` — Community maps and supporting data
- `09_Dissertation_Writing` — Dissertation writing materials
- `10_Reproducibility` — Python environment and technical notes

### Opening on Another Computer

1. Copy the complete `Oglala_Lakota_Dissertation_Research`
   folder to the destination computer.

2. Install VS Code and the Python and Jupyter extensions,
   or use JupyterLab.

3. Open the complete research folder in VS Code.

4. Open `10_Reproducibility/environment.yml`.

5. If Conda is installed, create the Python environment:

   conda env create -f 10_Reproducibility/environment.yml

6. Activate the environment:

   conda activate tribal-datacube

7. Open a notebook in `05_Jupyter_Notebooks` and select
   the `tribal-datacube` Python kernel.

### Important Portability Notes

The notebooks are preserved as original research records.

Some notebooks contain absolute paths from the original Mac,
or reference the earlier project directory structure.

These notebooks can be opened and reviewed, but executing
all cells on another computer may require updating file paths
and confirming dependencies.

Some historical workflows also reference files outside the
original project directory.

The original Wanzi 15-point NDVI lattice has been preserved
in `04_Environmental_Data_Cube/03_Original_Wanzi_Lattice`.

The archive includes completed research outputs; users do
not need to rerun analyses merely to view existing results.

### Research Integrity

Original datasets, notebook calculations, and completed
figures have not been recalculated or altered during
archive preparation.

Copied research files were verified using SHA-256 checksums.

### Tribal Data Sovereignty

Research data must be handled in accordance with applicable
Tribal governance, permissions, and data sovereignty protocols.

Consult `01_Research_Documentation/data_sovereignty.md`
before sharing or distributing archive contents.

### Archive Status

Research preservation: Completed for selected materials.
Cross-computer execution: Not yet fully validated.
