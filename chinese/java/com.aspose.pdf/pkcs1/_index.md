---
title: PKCS1
second_title: 用于 Java API 参考的 Aspose.PDF
description: 代表关于 PKCS1 标准的签名对象。
type: docs
weight: 254
url: /zh/java/com.aspose.pdf/pkcs1/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.Signature](../../com.aspose.pdf/signature)
```
public final class PKCS1 extends Signature
```

表示关于 PKCS 的签名对象\#1 标准。使用RSA加密算法和SHA-1摘要方法进行签名。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PKCS1(InputStream image)](#PKCS1-java.io.InputStream-) | 初始化 PKCS1 类的新实例。 |
| [PKCS1()](#PKCS1--) | 初始化 PKCS1 类的新实例。 |
| [PKCS1(String pfx, String password)](#PKCS1-java.lang.String-java.lang.String-) | 初始化 PKCS1 类的新实例。 |
| [PKCS1(InputStream pfx, String password)](#PKCS1-java.io.InputStream-java.lang.String-) | 初始化 PKCS1 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) | 关闭临时流的析构函数（如有必要）。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAuthority()](#getAuthority--) | 签署文件的人或当局的姓名。 |
| [getByteRange()](#getByteRange--) | 获取应描述摘要计算的确切字节范围的整数对数组（起始字节偏移量，以字节为单位的长度）。 |
| [getClass()](#getClass--) |  |
| [getContactInfo()](#getContactInfo--) | 获取签名者提供的信息，以便收件人能够联系签名者以验证签名，例如电话号码。 |
| [getCustomAppearance()](#getCustomAppearance--) | 获取/设置自定义外观。 |
| [getDate()](#getDate--) | 获取签名时间。 |
| [getImageInternal()](#getImageInternal--) | 获取图像流。 |
| [getLocation()](#getLocation--) | 获取签名的 CPU 主机名或物理位置。 |
| [getOcspSettings()](#getOcspSettings--) | 获取/设置 ocsp 设置。 |
| [getReason()](#getReason--) | 获取签名的原因，比如（我同意\\u0420\\u0406\\u0420\\u201a\\u0412�）。 |
| [getSignatureReferences()](#getSignatureReferences--) | 获取签名参考 |
| [getTimestampSettings()](#getTimestampSettings--) | 获取时间戳设置。 |
| [getUseLtv()](#getUseLtv--) | 获取/设置 ltv 验证标志。 |
| [hashCode()](#hashCode--) |  |
| [isShowProperties()](#isShowProperties--) | 强制显示/隐藏签名属性。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAuthority(String value)](#setAuthority-java.lang.String-) | 设置签署文档的人员或授权机构的名称。 |
| [setContactInfo(String value)](#setContactInfo-java.lang.String-) | 设置签名者提供的信息，使收件人能够联系签名者以验证签名，例如电话号码。 |
| [setCustomAppearance(SignatureCustomAppearance value)](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | 获取/设置自定义外观。 |
| [setDate(Date value)](#setDate-java.util.Date-) | 设置签约时间。 |
| [setImage(InputStream _signatureAppearanceStream)](#setImage-java.io.InputStream-) | 设置图像流。 |
| [setImageInternal(System.IO.Stream value)](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [setLocation(String value)](#setLocation-java.lang.String-) | 设置签名的 CPU 主机名或物理位置。 |
| [setOcspSettings(OcspSettings value)](#setOcspSettings-com.aspose.pdf.OcspSettings-) | 获取/设置 ocsp 设置。 |
| [setReason(String value)](#setReason-java.lang.String-) | 设置签名的原因，比如（我同意\\u0420\\u0406\\u0420\\u201a\\u0412�）。 |
| [setShowProperties(boolean value)](#setShowProperties-boolean-) | 强制显示/隐藏签名属性。 |
| [setTimestampSettings(TimestampSettings value)](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | 设置时间戳设置。 |
| [setUseLtv(boolean value)](#setUseLtv-boolean-) | 获取/设置 ltv 验证标志。 |
| [toString()](#toString--) |  |
| [verify()](#verify--) | 验证有关此签名的文档，如果文档有效则返回 true，否则返回 false。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PKCS1(InputStream image) {#PKCS1-java.io.InputStream-}
```
public PKCS1(InputStream image)
```


初始化 PKCS1 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | java.io.InputStream | 此图像将定义页面上的签名外观。 |

### PKCS1() {#PKCS1--}
```
public PKCS1()
```


初始化 PKCS1 类的新实例。

### PKCS1(String pfx, String password) {#PKCS1-java.lang.String-java.lang.String-}
```
public PKCS1(String pfx, String password)
```


初始化 PKCS1 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pfx | java.lang.String | Pfx 文件，其中包含用于签名的证书。 |
| password | java.lang.String | 证书的密码。 |

### PKCS1(InputStream pfx, String password) {#PKCS1-java.io.InputStream-java.lang.String-}
```
public PKCS1(InputStream pfx, String password)
```


初始化 PKCS1 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pfx | java.io.InputStream | 使用组织为 pfx 的证书数据流式传输。 |
| password | java.lang.String | 用于访问证书中私钥的密码。 |

### close() {#close--}
```
public void close()
```


关闭临时流的析构函数（如有必要）。

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
### getAuthority() {#getAuthority--}
```
public final String getAuthority()
```


签署文件的人或当局的姓名。

**退货：**
java.lang.String - 字符串值
### getByteRange() {#getByteRange--}
```
public int[] getByteRange()
```


获取应描述摘要计算的确切字节范围的整数对数组（起始字节偏移量，以字节为单位的长度）。

**退货：**
整数[- 整数值数组
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getContactInfo() {#getContactInfo--}
```
public String getContactInfo()
```


获取签名者提供的信息，以便收件人能够联系签名者以验证签名，例如电话号码。

**退货：**
java.lang.String - 字符串值
### getCustomAppearance() {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```


获取/设置自定义外观。

**退货：**
[SignatureCustomAppearance](../../com.aspose.pdf/signaturecustomappearance) SignatureCustomAppearance 实例
### getDate() {#getDate--}
```
public Date getDate()
```


获取签名时间。

**退货：**
[Date](../../java.util/date) 日期值
### getImageInternal() {#getImageInternal--}
```
public System.IO.Stream getImageInternal()
```


获取图像流。

仅供内部使用

**退货：**
com.aspose.ms.System.IO.Stream - 流对象
### getLocation() {#getLocation--}
```
public String getLocation()
```


获取签名的 CPU 主机名或物理位置。

**退货：**
java.lang.String - 字符串值
### getOcspSettings() {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```


获取/设置 ocsp 设置。

**退货：**
[OcspSettings](../../com.aspose.pdf/ocspsettings) OcspSettings 实例
### getReason() {#getReason--}
```
public String getReason()
```


获取签名的原因，比如（我同意\\u0420\\u0406\\u0420\\u201a\\u0412�）。

**退货：**
java.lang.String - 字符串值
### getSignatureReferences() {#getSignatureReferences--}
```
public List<SignatureReference> getSignatureReferences()
```


获取签名参考

**退货：**
java.util.List<com.aspose.pdf.engine.security.impl.signatures.SignatureReference> - java.util.List 对象 
### getTimestampSettings() {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```


获取时间戳设置。

**退货：**
[TimestampSettings](../../com.aspose.pdf/timestampsettings) 时间戳设置
### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


获取/设置 ltv 验证标志。

**退货：**
boolean - 布尔值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isShowProperties() {#isShowProperties--}
```
public boolean isShowProperties()
```


强制显示/隐藏签名属性。如果 ShowProperties 为真，则签名字段具有预定义的外观格式（表示的字符串）：-------------------------------- ---------- 数字签名者\{证书主题\ 日期：\{签名.日期\ 原因：\{签名.原因\ 地点：\{signature.Location\ }  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  - - 在哪里\{X\} 是 X 值的占位符。签名也可以有图像，在这种情况下，列出的字符串放在图像上。 ShowProperties 默认为真。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAuthority(String value) {#setAuthority-java.lang.String-}
```
public void setAuthority(String value)
```


设置签署文档的人员或授权机构的名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public void setContactInfo(String value)
```


设置签名者提供的信息，使收件人能够联系签名者以验证签名，例如电话号码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setCustomAppearance(SignatureCustomAppearance value) {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
```
public final void setCustomAppearance(SignatureCustomAppearance value)
```


获取/设置自定义外观。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [SignatureCustomAppearance](../../com.aspose.pdf/signaturecustomappearance) | SignatureCustomAppearance 实例 |

### setDate(Date value) {#setDate-java.util.Date-}
```
public void setDate(Date value)
```


设置签约时间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 日期对象 |

### setImage(InputStream _signatureAppearanceStream) {#setImage-java.io.InputStream-}
```
public void setImage(InputStream _signatureAppearanceStream)
```


设置图像流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| _signatureAppearanceStream | java.io.InputStream | 蒸汽对象 |

### setImageInternal(System.IO.Stream value) {#setImageInternal-com.aspose.ms.System.IO.Stream-}
```
public void setImageInternal(System.IO.Stream value)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | com.aspose.ms.System.IO.Stream |  |

### setLocation(String value) {#setLocation-java.lang.String-}
```
public void setLocation(String value)
```


设置签名的 CPU 主机名或物理位置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setOcspSettings(OcspSettings value) {#setOcspSettings-com.aspose.pdf.OcspSettings-}
```
public void setOcspSettings(OcspSettings value)
```


获取/设置 ocsp 设置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [OcspSettings](../../com.aspose.pdf/ocspsettings) | OcspSettings 实例 |

### setReason(String value) {#setReason-java.lang.String-}
```
public void setReason(String value)
```


设置签名的原因，比如（我同意\\u0420\\u0406\\u0420\\u201a\\u0412�）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```


强制显示/隐藏签名属性。如果 ShowProperties 为真，则签名字段具有预定义的外观格式（表示的字符串）：-------------------------------- ---------- 数字签名者\{证书主题\ 日期：\{签名.日期\ 原因：\{签名.原因\ 地点：\{signature.Location\ }  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  - - 在哪里\{X\} 是 X 值的占位符。签名也可以有图像，在这种情况下，列出的字符串放在图像上。 ShowProperties 默认为真。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setTimestampSettings(TimestampSettings value) {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
```
public void setTimestampSettings(TimestampSettings value)
```


设置时间戳设置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [时间戳设置](../../com.aspose.pdf/timestampsettings) | TimestampSettings |

### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


获取/设置 ltv 验证标志。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### verify() {#verify--}
```
public boolean verify()
```


验证有关此签名的文档，如果文档有效则返回 true，否则返回 false。

**退货：**
布尔值 - 如果文档有效则为真。
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
