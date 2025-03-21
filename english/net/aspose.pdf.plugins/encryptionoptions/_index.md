---
title: Class EncryptionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.EncryptionOptions class. Represents Encryption Options for Security plugin
type: docs
weight: 8540
url: /net/aspose.pdf.plugins/encryptionoptions/
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
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Close input streams after operation completed. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Close output streams after operation completed. |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | Cryptographic algorithm, see [`CryptoAlgorithm`](./cryptoalgorithm/) for details. |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | Document permissions, see [`Permissions`](../../aspose.pdf/permissions/) for details. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Returns OrganizerOptions plugin data collection. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Gets collection of added targets for saving operation results. |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | Owner password. |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | User password. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Adds new data source to the PdfOrganizer plugin data collection. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Adds new data source to the PdfOrganizer plugin data collection. |

### See Also

* class [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


