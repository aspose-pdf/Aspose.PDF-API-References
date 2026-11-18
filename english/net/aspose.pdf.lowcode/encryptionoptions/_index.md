---
title: Class EncryptionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LowCode.EncryptionOptions class. Represents Encryption Options for Security plugin
type: docs
weight: 7120
url: /net/aspose.pdf.lowcode/encryptionoptions/
---
## EncryptionOptions class

Represents Encryption Options for [`Security`](../security/) plugin.

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | Initializes new instance of the `EncryptionOptions` object with default options. |

## Properties

| Name | Description |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.lowcode/organizerbaseoptions/closeinputstreams/) { get; set; } | Close input streams after operation completed. |
| [CloseOutputStreams](../../aspose.pdf.lowcode/organizerbaseoptions/closeoutputstreams/) { get; set; } | Close output streams after operation completed. |
| [CryptoAlgorithm](../../aspose.pdf.lowcode/encryptionoptions/cryptoalgorithm/) { get; set; } | Cryptographic algorithm, see [`CryptoAlgorithm`](./cryptoalgorithm/) for details. |
| [DocumentPrivilege](../../aspose.pdf.lowcode/encryptionoptions/documentprivilege/) { get; set; } | Document permissions, see [`Permissions`](../../aspose.pdf/permissions/) for details. |
| [Inputs](../../aspose.pdf.lowcode/organizerbaseoptions/inputs/) { get; } | Returns OrganizerOptions plugin data collection. |
| [Outputs](../../aspose.pdf.lowcode/organizerbaseoptions/outputs/) { get; } | Gets collection of added targets for saving operation results. |
| [OwnerPassword](../../aspose.pdf.lowcode/encryptionoptions/ownerpassword/) { get; set; } | Owner password. |
| [UserPassword](../../aspose.pdf.lowcode/encryptionoptions/userpassword/) { get; set; } | User password. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.lowcode/organizerbaseoptions/addinput/)(IDataSource) | Adds new data source to the PdfOrganizer plugin data collection. |
| [AddOutput](../../aspose.pdf.lowcode/organizerbaseoptions/addoutput/)(IDataSource) | Adds new data source to the PdfOrganizer plugin data collection. |

### See Also

* class [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)


