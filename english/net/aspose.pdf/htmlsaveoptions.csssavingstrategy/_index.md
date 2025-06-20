---
title: Delegate HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: You can assign to this property custom strategy that implements processing or/and saving of one CSSs part that was created during conversion of PDF to HTML . In such case processing like saving to stream or disk must be done in that custom code
type: docs
weight: 5720
url: /net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy delegate

You can assign to this property custom strategy that implements processing or/and saving of one CSS's part that was created during conversion of PDF to HTML . In such case processing (like saving to stream or disk) must be done in that custom code

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Parameter | Type | Description |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | represents set of data that can be used for saving of supplied CSS part |

### See Also

* class [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


