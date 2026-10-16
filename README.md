# BLIU storefront preview

Responsive static storefront for BLIU Essentials and BLIU Luxe, based on the Google Stitch project screens and design systems.

## Preview locally

Open this folder in VS Code, then run a local static server from the project folder:

```powershell
python -m http.server 4173
```

Open `http://localhost:4173` in a browser. The default page is the BLIU gateway with Essentials and Luxe entry cards. Each line opens its own landing page, category tiles, and collection-scoped Shop All archive. Pages use `?page=` routes and do not need a build step or package install.

## Screens

Home, Essentials and Luxe collection landings, collection-scoped Shop All, Product Detail, Indian Size Guide, Shopping Bag, Secure Checkout, Order Confirmation, Account Access, My Account, Wishlist, Our Story & Craft, Style Journal, FAQs, Shipping & Returns, Track Order, Concierge & Contact, and Reviews.

The storefront is a front-end preview. Bag, wishlist, account details, address, and preview order data use this browser's local storage. Checkout does not charge a payment method; contact messages are not transmitted. Connect a store backend, payment provider, enquiry form, verified customer-care channels, final policy copy, and real product catalogue before launch.
