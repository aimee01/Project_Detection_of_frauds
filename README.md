# Project_Detection_of_frauds
EDA and Machine Learning to detect fraudulent transactions on an e-commerce website.

### Overview
This project aims at detecting frauds and find out the different aspects of a fraudulent transaction.

### Dataset
The datas come from users activities on a clothing eshop website.
We are using two datasets, one gathering the following variables:
* user_id 
* signup_time : time when the user enters the website
* purchase_time : time when the user makes an order
* purchase_value : value of the order
* device_id : Id of the desktop used to make the order
* source : How did the user go on the website, did he get attracted by visibility optimization methods, ads? : SEO/Ads/Direct
* browser : Chrome/Opera/Safari/IE/Firefox
* sex
* age
* Ip_address
* class : 1 if it's a fraud, else 0

The other dataset is based on Ip_addresses:
* lower_bound_ip_address
* upper_bound_ip_address
* country
