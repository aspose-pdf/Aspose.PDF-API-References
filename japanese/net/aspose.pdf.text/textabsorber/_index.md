---
title: "クラス TextAbsorber"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.TextAbsorber クラス。テキストの吸収オブジェクトを表します。テキスト抽出を実行し、結果に Text オブジェクトを介してアクセスできます。"
type: docs
weight: 10980
url: /ja/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber class

テキストの吸収オブジェクトを表します。テキスト抽出を実行し、結果に [`Text`](./text/) オブジェクトを介してアクセスできます。

```csharp
public class TextAbsorber
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | `TextAbsorber` の新しいインスタンスを初期化します。 |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | 抽出オプションを指定して `TextAbsorber` の新しいインスタンスを初期化します。 |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | テキスト検索オプションを指定して `TextAbsorber` の新しいインスタンスを初期化します。 |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | 抽出オプションとテキスト検索オプションの両方を指定して `TextAbsorber` の新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | [`TextExtractionError`](../textextractionerror/) オブジェクトのリストです。テキスト抽出中に見つかったエラーに関する情報が含まれます。エラーの検索は TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行され、パフォーマンスが低下する可能性があります。 |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | テキスト抽出オプションを取得または設定します。 |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | この値はテキスト抽出中にエラーが見つかったかどうかを示します。エラーの検索は TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行され、パフォーマンスが低下する可能性があります。 |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | `TextAbsorber` が PDF ドキュメントまたはページから抽出したテキストを取得します。 |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | テキスト検索オプションを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | 指定されたドキュメントからテキストを抽出します。 |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | 指定されたページからテキストを抽出します。 |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | 指定された XForm からテキストを抽出します。 |

## 備考

`TextAbsorber` オブジェクトは、Pdf ドキュメントまたはそのページからテキストを抽出するために使用されます。

## 例

この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。

```csharp
// ドキュメントを開く
Document doc = new Document(inFile);

// テキストを抽出するために TextAbsorber オブジェクトを作成します。
TextAbsorber absorber = new TextAbsorber();

// 最初のページに対して absorber を受け入れます。
doc.Pages[1].Accept(absorber);

// 抽出されたテキストを取得します。
string extractedText = absorber.Text;

```

### 関連項目

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


