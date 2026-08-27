---
title: "クラス FontRepository"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.FontRepository クラス。フォント検索を実行します。システムにインストールされたフォントと標準 PDF フォントを検索します。また、カスタムフォントを開く機能も提供します。"
type: docs
weight: 10720
url: /ja/net/aspose.pdf.text/fontrepository/
---
## FontRepository class

フォント検索を実行します。システムにインストールされたフォントと標準 PDF フォントを検索します。また、カスタムフォントを開く機能も提供します。

```csharp
public sealed class FontRepository
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FontRepository](fontrepository/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | フォント ソース コレクションを取得します。 |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | フォント 置換 ストラテジー コレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | 指定されたフォント名のフォントを検索して返します。 |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | 大文字小文字の区別を無視または考慮して、指定されたフォント名のフォントを検索して返します。 |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | 指定されたフォント名とフォントスタイルのフォントを検索して返します。 |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | 大文字小文字の区別を無視または考慮して、指定されたフォント名とフォントスタイルのフォントを検索して返します。 |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | システムにインストールされたフォントと標準の Pdf フォントをロードします。このメソッドはフォントのロード処理を高速化するために設計されました。既定では、任意のフォントが最初に要求されたときにフォントがロードされます。このメソッドを使用すると、Pdf ドキュメントが開かれる前にシステムおよび標準の Pdf フォントをすぐにロードします。 |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | 指定されたフォント ファイル パスでフォントを開きます。 |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | 指定されたフォント ストリームでフォントを開きます。 |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | 指定されたフォント ファイル パスとメトリクス ファイル パスでフォントを開きます。 |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | プロパティ [`Sources`](./sources/) で指定されたすべてのフォントを再ロードします。 |

## 例

この例は、フォントを検索し、最初のページのテキストのフォントを置換する方法を示しています。

```csharp
// フォントを検索
Font font = FontRepository.FindFont("Arial");

// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所のフォントを変更
absorber.TextFragments[1].TextState.Font = font;

// 保存 document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 関連項目

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


