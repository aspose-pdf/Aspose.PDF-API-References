---
title: Aspose::Pdf::Facades::PdfFileSecurity class
linktitle: PdfFileSecurity
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileSecurity class. Represents encrypting or decrypting a Pdf file with owner or user password, changing the security setting and password in C++.'
type: docs
weight: 2400
url: /cpp/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class


Represents encrypting or decrypting a [Pdf](../../aspose.pdf/) file with owner or user password, changing the security setting and password.

```cpp
class PdfFileSecurity : public Aspose::Pdf::Facades::SaveableFacade
```

## Methods

| Method | Description |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Initializes the facade. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Initializes the facade. |
| [ChangePassword](./changepassword/)(System::String, System::String, System::String) | Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Throws an exception if process failed. |
| [ChangePassword](./changepassword/)(System::String, System::String, System::String, System::SharedPtr\<DocumentPrivilege\>, KeySize) | Changes the user password and password by owner password, allows to reset [Pdf](../../aspose.pdf/) documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Throws an exception if process failed. |
| [ChangePassword](./changepassword/)(System::String, System::String, System::String, System::SharedPtr\<DocumentPrivilege\>, KeySize, Algorithm) | Changes the user password and password by owner password, allows to reset [Pdf](../../aspose.pdf/) documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. There are 6 possible combinations of [KeySize](../keysize/) and [Algorithm](../algorithm/) values. However ([KeySize.x40](../keysize/), [Algorithm.AES](../algorithm/)) and ([KeySize.x256](../keysize/), [Algorithm.RC4](../algorithm/)) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed. |
| [Close](./close/)() override | Closes the facade. |
| [get_AllowExceptions](./get_allowexceptions/)() | If this value set to true, exception will be thrown on opearation failure. Else, method returns false on failure and last exception can be checked with LastException property. |
| [get_LastException](./get_lastexception/)() const | Returns exception which was thrown by last operation. |
| [MfDecryptFile](./mfdecryptfile/)(System::String) | Decrypts an encrypted [Pdf](../../aspose.pdf/) document by owner password. If the document hasn't owner password, it is allow to use user password. Throws an exception if process failed. |
| [MfEncryptFile](./mfencryptfile/)(System::String, System::String, System::SharedPtr\<DocumentPrivilege\>, KeySize) | Encrypts [Pdf](../../aspose.pdf/) file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Throws exception if process failed. |
| [MfEncryptFile](./mfencryptfile/)(System::String, System::String, System::SharedPtr\<DocumentPrivilege\>, KeySize, Algorithm) | Encrypts [Pdf](../../aspose.pdf/) file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. There are 6 possible combinations of [KeySize](../keysize/) and [Algorithm](../algorithm/) values. However ([KeySize.x40](../keysize/), [Algorithm.AES](../algorithm/)) and ([KeySize.x256](../keysize/), [Algorithm.RC4](../algorithm/)) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed. |
| [PdfFileSecurity](./pdffilesecurity/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) | Initialize the object of [PdfFileSecurity](./) with input and output stream. |
| [PdfFileSecurity](./pdffilesecurity/)(System::String, System::String) | Initializes the object of [PdfFileSecurity](./) with input and output file. |
| [PdfFileSecurity](./pdffilesecurity/)() | Initialize the object of [PdfFileSecurity](./). |
| [PdfFileSecurity](./pdffilesecurity/)(System::SharedPtr\<Aspose::Pdf::Document\>) | Initializes new [PdfFileSecurity](./) object on base of the *document* . |
| [PdfFileSecurity](./pdffilesecurity/)(System::SharedPtr\<Aspose::Pdf::Document\>, System::String) | Initializes new [PdfFileSecurity](./) object on base of the *document* . |
| [PdfFileSecurity](./pdffilesecurity/)(System::SharedPtr\<Aspose::Pdf::Document\>, System::SharedPtr\<System::IO::Stream\>) | Initializes new [PdfFileSecurity](./) object on base of the *document* . |
| [set_AllowExceptions](./set_allowexceptions/)(bool) | If this value set to true, exception will be thrown on opearation failure. Else, method returns false on failure and last exception can be checked with LastException property. |
| [set_InputFile](./set_inputfile/)(System::String) | Sets the input file. |
| [set_InputStream](./set_inputstream/)(System::SharedPtr\<System::IO::Stream\>) | Sets the input stream. |
| [set_OutputFile](./set_outputfile/)(System::String) | Sets the output file. |
| [set_OutputStream](./set_outputstream/)(System::SharedPtr\<System::IO::Stream\>) | Sets the output stream. |
| [SetPrivilege](./setprivilege/)(System::SharedPtr\<DocumentPrivilege\>) | Sets [Pdf](../../aspose.pdf/) file security with empty user/owner passwords. The owner password will be added by a random string. Throws an exception if process failed. |
| [SetPrivilege](./setprivilege/)(System::String, System::String, System::SharedPtr\<DocumentPrivilege\>) | Sets [Pdf](../../aspose.pdf/) file security with original password. Throws an exception if process failed. |
| [TryChangePassword](./trychangepassword/)(System::String, System::String, System::String) | Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced Does not throw an exception if process failed. with a random string if the new owner password is null or empty. |
| [TryChangePassword](./trychangepassword/)(System::String, System::String, System::String, System::SharedPtr\<DocumentPrivilege\>, KeySize) | Changes the user password and password by owner password, allows to reset [Pdf](../../aspose.pdf/) documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Does not throw an exception if process failed. |
| [TryChangePassword](./trychangepassword/)(System::String, System::String, System::String, System::SharedPtr\<DocumentPrivilege\>, KeySize, Algorithm) | Changes the user password and password by owner password, allows to reset [Pdf](../../aspose.pdf/) documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. There are 6 possible combinations of [KeySize](../keysize/) and [Algorithm](../algorithm/) values. However ([KeySize.x40](../keysize/), [Algorithm.AES](../algorithm/)) and ([KeySize.x256](../keysize/), [Algorithm.RC4](../algorithm/)) are invalid and corresponding exception will be raised if kit encounters this combination. Does not throw an exception if process failed. |
| [TryDecryptFile](./trydecryptfile/)(System::String) | Decrypts an encrypted [Pdf](../../aspose.pdf/) document by owner password. If the document hasn't owner password, it is allow to use user password. Does not throw an exception if process failed. |
| [TryEncryptFile](./tryencryptfile/)(System::String, System::String, System::SharedPtr\<DocumentPrivilege\>, KeySize) | Encrypts [Pdf](../../aspose.pdf/) file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Does not throw an exception if process failed. |
| [TrySetPrivilege](./trysetprivilege/)(System::String, System::String, System::SharedPtr\<DocumentPrivilege\>) | Sets [Pdf](../../aspose.pdf/) file security with original password. Does not throw an exception if process failed. |
## See Also

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
