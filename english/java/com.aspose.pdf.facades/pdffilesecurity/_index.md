---
title: PdfFileSecurity
second_title: Aspose.PDF for Java API Reference
description: Represents encrypting or decrypting a Pdf file with owner or user password changing the security setting and password.
type: docs
weight: 44
url: /java/com.aspose.pdf.facades/pdffilesecurity/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public final class PdfFileSecurity extends SaveableFacade implements System.IDisposable
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
| [getAllowExceptions()](#getAllowExceptions--) | If this value set to true, exception will be thrown on operation failure. |
| [setAllowExceptions(boolean value)](#setAllowExceptions-boolean-) | If this value set to true, exception will be thrown on operation failure. |
| [getLastException()](#getLastException--) | Returns exception which was thrown by last operation. |
| [encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize)](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-) | Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. |
| [tryEncryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize)](#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-) | Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. |
| [encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize, int cipher)](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-) | Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. |
| [decryptFile(String ownerPassword)](#decryptFile-java.lang.String-) | Decrypts an encrypted Pdf document by owner password. |
| [tryDecryptFile(String ownerPassword)](#tryDecryptFile-java.lang.String-) | Decrypts an encrypted Pdf document by owner password. |
| [setPrivilege(DocumentPrivilege privilege)](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | Sets Pdf file security with empty user/owner passwords. |
| [setPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege)](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | Sets Pdf file security with original password. |
| [trySetPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege)](#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | Sets Pdf file security with original password. |
| [changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword)](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | Changes the user password and owner password by owner password, keeps the original security settings. |
| [tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword)](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-) | Changes the user password and owner password by owner password, keeps the original security settings. |
| [changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize)](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-) | Changes the user password and password by owner password, allows to reset Pdf documnent security. |
| [tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize)](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-) | Changes the user password and password by owner password, allows to reset Pdf documnent security. |
| [changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher)](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-) | Changes the user password and password by owner password, allows to reset Pdf documnent security. |
| [tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher)](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-) | Changes the user password and password by owner password, allows to reset Pdf document security. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Initializes the facade. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Initializes the facade. |
| [close()](#close--) | Closes the facade. |
| [dispose()](#dispose--) | Closes the facade. |
### PdfFileSecurity(InputStream inputStream, OutputStream outputStream) {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
```
public PdfFileSecurity(InputStream inputStream, OutputStream outputStream)
```


Initialize the object of PdfFileSecurity with input and output stream.

Obsolete("Use constructor without destination.")

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

Obsolete("Use constructor without destination.")

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

Obsolete("Use constructor without destination.")

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

Obsolete("Use constructor without destination.")

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

Obsolete("Use bindPdf(inputStream) method for facade initialization.")

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public void setInputStream(InputStream value)
```


Sets the input stream.

Obsolete("Use bindPdf(inputStream) method for facade initialization.")

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream | InputStream object |

### setOutputFile(String value) {#setOutputFile-java.lang.String-}
```
public void setOutputFile(String value)
```


Sets the output file.

Obsolete("Use save(outputStream) method for getting facade results.")

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### setOutputStream(OutputStream value) {#setOutputStream-java.io.OutputStream-}
```
public void setOutputStream(OutputStream value)
```


Sets the output stream.

Obsolete("Use save(outputStream) method for getting facade results.")

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.OutputStream | OutputStream object |

### getAllowExceptions() {#getAllowExceptions--}
```
public final boolean getAllowExceptions()
```


If this value set to true, exception will be thrown on operation failure. Else, method returns false on failure and last exception can be checked with LastException property.

**Returns:**
boolean - boolean value
### setAllowExceptions(boolean value) {#setAllowExceptions-boolean-}
```
public final void setAllowExceptions(boolean value)
```


If this value set to true, exception will be thrown on operation failure. Else, method returns false on failure and last exception can be checked with LastException property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getLastException() {#getLastException--}
```
public final RuntimeException getLastException()
```


Returns exception which was thrown by last operation.

**Returns:**
java.lang.RuntimeException - java.lang.RuntimeException
### encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize) {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-}
```
public boolean encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize)
```


Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Throws exception if process failed.

--------------------

```
String inFile = "input.pdf"; // The TestPath may be
 															// re-assigned.
 String outFile = "output.pdf"; // The TestPath may be
 															// re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print,
 		KeySize.x256);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | java.lang.String | User password. |
| ownerPassword | java.lang.String | Owner password. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Set privilege. |
| keySize | int | KeySize.x40 for 40 bits encryption, KeySize.x128 for 128 bits encryption and KeySize.x256 for 256 bits encryption. |

**Returns:**
boolean - True for success.
### tryEncryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize) {#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-}
```
public final boolean tryEncryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize)
```


Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Does not throw an exception if process failed.

```
string inFile = "input.pdf"; //The TestPath may be re-assigned.
 string outFile = "output.pdf"; //The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);
```

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


Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed.

--------------------

```
String inFile = "input.pdf"; // The TestPath may be
 															// re-assigned.
 String outFile = "output.pdf"; // The TestPath may be
 															// re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print,
 		KeySize.x256, Algorithm.AES);
```

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
public final boolean decryptFile(String ownerPassword)
```


Decrypts an encrypted Pdf document by owner password. If the document hasn't owner password, it is allow to use user password. Throws an exception if process failed.

```
string inFile = "input.pdf"; //The TestPath may be re-assigned.
 string outFile = "output.pdf"; //The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 fileSecurity.decryptFile("ownerpass");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | java.lang.String | Owner password. |

**Returns:**
boolean - True for success.
### tryDecryptFile(String ownerPassword) {#tryDecryptFile-java.lang.String-}
```
public final boolean tryDecryptFile(String ownerPassword)
```


Decrypts an encrypted Pdf document by owner password. If the document hasn't owner password, it is allow to use user password. Does not throw an exception if process failed.

```
string inFile = "input.pdf"; //The TestPath may be re-assigned.
 string outFile = "output.pdf"; //The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 bool result = fileSecurity.TryDecryptFile("ownerpass");
```

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


Sets Pdf file security with empty user/owner passwords. The owner password will be added by a random string. Throws an exception if process failed.

--------------------

```
string inFile = "input.pdf"; // The TestPath may be re-assigned.
 string outFile = "output.pdf"; // The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.setPrivilege(DocumentPrivilege.Print);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Set privilege. |

**Returns:**
boolean - True for success.
### setPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege) {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
```
public boolean setPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege)
```


Sets Pdf file security with original password. Throws an exception if process failed.

--------------------

```
string inFile = "input.pdf"; // The TestPath may be re-assigned.
 string outFile = "output.pdf"; // The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint());
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | java.lang.String | Original user password. |
| ownerPassword | java.lang.String | Original owner password. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Set privilege. |

**Returns:**
boolean - True for success.
### trySetPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege) {#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
```
public final boolean trySetPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege)
```


Sets Pdf file security with original password. Does not throw an exception if process failed.

```
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
```

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
public final boolean changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword)
```


Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Throws an exception if process failed.

```
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
  string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
  PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
  fileSecurity.changePassword("owner","newuser","newowner");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | java.lang.String | Original Owner password. |
| newUserPassword | java.lang.String | New User password. |
| newOwnerPassword | java.lang.String | New Owner password. |

**Returns:**
boolean - True for success.
### tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword) {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-}
```
public final boolean tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword)
```


Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced Does not throw an exception if process failed. with a random string if the new owner password is null or empty.

```
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
  string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
  PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
  bool result = fileSecurity.tryChangePassword("owner","newuser","newowner");
```

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


Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Throws an exception if process failed.

--------------------

```
string inFile = "input.pdf"; // The TestPath may be
 														// re-assigned.
 string outFile = "output.pdf"; // The TestPath may be
 															// re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.changePassword("owner", "newuser", "newowner",
 		DocumentPrivilege.Print, KeySize.x256);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | java.lang.String | Original owner password. |
| newUserPassword | java.lang.String | New User password. |
| newOwnerPassword | java.lang.String | New Owner password. |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | Reset security. |
| keySize | int | KeySize.x40 for 40 bits encryption, KeySize.x128 for 128 bits encryption and KeySize.x256 for 256 bits encryption. |

**Returns:**
boolean - True for success.
### tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize) {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-}
```
public final boolean tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize)
```


Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Does not throw an exception if process failed.

```
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);
```

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


Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed.

--------------------

```
string inFile = "input.pdf"; // The TestPath may be
 														// re-assigned.
 string outFile = "output.pdf"; // The TestPath may be
 															// re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.changePassword("owner", "newuser", "newowner",
 		DocumentPrivilege.Print, KeySize.x256, Algorithm.AES);
```

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
boolean - True for success.
### tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher) {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-}
```
public final boolean tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher)
```


Changes the user password and password by owner password, allows to reset Pdf document security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Does not throw an exception if process failed.

```
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);
```

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
### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of PDF file. |

### close() {#close--}
```
public void close()
```


Closes the facade.

### dispose() {#dispose--}
```
public void dispose()
```


Closes the facade.

