---
layout: post
title: "Trade Review for Thu 26 Sep 2024"
date: 2024-09-27
author: N30
categories: trading
tags: [gold, nasdaq, trading, demotrading, crt]
---
I am trading Hancock's CRT Model.

- Gold H4 setups (XM time)
- 0400 - 2 losses, continuation
- 0800 - no trade, no setup
- 1600 - 1 BE, CRT setup to 50%, still floating <100%
- 2000 - didn't trade

- Nasdaq
- 0400 - 1 loss, continuation
- 0800 - no trade, no setup
- 1600 - 1 win, CRT setup to 100%
- 2000 - didn't trade

## Gold Trades

- 0400 H4 (9PM EDT)
- Timed Range: 0000-0359 (5:00PM-8:59PM)
- Time of Purge:
- Time of Execution:
- Yet to update

- 0800 H4 (1AM EDT)
- No trade, no setup

- 1600 H4 (9AM EDT)
- Timed Range: 1200-1559 (5:00AM-8:59AM)
- Time of Purge: 
- Time of Execution:
- Time CSID SL Hit:
- Yet to update


- 2000 H4 (1PM EDT)
- Didn't trade
---

## Nasdaq Trades

- 0400 H4 (9PM EDT)
- Timed Range: 5:00PM-8:59PM
- Watched M5
- Time of Purge: 0500, broke high so watched for bearish CISD
- Time of CISD1: 0510
- Time of CISD2: 0540 
- Broke High of CISD2: 0540,  invalidating trade (SL position)
- I held positions with larger SL and closed loss at 0635
- Lesson: Place SL at CSID high/low. Stick to hancock trade setup rule, don't float unless ATR(4) is large
- I am only demo trading strategy right now, not dealing with risk management yet.

- 0800 H4 (1AM EDT)
- No trade, no setup

- 1600 H4 (9AM EDT)
- Timed Range: 1200-1559 (5:00AM-8:59AM)
- News at 1620
- Watched M1
- Time of Purge: 1603 , Broke CR high, so watched for bearish CSID
- Time of TS (on M5): 1610
- Time of CSID1: 1613
- Time of CSID2: 1620
- Time of Execution: 1627 (entered late)
- Time 50% hit: 1630
- Time 100% hit: 1634

- 2000 H4 (1PM EDT)
- Didn't trade

---

## Lessons and To Do:
- Backtest 1AM, 9AM, 1PM, 9PM for Gold and Nasdaq. Choose only high 2 probability H4s, and which not to trade.
- Also consider my work timing, the above candles are at 11AM, 3PM, 11PM, and 3AM. I can consider 11AM and 11PM for one asset. Or 3PM and 11PM for different assets. Usually when there is a setup on an H4 range, there is a continuation on the next H4.
- Always watch for a TS, not just CSID. TS is a necessary condition to validate. There are different forms of TS also, not just wicks. 
- Sometimes TS forms on M5 but CSID on M1, could be the same for M15 and M5
- Keep journal emtries in XM time (UTC+2) to simplify. Just the first headings can include NY Time in parentheses.
- Study simple CSID entries and invalidation with SL for Hancock model.
- Study advanced CSID entries and whether it is worth taking this extra step.
- Study simple CSID entries including ATR(4) adjustments for SL to allow for volatility.
- Incorporate risk management rules with Hancock CRT model, we can reset demo  balances next week for this.
- Can demo trade BTC, ETH and crypto during the weekend with Hancock model.
- Simplify my template for trade records. CSID time may not be necessary. Execution is important since we are dealing with a purge window, TP times are also important in case it floats over 2 H4s.
- Consider M5 TS, and M1 CSID1 and CSID2, review successful setups with this rule.
- Search Telegram and YouTube for Romeo, Hancock, and Mario CRT videos and watch.
