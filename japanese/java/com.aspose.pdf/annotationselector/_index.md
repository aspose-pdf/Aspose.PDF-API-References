---
title: "AnnotationSelector"
linktitle: "AnnotationSelector"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このクラスは Visitor テンプレートの考え方を使用してアノテーションを選択するために使用されます。"
type: docs
weight: 100
url: /ja/java/com.aspose.pdf/annotationselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationSelector

**All Implemented Interfaces:**
IAnnotationVisitor

```
public final class AnnotationSelector extends Object implements IAnnotationVisitor
```

このクラスは Visitor テンプレートの考え方を使用してアノテーションを選択するために使用されます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [AnnotationSelector](#AnnotationSelector--) | AnnotationSelector クラスの新しいインスタンスを初期化します。 |
| [AnnotationSelector](#AnnotationSelector-com.aspose.pdf.Annotation-) | AnnotationSelector クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSelected](#getSelected--) | 選択されたオブジェクトのリストです。 |
| [visit](#visit-com.aspose.pdf.BleedMarkAnnotation-) | {@link AnnotationSelector} が {@link BleedMarkAnnotation} オブジェクトで初期化されている場合、{@code bleedMark} を選択します。 |
| [visit](#visit-com.aspose.pdf.CaretAnnotation-) | AnnotationSelector が CaretAnnotation オブジェクトで初期化されている場合、キャレット注釈を選択します。 |
| [visit](#visit-com.aspose.pdf.CircleAnnotation-) | AnnotationSelector が CircleAnnotation オブジェクトで初期化されている場合、円形注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.ColorBarAnnotation-) | AnnotationSelector が ColorBar オブジェクトで初期化されている場合、ColorBar 注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | AnnotationSelector が FileAttachmentAnnotation オブジェクトで初期化されている場合、添付注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.FreeTextAnnotation-) | AnnotationSelector が FreeTextAnnotation オブジェクトで初期化されている場合、フリーテキスト注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.HighlightAnnotation-) | AnnotationSelector が FreeTextAnnotation オブジェクトで初期化されている場合、添付注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.InkAnnotation-) | AnnotationSelector が InkAnnotation オブジェクトで初期化されている場合、インク注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.LineAnnotation-) | AnnotationSelector が LineAnnotation オブジェクトで初期化されている場合、線注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.LinkAnnotation-) | AnnotationSelector が LinkAnnotation オブジェクトで初期化されている場合、リンク注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.MovieAnnotation-) | AnnotationSelector が MovieAnnotation オブジェクトで初期化されている場合、ムービー注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.PageInformationAnnotation-) | AnnotationSelector が {@link PageInformationAnnotation} オブジェクトで初期化されている場合、{@code pageInformation} を選択します。 |
| [visit](#visit-com.aspose.pdf.PDF3DAnnotation-) | AnnotationSelector が PDF3DAnnotation オブジェクトで初期化されている場合、PDF3D 注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.PolygonAnnotation-) | AnnotationSelector が PolygonAnnotation オブジェクトで初期化されている場合、多角形注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.PolylineAnnotation-) | AnnotationSelector が PolylineAnnotation オブジェクトで初期化されている場合、ポリライン注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.PopupAnnotation-) | AnnotationSelector が PopupAnnotation オブジェクトで初期化されている場合、ポップアップ注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.RedactionAnnotation-) | AnnotationSelector が RedactAnnotation オブジェクトで初期化されている場合、編集注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.RegistrationMarkAnnotation-) | AnnotationSelector が {@link RegistrationMarkAnnotation} オブジェクトで初期化されている場合、{@code registrationMark} を選択します。 |
| [visit](#visit-com.aspose.pdf.RichMediaAnnotation-) | AnnotationSelector が RichMedia 注釈オブジェクトで初期化されている場合、ムービー注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.ScreenAnnotation-) | AnnotationSelector が ScreenAnnotation オブジェクトで初期化されている場合、スクリーン注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.SquareAnnotation-) | AnnotationSelector が SquareAnnotation オブジェクトで初期化されている場合、正方形注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.SquigglyAnnotation-) | AnnotationSelector が SquigglyAnnotation オブジェクトで初期化されている場合、波線注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.StampAnnotation-) | AnnotationSelector が StampAnnotation オブジェクトで初期化されている場合、スタンプ注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.StrikeOutAnnotation-) | AnnotationSelector が StrikeOutAnnotation オブジェクトで初期化されている場合、取り消し線注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.TextAnnotation-) | AnnotationSelector が TextAnnotation オブジェクトで初期化されている場合、テキスト注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.TrimMarkAnnotation-) | AnnotationSelector が {@link TrimMarkAnnotation} オブジェクトで初期化されている場合、{@code trimMark} を選択します。 |
| [visit](#visit-com.aspose.pdf.UnderlineAnnotation-) | AnnotationSelector が UnderlineAnnotation オブジェクトで初期化されている場合、下線注釈を選択してください。 |
| [visit](#visit-com.aspose.pdf.WatermarkAnnotation-) | AnnotationSelector が WatermarkAnnotation オブジェクトで初期化されている場合、ウォーターマーク注釈を選択します。 |
| [visit](#visit-com.aspose.pdf.WidgetAnnotation-) | AnnotationSelector が WidgetAnnotation オブジェクトで初期化されている場合、ウィジェット注釈を選択します。 |

### AnnotationSelector {#AnnotationSelector--}
```
public AnnotationSelector()
```

AnnotationSelector クラスの新しいインスタンスを初期化します。

### AnnotationSelector {#AnnotationSelector-com.aspose.pdf.Annotation-}
AnnotationSelector クラスの新しいインスタンスを初期化します。

### getSelected {#getSelected--}
```
public List < Annotation > getSelected()
```

選択されたオブジェクトのリストです。

**Returns:**
Annotation インスタンスの一覧

### visit {#visit-com.aspose.pdf.BleedMarkAnnotation-}
{@link AnnotationSelector} が {@link BleedMarkAnnotation} オブジェクトで初期化されている場合、{@code bleedMark} を選択します。

### visit {#visit-com.aspose.pdf.CaretAnnotation-}
AnnotationSelector が CaretAnnotation オブジェクトで初期化されている場合、キャレット注釈を選択します。

### visit {#visit-com.aspose.pdf.CircleAnnotation-}
AnnotationSelector が CircleAnnotation オブジェクトで初期化されている場合、円形注釈を選択してください。

### visit {#visit-com.aspose.pdf.ColorBarAnnotation-}
AnnotationSelector が ColorBar オブジェクトで初期化されている場合、ColorBar 注釈を選択してください。

### visit {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
AnnotationSelector が FileAttachmentAnnotation オブジェクトで初期化されている場合、添付注釈を選択してください。

### visit {#visit-com.aspose.pdf.FreeTextAnnotation-}
AnnotationSelector が FreeTextAnnotation オブジェクトで初期化されている場合、フリーテキスト注釈を選択してください。

### visit {#visit-com.aspose.pdf.HighlightAnnotation-}
AnnotationSelector が FreeTextAnnotation オブジェクトで初期化されている場合、添付注釈を選択してください。

### visit {#visit-com.aspose.pdf.InkAnnotation-}
AnnotationSelector が InkAnnotation オブジェクトで初期化されている場合、インク注釈を選択してください。

### visit {#visit-com.aspose.pdf.LineAnnotation-}
AnnotationSelector が LineAnnotation オブジェクトで初期化されている場合、線注釈を選択してください。

### visit {#visit-com.aspose.pdf.LinkAnnotation-}
AnnotationSelector が LinkAnnotation オブジェクトで初期化されている場合、リンク注釈を選択してください。

### visit {#visit-com.aspose.pdf.MovieAnnotation-}
AnnotationSelector が MovieAnnotation オブジェクトで初期化されている場合、ムービー注釈を選択してください。

### visit {#visit-com.aspose.pdf.PageInformationAnnotation-}
AnnotationSelector が {@link PageInformationAnnotation} オブジェクトで初期化されている場合、{@code pageInformation} を選択します。

### visit {#visit-com.aspose.pdf.PDF3DAnnotation-}
AnnotationSelector が PDF3DAnnotation オブジェクトで初期化されている場合、PDF3D 注釈を選択してください。

### visit {#visit-com.aspose.pdf.PolygonAnnotation-}
AnnotationSelector が PolygonAnnotation オブジェクトで初期化されている場合、多角形注釈を選択してください。

### visit {#visit-com.aspose.pdf.PolylineAnnotation-}
AnnotationSelector が PolylineAnnotation オブジェクトで初期化されている場合、ポリライン注釈を選択してください。

### visit {#visit-com.aspose.pdf.PopupAnnotation-}
AnnotationSelector が PopupAnnotation オブジェクトで初期化されている場合、ポップアップ注釈を選択してください。

### visit {#visit-com.aspose.pdf.RedactionAnnotation-}
AnnotationSelector が RedactAnnotation オブジェクトで初期化されている場合、編集注釈を選択してください。

### visit {#visit-com.aspose.pdf.RegistrationMarkAnnotation-}
AnnotationSelector が {@link RegistrationMarkAnnotation} オブジェクトで初期化されている場合、{@code registrationMark} を選択します。

### visit {#visit-com.aspose.pdf.RichMediaAnnotation-}
AnnotationSelector が RichMedia 注釈オブジェクトで初期化されている場合、ムービー注釈を選択してください。

### visit {#visit-com.aspose.pdf.ScreenAnnotation-}
AnnotationSelector が ScreenAnnotation オブジェクトで初期化されている場合、スクリーン注釈を選択してください。

### visit {#visit-com.aspose.pdf.SquareAnnotation-}
AnnotationSelector が SquareAnnotation オブジェクトで初期化されている場合、正方形注釈を選択してください。

### visit {#visit-com.aspose.pdf.SquigglyAnnotation-}
AnnotationSelector が SquigglyAnnotation オブジェクトで初期化されている場合、波線注釈を選択してください。

### visit {#visit-com.aspose.pdf.StampAnnotation-}
AnnotationSelector が StampAnnotation オブジェクトで初期化されている場合、スタンプ注釈を選択してください。

### visit {#visit-com.aspose.pdf.StrikeOutAnnotation-}
AnnotationSelector が StrikeOutAnnotation オブジェクトで初期化されている場合、取り消し線注釈を選択してください。

### visit {#visit-com.aspose.pdf.TextAnnotation-}
AnnotationSelector が TextAnnotation オブジェクトで初期化されている場合、テキスト注釈を選択してください。

### visit {#visit-com.aspose.pdf.TrimMarkAnnotation-}
AnnotationSelector が {@link TrimMarkAnnotation} オブジェクトで初期化されている場合、{@code trimMark} を選択します。

### visit {#visit-com.aspose.pdf.UnderlineAnnotation-}
AnnotationSelector が UnderlineAnnotation オブジェクトで初期化されている場合、下線注釈を選択してください。

### visit {#visit-com.aspose.pdf.WatermarkAnnotation-}
AnnotationSelector が WatermarkAnnotation オブジェクトで初期化されている場合、ウォーターマーク注釈を選択します。

### visit {#visit-com.aspose.pdf.WidgetAnnotation-}
AnnotationSelector が WidgetAnnotation オブジェクトで初期化されている場合、ウィジェット注釈を選択します。
