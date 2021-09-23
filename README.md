# Sandwitch Attack Data Analysis
sandwich loss data


## Uniswap V2 Address Loss Summary

total Uniswap trader address count for past 7 days: 68,643

sample pool: 14,996

sample rate: 21.84%

# of addresses with loss in the sample pool: 3,856 (no contract addresses)

loss percentage: 3,856/14,996=25.71%

estimated # of address with loss for Uniswap V2 traders for past 7 days: 17,648

estimated # of address with loss > 10 ETH for Uniswap V2 traders: 439 (around 2.5% of all loss addresses)

## Loss Range Estimation

### Max&Min Loss in Sample

[Untitled](https://www.notion.so/c1c2fb0077dc4c4e94ee3e88daf95270)

### Loss Distribution

[uniswap_loss_usd (2).pdf](Sandwich%20Attack%20Data%20Summary(updated%2020210922)%20248a2b2b2d744175bec5a3c9d88792b8/uniswap_loss_usd_(2).pdf)

Histogram for loss in USD (only count loss under USD 100,000)

most of the loss is under USD 10,000（nearly 92%）

[estimated loss range in percentage(USD)](https://www.notion.so/ac93699f907c444faba7c49da165ccfd)

[estimated loss range in percentage(ETH)](https://www.notion.so/b0d2897bd5c048aeb970dd82c13692fc)

## Loss Transaction Count

[uniswap_loss_transaction (3).pdf](Sandwich%20Attack%20Data%20Summary(updated%2020210922)%20248a2b2b2d744175bec5a3c9d88792b8/uniswap_loss_transaction_(3).pdf)

Histogram for transaction count with loss for each address

[Estimated transaction with loss in each address](https://www.notion.so/172ce3afc265477ea76b9960395bfa08)

## Sample Loss Data:

loss_address_20210922.csv

[https://github.com/NFTGalaxy/sandwitch-attack-data-analysis/blob/main/data/uniswap/loss_address_20210922.csv](https://github.com/NFTGalaxy/sandwitch-attack-data-analysis/blob/main/data/uniswap/loss_address_20210922.csv)

## Back up

total trade address count : 

uniswap v2:  2,119,846 

uniswap v2 (address trade between 0911 to 0917):  68,643

uniswap v2 (address overall trade usd amount > USD 10,000):  194,407

uniswap v2 (address overall trade usd amount > USD 100,000):  16,058

uniswap v2 (address overall trade usd amount > USD 1,000,000):  535

sushiswap:  230,575

sushiswap (address overall trade usd amount > USD 100,000):  5,602