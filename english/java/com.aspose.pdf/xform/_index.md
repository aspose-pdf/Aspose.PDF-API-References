---
title: XForm
linktitle: XForm
second_title: Aspose.PDF for Java API Reference
description: Class represent XForm
type: docs
weight: 5590
url: /java/com.aspose.pdf/xform/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XForm

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer

```
public final class XForm extends Object implements com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer
```

Class represent XForm

## Methods

| Method | Description |
| --- | --- |
| [close](#close--) | Frees up memory |
| [containsOwnResources](#containsOwnResources--) | Returns True if contains Own Resources |
| [createNewForm](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | Creates new XForm in the document. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | Creates XForm which duplicates contents of the page. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [dispose](#dispose--) | Frees up memory |
| [freeMemory](#freeMemory--) | Clears cached data |
| [getBBox](#getBBox--) | Gets form bounding box. |
| [getContents](#getContents--) | Gets operators of the form. |
| [getEngineObj](#getEngineObj--) | Internal only |
| [getIT](#getIT--) | Gets form IT. Form IT is a name describing the intent of the XObject. |
| [getMatrix](#getMatrix--) | Gets matrix of the form. |
| [getName](#getName--) | Gets form name. Form name is name which used to reference form in XObejct ductionary in page resources. |
| [getOpi](#getOpi--) | Gets The Open Prepress Interface (OPI). |
| [getRectangle](#getRectangle--) | Gets rectangel of the form. |
| [getResources](#getResources--) | Returns resources of Form X-Object. If For does not have resources and allowCreate is true, Resources will be automatically created for the form. |
| [getResources](#getResources-boolean-) | Returns resources of Form X-Object |
| [getResourcesField](#getResourcesField--) | Gets Form XObject resources. |
| [getSubtype](#getSubtype--) | Gets form Subtype. |
| [setBBox](#setBBox-com.aspose.pdf.Rectangle-) | Sets form bounding box. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Sets matrix of the form. |
| [setName](#setName-java.lang.String-) | Sets form name. Form name is name which used to reference form in XObejct dictionary in page resources. |

### close {#close--}
```
public final void close()
```

Frees up memory

### containsOwnResources {#containsOwnResources--}
```
public boolean containsOwnResources()
```

Returns True if contains Own Resources

**Returns:**
boolean value

### createNewForm {#createNewForm-com.aspose.pdf.engine.data.ITrailerable-}
Creates new XForm in the document.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
Creates XForm which duplicates contents of the page.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-}


### dispose {#dispose--}
```
public final void dispose()
```

Frees up memory

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Clears cached data

### getBBox {#getBBox--}
```
public Rectangle getBBox()
```

Gets form bounding box.

**Returns:**
Rectangle

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

Gets operators of the form.

**Returns:**
OperatorCollection object

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Internal only

**Returns:**
IPdfObject object

### getIT {#getIT--}
```
public final String getIT()
```

Gets form IT. Form IT is a name describing the intent of the XObject.

**Returns:**
String value

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Gets matrix of the form.

**Returns:**
Matrix

### getName {#getName--}
```
public String getName()
```

Gets form name. Form name is name which used to reference form in XObejct ductionary in page resources.

**Returns:**
String

### getOpi {#getOpi--}
```
public Opi getOpi()
```

Gets The Open Prepress Interface (OPI).

**Returns:**
Opi instance

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Gets rectangel of the form.

**Returns:**
Rectangle

### getResources {#getResources--}
```
public Resources getResources()
```

Returns resources of Form X-Object. If For does not have resources and allowCreate is true, Resources will be automatically created for the form.

**Returns:**
Resources instance

### getResources {#getResources-boolean-}
```
public final Resources getResources(boolean allowCreate)
```

Returns resources of Form X-Object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| allowCreate |  | If For does not have resources and allowCreate is true, Resources will be automatically created for the form. |

**Returns:**
Resources instance

### getResourcesField {#getResourcesField--}
```
public final Resources getResourcesField()
```

Gets Form XObject resources.

**Returns:**
Resources instance. If For does not have resources, Resources will be automatically created for the form.

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

Gets form Subtype.

**Returns:**
String value

### setBBox {#setBBox-com.aspose.pdf.Rectangle-}
Sets form bounding box.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Sets matrix of the form.

### setName {#setName-java.lang.String-}
Sets form name. Form name is name which used to reference form in XObejct dictionary in page resources.
