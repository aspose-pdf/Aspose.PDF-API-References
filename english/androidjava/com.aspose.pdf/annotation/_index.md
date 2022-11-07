---
title: Annotation
second_title: Aspose.PDF for Java API Reference
description: Class representing annotation object.
type: docs
weight: 14
url: /java/com.aspose.pdf/annotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public abstract class Annotation extends BaseParagraph
```

Class representing annotation object.
## Fields

| Field | Description |
| --- | --- |
| [_disableUpdateAppearance](#-disableUpdateAppearance) |  |
## Methods

| Method | Description |
| --- | --- |
| [initialize(IDocument doc)](#initialize-com.aspose.pdf.IDocument-) |  |
| [getEngineObj()](#getEngineObj--) |  |
| [getEngineDict()](#getEngineDict--) |  |
| [getNormalAppearance()](#getNormalAppearance--) | Gets normal appearance. |
| [getFlags()](#getFlags--) | Returns flags of the a. |
| [setFlags(int value)](#setFlags-int-) | Sets flags of the annotation. |
| [getPage()](#getPage--) | Gets the page object with which this annotation is associated. |
| [getWidth()](#getWidth--) | Gets or sets width of the annotation. |
| [setWidth(double value)](#setWidth-double-) | Sets width of the annotation. |
| [getHeight()](#getHeight--) | Gets or sets height of the annotation. |
| [setHeight(double value)](#setHeight-double-) | Sets annotation height. |
| [getRect()](#getRect--) | Gets or sets annotation rectangle. |
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) |  |
| [getContents()](#getContents--) | Gets or sets annotation text. |
| [setContents(String value)](#setContents-java.lang.String-) |  |
| [getName()](#getName--) | Gets or sets annotation name on the page. |
| [setName(String value)](#setName-java.lang.String-) |  |
| [getModifiedInternal()](#getModifiedInternal--) | Gets date and time when annotation was recently modified. |
| [getModified()](#getModified--) |  |
| [setModifiedInternal(Object value)](#setModifiedInternal-java.lang.Object-) | Sets date and time when annotation was recently modified. |
| [setModified(Date value)](#setModified-java.util.Date-) |  |
| [getColor()](#getColor--) | Gets annotation color. |
| [setColor(Color value)](#setColor-com.aspose.pdf.Color-) | Sets annotation color. |
| [getBorder()](#getBorder--) | Gets annotation border characteristics. |
| [setBorder(Border value)](#setBorder-com.aspose.pdf.Border-) | Sets annotation border characteristics. |
| [getActiveState()](#getActiveState--) | Gets current annotation appearance state. |
| [setActiveState(String value)](#setActiveState-java.lang.String-) | Sets current annotation appearance state. |
| [getCharacteristics()](#getCharacteristics--) | Gets annotation characteristics. |
| [getStates()](#getStates--) | Gets appearance dictionary of annotation. |
| [getAlignment()](#getAlignment--) | Gets or sets text alignmennt for annotation. |
| [setAlignment(int value)](#setAlignment-int-) | Sets text alignmennt for annotation. |
| [getHorizontalAlignment_Annotation_New()](#getHorizontalAlignment-Annotation-New--) | Gets or sets text alignmennt for annotation. |
| [setHorizontalAlignment_Annotation_New(int value)](#setHorizontalAlignment-Annotation-New-int-) | Sets value of horizontal alignment. |
| [createAnnotation(IPdfObject annotEngineObj, Page page)](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | Initializes annotation from PDF object which describes the annotation. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor for annotation processing. |
| [flatten()](#flatten--) | Places annotation contents directly on the page, annotation object will be removed. |
| [getFullName()](#getFullName--) | Gets full qualified name of the annotation. |
| [getAppearance()](#getAppearance--) | Gets appearance dictionary of the annotation. |
| [getPageIndex()](#getPageIndex--) | Gets index of page which contains annotation. |
| [getPageIndex(Annotation annotation)](#getPageIndex-com.aspose.pdf.Annotation-) |  |
### _disableUpdateAppearance {#-disableUpdateAppearance}
```
public boolean _disableUpdateAppearance
```


### initialize(IDocument doc) {#initialize-com.aspose.pdf.IDocument-}
```
public void initialize(IDocument doc)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) |  |

### getEngineObj() {#getEngineObj--}
```
public IPdfObject getEngineObj()
```




**Returns:**
[IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject)
### getEngineDict() {#getEngineDict--}
```
public IPdfDictionary getEngineDict()
```




**Returns:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary)
### getNormalAppearance() {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```


Gets normal appearance.

**Returns:**
[XForm](../../com.aspose.pdf/xform) - Normal appearance form.
### getFlags() {#getFlags--}
```
public int getFlags()
```


Returns flags of the a.

**Returns:**
int - Flags of the annotation.
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Sets flags of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | New flags value. |

### getPage() {#getPage--}
```
public Page getPage()
```


Gets the page object with which this annotation is associated.

**Returns:**
[Page](../../com.aspose.pdf/page) - Page object where annotation is placed.
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets or sets width of the annotation.

**Returns:**
double - Width of the annotation.
### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets width of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | New width value. |

### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets or sets height of the annotation.

**Returns:**
double - Annotation height.
### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Sets annotation height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | New annotation height. |

### getRect() {#getRect--}
```
public Rectangle getRect()
```


Gets or sets annotation rectangle.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle of the annotation.
### setRect(Rectangle value) {#setRect-com.aspose.pdf.Rectangle-}
```
public void setRect(Rectangle value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### getContents() {#getContents--}
```
public String getContents()
```


Gets or sets annotation text.

**Returns:**
java.lang.String - Text of the annotation.
### setContents(String value) {#setContents-java.lang.String-}
```
public void setContents(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public String getName()
```


Gets or sets annotation name on the page.

**Returns:**
java.lang.String - Name of the annotation.
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getModifiedInternal() {#getModifiedInternal--}
```
public System.DateTime getModifiedInternal()
```


Gets date and time when annotation was recently modified.

**Returns:**
com.aspose.ms.System.DateTime - Date and time of annotation modification.
### getModified() {#getModified--}
```
public Date getModified()
```




**Returns:**
[Date](../../java.util/date)
### setModifiedInternal(Object value) {#setModifiedInternal-java.lang.Object-}
```
public void setModifiedInternal(Object value)
```


Sets date and time when annotation was recently modified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | Date and time of annotation modification. |

### setModified(Date value) {#setModified-java.util.Date-}
```
public void setModified(Date value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getColor() {#getColor--}
```
public Color getColor()
```


Gets annotation color.

**Returns:**
[Color](../../com.aspose.pdf/color) - Annotation color.
### setColor(Color value) {#setColor-com.aspose.pdf.Color-}
```
public void setColor(Color value)
```


Sets annotation color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | New color. |

### getBorder() {#getBorder--}
```
public Border getBorder()
```


Gets annotation border characteristics.  Border 

**Returns:**
[Border](../../com.aspose.pdf/border) - Border of the annotation.
### setBorder(Border value) {#setBorder-com.aspose.pdf.Border-}
```
public void setBorder(Border value)
```


Sets annotation border characteristics.  Border 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Border](../../com.aspose.pdf/border) | New annotation border characteristics. |

### getActiveState() {#getActiveState--}
```
public String getActiveState()
```


Gets current annotation appearance state.

**Returns:**
java.lang.String - String with annotation appearance state.
### setActiveState(String value) {#setActiveState-java.lang.String-}
```
public void setActiveState(String value)
```


Sets current annotation appearance state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | New active state value. |

### getCharacteristics() {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```


Gets annotation characteristics.

**Returns:**
[Characteristics](../../com.aspose.pdf/characteristics) - Annotation characteristics.
### getStates() {#getStates--}
```
public AppearanceDictionary getStates()
```


Gets appearance dictionary of annotation.

**Returns:**
[AppearanceDictionary](../../com.aspose.pdf/appearancedictionary) - AppearanceDictionary object which contains states of the annotation.
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Gets or sets text alignmennt for annotation.

**Returns:**
int - Text alignment.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Sets text alignmennt for annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | New annotation text alignment. |

### getHorizontalAlignment_Annotation_New() {#getHorizontalAlignment-Annotation-New--}
```
public int getHorizontalAlignment_Annotation_New()
```


Gets or sets text alignmennt for annotation.

**Returns:**
int - Horizntal alignment.
### setHorizontalAlignment_Annotation_New(int value) {#setHorizontalAlignment-Annotation-New-int-}
```
public void setHorizontalAlignment_Annotation_New(int value)
```


Sets value of horizontal alignment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | New horizontal alignment. |

### createAnnotation(IPdfObject annotEngineObj, Page page) {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
```
public static Annotation createAnnotation(IPdfObject annotEngineObj, Page page)
```


Initializes annotation from PDF object which describes the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotEngineObj | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) | PDF obejct describing annotation |
| page | [Page](../../com.aspose.pdf/page) |  |

**Returns:**
[Annotation](../../com.aspose.pdf/annotation) - Created annotation object of appropriate type
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public abstract void accept(AnnotationSelector visitor)
```


Accepts visitor for annotation processing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor for annotation processing. |

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
java.lang.String - Fully qualified name of the annotation.
### getAppearance() {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```


Gets appearance dictionary of the annotation.

**Returns:**
[AppearanceDictionary](../../com.aspose.pdf/appearancedictionary) - Annotation appearance.
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Gets index of page which contains annotation.

**Returns:**
int - Page index.
### getPageIndex(Annotation annotation) {#getPageIndex-com.aspose.pdf.Annotation-}
```
public int getPageIndex(Annotation annotation)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) |  |

**Returns:**
int
