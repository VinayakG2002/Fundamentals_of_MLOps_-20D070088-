Part 1
--------------------------------------------------------------------------------------

1. In the notes of Week 1, we compared & contrasted MLOps with DevOps. In this question, you need to understand what is meant by the term ***AIOps***, & then contrast it with MLOps.

Solution- AIOps is the application of artificial intelligence to enhance IT operations. Specifically, AIOps uses big data, analytics, and machine learning capabilities to do the following:
- To collect and aggregate huge amounts of operations data produced by different IT infrastructure components, applications and performance monitoring tools.
- Intelligently sift signals out of the noise to identify significant events, avoid false positive signals and patterns related to system performance and availability issues.
- Diagnose root causes and report them to IT for rapid response or in some cases resolve them by itself.

MLOps, on the other hand, pays attention to the managing training and testing data that is needed to create ML models effectively. It focuses on the ML operationalization pipeline. It’s a way to manage and streamline the building, deployment and maintenance of algorithms. MLOps bridges the gap between model building and deployment.

MLOps or AIOps both have are done to achieve the same end goal; i.e. business automation. 


2. ***Interpretable Machine Learning*** is another concept that has attracted lot of attention recently & is promoted by most of the MLOps frameworks. Explain what it means for a linear regression model to be interpretable. You may find [this resource](https://christophm.github.io/interpretable-ml-book/) useful.  

Solution- Linear regression is a linear approach to modelling the relationship between a scalar response and one or more explanatory variables. We can interpret linear regression as one variable y linearly dependent on n independent variables Xi (i=1,2,...n). This means:

y=a1* X1+a2* X2....+an* Xn +a0  (where ai are constants for all 0<=i=<n)

The values of the constants ai can be found out and then the equation which we get in the last gives us the best approximate value for y. This plane also divides the region into 2 different regions. 

Thus we can say that points which are more close to each other are more interrelated and thus we can classify data into various categories. Hence a linear regression model is interpretable.

Part 2
-------------------------
![image](https://user-images.githubusercontent.com/81005869/124963994-1df32400-e03e-11eb-9bdf-81bc858642a0.png)
