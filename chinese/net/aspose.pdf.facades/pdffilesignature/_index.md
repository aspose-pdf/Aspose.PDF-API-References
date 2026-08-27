---
title: "类 PdfFileSignature"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Facades.PdfFileSignature 类。表示用于使用证书签署 pdf 文件的类"
type: docs
weight: 4680
url: /zh/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

表示使用证书对 pdf 文件进行签名的类。

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | PdfFileSignature 类的构造函数。 |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | 基于 *document* 初始化新的 `PdfFileSignature` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取正在操作的 document facade。 |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | 获取确定 document 是否已认证的标志。 |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | 获取已启用 LTV 的标志。 |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | 设置或获取签名的图形外观。属性值表示图像文件名。 |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | 设置或获取签名的图形外观。属性值表示图像流。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化 facade。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | 绑定用于编辑的 Pdf 流。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | 绑定用于编辑的 Pdf 文件。 |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | 使用已放置在现有签名字段中的 MDP 签名对 document 进行认证。签名之前，签名字段必须为空，即字段不得包含签名字典。因此 pdf document 已经拥有签名字段，您无需提供签名的放置位置，对应的 page 和 rectangle 将从通过签名名称（参见 sigName 参数）找到的签名字段中获取。 |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | 使用 MDP 签名对 document 进行认证。签名原因、联系信息和位置等数据必须通过 Signature 对象 sig 的相应属性提供。 |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | 关闭 facade。 |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | 检查 PDF 是否具有数字签名。 |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | 检查 PDF 是否具有使用权限。 |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | 检查签名是否覆盖整个文档。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 释放 facade。 |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | 提取签名的单个 X.509 证书为流。 |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | 提取签名的图像。 |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | 返回经 MDP 签名类型认证的文档的访问权限值。 |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | 获取所有空签名字段的名称。 |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | 获取签名的联系信息。 |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | 获取签名的日期时间。 |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | 获取签名的位置。 |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | 获取签名的原因。 |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | 获取签名的修订版本。 |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | 获取所有非空签名的名称。 |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | 检索 PDF 文档中所有签名算法的信息。 |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | 获取签署 PDF 文档的个人或组织的名称。 |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | 获取总修订次数。 |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | 根据签名名称删除签名。 |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | 根据签名名称删除签名。 |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | 删除所有签名。 |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | 删除使用权限条目。 |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | 将结果 PDF 保存到流中。 |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | 将结果 PDF 保存到文件中。 |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | 设置证书文件和密码以进行签名操作。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | 使用给定类型的签名对文档进行签名，该签名放置在已存在的签名字段中。签名前，签名字段必须为空，即字段不能包含签名字典。因此 PDF 文档已经拥有签名字段，无需提供签名的放置位置，相关的页码和矩形会从通过签名名称（参见 SigName 参数）找到的签名字段中获取。签名原因、联系信息和位置等数据必须通过 Signature object sig 的相应属性提供。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | 使用给定类型的签名对文档进行签名。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | 使用给定类型的签名对文档进行签名，该签名放置在已存在的签名字段中。签名前，签名字段必须为空，即字段不能包含签名字典。因此 PDF 文档已经拥有签名字段，无需提供签名的放置位置，相关的页码和矩形会从通过签名名称（参见 SigName 参数）找到的签名字段中获取。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | 在 PDF 文档上创建签名。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | 使用给定类型的签名对文档进行签名。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | 使用已放置在现有签名字段中的给定类型签名对文档进行签名。签名之前，pdf 文档应已经具有签名字段，相关页面和矩形从通过签名名称（参见 SigName 参数）找到的签名字段中获取。 |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate)(SignatureName, out Stream) | 提取签名的单个 X.509 证书为流。 |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate_1)(SignatureName, out X509Certificate2) | 提取签名的单个 X.509 证书。 |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | 检查签名的有效性。 |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_2)(SignatureName, X509Certificate2) | 检查签名的有效性。验证使用外部公钥证书进行。 |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | 检查签名的有效性。 |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_3)(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) | 检查签名的有效性。验证使用外部公钥证书进行。 |

### 另请参见

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


