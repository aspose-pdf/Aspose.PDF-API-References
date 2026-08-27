---
title: "XForm"
linktitle: "XForm"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen representerar XForm"
type: docs
weight: 5590
url: /sv/java/com.aspose.pdf/xform/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XForm

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer

```
public final class XForm extends Object implements com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer
```

Klassen representerar XForm

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close](#close--) | Frigör minne |
| [containsOwnResources](#containsOwnResources--) | Returnerar True om den innehåller egna resurser. |
| [createNewForm](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | Skapar en ny XForm i dokumentet. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | Skapar XForm som duplicerar sidans innehåll. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [dispose](#dispose--) | Frigör minne |
| [freeMemory](#freeMemory--) | Rensar cachad data |
| [getBBox](#getBBox--) | Hämtar formulärets avgränsningsruta. |
| [getContents](#getContents--) | Hämtar formulärets operatorer. |
| [getEngineObj](#getEngineObj--) | Endast intern |
| [getIT](#getIT--) | Hämtar formulärets IT. Form IT är ett namn som beskriver avsikten med XObject. |
| [getMatrix](#getMatrix--) | Hämtar formulärets matris. |
| [getName](#getName--) | Hämtar formulärets namn. Formulärets namn är det namn som används för att referera till formuläret i XObject-ordlistan i sidresurserna. |
| [getOpi](#getOpi--) | Hämtar Open Prepress Interface (OPI). |
| [getRectangle](#getRectangle--) | Hämtar rektangel för formuläret. |
| [getResources](#getResources--) | Returnerar resurser för Form X-Object. Om For inte har resurser och allowCreate är true, kommer Resources automatiskt att skapas för formuläret. |
| [getResources](#getResources-boolean-) | Returnerar resurser för Form X-Object |
| [getResourcesField](#getResourcesField--) | Hämtar Form XObject-resurser. |
| [getSubtype](#getSubtype--) | Hämtar formulärets subtyp. |
| [setBBox](#setBBox-com.aspose.pdf.Rectangle-) | Ställer in formulärets begränsningsruta. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Ställer in matrisen för formuläret. |
| [setName](#setName-java.lang.String-) | Ställer in formulärets namn. Form name är namnet som används för att referera till formuläret i XObejct-ordboken i sidresurser. |

### close {#close--}
```
public final void close()
```

Frigör minne

### containsOwnResources {#containsOwnResources--}
```
public boolean containsOwnResources()
```

Returnerar True om den innehåller egna resurser.

**Returns:**
booleskt värde

### createNewForm {#createNewForm-com.aspose.pdf.engine.data.ITrailerable-}
Skapar en ny XForm i dokumentet.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
Skapar XForm som duplicerar sidans innehåll.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-}


### dispose {#dispose--}
```
public final void dispose()
```

Frigör minne

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Rensar cachad data

### getBBox {#getBBox--}
```
public Rectangle getBBox()
```

Hämtar formulärets avgränsningsruta.

**Returns:**
Rectangle

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

Hämtar formulärets operatorer.

**Returns:**
OperatorCollection-objekt

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Endast intern

**Returns:**
IPdfObject‑objekt

### getIT {#getIT--}
```
public final String getIT()
```

Hämtar formulärets IT. Form IT är ett namn som beskriver avsikten med XObject.

**Returns:**
String värde

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Hämtar formulärets matris.

**Returns:**
Matrix

### getName {#getName--}
```
public String getName()
```

Hämtar formulärets namn. Formulärets namn är det namn som används för att referera till formuläret i XObject-ordlistan i sidresurserna.

**Returns:**
String

### getOpi {#getOpi--}
```
public Opi getOpi()
```

Hämtar Open Prepress Interface (OPI).

**Returns:**
Opi-instans

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Hämtar rektangel för formuläret.

**Returns:**
Rectangle

### getResources {#getResources--}
```
public Resources getResources()
```

Returnerar resurser för Form X-Object. Om For inte har resurser och allowCreate är true, kommer Resources automatiskt att skapas för formuläret.

**Returns:**
Resources-instans

### getResources {#getResources-boolean-}
```
public final Resources getResources(boolean allowCreate)
```

Returnerar resurser för Form X-Object

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| allowCreate |  | Om For inte har resurser och allowCreate är true, kommer Resources automatiskt att skapas för formuläret. |

**Returns:**
Resources-instans

### getResourcesField {#getResourcesField--}
```
public final Resources getResourcesField()
```

Hämtar Form XObject-resurser.

**Returns:**
Resources-instans. Om For inte har resurser, kommer Resources automatiskt att skapas för formuläret.

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

Hämtar formulärets subtyp.

**Returns:**
String värde

### setBBox {#setBBox-com.aspose.pdf.Rectangle-}
Ställer in formulärets begränsningsruta.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Ställer in matrisen för formuläret.

### setName {#setName-java.lang.String-}
Ställer in formulärets namn. Form name är namnet som används för att referera till formuläret i XObejct-ordboken i sidresurser.
