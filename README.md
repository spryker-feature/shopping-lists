# Spryker Feature: Shopping Lists

The Shopping Lists feature allows customers to create and share multiple lists of products between company business units or single users.Shopping lists can be shared between users with different sets of permissions.

[Learn more](https://docs.spryker.com/docs/pbc/all/shopping-list-and-wishlist/202307.0/base-shop/shopping-lists-feature-overview/shopping-lists-feature-overview.html)

## Installation

```
composer require spryker-feature/shopping-lists
```

## Recommended feature dependencies
- [spryker-feature/cart](https://github.com/spryker-feature/cart)
- [spryker-feature/company-account](https://github.com/spryker-feature/company-account)
- [spryker-feature/customer-account-management](https://github.com/spryker-feature/customer-account-management)
- [spryker-feature/prices](https://github.com/spryker-feature/prices)
- [spryker-feature/product](https://github.com/spryker-feature/product)
- [spryker-feature/spryker-core](https://github.com/spryker-feature/spryker-core)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [Shop.ShoppingListPageExtension](https://github.com/spryker-shop/shopping-list-page-extension) (Extension)
- [ShoppingListProductOptionConnector ^1.5.0](https://github.com/spryker/shopping-list-product-option-connector) (Connector)
- [ShoppingListSessionExtension](https://github.com/spryker/shopping-list-session-extension) (Extension)
- [ShoppingListsRestApi ^1.3.0](https://github.com/spryker/shopping-lists-rest-api) (Legacy Glue)
- [ShoppingListsRestApiExtension ^1.0.0](https://github.com/spryker/shopping-lists-rest-api-extension) (Extension)
