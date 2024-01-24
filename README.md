## NODD Data Scripts

## Description
The NOAA Open Data Dissemination ([NODD](https://www.noaa.gov/information-technology/open-data-dissemination)) program works to make NOAA datasets openly available in the cloud. For students and scientists who may be new to cloud-hosted data, there is often a steep learning curve to the process of requesting, reading, and visualizing a dataset. Additionally, use of data in the the cloud is a relatively new topic among physical scientists within NOAA, so trainings and tools are not yet widely available for a general audience.

This project aims to bridge that gap by selecting NOAA datasets hosted on AWS, Azure, and/or Google to read, visualize, and display in an intuitive Jupyter Notebook format. The notebooks are easy to use and require little coding knowledge to execute, but provide a thorough foundation for scientists who are ready to begin writing their own code to access cloud-hosted data. 

Almost every notebook results in a data visualization, so the user can see exactly what data they've pulled and can, hopefully, get excited about the applications of physical science datasets!

## Usage
1. **finding_products.ipynb:**.    
This notebook outlines the access of cloud-hosted data from all three Cloud Service Providers (CSPs) that partner with NOAA. finding_products.ipynb does not produce any visualizations, but is meant to act as a guide for accessing datasets in the cloud, using GOES-R data as an example. 

2. **CAG_precip_trends.ipynb** and **CAG_temp_trends.ipynb:**.    
These notebooks do not use cloud-hosted data, but do use NCEI's Climate at a Glance ([CAG](https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/)) dataset to dive into climate data analysis. In both notebooks, through instructions guide the user through an analysis of trends. 

3. **xyz_csp.ipynb:**.    
All other notebooks use a NOAA dataset (xyz) hosted by a Cloud Service Provider (csp), as indicated in their file name. 

Each of these notebooks outlines the data product, intent, audience, and outcome in Markdown before any code is executed. This way, the user can ensure that the code fits their reserach needs and addresses questions they may have. 

The introduction is followed by executable code, where the user runs cells and provides user input as instructed by the notebook. 

The end of each notebook outlines product documentation, coding resources, and the Cloud Service Providers (CSPs) that currently host the dataset, according to the [NODD product page](https://www.noaa.gov/nodd/datasets). 

If the user wishes to continue evaluating the information in the provided notebooks, they are encouraged to download and run the code in their own environment or perform a simple analysis using Binder. 

## Support
If you have any questions about these notebooks, please contact Mya Sears at mjsears@ncsu.edu.     
If you have questions about NOAA datasets in the cloud, please reach out to the NODD team at nodd@noaa.gov.

## Authors and acknowledgment
Thank you to the scientists at the North Carolina Institute for Climate Studies ([NCICS](https://ncics.org)), who have provided ideas and context for these scripts. Many others throughout NOAA have similarly provided suggestions and use cases that have spurred ideas shown within the notebooks.  

Further coding acknowledgements are located at the foot of all Jupyter Notebooks within this repo.
