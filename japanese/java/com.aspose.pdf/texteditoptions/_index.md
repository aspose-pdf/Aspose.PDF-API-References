---
title: "TextEditOptions"
linktitle: "TextEditOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキスト編集操作のオプションを記述します。"
type: docs
weight: 4970
url: /ja/java/com.aspose.pdf/texteditoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextEditOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextEditOptions

```
public final class TextEditOptions extends TextOptions
```

テキスト編集操作のオプションを記述します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextEditOptions](#TextEditOptions--) | デフォルトオプションで {@code TextEditOptions} オブジェクトの新しいインスタンスを初期化します。NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-boolean-) | / * / * 指定されたテキスト再配置モード用に {@code TextEditOptions} オブジェクトの新しいインスタンスを初期化します。 / * / * |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-) | デフォルトオプションで {@code TextEditOptions} オブジェクトの新しいインスタンスを初期化します。NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | デフォルトオプションで {@code TextEditOptions} オブジェクトの新しいインスタンスを初期化します。NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | デフォルトオプションで {@code TextEditOptions} オブジェクトの新しいインスタンスを初期化します。NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-) | デフォルトオプションで {@code TextEditOptions} オブジェクトの新しいインスタンスを初期化します。NoCharacterAction.UseStandardFont LanguageTransformation.Default |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAllowLanguageTransformation](#getAllowLanguageTransformation--) | テキストの追加または編集時に言語変換の使用を許可する値を取得します。true - 必要に応じて言語変換が適用されます（デフォルト値）。false - 言語変換は適用されません。 |
| [getClippingPathsProcessing](#getClippingPathsProcessing--) | 編集されたテキストのクリッピングパス処理モードを取得します。 |
| [getFontReplaceBehavior](#getFontReplaceBehavior--) | フォント置換シナリオの動作を定義するモードを取得します。 |
| [getLanguageTransformationBehavior](#getLanguageTransformationBehavior--) | 言語変換シナリオの動作を定義するモードを取得します。 |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | フォントが要求された文字を含まない場合の動作を定義するモードを取得します。 |
| [getReplacementFont](#getReplacementFont--) | ユーザーフォントが必要な文字を含まない場合に置換に使用されるフォントを取得または設定します。 |
| [getToAttemptGetUnderlineFromSource](#getToAttemptGetUnderlineFromSource--) | <p> ソース文書のページ上でテキストの下線検索を許可する値を取得または設定します。 <p> (Obsolete) 代わりに TextSearchOptions.SearchForTextRelatedGraphics を使用してください。 </p> |
| [setAllowLanguageTransformation](#setAllowLanguageTransformation-boolean-) | テキストの追加または編集時に言語変換の使用を許可する値を設定します。true - 必要に応じて言語変換が適用されます（デフォルト値）。false - 言語変換は適用されません。 |
| [setClippingPathsProcessing](#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-) | 編集されたテキストのクリッピングパス処理モードを取得します。 |
| [setFontReplaceBehavior](#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-) | フォント置換シナリオの動作を定義するモードを設定します。 |
| [setLanguageTransformationBehavior](#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | 言語変換シナリオの動作を定義するモードを設定します。 |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | フォントが要求された文字を含まない場合の動作を定義するモードを設定します。 |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | ユーザーフォントが必要な文字を含まない場合に置換に使用されるフォントを取得または設定します。 |
| [setToAttemptGetUnderlineFromSource](#setToAttemptGetUnderlineFromSource-boolean-) | <p> ソース文書のページ上でテキストの下線検索を許可する値を取得または設定します。 <p> (Obsolete) 代わりに TextSearchOptions.SearchForTextRelatedGraphics を使用してください。 </p> |

### TextEditOptions {#TextEditOptions--}
```
public TextEditOptions()
```

デフォルトオプションで {@code TextEditOptions} オブジェクトの新しいインスタンスを初期化します。NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```

/ * / * 指定されたテキスト再配置モード用に {@code TextEditOptions} オブジェクトの新しいインスタンスを初期化します。 / * / *

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| allowLanguageTransformation |  |  |

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-}
デフォルトオプションで {@code TextEditOptions} オブジェクトの新しいインスタンスを初期化します。NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
デフォルトオプションで {@code TextEditOptions} オブジェクトの新しいインスタンスを初期化します。NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
デフォルトオプションで {@code TextEditOptions} オブジェクトの新しいインスタンスを初期化します。NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-}
デフォルトオプションで {@code TextEditOptions} オブジェクトの新しいインスタンスを初期化します。NoCharacterAction.UseStandardFont LanguageTransformation.Default

### getAllowLanguageTransformation {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```

テキストの追加または編集時に言語変換の使用を許可する値を取得します。true - 必要に応じて言語変換が適用されます（デフォルト値）。false - 言語変換は適用されません。

**Returns:**
ブール値

### getClippingPathsProcessing {#getClippingPathsProcessing--}
```
public final TextEditOptions.ClippingPathsProcessingMode getClippingPathsProcessing()
```

編集されたテキストのクリッピングパス処理モードを取得します。

**Returns:**
ClippingPathsProcessingMode 要素

### getFontReplaceBehavior {#getFontReplaceBehavior--}
```
public TextEditOptions.FontReplace getFontReplaceBehavior()
```

フォント置換シナリオの動作を定義するモードを取得します。

**Returns:**
FontReplace 値 @see FontReplace

### getLanguageTransformationBehavior {#getLanguageTransformationBehavior--}
```
public TextEditOptions.LanguageTransformation getLanguageTransformationBehavior()
```

言語変換シナリオの動作を定義するモードを取得します。

**Returns:**
LanguageTransformation 値 @see LanguageTransformation

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public TextEditOptions.NoCharacterAction getNoCharacterBehavior()
```

フォントが要求された文字を含まない場合の動作を定義するモードを取得します。

**Returns:**
NoCharacterAction 値 @see NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

ユーザーフォントが必要な文字を含まない場合に置換に使用されるフォントを取得または設定します。

**Returns:**
フォント インスタンス

### getToAttemptGetUnderlineFromSource {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```

<p> ソース文書のページ上でテキストの下線検索を許可する値を取得または設定します。 <p> (Obsolete) 代わりに TextSearchOptions.SearchForTextRelatedGraphics を使用してください。 </p>

**Returns:**
ブール値

### setAllowLanguageTransformation {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```

テキストの追加または編集時に言語変換の使用を許可する値を設定します。true - 必要に応じて言語変換が適用されます（デフォルト値）。false - 言語変換は適用されません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setClippingPathsProcessing {#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-}
編集されたテキストのクリッピングパス処理モードを取得します。

### setFontReplaceBehavior {#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-}
フォント置換シナリオの動作を定義するモードを設定します。

### setLanguageTransformationBehavior {#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
言語変換シナリオの動作を定義するモードを設定します。

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
フォントが要求された文字を含まない場合の動作を定義するモードを設定します。

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
ユーザーフォントが必要な文字を含まない場合に置換に使用されるフォントを取得または設定します。

### setToAttemptGetUnderlineFromSource {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```

<p> ソース文書のページ上でテキストの下線検索を許可する値を取得または設定します。 <p> (Obsolete) 代わりに TextSearchOptions.SearchForTextRelatedGraphics を使用してください。 </p>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
