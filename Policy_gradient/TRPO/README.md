# Summary
## 1. Approximately Optimal Approximate Reinforement Learning:  
It presents lower bound of the difference in reward between policy functions. This form is used in TRPO paper.   

That form is given by quantifying policy improvement.  
<p align="center"> <img src="./img/lemma.png" alt="MLE" width="80%" height="80%"/> </p>  

The new policy is defined as  
<p align="center"> <img src="./img/update.png" alt="MLE" width="80%" height="80%"/> </p>   

By that form, when α = 0, new policy is equal to π and, when α = 1 new policy is equal to π'. And the poliy gradient of new policy when α = 0 is given by  
<p align="center"> <img src="./img/gradient.png" alt="MLE" width="70%" height="70%"/> </p>  
By same insight, 
<p align="center"> <img src="./img/sight.png" alt="MLE" width="100%" height="100%"/> </p>  

___
**Lemma 2:** It shows that two differenct policy's expected reward difference is given by  
<p align="center"> <img src="./img/lemma2.png" alt="MLE" width="100%" height="100%"/> </p>  

Using **lemma 2** for defining lower bound of difference in reward between policy functions, is that  
<p align="center"> <img src="./img/lowerbound.png" alt="MLE" width="100%" height="100%"/> </p>  



## 2. Trust Region Policy Optimization:  


# Results

# Reference
TRPO paper: https://arxiv.org/pdf/1502.05477.pdf  
Approximately Optimal Approximate Reinfor ement Learning:  
https://people.eecs.berkeley.edu/~pabbeel/cs287-fa09/readings/KakadeLangford-icml2002.pdf   
https://ieor8100.github.io/rl/docs/Lecture%207%20-Approximate%20RL.pdf