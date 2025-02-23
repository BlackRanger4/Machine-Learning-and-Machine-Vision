# Machine Vision Learning - Datasets

## Overview
This folder contains datasets used in the **Machine Vision Learning** labs. Due to the large size of some datasets, they are hosted on Google Drive.

## Datasets
The dataset folder contains CSV files with processed data for various computer vision tasks. The raw datasets and additional resources can be accessed at the following link:

🔗 [Google Drive - Datasets](https://drive.google.com/drive/folders/1mElHo6XM_wXRwjLHbDESA0XkXUUwi7Aj)

## Structure
```
/dataset
  ├── local_dataset_1.csv
  ├── local_dataset_2.csv
  ├── ...
  ├── (Large datasets available in Google Drive)
```

## Usage
1. Clone the repository:
   ```bash
   git clone <repo_url>
   cd <repo_name>/datasets
   ```
2. Download large datasets from the provided Google Drive link.
3. Load the datasets in your Python scripts or Jupyter Notebooks:
   ```python
   import pandas as pd
   data = pd.read_csv('local_dataset_1.csv')
   ```

## Notes
- Ensure you have sufficient storage before downloading large files.
- Some datasets may require preprocessing before use.
- Refer to the respective lab notebooks for dataset usage details.

## License
The datasets are provided for educational and research purposes only. Check individual dataset licenses for more details.

## Author
Ali Sadeghian


