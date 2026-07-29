---
title: "WatermarkAnnotation"
linktitle: "WatermarkAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "クラスは Watermark アノテーションオブジェクトを記述します。"
type: docs
weight: 5510
url: /ja/java/com.aspose.pdf/watermarkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WatermarkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WatermarkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.WatermarkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class WatermarkAnnotation extends Annotation
```

クラスは Watermark アノテーションオブジェクトを記述します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [WatermarkAnnotation](#WatermarkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Watermark アノテーションクラスのコンストラクタ。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | アノテーションに対してビジターを適用します。 |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | 基底クラスの定義を空の本体でオーバーライドします。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getFixedPrint](#getFixedPrint--) | 透かし注釈の固定印刷オブジェクトです。 |
| [getOpacity](#getOpacity--) | 注釈の不透明度を取得または設定します。 |
| [setOpacity](#setOpacity-double-) | 注釈の不透明度を取得または設定します。 |
| [setText](#setText-com.aspose.pdf.facades.FormattedText-) | 注釈のテキストを設定します。 |
| [setTextAndState](#setTextAndState-java.lang.String:A-com.aspose.pdf.TextState-) | 注釈のテキストを設定します。 |

### WatermarkAnnotation {#WatermarkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Watermark アノテーションクラスのコンストラクタ。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
アノテーションに対してビジターを適用します。

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
基底クラスの定義を空の本体でオーバーライドします。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
AnnotationType 要素

### getFixedPrint {#getFixedPrint--}
```
public FixedPrint getFixedPrint()
```

透かし注釈の固定印刷オブジェクトです。

**Returns:**
FixedPrint オブジェクト

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

注釈の不透明度を取得または設定します。

**Returns:**
double 値

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

注釈の不透明度を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setText {#setText-com.aspose.pdf.facades.FormattedText-}
注釈のテキストを設定します。

### setTextAndState {#setTextAndState-java.lang.String:A-com.aspose.pdf.TextState-}
注釈のテキストを設定します。
