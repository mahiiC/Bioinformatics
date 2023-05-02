# Drug Discovery using Machine Learning and Data Analysis
Acetylcholinesterase is one of the most vital drug targets for the treatment of Alzheimer's disease which is a chronic neurodegenerative disease causing memory loss and cognitive abilities in elderly people.
Acetylcholinesterase (AChE) is an enzyme that is essential for the breakdown of the neurotransmitter acetylcholine in the nervous system. It is also the primary target of drugs used to treat Alzheimer's disease. However, these medications only provide symptomatic relief, and their therapeutic benefits diminish over time.
Screening of inhibitors for AChE enzymes have already gained some success with three commercial drugs approved by the FDA including donepezil, galantamine, and rivastigmine.
In this project, a machine learning model is built using bioactivity data of Acetylcholinesterase obtained from the ChEMBL database by installing the the ChEMBL web service package.
### Steps include-
1. Collection of the bioactivity data of molecules from the ChEMBL database with known activity against acetylcholinesterase, along with their structural and physicochemical properties. 
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

   
   
   

