# Introduction

it records some prompts to check how good AI now for understanding bridge game

* https://www.perplexity.ai/ (looks the best)
* https://copilot.microsoft.com/
* https://metaso.cn/
* https://openai.com/

## General info

* ChatGPT has app for this https://chatgpt.com/g/g-hJ8Xi2sdR-expert-bridge-bidding-play-assistant , can upload picture
* https://www.toolify.ai/ai-news/mastering-bridge-with-chat-gpt-the-power-of-ai-in-teaching-2293496
* https://www.youtube.com/watch?v=w_hmJ5Bl31k (good information to learn bridge using ChatGPT-4o)

## What to check
We can try to test the feature like

* PBN format and convert including xinrui, bbo
* understand the bridge
* leading card.
* play a hand (partlym dds)
* analysis the completed board/game
* learning how to play bridge

Which are not interesting

* understanding different bidding system (RAG?)
* upload picture to play bridge


# Experience one by one

## PBN file
### xinrui bridge hand

see https://www.perplexity.ai/search/can-you-analysis-the-xrbridge-Cvf47ZYcRFGy1L7jgmWNYw#5

very nice result to understand the xinrui bridge information from URL [6♥&by South](http://www.xinruibridge.com/deallog/DealLog.html?bidlog=1N,P%3B2D,P,2H,P%3B3C,P,3H,P%3B3S,P,4D,P%3B4N,P,5S,P%3B6H,P,P,P%3B&playlog=E:QC,AC,4C,3C%3BS:QD,6D,3D,5D%3BS:4H,5H,AH,3H%3BN:AD,2D,8S,7D%3BN:KD,9D,KS,TD%3BN:6C,JD,8C,JC%3BW:2C,QH,8D,5C%3BN:2H,7H,KH,3S%3BS:TC,KC,TH,JH%3BE:&deal=QT54.AQT2.AK3.63%20J96.J73.J98542.Q%20K8.K9864.Q.AT985%20A732.5.T76.KJ742&vul=None&dealer=N&contract=6H&declarer=N&wintrick=11&score=-50&str=%E4%B8%AA%E4%BA%BA%E8%B5%9B%20%E7%AC%AC2%E8%BD%AE%20%E7%89%8C%E5%8F%B7%201/8&dealid=1019693014&pbnid=309530839&deal=J96.J73.J98542.Q&K8.K9864.Q.AT984&A732.5.T76.KJ752&QT54.AQT2.AK3.63)

```
can you analysis the xrbridge's url http://www.xinruibridge.com/deallog/DealLog.html?bidlog=1N,P%3B2D,P,2H,P%3B3C,P,3H,P%3B3S,P,4D,P%3B4N,P,5S,P%3B6H,P,P,P%3B&playlog=E:QC,AC,4C,3C%3BS:QD,6D,3D,5D%3BS:4H,5H,AH,3H%3BN:AD,2D,8S,7D%3BN:KD,9D,KS,TD%3BN:6C,JD,8C,JC%3BW:2C,QH,8D,5C%3BN:2H,7H,KH,3S%3BS:TC,KC,TH,JH%3BE:&deal=QT54.AQT2.AK3.63%20J96.J73.J98542.Q%20K8.K9864.Q.AT985%20A732.5.T76.KJ742&vul=None&dealer=N&contract=6H&declarer=N&wintrick=11&score=-50&str=%E4%B8%AA%E4%BA%BA%E8%B5%9B%20%E7%AC%AC2%E8%BD%AE%20%E7%89%8C%E5%8F%B7%201/8&dealid=1019693014&pbnid=309530839&deal=J96.J73.J98542.Q&K8.K9864.Q.AT984&A732.5.T76.KJ752&QT54.AQT2.AK3.63|ul="6♥&by South" it is for bridge game
```

```
can you convert into PBN file format?
```

### bbo bridge hand

https://www.perplexity.ai/search/can-you-analysis-one-bridge-ha-Cuz_74auTWWpWirjfgWl0Q#2

One hand from https://bridgewinners.com/article/view/converting-a-bbo-link-into-a-pbn/

````
can you analysis one bridge hand from bridgebase URL https://www.bridgebase.com/tools/handviewer.html?n=s24kh29td2479qjc6&e=s378qjth348qjd3cj&s=s9ah67ad5ac237akq&w=s56h5kd68ktc4589t&b=1&d=n&v=-&a=pp2cp2dp3cp3nppp&p=sqsas5s2dad6d2d3d5d8dqh3c6cjcac4ckc5d4s3h6hkh2h4s6sks7s9h9hjhah5cqc8s4s8c7c9hth8ctd7stc2dkd9hqc3dtdjsjh7
````

it is LIN format, it is not analysis nicely, the deal looks ugly

`[Deal "N:24.29T.2479QJ.6 378QJT.348QJ.3.J 9A.67A.5A.237AKQ 56.5K.68KT.4589T"]
`

## Play card
### Leading card

see https://www.perplexity.ai/search/this-is-a-bridge-game-please-h-XJWtKrhQS22737pTZABjuQ#0

````
this is a bridge game, please help me to analysis the leading card

The opponents’ bidding is 1NT - 3NT, let’s say, and you look down at this
hand: ♠ A Q J 8 ♥ 9 6 ♦ J 9 7 6 4 ♣ A 2. How do you decide what to lead?
Do you rely on past experience of leading from similar hands?
````

Seems good analysis, but leading the `♠8`, which is quite worse

## Summarize the game/match and give suggestion

### Analysis one complete board

https://www.perplexity.ai/search/can-you-analysis-one-bridge-ha-Cuz_74auTWWpWirjfgWl0Q#6

Looks professional, unfortunately it is wrong. but it goes good direction

# Reference

* https://bridgeonline.ru/wp-content/uploads/2020/04/Winning_Notrump_Leads.pdf