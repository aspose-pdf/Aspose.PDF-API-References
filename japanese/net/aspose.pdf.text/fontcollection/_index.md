---
title: Class FontCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.FontCollection クラス。フォントコレクションを表します
type: docs
weight: 10530
url: /ja/net/aspose.pdf.text/fontcollection/
---
## FontCollection クラス

フォントコレクションを表します。

```csharp
public sealed class FontCollection : ICollection<Font>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | コレクションに実際に含まれている [`Font`](../font/) オブジェクト要素の数を取得します。 |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | コレクションへのアクセスが同期されているかどうか（スレッドセーフ）を示す値を取得します。 |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | 指定されたインデックスのフォント要素を取得します。（2 つのインデクサ） |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | コレクションへのアクセスを同期するために使用できるオブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | フォントリソースに新しいフォントを追加し、フォントリソースの自動割り当て名を返します。 |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | コレクションが特定の値を含むかどうかを判断します。 |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | フォントコレクションにフォントが存在するかどうかを確認します。 |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | 指定されたインデックスから始めて、互換性のある一次元配列にコレクション全体をコピーします。 |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | コレクション全体の列挙子を返します。 |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | コレクションから指定されたアイテムを削除します。 |

## 備考

`FontCollection` クラスによって表されるフォントコレクションは、いくつかのシナリオで使用されます。たとえば、[`Fonts`](../../aspose.pdf/resources/fonts/) プロパティを持つリソースで使用されます。

## 例

この例は、ページに宣言されたすべてのフォントを埋め込まれたものにする方法を示しています。

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

### 参照

* クラス [Font](../font/)
* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)