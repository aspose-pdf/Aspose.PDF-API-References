---
title: Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Result of conversion can contain one or several HTMLpages  that also can reference external files like images or fonts You can assign to this property delegate created from custom method that implements processing of got HTMLpageHTML itself that was created during conversion. In such case processing like saving in stream or disk can be done in that custom code . In such case All the necessary actions for saving of HTML pages markup must be undertaken in code of supplied method because saving of result in code of converter will be not in use. If processing for this or that case for some reason must be done by converters code itself not in custom code please set in custom code flag CustomProcessingCancelled of htmlSavingInfo parameters variable  it signals to converter that all the necessary steps for processing of that resource must be done in converter itself in same way as if there was no any external custom saving code 
type: docs
weight: 3610
url: /net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## HtmlSaveOptions.HtmlPageMarkupSavingStrategy delegate

Result of conversion can contain one or several HTML-pages ( that also can reference external files like images or fonts) You can assign to this property delegate created from custom method that implements processing of got HTML-page(HTML itself) that was created during conversion. In such case processing (like saving in stream or disk) can be done in that custom code . In such case All the necessary actions for saving of HTML page's markup must be undertaken in code of supplied method, because saving of result in code of converter will be not in use. If processing for this or that case for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'htmlSavingInfo' parameter's variable : it signals to converter that all the necessary steps for processing of that resource must be done in converter itself in same way as if there was no any external custom saving code .

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| Parameter | Type | Description |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | represents data that can be used for saving or processing of supplied HTML page |

### See Also

* class [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


