---
title: "PdfFileSignature"
linktitle: "PdfFileSignature"
second_title: "Aspose.PDF for Java API 参考"
description: "表示使用证书对 PDF 文件进行签名的类。"
type: docs
weight: 530
url: /zh/java/com.aspose.pdf.facades/pdffilesignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSignature

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSignature extends SaveableFacade
```

表示使用证书对 PDF 文件进行签名的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileSignature](#PdfFileSignature--) | PdfFileSignature 类的构造函数。 |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-) | PdfFileSignature 类的构造函数。 |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-) | PdfFileSignature 类的构造函数。 |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-) | PdfFileSignature 类的构造函数。 |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-java.lang.String-) | PdfFileSignature 类的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | 绑定用于编辑的 Pdf 流。 |
| [bindPdf](#bindPdf-java.lang.String-) | 绑定用于编辑的 Pdf 文件。 |
| [certify](#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-) | 使用 MDP 签名对文档进行认证。 |
| [certify](#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-) | 使用已放置在现有签名字段中的 MDP 签名对文档进行认证。签名之前，签名字段必须为空，即字段不能包含签名字典。因此，PDF 文档已经拥有签名字段，您不需要提供签名的放置位置，相关的页面和矩形将从通过签名名称（参见 sigName 参数）找到的签名字段中获取。 |
| [close](#close--) | 关闭该外观。 |
| [containsSignature](#containsSignature--) | 检查 PDF 是否具有数字签名。 |
| [containsUsageRights](#containsUsageRights--) | 检查 PDF 是否具有使用权限。 |
| [coversWholeDocument](#coversWholeDocument-com.aspose.pdf.facades.SignatureName-) | 检查签名是否覆盖整个文档。 |
| [coversWholeDocument](#coversWholeDocument-java.lang.String-) | 检查签名是否覆盖整个文档。 |
| [dispose](#dispose--) | 关闭 facade。此方法已过时，请改用 close()。 |
| [extractCertificate](#extractCertificate-com.aspose.pdf.facades.SignatureName-) | 提取签名的单个 X.509 证书为流。 |
| [extractCertificate](#extractCertificate-java.lang.String-) | 提取签名的单个 X.509 证书为流。 |
| [extractImage](#extractImage-com.aspose.pdf.facades.SignatureName-) | 提取签名的图像。 |
| [extractImage](#extractImage-java.lang.String-) | 提取签名的图像。 |
| [getAccessPermissions](#getAccessPermissions--) | 返回经 MDP 签名类型认证的文档的访问权限值。 |
| [getBlankSignNames](#getBlankSignNames--) | 获取所有空签名字段的名称。 |
| [getContactInfo](#getContactInfo-com.aspose.pdf.facades.SignatureName-) | 获取签名的联系信息。 |
| [getContactInfo](#getContactInfo-java.lang.String-) | 获取签名的联系信息。 |
| [getDateTime](#getDateTime-com.aspose.pdf.facades.SignatureName-) | 获取签名的日期时间。 |
| [getDateTime](#getDateTime-java.lang.String-) | 获取签名的日期时间。 |
| [getLocation](#getLocation-com.aspose.pdf.facades.SignatureName-) | 获取签名的位置。 |
| [getLocation](#getLocation-java.lang.String-) | 获取签名的位置。 |
| [getReason](#getReason-com.aspose.pdf.facades.SignatureName-) | 获取签名的原因。 |
| [getReason](#getReason-java.lang.String-) | 获取签名的原因。 |
| [getRevision](#getRevision-com.aspose.pdf.facades.SignatureName-) | 获取签名的修订版本。 |
| [getRevision](#getRevision-java.lang.String-) | 获取签名的修订版本。 |
| [getSignatureAppearance](#getSignatureAppearance--) | 获取签名的图形外观。属性值表示图像文件名。 |
| [getSignatureAppearanceStream](#getSignatureAppearanceStream--) | 获取签名的图形外观。属性值表示图像流。 |
| [getSignatureNames](#getSignatureNames--) | / * <p> / * 获取所有非空签名的名称。 / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / * |
| [getSignatureNames](#getSignatureNames-boolean-) | 获取所有非空签名的名称。 string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision()); |
| [getSignaturesInfo](#getSignaturesInfo--) | 检索 PDF 文档中所有签名算法的信息。 |
| [getSignerName](#getSignerName-com.aspose.pdf.facades.SignatureName-) | 获取签署 PDF 文档的个人或组织的名称。 |
| [getSignerName](#getSignerName-java.lang.String-) | 获取签署 PDF 文档的个人或组织的名称。 |
| [getSignNames](#getSignNames--) | <p> 获取所有非空签名的名称。 </p> <hr> |
| [getSignNames](#getSignNames-boolean-) | <p> 获取所有非空签名的名称。 </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre> |
| [getTotalRevision](#getTotalRevision--) | 获取总修订次数。 |
| [isCertified](#isCertified--) | 获取用于确定文档是否已认证的标志。 |
| [isContainSignature](#isContainSignature--) | 检查 PDF 是否具有数字签名。 |
| [isCoversWholeDocument](#isCoversWholeDocument-java.lang.String-) | 检查签名是否覆盖整个文档。 |
| [isLtvEnabled](#isLtvEnabled--) | 获取 LTV 启用标志。 |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-) | 根据签名名称移除签名。 string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-) | 根据签名名称移除签名。 string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-java.lang.String-) | <p> 根据签名名称移除签名。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignature](#removeSignature-java.lang.String-boolean-) | <p> 根据签名名称移除签名。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignatures](#removeSignatures--) | 移除所有签名。 string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeUsageRights](#removeUsageRights--) | 移除使用权条目。 |
| [save](#save--) | 保存已签名的 PDF 文件。必须先使用相应的 PdfFileSignature 构造函数提供输出文件名。 |
| [save](#save-java.io.OutputStream-) | 保存已签名的 PDF 文件。必须先使用相应的 PdfFileSignature 构造函数提供输出文件名。 |
| [save](#save-java.lang.String-) | 保存已签名的 PDF 文件。必须先使用相应的 PdfFileSignature 构造函数提供输出文件名。 |
| [setCertificate](#setCertificate-java.lang.String-java.lang.String-) | 设置证书文件和密码用于签名过程。 |
| [setSignatureAppearance](#setSignatureAppearance-java.lang.String-) | 设置签名的图形外观。属性值表示图像文件名。 |
| [setSignatureAppearanceStream](#setSignatureAppearanceStream-java.io.InputStream-) | 设置签名的图形外观。属性值表示图像流。 |
| [sign](#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | 使用给定类型的签名对文档进行签名。 |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-) | 在 PDF 文档上创建签名。 |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | 使用给定类型的签名对文档进行签名。 |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | 使用给定类型的签名对文档进行签名，该签名放置在已存在的签名字段中。 |
| [sign](#sign-java.lang.String-com.aspose.pdf.Signature-) | <p> 使用给定类型的签名对文档进行签名，该签名放置在已存在的签名字段中。签名之前，签名字段必须为空，即字段不能包含签名字典。因此 PDF 文档已经有签名字段，您不需要提供签名的放置位置，相关的页码和矩形会从通过签名名称找到的签名字段中获取（参见 SigName 参数）。签名原因、联系人和位置等信息必须通过 Signature 对象 sig 的相应属性提供。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre> |
| [sign](#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-) | <p> 使用给定类型的签名对文档进行签名，该签名放置在已存在的签名字段中。签名之前，签名字段必须为空，即字段不能包含签名字典。因此 PDF 文档已经有签名字段，您不需要提供签名的放置位置，相关的页码和矩形会从通过签名名称找到的签名字段中获取（参见 SigName 参数）。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre> |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-) | 提取签名的单个 X.509 证书为流。 |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-) | 提取签名的单个 X.509 证书。 |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-) | 检查签名的有效性。 |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | 检查签名的有效性。 |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | 检查签名的有效性。 |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | 检查签名的有效性。 |
| [verifySignature](#verifySignature-java.lang.String-) | 检查签名的有效性。 |
| [verifySignature](#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | 检查签名的有效性。 |
| [verifySigned](#verifySigned-java.lang.String-) | 检查签名的有效性。此方法已弃用，并将在 25.1 版本中删除。请改用 VerifySignature 方法。 |

### PdfFileSignature {#PdfFileSignature--}
```
public PdfFileSignature()
```

PdfFileSignature 类的构造函数。

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-}
PdfFileSignature 类的构造函数。

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-}
PdfFileSignature 类的构造函数。

### PdfFileSignature {#PdfFileSignature-java.lang.String-}
PdfFileSignature 类的构造函数。

### PdfFileSignature {#PdfFileSignature-java.lang.String-java.lang.String-}
PdfFileSignature 类的构造函数。

### bindPdf {#bindPdf-java.io.InputStream-}
绑定用于编辑的 Pdf 流。

### bindPdf {#bindPdf-java.lang.String-}
绑定用于编辑的 Pdf 文件。

### certify {#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-}
使用 MDP 签名对文档进行认证。

### certify {#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-}
使用已放置在现有签名字段中的 MDP 签名对文档进行认证。签名之前，签名字段必须为空，即字段不能包含签名字典。因此，PDF 文档已经拥有签名字段，您不需要提供签名的放置位置，相关的页面和矩形将从通过签名名称（参见 sigName 参数）找到的签名字段中获取。

### close {#close--}
```
public void close()
```

关闭该外观。

### containsSignature {#containsSignature--}
```
public boolean containsSignature()
```

检查 PDF 是否具有数字签名。

**Returns:**
返回布尔类型的结果。

### containsUsageRights {#containsUsageRights--}
```
public boolean containsUsageRights()
```

检查 PDF 是否具有使用权限。

**Returns:**
返回布尔类型的结果。

### coversWholeDocument {#coversWholeDocument-com.aspose.pdf.facades.SignatureName-}
检查签名是否覆盖整个文档。

### coversWholeDocument {#coversWholeDocument-java.lang.String-}
检查签名是否覆盖整个文档。

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

关闭 facade。此方法已过时，请改用 close()。

### extractCertificate {#extractCertificate-com.aspose.pdf.facades.SignatureName-}
提取签名的单个 X.509 证书为流。

### extractCertificate {#extractCertificate-java.lang.String-}
提取签名的单个 X.509 证书为流。

### extractImage {#extractImage-com.aspose.pdf.facades.SignatureName-}
提取签名的图像。

### extractImage {#extractImage-java.lang.String-}
提取签名的图像。

### getAccessPermissions {#getAccessPermissions--}
```
public DocMDPAccessPermissions getAccessPermissions()
```

返回经 MDP 签名类型认证的文档的访问权限值。

**Returns:**
PdfException 如果文档正在进行认证，则返回访问权限值；否则抛出异常。 @see com.aspose.pdf.DocMDPAccessPermissions

### getBlankSignNames {#getBlankSignNames--}
```
@Deprecated public List < String > getBlankSignNames()
```

获取所有空签名字段的名称。

**Returns:**
返回一个 arrayList。 @deprecated 请改用 GetBlankSignatureNames()。

### getContactInfo {#getContactInfo-com.aspose.pdf.facades.SignatureName-}
获取签名的联系信息。

### getContactInfo {#getContactInfo-java.lang.String-}
获取签名的联系信息。

### getDateTime {#getDateTime-com.aspose.pdf.facades.SignatureName-}
获取签名的日期时间。

### getDateTime {#getDateTime-java.lang.String-}
获取签名的日期时间。

### getLocation {#getLocation-com.aspose.pdf.facades.SignatureName-}
获取签名的位置。

### getLocation {#getLocation-java.lang.String-}
获取签名的位置。

### getReason {#getReason-com.aspose.pdf.facades.SignatureName-}
获取签名的原因。

### getReason {#getReason-java.lang.String-}
获取签名的原因。

### getRevision {#getRevision-com.aspose.pdf.facades.SignatureName-}
获取签名的修订版本。

### getRevision {#getRevision-java.lang.String-}
获取签名的修订版本。

### getSignatureAppearance {#getSignatureAppearance--}
```
public String getSignatureAppearance()
```

获取签名的图形外观。属性值表示图像文件名。

**Returns:**
字符串值

### getSignatureAppearanceStream {#getSignatureAppearanceStream--}
```
public InputStream getSignatureAppearanceStream()
```

获取签名的图形外观。属性值表示图像流。

**Returns:**
InputStream 元素

### getSignatureNames {#getSignatureNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames()
```

/ * <p> / * 获取所有非空签名的名称。 / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / *

**Returns:**
返回一个 IList<SignatureName>。 /

### getSignatureNames {#getSignatureNames-boolean-}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames(boolean onlyActive)
```

获取所有非空签名的名称。 string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholedocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision());

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| onlyActive |  | 如果为 true，则仅返回活动签名；否则返回所有签名。 |

**Returns:**
返回一个 IList<SignatureName>。

### getSignaturesInfo {#getSignaturesInfo--}
```
public final List <com.aspose.pdf.engine.security.SignatureAlgorithmInfo> getSignaturesInfo()
```

检索 PDF 文档中所有签名算法的信息。

**Returns:**
包含每个签名信息的 {@link SignatureAlgorithmInfo} 实例列表。

### getSignerName {#getSignerName-com.aspose.pdf.facades.SignatureName-}
获取签署 PDF 文档的个人或组织的名称。

### getSignerName {#getSignerName-java.lang.String-}
获取签署 PDF 文档的个人或组织的名称。

### getSignNames {#getSignNames--}
```
public final List < String > getSignNames()
```

<p> 获取所有非空签名的名称。 </p> <hr>

**Returns:**
返回一个 arrayList。

### getSignNames {#getSignNames-boolean-}
```
@Deprecated public List < String > getSignNames(boolean onlyActive)
```

<p> 获取所有非空签名的名称。 </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholedocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| onlyActive |  | 布尔值，如果为 true，则仅返回活动签名；否则返回所有签名。 |

**Returns:**
返回一个 arrayList。 @deprecated 该方法可能产生相同的签名名称，在验证期间无法区分。请改用 getSignatureNames(boolean onlyActive)。

### getTotalRevision {#getTotalRevision--}
```
public int getTotalRevision()
```

获取总修订次数。

**Returns:**
返回签名修订的总数。

### isCertified {#isCertified--}
```
public boolean isCertified()
```

获取用于确定文档是否已认证的标志。

**Returns:**
布尔值

### isContainSignature {#isContainSignature--}
```
@Deprecated public boolean isContainSignature()
```

检查 PDF 是否具有数字签名。

**Returns:**
返回布尔类型的结果。

### isCoversWholeDocument {#isCoversWholeDocument-java.lang.String-}
检查签名是否覆盖整个文档。

### isLtvEnabled {#isLtvEnabled--}
```
public final boolean isLtvEnabled()
```

获取 LTV 启用标志。

**Returns:**
布尔值

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-}
根据签名名称移除签名。 string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-}
根据签名名称移除签名。 string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-java.lang.String-}
<p> 根据签名名称移除签名。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignature {#removeSignature-java.lang.String-boolean-}
<p> 根据签名名称移除签名。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignatures {#removeSignatures--}
```
public final void removeSignatures()
```

移除所有签名。 string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf");

### removeUsageRights {#removeUsageRights--}
```
public void removeUsageRights()
```

移除使用权条目。

### save {#save--}
```
@Deprecated public void save()
```

保存已签名的 PDF 文件。必须先使用相应的 PdfFileSignature 构造函数提供输出文件名。

### save {#save-java.io.OutputStream-}
保存已签名的 PDF 文件。必须先使用相应的 PdfFileSignature 构造函数提供输出文件名。

### save {#save-java.lang.String-}
保存已签名的 PDF 文件。必须先使用相应的 PdfFileSignature 构造函数提供输出文件名。

### setCertificate {#setCertificate-java.lang.String-java.lang.String-}
设置证书文件和密码用于签名过程。

### setSignatureAppearance {#setSignatureAppearance-java.lang.String-}
设置签名的图形外观。属性值表示图像文件名。

### setSignatureAppearanceStream {#setSignatureAppearanceStream-java.io.InputStream-}
设置签名的图形外观。属性值表示图像流。

### sign {#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
使用给定类型的签名对文档进行签名。

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-}
在 PDF 文档上创建签名。

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
使用给定类型的签名对文档进行签名。

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
使用给定类型的签名对文档进行签名，该签名放置在已存在的签名字段中。

### sign {#sign-java.lang.String-com.aspose.pdf.Signature-}
<p> 使用给定类型的签名对文档进行签名，该签名放置在已存在的签名字段中。签名之前，签名字段必须为空，即字段不能包含签名字典。因此 PDF 文档已经有签名字段，您不需要提供签名的放置位置，相关的页码和矩形会从通过签名名称找到的签名字段中获取（参见 SigName 参数）。签名原因、联系人和位置等信息必须通过 Signature 对象 sig 的相应属性提供。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre>

### sign {#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-}
<p> 使用给定类型的签名对文档进行签名，该签名放置在已存在的签名字段中。签名之前，签名字段必须为空，即字段不能包含签名字典。因此 PDF 文档已经有签名字段，您不需要提供签名的放置位置，相关的页码和矩形会从通过签名名称找到的签名字段中获取（参见 SigName 参数）。 </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre>

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-}
提取签名的单个 X.509 证书为流。

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-}
提取签名的单个 X.509 证书。

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-}
检查签名的有效性。

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
检查签名的有效性。

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
检查签名的有效性。

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
检查签名的有效性。

### verifySignature {#verifySignature-java.lang.String-}
检查签名的有效性。

### verifySignature {#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
检查签名的有效性。

### verifySigned {#verifySigned-java.lang.String-}
检查签名的有效性。此方法已弃用，并将在 25.1 版本中删除。请改用 VerifySignature 方法。
