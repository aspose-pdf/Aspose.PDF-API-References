---
title: Class PdfFileSignature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSignature 类。表示一个使用证书对 PDF 文件进行签名的类
type: docs
weight: 4560
url: /zh/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature 类

表示一个使用证书对 PDF 文件进行签名的类。

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
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 获取文档外观正在处理的文档。 |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | 获取确定文档是否经过认证的标志。 |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | 获取 LTV 启用标志。 |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | 设置或获取签名的图形外观。属性值表示图像文件名。 |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | 设置或获取签名的图形外观。属性值表示图像流。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 初始化外观。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | 绑定用于编辑的 PDF 流。 |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | 绑定用于编辑的 PDF 文件。 |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | 使用已呈现签名字段中的 MDP 签名对文档进行认证。在签名之前，签名字段必须为空，即字段不得包含签名字典。因此，PDF 文档已经具有签名字段，您不应提供印章签名的位置，相关页面和矩形是从通过签名名称找到的签名字段中获取的（请参见 sigName 参数）。 |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | 使用 MDP 签名对文档进行认证。签名原因、联系和位置等数据必须通过签名对象 sig 的相应属性提供。 |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | 关闭外观。 |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | 检查 PDF 是否具有数字签名。 |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | 检查 PDF 是否具有使用权。 |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | 检查签名是否覆盖整个文档。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 处理外观。 |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | 提取签名的单个 X.509 证书作为流。 |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | 提取签名的图像。 |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | 返回由 MDP 签名类型认证文档的访问权限值。 |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | 获取所有空签名字段的名称。 |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | 获取签名的联系信息。 |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | 获取签名的日期时间。 |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | 获取签名的位置。 |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | 获取签名的原因。 |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | 获取签名的修订版。 |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | 获取所有非空签名的名称。 |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | 检索 PDF 文档中存在的所有签名算法的信息。 |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | 获取签署 PDF 文档的个人或组织的名称。 |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | 获取总修订版。 |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | 根据签名名称移除签名。 |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | 根据签名名称移除签名。 |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | 移除所有签名。 |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | 移除使用权条目。 |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | 将结果 PDF 保存到流。 |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | 将结果 PDF 保存到文件。 |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | 设置用于签名例程的证书文件和密码。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | 使用已呈现签名字段中的给定类型签名对文档进行签名。在签名之前，签名字段必须为空，即字段不得包含签名字典。因此，PDF 文档已经具有签名字段，您不应提供印章签名的位置，相关页面和矩形是从通过签名名称找到的签名字段中获取的（请参见 SigName 参数）。签名原因、联系和位置等数据必须通过签名对象 sig 的相应属性提供。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | 使用给定类型签名对文档进行签名。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | 使用已呈现签名字段中的给定类型签名对文档进行签名。在签名之前，签名字段必须为空，即字段不得包含签名字典。因此，PDF 文档已经具有签名字段，您不应提供印章签名的位置，相关页面和矩形是从通过签名名称找到的签名字段中获取的（请参见 SigName 参数）。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | 在 PDF 文档上进行签名。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | 使用给定类型签名对文档进行签名。 |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | 使用已呈现签名字段中的给定类型签名对文档进行签名。在签名之前，PDF 文档应已经具有签名字段，相关页面和矩形是从通过签名名称找到的签名字段中获取的（请参见 SigName 参数）。 |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | 检查签名的有效性。 |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | 检查签名的有效性。 |

### 另请参阅

* 类 [SaveableFacade](../saveablefacade/)
* 命名空间 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../)