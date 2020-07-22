# Exploratory data analysis and visualisation

### Purpose
The purpose of this project is to investigate and visualise data using several data science tools. The statistics related to all electricity generation in Australia is explored primarily through visualisation with tools such as `motion chart` and `linear regression`. The pre-processed tweets about bushfires in Australia is also investigated and explored through the process of exploratory data analysis (EDA).

### Version
1 May 2020

### User Instructions
- The Python code written to analyse and plot the data is a Jupyter notebook file. To run the Jupyter notebook file, `energy_data.xlsx` and `twitter_data.csv` should be placed in the same location as `Exploratory-Data-Analysis.ipynb`. 
- Alternatively, it can be viewed in `Exploratory-Data-Analysis.html` or `Exploratory-Data-Analysis.pdf`.

### Interesting Findings
- Energy dataset: As you can see from the motion chart below, the reliance on Wind increased significantly from 2009 to 2018 in South Australia, while that on Natural gas had been stagnant. On the other hand, the reliance on Natural gas continuously increased over time in Western Australia, while that on Wind fluctuated during the same time.</br>

&nbsp;&nbsp;&nbsp;<img src="images/motion_chart.gif" width="500">

- Twitter dataset: Seen from the violin plot below, the interquartile range (IQR) which is marked as red dots does not vary much among twitter age groups. Regarding the median which is represented as the white dot, it is noted that the median of the group "0-2" and the group "1-2" is lower than any other group. This means that the authors who had been using Twitter less than 2 years had less tweet length, on average, compared to the authors using Twitter more than 2 years.</br> 

&nbsp;&nbsp;&nbsp;<img src="images/violin_plot.png" width="500">

### Dataset
- [Australian Energy Statistics](https://www.energy.gov.au/government-priorities/energy-data/australian-energy-statistics)
- Twitter
