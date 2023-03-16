---
title: Annotation
second_title: Aspose.PDF for Java API Reference
description: Class representing annotation object.
type: docs
weight: 15
url: /java/com.aspose.pdf/annotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public abstract class Annotation extends BaseParagraph
```

Class representing annotation object.
## Methods

| Method | Description |
| --- | --- |
| [initialize(IDocument doc)](#initialize-com.aspose.pdf.IDocument-) | Instance initialization |
| [getEngineObj()](#getEngineObj--) | For Internal usage only |
| [getEngineDict()](#getEngineDict--) | Internal only |
| [isUpdateAppearanceOnConvert()](#isUpdateAppearanceOnConvert--) | If true, annotation appearance will be updated before converting PF document into image. |
| [setUpdateAppearanceOnConvert(boolean value)](#setUpdateAppearanceOnConvert-boolean-) | If true, annotation appearance will be updated before converting PF document into image. |
| [isUseFontSubset()](#isUseFontSubset--) | If this property set to true, fonts will be added to document as subsets. |
| [setUseFontSubset(boolean value)](#setUseFontSubset-boolean-) | If this property set to true, fonts will be added to document as subsets. |
| [getNormalAppearance()](#getNormalAppearance--) | Gets normal appearance. |
| [getFlags()](#getFlags--) | Get flags of the annotation. |
| [setFlags(int value)](#setFlags-int-) | Set flags of the annotation. |
| [getPage()](#getPage--) | Gets the page object with which this annotation is associated. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [getWidth()](#getWidth--) | Gets width of the annotation. |
| [setWidth(double value)](#setWidth-double-) | Sets width of the annotation. |
| [getPdfActions()](#getPdfActions--) | Gets list of annotation actions. |
| [getHeight()](#getHeight--) | Gets height of the annotation. |
| [setHeight(double value)](#setHeight-double-) | Sets height of the annotation. |
| [getRect()](#getRect--) | Gets annotation rectangle. |
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) | Sets annotation rectangle. |
| [getRectangle(boolean considerRotation)](#getRectangle-boolean-) | Returns rectangle of annotation taking into consideration page rotation. |
| [getContents()](#getContents--) | Gets annotation text. |
| [setContents(String value)](#setContents-java.lang.String-) | Sets annotation text. |
| [getName()](#getName--) | Gets annotation name on the page. |
| [setName(String value)](#setName-java.lang.String-) | Sets annotation name on the page. |
| [getModifiedInternal()](#getModifiedInternal--) | Gets date and time when annotation was recently modified. |
| [getModified()](#getModified--) | Gets date and time when annotation was recently modified. |
| [setModifiedInternal(System.DateTime value)](#setModifiedInternal-com.aspose.ms.System.DateTime-) | Sets date and time when annotation was recently modified. |
| [setModified(Date value)](#setModified-java.util.Date-) | Sets date and time when annotation was recently modified. |
| [getColor()](#getColor--) | Gets annotation color. |
| [setColor(Color value)](#setColor-com.aspose.pdf.Color-) | Sets annotation color. |
| [getBorder()](#getBorder--) | Gets annotation border characteristics. |
| [setBorder(Border value)](#setBorder-com.aspose.pdf.Border-) | Sets annotation border characteristics. |
| [getActiveState()](#getActiveState--) | Gets current annotation appearance state. |
| [setActiveState(String value)](#setActiveState-java.lang.String-) | Sets current annotation appearance state. |
| [getCharacteristics()](#getCharacteristics--) | Gets annotation characteristics. |
| [getStates()](#getStates--) | Gets appearance dictionary of annotation. |
| [getAlignment()](#getAlignment--) | Annotation alignment. |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.pdf.TextAlignment-) | Annotation alignment. |
| [getHorizontalAlignment_Annotation_New()](#getHorizontalAlignment-Annotation-New--) | Gets or sets text alignment for annotation. |
| [setHorizontalAlignment_Annotation_New(HorizontalAlignment value)](#setHorizontalAlignment-Annotation-New-com.aspose.pdf.HorizontalAlignment-) | Gets or sets text alignment for annotation. |
| [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Gets text alignment for annotation. |
| [setTextHorizontalAlignment(HorizontalAlignment value)](#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets text alignmennt for annotation. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor for annotation processing. |
| [flatten()](#flatten--) | Places annotation contents directly on the page, annotation object will be removed. |
| [getFullName()](#getFullName--) | Gets full qualified name of the annotation. |
| [getAppearance()](#getAppearance--) | Gets appearance dictionary of the annotation. |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | Update parameters and appearance, according to the matrix transform. |
| [getPageIndex()](#getPageIndex--) | Gets index of page which contains annotation. |
| [getPageIndex(Annotation annotation)](#getPageIndex-com.aspose.pdf.Annotation-) | Gets index of page which contains annotation. |
### initialize(IDocument doc) {#initialize-com.aspose.pdf.IDocument-}
```
public void initialize(IDocument doc)
```


Instance initialization

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | IDocument object |

### isUpdateAppearanceOnConvert() {#isUpdateAppearanceOnConvert--}
```
public static synchronized boolean isUpdateAppearanceOnConvert()
```


If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time.

**Returns:**
boolean - boolean value
### setUpdateAppearanceOnConvert(boolean value) {#setUpdateAppearanceOnConvert-boolean-}
```
public static synchronized void setUpdateAppearanceOnConvert(boolean value)
```


If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isUseFontSubset() {#isUseFontSubset--}
```
public static synchronized boolean isUseFontSubset()
```


If this property set to true, fonts will be added to document as subsets. Default value is true.

**Returns:**
boolean - boolean value
### setUseFontSubset(boolean value) {#setUseFontSubset-boolean-}
```
public static synchronized void setUseFontSubset(boolean value)
```


If this property set to true, fonts will be added to document as subsets. Default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getNormalAppearance() {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```


Gets normal appearance.

**Returns:**
[XForm](../../com.aspose.pdf/xform) - XForm object
### getFlags() {#getFlags--}
```
public int getFlags()
```


Get flags of the annotation.

**Returns:**
int - Flags of the annotation
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Set flags of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | flags of the annotation |

### getPage() {#getPage--}
```
public Page getPage()
```


Gets the page object with which this annotation is associated.

**Returns:**
[Page](../../com.aspose.pdf/page) - Page object
### getAnnotationType() {#getAnnotationType--}
```
public abstract AnnotationType getAnnotationType()
```


Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - int value
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets width of the annotation.

**Returns:**
double - double value, width of the annotation.
### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets width of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | width of the annotation. |

### getPdfActions() {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```


Gets list of annotation actions.

**Returns:**
[PdfActionCollection](../../com.aspose.pdf/pdfactioncollection) - PdfActionCollection instance
### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets height of the annotation.

**Returns:**
double - height of the annotation
### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Sets height of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | height of the annotation |

### getRect() {#getRect--}
```
public Rectangle getRect()
```


Gets annotation rectangle.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### setRect(Rectangle value) {#setRect-com.aspose.pdf.Rectangle-}
```
public void setRect(Rectangle value)
```


Sets annotation rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle value |

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
### getContents() {#getContents--}
```
public String getContents()
```


Gets annotation text.

**Returns:**
java.lang.String - String value
### setContents(String value) {#setContents-java.lang.String-}
```
public void setContents(String value)
```


Sets annotation text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getName() {#getName--}
```
public String getName()
```


Gets annotation name on the page.

**Returns:**
java.lang.String - String value
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Sets annotation name on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getModifiedInternal() {#getModifiedInternal--}
```
public System.DateTime getModifiedInternal()
```


Gets date and time when annotation was recently modified.

**Returns:**
com.aspose.ms.System.DateTime - DateTime object
### getModified() {#getModified--}
```
public Date getModified()
```


Gets date and time when annotation was recently modified.

**Returns:**
[Date](../../java.util/date) - date and time when annotation was recently modified.
### setModifiedInternal(System.DateTime value) {#setModifiedInternal-com.aspose.ms.System.DateTime-}
```
public void setModifiedInternal(System.DateTime value)
```


Sets date and time when annotation was recently modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.DateTime | DateTime object |

### setModified(Date value) {#setModified-java.util.Date-}
```
public void setModified(Date value)
```


Sets date and time when annotation was recently modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date object |

### getColor() {#getColor--}
```
public Color getColor()
```


Gets annotation color.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object
### setColor(Color value) {#setColor-com.aspose.pdf.Color-}
```
public void setColor(Color value)
```


Sets annotation color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color value |

### getBorder() {#getBorder--}
```
public Border getBorder()
```


Gets annotation border characteristics.  Border 

**Returns:**
[Border](../../com.aspose.pdf/border) - Border object
### setBorder(Border value) {#setBorder-com.aspose.pdf.Border-}
```
public void setBorder(Border value)
```


Sets annotation border characteristics.  Border 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Border](../../com.aspose.pdf/border) | Border value |

### getActiveState() {#getActiveState--}
```
public String getActiveState()
```


Gets current annotation appearance state.

**Returns:**
java.lang.String - String value
### setActiveState(String value) {#setActiveState-java.lang.String-}
```
public void setActiveState(String value)
```


Sets current annotation appearance state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getCharacteristics() {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```


Gets annotation characteristics.

**Returns:**
[Characteristics](../../com.aspose.pdf/characteristics) - Characteristics object
### getStates() {#getStates--}
```
public AppearanceDictionary getStates()
```


Gets appearance dictionary of annotation.

**Returns:**
[AppearanceDictionary](../../com.aspose.pdf/appearancedictionary) - AppearanceDictionary object
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Annotation alignment. This property is obsolete. Use getHorizontalAlignment\_Annotation\_New instead.

**Returns:**
[TextAlignment](../../com.aspose.pdf/textalignment) - TextAlignment element
### setAlignment(TextAlignment value) {#setAlignment-com.aspose.pdf.TextAlignment-}
```
public void setAlignment(TextAlignment value)
```


Annotation alignment. This property is obsolete. Use getHorizontalAlignment\_Annotation\_New instead.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.pdf/textalignment) | TextAlignment element |

### getHorizontalAlignment_Annotation_New() {#getHorizontalAlignment-Annotation-New--}
```
public final HorizontalAlignment getHorizontalAlignment_Annotation_New()
```


Gets or sets text alignment for annotation.

**Returns:**
[HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) - text alignment for annotation.
### setHorizontalAlignment_Annotation_New(HorizontalAlignment value) {#setHorizontalAlignment-Annotation-New-com.aspose.pdf.HorizontalAlignment-}
```
public final void setHorizontalAlignment_Annotation_New(HorizontalAlignment value)
```


Gets or sets text alignment for annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) | text alignmennt for annotation. |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public HorizontalAlignment getTextHorizontalAlignment()
```


Gets text alignment for annotation.

**Returns:**
[HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) - text alignment for annotation.
### setTextHorizontalAlignment(HorizontalAlignment value) {#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
```
public void setTextHorizontalAlignment(HorizontalAlignment value)
```


Sets text alignmennt for annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HorizontalAlignment](../../com.aspose.pdf/horizontalalignment) | text alignmennt for annotation. |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public abstract void accept(AnnotationSelector visitor)
```


Accepts visitor for annotation processing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | AnnotationSelector object. |

### flatten() {#flatten--}
```
public void flatten()
```


Places annotation contents directly on the page, annotation object will be removed.

### getFullName() {#getFullName--}
```
public String getFullName()
```


Gets full qualified name of the annotation.

**Returns:**
java.lang.String - String value
### getAppearance() {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```


Gets appearance dictionary of the annotation.

**Returns:**
[AppearanceDictionary](../../com.aspose.pdf/appearancedictionary) - AppearanceDictionary object
### changeAfterResize(Matrix transform) {#changeAfterResize-com.aspose.pdf.Matrix-}
```
public void changeAfterResize(Matrix transform)
```


Update parameters and appearance, according to the matrix transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.pdf/matrix) | Matrix that use for transformation (resize). |

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
