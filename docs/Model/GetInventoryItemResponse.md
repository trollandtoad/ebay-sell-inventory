# # GetInventoryItemResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**errors** | [**\eBay\Sell\Inventory\Model\Error[]**](Error.md) | This container will be returned if there were one or more errors associated with retrieving the inventory item record. | [optional]
**inventory_item** | [**\eBay\Sell\Inventory\Model\InventoryItemWithSkuLocaleGroupKeys**](InventoryItemWithSkuLocaleGroupKeys.md) |  | [optional]
**sku** | **string** | The seller-defined Stock-Keeping Unit (SKU) of the inventory item. The seller should have a unique SKU value for every product that they sell. | [optional]
**status_code** | **int** | The HTTP status code returned in this field indicates the success or failure of retrieving the inventory item record for the inventory item specified in the &lt;strong&gt;sku&lt;/strong&gt; field. See the &lt;strong&gt;HTTP status codes&lt;/strong&gt; table to see which each status code indicates. | [optional]
**warnings** | [**\eBay\Sell\Inventory\Model\Error[]**](Error.md) | This container will be returned if there were one or more warnings associated with retrieving the inventory item record. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
