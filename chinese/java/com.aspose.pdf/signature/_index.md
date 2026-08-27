---
title: "Signature"
linktitle: "Signature"
second_title: "Aspose.PDF for Java API 参考"
description: "一个抽象类，表示 PDF 文档中的签名对象。签名是具有签名对象值的字段，后者包含用于验证的数据信息。"
type: docs
weight: 4490
url: /zh/java/com.aspose.pdf/signature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature

```
public abstract class Signature extends Object
```

抽象类，表示 PDF 文档中的签名对象。签名是包含签名对象值的字段，后者包含用于验证文档有效性的数据。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Signature](#Signature--) | 初始化 {@code Signature} 类的新实例。 |
| [Signature](#Signature-java.io.InputStream-java.lang.String-) | 初始化 {@code Signature} 类的新实例。 |
| [Signature](#Signature-java.lang.String-java.lang.String-) | 初始化 {@code Signature} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [close](#close--) | 析构函数，关闭临时流（如有必要）。 |
| [getAuthority](#getAuthority--) | 签署文档的个人或机构的名称。 |
| [getByteRange](#getByteRange--) | 获取整数对数组（起始字节偏移量，字节长度），用于描述摘要计算的精确字节范围。 |
| [getContactInfo](#getContactInfo--) | 获取签署人提供的信息，以便收件人联系签署人验证签名，例如电话号码。 |
| [getCustomAppearance](#getCustomAppearance--) | 获取/设置自定义外观。 |
| [getCustomSign](#getCustomSign--) | 用于自定义哈希和签署文档的委托（Beta）。 {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [getCustomSignHash](#getCustomSignHash--) | 用于自定义签署文档哈希的委托（Beta）。 {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [getDate](#getDate--) | 获取签署时间。 |
| [getDefaultSignatureLength](#getDefaultSignatureLength--) | 获取或设置签名数据的默认长度（字节）。这是对签名长度的估计（字节）。如果设置了 {@code AvoidEstimatingSignatureLength}（{@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}）参数，则在通过 {@code CustomSignHash}（{@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}）进行签名时使用。默认值为 3000。 |
| [getImageInternal](#getImageInternal--) | 获取图像流。仅供内部使用 |
| [getLocation](#getLocation--) | 获取签署的 CPU 主机名或物理位置。 |
| [getOcspSettings](#getOcspSettings--) | 获取/设置 ocsp 设置。 |
| [getReason](#getReason--) | 获取签署原因，例如（I agreed!，Pip B.）。 |
| [getSignatureAlgorithmInfo](#getSignatureAlgorithmInfo--) | 检索签名中使用的签名算法信息。 |
| [getSignatureReferences](#getSignatureReferences--) | 获取签名引用 |
| [getTimestampSettings](#getTimestampSettings--) | 获取时间戳设置。 |
| [getUseLtv](#getUseLtv--) | 获取/设置 ltv 验证标志。 |
| [isAvoidEstimatingSignatureLength](#isAvoidEstimatingSignatureLength--) | 获取并设置一个选项，表示是否避免估计签名长度。在签署文档之前避免估计签名长度。用于通过 {@code CustomSignHash}（{@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}）以及 {@code ExternalSignature} 进行签名。如果 {@code CustomSignHash}（{@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}）返回的签名长度超过 {@code DefaultSignatureLength}（{@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}），则会抛出 {@code SignatureLengthMismatchException}。默认值为 {@code false}。 |
| [isShowProperties](#isShowProperties--) | 强制显示/隐藏签名属性。如果 ShowProperties 为 true，签名字段具有预定义的外观格式（字符串表示）： ------------------------------------------- 由 {certificate subject} 数字签名 日期: {signature.Date} 原因: {signature.Reason} 位置: {signature.Location} ------------------------------------------- 其中 {X} 为 X 值的占位符。签名也可以包含图像，在这种情况下上述字符串会放置在图像上。ShowProperties 默认为 true。 |
| [setAuthority](#setAuthority-java.lang.String-) | 设置签署文档的个人或机构名称。 |
| [setAvoidEstimatingSignatureLength](#setAvoidEstimatingSignatureLength-boolean-) | 获取并设置一个选项，表示是否避免估计签名长度。在签署文档之前避免估计签名长度。用于通过 {@code CustomSignHash}（{@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}）以及 {@code ExternalSignature} 进行签名。如果 {@code CustomSignHash}（{@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}）返回的签名长度超过 {@code DefaultSignatureLength}（{@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}），则会抛出 {@code SignatureLengthMismatchException}。默认值为 {@code false}。 |
| [setContactInfo](#setContactInfo-java.lang.String-) | 设置签署人提供的信息，以便收件人联系签署人验证签名，例如电话号码。 |
| [setCustomAppearance](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | 获取/设置自定义外观。 |
| [setCustomSign](#setCustomSign-com.aspose.pdf.CustomSign-) | 用于自定义哈希和签署文档的委托（Beta）。 {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [setCustomSignHash](#setCustomSignHash-com.aspose.pdf.SignHash-) | 用于自定义签署文档哈希的委托（Beta）。 {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [setDate](#setDate-java.util.Date-) | 设置签署时间。 |
| [setDefaultSignatureLength](#setDefaultSignatureLength-int-) | 获取或设置签名数据的默认长度（字节）。这是对签名长度的估计（字节）。如果设置了 {@code AvoidEstimatingSignatureLength}（{@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}）参数，则在通过 {@code CustomSignHash}（{@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}）进行签名时使用。默认值为 3000。 |
| [setImage](#setImage-java.io.InputStream-) | 设置图像流。 |
| [setImageInternal](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [setLocation](#setLocation-java.lang.String-) | 设置签署的 CPU 主机名或物理位置。 |
| [setOcspSettings](#setOcspSettings-com.aspose.pdf.OcspSettings-) | 获取/设置 ocsp 设置。 |
| [setReason](#setReason-java.lang.String-) | 设置签署原因，例如（I agreed!，Pip B.）。 |
| [setShowProperties](#setShowProperties-boolean-) | 强制显示/隐藏签名属性。如果 ShowProperties 为 true，签名字段具有预定义的外观格式（字符串表示）： ------------------------------------------- 由 {certificate subject} 数字签名 日期: {signature.Date} 原因: {signature.Reason} 位置: {signature.Location} ------------------------------------------- 其中 {X} 为 X 值的占位符。签名也可以包含图像，在这种情况下上述字符串会放置在图像上。ShowProperties 默认为 true。 |
| [setTimestampSettings](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | 设置时间戳设置。 |
| [setUseLtv](#setUseLtv-boolean-) | 获取/设置 ltv 验证标志。 |
| [verify](#verify--) | 验证文档中此签名，若文档有效返回 true，否则返回 false。 |
| [verify](#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | 验证文档中此签名，若文档有效返回 true，否则返回 false。 |
| [verify](#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | 验证文档中此签名，若文档有效返回 true，否则返回 false。 |

### Signature {#Signature--}
```
public Signature()
```

初始化 {@code Signature} 类的新实例。

### Signature {#Signature-java.io.InputStream-java.lang.String-}
初始化 {@code Signature} 类的新实例。

### Signature {#Signature-java.lang.String-java.lang.String-}
初始化 {@code Signature} 类的新实例。

### close {#close--}
```
public void close()
```

析构函数，关闭临时流（如有必要）。

### getAuthority {#getAuthority--}
```
public final String getAuthority()
```

签署文档的个人或机构的名称。

**Returns:**
字符串值

### getByteRange {#getByteRange--}
```
public int[] getByteRange()
```

获取整数对数组（起始字节偏移量，字节长度），用于描述摘要计算的精确字节范围。

**Returns:**
int 数组值

### getContactInfo {#getContactInfo--}
```
public String getContactInfo()
```

获取签署人提供的信息，以便收件人联系签署人验证签名，例如电话号码。

**Returns:**
字符串值

### getCustomAppearance {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```

获取/设置自定义外观。

**Returns:**
SignatureCustomAppearance 实例

### getCustomSign {#getCustomSign--}
```
public final CustomSign getCustomSign()
```

用于自定义哈希和签署文档的委托（Beta）。 {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

**Returns:**
SignHash 实例

### getCustomSignHash {#getCustomSignHash--}
```
public final SignHash getCustomSignHash()
```

用于自定义签署文档哈希的委托（Beta）。 {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

**Returns:**
SignHash 实例

### getDate {#getDate--}
```
public Date getDate()
```

获取签署时间。

**Returns:**
Date 值

### getDefaultSignatureLength {#getDefaultSignatureLength--}
```
public final int getDefaultSignatureLength()
```

获取或设置签名数据的默认长度（字节）。这是对签名长度的估计（字节）。如果设置了 {@code AvoidEstimatingSignatureLength}（{@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}）参数，则在通过 {@code CustomSignHash}（{@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}）进行签名时使用。默认值为 3000。

**Returns:**
int 值

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.IO.Stream getImageInternal()
```

获取图像流。仅供内部使用

**Returns:**
Stream 对象

### getLocation {#getLocation--}
```
public String getLocation()
```

获取签署的 CPU 主机名或物理位置。

**Returns:**
字符串值

### getOcspSettings {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```

获取/设置 ocsp 设置。

**Returns:**
OcspSettings 实例

### getReason {#getReason--}
```
public String getReason()
```

获取签署原因，例如（I agreed!，Pip B.）。

**Returns:**
字符串值

### getSignatureAlgorithmInfo {#getSignatureAlgorithmInfo--}
```
public final com.aspose.pdf.engine.security.SignatureAlgorithmInfo getSignatureAlgorithmInfo()
```

检索签名中使用的签名算法信息。

**Returns:**
一个 { SignatureAlgorithmInfo} 实例，包含有关签名算法的详细信息。

### getSignatureReferences {#getSignatureReferences--}
```
public List <com.aspose.pdf.engine.security.impl.signatures.SignatureReference> getSignatureReferences()
```

获取签名引用

**Returns:**
{@code java.util.List<SignatureReference> 对象}

### getTimestampSettings {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```

获取时间戳设置。

**Returns:**
TimestampSettings

### getUseLtv {#getUseLtv--}
```
public final boolean getUseLtv()
```

获取/设置 ltv 验证标志。

**Returns:**
布尔值

### isAvoidEstimatingSignatureLength {#isAvoidEstimatingSignatureLength--}
```
public final boolean isAvoidEstimatingSignatureLength()
```

获取并设置一个选项，表示是否避免估计签名长度。在签署文档之前避免估计签名长度。用于通过 {@code CustomSignHash}（{@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}）以及 {@code ExternalSignature} 进行签名。如果 {@code CustomSignHash}（{@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}）返回的签名长度超过 {@code DefaultSignatureLength}（{@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}），则会抛出 {@code SignatureLengthMismatchException}。默认值为 {@code false}。

**Returns:**
布尔值

### isShowProperties {#isShowProperties--}
```
public boolean isShowProperties()
```

强制显示/隐藏签名属性。如果 ShowProperties 为 true，签名字段具有预定义的外观格式（字符串表示）： ------------------------------------------- 由 {certificate subject} 数字签名 日期: {signature.Date} 原因: {signature.Reason} 位置: {signature.Location} ------------------------------------------- 其中 {X} 为 X 值的占位符。签名也可以包含图像，在这种情况下上述字符串会放置在图像上。ShowProperties 默认为 true。

**Returns:**
布尔值

### setAuthority {#setAuthority-java.lang.String-}
设置签署文档的个人或机构名称。

### setAvoidEstimatingSignatureLength {#setAvoidEstimatingSignatureLength-boolean-}
```
public final void setAvoidEstimatingSignatureLength(boolean value)
```

获取并设置一个选项，表示是否避免估计签名长度。在签署文档之前避免估计签名长度。用于通过 {@code CustomSignHash}（{@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}）以及 {@code ExternalSignature} 进行签名。如果 {@code CustomSignHash}（{@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}）返回的签名长度超过 {@code DefaultSignatureLength}（{@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}），则会抛出 {@code SignatureLengthMismatchException}。默认值为 {@code false}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setContactInfo {#setContactInfo-java.lang.String-}
设置签署人提供的信息，以便收件人联系签署人验证签名，例如电话号码。

### setCustomAppearance {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
获取/设置自定义外观。

### setCustomSign {#setCustomSign-com.aspose.pdf.CustomSign-}
用于自定义哈希和签署文档的委托（Beta）。 {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

### setCustomSignHash {#setCustomSignHash-com.aspose.pdf.SignHash-}
用于自定义签署文档哈希的委托（Beta）。 {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

### setDate {#setDate-java.util.Date-}
设置签署时间。

### setDefaultSignatureLength {#setDefaultSignatureLength-int-}
```
public final void setDefaultSignatureLength(int value)
```

获取或设置签名数据的默认长度（字节）。这是对签名长度的估计（字节）。如果设置了 {@code AvoidEstimatingSignatureLength}（{@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}）参数，则在通过 {@code CustomSignHash}（{@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}）进行签名时使用。默认值为 3000。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setImage {#setImage-java.io.InputStream-}
设置图像流。

### setImageInternal {#setImageInternal-com.aspose.ms.System.IO.Stream-}


### setLocation {#setLocation-java.lang.String-}
设置签署的 CPU 主机名或物理位置。

### setOcspSettings {#setOcspSettings-com.aspose.pdf.OcspSettings-}
获取/设置 ocsp 设置。

### setReason {#setReason-java.lang.String-}
设置签署原因，例如（I agreed!，Pip B.）。

### setShowProperties {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```

强制显示/隐藏签名属性。如果 ShowProperties 为 true，签名字段具有预定义的外观格式（字符串表示）： ------------------------------------------- 由 {certificate subject} 数字签名 日期: {signature.Date} 原因: {signature.Reason} 位置: {signature.Location} ------------------------------------------- 其中 {X} 为 X 值的占位符。签名也可以包含图像，在这种情况下上述字符串会放置在图像上。ShowProperties 默认为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setTimestampSettings {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
设置时间戳设置。

### setUseLtv {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```

获取/设置 ltv 验证标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### verify {#verify--}
```
public boolean verify()
```

验证文档中此签名，若文档有效返回 true，否则返回 false。

**Returns:**
如果文档有效，则为 true。

### verify {#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
验证文档中此签名，若文档有效返回 true，否则返回 false。

**Returns:**
如果文档有效，则为 true。

### verify {#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
验证文档中此签名，若文档有效返回 true，否则返回 false。

**Returns:**
如果文档有效，则为 true。
