---
title: HtmlSaveOptions.CustomHtmlSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions field. Result of conversion can contain one or several HTMLpages You can assign to this property delegate created from custom method that implements processing of one HTMLpageto be accurately  markupHTML without exteranl linked files if any that was created during conversion. In such case processing like saving of paages HTML in stream or disk can be done in that custom code . In such case all the necessary actions for saving of HTML page must be undertaken in code of supplied method because saving of result in code of converter will be not in use . If processing for this or that case for some reason must be done by converters code itself not in custom code please set in custom code flag CustomProcessingCancelled of htmlSavingInfo parameters variable  it will signal to converter that all the necessary steps for processing of that resource must be done in converter itself in same way as if there was no any external custom code for procesing 
type: docs
weight: 250
url: /net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## HtmlSaveOptions.CustomHtmlSavingStrategy field

Result of conversion can contain one or several HTML-pages You can assign to this property delegate created from custom method that implements processing of one HTML-page(to be accurately - markup-HTML, without exteranl linked files if any) that was created during conversion. In such case processing (like saving of paage's HTML in stream or disk) can be done in that custom code . In such case all the necessary actions for saving of HTML page must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that case for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'htmlSavingInfo' parameter's variable : it will signal to converter that all the necessary steps for processing of that resource must be done in converter itself in same way as if there was no any external custom code for procesing .

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### See Also

* delegate [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


