# Wikipedia Category Hierarchy Paths
 We have randomly sampled 713 unique paths each with a length of 5 from WikiPedia Category Hierarchy .We consider the level of each category, i.e., its shortest path to the root, as an indicator for the specificity of that category. The reason we include these paths is to enable the comparative analysis of several categories that are semantically related to each other. Given a set of categories, the objective of an effective specificity metric would be to allow for the correct specificity-based ordering of these categories, the correct ordering of which exists in the test collection. It is then possible to evaluate the performance of any specificity metric using rank correlation measures such as  Kendall's Tau to determine the relationship between the actual order of categories observed in the test collection and the list of categories ranked based on the specificity metric. 
 Each Path as it is shown below, starts with "STARTPATH" line, continues from the most general term to the most specific term in the path and ends with "ENDPATH" term.
 
 STARTPATH  
 Most general category  
 Second most general category  
 third most general category (third most specific category)  
 second most specific category  
 Most specific category  
 ENDPATH
 
