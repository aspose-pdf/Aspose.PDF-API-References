---
title: "FormImporterJsonOptions Class"
linktitle: "FormImporterJsonOptions"
articleTitle: "FormImporterJsonOptions"
second_title: "Aspose.PDF for .NET"
description: "Options for importing form field values from JSON. This class directly implements the required plugin option interfaces and holds a collection of input sourc..."
type: docs
weight: 320
url: "/net/aspose.pdf.lowcode/formimporterjsonoptions/"
keywords: "FormImporterJsonOptions, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## FormImporterJsonOptions class

Options for importing form field values from JSON.
 This class directly implements the required plugin option interfaces and
 holds a collection of input source pairs (PDF + JSON) and a collection of
 output targets where the resulting PDFs will be saved.

```csharp
public sealed class FormImporterJsonOptions : IPluginOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [FormImporterJsonOptions](./formimporterjsonoptions/#constructor) | Initializes a new instance of the FormImporterJsonOptions class. |

## Properties

| Name | Description |
| --- | --- |
| [Inputs](./inputs/) { get; } | Gets the collection of input source pairs (PDF source and corresponding JSON source). |
| [Outputs](./outputs/) { get; } | Gets the collection of output targets where the resulting PDFs will be saved. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](./addinput/)(*IDataSource, IDataSource*) | Adds a new pair of input sources – the PDF document and the JSON file. |
| [AddOutput](./addoutput/)(*IDataSource*) | Adds a new output target. |

### See Also

* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

