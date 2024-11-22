# Capstone-Project-Funding-in-Startups

### Observations:
1.  There are total 49436 unique permalink.
2.  There are 49350 unique names of the startup in the dataset.
3.  There are 753 unique market listed in the dataset.
4.  There are 1089 unique regions mentioned in the dataset.
5.  The dataset needs data cleaning as we can see the there are hyphens(garbage value) present in the columns.

### Insights: 

1.  Categories like Biotechnology, Mobile, Clean Technology, Software often top funding charts by Total funding, highlighting investor focus on technology-driven industries. The most funding is done for Biotechnology about 70 Billion Dollars.
2.  Categories like Trading, Payments, Communities, college, students, social media often top funding charts by Average funding. The most avg funding is done for Trading & Payments about 3.5 Billion dollars.
3.  Markets such as Biotechnology, Mobile, Clean Technology, Software are among the most funded, reflecting their critical importance during recent economic trends. Biotechnology market has funded the most about 73 Billion dollars.
4.  The most striking insight is the dramatic surge in startup formation and funding post-1980s, with the peak funding reaching approximately 10 billion dollars (10^10) for top performers, particularly in Mobile and Biotechnology sectors, while the majority of startups receive funding between 1 million dollars(10^6) and 100 million dollars(10^8), demonstrating a significant expansion in the startup ecosystem during this four-decade period (1980-2020).
5.  Startup funding experienced a dramatic surge around 2000-2005, reaching a peak of approximately 50 billion, followed by significant volatility, aligning with the dot-com bubble and subsequent recovery.
6.  Prior to the late 1980s, startup funding was minimal, indicating a significant shift in the investment landscape over the past few decades.
7.  Startup funding exhibits a strong correlation with economic cycles, peaking during Recovery periods (approximately 55 billion) and reaching its lowest point during Recession periods (25 billion).
8.  Before 1990, funding activity across all economic cycles was minimal, highlighting the significant growth and volatility of the startup funding landscape in recent decades.
9.  The distribution of funding velocity is highly skewed, with the majority of startups (approximately 700,000) having near-zero funding velocity.
10.  Only a small fraction of startups achieve rapid funding acceleration, with the maximum funding velocity reaching around 7x10^8 USD per year.
11.  Average funding for Niche segments: 9,399,979.49
12.  Average funding for Generalist segments: 13,183,965.45
13.  While both niche and generalist segments have similar median funding levels, generalist segments exhibit a wider range of funding amounts, with some outliers reaching significantly higher values (up to 30 billion USD).
14.  Niche segments tend to have a more concentrated funding distribution, with fewer high-value outliers and a maximum funding level around 1 billion USD.
15.  Startup survival probability decreases significantly after each funding round, with a sharp drop after the first round and continuing decline until around the fifth round.
16.  The majority of startups fail to secure continued funding beyond the early stages, with only a small fraction surviving past 10 funding rounds.
17.  The SF Bay Area dominates global startup funding, with approximately 140 billion USD, significantly outpacing other major tech hubs like New York City and Boston.
18.  Geographical concentration is evident, with Silicon Valley and New York City attracting a disproportionate share of global startup funding.
19.  Biotechnology market has received the highest number of funding rounds, with over 7,500 rounds, followed by Software with over 7,000 rounds, as Investors are more interested in these markets.
20.  Venture funding dominates with a total funding of approximately 3.7 billion, significantly surpassing other funding types like debt financing, seed funding, grants, and angel funding.
21.  Venture funding dominates in the top 5 markets, particularly in Biotechnology, with a total funding of approximately 1.1 billion, followed by Software with around 0.9 billion.
22.  The distribution is highly skewed, with a large peak at 0, meaning a significant number of startups have no equity financing at all and are completely debt-financed. There is a wide range of equity-to-debt ratios, from 0 to over 7 million, suggesting a diverse mix of financing strategies across the startups. The median and 75th percentile being at 0 indicate that more than half the startups have very low or no equity financing. This implies that the startup funding landscape is dominated by debt-heavy financing structures, with a smaller number of startups relying more heavily on equity.
23.  The analysis shows that, a relatively small portion of startups have a higher Round B funding compared to Round A, which indicate lower investor confidence, a cautious funding strategy or difficulties in getting to Series B.
24.  The scatter plot reveals a correlation between funding and age. Startups with higher funding, often exceeding 10 million, tend to be older, with some surpassing 100 years. However, there's a cluster of younger startups, less than 10 years old, securing funding below $10 million. This suggests that while funding can contribute to longevity, it's not the sole determinant.
25.  The scatter plot reveals a positive correlation between funding velocity and total funding. Startups with higher funding velocities, exceeding 100 million USD per year, tend to secure more total funding, often surpassing 10 billion USD. However, startups with lower funding velocities, below 100 million USD per year, and total funding below 10 billion USD also exist. This suggests that while a higher funding velocity can contribute to increased total funding, other factors like market demand and team experience also influence a startup's success. Additionally, economic cycles impact funding velocity and total funding, with expansion periods generally leading to higher values.

### Statistical Testing:
1.  A low p-value (< 0.05) indicates significant differences in funding between US and non-US startups.
2.  No significant difference in funding between Software and E-Commerce markets.
3.  No significant difference in funding between Urban and Rural regions.
4.  Significant difference in total funding between venture and debt financing.
5.  No significant differences in funding between economic cycles.
6.  No significant difference in funding between Niche and Generalist segments.

### Recommendations:

### 1. Portfolio Diversification:

**Recommendation:**  Diversify investment portfolios across multiple high-potential sectors, such as Biotechnology, Mobile, and Software. These sectors have consistently received the highest funding levels, indicating strong investor interest and growth potential.

**Rationale:**  Diversifying across sectors helps mitigate risk and capture opportunities in fast-moving, technology-driven industries.

### 2. Geographic Expansion:

**Recommendation:**  Explore investment opportunities outside the traditional startup hubs of the SF Bay Area and New York City. Consider incentivizing entrepreneurship in other regions to identify and support promising startups in emerging markets.

**Rationale:**  The data shows a significant funding concentration in Silicon Valley and NYC. Expanding into other regions can provide access to untapped talent and innovative ideas, potentially yielding higher returns.

### 3. Targeted Funding Strategies:

**Recommendation:**  Develop tailored programs and resources to help startups navigate the critical early funding rounds. Focus on supporting startups through the sharp drop-off in survival rates after the first few rounds.

**Rationale:**  The Kaplan-Meier Survival Curve highlights the challenges startups face in securing continued funding, especially after the initial rounds. Targeted interventions can improve sustainability and increase the likelihood of successful exits.

### 4. Niche Segment Support:

**Recommendation:**  Allocate a portion of investment capital to support niche/specialized startups, as they appear to receive lower funding compared to generalist segments, despite potentially filling important market gaps.

**Rationale:**  Niche startups may offer unique value propositions and opportunities for differentiation. Providing tailored support and funding can help these companies thrive and diversify the investment portfolio.

### 5. Economic Cycle Responsiveness:

**Recommendation:**  Closely monitor economic cycles and be prepared to adjust investment strategies accordingly. Allocate more resources during recovery periods when funding tends to surge, and maintain a more conservative approach during recessions.

**Rationale:**  The data shows a strong correlation between funding levels and economic cycles, with recovery periods experiencing the highest funding peaks. Adaptability to these trends can improve investment timing and returns.

### 6. Financing Structure Analysis:

**Recommendation:**  Investigate ways to encourage a more balanced debt-to-equity financing structure among startups, as the current landscape appears heavily skewed towards debt-heavy models.

**Rationale:**  The insights suggest the startup funding landscape is dominated by debt-heavy financing, which may impact long-term sustainability and growth. Identifying optimal financing structures can lead to better-capitalized and resilient startups.
### Business Problem:

Analyzing the funding landscape of startups can provide valuable insights to guide strategic decision-making for aspiring entrepreneurs and investors in the dynamic startup ecosystem. This study aims to uncover trends and patterns in startup funding, including the distribution of funding across different categories, markets, and regions, as well as the correlation between a startup's funding characteristics and its funding success. By examining factors such as funding rounds, funding types, geographical locations, and the impact of economic conditions, this project seeks to offer actionable recommendations to optimize the funding journey for startups and identify sectors with higher investment potential.
  
### Dataset:

### Dataset Description:

| **Column**           | **Description**                                |
|-----------------------|-----------------------------------------------|
| **permalink**         | Static hyperlink for the startup on Crunchbase. |
| **name**              | Name of the startup.                          |
| **homepage_url**      | Website address of the startup.               |
| **category_list**     | Categories the startups fall under.           |
| **market**            | Market the startup caters to.                 |
| **funding_total_usd** | Total funding received (in USD).              |
| **status**            | Current operating status.                     |
| **country_code**      | Country of origin.                            |
| **state_code**        | State of origin.                              |
| **region**            | Region of origin.                             |
| **city**              | City of origin.                               |
| **funding_rounds**    | Total rounds of funding.                      |
| **founded_at**        | Date of founding.                             |
| **founded_month**     | Month of founding.                            |
| **founded_quarter**   | Quarter of founding.                          |
| **founded_year**      | Year of founding.                             |
| **first_funding_at**  | Date of first funding.                        |
| **last_funding_at**   | Date of last funding.                         |
| **seed**              | Seed funding received (in USD).              |
| **venture**           | Venture funding received (in USD).           |
| **equity_crowdfunding**| Funding received by diluting equity.         |
| **undisclosed**       | Other undisclosed funding sources.            |
| **convertible_note**  | Funding received from convertible notes.      |
| **debt_financing**    | Funding received from debts.                  |
| **angel**             | Funding received from angel investors.        |
| **grant**             | Funding from grants.                          |
| **private_equity**    | Funding from private equity.                  |
| **post_ipo_equity**   | Funding from equity dilution after IPO.       |
| **post_ipo_debt**     | Funding from debts after IPO.                 |
| **secondary_market**  | Funding from secondary markets.               |
| **product_crowdfunding** | Funding from crowdfunding.                 |
| **round_A**           | Round A funding.                              |
| **round_B**           | Round B funding.                              |
| **round_C**           | Round C funding.                              |
| **round_D**           | Round D funding.                              |
| **round_E**           | Round E funding.                              |
| **round_F**           | Round F funding.                              |





