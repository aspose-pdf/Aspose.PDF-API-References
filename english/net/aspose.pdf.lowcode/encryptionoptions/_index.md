---
title: "EncryptionOptions Class"
linktitle: "EncryptionOptions"
articleTitle: "EncryptionOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.EncryptionOptions class. Represents Encryption Options for plugin."
type: docs
weight: 70
url: "/net/aspose.pdf.lowcode/encryptionoptions/"
keywords: "EncryptionOptions, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## EncryptionOptions class

Represents Encryption Options for [`Security`](../../aspose.pdf.lowcode/security/) plugin.

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [EncryptionOptions](./encryptionoptions/#constructor)(*string, string, [DocumentPrivilege](../../aspose.pdf.facades/documentprivilege/), [CryptoAlgorithm](../../aspose.pdf/cryptoalgorithm/)*) | Initializes new instance of the [`EncryptionOptions`](../../aspose.pdf.lowcode/encryptionoptions/) object with default options. |

## Properties

| Name | Description |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.lowcode/organizerbaseoptions/closeinputstreams/) { get; set; } | Close input streams after operation completed. *(Inherited from OrganizerBaseOptions)* |
| [CloseOutputStreams](../../aspose.pdf.lowcode/organizerbaseoptions/closeoutputstreams/) { get; set; } | Close output streams after operation completed. *(Inherited from OrganizerBaseOptions)* |
| [CryptoAlgorithm](./cryptoalgorithm/) { get; set; } | Cryptographic algorithm, see `CryptoAlgorithm` for details. |
| [DocumentPrivilege](./documentprivilege/) { get; set; } | Document permissions, see [`Permissions`](../../aspose.pdf/permissions/) for details. |
| [Inputs](../../aspose.pdf.lowcode/organizerbaseoptions/inputs/) { get; } | Returns OrganizerOptions plugin data collection. *(Inherited from OrganizerBaseOptions)* |
| [Outputs](../../aspose.pdf.lowcode/organizerbaseoptions/outputs/) { get; } | Gets collection of added targets for saving operation results. *(Inherited from OrganizerBaseOptions)* |
| [OwnerPassword](./ownerpassword/) { get; set; } | Owner password. |
| [UserPassword](./userpassword/) { get; set; } | User password. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.lowcode/organizerbaseoptions/addinput/)(*IDataSource*) | Adds new data source to the PdfOrganizer plugin data collection. *(Inherited from OrganizerBaseOptions)* |
| [AddOutput](../../aspose.pdf.lowcode/organizerbaseoptions/addoutput/)(*IDataSource*) | Adds new data source to the PdfOrganizer plugin data collection. *(Inherited from OrganizerBaseOptions)* |

### See Also

* class [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

