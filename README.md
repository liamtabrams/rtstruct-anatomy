# RTSTRUCT Anatomy

Interactive walk through one DICOM RT Structure Set: how it nests, how it points to its CT, how the
per-ROI lists join on ROI number, and how `ContourData` becomes organ outlines, with the pydicom path
for every element.

**View it:** https://liamtabrams.github.io/rtstruct-anatomy/

`index.html` is a single self-contained file (open it locally in any browser too). It is generated from
public data only; the generator lives in a separate (private) project repo.

## Data
Patient LCTSC-Train-S1-001, physicians' structure set, values unmodified.
LCTSC (Lung CT Segmentation Challenge 2017), The Cancer Imaging Archive,
DOI [10.7937/K9/TCIA.2017.3R3FVZ08](https://doi.org/10.7937/K9/TCIA.2017.3R3FVZ08), licensed
[CC BY 3.0](https://creativecommons.org/licenses/by/3.0/).
Yang J. et al., *Autosegmentation for thoracic radiation treatment planning: A grand challenge at AAPM 2017*,
Med Phys 45(10), 2018.
