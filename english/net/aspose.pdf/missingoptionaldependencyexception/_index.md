---
title: "MissingOptionalDependencyException Class"
linktitle: "MissingOptionalDependencyException"
articleTitle: "MissingOptionalDependencyException"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.MissingOptionalDependencyException class. Represents an error that occurs when an optional dependency required by a feature is not available in th..."
type: docs
weight: 1930
url: "/net/aspose.pdf/missingoptionaldependencyexception/"
keywords: "MissingOptionalDependencyException, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## MissingOptionalDependencyException class

Represents an error that occurs when an optional dependency required by a feature
 is not available in the application.

```csharp
public sealed class MissingOptionalDependencyException : PdfException
```

## Constructors

| Name | Description |
| --- | --- |
| [MissingOptionalDependencyException](./missingoptionaldependencyexception/#constructor) | Initializes a new instance of the [`MissingOptionalDependencyException`](../../aspose.pdf/missingoptionaldependencyexception/) class. |
| [MissingOptionalDependencyException](./missingoptionaldependencyexception/#constructor_1)(*string*) | Initializes a new instance of the [`MissingOptionalDependencyException`](../../aspose.pdf/missingoptionaldependencyexception/) class. |
| [MissingOptionalDependencyException](./missingoptionaldependencyexception/#constructor_2)(*string, Exception*) | Initializes a new instance of the [`MissingOptionalDependencyException`](../../aspose.pdf/missingoptionaldependencyexception/) class. |

## Methods

| Name | Description |
| --- | --- |
| [GenerateCrashReport](../../aspose.pdf/pdfexception/generatecrashreport/)(*CrashReportOptions*) | Forms crash report based on Exception HTML format. *(Inherited from PdfException)* |

## Remarks

This exception is thrown only when a caller uses a feature whose implementation
 dependencies are intentionally not exposed as transitive package dependencies.

### See Also

* class [PdfException](../pdfexception/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

