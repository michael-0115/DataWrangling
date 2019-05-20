### 001_Text Preprocessing
The data that we provide contains 2,500 patents. Each patent contains a large amount of information represented in the notoriously verbose XML format. The information includes, for example, publication reference, application reference, abstract, description, claims, citations, etc. Here, assume that we are going to focus on the analysis of patent citation network, and the analysis will take into account both the network itself and information associated with each patent (i.e., International Patent Classification (IPC) code and abstract). Therefore, your task is to extract the citation network, hierarchical IPC code, and abstract for each patent.

Task 1: Extract the hierarchical IPC code.

Task 2: Extract the citation network.

Task 3: Identify number of patent citation.

Task 4: Extract and preprocess abstracts (Abstract provides important information that can assist in learning the citation network. In this task, you are required to extract all the abstracts for all the patents, and then process and store those abstracts as sparse count vectors.)

Note: datafile "patents.xml" not uploaded yet.
