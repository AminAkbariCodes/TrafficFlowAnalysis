# Traffic Flow and Density Analysis

This Jupyter notebook is designed to analyze different aspects of traffic flow and density using several datasets. The notebook is capable of calculating and visualizing various traffic parameters such as Vehicle Hours Traveled (VHT), Vehicle Miles Traveled (VMT), traffic density, and flow.

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- scipy
- IPython

## Instructions

To run the notebook, you need to have four data files named `data1.zip`, `data2.zip`, `data3.zip`, and `data4.zip` in the same directory as the notebook. Alternatively, you can download the datasets from the following link: [https://www.dropbox.com/s/8t8iyt80pugw7cx/problem2.4-datasets.zip?dl=0](https://www.dropbox.com/s/8t8iyt80pugw7cx/problem2.4-datasets.zip?dl=0)

When running the notebook, you'll be prompted to choose one of the datasets to consider for the analysis. Enter your choice as a number between 1 and 4.

The notebook then reads the chosen dataset, performs calculations and outputs visualizations such as Flow-Density and Speed-Density plots. At the end, it also generates an Excel file named `Final_Results.xlsx` containing cumulative results.

## Code Structure

The notebook is divided into several sections:

1. **Import Statements**: The necessary libraries are imported.
2. **Data Loading**: The dataset is chosen and loaded into pandas DataFrames.
3. **Data Manipulation**: For each lane, calculations such as VHT, VMT, and effective VHT and VMT are performed.
4. **Traffic Density Calculation**: Traffic density 'k' is calculated for all lanes.
5. **Traffic Flow Calculation**: Traffic flow 'q' is calculated for all lanes.
6. **Speed Calculation**: Speed 'v' is calculated for all lanes.
7. **Final Calculations and Plotting**: The results are aggregated, and Flow-Density and Speed-Density plots are generated.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
