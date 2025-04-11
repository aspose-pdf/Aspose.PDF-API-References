---
title: Class CharInfoCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.CharInfoCollection クラス。CharInfo オブジェクトのコレクションを表します
type: docs
weight: 10450
url: /ja/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection クラス

CharInfo オブジェクトのコレクションを表します。

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | コレクションに実際に含まれている [`CharInfo`](../charinfo/) オブジェクト要素の数を取得します。 |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | コレクションへのアクセスが同期されているかどうか（スレッドセーフ）を示す値を取得します。 |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | 指定されたインデックスの CharInfo 要素を取得します。 |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | コレクションへのアクセスを同期するために使用できるオブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | コレクションは読み取り専用であり、NotImplementedException をスローします。 |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | コレクションは読み取り専用です。常に NotImplementedException をスローします。 |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | コレクションが特定の値を含むかどうかを判断します。 |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | 指定されたインデックスから始めて、互換性のある一次元配列にコレクション全体をコピーします。 |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | コレクション全体の列挙子を返します。 |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | コレクションは読み取り専用であり、NotImplementedException をスローします。 |

## 備考

テキストセグメントの文字の位置情報へのアクセスを提供します。

## 例

この例では、すべての文字を反復処理し、文字を取得する方法を示します。

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

### 参照

* クラス [CharInfo](../charinfo/)
* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)