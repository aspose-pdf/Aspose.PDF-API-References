---
title: Class TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextSearchOptions クラス。テキスト検索オプションを表します
type: docs
weight: 11040
url: /ja/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions クラス

テキスト検索オプションを表します

```csharp
public sealed class TextSearchOptions : TextOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | `TextSearchOptions` オブジェクトの新しいインスタンスを初期化します。正規表現の使用モードを指定します。 |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | `TextSearchOptions` オブジェクトの新しいインスタンスを初期化します。検索対象のテキストを限定する矩形を指定します。 |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | `TextSearchOptions` オブジェクトの新しいインスタンスを初期化します。検索対象のテキストを限定する矩形と正規表現の使用モードを指定します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | フォントの欠如に関連するエラーがテキスト（フラグメント）アブソーバーによって無視されるかどうかを取得または設定します。true - フォントの欠如に関するエラーが無視されることを意味します。無効なリソースを参照するテキストセグメントは処理中にスキップされます。false（デフォルト） - フォントの欠如エラーは例外をスローして処理を終了します。 |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | 通常のテキストの影を表すテキストフラグメントが検索中に無視されるかどうかを取得または設定します。true - 影のテキストが見つからないことを意味します（テキスト検索が近接した位置で重複したフラグメントを返す場合はこれを試してください）。false - 影のテキストも通常のテキストと同様に見つかることを意味します（デフォルト値）。 |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | 正規表現が使用されているかどうかを取得または設定します。 |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | テキストがページの境界内で検索されるかどうかを取得または設定します。 |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | テキスト抽出（デコーディング）エラーがテキスト（フラグメント）アブソーバーにログされるかどうかを取得または設定します。true - テキスト抽出（デコーディング）エラーがログされることを意味します。パフォーマンスが低下する可能性があります。false（デフォルト） - エラーログはありません。 |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | 検索対象のテキストを囲む矩形を取得または設定します。 |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | テキスト検索中にテキスト関連のグラフィック（下線、背景など）を検索することを許可する値を取得または設定します。true - テキスト関連のグラフィックが検索されます（デフォルト値）。false - ソースドキュメントに存在する可能性のあるグラフィック要素は無視されます。パフォーマンスの問題がある場合や、下線、背景、クリッピングを処理する必要がない場合はこれを設定します。 |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | 注釈内のテキストを検索することを許可する値を取得または設定します。true - 注釈内でテキストが検索されます。false - 注釈内のテキストは TextFragmentAbsorber によって解析されません。 |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | 指定された数の要素に対してページ上のテキスト関連のグラフィック（下線、背景など）を検索することを制限する値を取得または設定します。デフォルトは 250 です。パフォーマンスの問題がある場合は小さい値を設定し、見つからなかったグラフィック要素がある場合は大きい値を試してください。 |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | テキストがフォントエンジンエンコーディングを使用して検索されるかどうかを取得または設定します。true - フォントエンジンエンコーディングが使用されることを意味します（ドキュメント内のエンコーディングが不完全なためにテキスト検索が失敗する場合はこれを試してください）。false - ドキュメントのフォントエンコーディングが使用されます（デフォルト値）。 |

### 参照

* クラス [TextOptions](../textoptions/)
* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)