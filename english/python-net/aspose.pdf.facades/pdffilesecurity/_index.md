---
title: PdfFileSecurity
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents encrypting or decrypting a Pdf file with owner or user password, changing the security setting and password.
type: docs
weight: 300
url: /python-net/aspose.pdf.facades/pdffilesecurity/
---

## PdfFileSecurity class

Represents encrypting or decrypting a Pdf file with owner or user password, changing the security setting and password.

The PdfFileSecurity type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PdfFileSecurity(input_stream, output_stream)|Initializes a new instance of the PdfFileSecurity class|
|PdfFileSecurity(input_file, output_file)|Initializes a new instance of the PdfFileSecurity class|
|PdfFileSecurity()|Initialize the object of PdfFileSecurity.|
|PdfFileSecurity(document)|Initializes a new instance of the PdfFileSecurity class|
|PdfFileSecurity(document, output_file)|Initializes a new instance of the PdfFileSecurity class|
|PdfFileSecurity(document, output_stream)|Initializes a new instance of the PdfFileSecurity class|
## Properties
| Name | Description |
| :- | :- |
|document|Gets the document facade is working on.|
|allow_exceptions|If this value set to true, exception will be thrown on opearation failure. Else, method returns false on failure and last exception can be checked with LastException property.|
## Methods
| Name | Description |
| :- | :- |
|bind_pdf(src_file)|Initializes the facade.|
|bind_pdf(src_stream)|Initializes the facade.|
|bind_pdf(src_doc)|Binds PDF document for editing.|
|save(dest_file)|Saves the PDF document to the specified file.|
|save(dest_stream)|Saves the PDF document to the specified stream.|
|encrypt_file(user_password, owner_password, privilege, key_size)|Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access.<br/>            The user password and the owner password can be null or empty. The owner password will be replaced <br/>            with a random string if the input owner password is null or empty.<br/>            Throws exception if process failed.|
|encrypt_file(user_password, owner_password, privilege, key_size, cipher)|Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access.<br/>            The user password and the owner password can be null or empty. The owner password will be replaced <br/>            with a random string if the input owner password is null or empty.<br/>            There are 6 possible combinations of KeySize and Algorithm values. <br/>            However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding <br/>            exception will be raised if kit encounters this combination.<br/>            Throws an exception if process failed.|
|set_privilege(privilege)|Sets Pdf file security with empty user/owner passwords.<br/>            The owner password will be added by a random string.<br/>            Throws an exception if process failed.|
|set_privilege(user_password, owner_password, privilege)|Sets Pdf file security with original password.<br/>            Throws an exception if process failed.|
|change_password(owner_password, new_user_password, new_owner_password)|Changes the user password and owner password by owner password, keeps the original security settings.<br/>             The new user password and the new owner password can be null or empty. The owner password will be replaced <br/>             with a random string if the new owner password is null or empty.<br/>             Throws an exception if process failed.|
|change_password(owner_password, new_user_password, new_owner_password, privilege, key_size)|Changes the user password and password by owner password, allows to reset Pdf documnent security.<br/>            The new user password and the new owner password can be null or empty. The owner password will be replaced <br/>            with a random string if the new owner password is null or empty.<br/>            Throws an exception if process failed.|
|change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher)|Changes the user password and password by owner password, allows to reset Pdf documnent security.<br/>            The new user password and the new owner password can be null or empty. The owner password will be replaced <br/>            with a random string if the new owner password is null or empty.<br/>            There are 6 possible combinations of KeySize and Algorithm values. <br/>            However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding <br/>            exception will be raised if kit encounters this combination.<br/>            Throws an exception if process failed.|
|try_change_password(owner_password, new_user_password, new_owner_password)|Changes the user password and owner password by owner password, keeps the original security settings.<br/>             The new user password and the new owner password can be null or empty. The owner password will be replaced <br/>             Does not throw an exception if process failed.<br/>             with a random string if the new owner password is null or empty.|
|try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size)|Changes the user password and password by owner password, allows to reset Pdf documnent security.<br/>            The new user password and the new owner password can be null or empty. The owner password will be replaced <br/>            with a random string if the new owner password is null or empty.<br/>            Does not throw an exception if process failed.|
|try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher)|Changes the user password and password by owner password, allows to reset Pdf documnent security.<br/>            The new user password and the new owner password can be null or empty. The owner password will be replaced <br/>            with a random string if the new owner password is null or empty.<br/>            There are 6 possible combinations of KeySize and Algorithm values. <br/>            However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding <br/>            exception will be raised if kit encounters this combination.<br/>            Does not throw an exception if process failed.|
|close()|Closes the facade.|
|try_encrypt_file(user_password, owner_password, privilege, key_size)|Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access.<br/>            The user password and the owner password can be null or empty. The owner password will be replaced <br/>            with a random string if the input owner password is null or empty.<br/>            Does not throw an exception if process failed.|
|decrypt_file(owner_password)|Decrypts an encrypted Pdf document by owner password. <br/>            If the document hasn't owner password, it is allow to use user password.<br/>            Throws an exception if process failed.|
|try_decrypt_file(owner_password)|Decrypts an encrypted Pdf document by owner password. <br/>            If the document hasn't owner password, it is allow to use user password.<br/>            Does not throw an exception if process failed.|
|try_set_privilege(user_password, owner_password, privilege)|Sets Pdf file security with original password.<br/>            Does not throw an exception if process failed.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

