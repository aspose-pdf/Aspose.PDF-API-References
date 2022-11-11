---
title: PolygonAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class representing polygon annotation.
type: docs
weight: 288
url: /java/com.aspose.pdf/polygonannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation), [com.aspose.pdf.PolyAnnotation](../../com.aspose.pdf/polyannotation)
```
public final class PolygonAnnotation extends PolyAnnotation
```

Class representing polygon annotation.
## Constructors

| Constructor | Description |
| --- | --- |
| [PolygonAnnotation(IDocument document, Point[] vertices)](#PolygonAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point---) | Constructor for using with Generator. |
| [PolygonAnnotation(Page page, Rectangle rect, Point[] vertices)](#PolygonAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point---) | Creates new Polygon annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object for annotation processing. |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | Updates the points in Vertices, according to the matrix transform. |
| [createAnnotation(IPdfObject annotEngineObj, Page page)](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | For internal usage only |
| [deepClone()](#deepClone--) | Clones this instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Places annotation contents directly on the page, annotation object will be removed. |
| [getActiveState()](#getActiveState--) | Gets current annotation appearance state. |
| [getAlignment()](#getAlignment--) | Annotation alignment. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [getAppearance()](#getAppearance--) | Gets appearance dictionary of the annotation. |
| [getBorder()](#getBorder--) | Gets annotation border characteristics. |
| [getCharacteristics()](#getCharacteristics--) | Gets annotation characteristics. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Gets annotation color. |
| [getContents()](#getContents--) | Gets annotation text. |
| [getCreationDate()](#getCreationDate--) | Gets date and time when annotation was created. |
| [getEndingStyle()](#getEndingStyle--) | Gets the style of second line ending. |
| [getEngineDict()](#getEngineDict--) | Internal only |
| [getEngineObj()](#getEngineObj--) | For Internal usage only |
| [getFlags()](#getFlags--) | Get flags of the annotation. |
| [getFullName()](#getFullName--) | Gets full qualified name of the annotation. |
| [getHeight()](#getHeight--) | Gets height of the annotation. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets a horizontal alignment of paragraph |
| [getHorizontalAlignment_Annotation_New()](#getHorizontalAlignment-Annotation-New--) | Gets or sets text alignment for annotation. |
| [getHyperlink()](#getHyperlink--) | Gets the fragment hyperlink(for pdf generator). |
| [getInReplyTo()](#getInReplyTo--) | A reference to the annotation that this annotation is "in reply to". |
| [getIntent()](#getIntent--) | Gets the intent of the polygon or polyline annotation. |
| [getInteriorColor()](#getInteriorColor--) | Gets the interior color with which to fill the annotation's line endings. |
| [getMargin()](#getMargin--) | Gets a outer margin for paragraph (for pdf generation) |
| [getMeasure()](#getMeasure--) | Measure units specified for this annotation. |
| [getModified()](#getModified--) | Gets date and time when annotation was recently modified. |
| [getModifiedInternal()](#getModifiedInternal--) | Gets date and time when annotation was recently modified. |
| [getName()](#getName--) | Gets annotation name on the page. |
| [getNormalAppearance()](#getNormalAppearance--) | Gets normal appearance. |
| [getOpacity()](#getOpacity--) | Gets the constant opacity value to be used in painting the annotation. |
| [getPage()](#getPage--) | Gets the page object with which this annotation is associated. |
| [getPageIndex()](#getPageIndex--) | Gets index of page which contains annotation. |
| [getPageIndex(Annotation annotation)](#getPageIndex-com.aspose.pdf.Annotation-) | Gets index of page which contains annotation. |
| [getPdfActions()](#getPdfActions--) | Gets list of annotation actions. |
| [getPopup()](#getPopup--) | Pop-up annotation for entering or editing the text associated with this annotation. |
| [getRect()](#getRect--) | Gets annotation rectangle. |
| [getRectangle(boolean considerRotation)](#getRectangle-boolean-) | Returns rectangle of annotation taking into consideration page rotation. |
| [getReplyType()](#getReplyType--) | A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo. |
| [getRichText()](#getRichText--) | Gets a rich text string to be displayed in the pop-up window when the annotation is opened. |
| [getStartingStyle()](#getStartingStyle--) | Gets the style of first line ending. |
| [getStates()](#getStates--) | Gets appearance dictionary of annotation. |
| [getSubject()](#getSubject--) | Gets text representing desciption of the object. |
| [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Gets text alignment for annotation. |
| [getTitle()](#getTitle--) | Gets a text that shall be displayed in title bar of annotation. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets a vertical alignment of paragraph |
| [getVertices()](#getVertices--) | Gets an array of points representing the horizontal and vertical coordinates of each vertex. |
| [getWidth()](#getWidth--) | Gets width of the annotation. |
| [getZIndex()](#getZIndex--) | Gets an int value that indicates the Z-order of the graph. |
| [hashCode()](#hashCode--) |  |
| [initialize(IDocument doc)](#initialize-com.aspose.pdf.IDocument-) | Instance initialization |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [isInLineParagraph()](#isInLineParagraph--) | Gets a paragraph is inline. |
| [isInNewPage()](#isInNewPage--) | Gets a bool value that force this paragraph generates at new page. |
| [isKeptWithNext()](#isKeptWithNext--) | Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [isUpdateAppearanceOnConvert()](#isUpdateAppearanceOnConvert--) | If true, annotation appearance will be updated before converting PF document into image. |
| [isUseFontSubset()](#isUseFontSubset--) | If this property set to true, fonts will be added to document as subsets. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActiveState(String value)](#setActiveState-java.lang.String-) | Sets current annotation appearance state. |
| [setAlignment(int value)](#setAlignment-int-) | Annotation alignment. |
| [setBorder(Border value)](#setBorder-com.aspose.pdf.Border-) | Sets annotation border characteristics. |
| [setColor(Color value)](#setColor-com.aspose.pdf.Color-) | Sets annotation color. |
| [setContents(String value)](#setContents-java.lang.String-) | Sets annotation text. |
| [setEndingStyle(int value)](#setEndingStyle-int-) | Sets the style of second line ending. |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [setFlags(int value)](#setFlags-int-) | Set flags of the annotation. |
| [setHeight(double value)](#setHeight-double-) | Sets height of the annotation. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets a horizontal alignment of paragraph |
| [setHorizontalAlignment_Annotation_New(int value)](#setHorizontalAlignment-Annotation-New-int-) | Gets or sets text alignment for annotation. |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Sets hyperlink(for pdf generator). |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Sets a paragraph is inline. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Sets a boolean value that force this paragraph generates at new page. |
| [setInReplyTo(Annotation value)](#setInReplyTo-com.aspose.pdf.Annotation-) | A reference to the annotation that this annotation is "in reply to". |
| [setIntent(int value)](#setIntent-int-) | Sets the intent of the polygon or polyline annotation. |
| [setInteriorColor(Color value)](#setInteriorColor-com.aspose.pdf.Color-) | Sets the interior color with which to fill the annotation's line endings. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Sets a outer margin for paragraph (for pdf generation) |
| [setMeasure(Measure value)](#setMeasure-com.aspose.pdf.Measure-) | Measure units specified for this annotation. |
| [setModified(Date value)](#setModified-java.util.Date-) | Sets date and time when annotation was recently modified. |
| [setModifiedInternal(System.DateTime value)](#setModifiedInternal-com.aspose.ms.System.DateTime-) | Sets date and time when annotation was recently modified. |
| [setName(String value)](#setName-java.lang.String-) | Sets annotation name on the page. |
| [setOpacity(double value)](#setOpacity-double-) | Sets the constant opacity value to be used in painting the annotation. |
| [setPopup(PopupAnnotation value)](#setPopup-com.aspose.pdf.PopupAnnotation-) | Pop-up annotation for entering or editing the text associated with this annotation. |
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) | Sets annotation rectangle. |
| [setReplyType(int value)](#setReplyType-int-) | A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo. |
| [setRichText(String value)](#setRichText-java.lang.String-) | Sets a rich text string to be displayed in the pop-up window when the annotation is opened. |
| [setStartingStyle(int value)](#setStartingStyle-int-) | Sets the style of first line ending. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets text representing desciption of the object. |
| [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Sets text alignmennt for annotation. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets a text that shall be displayed in title bar of annotation. |
| [setUpdateAppearanceOnConvert(boolean value)](#setUpdateAppearanceOnConvert-boolean-) | If true, annotation appearance will be updated before converting PF document into image. |
| [setUseFontSubset(boolean value)](#setUseFontSubset-boolean-) | If this property set to true, fonts will be added to document as subsets. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets a vertical alignment of paragraph |
| [setVertices(Point[] value)](#setVertices-com.aspose.pdf.Point---) | Sets an array of points representing the horizontal and vertical coordinates of each vertex. |
| [setWidth(double value)](#setWidth-double-) | Sets width of the annotation. |
| [setZIndex(int value)](#setZIndex-int-) | Sets a int value that indicates the Z-order of the graph. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolygonAnnotation(IDocument document, Point[] vertices) {#PolygonAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point---}
```
public PolygonAnnotation(IDocument document, Point[] vertices)
```


Constructor for using with Generator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where annotation will be added. |
| vertices | [Point\[\]](../../com.aspose.pdf/point) | Array of points. |

### PolygonAnnotation(Page page, Rectangle rect, Point[] vertices) {#PolygonAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point---}
```
public PolygonAnnotation(Page page, Rectangle rect, Point[] vertices)
```


Creates new Polygon annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |
| vertices | [Point\[\]](../../com.aspose.pdf/point) | An array of polygon vertices points. |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object for annotation processing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

### changeAfterResize(Matrix transform) {#changeAfterResize-com.aspose.pdf.Matrix-}
```
public void changeAfterResize(Matrix transform)
```


Updates the points in Vertices, according to the matrix transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.pdf/matrix) | Matrix specifying the transformation. |

### createAnnotation(IPdfObject annotEngineObj, Page page) {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
```
public static Annotation createAnnotation(IPdfObject annotEngineObj, Page page)
```


For internal usage only

Initializes annotation from PDF object which describes the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotEngineObj | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) | PDF object describing annotation |
| page | [Page](../../com.aspose.pdf/page) | Page object |

**Returns:**
[Annotation](../../com.aspose.pdf/annotation) - Created annotation object of appropriate type
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones this instance. Virtual method. Always return null.

**Returns:**
java.lang.Object - Null
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### flatten() {#flatten--}
```
public void flatten()
```


Places annotation contents directly on the page, annotation object will be removed.

### getActiveState() {#getActiveState--}
```
public String getActiveState()
```


Gets current annotation appearance state.

**Returns:**
java.lang.String - String value
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Annotation alignment. This property is obsolete. Use getHorizontalAlignment\_Annotation\_New instead.

**Returns:**
int - TextAlignment element
### getAnnotationType() {#getAnnotationType--}
```
public int getAnnotationType()
```


Gets type of annotation.

**Returns:**
int - AnnotationType element
### getAppearance() {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```


Gets appearance dictionary of the annotation.

**Returns:**
[AppearanceDictionary](../../com.aspose.pdf/appearancedictionary) - AppearanceDictionary object
### getBorder() {#getBorder--}
```
public Border getBorder()
```


Gets annotation border characteristics.  Border 

**Returns:**
[Border](../../com.aspose.pdf/border) - Border object
### getCharacteristics() {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```


Gets annotation characteristics.

**Returns:**
[Characteristics](../../com.aspose.pdf/characteristics) - Characteristics object
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Gets annotation color.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object
### getContents() {#getContents--}
```
public String getContents()
```


Gets annotation text.

**Returns:**
java.lang.String - String value
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Gets date and time when annotation was created.

**Returns:**
[Date](../../java.util/date) - Date object
### getEndingStyle() {#getEndingStyle--}
```
public int getEndingStyle()
```


Gets the style of second line ending.

**Returns:**
int - LineEnding element
### getEngineDict() {#getEngineDict--}
```
public IPdfDictionary getEngineDict()
```


Internal only

**Returns:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) - IPdfDictionary object
### getEngineObj() {#getEngineObj--}
```
public IPdfObject getEngineObj()
```


For Internal usage only

**Returns:**
[IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) - Internal onject
### getFlags() {#getFlags--}
```
public int getFlags()
```


Get flags of the annotation.

**Returns:**
int - Flags of the annotation
### getFullName() {#getFullName--}
```
public String getFullName()
```


Gets full qualified name of the annotation.

**Returns:**
java.lang.String - String value
### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets height of the annotation.

**Returns:**
double - height of the annotation
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets a horizontal alignment of paragraph

**Returns:**
int - HorizontalAlignment value
### getHorizontalAlignment_Annotation_New() {#getHorizontalAlignment-Annotation-New--}
```
public final int getHorizontalAlignment_Annotation_New()
```


Gets or sets text alignment for annotation.

**Returns:**
int - text alignment for annotation.
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


Gets the fragment hyperlink(for pdf generator).

**Returns:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - the fragment hyperlink(for pdf generator).
### getInReplyTo() {#getInReplyTo--}
```
public Annotation getInReplyTo()
```


A reference to the annotation that this annotation is "in reply to". Both annotations must be on the same page of the document.

**Returns:**
[Annotation](../../com.aspose.pdf/annotation) - Annotation value
### getIntent() {#getIntent--}
```
public int getIntent()
```


Gets the intent of the polygon or polyline annotation.

**Returns:**
int - PolyIntent element
### getInteriorColor() {#getInteriorColor--}
```
public Color getInteriorColor()
```


Gets the interior color with which to fill the annotation's line endings.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets a outer margin for paragraph (for pdf generation)

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo value
### getMeasure() {#getMeasure--}
```
public Measure getMeasure()
```


Measure units specified for this annotation.

**Returns:**
[Measure](../../com.aspose.pdf/measure) - Measure instance
### getModified() {#getModified--}
```
public Date getModified()
```


Gets date and time when annotation was recently modified.

**Returns:**
[Date](../../java.util/date) - date and time when annotation was recently modified.
### getModifiedInternal() {#getModifiedInternal--}
```
public System.DateTime getModifiedInternal()
```


Gets date and time when annotation was recently modified.

**Returns:**
com.aspose.ms.System.DateTime - DateTime object
### getName() {#getName--}
```
public String getName()
```


Gets annotation name on the page.

**Returns:**
java.lang.String - String value
### getNormalAppearance() {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```


Gets normal appearance.

**Returns:**
[XForm](../../com.aspose.pdf/xform) - XForm object
### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


Gets the constant opacity value to be used in painting the annotation.

**Returns:**
double - double value
### getPage() {#getPage--}
```
public Page getPage()
```


Gets the page object with which this annotation is associated.

**Returns:**
[Page](../../com.aspose.pdf/page) - Page object
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Gets index of page which contains annotation.

**Returns:**
int - int value
### getPageIndex(Annotation annotation) {#getPageIndex-com.aspose.pdf.Annotation-}
```
public int getPageIndex(Annotation annotation)
```


Gets index of page which contains annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Annotation object |

**Returns:**
int - int value
### getPdfActions() {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```


Gets list of annotation actions.

**Returns:**
[PdfActionCollection](../../com.aspose.pdf/pdfactioncollection) - PdfActionCollection instance
### getPopup() {#getPopup--}
```
public PopupAnnotation getPopup()
```


Pop-up annotation for entering or editing the text associated with this annotation.

**Returns:**
[PopupAnnotation](../../com.aspose.pdf/popupannotation) - PopupAnnotation value
### getRect() {#getRect--}
```
public Rectangle getRect()
```


Gets annotation rectangle.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### getRectangle(boolean considerRotation) {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```


Returns rectangle of annotation taking into consideration page rotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| considerRotation | boolean | If true, page rotation is taken into consideration. |

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### getReplyType() {#getReplyType--}
```
public int getReplyType()
```


A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo.

**Returns:**
int - ReplyType value
### getRichText() {#getRichText--}
```
public String getRichText()
```


Gets a rich text string to be displayed in the pop-up window when the annotation is opened.

**Returns:**
java.lang.String - String value
### getStartingStyle() {#getStartingStyle--}
```
public int getStartingStyle()
```


Gets the style of first line ending.

**Returns:**
int - LineEnding element
### getStates() {#getStates--}
```
public AppearanceDictionary getStates()
```


Gets appearance dictionary of annotation.

**Returns:**
[AppearanceDictionary](../../com.aspose.pdf/appearancedictionary) - AppearanceDictionary object
### getSubject() {#getSubject--}
```
public String getSubject()
```


Gets text representing desciption of the object.

**Returns:**
java.lang.String - String value
### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public int getTextHorizontalAlignment()
```


Gets text alignment for annotation.

**Returns:**
int - text alignment for annotation.
### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets a text that shall be displayed in title bar of annotation.

**Returns:**
java.lang.String - String value
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Gets a vertical alignment of paragraph

**Returns:**
int - VerticalAlignment element
### getVertices() {#getVertices--}
```
public Point[] getVertices()
```


Gets an array of points representing the horizontal and vertical coordinates of each vertex.

**Returns:**
com.aspose.pdf.Point[] - array of Point value
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets width of the annotation.

**Returns:**
double - double value, width of the annotation.
### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


Gets an int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Returns:**
int - int value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initialize(IDocument doc) {#initialize-com.aspose.pdf.IDocument-}
```
public void initialize(IDocument doc)
```


Instance initialization

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | IDocument object |

### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


Gets a paragraph is inline. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isUpdateAppearanceOnConvert() {#isUpdateAppearanceOnConvert--}
```
public static synchronized boolean isUpdateAppearanceOnConvert()
```


If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time.

**Returns:**
boolean - boolean value
### isUseFontSubset() {#isUseFontSubset--}
```
public static synchronized boolean isUseFontSubset()
```


If this property set to true, fonts will be added to document as subsets. Default value is true.

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setActiveState(String value) {#setActiveState-java.lang.String-}
```
public void setActiveState(String value)
```


Sets current annotation appearance state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Annotation alignment. This property is obsolete. Use getHorizontalAlignment\_Annotation\_New instead.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | TextAlignment element |

### setBorder(Border value) {#setBorder-com.aspose.pdf.Border-}
```
public void setBorder(Border value)
```


Sets annotation border characteristics.  Border 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Border](../../com.aspose.pdf/border) | Border value |

### setColor(Color value) {#setColor-com.aspose.pdf.Color-}
```
public void setColor(Color value)
```


Sets annotation color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color value |

### setContents(String value) {#setContents-java.lang.String-}
```
public void setContents(String value)
```


Sets annotation text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setEndingStyle(int value) {#setEndingStyle-int-}
```
public void setEndingStyle(int value)
```


Sets the style of second line ending.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | LineEnding element |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Set flags of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | flags of the annotation |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Sets height of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | height of the annotation |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Sets a horizontal alignment of paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment value |

### setHorizontalAlignment_Annotation_New(int value) {#setHorizontalAlignment-Annotation-New-int-}
```
public final void setHorizontalAlignment_Annotation_New(int value)
```


Gets or sets text alignment for annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | text alignmennt for annotation. |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


Sets hyperlink(for pdf generator).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | hyperlink(for pdf generator). |

### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


Sets a paragraph is inline. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


Sets a boolean value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setInReplyTo(Annotation value) {#setInReplyTo-com.aspose.pdf.Annotation-}
```
public void setInReplyTo(Annotation value)
```


A reference to the annotation that this annotation is "in reply to". Both annotations must be on the same page of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Annotation](../../com.aspose.pdf/annotation) | Annotation value |

### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


Sets the intent of the polygon or polyline annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PolyIntent element |

### setInteriorColor(Color value) {#setInteriorColor-com.aspose.pdf.Color-}
```
public void setInteriorColor(Color value)
```


Sets the interior color with which to fill the annotation's line endings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color object |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Sets a outer margin for paragraph (for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### setMeasure(Measure value) {#setMeasure-com.aspose.pdf.Measure-}
```
public void setMeasure(Measure value)
```


Measure units specified for this annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Measure](../../com.aspose.pdf/measure) | Measure instance |

### setModified(Date value) {#setModified-java.util.Date-}
```
public void setModified(Date value)
```


Sets date and time when annotation was recently modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date object |

### setModifiedInternal(System.DateTime value) {#setModifiedInternal-com.aspose.ms.System.DateTime-}
```
public void setModifiedInternal(System.DateTime value)
```


Sets date and time when annotation was recently modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.DateTime | DateTime object |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Sets annotation name on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


Sets the constant opacity value to be used in painting the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setPopup(PopupAnnotation value) {#setPopup-com.aspose.pdf.PopupAnnotation-}
```
public void setPopup(PopupAnnotation value)
```


Pop-up annotation for entering or editing the text associated with this annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PopupAnnotation](../../com.aspose.pdf/popupannotation) | PopupAnnotation value |

### setRect(Rectangle value) {#setRect-com.aspose.pdf.Rectangle-}
```
public void setRect(Rectangle value)
```


Sets annotation rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle value |

### setReplyType(int value) {#setReplyType-int-}
```
public void setReplyType(int value)
```


A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ReplyType value |

### setRichText(String value) {#setRichText-java.lang.String-}
```
public void setRichText(String value)
```


Sets a rich text string to be displayed in the pop-up window when the annotation is opened.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setStartingStyle(int value) {#setStartingStyle-int-}
```
public void setStartingStyle(int value)
```


Sets the style of first line ending.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | LineEnding element |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Sets text representing desciption of the object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public void setTextHorizontalAlignment(int value)
```


Sets text alignmennt for annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | text alignmennt for annotation. |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Sets a text that shall be displayed in title bar of annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setUpdateAppearanceOnConvert(boolean value) {#setUpdateAppearanceOnConvert-boolean-}
```
public static synchronized void setUpdateAppearanceOnConvert(boolean value)
```


If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setUseFontSubset(boolean value) {#setUseFontSubset-boolean-}
```
public static synchronized void setUseFontSubset(boolean value)
```


If this property set to true, fonts will be added to document as subsets. Default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Sets a vertical alignment of paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment element |

### setVertices(Point[] value) {#setVertices-com.aspose.pdf.Point---}
```
public void setVertices(Point[] value)
```


Sets an array of points representing the horizontal and vertical coordinates of each vertex.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.pdf/point) | array of Point value |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets width of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | width of the annotation. |

### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex(int value)
```


Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

