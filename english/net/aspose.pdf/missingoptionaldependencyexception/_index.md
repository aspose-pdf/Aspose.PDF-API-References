---
title: "MissingOptionalDependencyException Class"
linktitle: "MissingOptionalDependencyException"
articleTitle: "MissingOptionalDependencyException"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.MissingOptionalDependencyException class. Represents an error that occurs when an optional dependency required by a feature is not available in th..."
type: docs
weight: 1890
url: "/net/aspose.pdf/missingoptionaldependencyexception/"
keywords: "MissingOptionalDependencyException, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
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
| [MissingOptionalDependencyException](missingoptionaldependencyexception/#constructor)() | Initializes a new instance of the `MissingOptionalDependencyException` class. |
| [MissingOptionalDependencyException](missingoptionaldependencyexception/#constructor_1)(string) | Initializes a new instance of the `MissingOptionalDependencyException` class with the specified error message. |
| [MissingOptionalDependencyException](missingoptionaldependencyexception/#constructor_2)(string, Exception) | Initializes a new instance of the `MissingOptionalDependencyException` class with the specified error message and inner exception. |

## Remarks

This exception is thrown only when a caller uses a feature whose implementation
 dependencies are intentionally not exposed as transitive package dependencies.

### See Also

* class [PdfException](../pdfexception/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

