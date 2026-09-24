---
title: "ICustomSecurityHandler Interface"
linktitle: "ICustomSecurityHandler"
articleTitle: "ICustomSecurityHandler"
second_title: "Aspose.PDF for .NET"
description: "The custom security handler interface."
type: docs
weight: 70
url: "/net/aspose.pdf.security/icustomsecurityhandler/"
product_version: "26.9.0"
---
## ICustomSecurityHandler interface

The custom security handler interface.

```csharp
public interface ICustomSecurityHandler
```

## Properties

| Name | Description |
| --- | --- |
| [Filter](./filter/) { get; } | Gets the filter name. |
| [KeyLength](./keylength/) { get; } | Gets the key length. |
| [Revision](./revision/) { get; } | Gets the handler or encryption algorithm revision. |
| [SubFilter](./subfilter/) { get; } | Gets the sub-filter name. |
| [Version](./version/) { get; } | Gets the handler or encryption algorithm version. |

## Methods

| Name | Description |
| --- | --- |
| [CalculateEncryptionKey](./calculateencryptionkey/)(*string*) | Calculate the EncryptionKey. Generally the key is calculated based on the UserKey. |
| [Decrypt](./decrypt/)(*byte[], int, int, byte[]*) | Decrypt the data array. |
| [Encrypt](./encrypt/)(*byte[], int, int, byte[]*) | Encrypt the data array. |
| [EncryptPermissions](./encryptpermissions/)(*int*) | Encrypt the document's permissions field. The result will be written to the Perms encryption dictionary field. |
| [GetOwnerKey](./getownerkey/)(*string, string*) | Creates an encoded array based on passwords that will be written to the O field of the encryption dictionary. |
| [GetUserKey](./getuserkey/)(*string*) | Creates an encoded array based on the user's password. |
| [Initialize](./initialize/)(*EncryptionParameters*) | Called to initialize the current instance for encryption. |
| [IsOwnerPassword](./isownerpassword/)(*string*) | Check if the password is the document owner's password. |
| [IsUserPassword](./isuserpassword/)(*string*) | Check if the password belongs to the user (password for opening the document). |

### See Also

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)

