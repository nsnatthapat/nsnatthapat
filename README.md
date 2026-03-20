# 👋 Hi! I’m Nat (Natthapat)
💼 Analytics Engineer | Decision Systems | BI Developor

🌏 Based in Seattle, WA 

## 💡 About Me

I'm a data-driven problem solver with a background in Informatics: Data Science and a Master's in Analytics. I thrive on translating complex business questions into actionable data solutions, leveraging my expertise in causal inference and decision science to drive impactful outcomes. With a passion for building scalable analytics pipelines and fostering a metric-driven mindset, I am dedicated to empowering teams to make informed decisions through data. Based in Seattle, I am always eager to connect with fellow data enthusiasts and professionals in the field.

**🤝 Connect with me** : 📫 [LinkedIn](https://www.linkedin.com/in/natthapat-sakulborrirug/) | ✉️ nsnatthapat@gmail.com


# 📊 Featured Professional Case Studies 

## Enterprise Performance Management Implementation  
*Professional Case Study*

Implemented an enterprise performance management (EPM) solution using Board to support financial planning and reporting across multiple departments.

**Context**  
The organization required a centralized platform for budgeting, forecasting, and operational reporting to replace fragmented spreadsheet-based workflows.

**Contribution**
- Designed multidimensional data models supporting finance and operational reporting
- Built dashboards and planning workflows for budgeting and performance tracking
- Integrated SQL-based data sources and flat files into Board cubes
- Supported stakeholders in Finance and PMO teams through reporting and analysis needs

**Tools**  
Board EPM • SQL • Excel • Data Modeling • OLAP Cubes

**Outcome**
Enabled centralized planning and reporting workflows, reducing reliance on manual spreadsheet consolidation and improving visibility into operational performance.

---

## Oracle OTBI Reporting Framework  
*Professional Case Study*

Developed operational reporting solutions using Oracle Transactional Business Intelligence (OTBI) to support business monitoring and decision-making.

**Context**  
Business teams required improved access to operational metrics from Oracle systems without relying on manual reporting or IT-managed data extracts.

**Contribution**
- Designed and developed OTBI reports for operational and financial monitoring
- Built custom analyses combining multiple subject areas within Oracle data models
- Collaborated with stakeholders to translate business questions into structured reporting logic
- Documented report logic and trained users on interpreting key metrics

**Tools**  
Oracle OTBI • SQL • Oracle ERP Data Models

**Outcome**
Enabled business teams to access self-service reporting directly within the Oracle ecosystem, reducing turnaround time for operational insights.


# ✏️ Portfolio 

## Marketing Measurement 
*Causal Inference, Counterfactual, Channel Attribution and ROI Analysis*
Project Link | Project Description
--- | ---
[Multi-Channel Online Ad Effectiveness Analysis - The Criterion Channel](https://github.com/nsnatthapat/criterion-channel-online-ad-campaign-effectiveness-roi) | Analyzed a 1.2M-user randomized experiment across five ad channels (Facebook, Twitter, Instagram, YouTube, Letterboxd) to measure incremental subscription lift and channel-level ROI. Found ~348% relative lift overall, with Twitter as the only statistically reliable positive-ROI channel and Instagram as a promising but underpowered opportunity.
[Online Ad Campaign Effectiveness Analysis - Rocket Fuel](https://github.com/nsnatthapat/rocket-fuel-ad-campaign-effectiveness-roi) | Evaluated a 96/4 treatment-control ad experiment using unadjusted lift, covariate-adjusted OLS, IPW, and Double Machine Learning. Found ~42% relative conversion lift and a treatment-only ROI of 37.7%, with actionable segmentation by impression frequency, day of week, and hour of day.
[Geo-Randomized Paid Search Effectiveness Analysis - eBay](https://github.com/nsnatthapat/eBay-paid-search-DMA-causal-analysis-roi) | Used a DMA-level ad suspension experiment and two-way fixed effects Difference-in-Differences to contrast naïve attribution (+272% ROI) against the true causal return (−60% ROI), quantifying how organic substitution causes standard attribution to overstate paid search value by over 330 percentage points.
[Multi-Channel Campaign Attribution & ROI Analysis - Patagonia](https://github.com/nsnatthapat/patagonia-ad-analysis) | Compared last-touch, first-touch, and linear attribution against intent-to-treat causal estimation across five channels (email, YouTube, Instagram, Google Search, contextual display) on 2M customer records. Found naive models overstate marketing impact ~4x, with contextual display flipping from the top-ranked channel (naive) to negative ROI (incremental).
[Discount Coupon Email Effectiveness, Targetting Method, and ROI Analysis  - Artea](https://github.com/nsnatthapat/artea-coupon-effectiveness) | Ran A/B test analysis on a 5,000-customer coupon experiment and built a fully interacted heterogeneous treatment effects model to identify high-lift segments (cart holders, Instagram-acquired users). Surfaced an algorithmic fairness issue: the targeting model significantly under-routes coupons to minority customers via acquisition channel as a proxy variable.
[Customer Response Ranking and Marginal ROI Analysis - Electronic Arts](https://github.com/nsnatthapat/ad-variety-roi-analysis-and-impression-ranking) | Trained CART and XGBoost models to rank mobile ad impressions by predicted CTR, finding that historical user CTR dominates in-session ad variety as a targeting signal. Showed targeted buying of top-ranked impressions nearly doubles ROI (351% → 682%) and derived the optimal mixed-channel budget allocation using a marginal ROI crossover framework.
[Cross-Brand Customer ID consolidation measurement on Marketing ROI: A Customer Data Platform Analysis - Amperity](https://github.com/nsnatthapat/amperity-customer-id-consolidation) | Simulated fragmented vs. resolved customer identity across a multi-brand retailer and quantified downstream distortion: 51% customer count overstatement, high-value customer share halved, and a 33-point ROI gap between realized performance and what the fragmented system self-reported — illustrating how poor identity quality creates both targeting errors and false measurement confidence.
[Display Advertising Effectiveness A/B Test - UberEats](https://github.com/nsnatthapat/display-advertising-effectiveness-experiment-for-ubereats) | Compared ITT and ATT estimators across 576K users to measure display ad impact, finding revenue lift concentrated in non-American markets and dormant users, while active users showed no significant response. Demonstrated that a naive within-treatment comparison inflates the estimated lift by ~30x due to selection bias in ad exposure.
[Geo-Randomized Ad Removal A/B Test - Starbucks](https://github.com/nsnatthapat/Geo-Randomized-Ad-Removal-A-B-Test---Starbucks) | Applied two-way fixed effects DiD on a 200-market panel to estimate the causal impact of Google Maps local search ads, finding a statistically significant lift of ~9.6 units per hour per store (~7.4% relative lift). Validated parallel trends via event study and pre-period regression before interpreting the estimate as causal.





## Consumer Analytics & Market Research
Project Link | Project Description
--- | ---
[Retail Market Research: Consumer Segmentation with PCA](https://github.com/nsnatthapat/consumer-segmentation-with-pca) | PApplied PCA to a retail attitude survey, reducing five correlated preference items into two interpretable dimensions — service orientation and price sensitivity — that together explain 90.5% of variance. Mapped respondents into four actionable customer segments to inform discount vs. full-service retail positioning decisions.


## AI & LLM Systems
Project Link | Project Description
--- | ---
[Market Research: Synthetic Customer Ratings via LLM - Wine Reviews](https://github.com/nsnatthapat/llm-for-market-research-wine-reviews) | Benchmarked zero-shot, few-shot, and chain-of-thought prompting strategies for LLM-based rating of wine reviews against human critic scores. Zero-shot (MAE 1.71) outperformed all engineered variants, while inter-run variance analysis (7-point spread across 20 identical calls) revealed non-determinism as the primary production risk for LLM annotation pipelines.
[LLM Fine-Tuning for Customer Review Triage - Amazon Reviews](https://github.com/nsnatthapat/llm-fine-tuning-for-review-triage) | Fine-tuned GPT-4.1-mini on 67 labeled magazine subscription reviews to produce structured JSON triage outputs (complaint tag, escalation flag, suggested action). Fine-tuning improved complaint tag accuracy from 27.3% to 63.6% and JSON validity to 100%, demonstrating that task-specific fine-tuning outperforms prompt engineering for schema-constrained classification.
[RAG System for Academic Program Office - UW MSBA](https://github.com/nsnatthapat/msba-office-rag-system) | Built and evaluated a retrieval-augmented generation system over 21 MSBA program documents (syllabi, policies, handbooks) for student support use cases. RAG scored 40/40 vs. 18/40 for the plain LLM baseline across factual accuracy, specificity, relevance, and hallucination control — with the largest gains on high-stakes policy and deadline queries.














