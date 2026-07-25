---
title: "ValidationResult"
linktitle: "ValidationResult"
second_title: "Aspose.PDF for Java API 参考"
description: "表示证书验证过程的结果。ValidationResult 类提供有关验证证书结果的信息，包括其。"
type: docs
weight: 40
url: /zh/java/com.aspose.pdf.security.certificatevalidation/validationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationResult

```
public final class ValidationResult extends Object
```

表示证书验证过程的结果。ValidationResult 类提供有关证书验证结果的信息，包括其状态以及描述验证期间遇到的任何问题的消息。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ValidationResult](#ValidationResult--) | 创建 {@link ValidationResult} 类的实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getMessage](#getMessage--) | 表示与验证结果关联的消息。Message 属性提供有关验证结果状态的额外上下文或信息。 |
| [getStatus](#getStatus--) | 获取证书验证过程的状态。Status 属性指示证书验证的结果。可能的值在 {@link ValidationStatus} 枚举中定义，例如 Valid、Invalid 或 Undefined。它提供对证书是否通过验证检查的洞察。 |
| [setMessage](#setMessage-java.lang.String-) | 表示与验证结果关联的消息。Message 属性提供有关验证结果状态的额外上下文或信息。 |
| [setStatus](#setStatus-int-) | 获取证书验证过程的状态。Status 属性指示证书验证的结果。可能的值在 {@link ValidationStatus} 枚举中定义，例如 Valid、Invalid 或 Undefined。它提供对证书是否通过验证检查的洞察。 |

### ValidationResult {#ValidationResult--}
```
public ValidationResult()
```

创建 {@link ValidationResult} 类的实例。

### getMessage {#getMessage--}
```
public final String getMessage()
```

表示与验证结果关联的消息。Message 属性提供有关验证结果状态的额外上下文或信息。

**Returns:**
字符串值

### getStatus {#getStatus--}
```
public final int getStatus()
```

获取证书验证过程的状态。Status 属性指示证书验证的结果。可能的值在 {@link ValidationStatus} 枚举中定义，例如 Valid、Invalid 或 Undefined。它提供对证书是否通过验证检查的洞察。

**Returns:**
ValidationStatus 元素

### setMessage {#setMessage-java.lang.String-}
表示与验证结果关联的消息。Message 属性提供有关验证结果状态的额外上下文或信息。

### setStatus {#setStatus-int-}
```
public final void setStatus(int value)
```

获取证书验证过程的状态。Status 属性指示证书验证的结果。可能的值在 {@link ValidationStatus} 枚举中定义，例如 Valid、Invalid 或 Undefined。它提供对证书是否通过验证检查的洞察。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | ValidationStatus 元素 |
