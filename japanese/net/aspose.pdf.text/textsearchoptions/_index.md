---
title: "クラス TextSearchOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Text.TextSearchOptions クラス。テキスト検索オプションを表します。"
type: docs
weight: 11230
url: /ja/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions class

テキスト検索オプションを表します。

```csharp
public sealed class TextSearchOptions : TextOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | `TextSearchOptions` オブジェクトの新しいインスタンスを初期化します。正規表現の使用モードを指定します。 |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | `TextSearchOptions` オブジェクトの新しいインスタンスを初期化します。検索対象テキストを限定する矩形を指定します。 |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | `TextSearchOptions` オブジェクトの新しいインスタンスを初期化します。検索対象テキストを限定する矩形と正規表現の使用モードを指定します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | テキスト（フラグメント）吸収器がフォントの欠如に関連するエラーを無視するかどうかを取得または設定します。true - フォントが欠如しているエラーを無視します。誤ったリソースを参照するテキストセグメントは処理中にスキップされます。false（既定） - フォント欠如エラーが例外をスローして処理を終了させます。 |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | 検索時に通常テキストの影を表すテキストフラグメントを無視するかどうかを取得または設定します。true - 影のテキストは見つかりません（検索結果に近接位置で重複フラグメントが返る場合に試してください）。false - 影のテキストも通常テキストと同様に見つかります（既定値）。 |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | 正規表現が使用されるかどうかを取得または設定します。 |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | テキストがページ境界内で検索されるかどうかを取得または設定します。 |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | テキスト（フラグメント）吸収器でテキスト抽出（デコード）エラーが記録されるかどうかを取得または設定します。true - テキスト抽出（デコード）エラーが記録されます。パフォーマンスが低下する可能性があります。false（既定） - エラーは記録されません。 |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | 検索対象テキストを囲む矩形を取得または設定します。 |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | テキスト検索時にテキスト関連のグラフィック（下線、背景など）を検索するかどうかの値を取得または設定します。true - テキスト関連のグラフィック検索が実行されます（既定値）。false - ソースドキュメントに存在する可能性のあるグラフィック要素は無視されます。パフォーマンス上の問題がある場合や、下線・背景・クリッピングを処理する必要がない場合に設定してください。 |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | アノテーション内のテキストを検索できるかどうかの値を取得または設定します。true - アノテーション内のテキストが検索されます。false - アノテーション内のテキストは TextFragmentAbsorber によって解析されません。 |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | ページ上でテキスト関連のグラフィック（下線、背景など）を検索する要素数の上限を設定する値を取得または設定します。既定は 250 です。パフォーマンス問題がある場合は小さい値を、いくつかのグラフィック要素が見つからない場合は大きい値を設定してください。 |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | テキスト検索にフォントエンジンのエンコーディングを使用するかどうかを取得または設定します。true - フォントエンジンのエンコーディングが使用されます（ドキュメントのエンコーディングが不完全で検索が失敗する場合に試してください）。false - ドキュメントのフォントエンコーディングが使用されます（既定値）。 |

### 関連項目

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


