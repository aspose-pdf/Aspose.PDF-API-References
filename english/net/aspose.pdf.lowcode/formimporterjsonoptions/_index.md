---
title: Class FormImporterJsonOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LowCode.FormImporterJsonOptions class. Options for importing form field values from JSON. This class directly implements the required plugin option interfaces and holds a collection of input source pairs PDF  JSON and a collection of output targets where the resulting PDFs will be saved
type: docs
weight: 7370
url: /net/aspose.pdf.lowcode/formimporterjsonoptions/
---
## FormImporterJsonOptions class

Options for importing form field values from JSON. This class directly implements the required plugin option interfaces and holds a collection of input source pairs (PDF + JSON) and a collection of output targets where the resulting PDFs will be saved.

```csharp
public sealed class FormImporterJsonOptions : IPluginOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [FormImporterJsonOptions](formimporterjsonoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Inputs](../../aspose.pdf.lowcode/formimporterjsonoptions/inputs/) { get; } | Gets the collection of input source pairs (PDF source and corresponding JSON source). |
| [Outputs](../../aspose.pdf.lowcode/formimporterjsonoptions/outputs/) { get; } | Gets the collection of output targets where the resulting PDFs will be saved. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.lowcode/formimporterjsonoptions/addinput/)(IDataSource, IDataSource) | Adds a new pair of input sources – the PDF document and the JSON file. |
| [AddOutput](../../aspose.pdf.lowcode/formimporterjsonoptions/addoutput/)(IDataSource) | Adds a new output target. |

### See Also

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)


