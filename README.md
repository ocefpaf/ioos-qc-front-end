# ioos-qc-front-end

## Instructions
1. Install environment, this might take a while (>10min)

To create the Conda environment execute: 

```
conda env create -f environment.yml
```

and then activate the new environment:

```
conda activate ioos-qc-front-end
```
2. Launch Streamlit

To launch the Streamlit app:
```
streamlit run streamlit_file_upload.py 
```

3. Follow onscreen instructions to complete QA/QC using QARTOD and download data with QA/QC flags as CSV file.

## Example Use Step-by-step Instructions
1. Launch Streamlit app
2. Drag and drop "water_level_example_test.csv" (from this repo) into "Drag and Drop files here"
3. Choose "sea_surface_height_above_sea_level" as the variable
4. Choose gross range test
5. Choose test range, leave default numbers for the example
6. Click run test
7. Download CSV file
