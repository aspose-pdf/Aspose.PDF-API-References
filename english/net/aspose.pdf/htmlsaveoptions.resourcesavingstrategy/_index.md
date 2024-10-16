---
title: Delegate HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: To this property You can assign delegate created from custom method that implements processing of external resourceFont or Image that was extracted from PDF and must be saved as external resource during conversion of PDF to HTML. In such case processing like saving in stream or disk can be done in that custom code and that custom code must return pathor any another string without quotemarks that will be afterwards incorporated into generated HTML instead of original supposed path to that image resource. In such case All the necessary actions for saving of image must be undertaken in code of supplied method because saving of result in code of converter will be not in use . If processing for this or that file for some reason must be done by converters code itself not in custom code please set in custom code flag CustomProcessingCancelled of resourceSavingInfo parameters variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code 
type: docs
weight: 4170
url: /net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## HtmlSaveOptions.ResourceSavingStrategy delegate

To this property You can assign delegate created from custom method that implements processing of external resource(Font or Image) that was extracted from PDF and must be saved as external resource during conversion of PDF to HTML. In such case processing (like saving in stream or disk) can be done in that custom code and that custom code must return path(or any another string without quotemarks) that will be afterwards incorporated into generated HTML instead of original supposed path to that image resource. In such case All the necessary actions for saving of image must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'resourceSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code .

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| Parameter | Type | Description |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | represents set of data for saving of resource |

### Return Value

must return URL to saved resource that will be used during generation of HTML

### See Also

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


