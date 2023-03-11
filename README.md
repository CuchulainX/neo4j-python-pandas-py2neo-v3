# neo4j-python-pandas-py2neo-v3
Use pandas to extract the data in excel and load it into the neo4j database in the form of triples to build a relevant knowledge map
# Neo4j knowledge map construction
![](https://s1.ax1x.com/2018/11/13/iObQkn.png)

### 1. Operating environment:
python3.6.5
windows10
For specific package dependencies, please refer to the file requirements.txt
```
pip install -r requirements.txt
```

### 2. Pandas extracts excel data
The Excel data structure is as follows

<img src="https://s1.ax1x.com/2018/11/13/iObTc8.png" width="800" hegiht="500" align=center />

Through the function data_extraction and function relation_extraction, the node data and contact data required to construct the knowledge map are respectively extracted to construct triplets.
Data extraction mainly uses pandas to convert excel data into dataframe type
invoice_neo4j.py
<img src="https://s1.ax1x.com/2018/11/13/iOb4ht.png" width="500" hegiht="313" align=center />

### 3. Node and edge data required for building a knowledge graph
DataToNeo4jClass.py
<img src="https://s1.ax1x.com/2018/11/13/iXk6iV.png" width="500" hegiht="313" align=center />

-------------------------------------------------- -------------------------------------------------- -
## 2019.2.15 update
### Update the neo4j_matrix.py code to convert the data extraction in the knowledge graph into a matrix, and provide data for the machine learning model

## Thank you for your support. In the future, the sharing of knowledge graphs will be synchronized to my official account [Cloud Data]
