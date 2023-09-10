# qarbitrage
Reinforcement learning based statistical arbitrage. 

*Disclaimer: These strategies are potential source of alpha and are used in the authors current trading models. Therefore code will be limited to reduce exposure to intricate details yet still include novel and relevent details for the reader. *

This repository aims to show the advantages of using reinforcement learning to trade the spread of two or more assets. 

Z-score are commonly used in statistical arbitrage to identify which asset(s) is cheap relative to another. A particular disadvantage to using z-scores include finding the optimal range to decuce whether the spread is wide enough to trigger buy/sell action. See below: 
