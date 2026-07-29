---
title: "枚举 CollectionFieldSubtype"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.CollectionFieldSubtype 枚举。表示方案集合中字段的子类型参数。"
type: docs
weight: 3150
url: /zh/net/aspose.pdf/collectionfieldsubtype/
---
## CollectionFieldSubtype enumeration

表示 sceme 集合中字段的子类型参数。

```csharp
public enum CollectionFieldSubtype
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 未定义子类型。 |
| S | `1` | 文本类型。字段数据应存储为 PDF 文本字符串。 |
| D | `2` | 日期类型。字段数据应存储为 PDF 日期字符串。 |
| N | `3` | 数字类型。字段数据应存储为 PDF 数字。 |
| F | `4` | 字段数据应为嵌入文件流的文件名，若文件规范的 UF 条目存在则以其标识；否则使用文件规范的 F 条目标识。 |
| Desc | `5` | 字段数据应为嵌入文件流的文件名，若文件规范的 UF 条目存在则以其标识；否则使用文件规范的 F 条目标识。 |
| ModDate | `6` | 字段数据应为嵌入文件流的修改日期，依据嵌入文件参数字典中的 ModDate 条目标识。 |
| CreationDate | `7` | 字段数据应为嵌入文件流的创建日期，依据嵌入文件中的 CreationDate 条目标识。 |
| Size | `8` | 字段数据应为嵌入文件的大小，依据嵌入文件参数字典中的 Size 条目标识。 |
| CompressedSize | `9` | (PDF 2.0) 字段数据是嵌入文件流的长度，依据嵌入文件流字典中的 Length 条目标识，且两个值应相同。 |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


