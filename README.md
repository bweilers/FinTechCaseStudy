# Kabbage Inc. - FinTech Case Study
</br>

## Overview
### Origin
Kabbage Inc. is a FinTech company that launched in 2009 in Atlanta, GA, and founded by Rob Frohwein and Kathryn Patralia (0). In 2011 Kabbage began operations in the lending space providing funding to both small business and consumers through its automated platform. Previously, the customers Kabbage serves would typically seek financing to alleviate cash flow challenges through traditional lenders (i.e., banks). It would take these customers multiple days simply to determine their eligibility for financing through traditional lenders. With the help of Kabbage Inc., small business and individual consumers are now able hear back about their eligibility within minutes, and receive funds within ____time. According to Biz2X, the size of the digital lending market as of 2022 is “at least $743 billion” (001).
</br>
An analysis of Google search trends over the past two year indicates that Kabbage Inc. remains on of the most relavant digital lending companies.
### Package Requirments & Versions
`pip install x` where x is the below listed packages
* `python == 3.9.12` 
* `pandas == 1.3.5+`
* `pytrends: 4.8.0`

`
kw_list = ['kabbage', 'c2fo', 'fundbox', 'lendingkart', 'prospa']
pytrends.build_payload(kw_list, timeframe='2020-01-01 2022-09-21')
interest_over_time_df = pytrends.interest_over_time()
interest_over_time_df
`
<p style="text-align:center;"><img src="Screenshot 2022-09-24 101432.png" width="500" height="200"/></p>


<<insert image of results>>

Since its founding, Kabbage Inc has gone through a full arch; from disruptor startup to established leader in the newly formed digital ending space, all the way to entrenched company under the umbrella of traditional finance. In 2020, Kabbage Inc. was acquired by American Express, which helped it secure this position.   According to an analysis of Google Trends, Kabbage has been one of the most searched companies over the past two years <<insert data and screen shot of restuls if necessary>>/ 
### Technologies 
To help its customers determine eligibility for financing Kabbage Inc. uses a variety of metrics in their data analytics and machine learning models. One such metric that they elaborate on in public documents on their website is the small business revenue index (2). With very little public data to track the ongoing financial performance of small businesses on a daily basis,  Kabbage was able to create the “Small Business Revenue Index” through live data connections with their customers to analyze revenue trends (2). Their approach was to establish the median revenue growth for US small businesses, assess an applying company’s performance against this and other metrics, then use their proprietary algorithm to determine if an applicant is credit worthy.
### Metrics to measure success
`	From: https://wealthybyte.com/kabbage-business-model-how-does-kabbage-make-money/
	“””Kabbage earns profit through all three products, which are SME loans, Kabbage Platform, and personal loans. This company has not made its detailed financials public. However, this company has made $100 million in revenues during 2019. The estimated annual revenue of this fintech firm is more than $46 million. 
This company charges 1.5% to 12% rates on SME loans along with additional fees depending on the creditworthiness and special circumstances. It assesses the credit history of individual applicants and charges a 6.44% fixed-rate on personal loans. 
Other fees this company charges include late fees, origination fees, and a fee on returned payments for the risk it takes while lending the money. Fees charged for using the Kabbage platform are not public. Every traditional lender may pay a different fee depending on the data and technology it uses. “””
</br>


## Future of Digital Lending
### Trends
One of the trends is the digital business lending companies are becoming more and more specialized. According to FinTechLabs.com, the top 10 emerging companies in the digital lending space are Capchase, Clearco, Pipe, Nav, BlueVine, OnDeck, Camino Financial, FundBox, CAN Capital, and Kabbage in the #2 spot (3). Capchase, the number 1 company on this list, is an example of a highly specialized lending company. Capchase provides digital lending solutions to SaaS companies seeking to elevate cash flow challenges as they service business clients with large accounts that have a Total Contract Value (TCV) of high 5 to 6 figures, but that are reluctant to pay upfront. According to Danny Crichton with Tech Crunch’s podcast, “Capchase is taking advantage of a new market [...] there are now hundreds if not thousands of SaaS companies making revenues. And one of the most common challenges with most SaaS companies is, if companies sign multi- month, multi- year purchase agreements, they say ‘We’re going to spend 2,000 a month for the next two years.’ That’s $48,000 across the total contract, what’s known as the total contract volume or TCV. The challeng is you can’t get that money up front. And Startups want money up front to pay for payroll, cashflow, growth, etc.” (4) Previously startups with cashflow challenges would have the option of getting venture debt. But the solution provided by Capchase is making the process of acquiring financing to overcome cashflow challenges much more frictionless for burgeoning startups. 	
Digital lending is also expanding into emerging markets. One example is within the quickly rising market of India, LendingKart has already established itself as a top contender. 
An additional trend of note is that digital lending is expanding into the Decentralized Finance (DeFi) space. To start, companies seeking to operate within the decentralized Web3.0 space have access to short term loans through DeFi companies like Aave, Maker, and Curve Finance. While these companies do not specialize in business loans, emerging companies like SALT Lending are starting to cater their loan service to businesses (7) by allowing borrowers to provide crypto currency as collateral and forgo traditional credit checks.
						
### Advice
In order to remain relevant within the digital lending space, Kabbage should seek to add metrics available from publicly available blockchains to their loan determination algorithms. Including measurable aspects of blockchains and crypto currency metrics in their loan determination algorithms would allow Kabbage to enter the growing DeFi pace. The technologies appropriate for this solution would be decentrialized finance on the blockchain. And Cardano identity for business. Much like Ethopia has given identity tokens to students to track academic progress, a FinTech company could give such identifier to businesses to help them establish credit through a decentralized platrofmr and apply for credit as needed.
Currently Kabbage’s strategy remains unchanged. And while this may keep in on a low risk path, if Kabbage wants to remain on the cutting edge they should seak an area of specialization that they could fill in addition to providing a path to PPP loans. Pursuing this dual path would allow them to both mitigate risk and possibly catch a new wave when it comes. To do this they must identify a new niche to service. Possible niches could include be based on industry or size of company. 
</br>

## Sources

0) https://craft.co/kabbage
https://en.wikipedia.org/wiki/Kabbage
001)https://www.biz2x.com/how-large-is-the-small-business-lending-market-in-2022/
https://newsroom.kabbage.com/news/technology/building-the-kabbage-small-business-revenue-index/
How Kabbage analyzes data. The metrics that Kabbage uses
https://fintechlabs.com/top-28-digital-lenders-to-u-s-small-businesses/
https://www.youtube.com/watch?v=WxPBx_YzXpc
https://debanked.com/2022/01/kabbage-co-founder-rob-frohwein-steps-down-from-the-company/
https://newsroom.kabbage.com/wp-content/uploads/2020/07/Kabbage-Paycheck-Protection-Program-PPP-Report.pdf
https://saltlending.com/business-loan/


