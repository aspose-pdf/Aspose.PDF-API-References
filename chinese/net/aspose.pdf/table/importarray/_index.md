---
title: Table.ImportArray
second_title: Aspose.PDF for .NET API Reference
description: 表方法。将一维数据数组导入表中。导入时每个数组项占用一个单元格，并从参数中定义的行和列开始。如果在导入过程中检测到所需的行仍然缺失，即目标表太小无法容纳所有数据，将创建必要的行
type: docs
weight: 250
url: /zh/net/aspose.pdf/table/importarray/
---
## Table.ImportArray 方法

将一维数据数组导入表中。导入时每个数组项占用一个单元格，并从参数中定义的行和列开始。如果在导入过程中检测到所需的行仍然缺失（即目标表太小无法容纳所有数据），将创建必要的行

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| importedArray | Object[] | 导入的数据，空值将作为空字符串导入 |
| firstFilledRow | Int32 | 定义目标表中导入开始的第一个目标行的编号。如果目标表中的行数少于所需行数，将首先创建缺失的行。 |
| firstFilledColumn | Int32 | 指定目标表中第一个目标列的编号，导入开始前该列必须存在于目标表中 |
| isLeftColumnsFilled | Boolean | 如果 'isLeftColumnsFilled'=false，则在第二行及所有后续填充行中，位于 firstFilledColumn 左侧的单元格将被跳过 |

### 另请参阅

* 类 [Table](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)