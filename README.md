# PHM08-Challenge-Data-Set

I’ll use a popular dataset available in NASA’s data repository, called [PHM08](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan). It’s a collection of data introduced for the first time in 2008 for a challenge competition at the first conference on Prognostics and Health Management. It’s a multivariate time series, that contains 218 turbofan engines, where each engine data has measurements from 21 sensors. Each engine starts to operate normally and ends in failure. 

The goal is to predict the **RUL** of the components. Below, there are the steps that will be followed to build the predictive maintenance algorithm. If you have already created a machine learning model with different datasets in the past, you’ll observe that the only difference is that you need an additional task. You have to compute the Remaining Useful Life values, that are needed to be compared with the predictions.

## Article related to the task

[Predicting the Remaining Useful Life of Turbofan Engine](https://pub.towardsai.net/predicting-the-remaining-useful-life-of-turbofan-engine-f38a17391cac?sk=32f6f00a3f24c7fb4bf6082c51ba63ff)

