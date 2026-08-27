---
title: "DocMDPAccessPermissions"
linktitle: "DocMDPAccessPermissions"
second_title: "Aspose.PDF for Java API 参考"
description: "此文档授予的访问权限。有效值为：1 - 不允许对文档进行任何更改；对文档的任何更改都会使签名失效。2 -。"
type: docs
weight: 1010
url: /zh/java/com.aspose.pdf/docmdpaccesspermissions/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocMDPAccessPermissions > com.aspose.pdf.DocMDPAccessPermissions, java.lang.Enum < DocMDPAccessPermissions >, com.aspose.pdf.DocMDPAccessPermissions

**All Implemented Interfaces:**
Serializable, Comparable < DocMDPAccessPermissions >

```
public enum DocMDPAccessPermissions extends Enum < DocMDPAccessPermissions >
```

此文档授予的访问权限。有效值为：1 - 不允许对文档进行任何更改；对文档的任何更改都会使签名失效。2 - 允许的更改包括填写表单、实例化页面模板和签名；其他更改会使签名失效。3 - 允许的更改与 2 相同，并且包括注释的创建、删除和修改；其他更改会使签名失效。

## 字段

| 字段 | 描述 |
| --- | --- |
| [AnnotationModification](#AnnotationModification) | 3 - 允许的更改与 2 相同，并且包括注释的创建、删除和修改；其他更改会使签名失效。 |
| [FillingInForms](#FillingInForms) | 2 - 允许的更改包括填写表单、实例化页面模板以及签名；其他更改会使签名失效。 |
| [NoChanges](#NoChanges) | 1 - 不允许对文档进行任何更改；对文档的任何更改都会使签名失效。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 返回此类型中具有指定名称的枚举常量。 |
| [values](#values--) | 返回一个数组，包含此枚举类型的常量，按声明顺序排列。 |

### AnnotationModification {#AnnotationModification}
```
public static final DocMDPAccessPermissions AnnotationModification
```

3 - 允许的更改与 2 相同，并且包括注释的创建、删除和修改；其他更改会使签名失效。

### FillingInForms {#FillingInForms}
```
public static final DocMDPAccessPermissions FillingInForms
```

2 - 允许的更改包括填写表单、实例化页面模板以及签名；其他更改会使签名失效。

### NoChanges {#NoChanges}
```
public static final DocMDPAccessPermissions NoChanges
```

1 - 不允许对文档进行任何更改；对文档的任何更改都会使签名失效。

### getByValue {#getByValue-int-}
```
public static DocMDPAccessPermissions getByValue(int value)
```



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
返回此类型中具有指定名称的枚举常量。

### values {#values--}
```
public static DocMDPAccessPermissions [] values()
```

返回一个数组，包含此枚举类型的常量，按声明顺序排列。

**Returns:**
一个数组，包含此枚举类型的常量，按声明顺序排列
