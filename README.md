# PERCCOM Thesis

This repository contains data analysis and visualization for the thesis project of the Erasmus Mundus Joint Master's Programme in Pervasive Computing & Communications for Sustainable Development (EMJMD PERCCOM) comprising 4 semesters of studies in 
[France](https://formations.univ-lorraine.fr/en/3378-erasmus-mundus-master-in-pervasive-computing-communications-for-sustainable-development.html), 
[Finland](https://scispace.com/pdf/perccom-a-master-program-in-pervasive-computing-and-1nvkz2m6zx.pdf), 
[Sweden](https://www.ltu.se/en/education/degree/exa2240-degree-of-master-of-science-120-credits---major-computer-science-and-engineering) with the thesis semester in Italy, 2017-2019.
 
The thesis _Data center energy efficiency assessment based on real data analysis_ is available at the Lappeenranta University of Technology thesis [archive](https://lutpub.lut.fi/handle/10024/159900).

Thesis presentation is available on [GDrive](https://drive.google.com/file/d/1DxFEsnab_NwH-ptO7cBi6As1Qin822Yg/view?usp=drive_link).


In addition, the following research papers detail various aspects of the data analysis and energy efficiency reporting in data centers:

- Grishina, A., Chinnici, M., De Chiara, D., Guarnieri, D., Kor, Ah-L. (2018). DC Energy Data Measurement and Analysis for Productivity and Waste Energy Assessment. 2018 IEEE International Conference on Computational Science and Engineering (CSE), Bucharest, Romania, pp. 1-11, doi: [10.1109/CSE.2018.00008](https://ieeexplore.ieee.org/abstract/document/8588212).
- Grishina, A., Chinnici, M., De Chiara, D., Rondeau, E., Kor, A.L. (2019). Energy-Oriented Analysis of HPC Cluster Queues: Emerging Metrics for Sustainable Data Center. In: Ntalianis, K., Vachtsevanos, G., Borne, P., Croitoru, A. (eds) Applied Physics, System Science and Computers III. APSAC 2018. Lecture Notes in Electrical Engineering, vol 574 . Springer, Cham. <https://doi.org/10.1007/978-3-030-21507-1_41>
- Grishina, A., Chinnici, M., Kor, A.-L., Rondeau, E., & Georges, J.-P. (2020). A Machine Learning Solution for Data Center Thermal Characteristics Analysis. Energies, 13(17), 4378. <https://doi.org/10.3390/en13174378>.
- Grishina, A., Chinnici, M., Kor, AL., Rondeau, E., Georges, JP., De Chiara, D. (2021). Data Center for Smart Cities: Energy and Sustainability Issue. In: Pop, F., Neagu, G. (eds) Big Data Platforms and Applications. Computer Communications and Networks. Springer, Cham. <https://doi.org/10.1007/978-3-030-38836-2_1>
- A. Grishina, M. Chinnici, A.-L. Kor, D. De Chiara, G. Guarnieri, E. Rondeau, J.-P. Georges (2022).
Thermal awareness to enhance data center energy efficiency,
Cleaner Engineering and Technology,
Volume 6,
2022,
100409,
ISSN 2666-7908,
<https://doi.org/10.1016/j.clet.2022.100409>.


## Methodology
Real monitoring data consists of time series with jobs scheduling data and thermal characteristics of Data Center IT room. The data is analysed with the help of an adapted data lifecycle methodology: through data preprocessing, analysis, and results exploitation stages with visualisation included in all steps when needed. Data analysis is performed within three phases: mathematical modelling applied to the dataset of a jobs scheduler; statistical evaluation of IT room thermal characteristics and thermal metrics evaluation applied to a dataset of IT room temperature readings near the server racks; hotspots localisation using K-Means clustering. 

## Results
Investigation on energy consumption and thermal characteristics of two clusters CRESCO4 and CRESCO6 
of a Data Center residing in ENEA Portici Research Center.

- Energy efficiency and thermal metrics are used to evaluate clusters' performance, and new metrics are proposed,
- DC impact on the environment is shown through the indirect carbon emissions evaluation per month,
- All results are visualized for further use in the manuscript.

## Usage

The repository contains data preprocessing, analysis, and visualization for (CRESCO4)[] and CRESCO6, two clusters in ENEA Portici Research center used for research purposes. 

Library and technology stack: 
- Python 3.5
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- SciPy

### Alternative viewer
If the `\*.ipynb` files are not displayed in Git, kindly use (NBViewer)[https://nbviewer.jupyter.org/] and use the link of a GitHub file location.

## Acknowlegement
The research work has been supported and funded by the PERCCOM Erasmus Mundus Program of the European Union (Klimova, A. et al., 2016). The author is thankful to ENEA Portici and Casaccia Energy Technologies Department, ICT Division teams for the data collection and fruitful collaboration. 

## About PERCCOM Master's Programme
Klimova, A. et al. (2016) ‘An international Master’s program in green ICT as a contribution to sustainable development’, Journal of Cleaner Production, 135, pp. 223–239. doi: 10.1016/j.jclepro.2016.06.032.

Note: similar Erasmus Mundus programmes and international researcher jobs can be found at the (Euraxess website)[https://euraxess.ec.europa.eu/) 
