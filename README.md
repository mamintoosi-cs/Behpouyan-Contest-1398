### Behpouyan Contest 1398

* `description.pdf` contest document 
* `test.xlsx` example format for predication data 
* `CPF.xlsx` split into two files:
	* `train_withut_sum.xlsx` contains sheet of industry data except last sheet
	* `train_sum.xlsx` the last sheet (total of all 33 industry)

* `aggrigate_data.ipynb` for trusting the reported data
* `train_sum_agg.xlsx` the trusted data with comparing `train_sum.xlsx` and result `aggrigate_data.ipynb`

* `prepare_data.ipynb`
	* preparing the data for training 
	* normalize data
    * feature engineering
 	* remove bad data ( ```ABS[label - data.mean] > 2.5 * data.std``` )
* `prepared_train_data.xlsx` prepared data by file `prepare_data.ipynb` contains **image 1**

![image 1](https://github.com/mamintoosi-cs/Behpouyan-Contest-1398/blob/master/image/image_1.png "Image 1")


* `predication.ipynb` train data and predicate result (Accuracy : [8, 9) )

* `holiday_94_to_98.xlsx` day status of jalali year 94 to 98



 :wink:


