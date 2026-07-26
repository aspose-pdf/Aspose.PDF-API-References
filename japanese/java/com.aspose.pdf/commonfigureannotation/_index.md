---
title: "CommonFigureAnnotation"
linktitle: "CommonFigureAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "共通の図形アノテーションを表す抽象クラスです。"
type: docs
weight: 770
url: /ja/java/com.aspose.pdf/commonfigureannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CommonFigureAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CommonFigureAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CommonFigureAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.CommonFigureAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class CommonFigureAnnotation extends MarkupAnnotation
```

共通の図形アノテーションを表す抽象クラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CommonFigureAnnotation](#CommonFigureAnnotation-com.aspose.pdf.IDocument-) | Generator で使用するためのコンストラクタ。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFrame](#getFrame--) | アノテーションの Rect エントリと基になる正方形または円の実際の境界との数値的差異を示す矩形。 |
| [getInteriorColor](#getInteriorColor--) | アノテーションの矩形または楕円を塗りつぶすための内部色。 |
| [setFrame](#setFrame-com.aspose.pdf.Rectangle-) | アノテーションの Rect エントリと基になる正方形または円の実際の境界との数値的差異を示す矩形。 |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | アノテーションの矩形または楕円を塗りつぶすための内部色。 |

### CommonFigureAnnotation {#CommonFigureAnnotation-com.aspose.pdf.IDocument-}
Generator で使用するためのコンストラクタ。

### getFrame {#getFrame--}
```
public Rectangle getFrame()
```

アノテーションの Rect エントリと基になる正方形または円の実際の境界との数値的差異を示す矩形。

**Returns:**
矩形フレーム

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

アノテーションの矩形または楕円を塗りつぶすための内部色。

**Returns:**
アノテーションの矩形または楕円を塗りつぶすための内部色。

### setFrame {#setFrame-com.aspose.pdf.Rectangle-}
アノテーションの Rect エントリと基になる正方形または円の実際の境界との数値的差異を示す矩形。

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
アノテーションの矩形または楕円を塗りつぶすための内部色。
