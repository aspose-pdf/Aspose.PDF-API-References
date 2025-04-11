---
title: Class FontRepository
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.FontRepository クラス。フォント検索を実行します。システムにインストールされたフォントと標準 Pdf フォントを検索します。また、カスタムフォントを開く機能も提供します。
type: docs
weight: 10540
url: /ja/net/aspose.pdf.text/fontrepository/
---
## FontRepository クラス

フォント検索を実行します。システムにインストールされたフォントと標準 Pdf フォントを検索します。また、カスタムフォントを開く機能も提供します。

```csharp
public sealed class FontRepository
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FontRepository](fontrepository/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | フォントソースのコレクションを取得します。 |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | フォント置換戦略のコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | 指定されたフォント名のフォントを検索して返します。 |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | 大文字と小文字の区別を無視するか尊重して、指定されたフォント名のフォントを検索して返します。 |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | 指定されたフォント名とフォントスタイルのフォントを検索して返します。 |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | 大文字と小文字の区別を無視するか尊重して、指定されたフォント名とフォントスタイルのフォントを検索して返します。 |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | システムにインストールされたフォントと標準 Pdf フォントをロードします。このメソッドはフォントのロードプロセスを高速化するために設計されました。デフォルトでは、任意のフォントの最初のリクエスト時にフォントがロードされます。このメソッドを使用すると、Pdf ドキュメントが開かれる前にシステムおよび標準 Pdf フォントが即座にロードされます。 |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | 指定されたフォントファイルパスのフォントを開きます。 |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | 指定されたフォントストリームのフォントを開きます。 |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | 指定されたフォントファイルパスとメトリクスファイルパスのフォントを開きます。 |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | プロパティ [`Sources`](./sources/) で指定されたすべてのフォントを再ロードします。 |

## 例

この例は、フォントを見つけて最初のページのテキストのフォントを置き換える方法を示しています。

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 参照

* クラス [TextFragmentAbsorber](../textfragmentabsorber/)
* クラス [Document](../../aspose.pdf/document/)
* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)