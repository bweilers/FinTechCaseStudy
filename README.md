# Kabbage Inc. - FinTech Case Study

## Overview
### Origin, Founders, Investors

Kabbage Inc. is a FinTech company that launched in 2009 in Atlanta, GA, and founded by Rob Frohwein and Kathryn Patralia (Kabbage, Craft.co, n.d)<sup>1</sup>.  According to Crunbase, Kabbage Inc. has raised approximately $2.5 Billion over 16 funding rounds (Kabbage, Crunchbase.com, n.d)<sup>2</sup>. Included among the investors are large venture capital groups such as SoftBank.
<br></br>
In 2011 Kabbage began operations in the lending space providing funding to both small business and consumers through its automated platform (Wikipedia, 2022)<sup>3</sup>. Previously, the customers Kabbage serves would typically seek financing to alleviate cash flow challenges through traditional lenders (i.e., banks). It would take these customers multiple days simply to determine their eligibility for financing through traditional lenders. With the help of Kabbage Inc., small business and individual consumers are now able hear back about their eligibility within minutes, and receive funds faster. According to Biz2X, a SaaS company the helps small and medium sized financial institutions customize their online lending experience, the size of the digital lending market as of 2022 is “at least $743 billion” (How Large is the Small Business Lending Market in 2022, 2022)<sup>4</sup>.
<br></br>
Since its founding, Kabbage Inc. has gone through a full business evolution arch; from disruptor startup to established leader in the newly formed digital ending space, all the way to an entrenched company under the umbrella of traditional finance. In 2020, Kabbage Inc. was acquired by American Express, which helped it secure this position.   
## Pytrends Analysis
An analysis of Google search trends over the past two year indicates that Kabbage Inc. remains one of the most relevant digital lending companies.
### Package Requirments & Versions

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

The above results show search trends on Google (since the start of 2020):

` timeframe='2020-01-01 2022-09-21'`

The results show that among digital lending companies with uniques searchable names, Kabbage is at the top.

---
## Technology & Metrics
### Technology  
To help its customers determine eligibility for financing Kabbage Inc. uses a variety of metrics in their data analytics and machine learning models. One such metric that they elaborate on in public documents on their website is the small business revenue index (Sathish et al, 2019)<sup>5</sup>. With very little public data to track the ongoing financial performance of small businesses on a daily basis,  Kabbage was able to create the “Small Business Revenue Index” through live data connections with their customers to analyze revenue trends (Sathish et al, 2019)<sup>5</sup>. Their approach was to establish the median revenue growth for US small businesses, assess an applying company’s performance against this and other metrics, then use their proprietary algorithm to determine if an applicant is credit worthy.
### Metrics to measure success
Kabbage Inc. is a privately traded company, so much of it's inner financial metrics remain private. However, according to WealthyByte.com:
>Kabbage earns profit through all three products, which are SME loans, Kabbage Platform, and personal loans. [...] this company has made $100 million in revenues during 2019. The estimated annual revenue of this fintech firm is more than $46 million (Kabbage Business Model, n.d.)<sup>6</sup>.


</br>

---
## Future of Digital Lending
### Trends
One of the trends is the digital business lending companies are becoming more and more specialized. According to Jim Bruene, the top 10 emerging companies in the digital lending space are Capchase, Clearco, Pipe, Nav, BlueVine, OnDeck, Camino Financial, FundBox, CAN Capital, and Kabbage in the #2 spot (Bruene, 2022)<sup>7</sup>. Capchase, the number 1 company on this list, is an example of a highly specialized lending company. Capchase provides digital lending solutions to SaaS companies seeking to elevate cash flow challenges as they service business clients with large accounts that have a Total Contract Value (TCV) of high 5 to 6 figures, but that are reluctant to pay upfront. According to Danny Crichton with Tech Crunch’s podcast:
 >“Capchase is taking advantage of a new market [...] there are now hundreds if not thousands of SaaS companies making revenues. And one of the most common challenges with most SaaS companies is, if companies sign multi-month, multi-year purchase agreements, they say ‘We’re going to spend 2,000 a month for the next two years.’ That’s $48,000 across the total contract, what’s known as the total contract volume or TCV. The challenge is you can’t get that money up front. And Startups want money up front to pay for payroll, cashflow, growth, etc.” (Crichton, 2020)<sup>8</sup>. 
 
 Previously startups with cash flow challenges would have the option of getting venture debt. But the solution provided by Capchase is making the process of acquiring financing to overcome cash flow challenges much more frictionless for burgeoning startups. 
 <br></br>	
Digital lending is also expanding into emerging markets. One example is within the quickly rising market of India, LendingKart has already established itself as a top contender. 
An additional trend of note is that digital lending is expanding into the Decentralized Finance (DeFi) space. To start, companies seeking to operate within the decentralized Web3.0 space have access to short term loans through DeFi companies like Aave, Maker, and Curve Finance. While these companies do not specialize in business loans, emerging companies like SALT Lending are starting to cater their loan service to businesses by allowing borrowers to provide crypto currency as collateral and forgo traditional credit checks (Business Loan, n.d.)<sup>9</sup>.
						
### Advice
In order to remain relevant within the digital lending space, Kabbage Inc. should seek to add metrics available from publicly available blockchains to their loan determination algorithms. Including measurable aspects of blockchains and crypto currency metrics in their loan determination algorithms would allow Kabbage Inc. to enter the growing DeFi pace. The technologies appropriate for this solution would be decentralized finance on the blockchain. 
<br></br>
Currently Kabbage Inc.'s strategy remains unchanged. And while this may keep in on a low risk path, if Kabbage wants to remain on the cutting edge they should seak an area of specialization that they could fill in addition to providing a path to PPP loans. Pursuing this dual path would allow them to both mitigate risk and possibly catch a new wave when it comes. To do this they must identify a new niche to service. The ideal niche would be one where there is a an abundance of data that can be fed into their machine learning loan determination algorithms. And with more and more aspects of everyday life and business becoming connected to the internet through IoT, the more opportunities for companies to specialed there will be.
</br>

---
## Sources

1. Kabbage (n.d.), [https://craft.co/kabbage](https://craft.co/kabbage)
2. Kabbabe (n.d.), [https://www.crunchbase.com/organization/kabbage/company_financials](https://www.crunchbase.com/organization/kabbage/company_financials)
3. Kabbage (n.d.), [https://en.wikipedia.org/wiki/Kabbage](https://en.wikipedia.org/wiki/Kabbage)
4. How Large is the Small Business Lending Market in 2022? (2022), [https://www.biz2x.com/how-large-is-the-small-business-lending-market-in-2022/](https://www.biz2x.com/how-large-is-the-small-business-lending-market-in-2022/)
5. Sathish, V. et al (October 28, 2019) Building the Kabbage Small Business Revenue Index, [https://newsroom.kabbage.com/news/technology/](https://newsroom.kabbage.com/news/technology/building-the-kabbage-small-business-revenue-index/)
6. Kabbage Business Mode - How Does Kabbage Make Money? (n.d.), [https://wealthybyte.com/kabbage-business-model-how-does-kabbage-make-money/](https://wealthybyte.com/kabbage-business-model-how-does-kabbage-make-money/) 
7. Bruene, Jim (July 29, 2022). Top 33 Digital Lenders to U.S. Small Businesses (SMB) in August 2022, [https://fintechlabs.com/top-28-digital-lenders-to-u-s-small-businesses/](https://fintechlabs.com/top-28-digital-lenders-to-u-s-small-businesses/)
8. Crichton, Danny (September 4, 2020), Capchase to help cash-out SaaS., [https://www.youtube.com/watch?v=WxPBx_YzXpc](https://www.youtube.com/watch?v=WxPBx_YzXpc)
9. Business loans for entrepreneurs like you (n.d.). [https://saltlending.com/business-loan/](https://saltlending.com/business-loan/)



