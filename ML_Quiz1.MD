### Machine Learning Quiz 1:

#### Clustering, Classification, Naive Bayes

1. High entropy means that the partitions in classification are: <br/>
**[a] not pure** <br/>
[b] pure <br/>
[c] useful <br/>
[d] useless <br/>

    Answer: [a]: not pure. Entropy is a measure of the randomness in the information being processed. The higher the entropy, the harder it is to draw any conclusions from that  information. It is a measure of disorder or purity or unpredictability or uncertainty. Low entropy means less uncertain and high entropy means more uncertain.

2. A machine learning problem involves four attributes plus a class. The attributes have 3, 3, 4, and 6 possible values each. The class has 3 possible values. How many maximum possible different examples are there? <br/>
[a] 9 <br/>
[b] 16 <br/>
[c] 144 <br/>
**[d] 216** <br/>

    Answer: [d]: 216. Maximum possible different examples are the products of the possible values of each attribute and the number of classes: $3 * 3 * 4 * 6 = 216$.

3. Which of the following is NOT supervised learning? <br/>
[a] Decision Tree <br/>
[b] Linear Regression <br/>
[c] Naive Bayesian <br/>
**[d] PCA** <br/>
    
    Answer: [d]: PCA. Principal Component Analysis (PCA) is not predictive analysis tool. It is a data pre-processing tool. It helps in picking out the most relevant linear combination of variables and use them in our predictive model. PCA is a technique for reducing the dimensionality of large datasets, increasing interpretability but at the same time minimizing information loss. 

4. Which of the following statements about Naive Bayes is **incorrect**? <br/>
[a] Attributes can be nominal or numeric <br/>
**[b] Attributes are statistically dependent of one another given the class value.** <br/>
[c] Attributes are statistically independent of one another given the class value. <br/>
[d] Attributes are equally important. <br/>

    Answer: [b]: Attributes are statistically dependent of one another given the class value. Naïve Bayes classifier assumes conditional independence between attributes and assigns the MAP class to new instances. Naive Bayes is a classification algorithm for binary (two-class) and multi-class classification problems. The technique is easiest to understand when described using binary or categorical input values.It is called naive Bayes because the calculation of the probabilities for each hypothesis are simplified to make their calculation tractable. Rather than attempting to calculate the values of each attribute value $P(d1, d2, d3|h)$, they are assumed to be conditionally independent given the target value and calculated as $P(d1|h) * P(d2|H)$ and so on.
    
5. Suppose we would like to perform clustering on spatial data such as the geometrical locations of houses. We wish to produce clusters of many different sizes and shapes. Which of the following methods is the most appropriate? <br/>
**[a] Density-based clustering** <br/>
[b] Model-based clustering <br/>
[c] K-means clustering <br/>
[d] Decision Trees <br/>  

    Answer: [a]: Density-based clustering. The density-based clustering methods recognize clusters based on density function distribution of the data object. For clusters with arbitrary shapes, these algorithms connect regions with sufficiently high densities into clusters.
