---
title: "クラス AnnotationSelector"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Annotations.AnnotationSelector クラス。このクラスは Visitor テンプレートの考え方を使用してアノテーションを選択するために使用されます。"
type: docs
weight: 1540
url: /ja/net/aspose.pdf.annotations/annotationselector/
---
## AnnotationSelector class

このクラスは、Visitor パターンの考え方を使用して注釈を選択するために使用されます。

```csharp
public sealed class AnnotationSelector : IAnnotationVisitor
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [AnnotationSelector](annotationselector/#constructor)() | AnnotationSelector クラスの新しいインスタンスを初期化します。 |
| [AnnotationSelector](annotationselector/#constructor_1)(Annotation) | 新しい `AnnotationSelector` オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Selected](../../aspose.pdf.annotations/annotationselector/selected/) { get; } | 選択されたオブジェクトのリストです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit)(BleedMarkAnnotation) | `AnnotationSelector` が [`BleedMarkAnnotation`](../bleedmarkannotation/) オブジェクトで初期化されている場合、*bleedMark* を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_1)(CaretAnnotation) | `AnnotationSelector` が CaretAnnotation オブジェクトで初期化されている場合、キャレット アノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_2)(CircleAnnotation) | `AnnotationSelector` が CircleAnnotation オブジェクトで初期化されている場合、円形アノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_3)(ColorBarAnnotation) | `AnnotationSelector` が ColorBar オブジェクトで初期化されている場合、ColorBar アノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_4)(FileAttachmentAnnotation) | `AnnotationSelector` が FileAttachmentAnnotation オブジェクトで初期化されている場合、添付ファイルアノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_5)(FreeTextAnnotation) | `AnnotationSelector` が FreeTextAnnotation オブジェクトで初期化されている場合、フリーテキストアノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_6)(HighlightAnnotation) | AnnotationSelector が FreeTextAnnotation オブジェクトで初期化されている場合、添付アノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_7)(InkAnnotation) | AnnotationSelector が InkAnnotation オブジェクトで初期化されている場合、インクアノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_8)(LineAnnotation) | AnnotationSelector が LineAnnotation オブジェクトで初期化されている場合、ラインアノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_9)(LinkAnnotation) | AnnotationSelector が LinkAnnotation オブジェクトで初期化されている場合、リンクアノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_10)(MovieAnnotation) | AnnotationSelector が MovieAnnotation オブジェクトで初期化されている場合、ムービーアノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_11)(PageInformationAnnotation) | `AnnotationSelector` が [`PageInformationAnnotation`](../pageinformationannotation/) オブジェクトで初期化されている場合、*pageInformation* を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_12)(PDF3DAnnotation) | AnnotationSelector が PDF3DAnnotation オブジェクトで初期化されている場合、PDF3D アノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_13)(PolygonAnnotation) | AnnotationSelector が PolygonAnnotation オブジェクトで初期化されている場合、ポリゴンアノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_14)(PolylineAnnotation) | AnnotationSelector が PolylineAnnotation オブジェクトで初期化されている場合、ポリラインアノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_15)(PopupAnnotation) | AnnotationSelector が PopupAnnotation オブジェクトで初期化されている場合、ポップアップアノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_16)(RedactionAnnotation) | AnnotationSelector が RedactAnnotation オブジェクトで初期化されている場合、Redact アノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_17)(RegistrationMarkAnnotation) | `AnnotationSelector` が [`RegistrationMarkAnnotation`](../registrationmarkannotation/) オブジェクトで初期化されている場合、*registrationMark* を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_18)(RichMediaAnnotation) | AnnotationSelector が RichMedia アノテーションオブジェクトで初期化されている場合、ムービーアノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_19)(ScreenAnnotation) | AnnotationSelector が ScreenAnnotation オブジェクトで初期化されている場合、スクリーンアノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_20)(SquareAnnotation) | AnnotationSelector が SquareAnnotation オブジェクトで初期化されている場合、Square アノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_21)(SquigglyAnnotation) | AnnotationSelector が SquigglyAnnotation オブジェクトで初期化されている場合、Squiggly アノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_22)(StampAnnotation) | AnnotationSelector が StampAnnotation オブジェクトで初期化されている場合、スタンプアノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_23)(StrikeOutAnnotation) | AnnotationSelector が StrikeOutAnnotation オブジェクトで初期化されている場合、StrikeOut アノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_24)(TextAnnotation) | AnnotationSelector が TextAnnotation オブジェクトで初期化されている場合、テキストアノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_25)(TrimMarkAnnotation) | `AnnotationSelector` が [`TrimMarkAnnotation`](../trimmarkannotation/) オブジェクトで初期化されている場合、*trimMark* を選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_26)(UnderlineAnnotation) | AnnotationSelector が UnderlineAnnotation オブジェクトで初期化されている場合、下線アノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_27)(WatermarkAnnotation) | AnnotationSelector が WatermarkAnnotation オブジェクトで初期化されている場合、ウォーターマークアノテーションを選択します。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_28)(WidgetAnnotation) | AnnotationSelector が WidgetAnnotation オブジェクトで初期化されている場合、ウィジェットアノテーションを選択します。 |

### 関連項目

* interface [IAnnotationVisitor](../iannotationvisitor/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


