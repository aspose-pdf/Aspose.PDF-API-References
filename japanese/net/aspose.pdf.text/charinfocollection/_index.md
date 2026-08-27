---
title: "クラス CharInfoCollection"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.CharInfoCollection クラス。CharInfo オブジェクトのコレクションを表します"
type: docs
weight: 10630
url: /ja/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection class

CharInfo オブジェクトのコレクションを表します。

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | コレクションに実際に含まれる [`CharInfo`](../charinfo/) オブジェクト要素の数を取得します。 |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | コレクションが読み取り専用かどうかを示す値を取得します |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | コレクションへのアクセスが同期化されているか（スレッドセーフ）を示す値を取得します。 |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | 指定されたインデックスの CharInfo 要素を取得します。 |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | コレクションへのアクセスを同期化するために使用できるオブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | コレクションは読み取り専用です。NotImplementedException をスローします。 |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | コレクションは読み取り専用です。常に NotImplementedException をスローします。 |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | コレクションが特定の値を含むかどうかを判断します。 |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | 対象配列の指定インデックスから開始して、互換性のある一次元配列にコレクション全体をコピーします。 |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | コレクション全体の列挙子を返します。 |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | コレクションは読み取り専用です。NotImplementedException をスローします。 |

## 備考

テキスト セグメント文字の位置情報へのアクセスを提供します。

## 例

この例は、すべての文字を反復処理し、文字情報を取得する方法を示します。

```csharp
//ドキュメントを開く
Document pdfDocument = new Document(inFile);
//ページのすべてのテキスト オブジェクトを収集するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
//すべてのページに対して吸収器を受け入れます
pdfDocument.Pages[1].Accept(textFragmentAbsorber);
//抽出されたテキスト フラグメントを取得します
TextFragmentCollection textFragmentCollection = textFragmentAbsorber.TextFragments;
            
//フラグメントをループ処理します
foreach (TextFragment textFragment in textFragmentCollection)
{
    //セグメントをループ処理する
    foreach (TextSegment textSegment in textFragment.Segments)
    {
        //文字をループ処理する
        for (int i = 1; i <= textSegment.Text.Length; i++)
        {
            CharInfo charInfo = textSegment.Characters[i];

            // 文字の位置と矩形情報を出力する
            Console.WriteLine("XIndent : {0} ", charInfo.Position.XIndent);
            Console.WriteLine("YIndent : {0} ", charInfo.Position.YIndent);
            Console.WriteLine("Width : {0} ", charInfo.Rectangle.Width);
            Console.WriteLine("Height : {0} ", charInfo.Rectangle.Height);
        }
    }
}
```

### 関連項目

* class [CharInfo](../charinfo/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


