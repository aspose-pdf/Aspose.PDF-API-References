---
title: Class AnnotationSelector
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AnnotationSelector クラス。このクラスは、Visitor テンプレートのアイデアを使用して注釈を選択するために使用されます。
type: docs
weight: 1450
url: /ja/net/aspose.pdf.annotations/annotationselector/
---
## AnnotationSelector クラス

このクラスは、Visitor テンプレートのアイデアを使用して注釈を選択するために使用されます。

```csharp
public sealed class AnnotationSelector : IAnnotationVisitor
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [AnnotationSelector](annotationselector/#constructor)() | AnnotationSelector クラスの新しいインスタンスを初期化します。 |
| [AnnotationSelector](annotationselector/#constructor_1)(Annotation) | 新しい `AnnotationSelector` オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Selected](../../aspose.pdf.annotations/annotationselector/selected/) { get; } | 選択されたオブジェクトのリスト。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit)(BleedMarkAnnotation) | `AnnotationSelector` が [`BleedMarkAnnotation`](../bleedmarkannotation/) オブジェクトで初期化されている場合、*bleedMark* を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_1)(CaretAnnotation) | AnnotationSelector が CaretAnnotation オブジェクトで初期化されている場合、キャレット注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_2)(CircleAnnotation) | AnnotationSelector が CircleAnnotation オブジェクトで初期化されている場合、円注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_3)(ColorBarAnnotation) | AnnotationSelector が ColorBar オブジェクトで初期化されている場合、ColorBar 注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_4)(FileAttachmentAnnotation) | AnnotationSelector が FileAttachmentAnnotation オブジェクトで初期化されている場合、添付ファイル注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_5)(FreeTextAnnotation) | AnnotationSelector が FreeTextAnnotation オブジェクトで初期化されている場合、自由テキスト注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_6)(HighlightAnnotation) | AnnotationSelector が FreeTextAnnotation オブジェクトで初期化されている場合、添付ファイル注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_7)(InkAnnotation) | AnnotationSelector が InkAnnotation オブジェクトで初期化されている場合、インク注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_8)(LineAnnotation) | AnnotationSelector が LineAnnotation オブジェクトで初期化されている場合、線注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_9)(LinkAnnotation) | AnnotationSelector が LinkAnnotation オブジェクトで初期化されている場合、リンク注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_10)(MovieAnnotation) | AnnotationSelector が MovieAnnotation オブジェクトで初期化されている場合、ムービー注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_11)(PageInformationAnnotation) | `AnnotationSelector` が [`PageInformationAnnotation`](../pageinformationannotation/) オブジェクトで初期化されている場合、*pageInformation* を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_12)(PDF3DAnnotation) | AnnotationSelector が PDF3DAnnotation オブジェクトで初期化されている場合、PDF3D 注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_13)(PolygonAnnotation) | AnnotationSelector が PolygonAnnotation オブジェクトで初期化されている場合、ポリゴン注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_14)(PolylineAnnotation) | AnnotationSelector が PolylineAnnotation オブジェクトで初期化されている場合、ポリライン注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_15)(PopupAnnotation) | AnnotationSelector が PopupAnnotation オブジェクトで初期化されている場合、ポップアップ注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_16)(RedactionAnnotation) | AnnotationSelector が RedactAnnotation オブジェクトで初期化されている場合、削除注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_17)(RegistrationMarkAnnotation) | `AnnotationSelector` が [`RegistrationMarkAnnotation`](../registrationmarkannotation/) オブジェクトで初期化されている場合、*registrationMark* を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_18)(RichMediaAnnotation) | AnnotationSelector が RichMedia 注釈オブジェクトで初期化されている場合、ムービー注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_19)(ScreenAnnotation) | AnnotationSelector が ScreenAnnotation オブジェクトで初期化されている場合、画面注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_20)(SquareAnnotation) | AnnotationSelector が SquareAnnotation オブジェクトで初期化されている場合、四角形注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_21)(SquigglyAnnotation) | AnnotationSelector が SquigglyAnnotation オブジェクトで初期化されている場合、うねうね注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_22)(StampAnnotation) | AnnotationSelector が StampAnnotation オブジェクトで初期化されている場合、スタンプ注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_23)(StrikeOutAnnotation) | AnnotationSelector が StrikeOutAnnotation オブジェクトで初期化されている場合、取り消し線注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_24)(TextAnnotation) | AnnotationSelector が TextAnnotation オブジェクトで初期化されている場合、テキスト注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_25)(TrimMarkAnnotation) | `AnnotationSelector` が [`TrimMarkAnnotation`](../trimmarkannotation/) オブジェクトで初期化されている場合、*trimMark* を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_26)(UnderlineAnnotation) | AnnotationSelector が UnderlineAnnotation オブジェクトで初期化されている場合、下線注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_27)(WatermarkAnnotation) | AnnotationSelector が WatermarkAnnotation オブジェクトで初期化されている場合、ウォーターマーク注釈を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_28)(WidgetAnnotation) | AnnotationSelector が WidgetAnnotation オブジェクトで初期化されている場合、ウィジェット注釈を選択します。 |

### 参照

* インターフェース [IAnnotationVisitor](../iannotationvisitor/)
* 名前空間 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* アセンブリ [Aspose.PDF](../../)