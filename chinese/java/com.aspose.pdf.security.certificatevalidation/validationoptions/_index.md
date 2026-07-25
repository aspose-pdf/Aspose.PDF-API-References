---
title: "ValidationOptions"
linktitle: "ValidationOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示在 PDF 文档中验证数字签名的选项。"
type: docs
weight: 30
url: /zh/java/com.aspose.pdf.security.certificatevalidation/validationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationOptions

```
public final class ValidationOptions extends Object
```

表示在 PDF 文档中验证数字签名的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ValidationOptions](#ValidationOptions--) | 创建 {@link ValidationOptions} 类的实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCheckCertificateChain](#getCheckCertificateChain--) | 获取或设置一个值，指示在验证过程中是否应检查证书链。当属性被设置时，将检查证书链的存在；如果不存在，则验证结果将为 {@link ValidationStatus#Undefined}，这对应于 Adobe Acrobat 的行为。如果只想在线检查吊销状态，则将该字段设置为 {@code false}。默认值为 {@code false}。 |
| [getRequestTimeout](#getRequestTimeout--) | 获取或设置验证过程中网络相关操作的超时时间（以毫秒为单位）。RequestTimeout 属性定义了系统在访问在线资源（如吊销状态或 OCSP 服务器）时应等待网络响应的最长时间。 |
| [getValidationMethod](#getValidationMethod--) | 获取或设置用于验证证书的方法。 |
| [getValidationMode](#getValidationMode--) | 获取或设置 PDF 文档中数字签名的验证模式。ValidationMode 属性决定验证过程的严格程度。 |
| [setCheckCertificateChain](#setCheckCertificateChain-boolean-) | 获取或设置一个值，指示在验证过程中是否应检查证书链。当属性被设置时，将检查证书链的存在；如果不存在，则验证结果将为 {@link ValidationStatus#Undefined}，这对应于 Adobe Acrobat 的行为。如果只想在线检查吊销状态，则将该字段设置为 {@code false}。默认值为 {@code false}。 |
| [setRequestTimeout](#setRequestTimeout-int-) | 获取或设置验证过程中网络相关操作的超时时间（以毫秒为单位）。RequestTimeout 属性定义了系统在访问在线资源（如吊销状态或 OCSP 服务器）时应等待网络响应的最长时间。 |
| [setValidationMethod](#setValidationMethod-int-) | 获取或设置用于验证证书的方法。 |
| [setValidationMode](#setValidationMode-int-) | 获取或设置 PDF 文档中数字签名的验证模式。ValidationMode 属性决定验证过程的严格程度。 |

### ValidationOptions {#ValidationOptions--}
```
public ValidationOptions()
```

创建 {@link ValidationOptions} 类的实例。

### getCheckCertificateChain {#getCheckCertificateChain--}
```
public final boolean getCheckCertificateChain()
```

获取或设置一个值，指示在验证过程中是否应检查证书链。当属性被设置时，将检查证书链的存在；如果不存在，则验证结果将为 {@link ValidationStatus#Undefined}，这对应于 Adobe Acrobat 的行为。如果只想在线检查吊销状态，则将该字段设置为 {@code false}。默认值为 {@code false}。

**Returns:**
布尔值

### getRequestTimeout {#getRequestTimeout--}
```
public final int getRequestTimeout()
```

获取或设置验证过程中网络相关操作的超时时间（以毫秒为单位）。RequestTimeout 属性定义了系统在访问在线资源（如吊销状态或 OCSP 服务器）时应等待网络响应的最长时间。

**Returns:**
int 值

### getValidationMethod {#getValidationMethod--}
```
public final int getValidationMethod()
```

获取或设置用于验证证书的方法。

**Returns:**
ValidationMethod 元素

### getValidationMode {#getValidationMode--}
```
public final int getValidationMode()
```

获取或设置 PDF 文档中数字签名的验证模式。ValidationMode 属性决定验证过程的严格程度。

**Returns:**
ValidationMode 元素

### setCheckCertificateChain {#setCheckCertificateChain-boolean-}
```
public final void setCheckCertificateChain(boolean value)
```

获取或设置一个值，指示在验证过程中是否应检查证书链。当属性被设置时，将检查证书链的存在；如果不存在，则验证结果将为 {@link ValidationStatus#Undefined}，这对应于 Adobe Acrobat 的行为。如果只想在线检查吊销状态，则将该字段设置为 {@code false}。默认值为 {@code false}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRequestTimeout {#setRequestTimeout-int-}
```
public final void setRequestTimeout(int value)
```

获取或设置验证过程中网络相关操作的超时时间（以毫秒为单位）。RequestTimeout 属性定义了系统在访问在线资源（如吊销状态或 OCSP 服务器）时应等待网络响应的最长时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setValidationMethod {#setValidationMethod-int-}
```
public final void setValidationMethod(int value)
```

获取或设置用于验证证书的方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | ValidationMethod 元素 |

### setValidationMode {#setValidationMode-int-}
```
public final void setValidationMode(int value)
```

获取或设置 PDF 文档中数字签名的验证模式。ValidationMode 属性决定验证过程的严格程度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | ValidationMode 元素 |
