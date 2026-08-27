---
title: "OperatorCollection 类"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.OperatorCollection 类。该类表示运算符的集合。"
type: docs
weight: 7220
url: /zh/net/aspose.pdf/operatorcollection/
---
## OperatorCollection class

类表示运算符的集合。

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | 获取集合中运算符的计数。 |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | 指示集合是否限制为快速文本提取。 |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | 获取一个值，指示集合是否为只读。 |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | 通过索引获取运算符。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | 接受 IOperatorSelector 访问者对象来处理运算符。 |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | 将其他集合中的所有运算符添加到集合中。 |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | 向集合中添加新运算符。 |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | 在内容运算符的末尾添加运算符。 |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | 取消上一次更新。当更改不应触发内容更新时，可调用此方法。 |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | 从列表中移除所有运算符。 |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | 如果集合包含给定的运算符，则返回 true。 |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | 将运算符复制到运算符列表中。 |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | 从集合中删除运算符。 |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | 从集合中删除单个运算符。 |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | 从集合中删除运算符。 |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | 执行与释放、释放或重置非托管资源相关的应用程序定义任务。 |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | 返回集合的枚举器。 |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | 在给定位置插入运算符。 |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | 将运算符插入集合中。 |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | 在给定位置插入运算符。 |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | 从集合中移除运算符。 |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | 用其他运算符替换集合中的运算符。 |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | 恢复文档更新。如果有任何未完成的更改，则更新内容流。 |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | 恢复文档更新。如果有任何未完成的更改，则更新内容流。如果 invalidate 参数为 true，则将所有运算符标记为已更改。 |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | 抑制内容数据的更新。内容流在调用 ResumeUpdate 之前不会被更新。 |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | 返回运算符的文本表示。 |

### 另请参见

* class [BaseOperatorCollection](../baseoperatorcollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


