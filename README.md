# Drug Discovery using Machine Learning and Data Analysis
COVID-19, caused by the virus SARS-CoV-2 has affected over 15 million people worldwide resulting in more than 5.32 million deaths. The process of drug discovery by traditional methods usually takes an enormous amount of time which we cannot afford during a pandemic. THerefore, machine learning prediction tools for identifying potential drug targets are being increasingly used to shorten the time required to find a potential drug target. 
In this project, a machine learning model is built using bioactivity data of Coronavirus target protein obtained from the ChEMBL database by installing the the ChEMBL web service package.
### Steps include-
1. Collection of the bioactivity data of molecules from the ChEMBL database with known activity against Coronavirus, along with their structural and physicochemical properties. 
2. Pre-processing of the data - 
   - Handling missing data
   - Labeling compounds as either being active, inactive or intermediate
3. Exploratory Data Analysis (Chemical Space Analysis) and Descriptor calculation using Lipinski descriptors
   - Conversion of IC50 values of molecules to pIC50 values
   - Removal of the "intermediate" bioactivity class from the dataset
   - Data Visualization and Statistical Analysis using the Mann-Whitney U test
   - pIC50 > 6 = Actives and pIC50 < 5 = Inactives parameters were used to define actives and inactives.
4. Descriptor Calculation and Dataset Preparation
   - Calculation of molecular fingerprint descriptors that are essentially a  quantitative description of the compounds in the dataset using PaDEL descriptor
   - Preparing the X and Y matrices
5. Model Building- Building a Regression Model using Random Forest
6. Plotting the expected and predicted IC50 values

   
   
   

