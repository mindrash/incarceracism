![incarceracism](./docs/1440x400.png)

[Etherscan](https://etherscan.com/address/0x5C3071CA988d75363A9CD800Bef9CBd2CeA005f4) | 
[Polyscan](https://polygonscan.com/address/0x041C3Ffed16970ffbAD868e409d106576CDAE905) | 
[tzkt](https://tzkt.io/KT1JrjQM1Meh8miZ4QcwEpWg7BMZ4mFXiu1C/operations/) | 
[Fantomscan](https://ftmscan.com/address/) | 
[Twitter](https://twitter.com/mindrash) | 
[Discord](https://discord.gg/B8F2R3qd) | 
[metadevil.io](https://metadevil.io) | 
[pebkac.fyi](https://pebkac.fyi) | 
[itsmookie.com](https://itsmookie.com)

# Incarceracism
Incarceracism is a data influenced view of the 70% racial minorities incarceration percentage based on the [Prisoners in 2020 - Statistical Tables NCJ 302776](https://bjs.ojp.gov/library/publications/prisoners-2020-statistical-tables) report provided by the Bureau of Justice Statistics.

NFT art details:<br/>
6,763 x 6,763 pixels PNG ERC-721 NFT [CC0 license](https://creativecommons.org/share-your-work/public-domain/cc0/)<br/>
<br/>
([Free mint on Etherscan](https://etherscan.io/address/0x5c3071ca988d75363a9cd800bef9cbd2cea005f4#writeContract#F4))

## Description
In my life I have learned that words may not be as impactful as data points. In this situation I don't feel I have many more words I could add to frame the thoughts and discussions that this data should call forth and draw out. I can provide a vehicle for the data to be looked at in another way. That is what I am hoping the Incarceracism art and NFT lends to facilitate change. The colors of the art are directly influenced in the programming logic that produces them to be at least 70% racially symbolic. I hope someone can appreciate them in a way that one may be displayed and cause someone to pause, think, and change.

There are a total of 3,000 pieces in the series, but will be distributed across multiple chains to spread the idea as far and wide as possible. Most of the series will be free mint except to provide a few examples to demonstrate. On Polygon 1,000 of them will be minted to demonstrate the series and to be held by the creator for yet to be determined future allocation. See below for how they are distributed.

| chain | amount                            | collection |
|-------|-----------------------------------|------------|
| Ethereum (ETH) | 100 - 3 minted, 97 free mint | [Incarceracism #1 - 100](https://opensea.io/collection/incarceracism-1-100) |
| Tezos (XTZ) | 100 | [Incarceracism #101 - 200](https://objkt.com/collection/KT1JrjQM1Meh8miZ4QcwEpWg7BMZ4mFXiu1C) | 
| Polygon (MATIC) | 1000 allocated to creator, 1700 ([free mint](https://etherscan.io/address/0x5c3071ca988d75363a9cd800bef9cbd2cea005f4#writeContract#F4)) | [Incarceracism #201 - 2900](https://opensea.io/collection/incarceracism-201-2900) |
| Fantom (FTM) | 100 - 3 to be minted, 97 free mint | TBD |

## Examples
![incarceracism](./docs/examples.png)

Incarceracism #1<br/>
![incarceracism](./docs/1.png)

## Technologies
- Python - art generation
- Solidity - ERC-721
- Ethereum, Tezos, Polygon, Fantom
- IPFS - hashed image on meta

ETH Contract: 0x5C3071CA988d75363A9CD800Bef9CBd2CeA005f4 ([free mint](https://etherscan.io/address/0x5c3071ca988d75363a9cd800bef9cbd2cea005f4#writeContract#F4))<br/>
Polygon Contract: 0x041C3Ffed16970ffbAD868e409d106576CDAE905<br/>
Fantom Contract: TBD<br/>
Tezos Contract: KT1JrjQM1Meh8miZ4QcwEpWg7BMZ4mFXiu1C<br/>

The art is deceptively simple, but took a long time to process. The handcuff placement is the most expensive part of the program for each piece. The code wants to find a good available location to put the handcuff so that it looks correct. That process can take some time and it will eventually give up after 1,000 tries.

The process took almost <strong>12.5 hours to create 3,000 pieces</strong>. Below is a log snippet:
```
root - INFO -  ___                                             _               
|_ _|_ __   ___ __ _ _ __ ___ ___ _ __ __ _  ___(_)___ _ __ ___  
 | || '_ \ / __/ _` | '__/ __/ _ \ '__/ _` |/ __| / __| '_ ` _ \ 
 | || | | | (_| (_| | | | (_|  __/ | | (_| | (__| \__ \ | | | | |
|___|_| |_|\___\__,_|_|  \___\___|_|  \__,_|\___|_|___/_| |_| |_|
                                                                 

root - INFO - ********************************************************************************
root - INFO - Starting: 2022-06-18 20:25:25.307085
root - INFO - Started creating: #0
root - INFO - Finished creating: #1
root - INFO - Started creating: #1
root - INFO - Finished creating: #2
root - INFO - Started creating: #2
root - INFO - Finished creating: #3
root - INFO - Started creating: #3
...
root - INFO - Finished creating: #2997
root - INFO - Started creating: #2997
root - INFO - Finished creating: #2998
root - INFO - Started creating: #2998
root - INFO - Finished creating: #2999
root - INFO - Started creating: #2999
root - INFO - Finished creating: #3000
root - INFO - ********************************************************************************
root - INFO - Finished: 2022-06-19 08:56:49.223790
```

## Variations

| variation           | description                                             |
|---------------------|---------------------------------------------------------|
| bg_color      | 8 colors |
| shapes color  | 70%+ minority colorations between 7 randomly selected palettes including orange  |
| bars          | 5% no bars, 95% random 2 - 23 bars |
| handcuffs     | random 1 - 20 with 1,000 attempts to place or else 0|
| bar color               | 98% black 2% orange |
| rotated                 | 33% rotated 180 degrees |

## Data Summary
### Prisoners in 2020 – Statistical Tables

NCJ Number 302776<br/>
Author(s): E. Ann Carson, Ph.D., BJS Statistician<br/>
Date Published: December 2021<br/>
Publication: Series Prisoners<br/>

### Description

"This report is the 95th in a series that began in 1926. It describes demographic and offense characteristics of state and federal prisoners. It also provides data on prisoners held under military jurisdiction. Findings are based on data from BJS’s National Prisoner Statistics program."
<br/><br/>
[https://bjs.ojp.gov/library/publications/prisoners-2020-statistical-tables](https://bjs.ojp.gov/library/publications/prisoners-2020-statistical-tables)
<br/><br/>

---

[Etherscan](https://etherscan.com/address/0x5C3071CA988d75363A9CD800Bef9CBd2CeA005f4) | 
[Polyscan](https://polygonscan.com/address/0x041C3Ffed16970ffbAD868e409d106576CDAE905) | 
[tzkt](https://tzkt.io/KT1JrjQM1Meh8miZ4QcwEpWg7BMZ4mFXiu1C/operations/) | 
[Fantomscan](https://ftmscan.com/address/) | 
[Twitter](https://twitter.com/mindrash) | 
[Discord](https://discord.gg/B8F2R3qd) | 
[metadevil.io](https://metadevil.io) | 
[pebkac.fyi](https://pebkac.fyi) | 
[itsmookie.com](https://itsmookie.com)
