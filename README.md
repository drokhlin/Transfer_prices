# Transfer_prices
This repository contains the code for the paper 

D.B.Rokhlin, G.A.Ougolnitsky "SOLO FTRL algorithm for production management with transfer prices"

In this paper we consider a firm, consisting from multiple production and sales divisions, and present a simple algorithm, 
producing a sequence of approximately firm-optimal transfer prices without any knowledge of the division revenue and cost functions. 
This algorithm is an instance of the SOLO FTRL algorithm of Orabona and Pal (2018), applied to the dual optimization problem.

1_good_dynamic.ipynb, 1_good_static.ipynb: one commodity, the revenues and costs $f_i$, $g_i$ are shifted power functions

d_goods_static.ipynb, d_goods_dynamic.ipynb:  two commodities, the revenues and costs $f_i$, $g_i$ are quadratic

The parameters of the revenue and cost functions are selected randomly. In the static problems these parameters are sampled only once and are fixed at all iterations. 
In the dynamic problem at each iteration they are independently sampled from the same distribution.
