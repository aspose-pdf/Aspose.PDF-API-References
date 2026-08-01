---
title: "クラス ParagraphAbsorber"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.ParagraphAbsorber クラス。セクションや段落などのページ構造オブジェクトの吸収オブジェクトを表します。テキストのセクションと段落の検索を実行し、テキスト座標空間でそれらを記述する矩形やポリゴンへのアクセスを提供します。また、テキストセグメントの検索を行い、構造要素でグループ化された TextFragments コレクションを介して検索結果へのアクセスを提供します。"
type: docs
weight: 10850
url: /ja/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class

セクションや段落などのページ構造オブジェクトの吸収オブジェクトを表します。テキストのセクションと段落を検索し、テキスト座標空間でそれらを記述する矩形や多角形へのアクセスを提供します。また、テキストセグメントの検索を実行し、構造要素でグループ化された !:TextFragments コレクションを介して検索結果へアクセスできます。

```csharp
public class ParagraphAbsorber
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | `ParagraphAbsorber` の新しいインスタンスを初期化します。このインスタンスはドキュメントまたはページのセクション/段落の検索を実行します。 |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | `ParagraphAbsorber` の新しいインスタンスを初期化します。このインスタンスはドキュメントまたはページのセクション/段落の検索を実行します。 |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | `ParagraphAbsorber` の新しいインスタンスを初期化します。このインスタンスは、指定されたパラメータでドキュメントまたはページのセクション/段落の検索を実行します。 |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | `ParagraphAbsorber` の新しいインスタンスを初期化します。このインスタンスは、指定されたパラメータでドキュメントまたはページのセクション/段落の検索を実行します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | 次のセクションの開始テキスト行を、前のセクションの最後の段落の続きとして扱うかどうかを示す値を取得または設定します。 |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | 吸収された [`PageMarkup`](../pagemarkup/) のコレクションを取得します。 |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | ParagraphAbsorberOptions を取得または設定します。 |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | 構造のより細かい要素に対する連続検索を実行する回数を指示する値を取得または設定します。既定の検索深度は 3 です。これは、水平に分割されたセクション（ヘッダー、段落など）に対して 3 回の検索を行い、垂直に分割されたセクション（列）に対しても 3 回の検索を行うことを意味します。 |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | TextReplaceOptions を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | 指定された[`Document`](../../aspose.pdf/document/)でセクションと段落の検索を実行します。 |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | 指定された[`Page`](../../aspose.pdf/page/)で検索を実行します。 |

## 備考

検索が完了すると、[`PageMarkups`](./pagemarkups/)コレクションに[`PageMarkup`](../pagemarkup/)オブジェクトが含まれます。これらは[`MarkupSection`](../markupsection/)と[`MarkupParagraph`](../markupparagraph/)のコレクションによってページ構造を表します。[`TextFragment`](../textfragment/)オブジェクトは検索結果のテキスト、テキストプロパティへのアクセスを提供し、テキストの編集やテキスト状態（フォント、フォントサイズ、色など）の変更を可能にします。

## 例

この例では、最初の PDF ドキュメントページの各段落の最初のテキストセグメントを見つけてハイライトする方法を示しています。

```csharp
// 開く document
Document doc = new Document("input.pdf");

// ParagraphAbsorber オブジェクトを作成します
ParagraphAbsorber absorber = new ParagraphAbsorber();

// 最初のページに対してアブソーバーを受け入れます
absorber.Visit(doc.Pages[1]);

// 最初のページのマークアップオブジェクトを取得します
PageMarkup markup = absorber.PageMarkups[0];

// ページテキストの構造要素をループして、各段落の最初のテキストフラグメントを見つけます
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // テキストプロパティを更新します
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// 保存 document
doc.Save(GetOutputPath("output.pdf"));
```

### 関連項目

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


