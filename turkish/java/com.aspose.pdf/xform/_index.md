---
title: "XForm"
linktitle: "XForm"
second_title: "Aspose.PDF for Java API Referansı"
description: "XForm'u temsil eden sınıf"
type: docs
weight: 5590
url: /tr/java/com.aspose.pdf/xform/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XForm

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer

```
public final class XForm extends Object implements com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer
```

XForm'u temsil eden sınıf

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [close](#close--) | Belleği serbest bırakır |
| [containsOwnResources](#containsOwnResources--) | Own Resources içeriyorsa True döndürür |
| [createNewForm](#createNewForm-com.aspose.pdf.engine.data.ITrailerable-) | Belge içinde yeni bir XForm oluşturur. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-) | Sayfanın içeriğini kopyalayan bir XForm oluşturur. |
| [createNewForm](#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-) |  |
| [dispose](#dispose--) | Belleği serbest bırakır |
| [freeMemory](#freeMemory--) | Önbelleğe alınmış verileri temizler |
| [getBBox](#getBBox--) | Formun sınırlayıcı kutusunu alır. |
| [getContents](#getContents--) | Formun operatörlerini alır. |
| [getEngineObj](#getEngineObj--) | Yalnızca dahili |
| [getIT](#getIT--) | Form IT'yi alır. Form IT, XObject'in amacını tanımlayan bir isimdir. |
| [getMatrix](#getMatrix--) | Formun matrisini alır. |
| [getName](#getName--) | Form adını alır. Form adı, sayfa kaynaklarındaki XObejct sözlüğünde formu referanslamak için kullanılan isimdir. |
| [getOpi](#getOpi--) | Açık Ön Baskı Arayüzü (OPI)'yi alır. |
| [getRectangle](#getRectangle--) | Formun dikdörtgenini alır. |
| [getResources](#getResources--) | Form X-Object'in kaynaklarını döndürür. Formun kaynakları yoksa ve allowCreate true ise, kaynaklar form için otomatik olarak oluşturulur. |
| [getResources](#getResources-boolean-) | Form X-Object'in kaynaklarını döndürür |
| [getResourcesField](#getResourcesField--) | Form XObject kaynaklarını alır. |
| [getSubtype](#getSubtype--) | Form alt tipini alır. |
| [setBBox](#setBBox-com.aspose.pdf.Rectangle-) | Formun sınırlayıcı kutusunu ayarlar. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Formun matrisini ayarlar. |
| [setName](#setName-java.lang.String-) | Form adını ayarlar. Form adı, sayfa kaynaklarındaki XObejct sözlüğünde formu referanslamak için kullanılan isimdir. |

### close {#close--}
```
public final void close()
```

Belleği serbest bırakır

### containsOwnResources {#containsOwnResources--}
```
public boolean containsOwnResources()
```

Own Resources içeriyorsa True döndürür

**Returns:**
boolean değer

### createNewForm {#createNewForm-com.aspose.pdf.engine.data.ITrailerable-}
Belge içinde yeni bir XForm oluşturur.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.IDocument-}
Sayfanın içeriğini kopyalayan bir XForm oluşturur.

### createNewForm {#createNewForm-com.aspose.pdf.Page-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.Copier-}


### dispose {#dispose--}
```
public final void dispose()
```

Belleği serbest bırakır

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Önbelleğe alınmış verileri temizler

### getBBox {#getBBox--}
```
public Rectangle getBBox()
```

Formun sınırlayıcı kutusunu alır.

**Returns:**
Rectangle

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

Formun operatörlerini alır.

**Returns:**
OperatorCollection nesnesi

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Yalnızca dahili

**Returns:**
IPdfObject nesnesi

### getIT {#getIT--}
```
public final String getIT()
```

Form IT'yi alır. Form IT, XObject'in amacını tanımlayan bir isimdir.

**Returns:**
String değeri

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Formun matrisini alır.

**Returns:**
Matris

### getName {#getName--}
```
public String getName()
```

Form adını alır. Form adı, sayfa kaynaklarındaki XObejct sözlüğünde formu referanslamak için kullanılan isimdir.

**Returns:**
Dize

### getOpi {#getOpi--}
```
public Opi getOpi()
```

Açık Ön Baskı Arayüzü (OPI)'yi alır.

**Returns:**
Opi örneği

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Formun dikdörtgenini alır.

**Returns:**
Rectangle

### getResources {#getResources--}
```
public Resources getResources()
```

Form X-Object'in kaynaklarını döndürür. Formun kaynakları yoksa ve allowCreate true ise, kaynaklar form için otomatik olarak oluşturulur.

**Returns:**
Resources örneği

### getResources {#getResources-boolean-}
```
public final Resources getResources(boolean allowCreate)
```

Form X-Object'in kaynaklarını döndürür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| allowCreate |  | Formun kaynakları yoksa ve allowCreate true ise, kaynaklar form için otomatik olarak oluşturulur. |

**Returns:**
Resources örneği

### getResourcesField {#getResourcesField--}
```
public final Resources getResourcesField()
```

Form XObject kaynaklarını alır.

**Returns:**
Resources örneği. Formun kaynakları yoksa, kaynaklar form için otomatik olarak oluşturulur.

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

Form alt tipini alır.

**Returns:**
String değeri

### setBBox {#setBBox-com.aspose.pdf.Rectangle-}
Formun sınırlayıcı kutusunu ayarlar.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Formun matrisini ayarlar.

### setName {#setName-java.lang.String-}
Form adını ayarlar. Form adı, sayfa kaynaklarındaki XObejct sözlüğünde formu referanslamak için kullanılan isimdir.
