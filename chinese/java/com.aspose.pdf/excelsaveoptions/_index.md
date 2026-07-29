---
title: "ExcelSaveOptions"
linktitle: "ExcelSaveOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "导出为 Excel 格式的保存选项"
type: docs
weight: 1260
url: /zh/java/com.aspose.pdf/excelsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.ExcelSaveOptions

```
public class ExcelSaveOptions extends UnifiedSaveOptions
```

导出为 Excel 格式的保存选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ExcelSaveOptions](#ExcelSaveOptions--) | 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat](#getFormat--) | / * / * 获取或设置在转换为 Excel 表时（在旧版引擎中）应用于（虚拟）缩放字体大小的因子。 / * 较小的值有助于搜索列并防止某些文档的列合并。 / * 默认值为 0.9；将值设为零可让算法自动选择缩放。 / * / * / * |
| [getMinimizeTheNumberOfWorksheets](#getMinimizeTheNumberOfWorksheets--) | 如果需要将结果工作簿中的工作表数量最小化，请设为 true。默认值为 false；这意味着每个 PDF 页面将保存为单独的工作表。 |
| [isInsertBlankColumnAtFirst](#isInsertBlankColumnAtFirst--) | 如果需要抑制在工作表的第一列插入空白列，请设为 false。默认值为 true；这意味着将插入空白列。 |
| [isUniformWorksheets](#isUniformWorksheets--) | 如果需要在整个文档中使用统一的列划分，请设为 true。默认值为 false；这意味着列划分将在每页独立。 |
| [setFormat](#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-) | 输出格式 |
| [setInsertBlankColumnAtFirst](#setInsertBlankColumnAtFirst-boolean-) | 如果需要抑制在工作表的第一列插入空白列，请设为 false。默认值为 true；这意味着将插入空白列。 |
| [setMinimizeTheNumberOfWorksheets](#setMinimizeTheNumberOfWorksheets-boolean-) | 如果需要将结果工作簿中的工作表数量最小化，请设为 true。默认值为 false；这意味着每个 PDF 页面将保存为单独的工作表。 |
| [setUniformWorksheets](#setUniformWorksheets-boolean-) | 定义将在转换中使用的转换引擎 |

### ExcelSaveOptions {#ExcelSaveOptions--}
```
public ExcelSaveOptions()
```

构造函数

### getFormat {#getFormat--}
```
public ExcelSaveOptions.ExcelFormat getFormat()
```

/ * / * 获取或设置在转换为 Excel 表时（在旧版引擎中）应用于（虚拟）缩放字体大小的因子。 / * 较小的值有助于搜索列并防止某些文档的列合并。 / * 默认值为 0.9；将值设为零可让算法自动选择缩放。 / * / * / *

**Returns:**
double 值 /

### getMinimizeTheNumberOfWorksheets {#getMinimizeTheNumberOfWorksheets--}
```
public boolean getMinimizeTheNumberOfWorksheets()
```

如果需要将结果工作簿中的工作表数量最小化，请设为 true。默认值为 false；这意味着每个 PDF 页面将保存为单独的工作表。

**Returns:**
布尔值

### isInsertBlankColumnAtFirst {#isInsertBlankColumnAtFirst--}
```
public boolean isInsertBlankColumnAtFirst()
```

如果需要抑制在工作表的第一列插入空白列，请设为 false。默认值为 true；这意味着将插入空白列。

**Returns:**
布尔值

### isUniformWorksheets {#isUniformWorksheets--}
```
public boolean isUniformWorksheets()
```

如果需要在整个文档中使用统一的列划分，请设为 true。默认值为 false；这意味着列划分将在每页独立。

**Returns:**
布尔值

### setFormat {#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-}
输出格式

### setInsertBlankColumnAtFirst {#setInsertBlankColumnAtFirst-boolean-}
```
public void setInsertBlankColumnAtFirst(boolean value)
```

如果需要抑制在工作表的第一列插入空白列，请设为 false。默认值为 true；这意味着将插入空白列。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMinimizeTheNumberOfWorksheets {#setMinimizeTheNumberOfWorksheets-boolean-}
```
public void setMinimizeTheNumberOfWorksheets(boolean value)
```

如果需要将结果工作簿中的工作表数量最小化，请设为 true。默认值为 false；这意味着每个 PDF 页面将保存为单独的工作表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUniformWorksheets {#setUniformWorksheets-boolean-}
```
public void setUniformWorksheets(boolean value)
```

定义将在转换中使用的转换引擎

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  |  |
