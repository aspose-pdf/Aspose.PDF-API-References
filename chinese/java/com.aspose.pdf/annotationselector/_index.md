---
title: "AnnotationSelector"
linktitle: "AnnotationSelector"
second_title: "Aspose.PDF for Java API 参考"
description: "此类用于使用 Visitor 模板思想选择注释。"
type: docs
weight: 100
url: /zh/java/com.aspose.pdf/annotationselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationSelector

**All Implemented Interfaces:**
IAnnotationVisitor

```
public final class AnnotationSelector extends Object implements IAnnotationVisitor
```

此类用于使用 Visitor 模板思想选择注释。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AnnotationSelector](#AnnotationSelector--) | 初始化 AnnotationSelector 类的新实例。 |
| [AnnotationSelector](#AnnotationSelector-com.aspose.pdf.Annotation-) | 初始化 AnnotationSelector 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getSelected](#getSelected--) | 已选择对象的列表。 |
| [visit](#visit-com.aspose.pdf.BleedMarkAnnotation-) | 如果 {@link AnnotationSelector} 已使用 {@link BleedMarkAnnotation} 对象初始化，则选择 {@code bleedMark}。 |
| [visit](#visit-com.aspose.pdf.CaretAnnotation-) | 如果 AnnotationSelector 已使用 CaretAnnotation 对象初始化，则选择 caret 注释。 |
| [visit](#visit-com.aspose.pdf.CircleAnnotation-) | 如果 AnnotationSelector 使用 CircleAnnotation 对象初始化，则选择圆形注释。 |
| [visit](#visit-com.aspose.pdf.ColorBarAnnotation-) | 如果 AnnotationSelector 使用 ColorBar 对象初始化，则选择 ColorBar 注释。 |
| [visit](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | 如果 AnnotationSelector 使用 FileAttachmentAnnotation 对象初始化，则选择附件注释。 |
| [visit](#visit-com.aspose.pdf.FreeTextAnnotation-) | 如果 AnnotationSelector 使用 FreeTextAnnotation 对象初始化，则选择自由文本注释。 |
| [visit](#visit-com.aspose.pdf.HighlightAnnotation-) | 如果 AnnotationSelector 使用 FreeTextAnnotation 对象初始化，则选择附件注释。 |
| [visit](#visit-com.aspose.pdf.InkAnnotation-) | 如果 AnnotationSelector 使用 InkAnnotation 对象初始化，则选择墨迹注释。 |
| [visit](#visit-com.aspose.pdf.LineAnnotation-) | 如果 AnnotationSelector 使用 LineAnnotation 对象初始化，则选择线条注释。 |
| [visit](#visit-com.aspose.pdf.LinkAnnotation-) | 如果 AnnotationSelector 使用 LinkAnnotation 对象初始化，则选择链接注释。 |
| [visit](#visit-com.aspose.pdf.MovieAnnotation-) | 如果 AnnotationSelector 使用 MovieAnnotation 对象初始化，则选择电影注释。 |
| [visit](#visit-com.aspose.pdf.PageInformationAnnotation-) | 如果 {@link AnnotationSelector} 使用 {@link PageInformationAnnotation} 对象初始化，则选择 {@code pageInformation}。 |
| [visit](#visit-com.aspose.pdf.PDF3DAnnotation-) | 如果 AnnotationSelector 使用 PDF3DAnnotation 对象初始化，则选择 PDF3D 注释。 |
| [visit](#visit-com.aspose.pdf.PolygonAnnotation-) | 如果 AnnotationSelector 使用 PolygonAnnotation 对象初始化，则选择多边形注释。 |
| [visit](#visit-com.aspose.pdf.PolylineAnnotation-) | 如果 AnnotationSelector 使用 PolylineAnnotation 对象初始化，则选择折线注释。 |
| [visit](#visit-com.aspose.pdf.PopupAnnotation-) | 如果 AnnotationSelector 使用 PopupAnnotation 对象初始化，则选择弹出注释。 |
| [visit](#visit-com.aspose.pdf.RedactionAnnotation-) | 如果 AnnotationSelector 使用 RedactAnnotation 对象初始化，则选择编辑注释。 |
| [visit](#visit-com.aspose.pdf.RegistrationMarkAnnotation-) | 如果 {@link AnnotationSelector} 使用 {@link RegistrationMarkAnnotation} 对象初始化，则选择 {@code registrationMark}。 |
| [visit](#visit-com.aspose.pdf.RichMediaAnnotation-) | 如果 AnnotationSelector 使用 RichMedia 注释对象初始化，则选择电影注释。 |
| [visit](#visit-com.aspose.pdf.ScreenAnnotation-) | 如果 AnnotationSelector 使用 ScreenAnnotation 对象初始化，则选择屏幕注释。 |
| [visit](#visit-com.aspose.pdf.SquareAnnotation-) | 如果 AnnotationSelector 使用 SquareAnnotation 对象初始化，则选择方形注释。 |
| [visit](#visit-com.aspose.pdf.SquigglyAnnotation-) | 如果 AnnotationSelector 使用 SquigglyAnnotation 对象初始化，则选择波浪线注释。 |
| [visit](#visit-com.aspose.pdf.StampAnnotation-) | 如果 AnnotationSelector 使用 StampAnnotation 对象初始化，则选择印章注释。 |
| [visit](#visit-com.aspose.pdf.StrikeOutAnnotation-) | 如果 AnnotationSelector 使用 StrikeOutAnnotation 对象初始化，则选择删除线注释。 |
| [visit](#visit-com.aspose.pdf.TextAnnotation-) | 如果 AnnotationSelector 使用 TextAnnotation 对象初始化，则选择文本注释。 |
| [visit](#visit-com.aspose.pdf.TrimMarkAnnotation-) | 如果 {@link AnnotationSelector} 使用 {@link TrimMarkAnnotation} 对象初始化，则选择 {@code trimMark}。 |
| [visit](#visit-com.aspose.pdf.UnderlineAnnotation-) | 如果 AnnotationSelector 使用 UnderlineAnnotation 对象初始化，则选择下划线注释。 |
| [visit](#visit-com.aspose.pdf.WatermarkAnnotation-) | 如果 AnnotationSelector 使用 WatermarkAnnotation 对象初始化，则选择水印注释。 |
| [visit](#visit-com.aspose.pdf.WidgetAnnotation-) | 如果 AnnotationSelector 使用 WidgetAnnotation 对象初始化，则选择小部件注释。 |

### AnnotationSelector {#AnnotationSelector--}
```
public AnnotationSelector()
```

初始化 AnnotationSelector 类的新实例。

### AnnotationSelector {#AnnotationSelector-com.aspose.pdf.Annotation-}
初始化 AnnotationSelector 类的新实例。

### getSelected {#getSelected--}
```
public List < Annotation > getSelected()
```

已选择对象的列表。

**Returns:**
Annotation 实例列表

### visit {#visit-com.aspose.pdf.BleedMarkAnnotation-}
如果 {@link AnnotationSelector} 已使用 {@link BleedMarkAnnotation} 对象初始化，则选择 {@code bleedMark}。

### visit {#visit-com.aspose.pdf.CaretAnnotation-}
如果 AnnotationSelector 已使用 CaretAnnotation 对象初始化，则选择 caret 注释。

### visit {#visit-com.aspose.pdf.CircleAnnotation-}
如果 AnnotationSelector 使用 CircleAnnotation 对象初始化，则选择圆形注释。

### visit {#visit-com.aspose.pdf.ColorBarAnnotation-}
如果 AnnotationSelector 使用 ColorBar 对象初始化，则选择 ColorBar 注释。

### visit {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
如果 AnnotationSelector 使用 FileAttachmentAnnotation 对象初始化，则选择附件注释。

### visit {#visit-com.aspose.pdf.FreeTextAnnotation-}
如果 AnnotationSelector 使用 FreeTextAnnotation 对象初始化，则选择自由文本注释。

### visit {#visit-com.aspose.pdf.HighlightAnnotation-}
如果 AnnotationSelector 使用 FreeTextAnnotation 对象初始化，则选择附件注释。

### visit {#visit-com.aspose.pdf.InkAnnotation-}
如果 AnnotationSelector 使用 InkAnnotation 对象初始化，则选择墨迹注释。

### visit {#visit-com.aspose.pdf.LineAnnotation-}
如果 AnnotationSelector 使用 LineAnnotation 对象初始化，则选择线条注释。

### visit {#visit-com.aspose.pdf.LinkAnnotation-}
如果 AnnotationSelector 使用 LinkAnnotation 对象初始化，则选择链接注释。

### visit {#visit-com.aspose.pdf.MovieAnnotation-}
如果 AnnotationSelector 使用 MovieAnnotation 对象初始化，则选择电影注释。

### visit {#visit-com.aspose.pdf.PageInformationAnnotation-}
如果 {@link AnnotationSelector} 使用 {@link PageInformationAnnotation} 对象初始化，则选择 {@code pageInformation}。

### visit {#visit-com.aspose.pdf.PDF3DAnnotation-}
如果 AnnotationSelector 使用 PDF3DAnnotation 对象初始化，则选择 PDF3D 注释。

### visit {#visit-com.aspose.pdf.PolygonAnnotation-}
如果 AnnotationSelector 使用 PolygonAnnotation 对象初始化，则选择多边形注释。

### visit {#visit-com.aspose.pdf.PolylineAnnotation-}
如果 AnnotationSelector 使用 PolylineAnnotation 对象初始化，则选择折线注释。

### visit {#visit-com.aspose.pdf.PopupAnnotation-}
如果 AnnotationSelector 使用 PopupAnnotation 对象初始化，则选择弹出注释。

### visit {#visit-com.aspose.pdf.RedactionAnnotation-}
如果 AnnotationSelector 使用 RedactAnnotation 对象初始化，则选择编辑注释。

### visit {#visit-com.aspose.pdf.RegistrationMarkAnnotation-}
如果 {@link AnnotationSelector} 使用 {@link RegistrationMarkAnnotation} 对象初始化，则选择 {@code registrationMark}。

### visit {#visit-com.aspose.pdf.RichMediaAnnotation-}
如果 AnnotationSelector 使用 RichMedia 注释对象初始化，则选择电影注释。

### visit {#visit-com.aspose.pdf.ScreenAnnotation-}
如果 AnnotationSelector 使用 ScreenAnnotation 对象初始化，则选择屏幕注释。

### visit {#visit-com.aspose.pdf.SquareAnnotation-}
如果 AnnotationSelector 使用 SquareAnnotation 对象初始化，则选择方形注释。

### visit {#visit-com.aspose.pdf.SquigglyAnnotation-}
如果 AnnotationSelector 使用 SquigglyAnnotation 对象初始化，则选择波浪线注释。

### visit {#visit-com.aspose.pdf.StampAnnotation-}
如果 AnnotationSelector 使用 StampAnnotation 对象初始化，则选择印章注释。

### visit {#visit-com.aspose.pdf.StrikeOutAnnotation-}
如果 AnnotationSelector 使用 StrikeOutAnnotation 对象初始化，则选择删除线注释。

### visit {#visit-com.aspose.pdf.TextAnnotation-}
如果 AnnotationSelector 使用 TextAnnotation 对象初始化，则选择文本注释。

### visit {#visit-com.aspose.pdf.TrimMarkAnnotation-}
如果 {@link AnnotationSelector} 使用 {@link TrimMarkAnnotation} 对象初始化，则选择 {@code trimMark}。

### visit {#visit-com.aspose.pdf.UnderlineAnnotation-}
如果 AnnotationSelector 使用 UnderlineAnnotation 对象初始化，则选择下划线注释。

### visit {#visit-com.aspose.pdf.WatermarkAnnotation-}
如果 AnnotationSelector 使用 WatermarkAnnotation 对象初始化，则选择水印注释。

### visit {#visit-com.aspose.pdf.WidgetAnnotation-}
如果 AnnotationSelector 使用 WidgetAnnotation 对象初始化，则选择小部件注释。
