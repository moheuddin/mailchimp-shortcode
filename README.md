# MailChimp Shortcode WordPress plugin

This plugin provides a shortcode for output of a simple MailChimp subscription form anywhere in your post. The form submits to an end-point provided by this plugin and uses the MailChimp API to submit the subscription request.

## Using this plugin

This plugin simply provides a shortcode (`[mailchimp_signup]`) for output of a MailChimp subscription form anywhere that is processed by `do_shortcode()`.

## Configuration

To keep this plugin simple, there is no UI. All configuration options can be configured either by defining PHP constants or specifying options on the shortcode itself. For more information on defining constants, check out the in-line documentation in the primary `mailchimp-shortcode.php` file. For more information on shortcode parameters, checkout the in-line documentation in the `lib/mailchimp-shortcode.class.php` file on the `shortcode()` method.

### Requirements

* **WordPress:** 4.1
* **PHP:** 5.3+
* **MailChimp API Key** created by a user of either _manager_, _admin_, or _owner_ capabilities.
