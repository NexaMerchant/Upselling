# NexaMerchant/Upselling

[![Build Status](https://github.com/NexaMerchant/upselling/workflows/Laravel/badge.svg)](https://github.com/NexaMerchant/upselling)
[![Release](https://img.shields.io/github/release/NexaMerchant/upselling.svg?style=flat-square)](https://github.com/NexaMerchant/upselling/releases)
[![Latest Version on Packagist](https://img.shields.io/packagist/v/Nexa-Merchant/upselling.svg?style=flat-square)](https://packagist.org/packages/Nexa-Merchant/upselling)
[![Total Downloads](https://img.shields.io/packagist/dt/Nexa-Merchant/upselling.svg?style=flat-square)](https://packagist.org/packages/Nexa-Merchant/upselling)


# How to Install


```
NexaMerchant\Upselling\Providers\UpsellingServiceProvider::class,
```
Add it to config/app.php $providers

# How to Publish

```
composer require nexa-merchant/upselling
```

# How to Publish Api Docs Or Install Apis Apps

```
php artisan l5-swagger:generate
```

# View Api Docs

```
http://localhost/api/upselling/documentation
```

# Points to Note
```
1) Upselling is a package that is used to upsell products.
2) It is a package that is used to upsell products.
3) You can chose the products you want to upsell.
4) Create a upselling rule and include product id, category id, brand id, price range, discount range, and quantity range.


```

# Upselling Method
> Base use NexaMerchant Cart rule, and use it for cost the price for order, use special coupon code for the the order.

