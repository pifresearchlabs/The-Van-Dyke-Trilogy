# The-Van-Dyke-Trilogy
The Van Dyke Trilogy — forensic investigations into the first prediction-market insider trading prosecution

The Van Dyke Series

Forensic investigations into the first federal insider-trading prosecution involving a prediction market.
On April 23, 2026, the U.S. Attorney's Office for the Southern District of New York unsealed an indictment against Master Sergeant Gannon Ken Van Dyke — an active-duty U.S. Army Special Forces operator stationed at Fort Bragg — alleging that he used classified information about Operation Absolute Resolve, the military operation to capture Nicolás Maduro, to make $409,881 in profit on Polymarket. The DOJ filed five counts; the CFTC filed a parallel civil complaint. It is the first prediction-market insider-trading case ever brought in U.S. federal court.
This repo is the four-part forensic record of that case, written from the on-chain trade data in the days following the indictment.

The pieces

📈 They Caught One. The Tape Shows 36 More.

 Identifies the cohort of 37 wallets that took the same trade as Van Dyke in the 18-hour pre-leak window, deploying $832K in capital and sitting on $254K of unrealized profit when Trump went on television. None of the other 36 have been named in any indictment.

🏗️ The Laundering Ceiling · Van Dyke Trilogy · I
Why better post-trade laundering wouldn't have helped. The pre-trade accumulation curve is the evidence; everything downstream of the trade is just metadata. Empirical confirmation via the cohort wallet that received three real-time funding top-ups — at 01:01, 03:52, and 04:40 UTC on January 3 — exactly during the insider window.

🎭 The Six Mistakes · Van Dyke Trilogy · II
A teardown of the operational errors that turned an insider trade into a federal case. Personal email on signup. Single fresh wallet. Photo on the USS Iwo Jima uploaded to a personal Google account. Linear laundering through a brokerage account in his own name. A burner email pre-registered two weeks before the first trade. Each mistake paired with what the sophisticated cohort apparently did instead.

🪞 The Proxy Problem · Van Dyke Trilogy · III
The structural piece. Polymarket's proxy-wallet architecture creates a four-layer identity gap: open-source forensics can prove the trade happened and identify the trading wallet, but matching the wallet to a real person requires a Polymarket subpoena. The DOJ caught Van Dyke because Polymarket cooperated. Whether the next 36 cases get built is a resourcing question, not a technical one.

The thesis, in one paragraph
Insider trading on prediction markets leaves a permanent trace that cannot be obfuscated, regardless of how the proceeds are laundered afterwards. The trace is the shape of the price chart in the hours before the news — flat-to-vertical, volume breaking before price, accumulation by a small number of large wallets at sub-15¢ entries. Identifying the pattern is open-source forensics; identifying the trader is subpoena work. The Van Dyke case proves the pattern is prosecutable. It does not prove the prosecution will scale.

Reading order
These pieces stand alone, but they sequence. If you read them in order, the argument builds:

They Caught One establishes that the cohort exists.
The Laundering Ceiling explains why the cohort can be identified at all.
The Six Mistakes shows what happens when an operator is naïve about that fact.
The Proxy Problem explains why the cohort probably won't all be prosecuted anyway.


How to read
All four pieces are single-file HTML. Open in any browser. Mobile-responsive. No build step, no dependencies, no tracking.

About
Published by @paidinfullintel — Paid In Full, an on-chain forensic publication covering the speculation economy. Wallet-holder behavior across spot, perpetuals, and prediction markets.

Disclaimer
Nothing in this repo is investment, legal, or tactical advice. The reporting is based on public on-chain data, the unsealed federal indictment, and contemporaneous news coverage. Wallet attributions are statistical pattern-matching, not legal identifications. The 36 wallets identified in the cohort are anonymous to this analysis and have not been accused of any crime.

Filed April 24, 2026. Data current to settlement on January 5, 2026.
