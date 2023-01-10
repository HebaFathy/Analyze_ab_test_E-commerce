# Analyze_ab_test_results
A/B tests are very commonly performed by data analysts and data scientists. It is important that you get some practice working with the difficulties of these.

For this project, you will be working to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Your goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

We used A/B test, Ztest, Logestic regression. 

For A/B test:
The calculated p-value from bootstrap sample with a value of 0.9 which is larger than apla value of 0.05, means we fail to reject the null hypotheses. In addition to, the difference in convertion rate for new page and old page is negative and is not statistically significant concluding that the old page has higher probablity of convert rate than new page. Therefore, the old page is statistically favored and is better than the new one.


For Ztest:
We fail to reject the null hypothesis that old page users is better or equal converted rate than old page users because z-score of 1.31092419842 does not exceed the critical value of 1.960. The converted rate for new page and old page have no difference. This result is the same as A/B test.

For Logestic Regression:
A several model tests are performed for the new page increases conversions. The conclusion is that the new page did not prove to be better than the old page and we do not have the proof to convert to the new page. This confirms previous conclusions, which is that we do not have evidence to reject the null and the old page should be kept.



