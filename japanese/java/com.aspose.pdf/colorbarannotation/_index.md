---
title: "ColorBarAnnotation"
linktitle: "ColorBarAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ColorBarAnnotation 注釈を表すクラス。プロパティ Color は無視され、代わりに ColorsOfCMYK の色が使用されます。作成時に、幅と高さの比率が向きを決定します。"
type: docs
weight: 680
url: /ja/java/com.aspose.pdf/colorbarannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.ColorBarAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class ColorBarAnnotation extends PrinterMarkAnnotation
```

ColorBarAnnotation アノテーションを表すクラスです。プロパティ Color は無視され、代わりに ColorsOfCMYK カラーが使用されます。作成時に幅と高さの比率でアノテーションの向き（水平または垂直）が決定されます。次に、アノテーション矩形が TrimBox の外にあるか確認し、外にない場合は、アノテーションの向きを考慮して最も近い TrimBox 外側の位置へシフトされます。幅（高さ）を縮小してアノテーションを TrimBox の外に収めることが可能です。レイアウト用の空間がない場合、幅/高さを 0 に設定できます（この場合、アノテーションはページに存在しますが表示されません）。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 指定されたページに新しい ColorBar 注釈を作成します。デフォルトは ColorsOfCMYK.Black です。 |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-) | 指定されたページに新しい ColorBar 注釈を作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 注釈を処理するためのビジタオブジェクトを受け取ります。 |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | マトリックス変換に従い、パラメータと外観を更新し、必要に応じて TrimBox の外へ移動します。 |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getColorOfCMYK](#getColorOfCMYK--) | 注釈が描画される色（シアン、マゼンタ、イエロー、ブラックのいずれか）を取得または設定します。 |
| [setColorOfCMYK](#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-) | 注釈が描画される色（シアン、マゼンタ、イエロー、ブラックのいずれか）を取得または設定します。 |

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
指定されたページに新しい ColorBar 注釈を作成します。デフォルトは ColorsOfCMYK.Black です。

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-}
指定されたページに新しい ColorBar 注釈を作成します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
注釈を処理するためのビジタオブジェクトを受け取ります。

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
マトリックス変換に従い、パラメータと外観を更新し、必要に応じて TrimBox の外へ移動します。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
int 値です。

### getColorOfCMYK {#getColorOfCMYK--}
```
public final ColorsOfCMYK getColorOfCMYK()
```

注釈が描画される色（シアン、マゼンタ、イエロー、ブラックのいずれか）を取得または設定します。

**Returns:**
ColorsOfCMYK 要素

### setColorOfCMYK {#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-}
注釈が描画される色（シアン、マゼンタ、イエロー、ブラックのいずれか）を取得または設定します。
