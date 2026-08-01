---
title: "クラス Font"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.Font クラス。フォントオブジェクトを表します。"
type: docs
weight: 10690
url: /ja/net/aspose.pdf.text/font/
---
## Font class

フォントオブジェクトを表します。

```csharp
public sealed class Font
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | PDF フォントオブジェクトの BaseFont 値を取得します。フォントの PostScript 名とも呼ばれます。 |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | PDF フォント（主に中国語/日本語/韓国語フォント）の中には、特定のフォント名を持つものがあります。この名前は PDF フォントプロパティ「BaseFont」の値で、場合によっては十六進形式で表されることがあります。直接この名前を読むと読めない形式になることがあります。可読形式を取得するには、そのフォント固有の規則でフォント名をデコードする必要があります。このプロパティはデコードされたフォント名を返すため、読めない [`FontName`](./fontname/) に遭遇した場合に使用してください。プロパティ [`FontName`](./fontname/) が可読形式であれば、このプロパティは [`FontName`](./fontname/) と同じになりますので、フォント名を可読形式で取得したいあらゆるケースでこのプロパティを使用できます。 |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | `Font` オブジェクトのフォント名を取得します。 |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | フォントの動作を調整するための便利なプロパティ |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | システムにフォントが存在（インストール）しているかどうかを示す値を取得します。 |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | フォントが埋め込まれているかどうかを示す値を取得または設定します。IFont に基づくフォントは自動的にサブセット化され、埋め込まれます。 |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | フォントがサブセットであるかどうかを示す値を取得または設定します。IFont に基づくフォントは自動的にサブセット化され、埋め込まれます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | このメソッドの目的は、フォントの埋め込みが失敗した場合にエラーの説明を返すことです。エラーがなければ空文字列を返します。 |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | 文字列を測定します。 |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | フォントをストリームに保存します。フォントは元のドキュメントの変換コピーでのみ使用されることを想定した中間 TTF 形式で保存されることに注意してください。フォントファイルは元のドキュメントのコンテキスト外で使用することは想定されていません。 |

## 例

この例では、最初のページでテキストを検索し、最初に見つかった検索結果のフォントを変更する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// すべての "hello world" テキスト出現箇所を検索するために TextFragmentAbsorber オブジェクトを作成します
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(absorber);

// フォントを作成し、埋め込み対象としてマークします。
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// 最初のテキスト出現箇所のフォントを変更
absorber.TextFragments[1].TextState.Font = font;


// 保存 document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 関連項目

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [FontRepository](../fontrepository/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


