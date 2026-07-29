---
title: "类 BoundsCheckableListT"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Generator.BoundsCheckableList1T 类。表示围绕 System.Collections.Generic.List 的 BoundsCheckableList 包装器。"
type: docs
weight: 5340
url: /zh/net/aspose.pdf.generator/boundscheckablelist-1/
---
## BoundsCheckableList&lt;T&gt; class

表示 BoundsCheckableList —— 对 System.Collections.Generic.List 的包装器。

```csharp
public class BoundsCheckableList<T> : IList<T>
    where T : IBoundsCheckableItem
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BoundsCheckableList](boundscheckablelist/#constructor)() | 初始化 BoundsCheckableList 类的新实例。 |
| [BoundsCheckableList](boundscheckablelist/#constructor_1)(BoundsCheckMode, double, double) | 初始化 BoundsCheckableList 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf.generator/boundscheckablelist-1/count/) { get; } | 获取 System.Collections.Generic.List 中包含的元素数量。 |
| [IsReadOnly](../../aspose.pdf.generator/boundscheckablelist-1/isreadonly/) { get; } | 获取指示集合是否为只读的值。 |
| [Item](../../aspose.pdf.generator/boundscheckablelist-1/item/) { get; set; } | 获取或设置集合中的段落。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf.generator/boundscheckablelist-1/add/)(T) | 根据 \"boundsCheckMode\" 参数，将对象添加到 System.Collections.Generic.List 的末尾。 |
| [Clear](../../aspose.pdf.generator/boundscheckablelist-1/clear/)() | 从 System.Collections.Generic.List 中移除所有元素。 |
| [Contains](../../aspose.pdf.generator/boundscheckablelist-1/contains/)(T) | 确定元素是否在 System.Collections.Generic.List 中。 |
| [CopyTo](../../aspose.pdf.generator/boundscheckablelist-1/copyto/)(T[], int) |  |
| [GetEnumerator](../../aspose.pdf.generator/boundscheckablelist-1/getenumerator/)() | 返回遍历 System.Collections.Generic.List 的枚举器。 |
| [IndexOf](../../aspose.pdf.generator/boundscheckablelist-1/indexof/)(T) | 搜索指定的对象并返回其在整个 System.Collections.Generic.List 中首次出现的零基索引。 |
| [Insert](../../aspose.pdf.generator/boundscheckablelist-1/insert/)(int, T) | 在指定索引处将元素插入到 System.Collections.Generic.List 中。 |
| [Remove](../../aspose.pdf.generator/boundscheckablelist-1/remove/)(T) | 从 System.Collections.Generic.List 中移除特定对象的首次出现。 |
| [RemoveAt](../../aspose.pdf.generator/boundscheckablelist-1/removeat/)(int) | 移除 System.Collections.Generic.List 中指定索引处的元素。 |
| [UpdateBoundsCheckMode](../../aspose.pdf.generator/boundscheckablelist-1/updateboundscheckmode/#updateboundscheckmode)(BoundsCheckMode) | 更新已初始化集合的 boundsCheckMode 参数。 |
| [UpdateBoundsCheckMode](../../aspose.pdf.generator/boundscheckablelist-1/updateboundscheckmode/#updateboundscheckmode_1)(BoundsCheckMode, double, double) | 更新已初始化集合的 boundsCheckMode 参数。 |

### 另请参见

* interface [IBoundsCheckableItem](../iboundscheckableitem/)
* namespace [Aspose.Pdf.Generator](../../aspose.pdf.generator/)
* assembly [Aspose.PDF](../../)


