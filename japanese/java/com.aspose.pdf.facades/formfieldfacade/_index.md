---
title: "FormFieldFacade"
linktitle: "FormFieldFacade"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "フィールドプロパティを表すクラス。"
type: docs
weight: 220
url: /ja/java/com.aspose.pdf.facades/formfieldfacade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.FormFieldFacade

```
public final class FormFieldFacade extends Object
```

フィールドプロパティを表すクラス。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [ALIGN_BOTTOM](#ALIGN_BOTTOM) | 垂直方向の配置を bottom スタイルとして定義します。 |
| [ALIGN_CENTER](#ALIGN_CENTER) | center スタイルへの aglignment を定義します。 |
| [ALIGN_JUSTIFIED](#ALIGN_JUSTIFIED) | テキストの整列配置スタイルを定義します。 |
| [ALIGN_LEFT](#ALIGN_LEFT) | 左揃えスタイルを定義します。 |
| [ALIGN_MIDDLE](#ALIGN_MIDDLE) | 垂直方向の配置を中央スタイルとして定義します。 |
| [ALIGN_RIGHT](#ALIGN_RIGHT) | 右揃えスタイルを定義します。 |
| [ALIGN_TOP](#ALIGN_TOP) | 垂直方向の配置を上部スタイルとして定義します。 |
| [ALIGN_UNDEFINED](#ALIGN_UNDEFINED) | 未定義の配置スタイルです。 |
| [BORDER_STYLE_BEVELED](#BORDER_STYLE_BEVELED) | ベベル加工された枠線スタイルを定義します。 |
| [BORDER_STYLE_DASHED](#BORDER_STYLE_DASHED) | 破線の枠線スタイルを定義します。 |
| [BORDER_STYLE_INSET](#BORDER_STYLE_INSET) | インセットされた枠線スタイルを定義します。 |
| [BORDER_STYLE_SOLID](#BORDER_STYLE_SOLID) | 実線の枠線スタイルを定義します。 |
| [BORDER_STYLE_UNDEFINED](#BORDER_STYLE_UNDEFINED) | 未定義の枠線スタイルです。 |
| [BORDER_STYLE_UNDERLINE](#BORDER_STYLE_UNDERLINE) | 下線付き枠線スタイルを定義します。 |
| [BORDER_WIDTH_MEDIUM](#BORDER_WIDTH_MEDIUM) | 中程度の枠線幅を定義します。 |
| [BORDER_WIDTH_THICK](#BORDER_WIDTH_THICK) | 太い枠線幅を定義します。 |
| [BORDER_WIDTH_THIN](#BORDER_WIDTH_THIN) | 細い枠線幅を定義します。 |
| [BORDER_WIDTH_UNDEFINED](#BORDER_WIDTH_UNDEFINED) | 未定義の枠線幅です。 |
| [BORDER_WIDTH_UNDIFIED](#BORDER_WIDTH_UNDIFIED) | 未定義の枠線幅です。 |
| [CHECK_BOX_STYLE_CHECK](#CHECK_BOX_STYLE_CHECK) | チェックボックスフィールドがチェックされたときの形状を定義します。 |
| [CHECK_BOX_STYLE_CIRCLE](#CHECK_BOX_STYLE_CIRCLE) | 円形チェックボックススタイルを定義します。 |
| [CHECK_BOX_STYLE_CROSS](#CHECK_BOX_STYLE_CROSS) | 十字チェックボックススタイルを定義します。 |
| [CHECK_BOX_STYLE_DIAMOND](#CHECK_BOX_STYLE_DIAMOND) | ダイヤモンド形チェックボックススタイルを定義します。 |
| [CHECK_BOX_STYLE_SQUARE](#CHECK_BOX_STYLE_SQUARE) | 四角形チェックボックススタイルを定義します。 |
| [CHECK_BOX_STYLE_STAR](#CHECK_BOX_STYLE_STAR) | 星形チェックボックススタイルを定義します。 |
| [CHECK_BOX_STYLE_UNDEFINED](#CHECK_BOX_STYLE_UNDEFINED) | 未定義のチェックボックススタイルを定義します。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FormFieldFacade](#FormFieldFacade--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAlignment](#getAlignment--) | フィールドテキストの配置を取得します。デフォルトは左揃えです。 |
| [getBackgroudColor](#getBackgroudColor--) | 廃止されたプロパティです。BackgroundColor を使用してください。このメソッドは非推奨です。 |
| [getBackgroundColor](#getBackgroundColor--) | フィールドの背景色を取得します。デフォルトは白です。 |
| [getBorderColor](#getBorderColor--) | フィールドの枠線の色を取得します。 |
| [getBorderStyle](#getBorderStyle--) | フィールドの枠線のスタイルを取得します。 |
| [getBorderWidth](#getBorderWidth--) | フィールドの枠線の幅を取得します。 |
| [getBox](#getBox--) | フィールドの位置を保持する矩形オブジェクトを取得します。 |
| [getButtonStyle](#getButtonStyle--) | FormFieldFacade.CheckBoxStyle*で定義されたチェックボックスまたはラジオボックスフィールドのスタイルを取得します。 |
| [getCaption](#getCaption--) | フォームフィールドの通常のキャプションを取得します。 |
| [getCustomFont](#getCustomFont--) | 標準の14フォント以外の非標準フォントの場合、そのフォント名を取得します。 |
| [getExportItems](#getExportItems--) | リスト/コンボ/ラジオボックスを追加するためのオプションを取得します |
| [getFont](#getFont--) | フィールドテキストのフォントスタイルタイプを取得します。 |
| [getFontSize](#getFontSize--) | フィールドテキストのサイズを取得します。 |
| [getItems](#getItems--) | コンボボックス/リスト/ラジオボックスフィールドの各オプションを表す文字列の配列を取得します。 |
| [getPageNumber](#getPageNumber--) | フィールドが配置されているページ番号を保持する整数値を取得します。 |
| [getPosition](#getPosition--) | フィールドの位置を保持する矩形オブジェクトを取得します。 |
| [getRotation](#getRotation--) | フィールドテキストの回転を取得します。 |
| [getTextColor](#getTextColor--) | フィールドテキストの色を取得します。 |
| [getTextEncoding](#getTextEncoding--) | フィールドテキストのテキストエンコーディングタイプを取得します。 |
| [reset](#reset--) | すべての視覚属性を空の値にリセットします。 |
| [setAlignment](#setAlignment-int-) | フィールドテキストの配置を設定します。デフォルトは左揃えです。 |
| [setBackgroudColor](#setBackgroudColor-java.awt.Color-) | 非推奨です。 |
| [setBackgroundColor](#setBackgroundColor-java.awt.Color-) | フィールドの背景色を設定します。デフォルトは白です。 |
| [setBorderColor](#setBorderColor-java.awt.Color-) | フィールドの枠線の色を設定します。 |
| [setBorderStyle](#setBorderStyle-int-) | フィールドの枠線のスタイルを設定します。 |
| [setBorderWidth](#setBorderWidth-float-) | フィールドの枠線の幅を設定します。 |
| [setBox](#setBox-java.awt.Rectangle-) | フィールドの位置を保持する矩形オブジェクトを設定します。 |
| [setButtonStyle](#setButtonStyle-int-) | FormFieldFacade.CheckBoxStyle*で定義されたチェックボックスまたはラジオボックスフィールドのスタイルを設定します。 |
| [setCaption](#setCaption-java.lang.String-) | フォームフィールドの通常のキャプションを設定します。 |
| [setCustomFont](#setCustomFont-java.lang.String-) | 標準の14フォント以外の非標準フォントの場合、そのフォント名を設定します。 |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | リスト/コンボ/ラジオボックスを追加するためのオプションを設定します |
| [setFont](#setFont-com.aspose.pdf.facades.FontStyle-) | フィールドテキストのフォントスタイルタイプを設定します。 |
| [setFontSize](#setFontSize-float-) | フィールドテキストのサイズを設定します。 |
| [setItems](#setItems-java.lang.String:A-) | コンボボックス/リスト/ラジオボックスフィールドのオプションを表す文字列の配列を設定します。 |
| [setPageNumber](#setPageNumber-int-) | フィールドが配置されているページ番号を保持する整数値を設定します。 |
| [setPosition](#setPosition-float:A-) | フィールドの位置を保持する矩形オブジェクトを設定します。 |
| [setRotation](#setRotation-int-) | フィールドテキストの回転を設定します。 |
| [setTextColor](#setTextColor-java.awt.Color-) | フィールドテキストの色を設定します。 |
| [setTextEncoding](#setTextEncoding-int-) | フィールドテキストのテキストエンコーディングタイプ {@link EncodingType} を設定します。 |

### ALIGN_BOTTOM {#ALIGN_BOTTOM}
```
public static final int ALIGN_BOTTOM
```

垂直方向の配置を bottom スタイルとして定義します。

### ALIGN_CENTER {#ALIGN_CENTER}
```
public static final int ALIGN_CENTER
```

center スタイルへの aglignment を定義します。

### ALIGN_JUSTIFIED {#ALIGN_JUSTIFIED}
```
public static final int ALIGN_JUSTIFIED
```

テキストの整列配置スタイルを定義します。

### ALIGN_LEFT {#ALIGN_LEFT}
```
public static final int ALIGN_LEFT
```

左揃えスタイルを定義します。

### ALIGN_MIDDLE {#ALIGN_MIDDLE}
```
public static final int ALIGN_MIDDLE
```

垂直方向の配置を中央スタイルとして定義します。

### ALIGN_RIGHT {#ALIGN_RIGHT}
```
public static final int ALIGN_RIGHT
```

右揃えスタイルを定義します。

### ALIGN_TOP {#ALIGN_TOP}
```
public static final int ALIGN_TOP
```

垂直方向の配置を上部スタイルとして定義します。

### ALIGN_UNDEFINED {#ALIGN_UNDEFINED}
```
public static final int ALIGN_UNDEFINED
```

未定義の配置スタイルです。

### BORDER_STYLE_BEVELED {#BORDER_STYLE_BEVELED}
```
public static final int BORDER_STYLE_BEVELED
```

ベベル加工された枠線スタイルを定義します。

### BORDER_STYLE_DASHED {#BORDER_STYLE_DASHED}
```
public static final int BORDER_STYLE_DASHED
```

破線の枠線スタイルを定義します。

### BORDER_STYLE_INSET {#BORDER_STYLE_INSET}
```
public static final int BORDER_STYLE_INSET
```

インセットされた枠線スタイルを定義します。

### BORDER_STYLE_SOLID {#BORDER_STYLE_SOLID}
```
public static final int BORDER_STYLE_SOLID
```

実線の枠線スタイルを定義します。

### BORDER_STYLE_UNDEFINED {#BORDER_STYLE_UNDEFINED}
```
public static final int BORDER_STYLE_UNDEFINED
```

未定義の枠線スタイルです。

### BORDER_STYLE_UNDERLINE {#BORDER_STYLE_UNDERLINE}
```
public static final int BORDER_STYLE_UNDERLINE
```

下線付き枠線スタイルを定義します。

### BORDER_WIDTH_MEDIUM {#BORDER_WIDTH_MEDIUM}
```
public static final float BORDER_WIDTH_MEDIUM
```

中程度の枠線幅を定義します。

### BORDER_WIDTH_THICK {#BORDER_WIDTH_THICK}
```
public static final float BORDER_WIDTH_THICK
```

太い枠線幅を定義します。

### BORDER_WIDTH_THIN {#BORDER_WIDTH_THIN}
```
public static final float BORDER_WIDTH_THIN
```

細い枠線幅を定義します。

### BORDER_WIDTH_UNDEFINED {#BORDER_WIDTH_UNDEFINED}
```
public static final float BORDER_WIDTH_UNDEFINED
```

未定義の枠線幅です。

### BORDER_WIDTH_UNDIFIED {#BORDER_WIDTH_UNDIFIED}
```
@Deprecated public static final float BORDER_WIDTH_UNDIFIED
```

未定義の枠線幅です。

### CHECK_BOX_STYLE_CHECK {#CHECK_BOX_STYLE_CHECK}
```
public static final int CHECK_BOX_STYLE_CHECK
```

チェックボックスフィールドがチェックされたときの形状を定義します。

### CHECK_BOX_STYLE_CIRCLE {#CHECK_BOX_STYLE_CIRCLE}
```
public static final int CHECK_BOX_STYLE_CIRCLE
```

円形チェックボックススタイルを定義します。

### CHECK_BOX_STYLE_CROSS {#CHECK_BOX_STYLE_CROSS}
```
public static final int CHECK_BOX_STYLE_CROSS
```

十字チェックボックススタイルを定義します。

### CHECK_BOX_STYLE_DIAMOND {#CHECK_BOX_STYLE_DIAMOND}
```
public static final int CHECK_BOX_STYLE_DIAMOND
```

ダイヤモンド形チェックボックススタイルを定義します。

### CHECK_BOX_STYLE_SQUARE {#CHECK_BOX_STYLE_SQUARE}
```
public static final int CHECK_BOX_STYLE_SQUARE
```

四角形チェックボックススタイルを定義します。

### CHECK_BOX_STYLE_STAR {#CHECK_BOX_STYLE_STAR}
```
public static final int CHECK_BOX_STYLE_STAR
```

星形チェックボックススタイルを定義します。

### CHECK_BOX_STYLE_UNDEFINED {#CHECK_BOX_STYLE_UNDEFINED}
```
public static final int CHECK_BOX_STYLE_UNDEFINED
```

未定義のチェックボックススタイルを定義します。

### FormFieldFacade {#FormFieldFacade--}
```
public FormFieldFacade()
```



### getAlignment {#getAlignment--}
```
public int getAlignment()
```

フィールドテキストの配置を取得します。デフォルトは左揃えです。

**Returns:**
int 値です。

### getBackgroudColor {#getBackgroudColor--}
```
@Deprecated public Color getBackgroudColor()
```

廃止されたプロパティです。BackgroundColor を使用してください。このメソッドは非推奨です。

**Returns:**
背景色

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

フィールドの背景色を取得します。デフォルトは白です。

**Returns:**
色要素

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

フィールドの枠線の色を取得します。

**Returns:**
フィールド枠線の色です。

### getBorderStyle {#getBorderStyle--}
```
public int getBorderStyle()
```

フィールドの枠線のスタイルを取得します。

**Returns:**
フィールド枠線のスタイルです。

### getBorderWidth {#getBorderWidth--}
```
public float getBorderWidth()
```

フィールドの枠線の幅を取得します。

**Returns:**
フィールド枠線の幅です。

### getBox {#getBox--}
```
public Rectangle getBox()
```

フィールドの位置を保持する矩形オブジェクトを取得します。

**Returns:**
矩形要素

### getButtonStyle {#getButtonStyle--}
```
public int getButtonStyle()
```

FormFieldFacade.CheckBoxStyle*で定義されたチェックボックスまたはラジオボックスフィールドのスタイルを取得します。

**Returns:**
int 値です。

### getCaption {#getCaption--}
```
public String getCaption()
```

フォームフィールドの通常のキャプションを取得します。

**Returns:**
文字列値

### getCustomFont {#getCustomFont--}
```
public String getCustomFont()
```

標準の14フォント以外の非標準フォントの場合、そのフォント名を取得します。

**Returns:**
文字列値

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

リスト/コンボ/ラジオボックスを追加するためのオプションを取得します

**Returns:**
String 値の配列

### getFont {#getFont--}
```
public FontStyle getFont()
```

フィールドテキストのフォントスタイルタイプを取得します。

**Returns:**
FontStyle 要素 @see FontStyle

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

フィールドテキストのサイズを取得します。

**Returns:**
float 値

### getItems {#getItems--}
```
public String [] getItems()
```

コンボボックス/リスト/ラジオボックスフィールドの各オプションを表す文字列の配列を取得します。

**Returns:**
String 値の配列

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

フィールドが配置されているページ番号を保持する整数値を取得します。

**Returns:**
int 値です。

### getPosition {#getPosition--}
```
public float[] getPosition()
```

フィールドの位置を保持する矩形オブジェクトを取得します。

**Returns:**
float 値の配列

### getRotation {#getRotation--}
```
public int getRotation()
```

フィールドテキストの回転を取得します。

**Returns:**
int 値です。

### getTextColor {#getTextColor--}
```
public Color getTextColor()
```

フィールドテキストの色を取得します。

**Returns:**
色要素

### getTextEncoding {#getTextEncoding--}
```
public int getTextEncoding()
```

フィールドテキストのテキストエンコーディングタイプを取得します。

**Returns:**
EncodingType 要素 @see EncodingType

### reset {#reset--}
```
public void reset()
```

すべての視覚属性を空の値にリセットします。

### setAlignment {#setAlignment-int-}
```
public void setAlignment(int value)
```

フィールドテキストの配置を設定します。デフォルトは左揃えです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setBackgroudColor {#setBackgroudColor-java.awt.Color-}
非推奨です。

### setBackgroundColor {#setBackgroundColor-java.awt.Color-}
フィールドの背景色を設定します。デフォルトは白です。

### setBorderColor {#setBorderColor-java.awt.Color-}
フィールドの枠線の色を設定します。

### setBorderStyle {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```

フィールドの枠線のスタイルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | フィールド枠線のスタイルです。 |

### setBorderWidth {#setBorderWidth-float-}
```
public void setBorderWidth(float value)
```

フィールドの枠線の幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | フィールド枠線の幅です。 |

### setBox {#setBox-java.awt.Rectangle-}
フィールドの位置を保持する矩形オブジェクトを設定します。

### setButtonStyle {#setButtonStyle-int-}
```
public void setButtonStyle(int value)
```

FormFieldFacade.CheckBoxStyle*で定義されたチェックボックスまたはラジオボックスフィールドのスタイルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setCaption {#setCaption-java.lang.String-}
フォームフィールドの通常のキャプションを設定します。

### setCustomFont {#setCustomFont-java.lang.String-}
標準の14フォント以外の非標準フォントの場合、そのフォント名を設定します。

### setExportItems {#setExportItems-java.lang.String:A:A-}
リスト/コンボ/ラジオボックスを追加するためのオプションを設定します

### setFont {#setFont-com.aspose.pdf.facades.FontStyle-}
フィールドテキストのフォントスタイルタイプを設定します。

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

フィールドテキストのサイズを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値 |

### setItems {#setItems-java.lang.String:A-}
コンボボックス/リスト/ラジオボックスフィールドのオプションを表す文字列の配列を設定します。

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

フィールドが配置されているページ番号を保持する整数値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setPosition {#setPosition-float:A-}
```
public void setPosition(float[] value)
```

フィールドの位置を保持する矩形オブジェクトを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | float 値の配列 |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

フィールドテキストの回転を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setTextColor {#setTextColor-java.awt.Color-}
フィールドテキストの色を設定します。

### setTextEncoding {#setTextEncoding-int-}
```
public void setTextEncoding(int value)
```

フィールドテキストのテキストエンコーディングタイプ {@link EncodingType} を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | EncodingType 要素 @see EncodingType |
