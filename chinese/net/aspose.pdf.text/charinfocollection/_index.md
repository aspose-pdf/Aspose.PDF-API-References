---
title: "类 CharInfoCollection"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.CharInfoCollection 类。表示 CharInfo 对象的集合"
type: docs
weight: 10630
url: /zh/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection class

表示 CharInfo 对象集合。

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | 获取集合中实际包含的 [`CharInfo`](../charinfo/) 对象元素的数量。 |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | 获取指示集合是否为只读的值 |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | 获取指示对集合的访问是否已同步（线程安全）的值。 |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | 获取指定索引处的 CharInfo 元素。 |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | 获取可用于同步对集合访问的对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | 集合为只读，抛出 NotImplementedException。 |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | 集合为只读。始终抛出 NotImplementedException。 |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | 确定集合是否包含特定值。 |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | 将整个集合复制到兼容的一维 Array 中，从目标数组的指定索引开始 |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | 返回整个集合的枚举器。 |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | 集合为只读，抛出 NotImplementedException。 |

## 备注

提供对文本段字符定位信息的访问。

## 示例

示例演示如何遍历所有字符并检索字符

```csharp
//打开文档
Document pdfDocument = new Document(inFile);
//创建 TextFragmentAbsorber 对象以收集页面的所有文本对象
TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
//对所有页面接受吸收器
pdfDocument.Pages[1].Accept(textFragmentAbsorber);
//获取提取的文本片段
TextFragmentCollection textFragmentCollection = textFragmentAbsorber.TextFragments;
            
//遍历这些片段
foreach (TextFragment textFragment in textFragmentCollection)
{
    //遍历段
    foreach (TextSegment textSegment in textFragment.Segments)
    {
        //遍历字符
        for (int i = 1; i <= textSegment.Text.Length; i++)
        {
            CharInfo charInfo = textSegment.Characters[i];

            // 打印字符位置和矩形信息
            Console.WriteLine("XIndent : {0} ", charInfo.Position.XIndent);
            Console.WriteLine("YIndent : {0} ", charInfo.Position.YIndent);
            Console.WriteLine("Width : {0} ", charInfo.Rectangle.Width);
            Console.WriteLine("Height : {0} ", charInfo.Rectangle.Height);
        }
    }
}
```

### 另请参见

* class [CharInfo](../charinfo/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


