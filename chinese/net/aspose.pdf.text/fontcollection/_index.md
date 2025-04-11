---
title: Class FontCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.FontCollection 类。表示字体集合
type: docs
weight: 10530
url: /zh/net/aspose.pdf.text/fontcollection/
---
## FontCollection 类

表示字体集合。

```csharp
public sealed class FontCollection : ICollection<Font>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | 获取集合中实际包含的 [`Font`](../font/) 对象元素的数量。 |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | 获取一个值，指示集合是否为只读 |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | 获取一个值，指示对集合的访问是否是同步的（线程安全）。 |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | 获取指定索引处的字体元素。（2 个索引器） |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | 获取一个可以用于同步访问集合的对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | 将新字体添加到字体资源，并返回自动分配的字体资源名称。 |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | 确定集合是否包含特定值。 |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | 检查字体是否存在于字体集合中。 |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | 将整个集合复制到一个兼容的一维数组，从目标数组的指定索引开始 |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | 返回整个集合的枚举器。 |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | 从集合中删除指定项。 |

## 备注

由 `FontCollection` 类表示的字体集合在多个场景中使用。例如，在具有 [`Fonts`](../../aspose.pdf/resources/fonts/) 属性的资源中。

## 示例

该示例演示如何将页面上声明的所有字体作为嵌入字体。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// ensure all fonts declared on page resources are embedded
// note that if fonts are declared on form resources they are not accessible from page resources
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### 另请参阅

* 类 [Font](../font/)
* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../)