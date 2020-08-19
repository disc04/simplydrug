## Welcome to simplydrug


<div align="justify">  To advance scientific communication and integrative drug discovery, we developed a set of open-source based analysis workflows. These workflows describe the early stages of biological assay development and high throughput screening and provide a hands-on introduction to Drug Discovery for everybody with basic knowledge of biology, python programming, or data science. </div>

<img style="float: left; margin-right:700px" width="400" src="hts_notebooks/hts_images/bcdd.png">

## List of notebooks

The notebooks are built in a sequence and gradually introduce concepts of experimental design, QC, and data analysis of different biological assays.
 
 * [__01a_enzyme_kinetics__](https://github.com/disc04/simplydrug/blob/master/hts_notebooks/01a_enzyme_kinetics.ipynb)      
Topics: enzyme kinetics, enzyme assays, fluorometry, assay variability and confidence intervals, Z-factor, Z-score based normalization, plate heatmap, hit extraction, molecule visualization, importing molecule bioactivity data.
 
 
 * [__01b_enzyme_kinetics_in_chain__ ](https://github.com/disc04/simplydrug/blob/master/hts_notebooks/01b_enzyme_kinetics_chain.ipynb)      
Topics: Running enzymatic assay for a number of plates, generating screen hit matrix, plot for all the plates in the screen.     


 
 * [__02a_ion_channel_development__ ](https://github.com/disc04/simplydrug/blob/master/hts_notebooks/02a_ion_channel_development.ipynb)             
Topics: Introduction to ion channels and assay development, ion flux assay normalization, ion channel kinetics time-series.


 
 * [__02b_ion_channel_cherry_picking__](https://github.com/disc04/simplydrug/blob/master/hts_notebooks/02b_ion_channel_cherry_picking.ipynb)         
 Topics: Calcium influx assay, cherry picking, percent of activation or inhibition.      
 
 
 
 * [__02c_ion_channel_dose_response__](https://github.com/disc04/simplydrug/blob/master/hts_notebooks/02c_ion_channel_dose_response.ipynb)       
Topics: Introduction to dose-response, Hill equation.   
   
 
 * [__03a_yeast_growth_screen__](https://github.com/disc04/simplydrug/blob/master/hts_notebooks/03a_yeast_growth_screen.ipynb)     
 Topics: Running yeast growth assay, growth curve, growth score, filtering out aberrant curves.
 
 
 * [__03b_yeast_growth_in_chain__](https://github.com/disc04/simplydrug/blob/master/hts_notebooks/03b_yeast_growth_in_chain.ipynb)     
 Topics: Running yeast growth assay for a number of plates, filtering, generating screen hit matrix, plotting all the plates in the screen.     
  
   
 * [__03c_yeast_cherry_picking__](https://github.com/disc04/simplydrug/blob/master/hts_notebooks/03c_yeast_cherry_picking.ipynb)         
Topics: Running yeast growth assay with different doses of the compounds. Generation of automatic ppt report.

  
 * [__04a_imaging_screen__](https://github.com/disc04/simplydrug/blob/master/hts_notebooks/04a_imaging_screen.ipynb)      
 Topics: High-content screening and image analysis, reporter system, cell viability, systematic errors detection and correction. 
 
 
 * [__4b_imaging_assay_development__](https://github.com/disc04/blob/master/simplydrug/hts_notebooks/4b_imaging_assay_development.ipynb)  
 Topics: Exploration data anslysdis, PCA, Batch effect.
 
 
 
 * [__04c_imaging_dose_response__ ](https://github.com/disc04/simplydrug/blob/master/hts_notebooks/04c_imaging_dose_response.ipynb)    
 Topics: Activity versus viability, fitting dose-response for imaging data. 
 
 
 * [__05_xtt_assay__](https://github.com/disc04/simplydrug/blob/master/hts_notebooks/05_xtt_assay.ipynb)    
Dose-response assay for compound toxicity.

## Install

There are several options:

1. Run the notebooks from Binder    

[![Binder](https://img.shields.io/badge/Binder%20Launch:-simplydrug-blue.svg?colorA=&logo=data:image/png;base64,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)](https://mybinder.org/v2/gh/disc04/simplydrug/master)

2. pip install simplydrug     

3. Clone this repository: git clone https://github.com/disc04/simplydrug


## Dependencies

The codebase relies on the following dependencies (tested version provided in parentheses):

 - python (3.6.1)
 - pubchempy (1.0.4)
 - scipy (1.4.1)
 - seaborn (0.10.0)
 - python-pptx (0.6.18)
 - wget(3.2)
 - xlrd (1.2.0)
 - rdkit (2019.09.3)

## Example usage

<div align="justify"> In each experiment, first, we merge numerical data coming from equipment with the plate layout (descriptors). We describe the experimental design in a layout excel file, and the names of the excel sheets become the names of the columns in a final data table. Each excel sheet contains a table with dimensions of the experiment plate (usually 96 or 384-well plates) and represents some aspect of the layout  -  well ID, treatment, cell density, compound ID, compound concentration, etc.</div> 

<div align="justify"> The layout file must contain sheets named  'Well' and 'Status'. The 'Well' table lists well IDs, and the 'Status' can contain either 'Sample', 'Positive' or 'Negative' control, or 'Reference' values. 'Reference' wells are excluded from calculations. The function add_layout merges measurements and layout by the 'Well' column.</div>

```python
import pandas as pd
import simplydrug.core as sd

data = pd.DataFrame(pd.ExcelFile('hts_notebooks//hts_data//enzyme_kinetics_data1.xlsx').parse(0))[['Well','0s','120s','240s', '360s']]
layout_path = 'hts_notebooks//hts_data//enzyme_kinetics_layout.xlsx'
chem_path = 'hts_notebooks//hts_data//compounds//example_chemicals.csv'
chem_plate = 'ex_plate1'

results = sd.add_layout(data, layout_path, chem_path = chem_path, chem_plate = chem_plate)
display(results.head())
```

<img style="float: left; margin-right:700px" width="950" src="hts_notebooks/hts_images/index_df.png">

To check our 384 well plate for systematic errors, we often use heatmap representation:

```python
sd.hts_heatmap(df = results, layout_path = layout_path, features = ['120s'], path = None)
```

<img style="float: left; margin-right:700px" width="500" src="hts_notebooks/hts_images/index_heatmap.png">

<div align="justify"> In this plate, most of the readings across the plate are close to the plate average, and four wells with high readings probably represent our hit compounds.</div>
<div align="justify"> Please refer to the documentation page for more information.</div>


### Copyright

<div align="justify"> Copyright 2020 onwards, Blavatnik Center for Drug Discovery. Licensed under the Apache License, Version 2.0 (the "License"); you may not use this project's files except in compliance with the License. A copy of the License is provided in the LICENSE file in this repository.
</div>
