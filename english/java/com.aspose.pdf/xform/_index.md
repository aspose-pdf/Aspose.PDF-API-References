---
title: XForm
second_title: Aspose.PDF for Java API Reference
description: Class represent XForm
type: docs
weight: 408
url: /java/com.aspose.pdf/xform/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.pdf.ISupportsMemoryCleanup, [com.aspose.pdf.engine.IOperatorContainer](../../com.aspose.pdf.engine/ioperatorcontainer)
```
public final class XForm implements ISupportsMemoryCleanup, IOperatorContainer
```

Class represent XForm
## Methods

| Method | Description |
| --- | --- |
| [getEngineObj()](#getEngineObj--) | Internal only |
| [getBBox()](#getBBox--) | Gets form bounding box. |
| [setBBox(Rectangle value)](#setBBox-com.aspose.pdf.Rectangle-) | Sets form bounding box. |
| [getName()](#getName--) | Gets form name. |
| [setName(String value)](#setName-java.lang.String-) | Sets form name. |
| [getIT()](#getIT--) | Gets form IT. |
| [getSubtype()](#getSubtype--) | Gets form Subtype. |
| [getContents()](#getContents--) | Gets operators of the form. |
| [getOpi()](#getOpi--) | Gets The Open Prepress Interface (OPI). |
| [getMatrix()](#getMatrix--) | Gets matrix of the form. |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.pdf.Matrix-) | Sets matrix of the form. |
| [getResources(boolean allowCreate)](#getResources-boolean-) | Returns resources of Form X-Object |
| [getResources()](#getResources--) | Returns resources of Form X-Object. |
| [getResources2()](#getResources2--) | Gets Form XObject resources. |
| [createNewForm(ITrailerable trailerable)](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | Creates new XForm in the document. |
| [containsOwnResources()](#containsOwnResources--) | Returns True if contains Own Resources |
| [createNewForm(Page source, ITrailerable trailerable, Copier copier)](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [createNewForm(Page source, IDocument document)](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | Creates XForm which duplicates contents of the page. |
| [getRectangle()](#getRectangle--) | Gets rectangel of the form. |
| [freeMemory()](#freeMemory--) | Clears cached data |
### getEngineObj() {#getEngineObj--}
```
public IPdfObject getEngineObj()
```


Internal only

**Returns:**
[IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) - IPdfObject object
### getBBox() {#getBBox--}
```
public Rectangle getBBox()
```


Gets form bounding box.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle
### setBBox(Rectangle value) {#setBBox-com.aspose.pdf.Rectangle-}
```
public void setBBox(Rectangle value)
```


Sets form bounding box.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle |

### getName() {#getName--}
```
public String getName()
```


Gets form name. Form name is name which used to reference form in XObejct ductionary in page resources.

**Returns:**
java.lang.String - String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Sets form name. Form name is name which used to reference form in XObejct dictionary in page resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### getIT() {#getIT--}
```
public final String getIT()
```


Gets form IT. Form IT is a name describing the intent of the XObject.

**Returns:**
java.lang.String
### getSubtype() {#getSubtype--}
```
public final String getSubtype()
```


Gets form Subtype.

**Returns:**
java.lang.String
### getContents() {#getContents--}
```
public OperatorCollection getContents()
```


Gets operators of the form.

**Returns:**
[OperatorCollection](../../com.aspose.pdf/operatorcollection) - OperatorCollection object
### getOpi() {#getOpi--}
```
public Opi getOpi()
```


Gets The Open Prepress Interface (OPI).

**Returns:**
[Opi](../../com.aspose.pdf/opi) - Opi instance
### getMatrix() {#getMatrix--}
```
public Matrix getMatrix()
```


Gets matrix of the form.

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Matrix
### setMatrix(Matrix value) {#setMatrix-com.aspose.pdf.Matrix-}
```
public void setMatrix(Matrix value)
```


Sets matrix of the form.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.pdf/matrix) | Matrix object |

### getResources(boolean allowCreate) {#getResources-boolean-}
```
public final Resources getResources(boolean allowCreate)
```


Returns resources of Form X-Object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| allowCreate | boolean | If For does not have resources and allowCreate is true, Resources will be automatically created for the form. |

**Returns:**
[Resources](../../com.aspose.pdf/resources) - Resources instance
### getResources() {#getResources--}
```
public Resources getResources()
```


Returns resources of Form X-Object. If For does not have resources and allowCreate is true, Resources will be automatically created for the form.

**Returns:**
[Resources](../../com.aspose.pdf/resources) - Resources instance
### getResources2() {#getResources2--}
```
public final Resources getResources2()
```


Gets Form XObject resources.

**Returns:**
[Resources](../../com.aspose.pdf/resources) - Resources instance. If For does not have resources, Resources will be automatically created for the form.
### createNewForm(ITrailerable trailerable) {#createNewForm-com.aspose.pdf.engine.data.ITrailerable-}
```
public static XForm createNewForm(ITrailerable trailerable)
```


Creates new XForm in the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) | Describes ITrailerable object |

**Returns:**
[XForm](../../com.aspose.pdf/xform) - Newly created XForm
### containsOwnResources() {#containsOwnResources--}
```
public boolean containsOwnResources()
```


Returns True if contains Own Resources

**Returns:**
boolean - boolean value
### createNewForm(Page source, ITrailerable trailerable, Copier copier) {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-}
```
public static XForm createNewForm(Page source, ITrailerable trailerable, Copier copier)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [Page](../../com.aspose.pdf/page) |  |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) |  |
| copier | [Copier](../../com.aspose.pdf/copier) |  |

**Returns:**
[XForm](../../com.aspose.pdf/xform)
### createNewForm(Page source, IDocument document) {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
```
public static XForm createNewForm(Page source, IDocument document)
```


Creates XForm which duplicates contents of the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [Page](../../com.aspose.pdf/page) | Source page |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where new XForm will be added. |

**Returns:**
[XForm](../../com.aspose.pdf/xform) - Newly created XForm.
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets rectangel of the form.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle
### freeMemory() {#freeMemory--}
```
public void freeMemory()
```


Clears cached data

