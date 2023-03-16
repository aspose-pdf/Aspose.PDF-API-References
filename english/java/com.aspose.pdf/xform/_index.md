---
title: XForm
second_title: Aspose.PDF for Java API Reference
description: Class represent XForm
type: docs
weight: 405
url: /java/com.aspose.pdf/xform/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.pdf.ISupportsMemoryCleanup
```
public final class XForm implements ISupportsMemoryCleanup
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
| [getContents()](#getContents--) | Gets operators of the form. |
| [getOpi()](#getOpi--) | Gets The Open Prepress Interface (OPI). |
| [getMatrix()](#getMatrix--) | Gets matrix of the form. |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.pdf.Matrix-) | Sets matrix of the form. |
| [getResources(boolean allowCreate)](#getResources-boolean-) | Returns resources of Form X-Object |
| [getResources()](#getResources--) | Returns resources of Form X-Object. |
| [getResources2()](#getResources2--) | Gets Form XObject resources. |
| [containsOwnResources()](#containsOwnResources--) | Returns True if contains Own Resources |
| [createNewForm(Page source, IDocument document)](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | Creates XForm which duplicates contents of the page. |
| [getRectangle()](#getRectangle--) | Gets rectangel of the form. |
| [freeMemory()](#freeMemory--) | Clears cached data |
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
### containsOwnResources() {#containsOwnResources--}
```
public boolean containsOwnResources()
```


Returns True if contains Own Resources

**Returns:**
boolean - boolean value
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

