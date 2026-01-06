# EC50-high-throughput-workflow

This repository contains the `EC50_processing_workflow.ipynb` which was used in the paper 'A high throughput workflow to assess biologically relevant ion transport and membrane lysis for antimicrobial discovery'. The workbook is in 2 sections: Processing - the interactive workflow used to process the data and Plotting - used to generate the plots shown in the ESI.

## Repository Structure 

- **hill_fit_plots**: Contains the hill plots generated from the `summary_file_with_hill_fits.csv`.

- **manual_processing_files**: Contains excel spreadsheets with manual processing of EC50 plate reader data.

- **plate_reader_data**: Contains date from the plate reader as .csv files, named date_initals_lipid_plate and metadata containing the cell layout by cell line as well as the layout of compounds and concentrations.

- **summary_file**: Contains the summary file generated from the `EC50_processing_workflow.ipynb` workflow generated on all the files within - **plate_reader_data**
