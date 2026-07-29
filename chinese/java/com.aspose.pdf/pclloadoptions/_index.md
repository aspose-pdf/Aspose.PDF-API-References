---
title: "PclLoadOptions"
linktitle: "PclLoadOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示将 PCL 文件加载（导入）到 pdf 文档的选项。"
type: docs
weight: 3530
url: /zh/java/com.aspose.pdf/pclloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PclLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PclLoadOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public final class PclLoadOptions extends LoadOptions implements IPipelineOptions
```

表示将 PCL 文件加载（导入）到 pdf 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PclLoadOptions](#PclLoadOptions--) | 创建 {@code PclLoadOptions} 对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBatchSize](#getBatchSize--) | 如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。 |
| [getConversionEngine](#getConversionEngine--) | 定义将在转换中使用的转换引擎 |
| [getExceptions](#getExceptions--) | 转换错误列表。 |
| [isSupressErrors](#isSupressErrors--) | 获取或设置布尔值，以指示是否应抑制 PCL 转换错误。 |
| [setBatchSize](#setBatchSize-int-) | 如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。 |
| [setConversionEngine](#setConversionEngine-int-) | 定义将在转换中使用的转换引擎 |
| [setSupressErrors](#setSupressErrors-boolean-) | 获取或设置布尔值，以指示是否应抑制 PCL 转换错误。 |

### PclLoadOptions {#PclLoadOptions--}
```
public PclLoadOptions()
```

创建 {@code PclLoadOptions} 对象。

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。

**Returns:**
int 值

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

定义将在转换中使用的转换引擎

**Returns:**
ConversionEngines 元素 @see ConversionEngines

### getExceptions {#getExceptions--}
```
public List < Exception > getExceptions()
```

转换错误列表。

**Returns:**
异常列表

### isSupressErrors {#isSupressErrors--}
```
public boolean isSupressErrors()
```

获取或设置布尔值，以指示是否应抑制 PCL 转换错误。

**Returns:**
布尔值

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

定义将在转换中使用的转换引擎

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| conversionEngine |  | ConversionEngines 元素 @see ConversionEngines |

### setSupressErrors {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```

获取或设置布尔值，以指示是否应抑制 PCL 转换错误。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| supressErrors |  | 布尔值 |
