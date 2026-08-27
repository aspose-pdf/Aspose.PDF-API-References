---
title: "FreeTextAnnotation"
linktitle: "FreeTextAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページ上に直接テキストを表示するフリーテキスト注釈を表します。通常のテキスト注釈とは異なり、フリーテキスト注釈には開閉状態がなく、代わりに。"
type: docs
weight: 1790
url: /ja/java/com.aspose.pdf/freetextannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FreeTextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FreeTextAnnotation extends MarkupAnnotation
```

ページ上に直接テキストを表示するフリーテキスト注釈を表します。通常のテキスト注釈とは異なり、フリーテキスト注釈には開閉状態がなく、ポップアップウィンドウで表示される代わりにテキストは常に表示されます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-) | Generator と共に使用するコンストラクタです。 |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | 指定されたページに新しい FreeText 注釈を作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 注釈を処理するためのビジタオブジェクトを受け取ります。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getCallout](#getCallout--) | 呼び出し線を指定するポイントの配列です。 |
| [getDefaultAppearance](#getDefaultAppearance--) | テキストの書式設定に使用されるデフォルトの外観文字列を取得します。 |
| [getDefaultAppearanceObject](#getDefaultAppearanceObject--) | FreeText 注釈のデフォルト外観を表すオブジェクトです。 |
| [getDefaultStyle](#getDefaultStyle--) | デフォルトのスタイル文字列を取得します。 |
| [getEndingStyle](#getEndingStyle--) | 終点のラインエンドスタイルを取得します。 |
| [getIntent](#getIntent--) | フリーテキスト注釈の意図を取得します。 |
| [getJustification](#getJustification--) | 注釈テキストの表示に使用される配置（左右揃え）の形式を指定するコードを取得します。 |
| [getRotate](#getRotate--) | 注釈の回転角度です。 |
| [getStartingStyle](#getStartingStyle--) | 終点のラインエンドスタイルを取得または設定します。このプロパティは廃止予定です。代わりに EndingStyle を使用してください。 |
| [getTextRectangle](#getTextRectangle--) | 注釈の Rect エントリと、その矩形内に含まれる矩形との数値的な差異を示す矩形です。内部の矩形は注釈テキストが表示される領域です。 |
| [getTextStyle](#getTextStyle--) | 外観のテキストのスタイルを取得または設定します。テキストスタイルが変更されると、テキストの外観が更新されます。 |
| [isValidXml](#isValidXml-java.lang.String-) |  |
| [setCallout](#setCallout-com.aspose.pdf.Point:A-) | 呼び出し線を指定するポイントの配列です。 |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | テキストの書式設定に使用されるデフォルトの外観文字列を設定します。 |
| [setDefaultStyle](#setDefaultStyle-java.lang.String-) | デフォルトのスタイル文字列を設定します。 |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | ラインエンドポイントのラインエンドスタイルを設定します。 |
| [setIntent](#setIntent-com.aspose.pdf.FreeTextIntent-) | フリーテキスト注釈の意図を設定します。 |
| [setJustification](#setJustification-com.aspose.pdf.Justification-) | 注釈テキストの表示に使用されるクアディング（配置）の形式を指定するコードを設定します。 |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | 注釈の回転角度です。 |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | 終点のラインエンドスタイルを取得または設定します。このプロパティは廃止予定です。代わりに EndingStyle を使用してください。 |
| [setTextRectangle](#setTextRectangle-com.aspose.pdf.Rectangle-) | 注釈の Rect エントリと、その矩形内に含まれる矩形との数値的な差異を示す矩形です。内部の矩形は注釈テキストが表示される領域です。 |
| [setTextStyle](#setTextStyle-int-int-int-) | パラメータ textStyle によって決定される書式を、fromInd インデックスから toInd インデックスまでのテキストフラグメントに設定します。 |
| [setTextStyle](#setTextStyle-int-java.lang.String-double-java.awt.Color-) | パラメータ textStyle によって決定される書式を、すべての注釈テキストに設定します。 |
| [setTextStyle](#setTextStyle-com.aspose.pdf.TextStyle-) | 外観のテキストのスタイルを設定します。テキストスタイルが変更されると、テキストの外観が更新されます。 |
| [updateAppearance](#updateAppearance--) | テキストが変更/移動された後、外観を更新します。 |

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-}
Generator と共に使用するコンストラクタです。

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-}
指定されたページに新しい FreeText 注釈を作成します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
注釈を処理するためのビジタオブジェクトを受け取ります。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
int 値です。

### getCallout {#getCallout--}
```
public final Point [] getCallout()
```

呼び出し線を指定するポイントの配列です。

**Returns:**
Point の配列

### getDefaultAppearance {#getDefaultAppearance--}
```
public String getDefaultAppearance()
```

テキストの書式設定に使用されるデフォルトの外観文字列を取得します。

**Returns:**
文字列値

### getDefaultAppearanceObject {#getDefaultAppearanceObject--}
```
public final DefaultAppearance getDefaultAppearanceObject()
```

FreeText 注釈のデフォルト外観を表すオブジェクトです。

**Returns:**
DefaultAppearance オブジェクト

### getDefaultStyle {#getDefaultStyle--}
```
public String getDefaultStyle()
```

デフォルトのスタイル文字列を取得します。

**Returns:**
文字列値

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

終点のラインエンドスタイルを取得します。

**Returns:**
LineEnding の値 @see LineEnding

### getIntent {#getIntent--}
```
public FreeTextIntent getIntent()
```

フリーテキスト注釈の意図を取得します。

**Returns:**
int の値 @see FreeTextIntent

### getJustification {#getJustification--}
```
public Justification getJustification()
```

注釈テキストの表示に使用される配置（左右揃え）の形式を指定するコードを取得します。

**Returns:**
int の値 @see Justification

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

注釈の回転角度です。

**Returns:**
Rotation 要素 @see Rotation

### getStartingStyle {#getStartingStyle--}
```
public final LineEnding getStartingStyle()
```

終点のラインエンドスタイルを取得または設定します。このプロパティは廃止予定です。代わりに EndingStyle を使用してください。

**Returns:**
LineEnding 要素

### getTextRectangle {#getTextRectangle--}
```
public final Rectangle getTextRectangle()
```

注釈の Rect エントリと、その矩形内に含まれる矩形との数値的な差異を示す矩形です。内部の矩形は注釈テキストが表示される領域です。

**Returns:**
矩形インスタンス

### getTextStyle {#getTextStyle--}
```
public TextStyle getTextStyle()
```

外観のテキストのスタイルを取得または設定します。テキストスタイルが変更されると、テキストの外観が更新されます。

**Returns:**
TextStyle の値

### isValidXml {#isValidXml-java.lang.String-}


### setCallout {#setCallout-com.aspose.pdf.Point:A-}
呼び出し線を指定するポイントの配列です。

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
テキストの書式設定に使用されるデフォルトの外観文字列を設定します。

### setDefaultStyle {#setDefaultStyle-java.lang.String-}
デフォルトのスタイル文字列を設定します。

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
ラインエンドポイントのラインエンドスタイルを設定します。

### setIntent {#setIntent-com.aspose.pdf.FreeTextIntent-}
フリーテキスト注釈の意図を設定します。

### setJustification {#setJustification-com.aspose.pdf.Justification-}
注釈テキストの表示に使用されるクアディング（配置）の形式を指定するコードを設定します。

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
注釈の回転角度です。

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
終点のラインエンドスタイルを取得または設定します。このプロパティは廃止予定です。代わりに EndingStyle を使用してください。

### setTextRectangle {#setTextRectangle-com.aspose.pdf.Rectangle-}
注釈の Rect エントリと、その矩形内に含まれる矩形との数値的な差異を示す矩形です。内部の矩形は注釈テキストが表示される領域です。

### setTextStyle {#setTextStyle-int-int-int-}
```
public final void setTextStyle(int fromInd, int toInd, int textStyles)
```

パラメータ textStyle によって決定される書式を、fromInd インデックスから toInd インデックスまでのテキストフラグメントに設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fromInd |  | テキストフラグメントの開始インデックス（0 から）。 |
| toInd |  | テキストフラグメントの終了インデックス（0 から数えて、こちらは含まれません）。 |
| textStyles |  | テキストフラグメントに適用されるスタイル。 |

### setTextStyle {#setTextStyle-int-java.lang.String-double-java.awt.Color-}
パラメータ textStyle によって決定される書式を、すべての注釈テキストに設定します。

### setTextStyle {#setTextStyle-com.aspose.pdf.TextStyle-}
外観のテキストのスタイルを設定します。テキストスタイルが変更されると、テキストの外観が更新されます。

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

テキストが変更/移動された後、外観を更新します。
