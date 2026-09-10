# YOWECH Shopify B2B Theme Setup

## Product architecture

Products are managed entirely from Shopify Admin. Do not create separate product-detail pages.

### Recommended product fields

- Product title: clear buyer-facing product name
- Product description: concise B2B product description
- Product images: clean product photography
- Price: reference wholesale price; use variants when pricing differs by option
- Product type: category/product type
- Collections: assign the product to one or more silicone categories
- `custom.moq`: minimum order quantity
- `custom.material`: silicone/material information
- `custom.colors`: available colors
- `custom.size`: dimensions/size
- `custom.packaging`: packaging information
- `custom.specifications`: technical specifications
- `custom.oem_odm`: OEM/ODM availability

## Core collections

Create these Shopify collections using the following handles so the theme links work correctly:

1. Silicone Kitchenware — `silicone-kitchenware`
2. Silicone Food Storage — `silicone-food-storage`
3. Silicone Baby Products — `silicone-baby-products`
4. Silicone Pet Products — `silicone-pet-products`
5. Silicone Household Products — `silicone-household-products`
6. Silicone Bathroom Products — `silicone-bathroom-products`
7. Silicone Beauty Products — `silicone-beauty-products`
8. Silicone Outdoor & Sports — `silicone-outdoor-sports`

## B2B-only model

The theme intentionally has no retail purchase flow:

- No cart
- No Add to Cart
- No Buy Now
- No checkout
- No shopping bag
- No retail quantity selector

The main conversion action is **Request a Quote**. WhatsApp and Email can be enabled through theme settings.

## Product SEO

For each product, write a unique title and description. Add useful specifications, MOQ, material and packaging information. Avoid duplicate manufacturer-style descriptions across large groups of products.

For each collection, add a unique collection description covering the category, wholesale intent and relevant OEM/ODM use cases.
