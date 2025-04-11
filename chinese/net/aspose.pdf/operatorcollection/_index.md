---
title: Class OperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OperatorCollection 类。类表示操作符的集合
type: docs
weight: 7080
url: /zh/net/aspose.pdf/operatorcollection/
---
## OperatorCollection 类

类表示操作符的集合

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | 获取集合中操作符的数量。 |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | 指示集合是否仅限于快速文本提取 |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | 获取一个值，指示集合是否为只读。 |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | 根据索引获取操作符。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | 接受 IOperatorSelector 访问者对象以处理操作符。 |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | 将其他集合中的所有操作符添加到集合中。 |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | 将新操作符添加到集合中。 |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | 将操作符添加到内容操作符的末尾。 |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | 取消最后一次更新。此方法可以在更改不应引发内容更新时调用。 |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | 从列表中移除所有操作符。 |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | 如果集合包含给定操作符，则返回 true。 |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | 将操作符复制到操作符列表中。 |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | 从集合中删除操作符。 |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | 从集合中删除操作符。 |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | 从集合中删除操作符。 |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | 执行与释放、释放或重置非托管资源相关的应用程序定义任务。 |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | 返回集合的枚举器 |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | 在给定位置插入操作符。 |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | 将操作符插入集合中。 |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | 在给定位置插入操作符。 |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | 从集合中移除操作符。 |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | 用其他操作符替换集合中的操作符。 |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | 恢复文档更新。如果有任何待处理更改，则更新内容流。 |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | 恢复文档更新。如果有任何待处理更改，则更新内容流。如果无效参数为 true，则将所有操作符标记为“已更改”。 |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | 抑制更新内容数据。在调用 ResumeUpdate 之前，内容流不会更新。 |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | 返回操作符的文本表示。 |

### 另请参阅

* 类 [BaseOperatorCollection](../baseoperatorcollection/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)