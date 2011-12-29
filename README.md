# PayPal Digital Goods for Express Checkout PHP Library Examples

PayPal's Digital Goods for Express Checkout service is a wonderful payment solution with disjointed documentation and an unfortunately verbose name.

I created the [PayPal Digital Goods PHP Library](https://github.com/thenbrent/paypal-digital-goods/) to connect the dots in the documentation and offer a PayPal library that is friendly to humans. 

# Goals

This repository is designed to do three things:

* demonstrate the PayPal PHP library in action;
* demonstrate how to setup the PHP library for your own use;
* show how to include the [PayPal Digital Goods PHP Library](https://github.com/thenbrent/paypal-digital-goods/) as a submodule in your applications main Git repository.


# Usage

To run the examples for yourself, clone the entire folder somewhere onto your server, eg. `http://example.com/paypal-examples/`.

	git clone --recursive git://github.com/thenbrent/paypal-digital-goods-php-examples.git

Note the use of the `--recursive` flag. This must be included to clone the library as it is included as a [Git submodule](http://book.git-scm.com/5_submodules.html).

Once cloned, visit `http://example.com/paypal-examples/index.php` in your browser & follow the links.


# Your Own Credentials

For convenience, this example uses my PayPal Sandbox Credentials. To test with your own API credentials, create a sandbox seller account and request it be set as a Digital Goods account in this [x.com forums topic](https://www.x.com/developers/paypal/forums/digital-goods/express-checkout-digital-goods-sandbox).

Login to the account and get your API credentials from the [API Access](https://www.sandbox.paypal.com/us/cgi-bin/webscr?cmd=_profile-api-access) page.

Copy the API Credentials into `http://example.com/paypal-examples/functions.php`.


