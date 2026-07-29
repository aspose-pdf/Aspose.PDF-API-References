---
title: "类 BaseOperatorCollection"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.BaseOperatorCollection 类。表示操作符集合的基类"
type: docs
weight: 2940
url: /zh/net/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection class

表示 operator 集合的基类。

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | 获取集合中运算符的计数。 |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | 指示集合是否限制为快速文本提取。 |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | 如果集合为只读，则返回 true。 |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | 通过索引获取运算符。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | 向集合中添加新运算符。 |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | 取消上一次更新。当更改不应触发内容更新时，可调用此方法。 |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | 清除集合。 |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | 检查操作符是否存在于集合中。 |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | 将运算符复制到运算符列表中。 |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | 返回集合的枚举器。 |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | 将运算符插入集合中。 |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | 从集合中移除操作符。 |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | 恢复文档更新。如果有任何未完成的更改，则更新内容流。 |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | 抑制内容数据的更新。内容流在调用 ResumeUpdate 之前不会被更新。 |

### 另请参见

* class [Operator](../operator/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


