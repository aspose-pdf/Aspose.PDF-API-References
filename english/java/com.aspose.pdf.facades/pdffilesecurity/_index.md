---
title: PdfFileSecurity
second_title: Aspose.PDF for Java API Reference
description: Represents encrypting or decrypting a Pdf file with owner or user password, changing the security setting and password.
type: docs
weight: 520
url: /java/com.aspose.pdf.facades/pdffilesecurity/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSecurity

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSecurity extends SaveableFacade implements com.aspose.ms.System.IDisposable
```

Represents encrypting or decrypting a Pdf file with owner or user password, changing the security setting and password.

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileSecurity](#PdfFileSecurity--) | Initialize the object of PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-) | Initialize the object of PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-) | Initialize the object of PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-) | Initialize the object of PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-) | Initialize the object of PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.lang.String-java.lang.String-) | Initialize the object of PdfFileSecurity. |

## Methods

| Method | Description |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Initializes the facade. |
| [bindPdf](#bindPdf-java.lang.String-) | Initializes the facade. |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Throws an exception if process failed. string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner"); |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. <p> Throws an exception if process failed. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be // re-assigned. string outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be // re-assigned. string outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [close](#close--) | Closes the facade. |
| [decryptFile](#decryptFile-java.lang.String-) | Decrypts an encrypted Pdf document by owner password. If the document hasn't owner password, it is allow to use user password. Throws an exception if process failed. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass"); |
| [dispose](#dispose--) | Closes the facade. |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Throws exception if process failed. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [getAllowExceptions](#getAllowExceptions--) | If this value set to true, exception will be thrown on operation failure. Else, method returns false on failure and last exception can be checked with LastException property. |
| [getLastException](#getLastException--) | Returns exception which was thrown by last operation. |
| [setAllowExceptions](#setAllowExceptions-boolean-) | If this value set to true, exception will be thrown on operation failure. Else, method returns false on failure and last exception can be checked with LastException property. |
| [setInputFile](#setInputFile-java.lang.String-) | Sets the input file. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setInputStream](#setInputStream-java.io.InputStream-) | Sets the input stream. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setOutputFile](#setOutputFile-java.lang.String-) | Sets the output file. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Sets the output stream. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setPrivilege](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Sets Pdf file security with empty user/owner passwords. The owner password will be added by a random string. Throws an exception if process failed. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre> |
| [setPrivilege](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Sets Pdf file security with original password. Throws an exception if process failed. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre> |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-) | Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced Does not throw an exception if process failed. with a random string if the new owner password is null or empty. string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner"); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Does not throw an exception if process failed. string inFile = ".D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | Changes the user password and password by owner password, allows to reset Pdf document security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Does not throw an exception if process failed. string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES); |
| [tryDecryptFile](#tryDecryptFile-java.lang.String-) | Decrypts an encrypted Pdf document by owner password. If the document hasn't owner password, it is allow to use user password. Does not throw an exception if process failed. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass"); |
| [tryEncryptFile](#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Does not throw an exception if process failed. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); |
| [trySetPrivilege](#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | Sets Pdf file security with original password. Does not throw an exception if process failed. string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print); |

### PdfFileSecurity {#PdfFileSecurity--}
```
public PdfFileSecurity()
```

Initialize the object of PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-}
Initialize the object of PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-}
Initialize the object of PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-}
Initialize the object of PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
Initialize the object of PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.lang.String-java.lang.String-}
Initialize the object of PdfFileSecurity.

### bindPdf {#bindPdf-java.io.InputStream-}
Initializes the facade.

### bindPdf {#bindPdf-java.lang.String-}
Initializes the facade.

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-}
Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Throws an exception if process failed. string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner");

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. <p> Throws an exception if process failed. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be // re-assigned. string outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre>

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be // re-assigned. string outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### close {#close--}
```
public void close()
```

Closes the facade.

### decryptFile {#decryptFile-java.lang.String-}
Decrypts an encrypted Pdf document by owner password. If the document hasn't owner password, it is allow to use user password. Throws an exception if process failed. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass");

### dispose {#dispose--}
```
public void dispose()
```

Closes the facade.

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Throws exception if process failed. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre>

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Throws an exception if process failed. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### getAllowExceptions {#getAllowExceptions--}
```
@Deprecated public final boolean getAllowExceptions()
```

If this value set to true, exception will be thrown on operation failure. Else, method returns false on failure and last exception can be checked with LastException property.

**Returns:**
boolean value @deprecated This property is deprecated and can not be used to allow throwing exceptions.

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Returns exception which was thrown by last operation.

**Returns:**
java.lang.RuntimeException

### setAllowExceptions {#setAllowExceptions-boolean-}
```
@Deprecated public final void setAllowExceptions(boolean value)
```

If this value set to true, exception will be thrown on operation failure. Else, method returns false on failure and last exception can be checked with LastException property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value @deprecated This property is deprecated and can not be used to allow throwing exceptions. |

### setInputFile {#setInputFile-java.lang.String-}
Sets the input file. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setInputStream {#setInputStream-java.io.InputStream-}
Sets the input stream. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setOutputFile {#setOutputFile-java.lang.String-}
Sets the output file. Obsolete("Use save(outputStream) method for getting facade results.")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Sets the output stream. Obsolete("Use save(outputStream) method for getting facade results.")

### setPrivilege {#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Sets Pdf file security with empty user/owner passwords. The owner password will be added by a random string. Throws an exception if process failed. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre>

### setPrivilege {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Sets Pdf file security with original password. Throws an exception if process failed. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre>

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-}
Changes the user password and owner password by owner password, keeps the original security settings. The new user password and the new owner password can be null or empty. The owner password will be replaced Does not throw an exception if process failed. with a random string if the new owner password is null or empty. string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner");

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Changes the user password and password by owner password, allows to reset Pdf documnent security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. Does not throw an exception if process failed. string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
Changes the user password and password by owner password, allows to reset Pdf document security. The new user password and the new owner password can be null or empty. The owner password will be replaced with a random string if the new owner password is null or empty. There are 6 possible combinations of KeySize and Algorithm values. However (KeySize.x40, Algorithm.AES) and (KeySize.x256, Algorithm.RC4) are invalid and corresponding exception will be raised if kit encounters this combination. Does not throw an exception if process failed. string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

### tryDecryptFile {#tryDecryptFile-java.lang.String-}
Decrypts an encrypted Pdf document by owner password. If the document hasn't owner password, it is allow to use user password. Does not throw an exception if process failed. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass");

### tryEncryptFile {#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Encrypts Pdf file with userpassword and ownerpassword and sets the document's privileges to access. The user password and the owner password can be null or empty. The owner password will be replaced with a random string if the input owner password is null or empty. Does not throw an exception if process failed. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);

### trySetPrivilege {#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
Sets Pdf file security with original password. Does not throw an exception if process failed. string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
