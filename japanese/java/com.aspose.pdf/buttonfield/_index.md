---
title: "ButtonField"
linktitle: "ButtonField"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "クラスはプッシュボタンフィールドを表します。"
type: docs
weight: 440
url: /ja/java/com.aspose.pdf/buttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Field, com.aspose.pdf.ButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class ButtonField extends Field
```

クラスはプッシュボタンフィールドを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ButtonField](#ButtonField--) | Generator 用のボタンフィールドコンストラクタです。 |
| [ButtonField](#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Generator 用のボタンフィールドコンストラクタです。 |
| [ButtonField](#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Generator 用のボタンフィールドコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addImage](#addImage-java.awt.image.BufferedImage-) | フィールドリソースに画像を追加し、描画します。 |
| [addImage](#addImage-java.awt.image.BufferedImage-boolean-) | 画像をフィールドリソースに追加し、描画します。 |
| [getAlternateCaption](#getAlternateCaption--) | アクティブ領域内でマウスボタンが押されたときに表示されるボタンの代替キャプションを取得します。 |
| [getAlternateIcon](#getAlternateIcon--) | アクティブ領域内でマウスボタンが押されたときに表示される代替アイコンを取得します。 |
| [getIconFit](#getIconFit--) | ウィジェット注釈のアイコンが注釈矩形内でどのように表示されるかを指定するアイコンフィットオブジェクトを取得します。 |
| [getICPosition](#getICPosition--) | アイコンキャプションの位置を取得します。 |
| [getNormalCaption](#getNormalCaption--) | 標準キャプションを取得します。 |
| [getNormalIcon](#getNormalIcon--) | ユーザーと対話していないときに表示されるボタンの標準アイコンを取得します。 |
| [getRolloverCaption](#getRolloverCaption--) | ユーザーがマウスボタンを押さずにカーソルをアクティブ領域に入れたときに表示されるボタンのロールオーバーキャプションを取得します。 |
| [getRolloverIcon](#getRolloverIcon--) | ユーザーがマウスボタンを押さずにカーソルをアクティブ領域に入れたときに表示されるボタンのロールオーバーアイコンを取得します。 |
| [setAlternateCaption](#setAlternateCaption-java.lang.String-) | アクティブ領域内でマウスボタンが押されたときに表示されるボタンの代替キャプションを設定します。 |
| [setAlternateIcon](#setAlternateIcon-com.aspose.pdf.XForm-) | アクティブ領域内でマウスボタンが押されたときに表示される代替アイコンを設定します。 |
| [setICPosition](#setICPosition-com.aspose.pdf.IconCaptionPosition-) | アイコンキャプションの位置を設定します。 |
| [setNormalCaption](#setNormalCaption-java.lang.String-) | 標準キャプションを設定します。 |
| [setNormalIcon](#setNormalIcon-com.aspose.pdf.XForm-) | ユーザーと対話していないときに表示されるボタンの標準アイコンを設定します。 |
| [setRolloverCaption](#setRolloverCaption-java.lang.String-) | ユーザーがマウスボタンを押さずにカーソルをアクティブ領域に入れたときに表示されるボタンのロールオーバーキャプションを設定します。 |
| [setRolloverIcon](#setRolloverIcon-com.aspose.pdf.XForm-) | ユーザーがマウスボタンを押さずにカーソルをアクティブ領域に入れたときに表示されるボタンのロールオーバーアイコンを設定します。 |

### ButtonField {#ButtonField--}
```
public ButtonField()
```

Generator 用のボタンフィールドコンストラクタです。

### ButtonField {#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Generator 用のボタンフィールドコンストラクタです。

### ButtonField {#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Generator 用のボタンフィールドコンストラクタです。

### addImage {#addImage-java.awt.image.BufferedImage-}
フィールドリソースに画像を追加し、描画します。

### addImage {#addImage-java.awt.image.BufferedImage-boolean-}
画像をフィールドリソースに追加し、描画します。

### getAlternateCaption {#getAlternateCaption--}
```
public String getAlternateCaption()
```

アクティブ領域内でマウスボタンが押されたときに表示されるボタンの代替キャプションを取得します。

**Returns:**
文字列値

### getAlternateIcon {#getAlternateIcon--}
```
public XForm getAlternateIcon()
```

アクティブ領域内でマウスボタンが押されたときに表示される代替アイコンを取得します。

**Returns:**
XForm オブジェクト

### getIconFit {#getIconFit--}
```
public IconFit getIconFit()
```

ウィジェット注釈のアイコンが注釈矩形内でどのように表示されるかを指定するアイコンフィットオブジェクトを取得します。

**Returns:**
IconFit オブジェクト

### getICPosition {#getICPosition--}
```
public IconCaptionPosition getICPosition()
```

アイコンキャプションの位置を取得します。

**Returns:**
アイコンキャプションの位置。 @see IconCaptionPosition

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

標準キャプションを取得します。

**Returns:**
文字列値

### getNormalIcon {#getNormalIcon--}
```
public XForm getNormalIcon()
```

ユーザーと対話していないときに表示されるボタンの標準アイコンを取得します。

**Returns:**
XForm オブジェクト

### getRolloverCaption {#getRolloverCaption--}
```
public String getRolloverCaption()
```

ユーザーがマウスボタンを押さずにカーソルをアクティブ領域に入れたときに表示されるボタンのロールオーバーキャプションを取得します。

**Returns:**
文字列値

### getRolloverIcon {#getRolloverIcon--}
```
public XForm getRolloverIcon()
```

ユーザーがマウスボタンを押さずにカーソルをアクティブ領域に入れたときに表示されるボタンのロールオーバーアイコンを取得します。

**Returns:**
XForm オブジェクト

### setAlternateCaption {#setAlternateCaption-java.lang.String-}
アクティブ領域内でマウスボタンが押されたときに表示されるボタンの代替キャプションを設定します。

### setAlternateIcon {#setAlternateIcon-com.aspose.pdf.XForm-}
アクティブ領域内でマウスボタンが押されたときに表示される代替アイコンを設定します。

### setICPosition {#setICPosition-com.aspose.pdf.IconCaptionPosition-}
アイコンキャプションの位置を設定します。

### setNormalCaption {#setNormalCaption-java.lang.String-}
標準キャプションを設定します。

### setNormalIcon {#setNormalIcon-com.aspose.pdf.XForm-}
ユーザーと対話していないときに表示されるボタンの標準アイコンを設定します。

### setRolloverCaption {#setRolloverCaption-java.lang.String-}
ユーザーがマウスボタンを押さずにカーソルをアクティブ領域に入れたときに表示されるボタンのロールオーバーキャプションを設定します。

### setRolloverIcon {#setRolloverIcon-com.aspose.pdf.XForm-}
ユーザーがマウスボタンを押さずにカーソルをアクティブ領域に入れたときに表示されるボタンのロールオーバーアイコンを設定します。
