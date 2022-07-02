# pallapay-merchant-paypage
Demo Form Merchant Pay Page

Please replace value between {} to real value

form input value details
merchant = You can get or new create merchant from Pallapay Backend from merchant page  [a link](https://www.pallapay.com/account/merchants) 
order = Your order id created by your's website.
item_name = Item name you want to put or your customer buy
item_number = Item number
amount = Total amount of your order
quantity = 1 (minimum qty 1)
currency = "AED, USD" currency code etc which is pallapay accept
custom = We will give you in response same value which is you sent to us.
Fill all the details of your customer 
first_name, last_name, email, phone, address, city, state, country, postalcode


once we will receive your payment we will notify to you Your IPN callback url with POST parameter. you have to set "Status IPN link" input box when you created merchant. 
once we will receive your payment we will redirect on your "Success link". you have set the link when you created merchant
if payment failed or cancel we will redirect on your fail page. you have set the link when you created merchant.