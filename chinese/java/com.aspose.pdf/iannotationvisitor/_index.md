---
title: IAnnotationVisitor
second_title: 用于 Java API 参考的 Aspose.PDF
description: 定义访问不同文档注释的Visitor。
type: docs
weight: 430
url: /zh/java/com.aspose.pdf/iannotationvisitor/
---
```
public interface IAnnotationVisitor
```

定义访问不同文档注释的Visitor。
## 方法

| 方法 | 描述 |
| --- | --- |
| [visit(CaretAnnotation caret)](#visit-com.aspose.pdf.CaretAnnotation-) | 访问/选择插入符号注释。 |
| [visit(CircleAnnotation circle)](#visit-com.aspose.pdf.CircleAnnotation-) | 访问/选择圆圈注释。 |
| [visit(FileAttachmentAnnotation attachment)](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | 访问/选择附件注释。 |
| [visit(FreeTextAnnotation freetext)](#visit-com.aspose.pdf.FreeTextAnnotation-) | 访问/选择自由文本注释。 |
| [visit(HighlightAnnotation highlight)](#visit-com.aspose.pdf.HighlightAnnotation-) | 访问/选择突出显示注释。 |
| [visit(InkAnnotation ink)](#visit-com.aspose.pdf.InkAnnotation-) | 访问/选择墨迹注释。 |
| [visit(LineAnnotation line)](#visit-com.aspose.pdf.LineAnnotation-) | 访问/选择行注释。 |
| [visit(LinkAnnotation link)](#visit-com.aspose.pdf.LinkAnnotation-) | 访问/选择链接注释。 |
| [visit(MovieAnnotation movie)](#visit-com.aspose.pdf.MovieAnnotation-) | 访问/选择电影注释。 |
| [visit(PolygonAnnotation polygon)](#visit-com.aspose.pdf.PolygonAnnotation-) | 访问/选择多边形注释。 |
| [visit(PolylineAnnotation polyline)](#visit-com.aspose.pdf.PolylineAnnotation-) | 访问/选择折线注释。 |
| [visit(PopupAnnotation popup)](#visit-com.aspose.pdf.PopupAnnotation-) | 访问/选择弹出注释。 |
| [visit(ScreenAnnotation screen)](#visit-com.aspose.pdf.ScreenAnnotation-) | 访问/选择屏幕注释。 |
| [visit(SquareAnnotation square)](#visit-com.aspose.pdf.SquareAnnotation-) | 访问/选择方形注释。 |
| [visit(SquigglyAnnotation squiggly)](#visit-com.aspose.pdf.SquigglyAnnotation-) | 访问/选择波浪注释。 |
| [visit(StampAnnotation stamp)](#visit-com.aspose.pdf.StampAnnotation-) | 访问/选择邮票注释。 |
| [visit(StrikeOutAnnotation strikeOut)](#visit-com.aspose.pdf.StrikeOutAnnotation-) | 访问/选择删除线注释。 |
| [visit(TextAnnotation text)](#visit-com.aspose.pdf.TextAnnotation-) | 访问/选择文本注释。 |
| [visit(UnderlineAnnotation underline)](#visit-com.aspose.pdf.UnderlineAnnotation-) | 访问/选择下划线注释。 |
| [visit(WidgetAnnotation widget)](#visit-com.aspose.pdf.WidgetAnnotation-) | 访问/选择小部件注释。 |
### visit(CaretAnnotation caret) {#visit-com.aspose.pdf.CaretAnnotation-}
```
public abstract void visit(CaretAnnotation caret)
```


访问/选择插入符号注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| caret | [CaretAnnotation](../../com.aspose.pdf/caretannotation) | CaretAnnotation 对象示例/模板。 |

### visit(CircleAnnotation circle) {#visit-com.aspose.pdf.CircleAnnotation-}
```
public abstract void visit(CircleAnnotation circle)
```


访问/选择圆圈注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| circle | [CircleAnnotation](../../com.aspose.pdf/circleannotation) | CircleAnnotation 对象示例/模板。 |

### visit(FileAttachmentAnnotation attachment) {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
```
public abstract void visit(FileAttachmentAnnotation attachment)
```


访问/选择附件注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| attachment | [FileAttachmentAnnotation](../../com.aspose.pdf/fileattachmentannotation) | FileAttachmentAnnotation 对象示例/模板。 |

### visit(FreeTextAnnotation freetext) {#visit-com.aspose.pdf.FreeTextAnnotation-}
```
public abstract void visit(FreeTextAnnotation freetext)
```


访问/选择自由文本注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| freetext | [FreeTextAnnotation](../../com.aspose.pdf/freetextannotation) | FreeTextAnnotation 对象示例/模板。 |

### visit(HighlightAnnotation highlight) {#visit-com.aspose.pdf.HighlightAnnotation-}
```
public abstract void visit(HighlightAnnotation highlight)
```


访问/选择突出显示注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| highlight | [HighlightAnnotation](../../com.aspose.pdf/highlightannotation) | HighlightAnnotation 对象示例/模板。 |

### visit(InkAnnotation ink) {#visit-com.aspose.pdf.InkAnnotation-}
```
public abstract void visit(InkAnnotation ink)
```


访问/选择墨迹注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ink | [InkAnnotation](../../com.aspose.pdf/inkannotation) | InkAnnotation 对象示例/模板。 |

### visit(LineAnnotation line) {#visit-com.aspose.pdf.LineAnnotation-}
```
public abstract void visit(LineAnnotation line)
```


访问/选择行注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| line | [LineAnnotation](../../com.aspose.pdf/lineannotation) | LineAnnotation 对象示例/模板。 |

### visit(LinkAnnotation link) {#visit-com.aspose.pdf.LinkAnnotation-}
```
public abstract void visit(LinkAnnotation link)
```


访问/选择链接注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| link | [LinkAnnotation](../../com.aspose.pdf/linkannotation) | LinkAnnotation 对象示例/模板。 |

### visit(MovieAnnotation movie) {#visit-com.aspose.pdf.MovieAnnotation-}
```
public abstract void visit(MovieAnnotation movie)
```


访问/选择电影注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| movie | [MovieAnnotation](../../com.aspose.pdf/movieannotation) | MovieAnnotation 对象示例/模板。 |

### visit(PolygonAnnotation polygon) {#visit-com.aspose.pdf.PolygonAnnotation-}
```
public abstract void visit(PolygonAnnotation polygon)
```


访问/选择多边形注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| polygon | [PolygonAnnotation](../../com.aspose.pdf/polygonannotation) | PolygonAnnotation 对象示例/模板。 |

### visit(PolylineAnnotation polyline) {#visit-com.aspose.pdf.PolylineAnnotation-}
```
public abstract void visit(PolylineAnnotation polyline)
```


访问/选择折线注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| polyline | [PolylineAnnotation](../../com.aspose.pdf/polylineannotation) | PolylineAnnotation 对象示例/模板。 |

### visit(PopupAnnotation popup) {#visit-com.aspose.pdf.PopupAnnotation-}
```
public abstract void visit(PopupAnnotation popup)
```


访问/选择弹出注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| popup | [PopupAnnotation](../../com.aspose.pdf/popupannotation) | PopupAnnotation 对象示例/模板。 |

### visit(ScreenAnnotation screen) {#visit-com.aspose.pdf.ScreenAnnotation-}
```
public abstract void visit(ScreenAnnotation screen)
```


访问/选择屏幕注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| screen | [ScreenAnnotation](../../com.aspose.pdf/screenannotation) | ScreenAnnotation 对象示例/模板。 |

### visit(SquareAnnotation square) {#visit-com.aspose.pdf.SquareAnnotation-}
```
public abstract void visit(SquareAnnotation square)
```


访问/选择方形注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| square | [SquareAnnotation](../../com.aspose.pdf/squareannotation) | SquareAnnotation 对象示例/模板。 |

### visit(SquigglyAnnotation squiggly) {#visit-com.aspose.pdf.SquigglyAnnotation-}
```
public abstract void visit(SquigglyAnnotation squiggly)
```


访问/选择波浪注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| squiggly | [SquigglyAnnotation](../../com.aspose.pdf/squigglyannotation) | SquigglyAnnotation 对象示例/模板。 |

### visit(StampAnnotation stamp) {#visit-com.aspose.pdf.StampAnnotation-}
```
public abstract void visit(StampAnnotation stamp)
```


访问/选择邮票注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stamp | [StampAnnotation](../../com.aspose.pdf/stampannotation) | StampAnnotation 对象示例/模板。 |

### visit(StrikeOutAnnotation strikeOut) {#visit-com.aspose.pdf.StrikeOutAnnotation-}
```
public abstract void visit(StrikeOutAnnotation strikeOut)
```


访问/选择删除线注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| strikeOut | [StrikeOutAnnotation](../../com.aspose.pdf/strikeoutannotation) | StrikeOutAnnotation 对象示例/模板。 |

### visit(TextAnnotation text) {#visit-com.aspose.pdf.TextAnnotation-}
```
public abstract void visit(TextAnnotation text)
```


访问/选择文本注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | [TextAnnotation](../../com.aspose.pdf/textannotation) | TextAnnotation 对象示例/模板。 |

### visit(UnderlineAnnotation underline) {#visit-com.aspose.pdf.UnderlineAnnotation-}
```
public abstract void visit(UnderlineAnnotation underline)
```


访问/选择下划线注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| underline | [UnderlineAnnotation](../../com.aspose.pdf/underlineannotation) | UnderlineAnnotation 对象示例/模板。 |

### visit(WidgetAnnotation widget) {#visit-com.aspose.pdf.WidgetAnnotation-}
```
public abstract void visit(WidgetAnnotation widget)
```


访问/选择小部件注释。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| widget | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) | WidgetAnnotation 对象示例/模板。 |
