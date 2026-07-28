---
title: "PdfXmpMetadata"
linktitle: "PdfXmpMetadata"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase para manipular metadatos XMP."
type: docs
weight: 620
url: /es/java/com.aspose.pdf.facades/pdfxmpmetadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfXmpMetadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class PdfXmpMetadata extends SaveableFacade implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

Clase para manipular metadatos XMP.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfXmpMetadata](#PdfXmpMetadata--) | <p> Constructor de PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |
| [PdfXmpMetadata](#PdfXmpMetadata-com.aspose.pdf.IDocument-) | <p> Constructor de PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-) | Agrega un campo de extensión a los metadatos. |
| [addItem](#addItem-int-com.aspose.pdf.XmpValue-) | <p> Agrega un valor a los metadatos XMP. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre> |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Agrega un par con clave y valor al diccionario. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Agrega un nuevo elemento al objeto diccionario. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | <p> Agrega un nuevo elemento al objeto diccionario. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre> |
| [clear](#clear--) | <p> Elimina todos los elementos del objeto. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre> |
| [contains](#contains-int-) | Comprueba si el diccionario contiene la propiedad especificada. |
| [contains](#contains-java.lang.String-) | <p> Comprueba si el diccionario contiene la clave especificada. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre> |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Comprueba si el par clave-valor especificado está contenido en el diccionario. |
| [containsKey](#containsKey-java.lang.String-) | Determina si este diccionario contiene la clave especificada. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copia los metadatos en una matriz. |
| [get_Item](#get_Item-java.lang.String-) | <p> Obtiene el valor por clave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [getByDefaultMetadataProperties](#getByDefaultMetadataProperties-int-) | <p> Obtiene el valor de los metadatos XMP por clave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [getExtensionFields](#getExtensionFields--) | <p> Obtiene el diccionario de campos de extensión. </p> |
| [getKeys](#getKeys--) | Obtiene las claves del diccionario. |
| [getNamespaceURIByPrefix](#getNamespaceURIByPrefix-java.lang.String-) | <p> Obtiene el URI del espacio de nombres por prefijo. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre> |
| [getPrefixByNamespaceURI](#getPrefixByNamespaceURI-java.lang.String-) | <p> Obtiene el prefijo por URI del espacio de nombres. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre> |
| [getSyncRoot](#getSyncRoot--) | Obtiene el objeto de sincronización de la colección. |
| [getValues](#getValues--) | Obtiene la colección de valores del diccionario. |
| [getXmpMetadata](#getXmpMetadata--) | <p> Obtiene el XmpMetadata del PDF de entrada en formato XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [getXmpMetadata](#getXmpMetadata-java.lang.String-) | <p> Obtiene el XmpMetadata del PDF de entrada en formato XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [isFixedSize](#isFixedSize--) | Devuelve true si la colección tiene tamaño fijo. |
| [isReadOnly](#isReadOnly--) | Devuelve true si la colección es de solo lectura. |
| [isSynchronized](#isSynchronized--) | Devuelve true si la colección está sincronizada. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Obtiene el objeto enumerador del diccionario. |
| [iteratorIt](#iteratorIt--) | Obtiene el objeto enumerador de la colección. |
| [registerNamespaceURI](#registerNamespaceURI-java.lang.String-java.lang.String-) | <p> Registra el URI del espacio de nombres. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre> |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Elimina el par clave/valor de la colección. |
| [removeItemByKey](#removeItemByKey-int-) | <p> Elimina el elemento con la clave especificada. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre> |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | <p> Elimina la clave del diccionario. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre> |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | <p> Establece el valor por clave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [setByDefaultMetadataProperties](#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-) | <p> Establece el valor de los metadatos XMP por clave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [size](#size--) | <p> Obtiene el recuento de los elementos en la colección. </p> |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Intenta encontrar la clave en el diccionario y recupera el valor si se encuentra. |

### PdfXmpMetadata {#PdfXmpMetadata--}
```
public PdfXmpMetadata()
```

<p> Constructor de PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### PdfXmpMetadata {#PdfXmpMetadata-com.aspose.pdf.IDocument-}
<p> Constructor de PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-}
Agrega un campo de extensión a los metadatos.

### addItem {#addItem-int-com.aspose.pdf.XmpValue-}
<p> Agrega un valor a los metadatos XMP. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre>

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Agrega un par con clave y valor al diccionario.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Agrega un nuevo elemento al objeto diccionario.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
<p> Agrega un nuevo elemento al objeto diccionario. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre>

### clear {#clear--}
```
public void clear()
```

<p> Elimina todos los elementos del objeto. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre>

### contains {#contains-int-}
```
public boolean contains(int property)
```

Comprueba si el diccionario contiene la propiedad especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad |  | Propiedad que será verificada. |

**Returns:**
True - si el diccionario contiene la propiedad especificada; de lo contrario, false.

### contains {#contains-java.lang.String-}
<p> Comprueba si el diccionario contiene la clave especificada. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre>

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Comprueba si el par clave-valor especificado está contenido en el diccionario.

### containsKey {#containsKey-java.lang.String-}
Determina si este diccionario contiene la clave especificada.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copia los metadatos en una matriz.

### get_Item {#get_Item-java.lang.String-}
<p> Obtiene el valor por clave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### getByDefaultMetadataProperties {#getByDefaultMetadataProperties-int-}
```
public XmpValue getByDefaultMetadataProperties(int key)
```

<p> Obtiene el valor de los metadatos XMP por clave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key |  | Clave del valor. |

**Returns:**
Valor de los metadatos XMP. @see DefaultMetadataProperties

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Obtiene el diccionario de campos de extensión. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} objeto

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Obtiene las claves del diccionario.

**Returns:**
Elemento ICollection

### getNamespaceURIByPrefix {#getNamespaceURIByPrefix-java.lang.String-}
<p> Obtiene el URI del espacio de nombres por prefijo. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre>

### getPrefixByNamespaceURI {#getPrefixByNamespaceURI-java.lang.String-}
<p> Obtiene el prefijo por URI del espacio de nombres. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre>

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtiene el objeto de sincronización de la colección.

**Returns:**
Elemento Object

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Obtiene la colección de valores del diccionario.

**Returns:**
objeto ICollection

### getXmpMetadata {#getXmpMetadata--}
```
public byte[] getXmpMetadata()
```

<p> Obtiene el XmpMetadata del PDF de entrada en formato XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
Los bytes del XmpMetadata.

### getXmpMetadata {#getXmpMetadata-java.lang.String-}
<p> Obtiene el XmpMetadata del PDF de entrada en formato XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
Los bytes del XmpMetadata.

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Devuelve true si la colección tiene tamaño fijo.

**Returns:**
valor booleano

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Devuelve true si la colección es de solo lectura.

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Devuelve true si la colección está sincronizada.

**Returns:**
valor booleano

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

Obtiene el objeto enumerador del diccionario.

**Returns:**
El objeto enumerador.

### iteratorIt {#iteratorIt--}
```
public com.aspose.ms.System.Collections.IEnumerator iteratorIt()
```

Obtiene el objeto enumerador de la colección.

**Returns:**
Objeto IEnumerator

### registerNamespaceURI {#registerNamespaceURI-java.lang.String-java.lang.String-}
<p> Registra el URI del espacio de nombres. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre>

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Elimina el par clave/valor de la colección.

### removeItemByKey {#removeItemByKey-int-}
```
public void removeItemByKey(int key)
```

<p> Elimina el elemento con la clave especificada. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| key |  | Clave del elemento que será eliminado. @see DefaultMetadataProperties |

### removeItemByKey {#removeItemByKey-java.lang.String-}
<p> Elimina la clave del diccionario. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre>

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
<p> Establece el valor por clave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### setByDefaultMetadataProperties {#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-}
<p> Establece el valor de los metadatos XMP por clave. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

### size {#size--}
```
public int size()
```

<p> Obtiene el recuento de los elementos en la colección. </p>

**Returns:**
valor int <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println("Count = " + pxm.size()); </pre>

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Intenta encontrar la clave en el diccionario y recupera el valor si se encuentra.
