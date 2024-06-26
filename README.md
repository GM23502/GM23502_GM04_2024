# GM23502_GM04_2024
Repository with an executable Jupyter Notebook with the same code as on the assignment that has been handed in by GM23502 for GM04 Advanced Bioinformatics. The module is offered by the department of Medical Genetics, School of Clinical Medicine, University of Cambridge.

The file with the code, "GM23502_GM04_Notebook.ipynb", is saved with the code having been run and the output being printed. "RVAS_counts.xlsx" is the input file, and "RVAS_results.csv" is the output file with the OR, 95% CIs, P value, and Adjusted P value included.

### To run the code independently

1. Download the repository and save it on your Desktop. **the setwd() command will have to be modified independently if the user is not running macOS**
2. Ensure the R kernel is downloaded for Jupyter Notebook. Donwloading the R kernel can be achieved by running the following three lines of code on the R console:

> install.packages("devtools")

> devtools::install_github("IRkernel/IRkernel")

> IRkernel::installspec()

3. Run the code independently

### R version and packages version

- R 4.3.3 (Angel Food Cake)
- tidyverse 2.0.0 

### Jupyter version

- IPython          : 8.12.0
- ipykernel        : 6.19.2
- ipywidgets       : 8.0.4
- jupyter_client   : 8.1.0
- jupyter_core     : 5.3.0
- jupyter_server   : 2.5.0
- jupyterlab       : 4.0.11
- nbclient         : 0.5.13
- nbconvert        : 6.5.4
- nbformat         : 5.7.0
- notebook         : 7.0.8
- qtconsole        : 5.4.2
- traitlets        : 5.7.1

### Computer software and processing chip used

- Computer: 14-inch 2023 MacBook Pro
- Chip: Apple M2 Pro
- MacOS: Sonoma 14.3.1
