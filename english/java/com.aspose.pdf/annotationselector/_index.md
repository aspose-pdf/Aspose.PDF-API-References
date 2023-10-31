---
title: AnnotationSelector
second_title: Aspose.PDF for Java API Reference
description: This class is used for selecting annotations using Visitor template idea.
type: docs
weight: 18
url: /java/com.aspose.pdf/annotationselector/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.pdf.IAnnotationVisitor](../../com.aspose.pdf/iannotationvisitor)
```
public final class AnnotationSelector implements IAnnotationVisitor
```

This class is used for selecting annotations using Visitor template idea.
## Constructors

| Constructor | Description |
| --- | --- |
| [AnnotationSelector()](#AnnotationSelector--) | Initializes new instance of the AnnotationSelector class. |
| [AnnotationSelector(Annotation annotation)](#AnnotationSelector-com.aspose.pdf.Annotation-) | Initializes new  AnnotationSelector  object. |
## Methods

| Method | Description |
| --- | --- |
| [getSelected()](#getSelected--) | The list of selected objects. |
| [visit(LinkAnnotation link)](#visit-com.aspose.pdf.LinkAnnotation-) | Select link annotation if AnnotationSelector was initialized with LinkAnnotation object. |
| [visit(FileAttachmentAnnotation attachment)](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | Select attachment annotation if AnnotationSelector was initialized with FileAttachmentAnnotation object. |
| [visit(TextAnnotation text)](#visit-com.aspose.pdf.TextAnnotation-) | Select text annotation if AnnotationSelector was initialized with TextAnnotation object. |
| [visit(RedactionAnnotation redact)](#visit-com.aspose.pdf.RedactionAnnotation-) | Select redact annotation if AnnotationSelector was initialized with RedactAnnotation object. |
| [visit(FreeTextAnnotation freetext)](#visit-com.aspose.pdf.FreeTextAnnotation-) | Select freetext annotation if AnnotationSelector was initialized with FreeTextAnnotation object. |
| [visit(HighlightAnnotation highlight)](#visit-com.aspose.pdf.HighlightAnnotation-) | Select attachment annotation if AnnotationSelector was initialized with FreeTextAnnotation object. |
| [visit(UnderlineAnnotation underline)](#visit-com.aspose.pdf.UnderlineAnnotation-) | Select underline annotation if AnnotationSelector was initialized with UnderlineAnnotation object. |
| [visit(StrikeOutAnnotation strikeOut)](#visit-com.aspose.pdf.StrikeOutAnnotation-) | Select strikeOut annotation if AnnotationSelector was initialized with StrikeOutAnnotation object. |
| [visit(SquigglyAnnotation squiggly)](#visit-com.aspose.pdf.SquigglyAnnotation-) | Select squiggly annotation if AnnotationSelector was initialized with SquigglyAnnotation object. |
| [visit(PopupAnnotation popup)](#visit-com.aspose.pdf.PopupAnnotation-) | Select popup annotation if AnnotationSelector was initialized with PopupAnnotation object. |
| [visit(LineAnnotation line)](#visit-com.aspose.pdf.LineAnnotation-) | Select line annotation if AnnotationSelector was initialized with LineAnnotation object. |
| [visit(CircleAnnotation circle)](#visit-com.aspose.pdf.CircleAnnotation-) | Select circle annotation if AnnotationSelector was initialized with CircleAnnotation object. |
| [visit(SquareAnnotation square)](#visit-com.aspose.pdf.SquareAnnotation-) | Select square annotation if AnnotationSelector was initialized with SquareAnnotation object. |
| [visit(InkAnnotation ink)](#visit-com.aspose.pdf.InkAnnotation-) | Select ink annotation if AnnotationSelector was initialized with InkAnnotation object. |
| [visit(PolylineAnnotation polyline)](#visit-com.aspose.pdf.PolylineAnnotation-) | Select polyline annotation if AnnotationSelector was initialized with PolylineAnnotation object. |
| [visit(PolygonAnnotation polygon)](#visit-com.aspose.pdf.PolygonAnnotation-) | Select polygon annotation if AnnotationSelector was initialized with PolygonAnnotation object. |
| [visit(CaretAnnotation caret)](#visit-com.aspose.pdf.CaretAnnotation-) | Select caret annotation if AnnotationSelector was initialized with CaretAnnotation object. |
| [visit(StampAnnotation stamp)](#visit-com.aspose.pdf.StampAnnotation-) | Select stamp annotation if AnnotationSelector was initialized with StampAnnotation object. |
| [visit(WidgetAnnotation widget)](#visit-com.aspose.pdf.WidgetAnnotation-) | Select widget annotation if AnnotationSelector was initialized with WidgetAnnotation object. |
| [visit(WatermarkAnnotation watermark)](#visit-com.aspose.pdf.WatermarkAnnotation-) | Select watermark annotation if AnnotationSelector was initialized with WatermarkAnnotation object. |
| [visit(MovieAnnotation movie)](#visit-com.aspose.pdf.MovieAnnotation-) | Select movie annotation if AnnotationSelector was initialized with MovieAnnotation object. |
| [visit(RichMediaAnnotation richMedia)](#visit-com.aspose.pdf.RichMediaAnnotation-) | Select movie annotation if AnnotationSelector was initialized with RichMedia annotation object. |
| [visit(ScreenAnnotation screen)](#visit-com.aspose.pdf.ScreenAnnotation-) | Select screen annotation if AnnotationSelector was initialized with ScreenAnnotation object. |
| [visit(PDF3DAnnotation pdf3D)](#visit-com.aspose.pdf.PDF3DAnnotation-) | Select PDF3D annotation if AnnotationSelector was initialized with PDF3DAnnotation object. |
| [visit(ColorBarAnnotation colorBar)](#visit-com.aspose.pdf.ColorBarAnnotation-) | Select ColorBar annotation if AnnotationSelector was initialized with ColorBar object. |
### AnnotationSelector() {#AnnotationSelector--}
```
public AnnotationSelector()
```


Initializes new instance of the AnnotationSelector class.

### AnnotationSelector(Annotation annotation) {#AnnotationSelector-com.aspose.pdf.Annotation-}
```
public AnnotationSelector(Annotation annotation)
```


Initializes new  AnnotationSelector  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Annotation to be selected. This object only describes some characteristics we want found annotations to have, e.g. the type of annotation. |

### getSelected() {#getSelected--}
```
public List<Annotation> getSelected()
```


The list of selected objects.

**Returns:**
java.util.List<com.aspose.pdf.Annotation> - List of Annotation instances
### visit(LinkAnnotation link) {#visit-com.aspose.pdf.LinkAnnotation-}
```
public void visit(LinkAnnotation link)
```


Select link annotation if AnnotationSelector was initialized with LinkAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| link | [LinkAnnotation](../../com.aspose.pdf/linkannotation) | LinkAnnotation object for selecting. |

### visit(FileAttachmentAnnotation attachment) {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
```
public void visit(FileAttachmentAnnotation attachment)
```


Select attachment annotation if AnnotationSelector was initialized with FileAttachmentAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attachment | [FileAttachmentAnnotation](../../com.aspose.pdf/fileattachmentannotation) | FileAttachmentAnnotation object for selecting. |

### visit(TextAnnotation text) {#visit-com.aspose.pdf.TextAnnotation-}
```
public void visit(TextAnnotation text)
```


Select text annotation if AnnotationSelector was initialized with TextAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | [TextAnnotation](../../com.aspose.pdf/textannotation) | TextAnnotation object for selecting. |

### visit(RedactionAnnotation redact) {#visit-com.aspose.pdf.RedactionAnnotation-}
```
public void visit(RedactionAnnotation redact)
```


Select redact annotation if AnnotationSelector was initialized with RedactAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| redact | [RedactionAnnotation](../../com.aspose.pdf/redactionannotation) | RedactAnnotation object for selecting. |

### visit(FreeTextAnnotation freetext) {#visit-com.aspose.pdf.FreeTextAnnotation-}
```
public void visit(FreeTextAnnotation freetext)
```


Select freetext annotation if AnnotationSelector was initialized with FreeTextAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| freetext | [FreeTextAnnotation](../../com.aspose.pdf/freetextannotation) | FreeTextAnnotation object for selecting. |

### visit(HighlightAnnotation highlight) {#visit-com.aspose.pdf.HighlightAnnotation-}
```
public void visit(HighlightAnnotation highlight)
```


Select attachment annotation if AnnotationSelector was initialized with FreeTextAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| highlight | [HighlightAnnotation](../../com.aspose.pdf/highlightannotation) | HighlightAnnotation object for selecting. |

### visit(UnderlineAnnotation underline) {#visit-com.aspose.pdf.UnderlineAnnotation-}
```
public void visit(UnderlineAnnotation underline)
```


Select underline annotation if AnnotationSelector was initialized with UnderlineAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| underline | [UnderlineAnnotation](../../com.aspose.pdf/underlineannotation) | UnderlineAnnotation object for selecting. |

### visit(StrikeOutAnnotation strikeOut) {#visit-com.aspose.pdf.StrikeOutAnnotation-}
```
public void visit(StrikeOutAnnotation strikeOut)
```


Select strikeOut annotation if AnnotationSelector was initialized with StrikeOutAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| strikeOut | [StrikeOutAnnotation](../../com.aspose.pdf/strikeoutannotation) | StrikeOutAnnotation object for selecting. |

### visit(SquigglyAnnotation squiggly) {#visit-com.aspose.pdf.SquigglyAnnotation-}
```
public void visit(SquigglyAnnotation squiggly)
```


Select squiggly annotation if AnnotationSelector was initialized with SquigglyAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| squiggly | [SquigglyAnnotation](../../com.aspose.pdf/squigglyannotation) | SquigglyAnnotation object for selecting. |

### visit(PopupAnnotation popup) {#visit-com.aspose.pdf.PopupAnnotation-}
```
public void visit(PopupAnnotation popup)
```


Select popup annotation if AnnotationSelector was initialized with PopupAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| popup | [PopupAnnotation](../../com.aspose.pdf/popupannotation) | PopupAnnotation object for selecting. |

### visit(LineAnnotation line) {#visit-com.aspose.pdf.LineAnnotation-}
```
public void visit(LineAnnotation line)
```


Select line annotation if AnnotationSelector was initialized with LineAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| line | [LineAnnotation](../../com.aspose.pdf/lineannotation) | LineAnnotation object for selecting. |

### visit(CircleAnnotation circle) {#visit-com.aspose.pdf.CircleAnnotation-}
```
public void visit(CircleAnnotation circle)
```


Select circle annotation if AnnotationSelector was initialized with CircleAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| circle | [CircleAnnotation](../../com.aspose.pdf/circleannotation) | CircleAnnotation object for selecting. |

### visit(SquareAnnotation square) {#visit-com.aspose.pdf.SquareAnnotation-}
```
public void visit(SquareAnnotation square)
```


Select square annotation if AnnotationSelector was initialized with SquareAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| square | [SquareAnnotation](../../com.aspose.pdf/squareannotation) | SquareAnnotation object for selecting. |

### visit(InkAnnotation ink) {#visit-com.aspose.pdf.InkAnnotation-}
```
public void visit(InkAnnotation ink)
```


Select ink annotation if AnnotationSelector was initialized with InkAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ink | [InkAnnotation](../../com.aspose.pdf/inkannotation) | InkAnnotation object for selecting. |

### visit(PolylineAnnotation polyline) {#visit-com.aspose.pdf.PolylineAnnotation-}
```
public void visit(PolylineAnnotation polyline)
```


Select polyline annotation if AnnotationSelector was initialized with PolylineAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| polyline | [PolylineAnnotation](../../com.aspose.pdf/polylineannotation) | PolylineAnnotation object for selecting. |

### visit(PolygonAnnotation polygon) {#visit-com.aspose.pdf.PolygonAnnotation-}
```
public void visit(PolygonAnnotation polygon)
```


Select polygon annotation if AnnotationSelector was initialized with PolygonAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| polygon | [PolygonAnnotation](../../com.aspose.pdf/polygonannotation) | PolygonAnnotation object for selecting. |

### visit(CaretAnnotation caret) {#visit-com.aspose.pdf.CaretAnnotation-}
```
public void visit(CaretAnnotation caret)
```


Select caret annotation if AnnotationSelector was initialized with CaretAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| caret | [CaretAnnotation](../../com.aspose.pdf/caretannotation) | CaretAnnotation object for selecting. |

### visit(StampAnnotation stamp) {#visit-com.aspose.pdf.StampAnnotation-}
```
public void visit(StampAnnotation stamp)
```


Select stamp annotation if AnnotationSelector was initialized with StampAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stamp | [StampAnnotation](../../com.aspose.pdf/stampannotation) | StampAnnotation object for selecting. |

### visit(WidgetAnnotation widget) {#visit-com.aspose.pdf.WidgetAnnotation-}
```
public void visit(WidgetAnnotation widget)
```


Select widget annotation if AnnotationSelector was initialized with WidgetAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| widget | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) | WidgetAnnotation object for selecting. |

### visit(WatermarkAnnotation watermark) {#visit-com.aspose.pdf.WatermarkAnnotation-}
```
public void visit(WatermarkAnnotation watermark)
```


Select watermark annotation if AnnotationSelector was initialized with WatermarkAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [WatermarkAnnotation](../../com.aspose.pdf/watermarkannotation) | WatermarkAnnotation for selecting. |

### visit(MovieAnnotation movie) {#visit-com.aspose.pdf.MovieAnnotation-}
```
public void visit(MovieAnnotation movie)
```


Select movie annotation if AnnotationSelector was initialized with MovieAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| movie | [MovieAnnotation](../../com.aspose.pdf/movieannotation) | MovieAnnotation object for selecting. |

### visit(RichMediaAnnotation richMedia) {#visit-com.aspose.pdf.RichMediaAnnotation-}
```
public void visit(RichMediaAnnotation richMedia)
```


Select movie annotation if AnnotationSelector was initialized with RichMedia annotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| richMedia | [RichMediaAnnotation](../../com.aspose.pdf/richmediaannotation) | RichMedia annotation. |

### visit(ScreenAnnotation screen) {#visit-com.aspose.pdf.ScreenAnnotation-}
```
public void visit(ScreenAnnotation screen)
```


Select screen annotation if AnnotationSelector was initialized with ScreenAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| screen | [ScreenAnnotation](../../com.aspose.pdf/screenannotation) | ScreenAnnotation object for selecting. |

### visit(PDF3DAnnotation pdf3D) {#visit-com.aspose.pdf.PDF3DAnnotation-}
```
public void visit(PDF3DAnnotation pdf3D)
```


Select PDF3D annotation if AnnotationSelector was initialized with PDF3DAnnotation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdf3D | [PDF3DAnnotation](../../com.aspose.pdf/pdf3dannotation) | PDF3DAnnotation object for selecting. |

### visit(ColorBarAnnotation colorBar) {#visit-com.aspose.pdf.ColorBarAnnotation-}
```
public final void visit(ColorBarAnnotation colorBar)
```


Select ColorBar annotation if AnnotationSelector was initialized with ColorBar object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorBar | [ColorBarAnnotation](../../com.aspose.pdf/colorbarannotation) | PDF3DAnnotation object for selecting. |

