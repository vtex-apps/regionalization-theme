# Store theme
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

[<i class="fa-brands fa-github"></i> Source code](https://github.com/vtex-apps/regionalization-theme)

Our boilerplate theme to create stores in the VTEX IO platform.

## Preview

![store-theme-default](https://user-images.githubusercontent.com/1354492/63937047-e8d81c80-ca37-11e9-86fc-61e88847bbfb.png)

## Features

### Delivery Promise

This theme includes the [Delivery Promise](https://help.vtex.com/docs/tutorials/delivery-promise-beta) feature, which provides customers with accurate delivery and pickup availability information based on their location.

**Key functionalities:**

* **Capturing the shopper's location:** Allows the store to obtain the shopper's location, either automatically via browser geolocation or manually via postal code/address, so product availability and delivery or pickup options are calculated specifically for that location.
* **Filtering by delivery method:** Lets shoppers restrict product listings to items available for delivery or pickup, based on their selected address and logistics information.
	* **Header:** Provides a global toggle (for example, to choose between Delivery or Pickup) that applies the chosen delivery method across the entire browsing session.
	* **Sidebar:** Adds PLP and search filters so shoppers can refine results on that page by delivery method (Delivery, Pickup, Pickup nearby, or pickup at a specific point).
* **Filtering by pickup point:** Scopes navigation to products that can be picked up at a chosen store or pickup location.
	* **Header:** Offers a global Filter by store/pickup point control so shoppers can select a specific store and see only products available for pickup there across the site.
	* **Sidebar:** Displays a list of eligible pickup points for the current search or PLP, allowing shoppers to refine results to one particular location.
* **Filtering by Delivery Option:** Enables filters for specific [Delivery Options](https://help.vtex.com/docs/tutorials/delivery-options-beta) and SLAs, so shoppers see only products that can be delivered under the selected delivery time option.
* **Filtering by Dynamic Estimate:** Allows shoppers to filter products by time-sensitive promises (such as "Receive today" or "Receive tomorrow"), using dynamically calculated delivery or pickup estimates for their location. These filters rely on dynamic estimates that are displayed only when an active Delivery Option (configured by the merchant) can realistically fulfill the order during the store's operating hours.

## Tutorial

To understand how things work, check our [Store Framework](https://developers.vtex.com/docs/guides/store-framework) documentation. 

## Dependencies
All store components that you see in this document are open source too. Production-ready, you can find those apps in this GitHub organization.

Store Framework is the baseline for creating any store using _VTEX IO Web Framework_.
* [Store](https://developers.vtex.com/docs/apps/vtex.store)

Store GraphQL is a middleware to access all VTEX APIs.
* [Store GraphQL](https://github.com/vtex-apps/store-graphql/blob/master/docs/README.md)

### Store Component Apps
* [Header](https://github.com/vtex-apps/store-header/blob/master/docs/README.md)
* [Footer](https://github.com/vtex-apps/store-footer/blob/master/docs/README.md)
* [Slider Layout](https://github.com/vtex-apps/slider-layout/blob/master/docs/README.md)
* [Shelf](https://github.com/vtex-apps/shelf/blob/master/docs/README.md)
* [Telemarketing](https://github.com/vtex-apps/telemarketing/blob/master/docs/README.md)
* [Menu](https://github.com/vtex-apps/menu/blob/master/docs/README.md)
* [Login](https://github.com/vtex-apps/login/blob/master/docs/README.md)
* [Minicart](https://github.com/vtex-apps/minicart/blob/master/docs/README.md)
* [Category Menu](https://github.com/vtex-apps/category-menu/blob/master/docs/README.md)
* [Product Summary](https://github.com/vtex-apps/product-summary/blob/master/docs/README.md)
* [Breadcrumb](https://github.com/vtex-apps/breadcrumb/blob/master/docs/README.md)
* [Search Result](https://github.com/vtex-apps/search-result/blob/master/docs/README.md)
* [Product Details](https://github.com/vtex-apps/product-details/blob/master/docs/README.md)
* [Store Components](https://github.com/vtex-apps/store-components/blob/master/docs/README.md)
* [Order Placed](https://github.com/vtex-apps/order-placed/blob/master/docs/README.md)
* [Shipping Option Components](https://github.com/vtex-apps/shipping-option-components/blob/master/docs/README.md) 

### Store Pixel Apps

 * [Google Tag Manager](https://github.com/vtex-apps/google-tag-manager/blob/master/docs/README.md)

## Contributing

Check it out [how to contribute](https://github.com/vtex-apps/store-discussion#vtex-io-community-for-store-developers) with this project.

## Contributors ✨

Thanks goes to these wonderful people:

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://www.hugoccosta.com"><img src="https://avatars2.githubusercontent.com/u/20212776?v=4" width="100px;" alt=""/><br /><sub><b>Hugo Costa</b></sub></a><br /><a href="https://github.com/vtex-apps/store-theme/commits?author=hugocostadev" title="Documentation">📖</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
