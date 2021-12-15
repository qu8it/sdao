## SDIP-002: SDOG Investor Value Recovery and Future DAO Viability Alignment Proposal

### Notes
*01: (New) Snowdog DAO will be abbreviated and referred to as SDAO.  
02: SDOG refers to the original Snowdog token, contract address: [0xde9e52f1838951e4d2bb6c59723b003c353979b6](https://snowtrace.io/token/0xde9e52f1838951e4d2bb6c59723b003c353979b6)  
03: SD2 used herein __only__ as a placeholder for the new SDAO protocol token.  
04: For further Q&As and clarification please join the (New) Snowdog DAO [Discord](https://discord.com/invite/2B8xctNajA)*

---

### SDAO Objectives

1. Successful launch of the SDAO protocol and long-term value accrual for its investors (in SD2);
2. Target a non-zero non-negative return on capital for SDOG investors;
3. Align SDOG investor preferences with SD2 investor preferences; and
4. SDAO token economics strategy to follow principles of decentralisation and backed by at least $1 equivalent of a basket of reserve currencies (e.g. MIM).


The new team seeks to ensure success of the new SDAO protocol (SD2), whilst seeking to provide a positive return on invested capital for SDOG investors. SDAO cannot ‘pre-mine’ and distribute SD2 to SDOG holders as this is: antithetical to long-term value alignment between past and future investors; a protocol failure (at time 0) in ensuring that tokens issued are backed by at least $1 (equivalent to a basket of reserve currencies); against general principles of decentralisation, i.e. SDAO governance control will be concentrated amongst SDOG holders, also to (1), hindering the possibility of establishing a successful DAO.

There are **TWO** options for the community to consider;
- Option 1: SDOG utility as a warrant/option tokens
- Option 2: SDOG utility as a reward rate booster/multiplier

---

### Option 1: Warrant/Option Feature

#### General Assumptions Underpinning this Option

1. SDOG superficially reclassified as a warrant token issued as part of the initial public funding round lasting 8 days (hosted by SnowbankDAO). 
2. ALL SDOG holders are considered henceforth public investors in SDAO and provided the initial seed capital (noting that >95% of which SnowbankDAO misappropriated, and legal recourse and/or recovery lag may be significant, and uncertain);
3. SDOGs trading in the secondary market are warrant tokens from (1), trading without any restrictions, and accessible to past and future (potential) investors.

#### Proposal

This approach seeks to treat SDOG as a precursor derivative of SD2. SDOG token holders will have the right to mint SD2 by burning SDOG and providing the intrinsic value of SD2. 

For example, an SDOG investor would provide 1 MIM and 1 SDOG to mint 1 SD2. Thus it only makes sense to the investor to redeem when SD2 price is above intrinsic value. The purchase price of this derivative was different for each investor; introducing a dynamic ‘strike price’ that is largely at the discretion of the investor.

Further, in order to ensure incentives are aligned with the long term success of SDAO, SDOG is also considered vested based on the supply of SD2 at a rate of 1%. This means that at 1 million SD2 supply, a maximum of 10,000 SDOGs can be redeemed. At approximately 7 million SD2 supply, all circulating supply of SDOGs will be eligible for redemption. As the protocol grows, the potential upside for SDOG investors is significant under this proposal, from the current valuation levels.

#### Scenario Analysis

Assumptions:  

Reference stable coin: MIM  
SD2 Supply: 1,000,000  
SDOG Vested: 10,000 (1% x SD2 supply)  
RFV: $2,000,000  
MV of Treasury (MVT): $10,000,000  
Intrinsic Value (IV) per SD2: $10  
Risk Free Price (RFP) per SD2: $2  
SD2 Market Price: $30 (assume 3x MVT)

Investor actions under this scenario:  

- SDOG Investor holdings: 5 SDOG  
- Cost of exercising warrant: 5 SDOG plus 50 MIM (5 x IV)  
- Investor receives: 5 SD2 (market value $150)  

SD2 treasury actions under this scenario:  

- Mint 5 SD2 and then autostake for investor  
- Burn 5 SDOG  
- Add 50 MIM to treasury Risk Free Assets (RFA) pool.  

#### Summary of Option 1

All SDOG holders are considered 'whitelisted' and seed investors in SDAO. If SD2 is trading at US$30 with an intrinsic value of US$10, SDOG investors will have the option to burn 1 SDOG and pay $10 MIM for 1 SD2. SD2 treasury will burn the SDOGs upon exercise and add the MIM to its RFA pool.

At an equilibrium valuation, we expect the floor price of SDOG to converge towards the price of SD2 minus the intrinsic value. If SDOGs were to trade below this valuation then a clear arbitrage will exist thus triggering a market driven pull to parity. Over a sufficient time horizon, this approach will recover value for SDOG holders whilst enabling the SD2 protocol to grow and succeed.

SDOGs will be considered a perpetual warrant honored by SDAO. Anybody, at any time, subject to vesting limitations, if holding SDOGs, will be able to pay the intrinsic value of SD2, burn SDOGs and receive SD2. Exercise of the warrant is entirely at the discretion of the holder.

---

### Option 2: Reward Rate Booster/Multiplier

#### General Assumptions Underpinning this Option

1. SDOG tokens to be attributed SDAO utility as a Reward Rate (APY/APR) multiplier;
2. Unless voted for by this DAO, no sunset provisions will apply to (1) and remain effective indefinitely;
3. ‘Base SDOG APY Multiplier’ will be a variable rate set through SDAO treasury policy;
4. SDOG and SD2 investor votes to be weighted equally, for all SDAO proposals;
5. Time subordination will not apply. That is, SDOG investors and SD2 investors can equally purchase SDOG tokens in the open market at any time and receive the reward rate multiplier effect. 
6. Maximum SDOG supply capped indefinitely at 75,111.428067 SDOG; and 
7. SDOGs may be burnt by the SDAO treasury or investors at their discretion without limitation.

#### Proposal

This proposal seeks to treat SDOG tokens as a reward rate (APY/APR) booster/multiplier. Investors staking SDOG tokens at the end of each epoch will receive the benefit of their reward rate multiplied by a factor, ‘SDOG_APY_Multiplier’, equal to:

>1 + (Base_SDOG_APY_Multiplier - 1) * (SDOG_Deposited / SDOG_Supply)

where:  
>Base_SDOG_APY_Multiplier: Variable rate set by treasury policy (and subject to future DAO approval)  
>SDOG_Deposited: Total SDOGs staked/held by investors at each epoch, sharing the same address as their sSD2 holdings.  
>SDOG_Supply: Static value, capped at 75,111.428067

Note that staking rewards can only be paid in SD2, irrespective of whether the staking is carried out via SD2 only or a combination of SDOG and SD2. Users will not be able to stake SDOG tokens without SD2. SDOG utility is limited to the detailed reward rate boost mechanics, the result of which is then retroactively applied to the user’s total sSD2 (staked SD2) holdings at the end of each epoch.

#### Scenario Analysis

Assumptions:

SD2 Staked: 1,000,000  
sSD2 Outstanding: 1,000,000  
Reward Rate: 0.50%  
SDOG Supply: 75,111.428067  
SDOG Staked: 10,000  
Base SDOG APY Multiplier: 150%  

(A) 10,000 SDOG staked by 25% of SD2 investor addresses  

Applicable Reward Rates:
  - SD2 Staked Only [75%]: 
    - Reward Rate: 0.50% (as per policy, unchanged)
  - SD2 Staked plus SDOG Staked [25%]:
    - SDOG APY Multiplier: 1 + (0.5 * 10000 / 75111.428067) =  107%
    - Reward Rate: 0.50% * 106.7% = 0.5333%
  - Blended Reward Rate (100%): 0.5083%

(B) 50,000 SDOG staked by 45% of SD2 investor addresses  

Applicable Reward Rates:
  - SD2 Staked Only [55%]: 
    - Reward Rate: 0.50% (as per policy, unchanged)
  - SD2 Staked plus SDOG Staked [45%]:
    - SDOG APY Multiplier: 1 + (0.5 * 50000 / 75111.428067) =  133%
    - Reward Rate: 0.50% * 133% = 0.6664%
  - Blended Reward Rate [100%]: 0.5749%


#### Summary of Option 2

This approach seeks to collectively incentivise SDOG utilisation; the more SD2 investors that boost their reward rate using SDOG, the higher the overall reward rate multiplier collectively for these subset of investors. SD2 only investors will receive their expected reward rate without subordination or negative consequences, and are encouraged (but not required) to purchase SDOGs to boost their reward rate. 
 
SDOG and SD2 will be equally weighted with respect to DAO on-chain voting. With regards to voting power, as the supply of SD2 increases, SDOG investors will become increasingly diluted, as intended. Consequently, SD2 investors will form the majority voice (in relation to DAO proposals) over the medium- to long- term horizon. This approach provides for a smooth transition to a larger and more representative investor base as the SDAO protocol grows. 

The ‘Base SDOG APY multiplier’ will be a variable rate set by future DAO voting, however, initially set by the team at 150%, inline with a token economics strategy seeking to rapidly add utility to SDOG, thus benefiting treasury assets valuation and runway (in the short-term).

---

Please consider each option in detail before voting.  

Join the SDAO [Discord](https://discord.com/invite/2B8xctNajA) for general discussion or to seek clarification of the options detailed.

