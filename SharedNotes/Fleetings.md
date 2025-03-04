Discuss organization of code:
* I like jupyter notebooks: 
    * can narrate the code outside of comments with more formatting  
    * allows for outputs and visualizations (data frames and graphs) to be represented directly under the code
    * followed with analysis 
    * can be dumped to a .py script
        * it will include all of the narrative by default
        * can be told to exclude markdown cells when rendering using the `Jupytext` library 

Discuss best way to communicate
* not email
* some other cross platform app: a team in teams allow us to organize everything in one place
    * Planner has task management board
    * direct messaging is easier to navigate
    * meetings/calendar can be organized there

Shared Obsidian Vault?
___
Use unsupervised discretization to overcome correlation?
* while the decision tree algorithm could potentially navigate correlation incidentally, the complexity it can introduce could make it less interpretable and cause overfitting
    * this is compounded by the fact that for attributes can be reused 
* the thought is to check if discretizing the correlated data to see if it undermines the similarity between the correlated numeric data
* this is based on the understanding that unsupervised discretization will build partitions based on their proportion to the class values in it, like preemptive splitting as a preprocessing step but focusing on each attribute by itself
* this would need to be checked for overfitting by checking for the distance between accuracy of the testing and training data (but we would do this either way)