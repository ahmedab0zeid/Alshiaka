=== Amazon payment services ===
Tags: Amazon payment services, Credit/ Debit card, Installments, Apple Pay, Visa Checkout, KNET, NAPS, Valu
Requires at least: 5.3
Tested up to: 6.0.2
Requires PHP: 7.0
Stable tag: 2.3.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-3.0.html

== Description ==
Amazon payment services makes it really easy to start accepting online payments (credit & debit cards) in the Middle East. Sign up is instant, at https://paymentservices.amazon.com/

== Changelog ==
`v2.3.0`
* New - New payment option (STC Pay) is integrated.

`v2.2.5`
* Fix - Failed order when back button click from thank you.
* Fix - 3ds redirection handling.
* Fix - Apple Pay button display on dom ready.
* Fix - WC compatibility.

`v2.2.4`
* Fix - Change Ajax calling to support third party plugin.

`v2.2.3`
* Fix - Scheduled task check status call only for APS orders.
* Fix - Redirection issue fixed.
* Fix - Order place checkout js error.
* Fix - Sanitize, Validate and Escape as per wordpress standard.
* New - KNET response fields added on thankyou & admin order detail page.

`v2.2.2`
* Fix - Stop http post of extra params on aps redirection endpoint
* New - Apple Pay : Display store  name in apple pay pop is now configurable from admin panel.

`v2.2.1`
* Fix - Apple Pay button implementation with generic function.
* Fix - WC compatibility.
* FIX - Html entity decode, html entites for signature.
* Fix - Plugin enabled in WC payment tab if any of the payment options enabled.
* Fix - Embedded hosted checkout clear card & plan detail while switch between cards.

`v2.2.0`
- Single Card Form Config for Installments and Cards
