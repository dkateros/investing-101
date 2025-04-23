---
title:
- Investing 101 for geeks
author:
- Dimitris Kateros
- George Andrianakis
theme:
- Copenhagen
colortheme:
- metropolis
---

# Who we are

## @dkateros

- *1999-2009* Electrical & Computer Engineering, Diploma, PhD, *National Technical University of Athens*

- *2010-today* Software Engineer, Architect, Team Leader, Chapter Leader, *Interamerican*

## @geoand86

- *2003-2008*, Electrical & Computer Engineering, Diploma, Msc, *National Technical University of Athens*

- *2008-2010*, Computing Systems, Diploma, Msc, *University of Athens*

- Today, Senior Principal Software Engineer, *Red Hat*

# Who we are not (DISCLAIMER)

**We are not a qualified licensed investment advisors**.

All information found here is for informational, entertainment or educational purposes only and should not be construed as personal investment advice.

Conduct your own research, or consult a licensed financial advisor before making any investment decisions.

Also: **Past performance is not a guarantee of future results**.

# Math

```
Study mathematics to understand physics.

Study physics to understand chemistry.

Study chemistry to understand biology.

Study biology to understand **psychology**.

Study psychology to understand **economics**.

...
```

# Income

Increasing your income is the most reliable way to obtain wealth.

Increased income leads to progressively increasing taxes.

(Greece) Salaried employees gross income takes multiple hits, especially after \texteuro 40K gross.

Social security (13%), taxes (44%), employer social security (22%).

For every \texteuro 122 spent by an employer, the employee receives *100(1-0.13)(1-0.44)=\texteuro49* net. This is just **~40%** of the total cost.

Also, employers typically budget about 6% a year for the severance package on top of that.

# Increasing net income

Tax deferred insurance policies

- 0% tax at the moment of investment.
- Little control over investments.
- Fees.
- Account taxed on maturity at a much lower rate.
- Still, for a 10-15 year horizon this can be advantageous.

Getting paid as a company and not as an individual

- Requires an annual income near 6 digits.
- There are some extra expenses.
- (Greece) Easier than it used to be (IKE is a popular entity type).
- (Greece) Lower taxation.
- Ability to subtract (potentially significant) expenses from taxable income.

# Stumbling on investing

I was investing on a tax deferred insurance policy. And I got a statement once a year.

At some point I became curious about how I can track the value of the underlying investment on my own.

I figured out it was a mutual fund that packaged, among other assets, something called **IWDA, an ETF**.

That was around 2018. At the time, *ourwallet.gr* seemed to be the most convincing take on ETFs in the Greek blogosphere.

As the typical numbers/optimization fixated engineering type, I was intrigued.

# Index investing with ETFs

*"The winning formula for success in investing is owning the entire stock market through an index fund, and then doing nothing. Just stay the course."* John C. Bogle

ETFs may be the easiest and cheapest way to invest on an index. Things to take note of:

- *Fees*. Amount that we pay the ETF provider each year as a percentage of the value of our holdings with the ETF.
- *Assets under management*. How much money does the ETF manage.
- *Index replication method*. I prefer physical. Synthetic methods might come with lower fees but with increased tracking error.
- *Past performance* (which is not a guarantee of future results). 
- *Distribution policy*. Distributing vs accumulating.
- *Hedging*. Insurance against currency risk.
- *Taxation* of capital gains.

# Investing vs Speculating

*"Our favorite holding period is forever."* Warren Buffett

*"Time in the market beats timing the market."* Kenneth Fischer

As a personal preference, we do not want to become traders. This seems to be a full-time job with its own learning curve.

Our idea of investing is:

1. Choose asset classes and future strategy.
2. Choose investment vehicles.
3. Invest excess income on a regular basis.
4. Rebalance between asset classes.
5. Revise strategy.

# Stock ETFs

Noteable indexes include:

- S&P 500
- MSCI World
- FTSE All World

Weighting strategies

Replication strategies

Evaluation metrics

- P/E ratio. P stands for stock price, E stands for stock earnings.
- EV/EBITDA ratio. More sophisticated than P/E but harder to get good data for.
- P/B ratio. P stands for total capitalization. B stands for booking (assets-liablities).
- Sharpe ratio. Return per point of volatility.
- ...

# S&P 500 charts

\includegraphics[height=0.9\textheight]{sp500-pe-pb.png}

# Bond ETFs

Noteable indexes include:

- FTSE World Government Bond
- Bloomberg Global Aggregate Bond
- Bloomberg US Aggregate Bond

Evaluation metrics

- Effective yield to maturity. Average bond yield.
- Effective maturity period. Average bond maturity length.
- Effective duration. The %ETF value increase/decrease for each point of decrease/increase in interest rates.
- Effective rating. Average bond rating.

Note that while hedging for stock ETFs makes little sense, for bond ETFs it is actually preferable.

# Money Market ETFs

A money market fund will typically offer a growth rate that is close to the central bank interest rates.

These can be great for practically getting interest for cash.

There is a very popular one that tracks the EURO short term rate (in practice, the ECB rate). 

Note that the ECB rate has been 2+ percent since 2023, but it was zero or negative between 2016 and 2022.

Overall a decent replacement for the concept of a HYSA.

# Asset classes diversification

- Large cap stock (developed)
- Large cap stock (emerging)
- Mid cap stock (developed)
- Aggregate bonds (developed)
- Government bonds (developed)

A typical portfolio will contain 2 or 3 of the above asset classes. The main idea is that different asset classes improve diversification [^1] and we can benefit from rebalancing. For example, if we have decided on a 30/70 bond/stock allocation and bonds underperform, we will have to sell stocks to buy bonds. This seems counterintuitive, but reflects the correct investing mindset: 

*Sell overperforming assets to buy underperforming assets*.

[^1]: Negative correlation between asset classes is not a given.

# Retirement

The stock/bond allocation can follow a rule of thumb like the following:

***N-age per cent stocks***

Where *N* can be somewhere between 100 (conservative) and 120 (aggressive). This approach is meant to smoothen the volatility of the portfolio (and improve sleep) at the cost of long term growth.

As we approach retirement age, we might need more stability and income than growth. A standard way to achieve this is through a "bond ladder". Turns out that a bond ETF is just that.

Even using *N=120*, by 60 years old we will have 40% bonds creating predictable income through dividends.

# Buying ETFs

Choose a broker that is reliable and cheap (fortunately, there are plenty available). Register with them. The process is similar with registering for a bank account.

Have a look at the broker's fees. 0.1-1% per trade is reasonable (including stock exchange fees).

Transfer money from your bank to the broker.

Buy UCITS ETFs domiciled in EU countries and traded in EU stock exchanges with low fees (e.g. the Germany exchanges using XETRA).

(Greece) Such ETFs incur zero capital gains tax (currently).

Test the reverse process to get comfortable with it. Sell an ETF, transfer the money back to your bank.

Treat investing and rebalancing as automated workflows. Leave emotions out of it and let time do it's thing.

# Psychology

As a child, I was exposed to the savings account narrative.

As a young adult, I experienced the effects of the greek stock market rise and fall in 1999.

It took quite some time to trust these sort of investment vehicles and brokers.

In February 2020 I witnessed first hand the market crash due to COVID. Fortunately, I was invested via Interamerican at the time and could not panic sell.

I still keep significant portions of my assets as cash or cash equivalents.

As a parent, I intend to teach my children to exercise critical thought about their finances and be aware of psychological biases.

# Questions

Be curious, not judgemental (Ted Lasso)

- Stock index replicating ETFs usually weigh on stock capitalization. Isn't this effectively the opposite of the sell overperforming assets to buy underperforming assets strategy?

- Does the existence of index stock ETFs inflate the value of the stocks that comprise the index?

- Does the value of an ETF reflect market sentiment about the ETF or does it translate exactly to the market value of the underlying assets?

# References

| Resource | Description |
| ---------| ----------- |
| justetf.com | ETF search and info |
| curvo.eu/backtest/en | Portfolio backtesting |
| www.investopedia.com | Investing education |
| ourwallet.gr | Greek blogosphere OG (probably) |
| /r/eupersonalfinance | Investing from the EU pov |

# Thank you

\includegraphics[height=0.9\textheight]{anyquestions.jpg}