# Dataset

This project uses a private HER2 immunohistochemistry (IHC) pathology image dataset.

Due to patient privacy and institutional regulations, raw images are not included
in this repository.

## Expected Data Structure

data/
├─ raw/
│  ├─ HER2_positive/
│  └─ HER2_negative/
├─ processed/
│  ├─ patches/
│  └─ metadata.csv
├─ splits/
│  ├─ train.csv
│  ├─ val.csv
│  └─ test.csv
