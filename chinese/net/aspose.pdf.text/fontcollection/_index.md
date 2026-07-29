---
title: "类 FontCollection"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.FontCollection 类。表示字体集合。"
type: docs
weight: 10710
url: /zh/net/aspose.pdf.text/fontcollection/
---
## FontCollection class

表示字体集合。

```csharp
public sealed class FontCollection : ICollection<Font>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | 获取集合中实际包含的 [`Font`](../font/) 对象元素的数量。 |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | 获取指示集合是否为只读的值 |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | 获取指示对集合的访问是否已同步（线程安全）的值。 |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | 获取指定索引处的字体元素。（2 个索引器） |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | 获取可用于同步对集合访问的对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | 向字体资源添加新字体并返回自动分配的字体资源名称。 |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | 确定集合是否包含特定值。 |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | 检查字体是否存在于字体集合中。 |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | 将整个集合复制到兼容的一维 Array 中，从目标数组的指定索引开始 |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | 返回整个集合的枚举器。 |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | 删除集合中指定的项。 |

## 备注

`FontCollection` 类表示的字体集合在多种场景中使用。例如，在具有 [`Fonts`](../../aspose.pdf/resources/fonts/) 属性的资源中。

## 示例

示例演示如何将页面上声明的所有字体设为嵌入。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 确保页面资源中声明的所有字体均已嵌入
// 注意，如果字体声明在表单资源中，则无法从页面资源访问它们。
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### 另请参见

* class [Font](../font/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


