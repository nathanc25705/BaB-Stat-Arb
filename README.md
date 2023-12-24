In the repo you will find a jupyter notebook containing oop python code for a bet-against-beta statistical arbitrage trading strategy as well as some analysis of the strategy performance.

The main motivation behind the bet-against-beta trading strategy is to challenge the assumptions of the Capital Asset Pricing Model (CAPM). The CAPM suggests a positive linear trend between expected returns and beta, i.e., higher-beta assets should yield higher risk adjusted returns due to their exposure to market risk. However, over time it has been observed that low-beta assets have historically provided higher risk adjusted returns than CAPM would predict, and the opposite is seen for high-beta assets. 

 

**Why is this?** 

* Frazzini and Pedersen, 2014 suggest that this effect may be due to funding or leverage constraints. They propose that an investor with constrained funding prefers to invest their capital in higher beta (more risk) assets with higher expected returns. This excess demand for risky assets overvalues high-beta names leading to lower returns than what would be predicted by CAPM.

* Hendershott, Livdan and Rösch, 2018 suggest that this effect may be due to the type of marginal investor during trading hours. They suggest that the marginal investor during the day is a risk-loving speculator who demands high-beta assets leading to an overvalue of these assets relative to what CAPM would suggest. In contrast they find that the marginal investor at night is a long-term investor who does not drive up the demand for high-beta assets above what is suggested by CAPM. 

 

The Bet-against-Beta (BaB) strategy attempts to profit from this mispricing of risky assets by going long low-beta assets and short high-beta assets to form a beta-neutral (free from market risk) portfolio. This type of strategy is known as a statistical arbitrage as it attempts to exploit deviations from statistical relationships between securities. 
