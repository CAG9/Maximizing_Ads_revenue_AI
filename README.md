# Maximizing ads revenue with Artificial Inteligence 
## Author: 
- Cesar Arcos: cesar99ag@gmail.com

## Absract:
We try to maximize the amount of user subscribed in a premium plan (example: "Amazon Prime"), We deploy 9 strategies with different package, form and special deal.
We solve this problem with Thompson sampling.

## Problem : 
Imagine an Online Retail Business that has million of customers. These customers are only people buying
some products on the website from time to time, getting them delivered at home. The business is doing good,
but the board of executives has decided to take some action plan to maximize revenue even more. This plan
consists of offering to the customers the option to subscribe to a premium plan, which will give them some
benefits like reduced prices, special deals, etc. This premium plan is offered at a yearly price of $ 100.
In this case study we will be facing 9 different strategies, and our AI will have no idea of which is
the best one, and absolutely no prior information on any of their conversion rates. However we will make the
assumption that each of these 9 strategies does have a fixed conversion rate. These strategies were carefully
and smartly elaborated by the marketing team, and each of them has the same goal: convert the maximum
clients to the premium plan.We use Online learning, it will consist of deploying a strategy
each time a customer browses the online retail business website to hang out inside or buy some products.
Then as the customer navigates the website, he or she will suddenly get a pop-up ad, suggesting him or her
to subscribe to the premium plan. And for each customer browsing the website, only one of the 9 strategies
will be deployed.

## Results: 
<pre><code>Absolute Return for 10000 users: $ 91300 
Relative Return for 10000 users: 94 %
</code></pre>

![thompson](https://user-images.githubusercontent.com/60860385/93363198-84d3f200-f80c-11ea-918e-8f1b342e4ba1.png)

The best strategy is the  6th, we gain 91300 dollars using the Thompson sampling instead random sampling. 

## License : 
CC BY-NC

## Requirements
* Python 3.7
* Matplotlib
