# DataWrangling

#### 001_Text Preprocessing
The data that we provide contains 2,500 patents. Each patent contains a large amount of information represented in the notoriously verbose XML format. The information includes, for example, publication reference, application reference, abstract, description, claims, citations, etc. Here, assume that we are going to focus on the analysis of patent citation network, and the analysis will take into account both the network itself and information associated with each patent (i.e., International Patent Classification (IPC) code and abstract). Therefore, your task is to extract the citation network, hierarchical IPC code, and abstract for each patent.
* Task 1: Extract the hierarchical IPC code.
* Task 2: Extract the citation network.
* Task 3: Identify number of patent citation.
* Task 4: Extract and preprocess abstracts (Abstract provides important information that can assist in learning the citation network. In this task, you are required to extract all the abstracts for all the patents, and then process and store those abstracts as sparse count vectors.)

* Note: datafile "patents.xml" not uploaded yet.


#### 002_Parsing and Cleansing Raw Data	Add files via upload	a minute ago
To wrangle a large set of property sales records stored in an unknown format and with unknown data quality issues.
* Task 1: Parsing the property sales data stored in “data.dat”
* Task 2: Auditing and cleansing the loaded data: 
To inspect and audit the data to identify the data problems, and then fix the problems. 
Problems might include:
  * Lexical errors, e.g., typos and spelling mistakes.
  * Irregularities, e.g., abnormal data values and data formats.
  * Violations of the Integrity constraint.
  * Outliers
  * Duplications
  * Missing values
  * Inconsistency, e.g., inhomogeneity in values and types in representing the same data

#### 003_Data Integration and Reshaping
* Task 1:To integrate data from two different data sources, indicated by S1 and S2 respectively, 
  * S1 (data_s1_ass4.csv): contains 4,600 records.
  * S2 (data_s2_ass4.xml): contains 430 records.
In order to finish the integration task, you will need to resolve schema conflicts (For example, structure conflicts, naming conflicts, and/or entity resolution conflicts) and data conflicts. The output of the task should be a unified data stored in a global schema that should be justified with a clear explanation of the semantic mapping between local schemas used in S1 and S2 and the global schema. While integrating the two datasets, you might need to add new columns, delete columns and merge columns. 

* Task 2: Data Normalization and analyze how they affect the distribution of the data.
  * score normalization, 
  * Min-Max normalization and
  * log transformation
