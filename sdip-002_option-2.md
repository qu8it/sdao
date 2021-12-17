## SDIP-002: SDOG Investor Value Recovery and Future DAO Viability Alignment Proposal

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


<img src="https://latex.codecogs.com/svg.latex?\small&space;1&space;&plus;&space;(SDOG\,&space;APY\,&space;Multiplier_{Base}&space;-&space;1)&space;*&space;\frac{SDOG_{Deposited}}{SDOG_{Supply}}&space;\\&space;\\&space;where:&space;\\&space;SDOG\,&space;APY\,&space;Multiplier_{Base}:\&space;\&space;variable\&space;rate\&space;set\&space;by\&space;treasury\&space;policy\&space;(and\&space;subject\&space;to\&space;future\&space;DAO\&space;approval)\\&space;SDOG_{Deposited}:\&space;\&space;total\&space;SDOGs\&space;staked\&space;by\&space;investors\&space;at\&space;each\&space;epoch,\&space;sharing\&space;the\&space;same\&space;address\&space;as\&space;their\&space;sSD2\&space;holdings\\&space;SDOG_{Supply}:\&space;\&space;static\&space;value,\&space;capped\&space;at\&space;75,111.428067" title="\small 1 + (SDOG\, APY\, Multiplier_{Base} - 1) * \frac{SDOG_{Deposited}}{SDOG_{Supply}} \\ \\ where: \\ SDOG\, APY\, Multiplier_{Base}:\ \ variable\ rate\ set\ by\ treasury\ policy\ (and\ subject\ to\ future\ DAO\ approval)\\ SDOG_{Deposited}:\ \ total\ SDOGs\ staked\ by\ investors\ at\ each\ epoch,\ sharing\ the\ same\ address\ as\ their\ sSD2\ holdings\\ SDOG_{Supply}:\ \ static\ value,\ capped\ at\ 75,111.428067" />


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
