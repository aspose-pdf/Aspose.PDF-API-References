---
title: "FontCollection クラス"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.FontCollection クラス。フォントコレクションを表します。"
type: docs
weight: 10710
url: /ja/net/aspose.pdf.text/fontcollection/
---
## FontCollection class

フォントコレクションを表します。

```csharp
public sealed class FontCollection : ICollection<Font>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | コレクションに実際に含まれる [`Font`](../font/) オブジェクト要素の数を取得します。 |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | コレクションが読み取り専用かどうかを示す値を取得します |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | コレクションへのアクセスが同期化されているか（スレッドセーフ）を示す値を取得します。 |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | 指定されたインデックスのフォント要素を取得します。（2 つのインデクサー） |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | コレクションへのアクセスを同期化するために使用できるオブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | フォントリソースに新しいフォントを追加し、フォントリソースに自動的に割り当てられた名前を返します。 |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | コレクションが特定の値を含むかどうかを判断します。 |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | フォントがフォントコレクションに存在するかどうかを確認します。 |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | 対象配列の指定インデックスから開始して、互換性のある一次元配列にコレクション全体をコピーします。 |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | コレクション全体の列挙子を返します。 |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | コレクションから指定された項目を削除します。 |

## 備考

`FontCollection` クラスで表されるフォントコレクションは、さまざまなシナリオで使用されます。例えば、[`Fonts`](../../aspose.pdf/resources/fonts/) プロパティを持つリソースで使用されます。

## 例

この例は、ページ上で宣言されたすべてのフォントを埋め込みフォントにする方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// ページリソースで宣言されたすべてのフォントが埋め込まれていることを確認します。
// フォームリソースで宣言されたフォントは、ページリソースからアクセスできないことに注意してください。
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### 関連項目

* class [Font](../font/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


