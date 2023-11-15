---
title: Class PdfFormFlattenFieldsOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfFormFlattenFieldsOptions class. Represents options for flatten all Fields not annotations on specified pages of document by PdfForm plugin
type: docs
weight: 6570
url: /net/aspose.pdf.plugins/pdfformflattenfieldsoptions/
---
## PdfFormFlattenFieldsOptions class

Represents options for flatten all Fields (not annotations) on specified pages of document by PdfForm plugin.

```csharp
public sealed class PdfFormFlattenFieldsOptions : PdfFormOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFormFlattenFieldsOptions](pdfformflattenfieldsoptions/#constructor_3)(HashSet&lt;int&gt;) | Initializes a new instance of the `PdfFormFlattenFieldsOptions` object by set of pages, on which ALL fields will be flatten. |
| [PdfFormFlattenFieldsOptions](pdfformflattenfieldsoptions/#constructor_1)(int) | Initializes a new instance of the `PdfFormFlattenFieldsOptions` object by page number, on which ALL fields will be flatten. |
| [PdfFormFlattenFieldsOptions](pdfformflattenfieldsoptions/#constructor)(SelectField) | Initializes a new instance of the `PdfFormFlattenFieldsOptions` object, by a delegate that specifies which fields to flatten. |
| [PdfFormFlattenFieldsOptions](pdfformflattenfieldsoptions/#constructor_2)(int, int) | Initializes a new instance of the `PdfFormFlattenFieldsOptions` object by page interval from pageFrom to pageTo (inclusive for both), on which ALL fields will be flatten. |

## Properties

| Name | Description |
| --- | --- |
| [DataCollection](../../aspose.pdf.plugins/pdfformoptions/datacollection/) { get; } | Returns FormOptions plugin data collection. |
| [GetPageNumbers](../../aspose.pdf.plugins/pdfformflattenfieldsoptions/getpagenumbers/) { get; } | Gets set of pages on which fields will be flattened by method Process call. |
| [GetSelectFieldDelegate](../../aspose.pdf.plugins/pdfformflattenfieldsoptions/getselectfielddelegate/) { get; } | Gets delegate specifying the field(s) to which flatten should be made. |
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


