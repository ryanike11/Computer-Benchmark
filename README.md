# Computer-Benchmark
Analyzing the performance of my custom built PC using a variety of gaming and synthetic benchmarks. 

I measured several varaibles as I tested my computer (such as but not limited to GPU/CPU temperature, power draw, utilization, and clock speed) to see if my PC was performaing as I'd expect for the componenets I bought. The two programs I used to measure these variables were Nvidia's Frameview and HWiNFO64 which saved the data as CSV's that I could then import into R. 
 
I displayed that information as bunch of graphs using ggplot2 in R. Once I had all the graphs, I used a python program to sort through all the outputed graphs into their relavent folders by game/synthetic benchmark. 

In addition, getting a baseline performance analysis of my computer will help me in the future if something starts to act up on my computer. 
 
For example, I'll have a good idea of when my the thermal compound on my CPU cooler needs to be replaced when CPU starts going significantly above the baseline temperature I found it operating at in my testing when all the componenets were new.  
