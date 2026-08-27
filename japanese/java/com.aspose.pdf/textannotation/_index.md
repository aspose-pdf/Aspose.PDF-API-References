---
title: "TextAnnotation"
linktitle: "TextAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントのポイントに添付された \"sticky note\" テキスト注釈を表します。"
type: docs
weight: 4920
url: /ja/java/com.aspose.pdf/textannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class TextAnnotation extends MarkupAnnotation
```

PDF ドキュメントのポイントに添付された「付箋」テキスト注釈を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextAnnotation](#TextAnnotation--) | TextAnnotation インスタンスを作成します |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.IDocument-) | TextAnnotation インスタンスを作成します |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | TextAnnotation インスタンスを作成します |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 注釈を処理するためのビジタオブジェクトを受け取ります。 |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | 基底クラスの定義を空の本体でオーバーライドします。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getIcon](#getIcon--) | 注釈の表示に使用されるアイコンを取得します。 |
| [getOpen](#getOpen--) | 注釈が最初に開いた状態で表示されるかどうかを指定するフラグを取得します。 |
| [setIcon](#setIcon-int-) | 注釈の表示に使用されるアイコンを設定します。 |
| [setOpen](#setOpen-boolean-) | 注釈が最初に開いた状態で表示されるかどうかを指定するフラグを設定します。 |

### TextAnnotation {#TextAnnotation--}
```
public TextAnnotation()
```

TextAnnotation インスタンスを作成します

### TextAnnotation {#TextAnnotation-com.aspose.pdf.IDocument-}
TextAnnotation インスタンスを作成します

### TextAnnotation {#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
TextAnnotation インスタンスを作成します

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
注釈を処理するためのビジタオブジェクトを受け取ります。

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
基底クラスの定義を空の本体でオーバーライドします。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
AnnotationType の値 @see AnnotationState

### getIcon {#getIcon--}
```
public int getIcon()
```

注釈の表示に使用されるアイコンを取得します。

**Returns:**
TextIcon の値 @see TextIcon

### getOpen {#getOpen--}
```
public boolean getOpen()
```

注釈が最初に開いた状態で表示されるかどうかを指定するフラグを取得します。

**Returns:**
ブール値

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

注釈の表示に使用されるアイコンを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | TextIcon の値 @see TextIcon |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

注釈が最初に開いた状態で表示されるかどうかを指定するフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
