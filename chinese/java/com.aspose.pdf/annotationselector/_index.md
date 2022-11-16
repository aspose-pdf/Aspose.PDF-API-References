---
title: AnnotationSelector
second_title: 用于 Java API 参考的 Aspose.PDF
description: 该类用于使用Visitor模板思想选择标注。
type: docs
weight: 19
url: /zh/java/com.aspose.pdf/annotationselector/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
[com.aspose.pdf.IAnnotationVisitor](../../com.aspose.pdf/iannotationvisitor)
```
public final class AnnotationSelector implements IAnnotationVisitor
```

该类用于使用Visitor模板思想选择标注。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AnnotationSelector()](#AnnotationSelector--) | 初始化 AnnotationSelector 类的新实例。 |
| [AnnotationSelector(Annotation annotation)](#AnnotationSelector-com.aspose.pdf.Annotation-) | 初始化新的 AnnotationSelector 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSelected()](#getSelected--) | 选定对象的列表。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [visit(CaretAnnotation caret)](#visit-com.aspose.pdf.CaretAnnotation-) | 如果 AnnotationSelector 是使用 CaretAnnotation 对象初始化的，则选择插入符号注释。 |
| [visit(CircleAnnotation circle)](#visit-com.aspose.pdf.CircleAnnotation-) | 如果 AnnotationSelector 是使用 CircleAnnotation 对象初始化的，则选择圆形注释。 |
| [visit(FileAttachmentAnnotation attachment)](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | 如果 AnnotationSelector 是使用 FileAttachmentAnnotation 对象初始化的，则选择附件注释。 |
| [visit(FreeTextAnnotation freetext)](#visit-com.aspose.pdf.FreeTextAnnotation-) | 如果 AnnotationSelector 是使用 FreeTextAnnotation 对象初始化的，则选择自由文本注释。 |
| [visit(HighlightAnnotation highlight)](#visit-com.aspose.pdf.HighlightAnnotation-) | 如果 AnnotationSelector 是使用 FreeTextAnnotation 对象初始化的，则选择附件注释。 |
| [visit(InkAnnotation ink)](#visit-com.aspose.pdf.InkAnnotation-) | 如果 AnnotationSelector 是使用 InkAnnotation 对象初始化的，则选择墨迹注释。 |
| [visit(LineAnnotation line)](#visit-com.aspose.pdf.LineAnnotation-) | 如果 AnnotationSelector 是使用 LineAnnotation 对象初始化的，则选择线注释。 |
| [visit(LinkAnnotation link)](#visit-com.aspose.pdf.LinkAnnotation-) | 如果 AnnotationSelector 是使用 LinkAnnotation 对象初始化的，则选择链接注释。 |
| [visit(MovieAnnotation movie)](#visit-com.aspose.pdf.MovieAnnotation-) | 如果 AnnotationSelector 是使用 MovieAnnotation 对象初始化的，则选择电影注释。 |
| [visit(PDF3DAnnotation pdf3D)](#visit-com.aspose.pdf.PDF3DAnnotation-) | 如果 AnnotationSelector 是使用 PDF3DAnnotation 对象初始化的，则选择 PDF3D 注释。 |
| [visit(PolygonAnnotation polygon)](#visit-com.aspose.pdf.PolygonAnnotation-) | 如果 AnnotationSelector 是使用 PolygonAnnotation 对象初始化的，则选择多边形注释。 |
| [visit(PolylineAnnotation polyline)](#visit-com.aspose.pdf.PolylineAnnotation-) | 如果 AnnotationSelector 是使用 PolylineAnnotation 对象初始化的，则选择折线注释。 |
| [visit(PopupAnnotation popup)](#visit-com.aspose.pdf.PopupAnnotation-) | 如果 AnnotationSelector 是使用 PopupAnnotation 对象初始化的，则选择弹出式注释。 |
| [visit(RedactionAnnotation redact)](#visit-com.aspose.pdf.RedactionAnnotation-) | 如果 AnnotationSelector 是使用 RedactAnnotation 对象初始化的，则选择编辑注释。 |
| [visit(RichMediaAnnotation richMedia)](#visit-com.aspose.pdf.RichMediaAnnotation-) | 如果 AnnotationSelector 是使用 RichMedia 注释对象初始化的，则选择电影注释。 |
| [visit(ScreenAnnotation screen)](#visit-com.aspose.pdf.ScreenAnnotation-) | 如果 AnnotationSelector 是使用 ScreenAnnotation 对象初始化的，则选择屏幕注释。 |
| [visit(SquareAnnotation square)](#visit-com.aspose.pdf.SquareAnnotation-) | 如果 AnnotationSelector 是使用 SquareAnnotation 对象初始化的，则选择方形注释。 |
| [visit(SquigglyAnnotation squiggly)](#visit-com.aspose.pdf.SquigglyAnnotation-) | 如果 AnnotationSelector 是使用 SquigglyAnnotation 对象初始化的，则选择波浪注释。 |
| [visit(StampAnnotation stamp)](#visit-com.aspose.pdf.StampAnnotation-) | 如果 AnnotationSelector 是使用 StampAnnotation 对象初始化的，则选择图章注释。 |
| [visit(StrikeOutAnnotation strikeOut)](#visit-com.aspose.pdf.StrikeOutAnnotation-) | 如果 AnnotationSelector 是使用 StrikeOutAnnotation 对象初始化的，则选择 strikeOut 注释。 |
| [visit(TextAnnotation text)](#visit-com.aspose.pdf.TextAnnotation-) | 如果 AnnotationSelector 是使用 TextAnnotation 对象初始化的，则选择文本注释。 |
| [visit(UnderlineAnnotation underline)](#visit-com.aspose.pdf.UnderlineAnnotation-) | 如果 AnnotationSelector 是使用 UnderlineAnnotation 对象初始化的，则选择下划线注释。 |
| [visit(WatermarkAnnotation watermark)](#visit-com.aspose.pdf.WatermarkAnnotation-) | 如果 AnnotationSelector 是使用 WatermarkAnnotation 对象初始化的，则选择水印注释。 |
| [visit(WidgetAnnotation widget)](#visit-com.aspose.pdf.WidgetAnnotation-) | 如果 AnnotationSelector 是使用 WidgetAnnotation 对象初始化的，则选择小部件注释。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnnotationSelector() {#AnnotationSelector--}
```
public AnnotationSelector()
```


初始化 AnnotationSelector 类的新实例。

### AnnotationSelector(Annotation annotation) {#AnnotationSelector-com.aspose.pdf.Annotation-}
```
public AnnotationSelector(Annotation annotation)
```


初始化新的 AnnotationSelector 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | 要选择的注释。该对象仅描述了我们希望找到的注释具有的一些特征，例如注释的类型。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getSelected() {#getSelected--}
```
public List<Annotation> getSelected()
```


选定对象的列表。

**退货：**
java.util.List<com.aspose.pdf.Annotation> - 注释实例列表
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### visit(CaretAnnotation caret) {#visit-com.aspose.pdf.CaretAnnotation-}
```
public void visit(CaretAnnotation caret)
```


如果 AnnotationSelector 是使用 CaretAnnotation 对象初始化的，则选择插入符号注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| caret | [CaretAnnotation](../../com.aspose.pdf/caretannotation) | 用于选择的 CaretAnnotation 对象。 |

### visit(CircleAnnotation circle) {#visit-com.aspose.pdf.CircleAnnotation-}
```
public void visit(CircleAnnotation circle)
```


如果 AnnotationSelector 是使用 CircleAnnotation 对象初始化的，则选择圆形注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| circle | [CircleAnnotation](../../com.aspose.pdf/circleannotation) | 用于选择的 CircleAnnotation 对象。 |

### visit(FileAttachmentAnnotation attachment) {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
```
public void visit(FileAttachmentAnnotation attachment)
```


如果 AnnotationSelector 是使用 FileAttachmentAnnotation 对象初始化的，则选择附件注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| attachment | [FileAttachmentAnnotation](../../com.aspose.pdf/fileattachmentannotation) | 用于选择的 FileAttachmentAnnotation 对象。 |

### visit(FreeTextAnnotation freetext) {#visit-com.aspose.pdf.FreeTextAnnotation-}
```
public void visit(FreeTextAnnotation freetext)
```


如果 AnnotationSelector 是使用 FreeTextAnnotation 对象初始化的，则选择自由文本注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| freetext | [FreeTextAnnotation](../../com.aspose.pdf/freetextannotation) | 用于选择的 FreeTextAnnotation 对象。 |

### visit(HighlightAnnotation highlight) {#visit-com.aspose.pdf.HighlightAnnotation-}
```
public void visit(HighlightAnnotation highlight)
```


如果 AnnotationSelector 是使用 FreeTextAnnotation 对象初始化的，则选择附件注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| highlight | [HighlightAnnotation](../../com.aspose.pdf/highlightannotation) | 用于选择的 HighlightAnnotation 对象。 |

### visit(InkAnnotation ink) {#visit-com.aspose.pdf.InkAnnotation-}
```
public void visit(InkAnnotation ink)
```


如果 AnnotationSelector 是使用 InkAnnotation 对象初始化的，则选择墨迹注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ink | [InkAnnotation](../../com.aspose.pdf/inkannotation) | 用于选择的 InkAnnotation 对象。 |

### visit(LineAnnotation line) {#visit-com.aspose.pdf.LineAnnotation-}
```
public void visit(LineAnnotation line)
```


如果 AnnotationSelector 是使用 LineAnnotation 对象初始化的，则选择线注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| line | [LineAnnotation](../../com.aspose.pdf/lineannotation) | 用于选择的 LineAnnotation 对象。 |

### visit(LinkAnnotation link) {#visit-com.aspose.pdf.LinkAnnotation-}
```
public void visit(LinkAnnotation link)
```


如果 AnnotationSelector 是使用 LinkAnnotation 对象初始化的，则选择链接注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| link | [LinkAnnotation](../../com.aspose.pdf/linkannotation) | 用于选择的 LinkAnnotation 对象。 |

### visit(MovieAnnotation movie) {#visit-com.aspose.pdf.MovieAnnotation-}
```
public void visit(MovieAnnotation movie)
```


如果 AnnotationSelector 是使用 MovieAnnotation 对象初始化的，则选择电影注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| movie | [MovieAnnotation](../../com.aspose.pdf/movieannotation) | 用于选择的 MovieAnnotation 对象。 |

### visit(PDF3DAnnotation pdf3D) {#visit-com.aspose.pdf.PDF3DAnnotation-}
```
public void visit(PDF3DAnnotation pdf3D)
```


如果 AnnotationSelector 是使用 PDF3DAnnotation 对象初始化的，则选择 PDF3D 注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdf3D | [PDF3DAnnotation](../../com.aspose.pdf/pdf3dannotation) | 用于选择的 PDF3DAnnotation 对象。 |

### visit(PolygonAnnotation polygon) {#visit-com.aspose.pdf.PolygonAnnotation-}
```
public void visit(PolygonAnnotation polygon)
```


如果 AnnotationSelector 是使用 PolygonAnnotation 对象初始化的，则选择多边形注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| polygon | [PolygonAnnotation](../../com.aspose.pdf/polygonannotation) | 用于选择的 PolygonAnnotation 对象。 |

### visit(PolylineAnnotation polyline) {#visit-com.aspose.pdf.PolylineAnnotation-}
```
public void visit(PolylineAnnotation polyline)
```


如果 AnnotationSelector 是使用 PolylineAnnotation 对象初始化的，则选择折线注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| polyline | [PolylineAnnotation](../../com.aspose.pdf/polylineannotation) | 用于选择的 PolylineAnnotation 对象。 |

### visit(PopupAnnotation popup) {#visit-com.aspose.pdf.PopupAnnotation-}
```
public void visit(PopupAnnotation popup)
```


如果 AnnotationSelector 是使用 PopupAnnotation 对象初始化的，则选择弹出式注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| popup | [PopupAnnotation](../../com.aspose.pdf/popupannotation) | 用于选择的 PopupAnnotation 对象。 |

### visit(RedactionAnnotation redact) {#visit-com.aspose.pdf.RedactionAnnotation-}
```
public void visit(RedactionAnnotation redact)
```


如果 AnnotationSelector 是使用 RedactAnnotation 对象初始化的，则选择编辑注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| redact | [RedactionAnnotation](../../com.aspose.pdf/redactionannotation) | 用于选择的 RedactAnnotation 对象。 |

### visit(RichMediaAnnotation richMedia) {#visit-com.aspose.pdf.RichMediaAnnotation-}
```
public void visit(RichMediaAnnotation richMedia)
```


如果 AnnotationSelector 是使用 RichMedia 注释对象初始化的，则选择电影注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| richMedia | [RichMediaAnnotation](../../com.aspose.pdf/richmediaannotation) | 富媒体注释。 |

### visit(ScreenAnnotation screen) {#visit-com.aspose.pdf.ScreenAnnotation-}
```
public void visit(ScreenAnnotation screen)
```


如果 AnnotationSelector 是使用 ScreenAnnotation 对象初始化的，则选择屏幕注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| screen | [ScreenAnnotation](../../com.aspose.pdf/screenannotation) | 用于选择的 ScreenAnnotation 对象。 |

### visit(SquareAnnotation square) {#visit-com.aspose.pdf.SquareAnnotation-}
```
public void visit(SquareAnnotation square)
```


如果 AnnotationSelector 是使用 SquareAnnotation 对象初始化的，则选择方形注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| square | [SquareAnnotation](../../com.aspose.pdf/squareannotation) | 用于选择的 SquareAnnotation 对象。 |

### visit(SquigglyAnnotation squiggly) {#visit-com.aspose.pdf.SquigglyAnnotation-}
```
public void visit(SquigglyAnnotation squiggly)
```


如果 AnnotationSelector 是使用 SquigglyAnnotation 对象初始化的，则选择波浪注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| squiggly | [SquigglyAnnotation](../../com.aspose.pdf/squigglyannotation) | 用于选择的 SquigglyAnnotation 对象。 |

### visit(StampAnnotation stamp) {#visit-com.aspose.pdf.StampAnnotation-}
```
public void visit(StampAnnotation stamp)
```


如果 AnnotationSelector 是使用 StampAnnotation 对象初始化的，则选择图章注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stamp | [StampAnnotation](../../com.aspose.pdf/stampannotation) | 用于选择的 StampAnnotation 对象。 |

### visit(StrikeOutAnnotation strikeOut) {#visit-com.aspose.pdf.StrikeOutAnnotation-}
```
public void visit(StrikeOutAnnotation strikeOut)
```


如果 AnnotationSelector 是使用 StrikeOutAnnotation 对象初始化的，则选择 strikeOut 注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| strikeOut | [StrikeOutAnnotation](../../com.aspose.pdf/strikeoutannotation) | 用于选择的 StrikeOutAnnotation 对象。 |

### visit(TextAnnotation text) {#visit-com.aspose.pdf.TextAnnotation-}
```
public void visit(TextAnnotation text)
```


如果 AnnotationSelector 是使用 TextAnnotation 对象初始化的，则选择文本注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | [TextAnnotation](../../com.aspose.pdf/textannotation) | 用于选择的 TextAnnotation 对象。 |

### visit(UnderlineAnnotation underline) {#visit-com.aspose.pdf.UnderlineAnnotation-}
```
public void visit(UnderlineAnnotation underline)
```


如果 AnnotationSelector 是使用 UnderlineAnnotation 对象初始化的，则选择下划线注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| underline | [UnderlineAnnotation](../../com.aspose.pdf/underlineannotation) | 用于选择的 UnderlineAnnotation 对象。 |

### visit(WatermarkAnnotation watermark) {#visit-com.aspose.pdf.WatermarkAnnotation-}
```
public void visit(WatermarkAnnotation watermark)
```


如果 AnnotationSelector 是使用 WatermarkAnnotation 对象初始化的，则选择水印注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| watermark | [WatermarkAnnotation](../../com.aspose.pdf/watermarkannotation) | 用于选择的 WatermarkAnnotation。 |

### visit(WidgetAnnotation widget) {#visit-com.aspose.pdf.WidgetAnnotation-}
```
public void visit(WidgetAnnotation widget)
```


如果 AnnotationSelector 是使用 WidgetAnnotation 对象初始化的，则选择小部件注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| widget | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) | 用于选择的 WidgetAnnotation 对象。 |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
