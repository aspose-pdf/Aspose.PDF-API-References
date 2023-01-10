---
title: HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF for Java API Reference
description: To this property You can assign delegate created from custom method that implements processing of external resourceFont or Image that was extracted from PDF and must be saved as external resource during conversion of PDF to HTML.
type: docs
weight: 25
url: /java/com.aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract static class HtmlSaveOptions.ResourceSavingStrategy extends System.MulticastDelegate
```

To this property You can assign delegate created from custom method that implements processing of external resource(Font or Image) that was extracted from PDF and must be saved as external resource during conversion of PDF to HTML. In such case processing (like saving in stream or disk) can be done in that custom code and that custom code must return path(or any another string without quotemarks) that will be afterwards incorporated into generated HTML instead of original supposed path to that image resource. In such case All the necessary actions for saving of image must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'resourceSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code .
## Constructors

| Constructor | Description |
| --- | --- |
| [ResourceSavingStrategy()](#ResourceSavingStrategy--) |  |
## Methods

| Method | Description |
| --- | --- |
| [invoke(SaveOptions.ResourceSavingInfo resourceSavingInfo)](#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-) | Invoked method |
### ResourceSavingStrategy() {#ResourceSavingStrategy--}
```
public ResourceSavingStrategy()
```


### invoke(SaveOptions.ResourceSavingInfo resourceSavingInfo) {#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-}
```
public abstract String invoke(SaveOptions.ResourceSavingInfo resourceSavingInfo)
```


Invoked method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resourceSavingInfo | [ResourceSavingInfo](../../com.aspose.pdf/resourcesavinginfo) | SaveOptions.ResourceSavingInfo object |

**Returns:**
java.lang.String - String object
