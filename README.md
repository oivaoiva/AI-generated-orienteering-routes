<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# AI generated orienteering routes

Final project for the Building AI course

## Summary

This project is about building an AI to generate orienteering training courses based on the orienteering world cup routes. We gather data from the various world cup competitions and try to delegate the course set to the AI.


## Background

Orienteering course setting takes time in the forest and on the computer screen. Sometimes courses need a lot of tiny adjustments. There are many things to delegate to the AI and workflows that could be easy to automate. To make a good training course, you will need many years of knowledge and experience in the course setting. The final project could save a lot of time and bring more joy to the self-training.


## How is it used?

The user would upload the base map to the web service and select the difficulty, length, number of checkpoints, and additional settings of the final map. Then the AI solution would generate a world-class training map, which the user could go and test. If the user wants to adjust the training map, the service saves the map as a draft, and the user can come and edit it afterward.


## Data sources and AI methods
The data source to use is the collected library of world cup maps and the [World Of O Maps database](http://omaps.worldofo.com/index.php?). The best AI methods to use might be the Machine learning and Deep reinforcement learning (RL). [Read more of the ML and RL as a mapping tool.](https://medium.com/devseed/exploring-new-ai-methods-for-road-mapping-7edbe6b73c19)

If the user doesn't have a base map, he/she can use [Pullautuskartta database](https://pullautuskartta.fi/) to export selected terrain as a base map.


## Challenges

The solution does not automatize the whole course setting process and won't know if the generated map is 100% suitable for training in the selected terrain. As well if the base map isn't up to date, the generated course could mislead the user.  This solution won't be good for beginner orienteers.


## What next?

The prototype concept could be developed by a couple of developers. Also, the map database needs to be built up. 


## Acknowledgments

* [Pullautuskartta database](https://pullautuskartta.fi/)
* [World Of O Maps database](http://omaps.worldofo.com/index.php?)
* [ML and RL as a mapping tool.](https://medium.com/devseed/exploring-new-ai-methods-for-road-mapping-7edbe6b73c19)
