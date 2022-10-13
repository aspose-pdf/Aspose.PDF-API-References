---
title: PdfFileSecurity
second_title: Aspose.PDF for Java API Reference
description: Represents encrypting or decrypting a Pdf file with owner or user password changing the security setting and password.
type: docs
weight: 39
url: /java/com.aspose.pdf.facades/pdffilesecurity/
---
**Inheritance:**
java.lang.Object
```
public final class PdfFileSecurity
```

Represents encrypting or decrypting a Pdf file with owner or user password, changing the security setting and password.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileSecurity(InputStream inputStream, OutputStream outputStream)](#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-) | Initialize the object of PdfFileSecurity with input and output stream. |
| [PdfFileSecurity(String inputFile, String outputFile)](#PdfFileSecurity-java.lang.String-java.lang.String-) | Initializes the object of PdfFileSecurity with input and output file. |
| [PdfFileSecurity()](#PdfFileSecurity--) | Initialize the object of PdfFileSecurity. |
| [PdfFileSecurity(IDocument document)](#PdfFileSecurity-com.aspose.pdf.IDocument-) | Initializes new  PdfFileSecurity  object on base of the  document . |
| [PdfFileSecurity(IDocument document, String outputFile)](#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-) | Initializes new  PdfFileSecurity  object on base of the  document . |
| [PdfFileSecurity(IDocument document, OutputStream outputStream)](#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-) | Initializes new  PdfFileSecurity  object on base of the  document . |
## Methods

| Method | Description |
| --- | --- |
| [setInputFile(String value)](#setInputFile-java.lang.String-) | Sets the input file. |
| [setInputStream(InputStream value)](#setInputStream-java.io.InputStream-) | Sets the input stream. |
| [setOutputFile(String value)](#setOutputFile-java.lang.String-) | Sets the output file. |
| [setOutputStream(OutputStream value)](#setOutputStream-java.io.OutputStream-) | Sets the output stream. |
| [encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize)](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-) | Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. |
| [encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize, int cipher)](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-) | Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. |
| [decryptFile(String ownerPassword)](#decryptFile-java.lang.String-) | Decrypts an encrypted Pdf document by owner password. |
| [setPrivilege(DocumentPrivilege privilege)](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | Sets Pdf file security without being encrypted. |
| [setPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege)](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | Sets Pdf file security with original password. |
| [changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword)](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | Changes the user password and owner password by owner password, keeps the original security settings. |
| [changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize)](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-) | Changes the user password and password by owner password, allows to reset Pdf documnent security. |
| [changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher)](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-) | Changes the user password and password by owner password, allows to reset Pdf documnent security. |
| [getDocument()](#getDocument--) | Gets the document  PdfFileSecurity  is working on. |
| [close()](#close--) |  |
| [dispose()](#dispose--) |  |
### PdfFileSecurity(InputStream inputStream, OutputStream outputStream) {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
```
public PdfFileSecurity(InputStream inputStream, OutputStream outputStream)
```


Initialize the object of PdfFileSecurity with input and output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input Pdf Stream. |
| outputStream | java.io.OutputStream | Output Pdf Stream. |

### PdfFileSecurity(String inputFile, String outputFile) {#PdfFileSecurity-java.lang.String-java.lang.String-}
```
public PdfFileSecurity(String inputFile, String outputFile)
```


Initializes the object of PdfFileSecurity with input and output file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source input Pdf file. |
| outputFile | java.lang.String | Output Pdf file. |

### PdfFileSecurity() {#PdfFileSecurity--}
```
public PdfFileSecurity()
```


Initialize the object of PdfFileSecurity.

### PdfFileSecurity(IDocument document) {#PdfFileSecurity-com.aspose.pdf.IDocument-}
```
public PdfFileSecurity(IDocument document)
```


Initializes new  PdfFileSecurity  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### PdfFileSecurity(IDocument document, String outputFile) {#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-}
```
public PdfFileSecurity(IDocument document, String outputFile)
```


Initializes new  PdfFileSecurity  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| outputFile | java.lang.String | Output Pdf file. |

### PdfFileSecurity(IDocument document, OutputStream outputStream) {#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public PdfFileSecurity(IDocument document, OutputStream outputStream)
```


Initializes new  PdfFileSecurity  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| outputStream | java.io.OutputStream | Output Pdf Stream. |

### setInputFile(String value) {#setInputFile-java.lang.String-}
```
public void setInputFile(String value)
```


Sets the input file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public void setInputStream(InputStream value)
```


Sets the input stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream |  |

### setOutputFile(String value) {#setOutputFile-java.lang.String-}
```
public void setOutputFile(String value)
```


Sets the output file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setOutputStream(OutputStream value) {#setOutputStream-java.io.OutputStream-}
```
public void setOutputStream(OutputStream value)
```


Sets the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.OutputStream |  |

### encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize) {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-}
```
public boolean encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize)
```


Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty.

--------------------

> ```
> String inFile = "..\\AsposePdfKitExample\\example1.pdf"; // The TestPath may be
>  															// re-assigned.
>  String outFile = "..\\AsposePdfKitExample\\Kit0401.pdf"; // The TestPath may be
>  															// re-assigned.
>  PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
>  fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print,
>  		KeySize.x256);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | java.lang.String | User password. |
| ownerPassword | java.lang.String | Owner password. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Set privilege. |
| keySize | int | KeySize.x40 for 40 bits encryption, KeySize.x128 for 128 bits encryption and KeySize.x256 for 256 bits encryption. |

**Returns:**
boolean - True for success, or false.
### encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize, int cipher) {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-}
```
public boolean encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize, int cipher)
```


Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination.

--------------------

> ```
> String inFile = "..\\AsposePdfKitExample\\example1.pdf"; // The TestPath may be
>  															// re-assigned.
>  String outFile = "..\\AsposePdfKitExample\\Kit0401.pdf"; // The TestPath may be
>  															// re-assigned.
>  PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
>  fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print,
>  		KeySize.x256, Algorithm.AES);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | java.lang.String | User password. |
| ownerPassword | java.lang.String | Owner password. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Set privilege. |
| keySize | int | KeySize.x40 for 40 bits encryption, KeySize.x128 for 128 bits encryption and KeySize.x256 for 256 bits encryption. |
| cipher | int | Algorithm.AES to encrypt using AES algorithm or Algorithm.RC4 for RC4 encryption. |

**Returns:**
boolean - True for success, or false.
### decryptFile(String ownerPassword) {#decryptFile-java.lang.String-}
```
public boolean decryptFile(String ownerPassword)
```


Decrypts an encrypted Pdf document by owner password. If the document hasn't owner password, it is allow to use user password.

--------------------

> ```
> string inFile = "..\\AsposePdfKitExample\\Kit0401.pdf"; // The TestPath may be
>  														// re-assigned.
>  string outFile = "..\\AsposePdfKitExample\\Kit0404.pdf"; // The TestPath may be
>  															// re-assigned.
>  PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
>  fileSecurity.DecryptFile("ownerpass");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | java.lang.String | Owner password. |

**Returns:**
boolean - True for success,or false.
### setPrivilege(DocumentPrivilege privilege) {#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-}
```
public boolean setPrivilege(DocumentPrivilege privilege)
```


Sets Pdf file security without being encrypted. The owner password will be added by a random string.

--------------------

> ```
> string inFile = "..\\AsposePdfKitExample\\example1.pdf"; // The TestPath may be
>  															// re-assigned.
>  string outFile = "..\\AsposePdfKitExample\\Kit0405.pdf"; // The TestPath may be
>  															// re-assigned.
>  PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
>  fileSecurity.SetPrivilege(DocumentPrivilege.Print);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Set privilege. |

**Returns:**
boolean - True for success, or false.
### setPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege) {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
```
public boolean setPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege)
```


Sets Pdf file security with original password.

--------------------

> ```
> string inFile = "..\\AsposePdfKitExample\\example1.pdf"; // The TestPath may be
>  															// re-assigned.
>  string outFile = "..\\AsposePdfKitExample\\Kit0405.pdf"; // The TestPath may be
>  															// re-assigned.
>  PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
>  fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | java.lang.String | Original user password. |
| ownerPassword | java.lang.String | Original owner password. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Set privilege. |

**Returns:**
boolean - True for success, or false.
### changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword) {#changePassword-java.lang.String-java.lang.String-java.lang.String-}
```
public boolean changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword)
```


Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty.

--------------------

> ```
> string inFile = "..\\AsposePdfKitExample\\Kit0406.pdf"; // The TestPath may be
>  														// re-assigned.
>  string outFile = "..\\AsposePdfKitExample\\Kit0407.pdf"; // The TestPath may be
>  															// re-assigned.
>  PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
>  fileSecurity.ChangePassword("owner", "newuser", "newowner");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | java.lang.String | Original Owner password. |
| newUserPassword | java.lang.String | New User password. |
| newOwnerPassword | java.lang.String | New Owner password. |

**Returns:**
boolean - True for success,or false.
### changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize) {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-}
```
public boolean changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize)
```


Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty.

--------------------

> ```
> string inFile = "..\\AsposePdfKitExample\\Kit0401.pdf"; // The TestPath may be
>  														// re-assigned.
>  string outFile = "..\\AsposePdfKitExample\\Kit0407.pdf"; // The TestPath may be
>  															// re-assigned.
>  PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
>  fileSecurity.ChangePassword("owner", "newuser", "newowner",
>  		DocumentPrivilege.Print, KeySize.x256);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | java.lang.String | Original owner password. |
| newUserPassword | java.lang.String | New User password. |
| newOwnerPassword | java.lang.String | New Owner password. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Reset security. |
| keySize | int | KeySize.x40 for 40 bits encryption, KeySize.x128 for 128 bits encryption and KeySize.x256 for 256 bits encryption. |

**Returns:**
boolean - True for success, or false.
### changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher) {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-}
```
public boolean changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher)
```


Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination.

--------------------

> ```
> string inFile = "..\\AsposePdfKitExample\\Kit0401.pdf"; // The TestPath may be
>  														// re-assigned.
>  string outFile = "..\\AsposePdfKitExample\\Kit0407.pdf"; // The TestPath may be
>  															// re-assigned.
>  PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
>  fileSecurity.ChangePassword("owner", "newuser", "newowner",
>  		DocumentPrivilege.Print, KeySize.x256, Algorithm.AES);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | java.lang.String | Original owner password. |
| newUserPassword | java.lang.String | New User password. |
| newOwnerPassword | java.lang.String | New Owner password. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Reset security. |
| keySize | int | KeySize.x40 for 40 bits encryption, KeySize.x128 for 128 bits encryption and KeySize.x256 for 256 bits encryption. |
| cipher | int | Algorithm.AES to encrypt using AES algorithm or Algorithm.RC4 for RC4 encryption. |

**Returns:**
boolean - True for success, or false.
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Gets the document  PdfFileSecurity  is working on.

**Returns:**
[IDocument](../../com.aspose.pdf/idocument)
### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public void dispose()
```




