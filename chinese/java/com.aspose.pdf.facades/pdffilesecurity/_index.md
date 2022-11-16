---
title: PdfFileSecurity
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示使用更改安全设置和密码的所有者或用户密码加密或解密 Pdf 文件。
type: docs
weight: 44
url: /zh/java/com.aspose.pdf.facades/pdffilesecurity/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)

**所有已实现的接口：**
com.aspose.ms.System.IDisposable
```
public final class PdfFileSecurity extends SaveableFacade implements System.IDisposable
```

表示使用所有者或用户密码加密或解密 Pdf 文件，更改安全设置和密码。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileSecurity(InputStream inputStream, OutputStream outputStream)](#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-) | 使用输入和输出流初始化 PdfFileSecurity 的对象。 |
| [PdfFileSecurity(String inputFile, String outputFile)](#PdfFileSecurity-java.lang.String-java.lang.String-) | 使用输入和输出文件初始化 PdfFileSecurity 的对象。 |
| [PdfFileSecurity()](#PdfFileSecurity--) | 初始化 PdfFileSecurity 对象。 |
| [PdfFileSecurity(IDocument document)](#PdfFileSecurity-com.aspose.pdf.IDocument-) | 在文档的基础上初始化新的 PdfFileSecurity 对象。 |
| [PdfFileSecurity(IDocument document, String outputFile)](#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-) | 在文档的基础上初始化新的 PdfFileSecurity 对象。 |
| [PdfFileSecurity(IDocument document, OutputStream outputStream)](#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-) | 在文档的基础上初始化新的 PdfFileSecurity 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 初始化门面。 |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | 初始化门面。 |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | 初始化门面。 |
| [changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword)](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | 通过所有者密码更改用户密码和所有者密码，保持原来的安全设置。 |
| [changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize)](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-) | 通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。 |
| [changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher)](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-) | 通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。 |
| [close()](#close--) | 关闭门面。 |
| [decryptFile(String ownerPassword)](#decryptFile-java.lang.String-) | 通过所有者密码解密加密的 Pdf 文档。 |
| [dispose()](#dispose--) | 关闭门面。 |
| [encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize)](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-) | 使用用户密码和所有者密码加密 Pdf 文件，并设置文档的访问权限。 |
| [encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize, int cipher)](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-) | 使用用户密码和所有者密码加密 Pdf 文件，并设置文档的访问权限。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowExceptions()](#getAllowExceptions--) | 如果此值设置为 true，将在操作失败时抛出异常。 |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | 获取正在处理的文档外观。 |
| [getLastException()](#getLastException--) | 返回上次操作抛出的异常。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | 将 PDF 文档保存到指定的流。 |
| [save(String destFile)](#save-java.lang.String-) | 将 PDF 文档保存到指定文件。 |
| [setAllowExceptions(boolean value)](#setAllowExceptions-boolean-) | 如果此值设置为 true，将在操作失败时抛出异常。 |
| [setInputFile(String value)](#setInputFile-java.lang.String-) | 设置输入文件。 |
| [setInputStream(InputStream value)](#setInputStream-java.io.InputStream-) | 设置输入流。 |
| [setOutputFile(String value)](#setOutputFile-java.lang.String-) | 设置输出文件。 |
| [setOutputStream(OutputStream value)](#setOutputStream-java.io.OutputStream-) | 设置输出流。 |
| [setPrivilege(DocumentPrivilege privilege)](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | 使用空用户/所有者密码设置 Pdf 文件安全性。 |
| [setPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege)](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | 使用原始密码设置 Pdf 文件安全性。 |
| [toString()](#toString--) |  |
| [tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword)](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-) | 通过所有者密码更改用户密码和所有者密码，保持原来的安全设置。 |
| [tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize)](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-) | 通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。 |
| [tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher)](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-) | 通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。 |
| [tryDecryptFile(String ownerPassword)](#tryDecryptFile-java.lang.String-) | 通过所有者密码解密加密的 Pdf 文档。 |
| [tryEncryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize)](#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-) | 使用用户密码和所有者密码加密 Pdf 文件，并设置文档的访问权限。 |
| [trySetPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege)](#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | 使用原始密码设置 Pdf 文件安全性。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileSecurity(InputStream inputStream, OutputStream outputStream) {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
```
public PdfFileSecurity(InputStream inputStream, OutputStream outputStream)
```


使用输入和输出流初始化 PdfFileSecurity 的对象。

Obsolete("使用没有目的地的构造函数。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入 Pdf 流。 |
| outputStream | java.io.OutputStream | 输出 Pdf 流。 |

### PdfFileSecurity(String inputFile, String outputFile) {#PdfFileSecurity-java.lang.String-java.lang.String-}
```
public PdfFileSecurity(String inputFile, String outputFile)
```


使用输入和输出文件初始化 PdfFileSecurity 的对象。

Obsolete("使用没有目的地的构造函数。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 源输入 Pdf 文件。 |
| outputFile | java.lang.String | 输出 Pdf 文件。 |

### PdfFileSecurity() {#PdfFileSecurity--}
```
public PdfFileSecurity()
```


初始化 PdfFileSecurity 对象。

### PdfFileSecurity(IDocument document) {#PdfFileSecurity-com.aspose.pdf.IDocument-}
```
public PdfFileSecurity(IDocument document)
```


在文档的基础上初始化新的 PdfFileSecurity 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |

### PdfFileSecurity(IDocument document, String outputFile) {#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-}
```
public PdfFileSecurity(IDocument document, String outputFile)
```


在文档的基础上初始化新的 PdfFileSecurity 对象。

Obsolete("使用没有目的地的构造函数。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |
| outputFile | java.lang.String | 输出 Pdf 文件。 |

### PdfFileSecurity(IDocument document, OutputStream outputStream) {#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public PdfFileSecurity(IDocument document, OutputStream outputStream)
```


在文档的基础上初始化新的 PdfFileSecurity 对象。

Obsolete("使用没有目的地的构造函数。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |
| outputStream | java.io.OutputStream | 输出 Pdf 流。 |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象。 |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |
| password | java.lang.String | PDF文档的密码。 |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件。 |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件 |
| password | java.lang.String | PDF文档的密码。 |

### changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword) {#changePassword-java.lang.String-java.lang.String-java.lang.String-}
```
public final boolean changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword)
```


通过所有者密码更改用户密码和所有者密码，保持原来的安全设置。新用户密码和新所有者密码可以为空或为空。如果新所有者密码为 null 或为空，则所有者密码将替换为随机字符串。如果进程失败则抛出异常。

```
string inFile = "D:\\input.pdf"; //可以重新分配 TestPath。
  string outFile = "D:\\output.pdf";	//可以重新分配 TestPath。
  PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
  fileSecurity.changePassword("owner","newuser","newowner");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | java.lang.String | 原始所有者密码。 |
| newUserPassword | java.lang.String | 新用户密码。 |
| newOwnerPassword | java.lang.String | 新所有者密码。 |

**退货：**
boolean - True 表示成功。
### changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize) {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-}
```
public boolean changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize)
```


通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。新用户密码和新所有者密码可以为空或为空。如果新所有者密码为 null 或为空，则所有者密码将替换为随机字符串。如果进程失败则抛出异常。

--------------------

```
string inFile = "input.pdf"; //测试路径可能是
 														//重新分配。
 string outFile = "output.pdf"; //测试路径可能是
 															//重新分配。
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.changePassword("owner", "newuser", "newowner",
 		DocumentPrivilege.Print, KeySize.x256);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | java.lang.String | 原始所有者密码。 |
| newUserPassword | java.lang.String | 新用户密码。 |
| newOwnerPassword | java.lang.String | 新所有者密码。 |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | 重置安全。 |
| keySize | int | KeySize.x40 用于 40 位加密，KeySize.x128 用于 128 位加密，KeySize.x256 用于 256 位加密。 |

**退货：**
boolean - True 表示成功。
### changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher) {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-}
```
public boolean changePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher)
```


通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。新用户密码和新所有者密码可以为空或为空。如果新所有者密码为 null 或为空，则所有者密码将替换为随机字符串。 KeySize 和 Algorithm 值有 6 种可能的组合。但是(KeySize.x40, Algorithm.AES) 和(KeySize.x256, Algorithm.RC4) 是无效的，如果kit遇到这个组合会抛出相应的异常。如果进程失败则抛出异常。

--------------------

```
string inFile = "input.pdf"; //测试路径可能是
 														//重新分配。
 string outFile = "output.pdf"; //测试路径可能是
 															//重新分配。
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.changePassword("owner", "newuser", "newowner",
 		DocumentPrivilege.Print, KeySize.x256, Algorithm.AES);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | java.lang.String | 原始所有者密码。 |
| newUserPassword | java.lang.String | 新用户密码。 |
| newOwnerPassword | java.lang.String | 新所有者密码。 |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | 重置安全。 |
| keySize | int | KeySize.x40 用于 40 位加密，KeySize.x128 用于 128 位加密，KeySize.x256 用于 256 位加密。 |
| cipher | int | Algorithm.AES 使用 AES 算法进行加密或使用 Algorithm.RC4 进行 RC4 加密。 |

**退货：**
boolean - True 表示成功。
### close() {#close--}
```
public void close()
```


关闭门面。

### decryptFile(String ownerPassword) {#decryptFile-java.lang.String-}
```
public final boolean decryptFile(String ownerPassword)
```


通过所有者密码解密加密的 Pdf 文档。如果文档没有所有者密码，则允许使用用户密码。如果进程失败则抛出异常。

```
string inFile = "input.pdf"; //可以重新分配 TestPath。
 string outFile = "output.pdf"; //可以重新分配 TestPath。
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 fileSecurity.decryptFile("ownerpass");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | java.lang.String | 所有者密码。 |

**退货：**
boolean - True 表示成功。
### dispose() {#dispose--}
```
public void dispose()
```


关闭门面。

### encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize) {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-}
```
public boolean encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize)
```


使用用户密码和所有者密码加密 Pdf 文件，并设置文档的访问权限。用户密码和所有者密码可以为 null 或为空。如果输入的所有者密码为 null 或为空，则所有者密码将替换为随机字符串。如果进程失败则抛出异常。

--------------------

```
String inFile = "input.pdf"; //测试路径可能是
 															//重新分配。
 String outFile = "output.pdf"; //测试路径可能是
 															//重新分配。
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print,
 		KeySize.x256);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | java.lang.String | 用户密码。 |
| ownerPassword | java.lang.String | 所有者密码。 |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | 设置特权。 |
| keySize | int | KeySize.x40 用于 40 位加密，KeySize.x128 用于 128 位加密，KeySize.x256 用于 256 位加密。 |

**退货：**
boolean - True 表示成功。
### encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize, int cipher) {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-}
```
public boolean encryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize, int cipher)
```


使用用户密码和所有者密码加密 Pdf 文件，并设置文档的访问权限。用户密码和所有者密码可以为 null 或为空。如果输入的所有者密码为 null 或为空，则所有者密码将替换为随机字符串。 KeySize 和 Algorithm 值有 6 种可能的组合。但是(KeySize.x40, Algorithm.AES) 和(KeySize.x256, Algorithm.RC4) 是无效的，如果kit遇到这个组合会抛出相应的异常。如果进程失败则抛出异常。

--------------------

```
String inFile = "input.pdf"; //测试路径可能是
 															//重新分配。
 String outFile = "output.pdf"; //测试路径可能是
 															//重新分配。
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print,
 		KeySize.x256, Algorithm.AES);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | java.lang.String | 用户密码。 |
| ownerPassword | java.lang.String | 所有者密码。 |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | 设置特权。 |
| keySize | int | KeySize.x40 用于 40 位加密，KeySize.x128 用于 128 位加密，KeySize.x256 用于 256 位加密。 |
| cipher | int | Algorithm.AES 使用 AES 算法进行加密或使用 Algorithm.RC4 进行 RC4 加密。 |

**退货：**
boolean - True 表示成功，否则为 false。
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getAllowExceptions() {#getAllowExceptions--}
```
public final boolean getAllowExceptions()
```


如果此值设置为 true，将在操作失败时抛出异常。否则，方法在失败时返回 false，并且可以使用 LastException 属性检查最后一个异常。

**退货：**
boolean - 布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


获取正在处理的文档外观。

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 元素
### getLastException() {#getLastException--}
```
public final RuntimeException getLastException()
```


返回上次操作抛出的异常。

**退货：**
java.lang.RuntimeException - java.lang.RuntimeException 异常
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


将 PDF 文档保存到指定的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destStream | java.io.OutputStream | 目标流。 |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


将 PDF 文档保存到指定文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destFile | java.lang.String | 目标文件。 |

### setAllowExceptions(boolean value) {#setAllowExceptions-boolean-}
```
public final void setAllowExceptions(boolean value)
```


如果此值设置为 true，将在操作失败时抛出异常。否则，方法在失败时返回 false，并且可以使用 LastException 属性检查最后一个异常。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setInputFile(String value) {#setInputFile-java.lang.String-}
```
public void setInputFile(String value)
```


设置输入文件。

Obsolete("使用 bindPdf(inputStream) 方法进行门面初始化。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public void setInputStream(InputStream value)
```


设置输入流。

Obsolete("使用 bindPdf(inputStream) 方法进行门面初始化。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.InputStream | 输入流对象 |

### setOutputFile(String value) {#setOutputFile-java.lang.String-}
```
public void setOutputFile(String value)
```


设置输出文件。

Obsolete("使用 save(outputStream) 方法获取外观结果。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setOutputStream(OutputStream value) {#setOutputStream-java.io.OutputStream-}
```
public void setOutputStream(OutputStream value)
```


设置输出流。

Obsolete("使用 save(outputStream) 方法获取外观结果。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.OutputStream | 输出流对象 |

### setPrivilege(DocumentPrivilege privilege) {#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-}
```
public boolean setPrivilege(DocumentPrivilege privilege)
```


使用空用户/所有者密码设置 Pdf 文件安全性。所有者密码将由一个随机字符串添加。如果进程失败则抛出异常。

--------------------

```
string inFile = "input.pdf"; //可以重新分配 TestPath。
 string outFile = "output.pdf"; //可以重新分配 TestPath。
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.setPrivilege(DocumentPrivilege.Print);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | 设置特权。 |

**退货：**
boolean - True 表示成功。
### setPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege) {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
```
public boolean setPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege)
```


使用原始密码设置 Pdf 文件安全性。如果进程失败则抛出异常。

--------------------

```
string inFile = "input.pdf"; //可以重新分配 TestPath。
 string outFile = "output.pdf"; //可以重新分配 TestPath。
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile);
 fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint());
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | java.lang.String | 原始用户密码。 |
| ownerPassword | java.lang.String | 原始所有者密码。 |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | 设置特权。 |

**退货：**
boolean - True 表示成功。
### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword) {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-}
```
public final boolean tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword)
```


通过所有者密码更改用户密码和所有者密码，保持原来的安全设置。新用户密码和新所有者密码可以为空或为空。所有者密码将被替换 如果进程失败，则不会抛出异常。如果新所有者密码为 null 或为空，则使用随机字符串。

```
string inFile = "D:\\input.pdf"; //可以重新分配 TestPath。
  string outFile = "D:\\output.pdf";	//可以重新分配 TestPath。
  PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
  bool result = fileSecurity.tryChangePassword("owner","newuser","newowner");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | java.lang.String | 原始所有者密码。 |
| newUserPassword | java.lang.String | 新用户密码。 |
| newOwnerPassword | java.lang.String | 新所有者密码。 |

**退货：**
boolean - True 表示成功，否则为 false。
### tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize) {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-}
```
public final boolean tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize)
```


通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。新用户密码和新所有者密码可以为空或为空。如果新所有者密码为 null 或为空，则所有者密码将替换为随机字符串。如果进程失败，则不会抛出异常。

```
string inFile = ".D:\\input.pdf"; //可以重新分配 TestPath。
 string outFile = "D:\\output.pdf";	//可以重新分配 TestPath。
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | java.lang.String | 原始所有者密码。 |
| newUserPassword | java.lang.String | 新用户密码。 |
| newOwnerPassword | java.lang.String | 新所有者密码。 |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | 重置安全。 |
| keySize | int | KeySize.x40 用于 40 位加密，KeySize.x128 用于 128 位加密，KeySize.x256 用于 256 位加密。 |

**退货：**
boolean - True 表示成功，否则为 false。
### tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher) {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-int-}
```
public final boolean tryChangePassword(String ownerPassword, String newUserPassword, String newOwnerPassword, DocumentPrivilege privilege, int keySize, int cipher)
```


通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。新用户密码和新所有者密码可以为空或为空。如果新所有者密码为 null 或为空，则所有者密码将替换为随机字符串。 KeySize 和 Algorithm 值有 6 种可能的组合。但是(KeySize.x40, Algorithm.AES) 和(KeySize.x256, Algorithm.RC4) 是无效的，如果kit遇到这个组合会抛出相应的异常。如果进程失败，则不会抛出异常。

```
string inFile = "D:\\input.pdf"; //可以重新分配 TestPath。
 string outFile = "D:\\output.pdf";	//可以重新分配 TestPath。
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | java.lang.String | 原始所有者密码。 |
| newUserPassword | java.lang.String | 新用户密码。 |
| newOwnerPassword | java.lang.String | 新所有者密码。 |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | 重置安全。 |
| keySize | int | KeySize.x40 用于 40 位加密，KeySize.x128 用于 128 位加密，KeySize.x256 用于 256 位加密。 |
| cipher | int | Algorithm.AES 使用 AES 算法进行加密或使用 Algorithm.RC4 进行 RC4 加密。 |

**退货：**
boolean - True 表示成功，否则为 false。
### tryDecryptFile(String ownerPassword) {#tryDecryptFile-java.lang.String-}
```
public final boolean tryDecryptFile(String ownerPassword)
```


通过所有者密码解密加密的 Pdf 文档。如果文档没有所有者密码，则允许使用用户密码。如果进程失败，则不会抛出异常。

```
string inFile = "input.pdf"; //可以重新分配 TestPath。
 string outFile = "output.pdf"; //可以重新分配 TestPath。
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 bool result = fileSecurity.TryDecryptFile("ownerpass");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ownerPassword | java.lang.String | 所有者密码。 |

**退货：**
boolean - True 表示成功，否则为 false。
### tryEncryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize) {#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-int-}
```
public final boolean tryEncryptFile(String userPassword, String ownerPassword, DocumentPrivilege privilege, int keySize)
```


使用用户密码和所有者密码加密 Pdf 文件，并设置文档的访问权限。用户密码和所有者密码可以为 null 或为空。如果输入的所有者密码为 null 或为空，则所有者密码将替换为随机字符串。如果进程失败，则不会抛出异常。

```
string inFile = "input.pdf"; //可以重新分配 TestPath。
 string outFile = "output.pdf"; //可以重新分配 TestPath。
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | java.lang.String | 用户密码。 |
| ownerPassword | java.lang.String | 所有者密码。 |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | 设置特权。 |
| keySize | int | KeySize.x40 用于 40 位加密，KeySize.x128 用于 128 位加密，KeySize.x256 用于 256 位加密。 |

**退货：**
boolean - True 表示成功，否则为 false。
### trySetPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege) {#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
```
public final boolean trySetPrivilege(String userPassword, String ownerPassword, DocumentPrivilege privilege)
```


使用原始密码设置 Pdf 文件安全性。如果进程失败，则不会抛出异常。

```
string inFile = "D:\\input.pdf"; //可以重新分配 TestPath。
 string outFile = "D:\\output.pdf"; //可以重新分配 TestPath。
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);
 bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | java.lang.String | 原始用户密码。 |
| ownerPassword | java.lang.String | 原始所有者密码。 |
| privilege | [DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) | 设置特权。 |

**退货：**
boolean - True 表示成功，否则为 false。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
