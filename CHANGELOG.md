# Changelog

All Notable changes to **Laravel Localized Routes** will be documented in this file.

## 1.3.2 (2019-08-31)

- Add locale middleware for localized routes

## 1.3.1 (2019-06-11)

- Swap `funkjedi/composer-include-files` with `0.0.0/composer-include-files`.
 The former was no longer working in vendor packages (https://github.com/funkjedi/composer-include-files/pull/9).

## 1.3.0 (2019-05-14)

- Add support for signed Routes with locale (#5)

## 1.2.0 (2019-04-30)

- Enable the use of customs domains or subdomains instead of slugs.

## 1.1.0 (2019-03-19)

- Add option to remove the main locale slug from the URL.

## 1.0.1 (2019-03-13)

- Register the `UrlGenerator` the same way Laravel does in recent versions

## 1.0.0 (2018-04-03)

- Automatically register a route for each locale you wish to support.
- Generate localized route URL's in the simplest way using the `route()` helper.
- Redirect to localized routes using the `redirect()->route()` helper.
- Allow routes to be cached.
- Let you work with routes without thinking too much about locales.
- Optionally translate each segment in your URI's.
