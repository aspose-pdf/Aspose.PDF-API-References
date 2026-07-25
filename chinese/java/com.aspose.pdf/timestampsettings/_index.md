---
title: "TimestampSettings"
linktitle: "TimestampSettings"
second_title: "Aspose.PDF for Java API 参考"
description: "表示签名过程使用的 ocsp 设置。"
type: docs
weight: 5360
url: /zh/java/com.aspose.pdf/timestampsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TimestampSettings

```
public class TimestampSettings extends Object
```

表示签名过程使用的 ocsp 设置。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-) | 初始化 {@code TimestampSettings} 类的新实例。 |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | 初始化 {@code TimestampSettings} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBasicAuthCredentials](#getBasicAuthCredentials--) | 获取基本身份验证凭据，用户名和密码会组合成字符串 "username:password"。 |
| [getDigestHashAlgorithm](#getDigestHashAlgorithm--) | 获取/设置内部哈希函数的摘要算法。 |
| [getServerUrl](#getServerUrl--) | 获取时间戳服务器的 URL。 |
| [setBasicAuthCredentials](#setBasicAuthCredentials-java.lang.String-) | 设置基本身份验证凭据，用户名和密码组合成字符串 "username:password"。 |
| [setDigestHashAlgorithm](#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-) | 获取/设置内部哈希函数的摘要算法。 |
| [setServerUrl](#setServerUrl-java.lang.String-) | 设置时间戳服务器 URL。 |

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-}
初始化 {@code TimestampSettings} 类的新实例。

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
初始化 {@code TimestampSettings} 类的新实例。

### getBasicAuthCredentials {#getBasicAuthCredentials--}
```
public String getBasicAuthCredentials()
```

获取基本身份验证凭据，用户名和密码会组合成字符串 "username:password"。

**Returns:**
字符串值

### getDigestHashAlgorithm {#getDigestHashAlgorithm--}
```
public final DigestHashAlgorithm getDigestHashAlgorithm()
```

获取/设置内部哈希函数的摘要算法。

**Returns:**
DigestHashAlgorithm 元素 @see DigestHashAlgorithm

### getServerUrl {#getServerUrl--}
```
public String getServerUrl()
```

获取时间戳服务器的 URL。

**Returns:**
字符串值

### setBasicAuthCredentials {#setBasicAuthCredentials-java.lang.String-}
设置基本身份验证凭据，用户名和密码组合成字符串 "username:password"。

### setDigestHashAlgorithm {#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-}
获取/设置内部哈希函数的摘要算法。

### setServerUrl {#setServerUrl-java.lang.String-}
设置时间戳服务器 URL。
