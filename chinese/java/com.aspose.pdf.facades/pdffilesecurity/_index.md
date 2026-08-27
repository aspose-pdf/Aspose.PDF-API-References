---
title: "PdfFileSecurity"
linktitle: "PdfFileSecurity"
second_title: "Aspose.PDF for Java API 参考"
description: "表示使用所有者或用户密码对 PDF 文件进行加密或解密、修改安全设置和密码的功能。"
type: docs
weight: 520
url: /zh/java/com.aspose.pdf.facades/pdffilesecurity/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSecurity

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSecurity extends SaveableFacade implements com.aspose.ms.System.IDisposable
```

表示使用所有者或用户密码对 PDF 文件进行加密或解密、修改安全设置和密码的功能。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileSecurity](#PdfFileSecurity--) | 初始化 PdfFileSecurity 对象。 |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-) | 初始化 PdfFileSecurity 对象。 |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-) | 初始化 PdfFileSecurity 对象。 |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-) | 初始化 PdfFileSecurity 对象。 |
| [PdfFileSecurity](#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-) | 初始化 PdfFileSecurity 对象。 |
| [PdfFileSecurity](#PdfFileSecurity-java.lang.String-java.lang.String-) | 初始化 PdfFileSecurity 对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | 初始化 facade。 |
| [bindPdf](#bindPdf-java.lang.String-) | 初始化 facade。 |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | 通过所有者密码更改用户密码和所有者密码，保持原始安全设置。新的用户密码和新的所有者密码可以为 null 或为空。如果新的所有者密码为 null 或为空，所有者密码将被随机字符串替代。处理失败时抛出异常。 string inFile = \"D:\\\\input.pdf\"; //The TestPath may be re-assigned. string outFile = \"D:\\\\output.pdf\"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword(\"owner\",\"newuser\",\"newowner\"); |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> 通过所有者密码更改用户密码和所有者密码，允许重置 Pdf 文档安全性。新的用户密码和新的所有者密码可以为 null 或为空。如果新的所有者密码为 null 或为空，所有者密码将被随机字符串替代。 <p> 处理失败时抛出异常。 </p> <hr> <pre> string inFile = \"input.pdf\"; // The TestPath may be // re-assigned. string outFile = \"output.pdf\"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword(\"owner\", \"newuser\", \"newowner\", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> 通过所有者密码更改用户密码和所有者密码，允许重置 Pdf 文档安全性。新的用户密码和新的所有者密码可以为 null 或为空。如果新的所有者密码为 null 或为空，所有者密码将被随机字符串替代。有 6 种可能的 KeySize 和 Algorithm 组合。然而 (KeySize.x40, Algorithm.AES) 和 (KeySize.x256, Algorithm.RC4) 是无效的，如果套件遇到此组合将抛出相应的异常。处理失败时抛出异常。 </p> <hr> <pre> string inFile = \"input.pdf\"; // The TestPath may be // re-assigned. string outFile = \"output.pdf\"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword(\"owner\", \"newuser\", \"newowner\", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [close](#close--) | 关闭该外观。 |
| [decryptFile](#decryptFile-java.lang.String-) | 通过所有者密码解密加密的 Pdf 文档。如果文档没有所有者密码，则允许使用用户密码。处理失败时抛出异常。 string inFile = \"input.pdf\"; //The TestPath may be re-assigned. string outFile = \"output.pdf\"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile(\"ownerpass\"); |
| [dispose](#dispose--) | 关闭该外观。 |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> 使用用户密码和所有者密码加密 Pdf 文件并设置文档的访问权限。用户密码和所有者密码可以为 null 或为空。如果输入的所有者密码为 null 或为空，所有者密码将被随机字符串替代。处理失败时抛出异常。 </p> <hr> <pre> String inFile = \"input.pdf\"; // The TestPath may be // re-assigned. String outFile = \"output.pdf\"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile(\"userpass\", \"ownerpass\", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> 使用用户密码和所有者密码加密 Pdf 文件并设置文档的访问权限。用户密码和所有者密码可以为 null 或为空。如果输入的所有者密码为 null 或为空，所有者密码将被随机字符串替代。有 6 种可能的 KeySize 和 Algorithm 组合。然而 (KeySize.x40, Algorithm.AES) 和 (KeySize.x256, Algorithm.RC4) 是无效的，如果套件遇到此组合将抛出相应的异常。处理失败时抛出异常。 </p> <hr> <pre> String inFile = \"input.pdf\"; // The TestPath may be // re-assigned. String outFile = \"output.pdf\"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile(\"userpass\", \"ownerpass\", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [getAllowExceptions](#getAllowExceptions--) | 如果此值设置为 true，操作失败时将抛出异常。否则，方法在失败时返回 false，且可以通过 LastException 属性检查最后的异常。 |
| [getLastException](#getLastException--) | 返回上一次操作抛出的异常。 |
| [setAllowExceptions](#setAllowExceptions-boolean-) | 如果此值设置为 true，操作失败时将抛出异常。否则，方法在失败时返回 false，且可以通过 LastException 属性检查最后的异常。 |
| [setInputFile](#setInputFile-java.lang.String-) | 设置输入文件。Obsolete(\"Use bindPdf(inputStream) method for facade initialization.\") |
| [setInputStream](#setInputStream-java.io.InputStream-) | 设置输入流。Obsolete(\"Use bindPdf(inputStream) method for facade initialization.\") |
| [setOutputFile](#setOutputFile-java.lang.String-) | 设置输出文件。Obsolete(\"Use save(outputStream) method for getting facade results.\") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | 设置输出流。Obsolete(\"Use save(outputStream) method for getting facade results.\") |
| [setPrivilege](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | <p> 设置 Pdf 文件安全，使用空的用户/所有者密码。所有者密码将由随机字符串添加。若处理失败，将抛出异常。 </p> <hr> <pre> string inFile = \"input.pdf\"; // The TestPath may be re-assigned. string outFile = \"output.pdf\"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre> |
| [setPrivilege](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | <p> 设置 Pdf 文件安全，使用原始密码。若处理失败，将抛出异常。 </p> <hr> <pre> string inFile = \"input.pdf\"; // The TestPath may be re-assigned. string outFile = \"output.pdf\"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre> |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-) | 通过所有者密码更改用户密码和所有者密码，保持原始安全设置。新的用户密码和新的所有者密码可以为 null 或为空。如果新的所有者密码为 null 或为空，所有者密码将被随机字符串替代。若处理失败，不会抛出异常。 string inFile = \"D:\\\\\\input.pdf\"; //The TestPath may be re-assigned. string outFile = \"D:\\\\\\output.pdf\"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword(\"owner\",\"newuser\",\"newowner\"); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | 通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全。新的用户密码和新的所有者密码可以为 null 或为空。如果新的所有者密码为 null 或为空，所有者密码将被随机字符串替代。若处理失败，不会抛出异常。 string inFile = \".D:\\\\\\input.pdf\"; //The TestPath may be re-assigned. string outFile = \"D:\\\\\\output.pdf\"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword(\"owner\",\"newuser\",\"newowner\", DocumentPrivilege.Print,KeySize.x256); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | 通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全。新的用户密码和新的所有者密码可以为 null 或为空。如果新的所有者密码为 null 或为空，所有者密码将被随机字符串替代。有 6 种可能的 KeySize 与 Algorithm 组合。然而 (KeySize.x40, Algorithm.AES) 和 (KeySize.x256, Algorithm.RC4) 是无效的，如果工具遇到此组合将抛出相应异常。若处理失败，不会抛出异常。 string inFile = \"D:\\\\\\input.pdf\"; //The TestPath may be re-assigned. string outFile = \"D:\\\\\\output.pdf\"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword(\"owner\",\"newuser\",\"newowner\", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES); |
| [tryDecryptFile](#tryDecryptFile-java.lang.String-) | 使用所有者密码解密加密的 Pdf 文档。如果文档没有所有者密码，则允许使用用户密码。若处理失败，不会抛出异常。 string inFile = \"input.pdf\"; //The TestPath may be re-assigned. string outFile = \"output.pdf\"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile(\"ownerpass\"); |
| [tryEncryptFile](#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | 使用用户密码和所有者密码加密 Pdf 文件，并设置文档的访问权限。用户密码和所有者密码可以为 null 或为空。如果输入的所有者密码为 null 或为空，所有者密码将被随机字符串替代。若处理失败，不会抛出异常。 string inFile = \"input.pdf\"; //The TestPath may be re-assigned. string outFile = \"output.pdf\"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile(\"userpass\", \"ownerpass\", DocumentPrivilege.Print, KeySize.x256); |
| [trySetPrivilege](#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | 使用原始密码设置 Pdf 文件安全。若处理失败，不会抛出异常。 string inFile = \"D:\\\\\\input.pdf\"; //The TestPath may be re-assigned. string outFile = \"D:\\\\\\output.pdf\"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print); |

### PdfFileSecurity {#PdfFileSecurity--}
```
public PdfFileSecurity()
```

初始化 PdfFileSecurity 对象。

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-}
初始化 PdfFileSecurity 对象。

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-}
初始化 PdfFileSecurity 对象。

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-}
初始化 PdfFileSecurity 对象。

### PdfFileSecurity {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
初始化 PdfFileSecurity 对象。

### PdfFileSecurity {#PdfFileSecurity-java.lang.String-java.lang.String-}
初始化 PdfFileSecurity 对象。

### bindPdf {#bindPdf-java.io.InputStream-}
初始化 facade。

### bindPdf {#bindPdf-java.lang.String-}
初始化 facade。

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-}
通过所有者密码更改用户密码和所有者密码，保持原始安全设置。新的用户密码和新的所有者密码可以为 null 或为空。如果新的所有者密码为 null 或为空，所有者密码将被随机字符串替代。若处理失败，将抛出异常。 string inFile = \"D:\\\\input.pdf\"; //The TestPath may be re-assigned. string outFile = \"D:\\\\output.pdf\"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword(\"owner\",\"newuser\",\"newowner\");

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> 通过所有者密码更改用户密码和所有者密码，允许重置 Pdf 文档安全性。新的用户密码和新的所有者密码可以为 null 或为空。如果新的所有者密码为 null 或为空，所有者密码将被随机字符串替代。 <p> 处理失败时抛出异常。 </p> <hr> <pre> string inFile = \"input.pdf\"; // The TestPath may be // re-assigned. string outFile = \"output.pdf\"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword(\"owner\", \"newuser\", \"newowner\", DocumentPrivilege.Print, KeySize.x256); </pre>

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> 通过所有者密码更改用户密码和所有者密码，允许重置 Pdf 文档安全性。新的用户密码和新的所有者密码可以为 null 或为空。如果新的所有者密码为 null 或为空，所有者密码将被随机字符串替代。有 6 种可能的 KeySize 和 Algorithm 组合。然而 (KeySize.x40, Algorithm.AES) 和 (KeySize.x256, Algorithm.RC4) 是无效的，如果套件遇到此组合将抛出相应的异常。处理失败时抛出异常。 </p> <hr> <pre> string inFile = \"input.pdf\"; // The TestPath may be // re-assigned. string outFile = \"output.pdf\"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword(\"owner\", \"newuser\", \"newowner\", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### close {#close--}
```
public void close()
```

关闭该外观。

### decryptFile {#decryptFile-java.lang.String-}
通过所有者密码解密加密的 Pdf 文档。如果文档没有所有者密码，则允许使用用户密码。处理失败时抛出异常。 string inFile = \"input.pdf\"; //The TestPath may be re-assigned. string outFile = \"output.pdf\"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile(\"ownerpass\");

### dispose {#dispose--}
```
public void dispose()
```

关闭该外观。

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> 使用用户密码和所有者密码加密 Pdf 文件并设置文档的访问权限。用户密码和所有者密码可以为 null 或为空。如果输入的所有者密码为 null 或为空，所有者密码将被随机字符串替代。处理失败时抛出异常。 </p> <hr> <pre> String inFile = \"input.pdf\"; // The TestPath may be // re-assigned. String outFile = \"output.pdf\"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile(\"userpass\", \"ownerpass\", DocumentPrivilege.Print, KeySize.x256); </pre>

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> 使用用户密码和所有者密码加密 Pdf 文件并设置文档的访问权限。用户密码和所有者密码可以为 null 或为空。如果输入的所有者密码为 null 或为空，所有者密码将被随机字符串替代。有 6 种可能的 KeySize 和 Algorithm 组合。然而 (KeySize.x40, Algorithm.AES) 和 (KeySize.x256, Algorithm.RC4) 是无效的，如果套件遇到此组合将抛出相应的异常。处理失败时抛出异常。 </p> <hr> <pre> String inFile = \"input.pdf\"; // The TestPath may be // re-assigned. String outFile = \"output.pdf\"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile(\"userpass\", \"ownerpass\", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### getAllowExceptions {#getAllowExceptions--}
```
@Deprecated public final boolean getAllowExceptions()
```

如果此值设置为 true，操作失败时将抛出异常。否则，方法在失败时返回 false，且可以通过 LastException 属性检查最后的异常。

**Returns:**
布尔值 @deprecated 此属性已弃用，不能用于允许抛出异常。

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

返回上一次操作抛出的异常。

**Returns:**
java.lang.RuntimeException

### setAllowExceptions {#setAllowExceptions-boolean-}
```
@Deprecated public final void setAllowExceptions(boolean value)
```

如果此值设置为 true，操作失败时将抛出异常。否则，方法在失败时返回 false，且可以通过 LastException 属性检查最后的异常。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 @deprecated 此属性已弃用，不能用于允许抛出异常。 |

### setInputFile {#setInputFile-java.lang.String-}
设置输入文件。Obsolete(\"Use bindPdf(inputStream) method for facade initialization.\")

### setInputStream {#setInputStream-java.io.InputStream-}
设置输入流。Obsolete(\"Use bindPdf(inputStream) method for facade initialization.\")

### setOutputFile {#setOutputFile-java.lang.String-}
设置输出文件。Obsolete(\"Use save(outputStream) method for getting facade results.\")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
设置输出流。Obsolete(\"Use save(outputStream) method for getting facade results.\")

### setPrivilege {#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-}
<p> 设置 Pdf 文件安全，使用空的用户/所有者密码。所有者密码将由随机字符串添加。若处理失败，将抛出异常。 </p> <hr> <pre> string inFile = \"input.pdf\"; // The TestPath may be re-assigned. string outFile = \"output.pdf\"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre>

### setPrivilege {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
<p> 设置 Pdf 文件安全，使用原始密码。若处理失败，将抛出异常。 </p> <hr> <pre> string inFile = \"input.pdf\"; // The TestPath may be re-assigned. string outFile = \"output.pdf\"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre>

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-}
通过所有者密码更改用户密码和所有者密码，保持原始安全设置。新的用户密码和新的所有者密码可以为 null 或为空。如果新的所有者密码为 null 或为空，所有者密码将被随机字符串替换。过程失败时不抛出异常。 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner");

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
通过所有者密码更改用户密码和所有者密码，允许重置 PDF 文档安全。新的用户密码和新的所有者密码可以为 null 或为空。如果新的所有者密码为 null 或为空，所有者密码将被随机字符串替换。过程失败时不抛出异常。 string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
通过所有者密码更改用户密码和所有者密码，允许重置 PDF 文档安全。新的用户密码和新的所有者密码可以为 null 或为空。如果新的所有者密码为 null 或为空，所有者密码将被随机字符串替换。KeySize 和 Algorithm 值共有 6 种可能组合。然而 (KeySize.x40, Algorithm.AES) 和 (KeySize.x256, Algorithm.RC4) 是无效的，如果工具遇到此组合将抛出相应异常。过程失败时不抛出异常。 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

### tryDecryptFile {#tryDecryptFile-java.lang.String-}
使用所有者密码解密加密的 Pdf 文档。如果文档没有所有者密码，则允许使用用户密码。若处理失败，不会抛出异常。 string inFile = \"input.pdf\"; //The TestPath may be re-assigned. string outFile = \"output.pdf\"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile(\"ownerpass\");

### tryEncryptFile {#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
使用用户密码和所有者密码加密 Pdf 文件，并设置文档的访问权限。用户密码和所有者密码可以为 null 或为空。如果输入的所有者密码为 null 或为空，所有者密码将被随机字符串替代。若处理失败，不会抛出异常。 string inFile = \"input.pdf\"; //The TestPath may be re-assigned. string outFile = \"output.pdf\"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile(\"userpass\", \"ownerpass\", DocumentPrivilege.Print, KeySize.x256);

### trySetPrivilege {#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
使用原始密码设置 PDF 文件安全。过程失败时不抛出异常。 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
