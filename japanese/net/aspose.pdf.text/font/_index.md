---
title: Class Font
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.Font クラス。フォントオブジェクトを表します
type: docs
weight: 10510
url: /ja/net/aspose.pdf.text/font/
---
## フォントクラス

フォントオブジェクトを表します。

```csharp
public sealed class Font
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | PDFフォントオブジェクトのBaseFont値を取得します。フォントのPostScript名としても知られています。 |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | 時々、PDFフォント（通常は中国語/日本語/韓国語フォント）は特定のフォント名を持つことがあります。この名前はPDFフォントプロパティ「BaseFont」の値であり、時にはこのプロパティが16進数形式で表されることがあります。この名前を直接読むと、読み取れない形式で表されることがあります。読みやすい形式を取得するには、このフォントに特有のルールに従ってフォント名をデコードする必要があります。このプロパティはデコードされたフォント名を返すため、読み取れない [`FontName`](./fontname/) に出会った場合に使用してください。プロパティ [`FontName`](./fontname/) が読みやすい形式を持つ場合、このプロパティは [`FontName`](./fontname/) と同じになるため、フォント名を読みやすい形式で取得する必要がある場合はこのプロパティを使用できます。 |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | `Font` オブジェクトのフォント名を取得します。 |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | フォントの動作を調整するための便利なプロパティ |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | フォントがシステムに存在（インストール）しているかどうかを示す値を取得します。 |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | フォントが埋め込まれているかどうかを示す値を取得または設定します。IFontに基づくフォントは自動的にサブセット化され、埋め込まれます。 |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | フォントがサブセットであるかどうかを示す値を取得または設定します。IFontに基づくフォントは自動的にサブセット化され、埋め込まれます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | このメソッドの目的は、フォントの埋め込みが失敗した場合にエラーの説明を返すことです。エラーがない場合は空の文字列を返します。 |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | 文字列を測定します。 |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | フォントをストリームに保存します。フォントは、元のドキュメントの変換されたコピーでのみ使用されることを意図した中間TTF形式に保存されることに注意してください。フォントファイルは元のドキュメントのコンテキスト外で使用されることを意図していません。 |

## 例

この例は、最初のページでテキストを検索し、最初の検索結果のフォントを変更する方法を示しています。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;


// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 参照

* クラス [TextFragmentAbsorber](../textfragmentabsorber/)
* クラス [FontRepository](../fontrepository/)
* クラス [Document](../../aspose.pdf/document/)
* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)