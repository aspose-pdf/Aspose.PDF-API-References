---
title: FontCollection
second_title: Aspose.PDF for .NET API 参考
description: 代表字体集合
type: docs
weight: 6710
url: /zh/net/aspose.pdf.text/fontcollection/
---
## FontCollection class

代表字体集合。

```csharp
public sealed class FontCollection : ICollection<Font>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count) { get; } | 获取数量[`Font`](../font)集合中实际包含的对象元素。 |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly) { get; } | 获取表示集合是否为只读的值 |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized) { get; } | 获取一个值，该值指示对集合的访问是否同步（线程安全）。 |
| [Item](../../aspose.pdf.text/fontcollection/item) { get; } | 获取指定索引处的字体元素。 (2 indexers) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot) { get; } | 获取可用于同步访问集合的对象。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add)(Font, out string) | 将新字体添加到字体资源并返回自动分配的字体资源名称。 |
| [Contains](../../aspose.pdf.text/fontcollection/contains#contains)(Font) | 确定集合是否包含特定值。 |
| [Contains](../../aspose.pdf.text/fontcollection/contains#contains_1)(string) | 检查字体集合中是否存在字体。 |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto)(Font[], int) | 将整个集合复制到一个兼容的一维数组中，从目标数组的指定索引开始 |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator)() | 返回整个集合的枚举数。 |
| [Remove](../../aspose.pdf.text/fontcollection/remove)(Font) | 从集合中删除指定的项目。 |

### 评论

表示的字体集合[`FontCollection`](../fontcollection)类用于多种场景。 例如，在具有[`Fonts`](../../aspose.pdf/resources/fonts)财产。

### 例子

该示例演示了如何将页面上声明的所有字体设为嵌入。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 确保嵌入页面资源上声明的所有字体
// 请注意，如果在表单资源上声明了字体，则无法从页面资源中访问它们
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### 也可以看看

* class [Font](../font)
* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
