---
title: Class TimestampOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LowCode.TimestampOptions class. Options for the Timestamp LowCode plugin
type: docs
weight: 8080
url: /net/aspose.pdf.lowcode/timestampoptions/
---
## TimestampOptions class

Options for the Timestamp Low‑Code plugin.

```csharp
public sealed class TimestampOptions : PdfConverterOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TimestampOptions](timestampoptions/#constructor)() | Creates a new instance with default values. Used to sing TSA with a PFX file. |
| [TimestampOptions](timestampoptions/#constructor_1)(Stream, string) | Creates a new instance with a PFX stream and password. |
| [TimestampOptions](timestampoptions/#constructor_2)(string, string) | Creates a new instance with a PFX file path and password. |

## Properties

| Name | Description |
| --- | --- |
| [BasicAuthCredentials](../../aspose.pdf.lowcode/timestampoptions/basicauthcredentials/) { get; set; } | Gets or sets the basic authentication credentials, Username and password are combined into a string "username:password". |
| [DigestHashAlgorithm](../../aspose.pdf.lowcode/timestampoptions/digesthashalgorithm/) { get; set; } | Digest hash algorithm to use for the timestamp. Defaults to Sha256. |
| [Inputs](../../aspose.pdf.lowcode/pdfconverteroptions/inputs/) { get; } | Returns PdfConverterOptions plugin data collection. |
| override [OperationName](../../aspose.pdf.lowcode/timestampoptions/operationname/) { get; } |  |
| [Outputs](../../aspose.pdf.lowcode/pdfconverteroptions/outputs/) { get; } | Gets collection of added targets for saving operation results. |
| [PageNumber](../../aspose.pdf.lowcode/timestampoptions/pagenumber/) { get; set; } | Page number on which the timestamped signature will be applied. |
| [Rectangle](../../aspose.pdf.lowcode/timestampoptions/rectangle/) { get; set; } | Rectangle defining the annotation area (ignored when Visible is false). |
| [ServerUrl](../../aspose.pdf.lowcode/timestampoptions/serverurl/) { get; set; } | URL of the timestamp server. |
| [SigContact](../../aspose.pdf.lowcode/timestampoptions/sigcontact/) { get; set; } | Contact information for the signature. |
| [SigLocation](../../aspose.pdf.lowcode/timestampoptions/siglocation/) { get; set; } | Location for the signature. |
| [SigReason](../../aspose.pdf.lowcode/timestampoptions/sigreason/) { get; set; } | Reason for the signature. |
| [Visible](../../aspose.pdf.lowcode/timestampoptions/visible/) { get; set; } | Visibility flag – false for a pure timestamp (no visible annotation). |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.lowcode/pdfconverteroptions/addinput/)(IDataSource) | Adds new data source to the PdfConverter plugin data collection. |
| [AddOutput](../../aspose.pdf.lowcode/pdfconverteroptions/addoutput/)(IDataSource) | Adds new data source to the PdfToXLSXConverterOptions plugin data collection. |

### See Also

* class [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)


