---
title: "Table.ImportArray"
second_title: "Aspose.PDF for .NET API 参考"
description: "Table 方法。将一维数据数组导入表格。导入时每个数组项对应一个单元格，并从参数中定义的行和列开始。导入过程中如果检测到必要的行仍然缺失，例如目标表格太小而无法容纳所有数据，则会创建所需的行。"
type: docs
weight: 250
url: /zh/net/aspose.pdf/table/importarray/
---
## Table.ImportArray method

将一维数据数组导入表格。导入时每个数组项对应一个单元格，并从参数中定义的行和列开始。导入过程中，如果检测到必要的行仍不存在（即目标表格太小，无法容纳所有数据），将创建所需的行。

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| importedArray | Object[] | 导入的数据，null 将作为空字符串导入 |
| firstFilledRow | Int32 | 定义目标表格中导入开始的第一行编号。如果目标表格中的行数少于所需行数，将首先创建缺失的行。 |
| firstFilledColumn | Int32 | 指定目标表中第一目标列的编号，列必须在导入开始前已存在于目标表中 |
| isLeftColumnsFilled | Boolean | 如果 'isLeftColumnsFilled'=false，则在第二行及其后所有已填充的行中，位于 firstFilledColumn 左侧的单元格将被跳过 |

### 另请参见

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


