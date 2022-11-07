---
title: XForm
second_title: Aspose.PDF for Java API Reference
description: Class represent XForm
type: docs
weight: 323
url: /java/com.aspose.pdf/xform/
---
**Inheritance:**
java.lang.Object
```
public final class XForm
```

Class represent XForm
## Methods

| Method | Description |
| --- | --- |
| [getEngineObj()](#getEngineObj--) |  |
| [getBBox()](#getBBox--) | Gets or sets form bounding box. |
| [setBBox(Rectangle value)](#setBBox-com.aspose.pdf.Rectangle-) |  |
| [getName()](#getName--) | Gets form name. |
| [setName(String value)](#setName-java.lang.String-) | Sets form name. |
| [getContents()](#getContents--) | Gets operators of the form |
| [getMatrix()](#getMatrix--) | Gets matrix of the form. |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.pdf.Matrix-) | Sets matrix of the form. |
| [getResources()](#getResources--) | Gets Form XObject resources. |
| [createNewForm(ITrailerable trailerable)](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | Creates new XForm in the document. |
| [containsOwnResources()](#containsOwnResources--) |  |
| [createNewForm(Page source, ITrailerable trailerable, Copier copier)](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [createNewForm(Page source, IDocument document)](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | Creates XForm which duplicates contents of the page. |
| [getRectangle()](#getRectangle--) |  |
| [getRectangle_Rename_Namesake()](#getRectangle-Rename-Namesake--) |  |
### getEngineObj() {#getEngineObj--}
```
public IPdfObject getEngineObj()
```




**Returns:**
[IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject)
### getBBox() {#getBBox--}
```
public Rectangle getBBox()
```


Gets or sets form bounding box.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### setBBox(Rectangle value) {#setBBox-com.aspose.pdf.Rectangle-}
```
public void setBBox(Rectangle value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### getName() {#getName--}
```
public String getName()
```


Gets form name. Form name is name which used to reference form in XObejct ductionary in page resources.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Sets form name. Form name is name which used to reference form in XObejct ductionary in page resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getContents() {#getContents--}
```
public OperatorCollection getContents()
```


Gets operators of the form

**Returns:**
[OperatorCollection](../../com.aspose.pdf/operatorcollection)
### getMatrix() {#getMatrix--}
```
public Matrix getMatrix()
```


Gets matrix of the form.

**Returns:**
[Matrix](../../com.aspose.pdf/matrix)
### setMatrix(Matrix value) {#setMatrix-com.aspose.pdf.Matrix-}
```
public void setMatrix(Matrix value)
```


Sets matrix of the form.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.pdf/matrix) |  |

### getResources() {#getResources--}
```
public Resources getResources()
```


Gets Form XObject resources.

**Returns:**
[Resources](../../com.aspose.pdf/resources)
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




**Returns:**
boolean
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
public double[] getRectangle()
```




**Returns:**
double[]
### getRectangle_Rename_Namesake() {#getRectangle-Rename-Namesake--}
```
public Rectangle getRectangle_Rename_Namesake()
```




**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
