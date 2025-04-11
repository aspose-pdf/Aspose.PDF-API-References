---
title: Class AnnotationSelector
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AnnotationSelector 类。此类用于使用访问者模板思想选择注释
type: docs
weight: 1450
url: /zh/net/aspose.pdf.annotations/annotationselector/
---
## AnnotationSelector 类

此类用于使用访问者模板思想选择注释。

```csharp
public sealed class AnnotationSelector : IAnnotationVisitor
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [AnnotationSelector](annotationselector/#constructor)() | 初始化 AnnotationSelector 类的新实例。 |
| [AnnotationSelector](annotationselector/#constructor_1)(Annotation) | 初始化新的 `AnnotationSelector` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Selected](../../aspose.pdf.annotations/annotationselector/selected/) { get; } | 选定对象的列表。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit)(BleedMarkAnnotation) | 如果 `AnnotationSelector` 是使用 [`BleedMarkAnnotation`](../bleedmarkannotation/) 对象初始化的，则选择 *bleedMark*。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_1)(CaretAnnotation) | 如果 AnnotationSelector 是使用 CaretAnnotation 对象初始化的，则选择光标注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_2)(CircleAnnotation) | 如果 AnnotationSelector 是使用 CircleAnnotation 对象初始化的，则选择圆形注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_3)(ColorBarAnnotation) | 如果 AnnotationSelector 是使用 ColorBar 对象初始化的，则选择 ColorBar 注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_4)(FileAttachmentAnnotation) | 如果 AnnotationSelector 是使用 FileAttachmentAnnotation 对象初始化的，则选择附件注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_5)(FreeTextAnnotation) | 如果 AnnotationSelector 是使用 FreeTextAnnotation 对象初始化的，则选择自由文本注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_6)(HighlightAnnotation) | 如果 AnnotationSelector 是使用 FreeTextAnnotation 对象初始化的，则选择附件注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_7)(InkAnnotation) | 如果 AnnotationSelector 是使用 InkAnnotation 对象初始化的，则选择墨水注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_8)(LineAnnotation) | 如果 AnnotationSelector 是使用 LineAnnotation 对象初始化的，则选择线条注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_9)(LinkAnnotation) | 如果 AnnotationSelector 是使用 LinkAnnotation 对象初始化的，则选择链接注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_10)(MovieAnnotation) | 如果 AnnotationSelector 是使用 MovieAnnotation 对象初始化的，则选择电影注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_11)(PageInformationAnnotation) | 如果 `AnnotationSelector` 是使用 [`PageInformationAnnotation`](../pageinformationannotation/) 对象初始化的，则选择 *pageInformation*。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_12)(PDF3DAnnotation) | 如果 AnnotationSelector 是使用 PDF3DAnnotation 对象初始化的，则选择 PDF3D 注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_13)(PolygonAnnotation) | 如果 AnnotationSelector 是使用 PolygonAnnotation 对象初始化的，则选择多边形注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_14)(PolylineAnnotation) | 如果 AnnotationSelector 是使用 PolylineAnnotation 对象初始化的，则选择折线注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_15)(PopupAnnotation) | 如果 AnnotationSelector 是使用 PopupAnnotation 对象初始化的，则选择弹出注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_16)(RedactionAnnotation) | 如果 AnnotationSelector 是使用 RedactAnnotation 对象初始化的，则选择编辑注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_17)(RegistrationMarkAnnotation) | 如果 `AnnotationSelector` 是使用 [`RegistrationMarkAnnotation`](../registrationmarkannotation/) 对象初始化的，则选择 *registrationMark*。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_18)(RichMediaAnnotation) | 如果 AnnotationSelector 是使用 RichMedia 注释对象初始化的，则选择电影注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_19)(ScreenAnnotation) | 如果 AnnotationSelector 是使用 ScreenAnnotation 对象初始化的，则选择屏幕注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_20)(SquareAnnotation) | 如果 AnnotationSelector 是使用 SquareAnnotation 对象初始化的，则选择正方形注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_21)(SquigglyAnnotation) | 如果 AnnotationSelector 是使用 SquigglyAnnotation 对象初始化的，则选择波浪线注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_22)(StampAnnotation) | 如果 AnnotationSelector 是使用 StampAnnotation 对象初始化的，则选择印章注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_23)(StrikeOutAnnotation) | 如果 AnnotationSelector 是使用 StrikeOutAnnotation 对象初始化的，则选择删除线注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_24)(TextAnnotation) | 如果 AnnotationSelector 是使用 TextAnnotation 对象初始化的，则选择文本注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_25)(TrimMarkAnnotation) | 如果 `AnnotationSelector` 是使用 [`TrimMarkAnnotation`](../trimmarkannotation/) 对象初始化的，则选择 *trimMark*。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_26)(UnderlineAnnotation) | 如果 AnnotationSelector 是使用 UnderlineAnnotation 对象初始化的，则选择下划线注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_27)(WatermarkAnnotation) | 如果 AnnotationSelector 是使用 WatermarkAnnotation 对象初始化的，则选择水印注释。 |
| [Visit](../../aspose.pdf.annotations/annotationselector/visit/#visit_28)(WidgetAnnotation) | 如果 AnnotationSelector 是使用 WidgetAnnotation 对象初始化的，则选择小部件注释。 |

### 另请参阅

* 接口 [IAnnotationVisitor](../iannotationvisitor/)
* 命名空间 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* 程序集 [Aspose.PDF](../../)