# CVoteRank
Overview: This repository contains the implementation of the CVoteRank method in a Jupyter Notebook.

 1. CVoteRank-Final.ipynb: This Jupyter Notebook (Version 6.5.2) contains the implementation of the CVoteRank method. Change the path in os.chdir(), and provide the dataset name in the CSV format.
 2. Toy-CVoteRank.csv is the Toy network used in our manuscript. (Please note: For the toy network, We get the three different communities for the 15 nodes, i.e.,{1: 1, 2: 1, 3: 1, 4: 1, 5: 1, 6: 1, 7: 0, 8: 0, 9: 0, 10: 0, 11: 0, 12: 2, 13: 2, 14: 2, 15: 2}, implies nodes in a community are:{1, 2, 3, 4, 5, 6}, nodes in another community are {7, 8, 9, 10, 11}, and nodes in another community are {12, 13, 14, 15}).
 3. dataset: A folder containing 12 datasets in CSV format used for the experiments. Each dataset represents a graph.
 4. results: The computed results are stored inside the dataset folder of the respective name of the dataset.
