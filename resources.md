## 1. A/B Testing

* [A/B Testing course (Udacity/Google)](https://www.udacity.com/course/ab-testing--ud257)
* [Tutorial: Advanced A/B testing workshop](https://eleafeit.github.io/ab_test/)
* [Trustworthy Online Experiments](https://www.amazon.com/Trustworthy-Online-Controlled-Experiments-Practical-ebook/dp/B0845Y3DJV)
* [TDS: Common Pitfalls of Running an A/B Test](https://towardsdatascience.com/online-controlled-experiment-8-common-pitfalls-and-solutions-ea4488e5a82e)
* [TDS: How to choose a sample size](https://towardsdatascience.com/how-is-sample-size-related-to-standard-error-power-confidence-level-and-effect-size-c8ee8d904d9c)
* [TDS: Peeking in A/B test](https://towardsdatascience.com/unlocking-peeking-in-ab-tests-7847b9c2f6bb)
* [Netflix Blog: Meta Analysis and Optimal Stopping](https://netflixtechblog.com/improving-experimentation-efficiency-at-netflix-with-meta-analysis-and-optimal-stopping-d8ec290ae5be)
* [Run randomness check: A/A test](https://vwo.com/blog/aa-test-before-ab-testing/) and [TDS: statistical approach to A/A test](https://towardsdatascience.com/an-a-b-test-loses-its-luster-if-a-a-tests-fail-2dd11fa6d241)
* [Lyft Engineering: Network effect](https://eng.lyft.com/experimentation-in-a-ridesharing-marketplace-b39db027a66e)
* [TDS: A/B testing in social network](https://towardsdatascience.com/ab-testing-challenges-in-social-networks-e67611c92916)
* [Paper: Network A/B Testing: From Sampling to Estimation, Gui et al.](https://hanj.cs.illinois.edu/pdf/www15_hgui.pdf)
* [Blog: Designing A/B tests in a collaboration network](https://www.unofficialgoogledatascience.com/2018/01/designing-ab-tests-in-collaboration.html)
* [Paper: A/B Testing for Social Network Services with Directed User Graphs](http://www.tkl.iis.u-tokyo.ac.jp/~kenn-chen/files/AB%20Testing%20for%20Social%20Network%20Services%20with%20Directed%20User%20Graphs.pdf)
* [Paper: Graph Cluster Randomization: Network Exposure to Multiple Universes](http://chbrown.github.io/kdd-2013-usb/kdd/p329.pdf)
* [TDS Blog: Sample Ratio Mismatch](https://towardsdatascience.com/the-essential-guide-to-sample-ratio-mismatch-for-your-a-b-tests-96a4db81d7a4)
* [Blog: Pitfalls of Multi-arm Experiments](https://blog.statsig.com/pitfalls-of-multi-arm-experiments-445c81ae75d)
* [Udemy Course: 
Bayesian Machine Learning in Python: A/B Testing](https://aetna-abc.udemy.com/course/bayesian-machine-learning-in-python-ab-testing/learn/lecture/21793938?start=15#overview)

## 2. Quasi-Experiment and Observational Study

* General:
  * [Beyond A/B Testing: Primer on Causal Inference](https://towardsdatascience.com/beyond-a-b-testing-primer-on-causal-inference-d8e462d90a0b)
  * [Causal Inference: What, Why, and How](https://towardsdatascience.com/causal-inference-what-why-and-how-d7336b0081ec)
* Difference in difference:
  * [Airbnb Blog: Difference in difference](https://medium.com/airbnb-engineering/experimentation-measurement-for-search-engine-optimization-b64136629760)
  * [Tutorial: Causal Inference using Difference in Differences, Causal Impact, and Synthetic Control](https://towardsdatascience.com/causal-inference-using-difference-in-differences-causal-impact-and-synthetic-control-f8639c408268)
  * [Causal Inference in Data Science: A/B Testing and the need for Marginal Structural Modeling](https://towardsdatascience.com/causal-inference-in-data-science-a-b-testing-and-the-need-for-marginal-structural-modeling-b9ab299681bb)
  * [Causal Inference in Data Science: A/B Testing & Randomized Trials with Covariate Adjustment](https://towardsdatascience.com/causal-inference-in-data-science-a-b-testing-randomized-trials-with-covariate-adjustment-f5a24bd023b3)
* Uplift Model
  * [TDS Blog: Introduction to Uplift model](https://towardsdatascience.com/a-quick-uplift-modeling-introduction-6e14de32bfe0)
  * [Blog: Enterprise Causal Inference: Beyond Churn Modeling](https://medium.com/data-from-the-trenches/enterprise-causal-inference-beyond-churn-modeling-78a13a431501)
  * [Uplift Modeling](https://towardsdatascience.com/uplift-modeling-e38f96b1ef60)
  * [Article: How uplift modeling helped Obama’s campaign — and can aid marketers](https://www.predictiveanalyticsworld.com/machinelearningtimes/how-uplift-modeling-helped-obamas-campaign-and-can-aid-marketers/2613/)
  * [Blog: Causal Machine Learning: Individualized Treatment Effects and Uplift Modeling](https://johaupt.github.io/causal%20machine%20learning/Uplift_ITE_summary) 
* Regression Discontinuity (RDD):
  * [TDS Blog: An Introduction to Regression Discontinuity Design](https://towardsdatascience.com/an-introduction-to-regression-discontinuity-design-f55075079def) 
* Instrument Variables:
  * [Roblox Tech Blog: Causal Inference Using Instrumental Variables](https://robloxtechblog.com/causal-inference-using-instrumental-variables-580272d9ddbd)
  * [Tutorial: Machine Learning Meets Instrumental Variables](https://medium.com/teconomics-blog/machine-learning-meets-instrumental-variables-c8eecf5cec95) 
  * [Regression Discontinuity Design: The Crown Jewel of Causal Inference](https://towardsdatascience.com/the-crown-jewel-of-causal-inference-regression-discontinuity-design-rdd-bad37a68e786)
  * [Synthetic Instrumental Variables](https://towardsdatascience.com/synthetic-instrumental-variables-968b12f68772)
* Synthetic Control:
  * [Tutorial: Causal Inference Using Synthetic Control: The Ultimate Guide](https://towardsdatascience.com/causal-inference-using-synthetic-control-the-ultimate-guide-a622ad5cf827) 
* Switch-backs:
  * [DoorDash tech blog: Switchback Tests and Randomized Experimentation Under Network Effects at DoorDash](https://medium.com/@DoorDash/switchback-tests-and-randomized-experimentation-under-network-effects-at-doordash-f1d938ab7c2a) 
* Local Average Treatment Effect (LATE)
* Propensity Score Matching:
  * [Targeted Maximum Likelihood (TMLE) for Causal Inference](https://towardsdatascience.com/targeted-maximum-likelihood-tmle-for-causal-inference-1be88542a749)
  * [Causal Inference in Data Science: Conditional Independence via Propensity Score Adjustment](https://towardsdatascience.com/causal-inference-in-data-science-conditional-independence-via-propensity-score-adjustment-bbe6d70e2a5)
* With temporal elements:
  * [G-computation in Causal Inference](https://towardsdatascience.com/g-computation-in-causal-inference-774099da3631)
* Text-based/NLP:
  * [Text-based Causal Inference](https://towardsdatascience.com/text-based-causal-inference-86e640efb2af) 
  * [Improving NLP with Causality](https://towardsdatascience.com/improving-nlp-with-causality-2dec1fa90b74)

## 3. Natural Experiments

* Example: [Does compulsory school attendance affect schooling and earnings?](https://www.jstor.org/stable/2937954)

## 4. Advanced Causal Inference Methods

* Causal Trees and Causal Forest:
  * [Causal Tree Learning For Heterogeneous Treatment Effect Estimation](https://www.causalflows.com/causal-tree-learning/)
* Heterogeneous Treatment Effects:
  * [Not Merely Averages: Using Machine Learning to Estimate Heterogeneous Treatment Effects (CATE, BLP, GATES, CLAN)](https://towardsdatascience.com/not-merely-averages-using-machine-learning-to-estimate-heterogeneous-treatment-effects-573bf7376a73)
* Causal ML:
  * [Causal ML for Data Science: Deep Learning with Instrumental Variables](https://towardsdatascience.com/causal-ml-for-data-science-deep-learning-with-instrumental-variables-96e5b7cc0482)
  * [Meta-learners for Estimating Treatment Effect in Causal Inference](https://towardsdatascience.com/meta-learners-for-estimating-treatment-effect-in-causal-inference-4f7071503401)
* Causal Deep Learning:
  * [Multivariate Time Series Forecasting Based on Causal Inference with Transfer Entropy and Graph Neural Network](https://www.researchgate.net/publication/341148262_Multivariate_Time_Series_Forecasting_Based_on_Causal_Inference_with_Transfer_Entropy_and_Graph_Neural_Network)

## 5. Blogs to follow

* [Leihua Ye, Ph.D. Researcher](https://leihua-ye.medium.com/)
* [Andrew Rothman](https://anr248.medium.com/)
