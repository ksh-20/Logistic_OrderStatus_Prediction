# Logistic_OrderStatus_Prediction

Dataset taken from Kaggle

About Dataset
Context
BL is a small leather products business which has recently started selling its products on Amazon. Currently, it has around 40 SKUs registered in the Indian Marketplace. Over the past few months, it has incurred some loss due to return orders. Now, BL seeks help to predict the likelihood of a new order being rejected. This would help them to take necessary actions and subsequently reduce the loss.

Objective
To build a model which would predict the order status (Delivered to buyer or Returned to seller)

Data Dictionary
The Order data is provided in an excel file. The columns are:

Independent Features:

order_no - Unique Amazon Order Number

order_date - Date on which the order was placed

buyer - Name of the buyer

ship_city - Delivery Address City

ship_state - Delivery Address State

sku - Unique identifier of a product

description - Product description

quantity - Number of units ordered

item_total - Total amount paid by the buyer

shipping_fee - Charges borne by Boss Leathers to ship the item

cod - Mode of payment: Cash on delivery or not

Label / Target Feature:

order_status - Status of the order
