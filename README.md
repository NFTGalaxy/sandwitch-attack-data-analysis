# Sandwitch Attack Data Analysis
sandwich loss data


## Uniswap V2 Address Loss Summary

total Uniswap trader address count for past 7 days (20210911-20210917): 64,296 (no contract addresses)


addresses with loss in the sample pool: 16,560 (no contract addresses)

* loss percentage: 16,560/64,296=25.76%

* address with loss > 10 ETH for Uniswap V2 traders: 346

## Loss Range Estimation

### Max&Min Loss in Sample
|     |              |             | 
|-----|--------------|-------------| 
| #   | max          | min         | 
| usd  | 	1305175.35	 | 	-407178.24	 | 
| eth | 360.94       | -111.60     | 



### Loss Distribution

most of the loss is under USD 10,000（nearly 92%）

![Image of loss](https://github.com/NFTGalaxy/sandwitch-attack-data-analysis/blob/main/data/uniswap/uniswap_loss_usd.jpg)



|                     |       | 
|---------------------|-------| 
| usd_loss            | %     | 
 | 	(min, 0.0]	 | 	3.79	 | 
 | 	(0.0, 10,000.0]	 | 	87.57	 | 
 | 	(10,000.0, 50,000.0]	 | 	7.37	 | 
 | 	(50,000.0, 100,000.0]	 | 	0.83	 | 
 | 	(100,000.0, max]	 | 	0.44	 | 


|              |       | 
|--------------|-------| 
| eth_loss     | %     | 
|	(-min, 0.0]	|	3.79	|
|	(0.0, 1.0]	|	76.99	|
|	(1.0, 10.0]	|	17.13	|
|	(10.0, 20.0]	|	1.33	|
|	(20.0, max]	|	0.76	| 


## Loss Transaction Count

![Image of loss transaction](https://github.com/NFTGalaxy/sandwitch-attack-data-analysis/blob/main/data/uniswap/uniswap_loss_transaction.jpg)


|                |       | 
|----------------|-------| 
| sandwich_count | %     | 
|	(1, 5]	|	51.25	|
|	(5, 10]	|	19.00	|
|	(10, 50]	|	24.54	|
|	(50, 100]	|	3.60	|
|	(100, max]	|	1.61	|

## Sample Loss Data:

[loss_address.csv](https://github.com/NFTGalaxy/sandwitch-attack-data-analysis/blob/main/data/uniswap/loss_address.csv)



## Sushiswap Address Loss Summary

total Uniswap trader address count for past 7 days (20210911-20210917): 18,219  (no contract addresses)


addresses with loss in the sample pool: 4,673 (no contract addresses)

* loss percentage: 4,673/18,219=25.65%

* address with loss > 10 ETH: 155


## Loss Range Estimation

### Max&Min Loss in Sample
|     |              |             | 
|-----|--------------|-------------| 
| #   | max          | min         | 
| usd | 1,305,874.05	 | 	-59,662.09| 
| eth | 361.11	 	| 	-16.50 | 



### Loss Distribution

most of the loss is under USD 10,000（nearly 88.4%）

![Image of loss](https://github.com/NFTGalaxy/sandwitch-attack-data-analysis/blob/main/data/sushiswap/sushiswap_loss_usd.jpg)



|                     |       | 
|---------------------|-------| 
| usd_loss            | %     | 
 | 	(min, 0.0]	 | 	3.77	 | 
 | 	(0.0, 10,000.0]	 | 	84.65	 | 
 | 	(10,000.0, 50,000.0]	 | 	9.42	 | 
 | 	(50,000.0, 100,000.0]	 | 	1.24	 | 
 | 	(100,000.0, max]	 | 	0.92	 | 


|              |       | 
|--------------|-------| 
| eth_loss     | %     | 
|	(-min, 0.0]	|	3.77	|
|	(0.0, 1.0]	|	72.22	|
|	(1.0, 10.0]	|	20.70	|
|	(10.0, 20.0]	|	1.97	|
|	(20.0, max]	|	1.35	|


## Loss Transaction Count

![Image of loss transaction](https://github.com/NFTGalaxy/sandwitch-attack-data-analysis/blob/main/data/sushiswap/sushiswap_loss_transaction.jpg)


|                |       | 
|----------------|-------| 
| sandwich_count | %     | 
|	(1, 5]	|	48.76	|
|	(5, 10]	|	18.34	|
|	(10, 50]	|	25.66	|
|	(50, 100]	|	4.37	|
|	(100, max]	|	2.86	|


## Sample Loss Data:

[loss_address_sushiswap.csv](https://github.com/NFTGalaxy/sandwitch-attack-data-analysis/blob/main/data/sushiswap/loss_address_sushiswap.csv)


## Back up

total trade address count : 

* uniswap v2:  2,119,846 

  * uniswap v2 (address overall trade usd amount > USD 10,000):  194,407

  * uniswap v2 (address overall trade usd amount > USD 100,000):  16,058

  * uniswap v2 (address overall trade usd amount > USD 1,000,000):  535

* sushiswap:  230,575

  * sushiswap (address overall trade usd amount > USD 100,000):  5,602
