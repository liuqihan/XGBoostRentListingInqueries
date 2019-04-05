 # Rental Listing Inquiries

## 数据说明

Rental Listing Inquiries数据集是Kaggle平台上的一个分类竞赛任务，需要根据公寓的特征来预测其受欢迎程度（用户感兴趣程度分为高、中、低三类）。其中房屋的特征x共有14维，响应值y为用户对该公寓的感兴趣程度。评价标准为logloss。 数据链接：<https://www.kaggle.com/c/two-sigma-connect-rental-listing-inquiries> 训练数据（RentListingInquries_train.json） 和测试数据（RentListingInquries_test.json）

## 代码说明

### 特征工程

[FE_RentListingInqueries.ipynb](https://github.com/SophiaYuSophiaYu/XGBoostRentListingInqueries/blob/master/FE_RentListingInqueries.ipynb)

### 逻辑回归LR和支持向量机SVM

[LR_SVM_RentalListingInquiries.ipynb](https://github.com/SophiaYuSophiaYu/XGBoostRentListingInqueries/blob/master/LR_SVM_RentalListingInquiries.ipynb)

### XGBoost

[1_xgboost_Rental_n_estimators.ipynb](https://github.com/SophiaYuSophiaYu/XGBoostRentListingInqueries/blob/master/1_xgboost_Rental_n_estimators.ipynb)

[2_xgboost_Rental_TreeDepth_ChildWeight.ipynb](https://github.com/SophiaYuSophiaYu/XGBoostRentListingInqueries/blob/master/2_xgboost_Rental_TreeDepth_ChildWeight.ipynb)

[3_xgboost_Rental_TreeDepth_ChildWeight.ipynb](https://github.com/SophiaYuSophiaYu/XGBoostRentListingInqueries/blob/master/3_xgboost_Rental_TreeDepth_ChildWeight.ipynb)

[4_xgboost_Rental_nestimators.ipynb](https://github.com/SophiaYuSophiaYu/XGBoostRentListingInqueries/blob/master/4_xgboost_Rental_nestimators.ipynb)

[5_xgboost_Rental_subsample_colsample.ipynb](https://github.com/SophiaYuSophiaYu/XGBoostRentListingInqueries/blob/master/5_xgboost_Rental_subsample_colsample.ipynb)

[6_xgboost_Rental_RegL1L2.ipynb](https://github.com/SophiaYuSophiaYu/XGBoostRentListingInqueries/blob/master/6_xgboost_Rental_RegL1L2.ipynb)

[7_xgboost_Rental_savemodel.ipynb](https://github.com/SophiaYuSophiaYu/XGBoostRentListingInqueries/blob/master/7_xgboost_Rental_savemodel.ipynb)

[8_xgboost_Rental_test.ipynb](https://github.com/SophiaYuSophiaYu/XGBoostRentListingInqueries/blob/master/8_xgboost_Rental_test.ipynb)



