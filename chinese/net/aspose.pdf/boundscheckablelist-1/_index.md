---
title: Class BoundsCheckableListT
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.BoundsCheckableList1T 类。表示 System.Collections.Generic.List 的 BoundsCheckableList 包装器
type: docs
weight: 2930
url: /zh/net/aspose.pdf/boundscheckablelist-1/
---
## BoundsCheckableList&lt;T&gt; 类

表示 BoundsCheckableList - System.Collections.Generic.List 的包装器。

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
| [Count](../../aspose.pdf/boundscheckablelist-1/count/) { get; } | 获取 System.Collections.Generic.List 中包含的元素数量。 |
| [IsReadOnly](../../aspose.pdf/boundscheckablelist-1/isreadonly/) { get; } | 获取指示集合是否为只读的值。 |
| [Item](../../aspose.pdf/boundscheckablelist-1/item/) { get; set; } | 获取或设置来自集合的段落。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf/boundscheckablelist-1/add/)(T) | 根据 "boundsCheckMode" 参数将对象添加到 System.Collections.Generic.List 的末尾。 |
| [Clear](../../aspose.pdf/boundscheckablelist-1/clear/)() | 从 System.Collections.Generic.List 中移除所有元素。 |
| [Contains](../../aspose.pdf/boundscheckablelist-1/contains/)(T) | 确定元素是否在 System.Collections.Generic.List 中。 |
| [CopyTo](../../aspose.pdf/boundscheckablelist-1/copyto/)(T[], int) |  |
| [GetEnumerator](../../aspose.pdf/boundscheckablelist-1/getenumerator/)() | 返回一个枚举器，该枚举器遍历 System.Collections.Generic.List。 |
| [IndexOf](../../aspose.pdf/boundscheckablelist-1/indexof/)(T) | 搜索指定对象并返回在整个 System.Collections.Generic.List 中第一次出现的零基索引。 |
| [Insert](../../aspose.pdf/boundscheckablelist-1/insert/)(int, T) | 在指定索引处将元素插入到 System.Collections.Generic.List 中。 |
| [Remove](../../aspose.pdf/boundscheckablelist-1/remove/)(T) | 从 System.Collections.Generic.List 中移除特定对象的第一次出现。 |
| [RemoveAt](../../aspose.pdf/boundscheckablelist-1/removeat/)(int) | 移除 System.Collections.Generic.List 中指定索引处的元素。 |
| [UpdateBoundsCheckMode](../../aspose.pdf/boundscheckablelist-1/updateboundscheckmode/#updateboundscheckmode)(BoundsCheckMode) | 更新已初始化集合的 boundsCheckMode 参数。 |
| [UpdateBoundsCheckMode](../../aspose.pdf/boundscheckablelist-1/updateboundscheckmode/#updateboundscheckmode_1)(BoundsCheckMode, double, double) | 更新已初始化集合的 boundsCheckMode 参数。 |

### 另见

* 接口 [IBoundsCheckableItem](../iboundscheckableitem/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)