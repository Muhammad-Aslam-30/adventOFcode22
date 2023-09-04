This is a Master thesis work titled **"Optimal Multilayer Storage of Useful Intermediate Results of Big Data Applications"**
The souce code in SparkCAD.ipynb will contain the code for implementation where it visulize the logical plan of an entire Spark application in the form of DAG graphs. The code parses the execution logs of SparkI. Some of the sample logs are available in the logs folder. Below are the requirements to run the code successfully in Jupyter Notebook.

 * [Python](https://www.python.org/downloads/)
 * [Jupyter](https://jupyter.org/)
 * [Graphviz](https://graphviz.readthedocs.io/en/stable/manual.html)

### Steps in the implementation phase ###
- [x] Analyze and create a recommended schedule for RDDs persistance state.
- [x] Analyze and strore RDDs recomputation time. 
- [x] Reorder recommended schedule based on the RDDs persistance state.
- [x] Create a time model for RDDs to be cached.
- [x] Analyze the time model and suggest the optimal storage level.
- [x] Create functions to deal with the storage level suggestions.
- [x] Create functions to change the storage level of an RDD based on its recomputation time.

### Steps in the evaluation phase ###
- [ ] Develop a Spark code based on the user's template.
- [ ] Run the application in SparkI to generate enriched execution logs.
- [ ] Evaluate the enriched execution logs in SparkCAD+.
- [ ] compare the performance with and without using SparkCAD+.

### Results ###
