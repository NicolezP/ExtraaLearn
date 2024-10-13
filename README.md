# ExtraaLearn
*A Supervised Binary Classification Project*

The EdTech industry has experienced tremendous growth over the past decade, with forecasts predicting the online education market to reach $286.62 billion by 2023. This expansion has only accelerated in recent years, especially during the COVID-19 pandemic, as online education became the preferred choice due to its flexibility, personalized learning, and accessibility. However, with this surge in demand, many new companies have emerged, creating fierce competition in the market.
<br><br>
## Goal 
**ExtraaLearn**, a startup Edtech company offering online education, faces a key challenge: identifying which of its many leads are most likely to convert into paying customers.
Our goal is to build a machine learning model that:
* Predicts lead conversion likelihood
* Reveals key factors driving conversions
* Profiles high-potential leads for targeted resource allocation
This approach will help ExtraaLearn focus efforts on the leads that matter most, optimizing growth in a highly competitive market.

## Process
followed a systematic approach to build and refine models for predicting lead conversion:
1. **Data Exploration**: We began by cleaning and analyzing the dataset to understand key features and handle missing values.
2. **Feature Engineering**: Dummy variables were created for categorical data, and the dataset was split into training and testing sets.
3. **Modeling**: We built and evaluated a Decision Tree model, followed by tuning it using GridSearchCV for better performance. A Random Forest model was also created and optimized similarly.
4. **Evaluation**: Both models were assessed using metrics like precision and recall, with a focus on precision to minimize false positives.
5. **Insights**: Key factors such as time spent on website and first interaction were identified as the most influential in predicting conversions.

## Insights
**Tuned Random Forest** emerged as the top performer in terms of **precision**, crucial for reducing false positives in lead conversion

**Top Influential Features:**
1. **Time spent on website** – Longer engagement indicates a higher likelihood of conversion.
2. **First interaction with website** – Leads that initially interact through the website show higher conversion rates.
3. **Profile completion** – Fully completed profiles significantly correlate with conversion.
4. **Page views per visit** – Higher engagement correlates with conversion probability.
5. **Age** – Certain age groups (35-55 years old) show a higher likelihood of conversion.

### Actionable Recommendations:
1. **Focus on Website Engagement**: Invest in online marketing and website optimization, as initial interactions via the website have the highest conversion rate.
2. **Improve Usability**: Leads who spend more time on the site are more likely to convert, suggesting that improving navigation could make it easier for genuinely interested leads to find relevant information.
3. **Encourage Profile Completion**: Offering incentives (e.g., a free trial) for completing profiles could boost conversions and give ExtraaLearn’s sales team better insights for lead profiling.
4. **Telemarketing Insights**: The model shows that telemarketing efforts can enhance conversion, especially for leads who have recently interacted with ExtraaLearn via phone.
