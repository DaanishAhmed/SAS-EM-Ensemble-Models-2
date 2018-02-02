Heterogeneous Models on Vehicle Accident Data
----------------

This project involves using SAS Enterprise Miner to analyze a dataset containing vehicular accident information.  I will use ensemble models, which combine distinct models and average their outputs.  Heterogeneous models combine different types of predictive models (such as regression, neural networks, and SVM).  By experimenting with different combinations of ensemble and individual models, I will determine which method is the most accurate and which can identify the highest number of fatal accidents.

The full report can be found in the file "Ensemble Models 2.pdf".  This report shows a complete breakdown of my analysis, including problem identification, motivation, data exploration, data preparation, data partition, ensemble model development, model results, model comparison, and proposed solutions.  Tables and visualizations are included in the appendix.

The dataset "Accidents.xls" was provided by my course instructor at the University of Maryland University College.  It is the same dataset used in my SVM project.  The variable description can be found in the "Data Codes" tab of the Excel file.  First, I converted it into a .csv file using Excel.  Since it uses an older Excel version, I am also providing the .csv file.  Next, I converted it to a .sas7bdat file using SAS Enterprise Miner.  Finally, the data source can be imported into your SAS EM project.

The process flow diagram I created for this project (seen in Figure 1 of my report's appendix) is included in the file "heterogeneous diagram.xml".  The requirements are described in the file "requirements.txt".  To use this diagram, you need to import the .xml diagram into your SAS EM project.