# 401k Capital Flight - Fly Over Funds

Inspired by the content in "Survival of the Richest: Escape Fantasies of the Tech Billionaires" by Douglas Rushkoff, I will be anazlyzing the options provided by TNReady, the 401k portal/provider for State of TN employees.

Based on the funds available, I will research what the underlying assets of the funds contain and where they are located. For location I will be using corporate HQ or the city/country the comapny is incorporated in as that is where I will say the money is 'flowing' to. 

I expect the vast majority of money to flow out of Tennessee, meaning other regions are benefiting from our capital and capital flight out of the state is occurring. States like Tennessee are essentially "Fly over funds." 

I will use the EDGAR Database provided by the SEC with the APIs:
data.sec.gov/api/xbrl/companyconcept/
data.sec.gov/api/xbrl/companyfacts/
data.sec.gov/api/xbrl/frames/

The relevant forms are N-Q (Quarterly) and N-CSR (Annual) which contain the mutual fund holdings. 

I could have used the Morningstat API but requires a paid token authenticator or webscraped with a premium subscription. I want this to start no/zero cost.  
