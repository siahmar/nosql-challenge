#### Module 12 Challenge

#### Part 1: Database and Jupyter Notebook Set Up

The **Siawash_NoSQL_setup.ipynb** sets up and updates the database. The **Siawash_NoSQL_analysis.ipynb** queries relevant information for analyses and converts results into Pandas DataFrame. The data provided in the establishments.json file was imported using Terminal with:

**mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json**
