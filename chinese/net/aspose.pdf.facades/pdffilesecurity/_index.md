---
title: Class PdfFileSecurity
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSecurity class. 表示使用所有者或用户密码加密或解密Pdf文件，改变安全设置和密码
type: docs
weight: 4550
url: /zh/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

表示使用所有者或用户密码加密或解密Pdf文件，改变安全设置和密码。

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | 初始化PdfFileSecurity对象。 |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | 基于*document*初始化新的`PdfFileSecurity`对象。 |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取正在处理的文档外观。 |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | 返回上一个操作抛出的异常。 |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化外观。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | 初始化外观。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | 初始化外观。 |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | 通过所有者密码更改用户密码和所有者密码，保持原始安全设置。新用户密码和新所有者密码可以为null或空。如果新所有者密码为null或空，则所有者密码将被随机字符串替换。如果处理失败，则抛出异常。 |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | 通过所有者密码更改用户密码和密码，允许重置Pdf文档安全性。新用户密码和新所有者密码可以为null或空。如果新所有者密码为null或空，则所有者密码将被随机字符串替换。如果处理失败，则抛出异常。 |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | 通过所有者密码更改用户密码和密码，允许重置Pdf文档安全性。新用户密码和新所有者密码可以为null或空。如果新所有者密码为null或空，则所有者密码将被随机字符串替换。KeySize和Algorithm值有6种可能的组合。然而（KeySize.x40，Algorithm.AES）和（KeySize.x256，Algorithm.RC4）是无效的，如果遇到这种组合，将引发相应的异常。如果处理失败，则抛出异常。 |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | 关闭外观。 |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | 通过所有者密码解密加密的Pdf文档。如果文档没有所有者密码，则允许使用用户密码。如果处理失败，则抛出异常。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放外观。 |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | 使用用户密码和所有者密码加密Pdf文件，并设置文档的访问权限。用户密码和所有者密码可以为null或空。如果输入的所有者密码为null或空，则所有者密码将被随机字符串替换。如果处理失败，则抛出异常。 |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | 使用用户密码和所有者密码加密Pdf文件，并设置文档的访问权限。用户密码和所有者密码可以为null或空。如果输入的所有者密码为null或空，则所有者密码将被随机字符串替换。KeySize和Algorithm值有6种可能的组合。然而（KeySize.x40，Algorithm.AES）和（KeySize.x256，Algorithm.RC4）是无效的，如果遇到这种组合，将引发相应的异常。如果处理失败，则抛出异常。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | 将PDF文档保存到指定的流。 |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | 将PDF文档保存到指定的文件。 |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | 使用空的用户/所有者密码设置Pdf文件安全性。所有者密码将由随机字符串添加。如果处理失败，则抛出异常。 |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | 使用原始密码设置Pdf文件安全性。如果处理失败，则抛出异常。 |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | 通过所有者密码更改用户密码和所有者密码，保持原始安全设置。新用户密码和新所有者密码可以为null或空。如果新所有者密码为null或空，则所有者密码将被随机字符串替换。如果处理失败，则不抛出异常。 |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | 通过所有者密码更改用户密码和密码，允许重置Pdf文档安全性。新用户密码和新所有者密码可以为null或空。如果新所有者密码为null或空，则所有者密码将被随机字符串替换。如果处理失败，则不抛出异常。 |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | 通过所有者密码更改用户密码和密码，允许重置Pdf文档安全性。新用户密码和新所有者密码可以为null或空。如果新所有者密码为null或空，则所有者密码将被随机字符串替换。KeySize和Algorithm值有6种可能的组合。然而（KeySize.x40，Algorithm.AES）和（KeySize.x256，Algorithm.RC4）是无效的，如果遇到这种组合，将引发相应的异常。如果处理失败，则不抛出异常。 |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | 通过所有者密码解密加密的Pdf文档。如果文档没有所有者密码，则允许使用用户密码。如果处理失败，则不抛出异常。 |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | 使用用户密码和所有者密码加密Pdf文件，并设置文档的访问权限。用户密码和所有者密码可以为null或空。如果输入的所有者密码为null或空，则所有者密码将被随机字符串替换。如果处理失败，则不抛出异常。 |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | 使用原始密码设置Pdf文件安全性。如果处理失败，则不抛出异常。 |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)