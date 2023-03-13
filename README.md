# Debug-in-Python-decitiontree
if there exists a categorical column, lets' say it has three levels: a, b, c. The python will give different answers at the same dataset different sequences. 
The idea behind it is that python can not recognize abc, so they give abc 012 randomly. After giving the levels number, python sort the level by numbers. In this part, some bug happens. So there will exists different grouping way and different ess.
The idea behind the debug way is to enumerate all the combination way of encoding the categorical variable and choose the optimal grouping way by minimum ess. For example, we encode abc as 012,021,102,120,201,210. Then plant tree based on these 6 situations. Among them, choose the best one.
