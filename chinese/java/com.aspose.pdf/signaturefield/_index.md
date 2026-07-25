---
title: "SignatureField"
linktitle: "SignatureField"
second_title: "Aspose.PDF for Java API 参考"
description: "表示签名表单字段。"
type: docs
weight: 4510
url: /zh/java/com.aspose.pdf/signaturefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Field, com.aspose.pdf.SignatureField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class SignatureField extends Field
```

表示签名表单字段。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SignatureField](#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | 初始化 {@code SignatureField} 类的新实例。 |
| [SignatureField](#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 初始化 {@code SignatureField} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [clear](#clear--) | 从字段中移除签名对象。 |
| [extractCertificate](#extractCertificate--) | 以流的形式提取 DER 格式的单个 X.509 证书。 |
| [extractCertificateObject](#extractCertificateObject--) | 提取单个 X.509 证书对象。 |
| [extractImage](#extractImage--) | 提取签名的图像为 JPEG 编码的流。 |
| [extractImage](#extractImage-com.aspose.pdf.ImageType-) | 提取签名的图像为 JPEG 编码的流。 |
| [getSignature](#getSignature--) | 获取签名对象。此对象包含有关公钥密码标准的签名数据。类 {@code PKCS1}、{@code PKCS7} 和 {@code PKCS7Detached} 代表所有受支持的签名对象类型。 |
| [sign](#sign-com.aspose.pdf.Signature-) | 使用此签名字段对文档进行签名。 |
| [sign](#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-) | 使用此签名字段签署文档。 |

### SignatureField {#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
初始化 {@code SignatureField} 类的新实例。

### SignatureField {#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
初始化 {@code SignatureField} 类的新实例。

### clear {#clear--}
```
public void clear()
```

从字段中移除签名对象。

### extractCertificate {#extractCertificate--}
```
public InputStream extractCertificate()
```

以流的形式提取 DER 格式的单个 X.509 证书。

**Returns:**
如果找到证书，则返回单个 X.509 证书；否则返回 null。

### extractCertificateObject {#extractCertificateObject--}
```
public final com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 extractCertificateObject()
```

提取单个 X.509 证书对象。

**Returns:**
如果找到证书，则返回单个 X.509 证书；否则返回 null。

### extractImage {#extractImage--}
```
public InputStream extractImage()
```

提取签名的图像为 JPEG 编码的流。

**Returns:**
如果成功找到图像，则返回 JPEG 编码的流对象；否则返回 null。

### extractImage {#extractImage-com.aspose.pdf.ImageType-}
提取签名的图像为 JPEG 编码的流。

**Returns:**
如果成功找到图像，则返回 JPEG 编码的流对象；否则返回 null。

### getSignature {#getSignature--}
```
public final Signature getSignature()
```

获取签名对象。此对象包含有关公钥密码标准的签名数据。类 {@code PKCS1}、{@code PKCS7} 和 {@code PKCS7Detached} 代表所有受支持的签名对象类型。

**Returns:**
签名对象

### sign {#sign-com.aspose.pdf.Signature-}
使用此签名字段对文档进行签名。

### sign {#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-}
使用此签名字段签署文档。
