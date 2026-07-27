---
title: "PdfFileSecurity"
linktitle: "PdfFileSecurity"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a criptografia ou descriptografia de um arquivo PDF com senha de proprietário ou de usuário, alterando as configurações de segurança e a senha."
type: docs
weight: 520
url: /pt/java/com.aspose.pdf.facades/pdffilesecurity/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSecurity

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSecurity extends SaveableFacade implements com.aspose.ms.System.IDisposable
```

Representa a criptografia ou descriptografia de um arquivo PDF com senha de proprietário ou de usuário, alterando as configurações de segurança e a senha.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfFileSecurity](#PdfFileSecurity--) | Inicialize o objeto de PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-) | Inicialize o objeto de PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-) | Inicialize o objeto de PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-) | Inicialize o objeto de PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-) | Inicialize o objeto de PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.lang.String-java.lang.String-) | Inicialize o objeto de PdfFileSecurity. |

## Métodos

| Método | Descrição |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Inicializa a fachada. |
| [bindPdf](#bindPdf-java.lang.String-) | Inicializa a fachada. |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | Altera a senha de usuário e a senha do proprietário usando a senha do proprietário, mantendo as configurações de segurança originais. A nova senha de usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Lança uma exceção se o processo falhar. string inFile = "D:\\\\input.pdf"; //O TestPath pode ser reatribuído. string outFile = "D:\\\\output.pdf"; //O TestPath pode ser reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner"); |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Altera a senha de usuário e a senha do proprietário usando a senha do proprietário, permitindo redefinir a segurança do documento Pdf. A nova senha de usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. <p> Lança uma exceção se o processo falhar. </p> <hr> <pre> string inFile = "input.pdf"; // O TestPath pode ser // reatribuído. string outFile = "output.pdf"; // O TestPath pode ser // reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Altera a senha de usuário e a senha do proprietário usando a senha do proprietário, permitindo redefinir a segurança do documento Pdf. A nova senha de usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Existem 6 combinações possíveis de valores de KeySize e Algorithm. No entanto, (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) são inválidos e a exceção correspondente será lançada se o kit encontrar essa combinação. Lança uma exceção se o processo falhar. </p> <hr> <pre> string inFile = "input.pdf"; // O TestPath pode ser // reatribuído. string outFile = "output.pdf"; // O TestPath pode ser // reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [close](#close--) | Fecha a fachada. |
| [decryptFile](#decryptFile-java.lang.String-) | Descriptografa um documento Pdf criptografado usando a senha do proprietário. Se o documento não possuir senha do proprietário, é permitido usar a senha de usuário. Lança uma exceção se o processo falhar. string inFile = "input.pdf"; //O TestPath pode ser reatribuído. string outFile = "output.pdf"; //O TestPath pode ser reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass"); |
| [dispose](#dispose--) | Fecha a fachada. |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Criptografa o arquivo Pdf com senha de usuário e senha de proprietário e define as permissões do documento para acesso. A senha de usuário e a senha de proprietário podem ser nulas ou vazias. A senha de proprietário será substituída por uma string aleatória se a senha de proprietário fornecida for nula ou vazia. Lança uma exceção se o processo falhar. </p> <hr> <pre> String inFile = "input.pdf"; // O TestPath pode ser // reatribuído. String outFile = "output.pdf"; // O TestPath pode ser // reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Criptografa o arquivo Pdf com userpassword e ownerpassword e define os privilégios do documento para acesso. A senha do usuário e a senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a senha do proprietário de entrada for nula ou vazia. Existem 6 combinações possíveis de valores de KeySize e Algorithm. No entanto, (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) são inválidos e a exceção correspondente será lançada se o kit encontrar essa combinação. Lança uma exceção se o processo falhar. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [getAllowExceptions](#getAllowExceptions--) | Se este valor for definido como true, uma exceção será lançada em caso de falha na operação. Caso contrário, o método retorna false na falha e a última exceção pode ser verificada com a propriedade LastException. |
| [getLastException](#getLastException--) | Retorna a exceção que foi lançada pela última operação. |
| [setAllowExceptions](#setAllowExceptions-boolean-) | Se este valor for definido como true, uma exceção será lançada em caso de falha na operação. Caso contrário, o método retorna false na falha e a última exceção pode ser verificada com a propriedade LastException. |
| [setInputFile](#setInputFile-java.lang.String-) | Define o arquivo de entrada. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setInputStream](#setInputStream-java.io.InputStream-) | Define o fluxo de entrada. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setOutputFile](#setOutputFile-java.lang.String-) | Define o arquivo de saída. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Define o fluxo de saída. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setPrivilege](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Define a segurança do arquivo Pdf com senhas de usuário/proprietário vazias. A senha do proprietário será adicionada por uma string aleatória. Lança uma exceção se o processo falhar. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre> |
| [setPrivilege](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Define a segurança do arquivo Pdf com a senha original. Lança uma exceção se o processo falhar. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre> |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-) | Altera a senha do usuário e a senha do proprietário usando a senha do proprietário, mantendo as configurações de segurança originais. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Não lança uma exceção se o processo falhar. string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner"); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Altera a senha do usuário e a senha do proprietário usando a senha do proprietário, permitindo redefinir a segurança do documento Pdf. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Não lança uma exceção se o processo falhar. string inFile = ".D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | Altera a senha do usuário e a senha do proprietário usando a senha do proprietário, permite redefinir a segurança do documento Pdf. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Existem 6 combinações possíveis de valores de KeySize e Algorithm. No entanto, (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) são inválidas e a exceção correspondente será lançada se o kit encontrar essa combinação. Não lança uma exceção se o processo falhar. string inFile = "D:\\\\input.pdf"; //O TestPath pode ser reatribuído. string outFile = "D:\\\\output.pdf"; //O TestPath pode ser reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES); |
| [tryDecryptFile](#tryDecryptFile-java.lang.String-) | Descriptografa um documento Pdf criptografado usando a senha do proprietário. Se o documento não possuir senha do proprietário, é permitido usar a senha do usuário. Não lança uma exceção se o processo falhar. string inFile = "input.pdf"; //O TestPath pode ser reatribuído. string outFile = "output.pdf"; //O TestPath pode ser reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass"); |
| [tryEncryptFile](#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Criptografa um arquivo Pdf com senha de usuário e senha de proprietário e define os privilégios do documento para acesso. A senha do usuário e a senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a senha de proprietário de entrada for nula ou vazia. Não lança uma exceção se o processo falhar. string inFile = "input.pdf"; //O TestPath pode ser reatribuído. string outFile = "output.pdf"; //O TestPath pode ser reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); |
| [trySetPrivilege](#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | Define a segurança do arquivo Pdf com a senha original. Não lança uma exceção se o processo falhar. string inFile = "D:\\\\input.pdf"; //O TestPath pode ser reatribuído. string outFile = "D:\\\\output.pdf"; //O TestPath pode ser reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print); |

### PdfFileSecurity {#PdfFileSecurity--}
```
public PdfFileSecurity()
```

Inicialize o objeto de PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-}
Inicialize o objeto de PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-}
Inicialize o objeto de PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-}
Inicialize o objeto de PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
Inicialize o objeto de PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.lang.String-java.lang.String-}
Inicialize o objeto de PdfFileSecurity.

### bindPdf {#bindPdf-java.io.InputStream-}
Inicializa a fachada.

### bindPdf {#bindPdf-java.lang.String-}
Inicializa a fachada.

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-}
Altera a senha do usuário e a senha do proprietário usando a senha do proprietário, mantendo as configurações de segurança originais. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Lança uma exceção se o processo falhar. string inFile = "D:\\input.pdf"; //O TestPath pode ser reatribuído. string outFile = "D:\\output.pdf"; //O TestPath pode ser reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner");

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Altera a senha de usuário e a senha do proprietário usando a senha do proprietário, permitindo redefinir a segurança do documento Pdf. A nova senha de usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. <p> Lança uma exceção se o processo falhar. </p> <hr> <pre> string inFile = "input.pdf"; // O TestPath pode ser // reatribuído. string outFile = "output.pdf"; // O TestPath pode ser // reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre>

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Altera a senha de usuário e a senha do proprietário usando a senha do proprietário, permitindo redefinir a segurança do documento Pdf. A nova senha de usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Existem 6 combinações possíveis de valores de KeySize e Algorithm. No entanto, (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) são inválidos e a exceção correspondente será lançada se o kit encontrar essa combinação. Lança uma exceção se o processo falhar. </p> <hr> <pre> string inFile = "input.pdf"; // O TestPath pode ser // reatribuído. string outFile = "output.pdf"; // O TestPath pode ser // reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### close {#close--}
```
public void close()
```

Fecha a fachada.

### decryptFile {#decryptFile-java.lang.String-}
Descriptografa um documento Pdf criptografado usando a senha do proprietário. Se o documento não possuir senha do proprietário, é permitido usar a senha de usuário. Lança uma exceção se o processo falhar. string inFile = "input.pdf"; //O TestPath pode ser reatribuído. string outFile = "output.pdf"; //O TestPath pode ser reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass");

### dispose {#dispose--}
```
public void dispose()
```

Fecha a fachada.

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Criptografa o arquivo Pdf com senha de usuário e senha de proprietário e define as permissões do documento para acesso. A senha de usuário e a senha de proprietário podem ser nulas ou vazias. A senha de proprietário será substituída por uma string aleatória se a senha de proprietário fornecida for nula ou vazia. Lança uma exceção se o processo falhar. </p> <hr> <pre> String inFile = "input.pdf"; // O TestPath pode ser // reatribuído. String outFile = "output.pdf"; // O TestPath pode ser // reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre>

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Criptografa o arquivo Pdf com userpassword e ownerpassword e define os privilégios do documento para acesso. A senha do usuário e a senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a senha do proprietário de entrada for nula ou vazia. Existem 6 combinações possíveis de valores de KeySize e Algorithm. No entanto, (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) são inválidos e a exceção correspondente será lançada se o kit encontrar essa combinação. Lança uma exceção se o processo falhar. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### getAllowExceptions {#getAllowExceptions--}
```
@Deprecated public final boolean getAllowExceptions()
```

Se este valor for definido como true, uma exceção será lançada em caso de falha na operação. Caso contrário, o método retorna false na falha e a última exceção pode ser verificada com a propriedade LastException.

**Returns:**
valor booleano @deprecated Esta propriedade está obsoleta e não pode ser usada para permitir lançar exceções.

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Retorna a exceção que foi lançada pela última operação.

**Returns:**
java.lang.RuntimeException

### setAllowExceptions {#setAllowExceptions-boolean-}
```
@Deprecated public final void setAllowExceptions(boolean value)
```

Se este valor for definido como true, uma exceção será lançada em caso de falha na operação. Caso contrário, o método retorna false na falha e a última exceção pode ser verificada com a propriedade LastException.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano @deprecated Esta propriedade está obsoleta e não pode ser usada para permitir lançar exceções. |

### setInputFile {#setInputFile-java.lang.String-}
Define o arquivo de entrada. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setInputStream {#setInputStream-java.io.InputStream-}
Define o fluxo de entrada. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setOutputFile {#setOutputFile-java.lang.String-}
Define o arquivo de saída. Obsolete("Use save(outputStream) method for getting facade results.")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Define o fluxo de saída. Obsolete("Use save(outputStream) method for getting facade results.")

### setPrivilege {#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Define a segurança do arquivo Pdf com senhas de usuário/proprietário vazias. A senha do proprietário será adicionada por uma string aleatória. Lança uma exceção se o processo falhar. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre>

### setPrivilege {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Define a segurança do arquivo Pdf com a senha original. Lança uma exceção se o processo falhar. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre>

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-}
Altera a senha do usuário e a senha do proprietário usando a senha do proprietário, mantendo as configurações de segurança originais. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Não lança uma exceção se o processo falhar. string inFile = "D:\\input.pdf"; //O TestPath pode ser reatribuído. string outFile = "D:\\output.pdf"; //O TestPath pode ser reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner");

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Altera a senha do usuário e a senha pelo senha do proprietário, permite redefinir a segurança do documento Pdf. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Não lança uma exceção se o processo falhar. string inFile = ".D:\\\\input.pdf"; //O TestPath pode ser reatribuído. string outFile = "D:\\\\output.pdf"; //O TestPath pode ser reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
Altera a senha do usuário e a senha pelo senha do proprietário, permite redefinir a segurança do documento Pdf. A nova senha do usuário e a nova senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a nova senha do proprietário for nula ou vazia. Existem 6 combinações possíveis de valores de KeySize e Algorithm. No entanto (KeySize.x40, Algorithm.AES) e (KeySize.x256, Algorithm.RC4) são inválidos e a exceção correspondente será lançada se o kit encontrar essa combinação. Não lança uma exceção se o processo falhar. string inFile = "D:\\\\input.pdf"; //O TestPath pode ser reatribuído. string outFile = "D:\\\\output.pdf"; //O TestPath pode ser reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

### tryDecryptFile {#tryDecryptFile-java.lang.String-}
Descriptografa um documento Pdf criptografado usando a senha do proprietário. Se o documento não possuir senha do proprietário, é permitido usar a senha do usuário. Não lança uma exceção se o processo falhar. string inFile = "input.pdf"; //O TestPath pode ser reatribuído. string outFile = "output.pdf"; //O TestPath pode ser reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass");

### tryEncryptFile {#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Criptografa um arquivo Pdf com senha de usuário e senha de proprietário e define os privilégios do documento para acesso. A senha do usuário e a senha do proprietário podem ser nulas ou vazias. A senha do proprietário será substituída por uma string aleatória se a senha de proprietário de entrada for nula ou vazia. Não lança uma exceção se o processo falhar. string inFile = "input.pdf"; //O TestPath pode ser reatribuído. string outFile = "output.pdf"; //O TestPath pode ser reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);

### trySetPrivilege {#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
Define a segurança do arquivo Pdf com a senha original. Não lança uma exceção se o processo falhar. string inFile = "D:\\\\input.pdf"; //O TestPath pode ser reatribuído. string outFile = "D:\\\\output.pdf"; //O TestPath pode ser reatribuído. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
