---
title: Class CharInfoCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.CharInfoCollection 类。表示 CharInfo 对象集合
type: docs
weight: 10450
url: /zh/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection 类

表示 CharInfo 对象集合。

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | 获取集合中实际包含的 [`CharInfo`](../charinfo/) 对象元素的数量。 |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | 获取一个值，指示集合是否为只读 |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | 获取一个值，指示对集合的访问是否是同步的（线程安全）。 |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | 获取指定索引处的 CharInfo 元素。 |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | 获取一个可以用于同步访问集合的对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | 集合是只读的，抛出 NotImplementedException。 |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | 集合是只读的。始终抛出 NotImplementedException。 |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | 确定集合是否包含特定值。 |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | 将整个集合复制到一个兼容的一维数组，从目标数组的指定索引开始 |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | 返回整个集合的枚举器。 |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | 集合是只读的，抛出 NotImplementedException。 |

## 备注

提供对文本段字符的定位信息的访问。

## 示例

该示例演示如何遍历所有字符并检索字符

```csharp
//open document
Document pdfDocument = new Document(inFile);
//create TextFragmentAbsorber object to collect all the text objects of the page
TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
//accept the absorber for all the pages
pdfDocument.Pages[1].Accept(textFragmentAbsorber);
//get the extracted text fragments
TextFragmentCollection textFragmentCollection = textFragmentAbsorber.TextFragments;
            
//loop through the fragments
foreach (TextFragment textFragment in textFragmentCollection)
{
    //loop through the segments
    foreach (TextSegment textSegment in textFragment.Segments)
    {
        //loop through the characters
        for (int i = 1; i <= textSegment.Text.Length; i++)
        {
            CharInfo charInfo = textSegment.Characters[i];

            // print character position and rectangle info
            Console.WriteLine("XIndent : {0} ", charInfo.Position.XIndent);
            Console.WriteLine("YIndent : {0} ", charInfo.Position.YIndent);
            Console.WriteLine("Width : {0} ", charInfo.Rectangle.Width);
            Console.WriteLine("Height : {0} ", charInfo.Rectangle.Height);
        }
    }
}
```

### 另请参阅

* 类 [CharInfo](../charinfo/)
* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../)