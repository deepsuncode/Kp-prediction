# A Transformer-Based Framework for Geomagnetic Activity Prediction
Yasser Abduallah, Jason T. L. Wang, Chunhui Xu, Haimin Wang 

Geomagnetic activities have a crucial impact on Earth, which can affect spacecraft and electrical power grids. Geospace scientists use a geomagnetic index, called the Kp index, to describe the overall level of geomagnetic activity. This index is an important indicator of disturbances in the Earth’s magnetic field and is used by the U.S. Space Weather Prediction Center as an alert and warning service for users who may be affected by the disturbances. Early and accurate prediction of the Kp index is essential for preparedness and disaster risk management. In this paper, we present a novel deep learning method, named KpNet, to perform short-term, 1–9 hour ahead, forecasting of the Kp index based on the solar wind parameters taken from the NASA Space Science Data Coordinated Archive. KpNet combines transformer encoder blocks with Bayesian inference, which is capable of quantifying both aleatoric uncertainty (data uncertainty) and epistemic uncertainty (model uncertainty) when making Kp predictions. Experimental results show that KpNet outperforms closely related machine learning methods in terms of the root mean square error and R-squared score. Furthermore, KpNet can provide both data and model uncertainty quantification results, which the existing methods cannot offer. To our knowledge, this is the first time that Bayesian transformers have been used for Kp prediction.

References:

A Transformer-Based Framework for Geomagnetic Activity Prediction. Y. Abduallah, J. T. L. Wang, C. Xu, H. Wang, in Proceedings of the International Symposium on Methodologies for Intelligent Systems, pp 325–335, 2022.

https://link.springer.com/chapter/10.1007/978-3-031-16564-1_31
