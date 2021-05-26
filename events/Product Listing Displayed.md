# Product Listing Displayed

## Javascript Code
```js
window.appEventData1491 = window.appEventData1491 || [];
appEventData1491.push({
  "event": "Product Listing Displayed",
    "listingDisplayed": {
        "filterList": "<filterList>",
        "listing": [
            {
                "productInfo": {
                    "brand": "<brand>"
                }
            }
        ],
        "listingContext": "<listingContext>",
        "listingDriver": "<listingDriver>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|brand|string|Describes the brand of a product or offering.|Ford, Chevrolet, Dodge, Levis, Columbia, Patagonia|||||||
|filterList|string|A twice delimited string of filterType and filterValue pairs.  Use ~ between type and value.  Use | between pairs|sort~price ascending|color~green|size~medium|||||||
|listingContext|string|Describes the context of a listing display (sort changed, filter added, filter removed)|Filter Added, Filter Removed, Sort Change, Pagination|||||||
|listingDriver|string|Describes the action that caused the listing to be displayed|Onsite Search, Curated Assortment, Navigation|||||||
