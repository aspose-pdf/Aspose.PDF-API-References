---
title: Class ParagraphAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.ParagraphAbsorber クラス。セクションや段落などのページ構造オブジェクトのアブソーバーオブジェクトを表します。テキストのセクションや段落を検索し、テキスト座標空間でそれを説明する矩形や多角形へのアクセスを提供します。また、テキストセグメントの検索を行い、構造要素によってグループ化された TextFragments コレクションを介して検索結果へのアクセスを提供します。
type: docs
weight: 10670
url: /ja/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber クラス

セクションや段落などのページ構造オブジェクトのアブソーバーオブジェクトを表します。テキストのセクションや段落を検索し、テキスト座標空間でそれを説明する矩形や多角形へのアクセスを提供します。また、テキストセグメントの検索を行い、構造要素によってグループ化された !:TextFragments コレクションを介して検索結果へのアクセスを提供します。

```csharp
public class ParagraphAbsorber
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | ドキュメントまたはページのセクション/段落を検索する `ParagraphAbsorber` の新しいインスタンスを初期化します。 |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | ドキュメントまたはページのセクション/段落を検索する `ParagraphAbsorber` の新しいインスタンスを初期化します。 |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | 指定されたパラメーターでドキュメントまたはページのセクション/段落を検索する `ParagraphAbsorber` の新しいインスタンスを初期化します。 |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | 指定されたパラメーターでドキュメントまたはページのセクション/段落を検索する `ParagraphAbsorber` の新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | 次のセクションの開始テキスト行が前のセクションの最後の段落の続きとして扱われるかどうかを示す値を取得または設定します。 |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | 吸収された [`PageMarkup`](../pagemarkup/) のコレクションを取得します。 |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | ParagraphAbsorberOptions を取得または設定します。 |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | 構造のより細かい要素のために何回連続検索を行うかを指示する値を取得または設定します。デフォルトの検索深度は 3 です。これは、水平に分割されたセクション（ヘッダー、段落など）に対して 3 回、垂直に分割されたセクション（列）に対して 3 回の検索を意味します。 |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | TextReplaceOptions を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | 指定された [`Document`](../../aspose.pdf/document/) でセクションと段落を検索します。 |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | 指定された [`Page`](../../aspose.pdf/page/) で検索を行います。 |

## 備考

検索が完了すると、[`PageMarkups`](./pagemarkups/) コレクションには、[`MarkupSection`](../markupsection/) と [`MarkupParagraph`](../markupparagraph/) のコレクションによってページ構造を表す [`PageMarkup`](../pagemarkup/) オブジェクトが含まれます。[`TextFragment`](../textfragment/) オブジェクトは、検索されたテキストの発生、テキストプロパティへのアクセスを提供し、テキストを編集したり、テキストの状態（フォント、フォントサイズ、色など）を変更したりすることができます。

## 例

この例では、最初の PDF ドキュメントページの各段落の最初のテキストセグメントを見つけてハイライトする方法を示します。

```csharp
// Open document
Document doc = new Document("input.pdf");

// Create ParagraphAbsorber object
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Get markup object of first page
PageMarkup markup = absorber.PageMarkups[0];

// Loop through structure elements of the page text to find first text fragment of each paragraph
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Update text properties
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Save document
doc.Save(GetOutputPath("output.pdf"));
```

### 参照

* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)