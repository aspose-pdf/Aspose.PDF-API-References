---
title: "类 PdfFileSecurity"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.PdfFileSecurity 类。表示使用所有者或用户密码对 Pdf 文件进行加密或解密，并更改安全设置和密码。"
type: docs
weight: 4670
url: /zh/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

表示使用所有者或用户密码对 Pdf 文件进行加密或解密，修改安全设置和密码。

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | 初始化 PdfFileSecurity 对象。 |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | 基于 *document* 初始化新的 `PdfFileSecurity` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取正在操作的 document facade。 |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | 返回上一次操作抛出的异常。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化 facade。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | 初始化 facade。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | 初始化 facade。 |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | 通过所有者密码更改用户密码和所有者密码，保持原始安全设置。新的用户密码和新的所有者密码可以为 null 或 empty。如果新的所有者密码为 null 或 empty，则所有者密码将被随机字符串替代。如果处理失败，则抛出异常。 |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | 通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。新的用户密码和新的所有者密码可以为 null 或 empty。如果新的所有者密码为 null 或 empty，则所有者密码将被随机字符串替代。如果处理失败，则抛出异常。 |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | 通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。新的用户密码和新的所有者密码可以为 null 或 empty。如果新的所有者密码为 null 或 empty，则所有者密码将被随机字符串替代。KeySize 和 Algorithm 值有 6 种可能的组合。然而 (KeySize.x40, Algorithm.AES) 和 (KeySize.x256, Algorithm.RC4) 是无效的，如果工具遇到此组合将引发相应的异常。如果处理失败，则抛出异常。 |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | 关闭 facade。 |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | 通过所有者密码解密加密的 Pdf 文档。如果文档没有所有者密码，则允许使用用户密码。若处理失败，则抛出异常。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放 facade。 |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | 使用 userpassword 和 ownerpassword 加密 Pdf 文件并设置文档的访问权限。user password 和 owner password 可以为 null 或为空。如果输入的 owner password 为 null 或为空，owner password 将被随机字符串替代。处理失败时抛出异常。 |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | 使用 userpassword 和 ownerpassword 加密 Pdf 文件并设置文档的访问权限。user password 和 owner password 可以为 null 或为空。如果输入的 owner password 为 null 或为空，owner password 将被随机字符串替代。KeySize 和 Algorithm 值共有 6 种可能的组合。然而 (KeySize.x40, Algorithm.AES) 和 (KeySize.x256, Algorithm.RC4) 是无效的，如果工具遇到此组合将抛出相应的异常。处理失败时抛出异常。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | 将 PDF 文档保存到指定的流中。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | 将 PDF 文档保存到指定的文件中。 |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | 使用空的用户/所有者密码设置 Pdf 文件的安全性。所有者密码将由随机字符串添加。处理失败时抛出异常。 |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | 使用原始密码设置 Pdf 文件的安全性。处理失败时抛出异常。 |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | 通过所有者密码更改用户密码和所有者密码，保持原始安全设置。新的用户密码和新的所有者密码可以为 null 或为空。如果新的所有者密码为 null 或为空，所有者密码将被随机字符串替代。处理失败时不抛出异常。 |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | 通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。新的用户密码和新的所有者密码可以为 null 或为空。如果新的所有者密码为 null 或为空，所有者密码将被随机字符串替代。处理失败时不抛出异常。 |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | 通过所有者密码更改用户密码和密码，允许重置 Pdf 文档安全性。新的用户密码和新的所有者密码可以为 null 或为空。如果新的所有者密码为 null 或为空，所有者密码将被随机字符串替代。KeySize 和 Algorithm 值共有 6 种可能的组合。然而 (KeySize.x40, Algorithm.AES) 和 (KeySize.x256, Algorithm.RC4) 是无效的，如果工具遇到此组合将抛出相应的异常。处理失败时不抛出异常。 |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | 使用所有者密码解密加密的 Pdf 文档。如果文档没有所有者密码，则允许使用用户密码。处理失败时不抛出异常。 |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | 使用 userpassword 和 ownerpassword 加密 Pdf 文件并设置文档的访问权限。user password 和 owner password 可以为 null 或为空。如果输入的 owner password 为 null 或为空，owner password 将被随机字符串替代。处理失败时不抛出异常。 |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | 使用原始密码设置 Pdf 文件的安全性。处理失败时不抛出异常。 |

### 另请参见

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


