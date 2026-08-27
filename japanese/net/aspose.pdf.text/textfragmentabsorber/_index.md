---
title: "クラス TextFragmentAbsorber"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.TextFragmentAbsorber クラス。テキスト フラグメントの吸収オブジェクトを表します。テキスト検索を実行し、TextFragments コレクションを介して検索結果にアクセスできるようにします。"
type: docs
weight: 11130
url: /ja/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

テキスト フラグメントの吸収オブジェクトを表します。テキスト検索を実行し、[`TextFragments`](./textfragments/) コレクションを介して検索結果にアクセスできます。

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | ドキュメントまたはページのすべてのテキスト セグメントの検索を実行する `TextFragmentAbsorber` の新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | 指定された System.Text.RegularExpressions.Regex クラス オブジェクト用に `TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | 指定されたテキスト フレーズ用に `TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | `TextFragmentAbsorber` の新しいインスタンスをテキスト編集オプションで初期化し、Document または Page のすべてのテキストセグメントを検索します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | 指定されたテキストフレーズとテキスト編集オプション用に、`TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | 指定されたテキストフレーズとテキスト検索オプション用に、`TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | 指定されたテキストフレーズとテキスト検索オプション用に、`TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | 指定されたテキストフレーズとテキスト編集オプション用に、`TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | 指定されたテキストフレーズとテキスト検索オプション用に、`TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | 指定されたテキストフレーズ、テキスト検索オプション、テキスト編集オプション用に、`TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | [`TextExtractionError`](../textextractionerror/) オブジェクトのリストです。テキスト抽出中に見つかったエラーに関する情報が含まれます。エラーの検索は TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行され、パフォーマンスが低下する可能性があります。 |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | テキスト抽出オプションを取得または設定します。 |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | この値はテキスト抽出中にエラーが見つかったかどうかを示します。エラーの検索は TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行され、パフォーマンスが低下する可能性があります。 |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | `TextFragmentAbsorber` が PDF Document または Page で検索するフレーズを取得または設定します。 |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | 検索結果の辞書を取得します。キーは System.Text.RegularExpressions.Regex クラス、値は [`TextFragment`](../textfragment/) です。 |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | PDF Document または Page で [`TextAbsorber`](../textabsorber/) が抽出したテキストを取得します。 |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | テキスト編集オプションを取得または設定します。オプションは要求されたシンボルがフォントで描画できない場合の特別な動作を定義します。 |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | 検索結果を表す [`TextFragment`](../textfragment/) オブジェクトのコレクションを取得します。 |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | テキスト置換オプションを取得または設定します。このオプションは、フラグメントテキストが短くまたは長く置換される際の動作を定義します。 |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | 検索オプションを取得または設定します。このオプションにより正規表現を使用した検索が可能になります。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | 吸収されたすべてのテキストフラグメントにフォントサイズを適用します。すべてのフラグメントが page(s) 上で吸収されている場合、フラグメントをループ処理するよりも高速に動作します。そうでない場合はループ処理と同様に動作します。 |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | 吸収されたすべてのテキストフラグメントにフォントを適用します。すべてのフラグメントが page(s) 上で吸収されている場合、フラグメントをループ処理するよりも高速に動作します。そうでない場合はループ処理と同様に動作します。 |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | 吸収されたすべてのテキストフラグメントにフォントとサイズを適用します。すべてのフラグメントが page(s) 上で吸収されている場合、フラグメントをループ処理するよりも高速に動作します。そうでない場合はループ処理と同様に動作します。 |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | Document からすべてのテキストを削除します。 |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | 指定された Page からすべてのテキストを削除します。 |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | 指定された Page の指定された矩形領域内のテキストを削除します。 |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | この `TextFragmentAbsorber` オブジェクトの TextFragments コレクションをクリアします。 |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | 指定された Document で検索を実行します。 |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | 指定された Page で検索を実行します。 |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | 指定されたフォームオブジェクトで検索を実行します。 |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | 指定された XForm からテキストを抽出します。 |

## 備考

`TextFragmentAbsorber` オブジェクトは主にテキスト検索シナリオで使用されます。検索が完了すると、検索結果は [`TextFragment`](../textfragment/) オブジェクトとして表され、これらは [`TextFragments`](./textfragments/) コレクションに含まれます。[`TextFragment`](../textfragment/) オブジェクトは検索結果のテキスト、テキストプロパティへのアクセスを提供し、テキストの編集やテキスト状態（フォント、フォントサイズ、カラーなど）の変更が可能です。

## 例

この例では、最初の PDF 文書ページでテキストを検索し、そのテキストとフォントを置換する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// document テキストフォントを変更するために使用されるフォントを検索します
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// 最初のテキスト出現箇所のテキストとフォントを変更します
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// 保存 document
doc.Save(@"D:\Tests\output.pdf");  
```

### 関連項目

* class [TextAbsorber](../textabsorber/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


