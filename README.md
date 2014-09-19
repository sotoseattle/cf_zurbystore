# Zurby Store

A simple Rails Store with Zurb's Foundation framework as front end.

![screenshot](https://s3.amazonaws.com/fjs6_bucket/zurbystore.jpg)

### Implementation Problems

The app uses Foundation v. 5.4.0 instead of the latest available (5.4.4) because there is a conflict in the sass library between Foundation 5.4.4 and Rails 4.1.6.

Bug issue tracked at: [github/zub](https://github.com/zurb/foundation/issues/5811)

The way I was able to circumvent the problem is detailed here: [Gist](https://gist.github.com/sotoseattle/b067e4e5d2c3cbf7e057)

### Description

There is a single controller: Products with complete CRUD functionality.

The default route is a list of all existing products in the database.

The user can create new products filling a form that includes name and price in USD. The user can also edit and delete a pre specified product.
