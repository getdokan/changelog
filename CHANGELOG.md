# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Ongoing
- **Mobile Responsive**
- **Avalara Tax Service**
- **Signup with OTP**
- **Multi-lingual support in everywhere**
- **Product Pre-order**
- **Stripe Connect**

## [2.4.0] - 2025-09-30
- **Migration** order-service, report-service, shipping-service and activity-service has been migrated into laravel.
- **Product Q&A** customers can ask questions and vendors can reply.
- **Product Review** admin & vendor can see their product reviews in dashboard and admin can approve review.
- **OTO Shipping Gateway**
- **Redx Shipping Gateway**
- **Steadfast Shipping Gateway**
- Enhanced shipping
- Lots of UI enhancements and issue fixes

## [2.3.0] - 2025-08-11
- **Multi-lingual** support (products, categories, collections, brands, etc). The customer can switch between supported languages.
- **Shurjopay** payment gateway for Bangladesh
- **Customer account self deletion**
- **Enhanced bulk edit**
- Lots of UI enhancements and issue fixes

## [2.2.5] - 2025-07-24
- **Preview functionality** for categories and collections with tooltips
- Fixed multiple missing localizations
- Fixed tax import
- Attribute and variation UX improvements
- Reduced nested levels of sitemap

## [2.2.4] - 2025-07-15
- **Romanian language** support
- **Vendor commission information** in vendor details

## [2.2.3] - 2025-07-11
- **Webhooks:** limited events support. more events will be supported later.
- **Private Media Uploader**
- **Upload file using url**
- **Downloadable Products v2**
- **Romanian Language support**
- **Display vendor commission in their billing page**
- **Enhanced category and attribute.**
- Lots of UI enhancements.
- Fixed a lots of bugs.

## [2.2.2] - 2025-06-19

### Added
- **Product Attribute Block**
- **Theme Store:** https://themes.dokan.co

### Enhanced
- Lots of UI enhancements.

### Bug Fixes
- Fixed a lots of bugs.

## [2.2.1] - 2025-06-12

### Added
- **Product Duplicate**
- **Category Export**
- **Category Import**

### Enhanced
- Lots of UI enhancements.

### Bug Fixes
- Fixed a lots of bugs.

## [2.2.0] - 2025-05-19

### Added
- **Custom Email Domain:** admin can configure to use his own domain for sending emails.
- **bKash Gateway:** customers can pay vis bkash.
- **www Domain support:** admin can add both www & non-www version of domain together.
- **Wishlist:** customers can add products to various lists for future use.
- **Product Abuse Report:** customer can report about products.
- **Woocommerce Store Migrator:** standalone admin can migrate products, customers from woocommerce.
- **Packing Slip Generator:** vendor/admin can download generated packing slips for shipments.
- **POS Invoice Print:** admin/vendor can print POS size invoices.
- **Global Attribute:** admin can create global attributes to reuse in cartegory or products.
- **Revamped Attribute Mapping**
- **Product Import Field Mapping**

### Enhanced
- Lots of UI enhancements.

### Bug Fixes
- Fixed a lots of bugs.

## [2.1.2] - 2025-02-26

### Added
- **Builder Multi-lingual:** admin can customize the pages and different texts for each supported languages.
- **Mobile login with OTP:** vendor can login via mobile otp verification.
- **Image Cropping:** admin/vendor can crop image after uploading images.
- **Theme search and scroll:** admin can search for themes in theme library.
- **Yearly Billing:** admin can purchase cloud subscription with both monthly and yearly payment.

### Bug Fixes
- Show refunded orders in proper tab
- Domain verification issue
- Image `alt` tag text saving issue
- Support noscript and comment in head tags
- Fixed recommended UI issues.

### Enhanced
- Enahnced shipping UI

## [2.1.1] - 2024-12-30

### Added
- **Collection details page customization through builder:** admin can customize collection details page through page builder.
- **Category list page customization through builder:** admin can customize category list page through page builder.
- **Category details page customization through builder:** admin can customize category details page through page builder.
- **Store Details page customization:** admin can customize store details page through page buikder.
- **Megamenu (Dropdown) Block:** admin can create dropdown in builder.
- **Recently Viewed Products:** using this block, admin can show the recently viewed products to users.
- **New Theme:** Pulse, Lumen, Vivid, Verge and Nova.
- **New Theme Version:** Storefront, Mega Mall have new version.
- **Order Private File Download:** digital files will be downloaded privately.
- **Zero Payment Method:** for handling free products purchase.

### Bug Fixes
- https://github.com/getdokan/project/issues/1637 Refund Option Available Before Payment, Should Be Enabled Only After Payment Status is 'Paid' | MT
- https://github.com/getdokan/project/issues/1659 Tax Not Calculated on Shipping at Checkout, But Calculated on Order Received Page
- https://github.com/getdokan/project/issues/1597  Display Payment Methods in Order Activity for Cash on Delivery
- https://github.com/getdokan/project/issues/1612 Unrestricted Download Link Access for Digital Products. | MT
- https://github.com/getdokan/project/issues/1768 Error When Reconnecting Mailchimp Integration

### Enhanced
- **Synchronized Cart System:** removed cart from localstorage.
- **Mobile Responsive:** made more dashboard and storefront pages responsive.
- **Tax Configuration:** enhanced manual tax configuration.

## [2.1.0] - 2024-10-18

### Added
- **Bank Gateway:** The manual payment gateway "Bank" has been added.
- **Payfast:** payment gateway.
- **Vendor Subscription via Paypal:** vendor can purchase subscription using paypal.
- **Product Bulk Edit:** Products can now be edited in bulk.
- **Product Collections:** admin can create prouduct collections and display products in storefront.
- **Single Product Page Customization:** admin can customize single product page through page builder.
- **Shop Page Customization:** admin can customize shop page through page builder.
- **Tab Block:** while customizing through builder, admin can create tab using this block.
- **Mobile Responsive:** made various dashboard and storefront pages responsive.

### Enhanced
- **Coupon:** enhanced coupon creation.

## [2.0.2] - 2024-09-18

### Added
- **Paystack Gateway** Added paystack gateway for collecting payments from customers. Payout & subscription will be introduced later.

## [2.0.1] - 2024-09-11

### Added
- **Payout via Bank Transfer:** Vendor Payout via Manual Bank Transfer is now available in all countries.

## [2.0.0] - 2024-09-05

### Added

- **Standalone Shop:** Empowers small to medium entrepreneurs to quickly launch their own online shops.
- **Support PIN:** Enables admin to provide temporary access of their marketplace/shop to the support team.
- **Multiple Payment Gateways:** Added support for gateways like RazorPay, MangoPay, SSLCommerz, Tap, Iyzico etc.
- **Multiple Language Support:** Multiple language translations are available now.
- **Return an Item:** Enables admin to return an ordered item.
- **Snippet Settings:** Allows admin to add custom JS snippet to their marketplace/shop.
- **Product/Store Social Share:** The social share links have been added to product/store page in the storefront.
- **Social Links Block:** Dokan Builder has a new social link block.
- **Block Presets:** Multiple block presets have been added to Dokan Builder which saves huge time.
- **Blocks:** Multiple block elements have been added to Dokan Builder which is helpful for building website faster.
- **Product Filter:** Improved new design of filtering products in the admin dashboard.
- **Approve/Reject Payout Request:** Admin can now approve or reject a payout request with a note.
- **Frequently Bought Together:** A new section called Frequently Bought Together has been added to product page in the storefront.
- **Order Invoice:** Customers can now download order invoices.
- **Changelog:** A new changelog button has been added to the navigation bar of the dashboard which shows the changes in Dokan Cloud.
- **Full-day Store Opening:** Vendors/Sellers can now choose "Full Day" instead of a time range in their store details settings.
- **Product Zoom:** Customers can now hover over the image of a product and see the magnified view of the product image.
- **Vendor Onboarding Customization:** Admin can now customize which fields are required for vendor registration. All fields are turned off by default.
- **Order Activity:** Order activity has been added to the order details page in admin/vendor dashboard.
- **Calendly Integration:** To get feedback faster, we have added a calendly meeting schedule link on the navigation bar of the dashboard.
- **Survey:** To better understand users' needs, we have added a survey module through which we will collect user feedback.

### Changed

- **Revamped Shipping:** Shipping module has been reimagined with ease of use in mind.
- **Revamped Payment:** Payment module has been reimplemented to support more sub-gateways for stripe and mangopay.
- **Login and Registration:** The pages have been redesigned.

## [1.0.0] - 2024-03-18

### Added

- **Storefront** The customer-facing storefront has been added.
- **Dashboard** The backend for a marketplace. Accessible by admin and vendor.
- **Auth Module:** Basic Login/Registration features for admin/vendor/customer.
- **Catalog Module:** Brand, Category and Product management features were added for admin/vendor.
- **Cart Module:** Customers can add products to the cart.
- **Order/Checkout Module:** Customers can place an order from the checkout page. Admin/vendor can deliver, cancel.
- **Shipping Module:** Vendors can set shipping profile, and customers can see the calculated shipping charge at checkout. Vendors can purchase shipping label or fulfill the order manually.
- **Tax Module:** Admin can set tax classes, and customers can see the calculated tax at checkout.
- **Payment Module:** Admin can set payment gateways, and vendors can connect to them. Customers can purchase using the enabled gateways.
- **Payout Module:** Vendors can receive payouts from admin either automatically (depends on the gateway) or manually.
- **Report Module:** Admin an Vendor can see various reports on the homepage of their dashboard.
- **Builder Module:** Admin can customize the look and feel of their storefront using Dokan Builder with prefilled themes: Storefront and MegaMall.
- **Integration Module:** Admin can add various integration to extend the functionality of the marketplace.
- **Domain Module:** Admin can map their own domains without having to worry about disk storage, server configuration, SSL configuration etc.
- **Team Module:** Admin and Vendor can have team members to delegate some responsibilities of their marketplace or store.
- **SEO Module:** Admin can configure the SEO keywords and settings as they see fit for their marketplace.
- **Subscription Plan:** Admin can configure the subscription plans for the vendors.
- **Policies:** Admin can set up various policy for their marketplace: Return/Refund/Shipping/Privacy/TOS etc.
- **Settings:** Admin and vendor can configure their marketplace/store with various settings.
