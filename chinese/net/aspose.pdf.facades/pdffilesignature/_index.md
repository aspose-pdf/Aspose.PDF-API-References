---
title: PdfFileSignature
second_title: Aspose.PDF for .NET API 参考
description: 代表一个类用证书签署一个pdf文件
type: docs
weight: 2570
url: /zh/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

代表一个类，用证书签署一个pdf文件。

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PdfFileSignature](pdffilesignature#constructor)() | PdfFileSignature 类的构造函数。 |
| [PdfFileSignature](pdffilesignature#constructor_1)(Document) | 初始化新的[`PdfFileSignature`](../pdffilesignature)对象基于*document*. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | 获取正在处理的文档外观。 |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified) { get; } | 获取确定文档是否经过认证的标志。 |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled) { get; } | 获取 LTV 启用标志。 |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance) { get; set; } | 设置或获取签名的图形外观。属性值代表图像文件名。 |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream) { get; set; } | 设置或获取签名的图形外观。属性值代表图像流。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | 初始化外观。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_1)(Stream) | 绑定 Pdf 流进行编辑。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_2)(string) | 绑定一个 Pdf 文件进行编辑。 |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify_1)(string, DocMDPSignature) | 用 MDP 签名证明文档已经存在签名字段。 签名前签名字段必须为空，即字段不能包含签名字典。 因此 pdf 文档已经有签名字段，你不应该提供的地方盖章签名， 对应的页面和矩形取自签名名称找到的签名字段（见sigName参数）。 |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | 用 MDP 签名证明文档。 签名原因、联系人和位置等数据必须由签名对象 sig 的相应属性提供。 |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close)() | 关闭门面。 |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature)() | 检查 pdf 是否有数字签名。 |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights)() | 检查 pdf 是否具有使用权限。 |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument)(string) | 检查签名是否覆盖整个文档。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | 处理外观。 |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate)(string) | 将签名的单个 X.509 证书提取为流。 |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage)(string) | 提取签名的图像。 |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions)() | 按MDP签名类型返回认证文档的访问权限值。 |
| [GetBlankSignNames](../../aspose.pdf.facades/pdffilesignature/getblanksignnames)() | 获取所有空签名字段的名称。 |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo)(string) | 获取签名的联系方式 |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime)(string) | 获取签名的日期时间。 |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation)(string) | 获取签名的位置。 |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason)(string) | 获取签名的原因。 |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision)(string) | 获取签名的修订版。 |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername)(string) | 获取签署 pdf 文档的个人或组织的名称。 |
| [GetSignNames](../../aspose.pdf.facades/pdffilesignature/getsignnames)(bool) | 获取所有非空签名的名称。 |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision)() | 获取总修订版。 |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature)(string) | 根据签名的名字去掉签名。 |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature_1)(string, bool) | 根据签名的名称删除签名。 |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights)() | 删除使用权限条目。 |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_1)(Stream) | 将结果 PDF 保存到流中。 |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_2)(string) | 将结果 PDF 保存到文件中。 |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate)(string, string) | 为签名例程设置证书文件和密码。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_4)(string, Signature) | 用给定类型的签名对文档进行签名，该签名放置在已经存在的签名字段中。 在签名之前签名字段必须为空，即字段不能包含签名字典。 因此pdf文档已经有签名字段，你不应该提供这个地方为签名盖章， 对应的页面和矩形取自签名名称（见SigName参数）找到的签名字段。 签名原因，联系人和位置等数据必须由签名对象sig的相应属性提供。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign)(int, bool, Rectangle, Signature) | 使用给定类型签名对文档进行签名。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_5)(string, string, string, string, Signature) | 用给定类型的签名对文档进行签名，该签名放置在已经存在的签名字段中。 在签名之前签名字段必须为空，即字段不能包含签名字典。 因此pdf文档已经有签名字段，你不应该提供这个地方为签名盖章， 对应的页面和矩形取自签名名称找到的签名字段（参见SigName参数）。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_1)(int, string, string, string, bool, Rectangle) | 在pdf文档上签名。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_2)(int, string, string, string, bool, Rectangle, Signature) | 使用给定类型签名对文档进行签名。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | 用给定类型的签名对文档进行签名，该签名放置在已经存在的签名字段中。 在签署 pdf 文档之前应该已经有签名字段，从签名名称找到的 签名字段中获取相应的页面和矩形（参见 SigName 参数） . |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature)(string) | 检查签名的有效性。 |
| [VerifySigned](../../aspose.pdf.facades/pdffilesignature/verifysigned)(string) | 检查签名的有效性。 |

### 也可以看看

* class [SaveableFacade](../saveablefacade)
* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
