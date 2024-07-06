##### This is experiment is discussed to understand the functioning of path based reasoning technqiues ([slides](https://github.com/SankarshU/Knowledge-Graph-Reasoning/blob/1f41f39ab68d6cada3aeb5dda0b3d8dd2cacc1c6/Experiments_with_CURL/KGR-Path%20Based%20Reasoning%20CURL.pptx))
##### Particular code and its modification to preform the experiment has been included ([code](https://github.com/SankarshU/Knowledge-Graph-Reasoning/tree/9470fac97ad7a57661cc306cdc11ce1039945a7d/Experiments_with_CURL/Code_for_CURL_Expt))
##### Data preparion is not included in teh Repo,adhering to  the data protection policy but idea can be applied and validated on publicly available data
##### The troubleshooting experiment is intended to demonstrate a way to explore/understand path-based knowledge reasoning, both conceptually and  implementation. For accurate experiments, please consider the datasets mentioned in the paper 

#### In a troubleshooting scenario we are given followlling 
- Tickets/Problems (T)
- Workorders/Resolutions (W)
- Relation between a Ticket and its Resolution
- Various characteristics of Tickets and Resolutions as attributes
- Other information such as:
  - Faults
  - Locations
  - Weather
  - others

#### The task is to provide various reasons as to why a particular Ticket was resolved in a particular way, given the above information

- Preqreusites : Knowledge graph creation using all the above information
- Apply knwolege graph reasoning to answer questions traversing the knowledge graph

#### Fig1:Knowledge graph from the sample data   
![image](https://github.com/SankarshU/Knowledge-Graph-Reasoning/assets/44226862/4f9eeeff-221a-410a-aaf8-7d1f728cd84b)

#### Fig2:Evaluation of KGR using CURL and comparision with results from benchmark dataset from the paper
![image](https://github.com/SankarshU/Knowledge-Graph-Reasoning/assets/44226862/27810835-8d7e-4784-bd6f-be9ff0a151b4)

#### Fig3:A particular scenario to explore with CURL[providing additional context for ticket(T) entity during the traversal]
![image](https://github.com/SankarshU/Knowledge-Graph-Reasoning/assets/44226862/5b90e437-df67-485f-97f2-46c61d02a3b3)
