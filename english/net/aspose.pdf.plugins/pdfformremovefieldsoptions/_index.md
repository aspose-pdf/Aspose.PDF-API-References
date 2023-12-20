---
title: Class PdfFormRemoveFieldsOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfFormRemoveFieldsOptions class. Represents options for remove all Fields from specified pages of document by PdfForm plugin
type: docs
weight: 6680
url: /net/aspose.pdf.plugins/pdfformremovefieldsoptions/
---
## PdfFormRemoveFieldsOptions class

Represents options for remove all Fields from specified pages of document by PdfForm plugin.

```csharp
public sealed class PdfFormRemoveFieldsOptions : PdfFormOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFormRemoveFieldsOptions](pdfformremovefieldsoptions/#constructor_3)(HashSet&lt;int&gt;) | Initializes a new instance of the `PdfFormRemoveFieldsOptions` object by set of pages, on which ALL fields will be removed. |
| [PdfFormRemoveFieldsOptions](pdfformremovefieldsoptions/#constructor_1)(int) | Initializes a new instance of the `PdfFormRemoveFieldsOptions` object by page number, on which ALL fields will be removed. |
| [PdfFormRemoveFieldsOptions](pdfformremovefieldsoptions/#constructor)(SelectField) | Initializes a new instance of the `PdfFormRemoveFieldsOptions` object, by a delegate that specifies which fields to remove. |
| [PdfFormRemoveFieldsOptions](pdfformremovefieldsoptions/#constructor_2)(int, int) | Initializes a new instance of the `PdfFormRemoveFieldsOptions` object by page interval from pageFrom to pageTo (inclusive for both), on which ALL fields will be removed. |

## Properties

| Name | Description |
| --- | --- |
| [DataCollection](../../aspose.pdf.plugins/pdfformoptions/datacollection/) { get; } | Returns FormOptions plugin data collection. |
| [GetPageNumbers](../../aspose.pdf.plugins/pdfformremovefieldsoptions/getpagenumbers/) { get; } | Gets set of pages on which fields will be removed by method Process call. |
| [GetSelectFieldDelegate](../../aspose.pdf.plugins/pdfformremovefieldsoptions/getselectfielddelegate/) { get; } | Gets delegate specifying the field(s) to which remove should be made. |
| [SaveTargetsCollection](../../aspose.pdf.plugins/pdfformoptions/savetargetscollection/) { get; } | Gets collection of added targets for saving operation results. |

## Methods

| Name | Description |
| --- | --- |
| [AddDataSource](../../aspose.pdf.plugins/pdfformoptions/adddatasource/)(IDataSource) | Adds new data source to the PdfForm plugin data collection. |
| [AddSaveDataSource](../../aspose.pdf.plugins/pdfformoptions/addsavedatasource/)(IDataSource) | Adds new data source to the PdfForm plugin data collection. |

### See Also

* class [PdfFormOptions](../pdfformoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


