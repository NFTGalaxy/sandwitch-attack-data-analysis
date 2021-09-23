# Sandwitch Attack Data Analysis
sandwich loss data


## Uniswap V2 Address Loss Summary

total Uniswap trader address count for past 7 days (20210911-20210917): 68,643

* sample pool: 14,996

* sample rate: 21.84%

addresses with loss in the sample pool: 3,856 (no contract addresses)

* loss percentage: 3,856/14,996=25.71%


**estimated # of address with loss for Uniswap V2 traders for past 7 days: 17,648** 

**estimated # of address with loss > 10 ETH for Uniswap V2 traders: 439 (around 2.5% of all loss addresses)**

## Loss Range Estimation

### Max&Min Loss in Sample
|     |              |             | 
|-----|--------------|-------------| 
| #   | max          | min         | 
| usd | 1,035,494.73 | -320,164.72 | 
| eth | 360.94       | -111.60     | 



### Loss Distribution

most of the loss is under USD 10,000（nearly 92%）

![Image of loss](https://github.com/NFTGalaxy/sandwitch-attack-data-analysis/blob/main/data/uniswap/uniswap_loss_usd.jpg)



|                     |       | 
|---------------------|-------| 
| usd_loss            | %     | 
| (min, 0.0]          | 3.68  | 
| (0.0, 10,000.0]      | 88.56 | 
| (10,000.0, 50,000.0]  | 6.85  | 
| (50,000.0, 100,000.0] | 0.54  | 
| (100,000.0, max]     | 0.36  | 


|              |       | 
|--------------|-------| 
| eth_loss     | %     | 
| (-min, 0.0]  | 3.68  | 
| (0.0, 1.0]   | 76.34 | 
| (1.0, 10.0]  | 17.48 | 
| (10.0, 20.0] | 1.69  | 
| (20.0, max]  | 0.80  | 


## Loss Transaction Count

![Image of loss transaction](https://github.com/NFTGalaxy/sandwitch-attack-data-analysis/blob/main/data/uniswap/uniswap_loss_transaction.jpg)


|                |       | 
|----------------|-------| 
| sandwich_count | %     | 
| (1, 5]         | 51.44 | 
| (5, 10]        | 19.08 | 
| (10, 50]       | 24.20 | 
| (50, 100]      | 3.64  | 
| (100, max]     | 1.63  | 


## Sample Loss Data:

[loss_address_20210922.csv](https://github.com/NFTGalaxy/sandwitch-attack-data-analysis/blob/main/data/uniswap/loss_address_20210922.csv)

## Back up

total trade address count : 

* uniswap v2:  2,119,846 

  * uniswap v2 (address trade between 0911 to 0917):  68,643

  * uniswap v2 (address overall trade usd amount > USD 10,000):  194,407

  * uniswap v2 (address overall trade usd amount > USD 100,000):  16,058

  * uniswap v2 (address overall trade usd amount > USD 1,000,000):  535

* sushiswap:  230,575

  * sushiswap (address overall trade usd amount > USD 100,000):  5,602
