# pallapay-merchant-paypage
Demo Form Merchant Pay Page

Please replace value between {} to real value<br />

form input value details<br />
merchant = You can get or new create merchant from Pallapay Backend from [merchant page](https://www.pallapay.com/account/merchants) <br />
order = Your order id created by your's website.<br />
item_name = Item name you want to put or your customer buy<br />
item_number = Item number<br />
amount = Total amount of your order<br />
quantity = 1 (minimum qty 1)<br />
currency = "AED, USD" currency code etc which is pallapay accept<br />
custom = We will give you in response same value which is you sent to us.<br />
Fill all the details of your customer <br />
first_name, last_name, email, phone, address, city, state, country, postalcode<br />


once we will receive your payment we will notify to you Your IPN callback url with POST parameter. you have to set "Status IPN link" input box when you created merchant. <br />
once we will receive your payment we will redirect on your "Success link". you have set the link when you created merchant<br />
if payment failed or cancel we will redirect on your fail page. you have set the link when you created merchant.<br />