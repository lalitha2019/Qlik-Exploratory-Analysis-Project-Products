# Qlik-Exploratory-Analysis-Project-Products
Data source: https://www.kaggle.com/datasets/berkayalan/retail-sales-data 
Data format: csv 
Number of files: 1 product_hierarchy.csv - Data includes product Id, hierarchy Ids and product dimenstions. Relatively smal file, with 699 rows. Source does not include a description of data. Thus, the purpose of hierarchy, promotion codes etc. is not clear.
Tool: QlikCloud (free trial) 
Explored this data in 2 ways.
  One, the Product data without much changes except for replacing blanks with nulls, defining a sort order on a couple of columns, etc., - ("Qlik Sense - Exploring Products Data - October 1, 2022.pdf")
  The other was by splitting the product id's into 2 groups - those with a non-null cluster_id and those with no cluster_id.  ("Qlik Sense - Comparing products  - no cluster_id Vs cluster_id - October 7, 2022.pdf")
Qlik project file: "Products only.qvf"
The "Load Script" contains the script for loading Product data, splitting it into groups and joining them. This was done mostly to experiment with "join".
