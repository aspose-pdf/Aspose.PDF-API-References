---
title: Class TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragmentAbsorber クラス。テキストフラグメントのアブソーバーオブジェクトを表します。テキスト検索を実行し、TextFragments コレクションを介して検索結果にアクセスを提供します。
type: docs
weight: 10950
url: /ja/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber クラス

テキストフラグメントのアブソーバーオブジェクトを表します。テキスト検索を実行し、[`TextFragments`](./textfragments/) コレクションを介して検索結果にアクセスを提供します。

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | ドキュメントまたはページのすべてのテキストセグメントを検索する `TextFragmentAbsorber` の新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | 指定された System.Text.RegularExpressions.Regex クラスオブジェクトのための `TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | 指定されたテキストフレーズのための `TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | テキスト編集オプションを持つ `TextFragmentAbsorber` の新しいインスタンスを初期化し、ドキュメントまたはページのすべてのテキストセグメントを検索します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | 指定されたテキストフレーズとテキスト編集オプションのための `TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | 指定されたテキストフレーズとテキスト検索オプションのための `TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | 指定されたテキストフレーズとテキスト検索オプションのための `TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | 指定されたテキストフレーズとテキスト編集オプションのための `TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | 指定されたテキストフレーズとテキスト検索オプションのための `TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | 指定されたテキストフレーズ、テキスト検索オプション、およびテキスト編集オプションのための `TextFragmentAbsorber` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | [`TextExtractionError`](../textextractionerror/) オブジェクトのリスト。テキスト抽出中に見つかったエラーに関する情報を含みます。エラーの検索は、TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行されます。また、パフォーマンスが低下する可能性があります。 |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | テキスト抽出オプションを取得または設定します。 |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | テキスト抽出中にエラーが見つかったかどうかを示す値。エラーの検索は、TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行されます。また、パフォーマンスが低下する可能性があります。 |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | `TextFragmentAbsorber` が PDF ドキュメントまたはページで検索するフレーズを取得または設定します。 |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | System.Text.RegularExpressions.Regex クラスをキーとし、[`TextFragment`](../textfragment/) を値とする検索の発生回数の辞書を取得します。 |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | [`TextAbsorber`](../textabsorber/) が PDF ドキュメントまたはページで抽出したテキストを取得します。 |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | テキスト編集オプションを取得または設定します。オプションは、要求されたシンボルがフォントで書き込めない場合の特別な動作を定義します。 |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | [`TextFragment`](../textfragment/) オブジェクトで表される検索の発生回数のコレクションを取得します。 |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | テキスト置換オプションを取得または設定します。オプションは、フラグメントテキストが短く/長く置き換えられるときの動作を定義します。 |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | 検索オプションを取得または設定します。オプションは、正規表現を使用した検索を可能にします。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | 吸収されたすべてのテキストフラグメントにフォントサイズを適用します。すべてのフラグメントがページに吸収された場合、フラグメントをループするよりも速く動作します。それ以外の場合は、ループと同様に動作します。 |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | 吸収されたすべてのテキストフラグメントにフォントを適用します。すべてのフラグメントがページに吸収された場合、フラグメントをループするよりも速く動作します。それ以外の場合は、ループと同様に動作します。 |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | 吸収されたすべてのテキストフラグメントにフォントとサイズを適用します。すべてのフラグメントがページに吸収された場合、フラグメントをループするよりも速く動作します。それ以外の場合は、ループと同様に動作します。 |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | ドキュメントからすべてのテキストを削除します。 |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | 指定されたページからすべてのテキストを削除します。 |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | 指定されたページから指定された矩形内のテキストを削除します。 |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | この `TextFragmentAbsorber` オブジェクトの TextFragments コレクションをクリアします。 |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | 指定されたドキュメントで検索を実行します。 |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | 指定されたページで検索を実行します。 |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | 指定されたフォームオブジェクトで検索を実行します。 |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | 指定された XForm でテキストを抽出します。 |

## 備考

`TextFragmentAbsorber` オブジェクトは基本的にテキスト検索シナリオで使用されます。検索が完了すると、発生回数は [`TextFragment`](../textfragment/) オブジェクトで表され、[`TextFragments`](./textfragments/) コレクションに含まれます。[`TextFragment`](../textfragment/) オブジェクトは、検索発生テキスト、テキストプロパティへのアクセスを提供し、テキストを編集したり、テキストの状態（フォント、フォントサイズ、色など）を変更したりできます。

## 例

この例は、最初の PDF ドキュメントページでテキストを見つけ、そのテキストとフォントを置き換える方法を示しています。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 参照

* クラス [TextAbsorber](../textabsorber/)
* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)