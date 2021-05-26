# Checkout Step Encountered

## Javascript Code
```js
window.appEventData1491 = window.appEventData1491 || [];
appEventData1491.push({
  "event": "Checkout Step Encountered",
    "eventDetails": {
        "checkoutStep": "<checkoutStep>"
    },
    "product": [
        {
            "price": {
                "priceType": "<priceType>"
            },
            "productInfo": {
                "sku": "<sku>"
            }
        }
    ]
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|checkoutStep|string|Describes a discrete step in the checkout flow. |Cart Review, Billing Info, Shipping Info, Order Review|||||||
|priceType|string|Describes the type of price offered using commonly used terms. |1st mark, 2nd mark, 3rd mark, clearance, sale, doorbuster|||||||
|sku|string|Stock Keeping Unit (SKU) Unique Identifier of specific item (typically) held in inventory.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level below productID for products with SKU variants. |34567890, 4567890, 00155-large-cornflower|||||||
