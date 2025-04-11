---
title: Class TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextAbsorber クラス。テキストのアブソーバーオブジェクトを表します。テキスト抽出を行い、結果にアクセスするための Text オブジェクトを提供します。
type: docs
weight: 10800
url: /ja/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber クラス

テキストのアブソーバーオブジェクトを表します。テキスト抽出を行い、[`Text`](./text/) オブジェクトを介して結果にアクセスします。

```csharp
public class TextAbsorber
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | `TextAbsorber` の新しいインスタンスを初期化します。 |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | 抽出オプションを使用して `TextAbsorber` の新しいインスタンスを初期化します。 |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | テキスト検索オプションを使用して `TextAbsorber` の新しいインスタンスを初期化します。 |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | 抽出およびテキスト検索オプションを使用して `TextAbsorber` の新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | [`TextExtractionError`](../textextractionerror/) オブジェクトのリスト。テキスト抽出中に見つかったエラーに関する情報を含みます。エラーの検索は、TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行されます。また、パフォーマンスが低下する可能性があります。 |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | テキスト抽出オプションを取得または設定します。 |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | テキスト抽出中にエラーが見つかったかどうかを示す値。エラーの検索は、TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行されます。また、パフォーマンスが低下する可能性があります。 |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | `TextAbsorber` が PDF ドキュメントまたはページから抽出したテキストを取得します。 |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | テキスト検索オプションを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | 指定されたドキュメントのテキストを抽出します |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | 指定されたページのテキストを抽出します |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | 指定された XForm のテキストを抽出します。 |

## 備考

`TextAbsorber` オブジェクトは、Pdf ドキュメントまたはドキュメントのページからテキストを抽出するために使用されます。

## 例

この例は、最初の PDF ドキュメントページのテキストを抽出する方法を示しています。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### 参照

* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)