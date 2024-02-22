Submission Note for CIS5450 Term Project, Fall 2023
 
Team: Claudia Peinado, Jeff Robson, Chukwudire Uba
 
Date: 4 December 2023
 
The following Google Colab code notebooks are presented in satisfaction of the requirements for Deliverable 1 of the CIS5450 Term Project, Fall 2023
 
The listed annotated notebooks represent the functional code used to complete the requirements of the term project:
 
1. CIS5450_TermProject_01_acquire_data_COMPLETE.ipynb:  This notebook — generally archival in nature — reflects the workflow to identify, collect, and parse resources, discretize large datasets, clean and parse data, and conduct preliminary data investigations. It captures the whole of the foundational data acquisition work, including ideas that were tried and later discarded in favour of more optimal approaches.
2. CIS5450_TermProject_02_load_data_COMPLETE.ipynb: This notebook reflects a foundational step of the overall project process. Here, we read project datasets into a Dask dataframe format for modification and analysis in later project steps. In this notebook, we mount a shared drive of project data in comma-separated value (.csv) format, and define and run a series of functions to read the datasets.
3. CIS5450_TermProject_03_compose_data_COMPLETE.ipynb: This notebook includes the necessary step to collate, clean, and compile a project dataset from the distinct data sources introduced in Data Foundations. The resulting product from this notebook is a project dataset comprising a series of summary data joined with the English Indices of Deprivation to illustrate data trends at the sub-borough level. This project dataset is used as the basis for modelling tasks.
4. CIS5450_TermProject_04_map_data_COMPLETE.ipynb: This notebook includes code to visualize several cartographic products that help a selection of influences on the housing and STR markets in inner London.
5. CIS5450_TermProject_05_Bivariate_Model_COMPLETE.ipynb: This notebook explores a bivariate relationship between a dependent variable cost_fl_area (the average property cost per square metre in an LSOA geographic area) and an independent variable count_list (the number of short-term rental [STR] listings in a LSOA geographic area) using standard Linear Regression, Random Forest, and Decision Tree (both regression) modelling approaches. This is the first of three notebooks that apply a modelling approach to the data we have sourced, cleaned, and collated.
6. CIS5450_TermProject_06_Expanded_Variable_Model_COMPLETE.ipynb: This notebook continues exploration of the linear relationship between the dependent and independent variable above. In this notebook, we introduce several confounding variables in the form of the scores for the domains established in the English Indicies of Deprivation 2019, collected at the LSOA level for Greater London. This is the second of three notebooks that apply a modelling approach to the data we have sourced, cleaned, and collated. We apply several linear regression techniques–including the introduction of neural network architecture–to explore this relationship.
7. CIS5450_TermProject_07_STR_Feature_Review_COMPLETE.ipynb: This notebook reflects a corollary data investigation premised on a detailed variant of the STR listings dataset that explores the relationship between STR property features and their cumulative pricing. In this notebook, we build a condensed data pipeline by loading, cleaning, and analyzing detailed STR data before applying a series of modelling approaches to explore the relationship

In addition, we include for posterity several notebooks in the folder ‘deprecated_archive’; these notebooks represent previous exploratory work that was made obsolete by later upstream changes to data or the study approach. These deprecated notebooks are:
 
1. CIS5450_TermProject_clean_data_DEP.ipynb
2. CIS5450_TermProject_compose_data_with_regression_test_DEP.ipynb
3. CIS5450_TermProject_Linear_Model_V1_DEP.ipynb
4. CIS5450_TermProject_RandomForest_and_DecisionTree_models_V1_DEP.ipynb
 
For Deliverable 2, the following Medium blog post is provided:
 
“London Calling: Exploring the influence of short-term rentals on housing affordability in pre-pandemic inner London”
 
https://medium.com/@jsrobson_/london-calling-exploring-the-pre-pandemic-influence-of-short-term-rentals-on-urban-property-47bc2708eb4d
