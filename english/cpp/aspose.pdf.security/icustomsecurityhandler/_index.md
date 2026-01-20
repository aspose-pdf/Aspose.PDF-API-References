---
title: Aspose::Pdf::Security::ICustomSecurityHandler class
linktitle: ICustomSecurityHandler
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Security::ICustomSecurityHandler class. The custom security handler interface in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler class


The custom security handler interface.

```cpp
class ICustomSecurityHandler : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [CalculateEncryptionKey](./calculateencryptionkey/)(System::String) | Calculate the EncryptionKey. Generally the key is calculated based on the UserKey. You can use values from EncryptionParams, which contains the current parameters at the time of the call. This value is passed as the key argument in [Encrypt](./encrypt/) and [Decrypt](./decrypt/). |
| virtual [Decrypt](./decrypt/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>) | Decrypt the data array. |
| virtual [Encrypt](./encrypt/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>) | Encrypt the data array. |
| virtual [EncryptPermissions](./encryptpermissions/)(int32_t) | Encrypt the document's permissions field. The result will be written to the Perms encryption dictionary field. When opening a document, the value can be obtained in [EncryptionParameters](../encryptionparameters/) via the Perms field. Allows you to check if the document permissions have changed. |
| virtual [get_Filter](./get_filter/)() | Gets the filter name. |
| virtual [get_KeyLength](./get_keylength/)() | Gets the key length. |
| virtual [get_Revision](./get_revision/)() | Gets the handler or encryption algorithm revision. |
| virtual [get_SubFilter](./get_subfilter/)() | Gets the sub-filter name. |
| virtual [get_Version](./get_version/)() | Gets the handler or encryption algorithm version. |
| virtual [GetOwnerKey](./getownerkey/)(System::String, System::String) | Creates an encoded array based on passwords that will be written to the O field of the encryption dictionary. Should only rely on the arguments passed. The user password can be calculated from this field using the owner password. Called during encryption to prepare it and populate the encryption dictionary. The value will be available in [CalculateEncryptionKey](./calculateencryptionkey/) to get the key from the UserKey. The passwords specified by the user when calling document encryption will be passed. Passwords may not be specified or only one may be specified. |
| virtual [GetUserKey](./getuserkey/)(System::String) | Creates an encoded array based on the user's password. This value is typically used to check if the password belongs to the user or owner, and to get the encryption key. Called during encryption to prepare it and populate the encryption dict. The user-specified password is passed as an argument when calling document encryption. |
| virtual [Initialize](./initialize/)(System::SharedPtr\<EncryptionParameters\>) | Called to initialize the current instance for encryption. [Note](../../aspose.pdf/note/) that when encrypting, it will be filled with the data of the transferred properties [ICustomSecurityHandler](./), and when opening the document from the encryption dictionary. If the method is called during new encryption, then [EncryptionParameters::UserKey](../) and [EncryptionParameters::OwnerKey](../) will be null. |
| virtual [IsOwnerPassword](./isownerpassword/)(System::String) | Check if the password is the document owner's password. The method is called after Initialize. The method call is used in the PDF API. |
| virtual [IsUserPassword](./isuserpassword/)(System::String) | Check if the password belongs to the user (password for opening the document). The method is called after Initialize. The method call is used in the PDF API. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security](../)
* Library [Aspose.PDF for C++](../../)
