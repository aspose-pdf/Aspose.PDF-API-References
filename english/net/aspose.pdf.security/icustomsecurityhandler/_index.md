---
title: Interface ICustomSecurityHandler
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ICustomSecurityHandler interface. The custom security handler interface
type: docs
weight: 10150
url: /net/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler interface

The custom security handler interface.

```csharp
public interface ICustomSecurityHandler
```

## Properties

| Name | Description |
| --- | --- |
| [Filter](../../aspose.pdf.security/icustomsecurityhandler/filter/) { get; } | Gets the filter name. |
| [KeyLength](../../aspose.pdf.security/icustomsecurityhandler/keylength/) { get; } | Gets the key length. |
| [Revision](../../aspose.pdf.security/icustomsecurityhandler/revision/) { get; } | Gets the handler or encryption algorithm revision. |
| [SubFilter](../../aspose.pdf.security/icustomsecurityhandler/subfilter/) { get; } | Gets the sub-filter name. |
| [Version](../../aspose.pdf.security/icustomsecurityhandler/version/) { get; } | Gets the handler or encryption algorithm version. |

## Methods

| Name | Description |
| --- | --- |
| [CalculateEncryptionKey](../../aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/)(string) | Calculate the EncryptionKey. Generally the key is calculated based on the UserKey. You can use values from EncryptionParams, which contains the current parameters at the time of the call. This value is passed as the key argument in [`Encrypt`](./encrypt/) and [`Decrypt`](./decrypt/). |
| [Decrypt](../../aspose.pdf.security/icustomsecurityhandler/decrypt/)(byte[], int, int, byte[]) | Decrypt the data array. |
| [Encrypt](../../aspose.pdf.security/icustomsecurityhandler/encrypt/)(byte[], int, int, byte[]) | Encrypt the data array. |
| [EncryptPermissions](../../aspose.pdf.security/icustomsecurityhandler/encryptpermissions/)(int) | Encrypt the document's permissions field. The result will be written to the Perms encryption dictionary field. When opening a document, the value can be obtained in [`EncryptionParameters`](../encryptionparameters/) via the Perms field. Allows you to check if the document permissions have changed. |
| [GetOwnerKey](../../aspose.pdf.security/icustomsecurityhandler/getownerkey/)(string, string) | Creates an encoded array based on passwords that will be written to the O field of the encryption dictionary. Should only rely on the arguments passed. The user password can be calculated from this field using the owner password. Called during encryption to prepare it and populate the encryption dictionary. The value will be available in [`CalculateEncryptionKey`](./calculateencryptionkey/) to get the key from the UserKey. The passwords specified by the user when calling document encryption will be passed. Passwords may not be specified or only one may be specified. |
| [GetUserKey](../../aspose.pdf.security/icustomsecurityhandler/getuserkey/)(string) | Creates an encoded array based on the user's password. This value is typically used to check if the password belongs to the user or owner, and to get the encryption key. Called during encryption to prepare it and populate the encryption dict. The user-specified password is passed as an argument when calling document encryption. |
| [Initialize](../../aspose.pdf.security/icustomsecurityhandler/initialize/)(EncryptionParameters) | Called to initialize the current instance for encryption. Note that when encrypting, it will be filled with the data of the transferred properties `ICustomSecurityHandler`, and when opening the document from the encryption dictionary. If the method is called during new encryption, then [`UserKey`](../encryptionparameters/userkey/) and [`OwnerKey`](../encryptionparameters/ownerkey/) will be null. |
| [IsOwnerPassword](../../aspose.pdf.security/icustomsecurityhandler/isownerpassword/)(string) | Check if the password is the document owner's password. The method is called after Initialize. The method call is used in the PDF API. |
| [IsUserPassword](../../aspose.pdf.security/icustomsecurityhandler/isuserpassword/)(string) | Check if the password belongs to the user (password for opening the document). The method is called after Initialize. The method call is used in the PDF API. |

### See Also

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


