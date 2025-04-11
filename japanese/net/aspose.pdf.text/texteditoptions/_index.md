---
title: Class TextEditOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptions クラス。テキスト編集操作のオプションを説明します
type: docs
weight: 10820
url: /ja/net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions クラス

テキスト編集操作のオプションを説明します。

```csharp
public sealed class TextEditOptions : TextOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | 指定された言語変換許可のために `TextEditOptions` オブジェクトの新しいインスタンスを初期化します。 |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | 指定されたフォント置換動作モードのために `TextEditOptions` オブジェクトの新しいインスタンスを初期化します。 |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | 指定された言語変換動作モードのために `TextEditOptions` オブジェクトの新しいインスタンスを初期化します。 |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | 指定されたノーキャラクター動作モードのために `TextEditOptions` オブジェクトの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | テキストの追加または編集中に言語変換の使用を許可する値を取得または設定します。 true - 必要に応じて言語変換が適用されます（デフォルト値）。 false - 言語変換は適用されません。 |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | 編集されたテキストのクリッピングパスを処理するモードを取得します。 |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | フォント置換シナリオの動作を定義するモードを取得します。 |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | 言語変換シナリオの動作を定義するモードを取得します。 |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | フォントが要求された文字を含まない場合の動作を定義するモードを取得または設定します。 |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | ユーザーフォントが必要な文字を含まない場合に置換に使用されるフォントを取得または設定します。 |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | ソースドキュメントのページでテキストの下線を検索することを許可する値を取得または設定します。（廃止予定）代わりに TextSearchOptions.SearchForTextRelatedGraphics を使用してください。 |

### 関連項目

* クラス [TextOptions](../textoptions/)
* 名前空間 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../)