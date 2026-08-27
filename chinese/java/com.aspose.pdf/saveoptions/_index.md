---
title: "SaveOptions"
linktitle: "SaveOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "SaveOptions 类型在各个保存选项上保持抽象层级。"
type: docs
weight: 4370
url: /zh/java/com.aspose.pdf/saveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions

```
public abstract class SaveOptions extends Object
```

SaveOptions 类型在各个保存选项上保持抽象层级。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getSaveFormat](#getSaveFormat--) | 数据保存的格式。 |
| [getWarningHandler](#getWarningHandler--) | 回调以处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。Continue 是默认操作，保存操作将继续；但用户也可以返回 Abort，此时保存操作应停止。 |
| [isCacheGlyphs](#isCacheGlyphs--) | 获取或设置布尔值，以指示在准备 APS 页面时是否缓存字体字形。此操作可提高 PDF 转换为其他格式的性能，但会增加内存消耗。 |
| [isCloseResponse](#isCloseResponse--) | 获取布尔值，以指示文档保存到响应后是否关闭 Response 对象。 |
| [setCacheGlyphs](#setCacheGlyphs-boolean-) | 获取或设置布尔值，以指示在准备 APS 页面时是否缓存字体字形。此操作可提高 PDF 转换为其他格式的性能，但会增加内存消耗。 |
| [setCloseResponse](#setCloseResponse-boolean-) | 设置布尔值，以指示文档保存到响应后是否关闭 Response 对象。 |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | 回调以处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。Continue 是默认操作，保存操作将继续；但用户也可以返回 Abort，此时保存操作应停止。 |

### getSaveFormat {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```

数据保存的格式。

**Returns:**
SaveFormat 值 @see SaveFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

回调以处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。Continue 是默认操作，保存操作将继续；但用户也可以返回 Abort，此时保存操作应停止。

**Returns:**
IWarningCallback 值

### isCacheGlyphs {#isCacheGlyphs--}
```
public final boolean isCacheGlyphs()
```

获取或设置布尔值，以指示在准备 APS 页面时是否缓存字体字形。此操作可提高 PDF 转换为其他格式的性能，但会增加内存消耗。

**Returns:**
布尔值

### isCloseResponse {#isCloseResponse--}
```
public boolean isCloseResponse()
```

获取布尔值，以指示文档保存到响应后是否关闭 Response 对象。

**Returns:**
布尔值

### setCacheGlyphs {#setCacheGlyphs-boolean-}
```
public final void setCacheGlyphs(boolean value)
```

获取或设置布尔值，以指示在准备 APS 页面时是否缓存字体字形。此操作可提高 PDF 转换为其他格式的性能，但会增加内存消耗。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setCloseResponse {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```

设置布尔值，以指示文档保存到响应后是否关闭 Response 对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
回调以处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。Continue 是默认操作，保存操作将继续；但用户也可以返回 Abort，此时保存操作应停止。
