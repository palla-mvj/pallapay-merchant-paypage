# pallapay-merchant-paypage

## Create payment page

Please replace values between `{}` with real value in `index.php` file.

`merchant` = You can get or new create merchant from Pallapay Backend from [merchant page](https://www.pallapay.com/account/merchants)

`order` = Your order id created by your website.

`item_name` = Item name that user want to pay for

`item_number` = Item number

`amount` = Total amount of your order

`quantity` = 1 (minimum qty 1)

`currency` = `AED` or `USD` are supported at the moment. (Contact us for more)

`custom` = Your custom value, you will get this value back in `ipn_notify.php` (ipn_notify_url) when the payment was paid.

Customer details : 

`first_name`, `last_name`, `email`, `phone`, `address`, `city`, `state`, `country`, `postalcode`

Once we received your payment we will call your IPN callback url with method `POST`.
You have to set `Status IPN url` input when you create your merchant.
When the payment was done successfully user will be redirected to your `Success link`.
If payment failed or canceled we will redirect user to your `Fail link`.

> (You need to provide `Status IPN url`, `Success link` and `Fail link` in your panel when you create your merchant).


## Ipn notify

You can checkout the `ipn_notify.php` to see an example ipn_notify callback.

You should write your own logics in that file.

## Contact us

Feel free to contact us if you had any question.
