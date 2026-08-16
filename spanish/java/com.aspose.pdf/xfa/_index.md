---
title: "XFA"
linktitle: "XFA"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un formulario XML respecto a la arquitectura de formularios XML (XFA)."
type: docs
weight: 5550
url: /es/java/com.aspose.pdf/xfa/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFA

```
public final class XFA extends Object
```

Representa un formulario XML respecto a la arquitectura de formularios XML (XFA).

## Métodos

| Método | Descripción |
| --- | --- |
| [appendToTemplate](#appendToTemplate-java.lang.String-java.lang.String-) | Agregar valor XML al nodo de la plantilla que coincide con la expresión XPath |
| [beginCachedUpdates](#beginCachedUpdates--) | Iniciar modo de actualizaciones en caché. Todos los cambios realizados en XFA se almacenarán en caché y se guardarán en la estructura del documento al llamar a EndCachedUpdates. Esto permite mejorar el rendimiento al evitar operaciones redundantes al guardar paquetes XML en el documento cuando se realizan muchos cambios en XFA. |
| [endCachedUpdates](#endCachedUpdates--) | Finaliza las actualizaciones en caché y guarda todos los datos en la estructura del documento. |
| [flattenXfaField](#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-) | Aplanar campo del formulario XFA. |
| [get_Item](#get_Item-java.lang.String-) | Obtiene el valor del nodo de datos según {@code path}. |
| [getConfig](#getConfig--) | Componente Config de XFA de un formulario XFA. |
| [getDatasets](#getDatasets--) | Componente Datasets de XFA de un formulario XFA. |
| [getFieldNames](#getFieldNames--) | Lista de nombres de campos en la plantilla del formulario. |
| [getFieldsWithTextValuesMap](#getFieldsWithTextValuesMap--) | <p> Devuelve un mapa con el nombre corto del campo y su valor de cadena para todos los campos. </p> |
| [getFieldTemplate](#getFieldTemplate-java.lang.String-) | Devuelve el nodo XML del campo XFA de la plantilla. |
| [getFieldTemplates](#getFieldTemplates--) | Devuelve la lista de todas las plantillas de campo en el formulario XFA. |
| [getForm](#getForm--) | Obtiene el componente de formulario XFA de un formulario XFA. |
| [getNamespaceManager_](#getNamespaceManager_--) | Obtiene el espacio de nombres para el formulario XFA. Los siguientes espacios de nombres están definidos: \"data\" para datos del formulario y \"tpl\" para la plantilla del formulario. |
| [getNamespaceManager](#getNamespaceManager--) | Devuelve el administrador de espacios de nombres con los espacios de nombres utilizados para la plantilla y los datos. |
| [getTemplate](#getTemplate--) | Componente Template de XFA de un formulario XFA. |
| [getXDP](#getXDP--) | Paquete de datos XML (todos los componentes del formulario XFA dentro de un contenedor XML circundante). |
| [getXfaField](#getXfaField-java.lang.String-) |  |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Obtiene el valor del nodo de datos según {@code path}. |
| [setFieldImage](#setFieldImage-java.lang.String-java.io.InputStream-) | Establece la imagen para el campo XFA. |
| [setFieldImageInternal](#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [tryGetTemplateString](#tryGetTemplateString-java.lang.String-) | Intenta exportar el script de cálculo del formulario XFA. De lo contrario, devuelve la cadena vacía; |

### appendToTemplate {#appendToTemplate-java.lang.String-java.lang.String-}
Agregar valor XML al nodo de la plantilla que coincide con la expresión XPath

### beginCachedUpdates {#beginCachedUpdates--}
```
public void beginCachedUpdates()
```

Iniciar modo de actualizaciones en caché. Todos los cambios realizados en XFA se almacenarán en caché y se guardarán en la estructura del documento al llamar a EndCachedUpdates. Esto permite mejorar el rendimiento al evitar operaciones redundantes al guardar paquetes XML en el documento cuando se realizan muchos cambios en XFA.

### endCachedUpdates {#endCachedUpdates--}
```
public void endCachedUpdates()
```

Finaliza las actualizaciones en caché y guarda todos los datos en la estructura del documento.

### flattenXfaField {#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-}
Aplanar campo del formulario XFA.

### get_Item {#get_Item-java.lang.String-}
Obtiene el valor del nodo de datos según {@code path}.

### getConfig {#getConfig--}
```
public com.aspose.ms.System.Xml.XmlNode getConfig()
```

Componente Config de XFA de un formulario XFA.

**Returns:**
Objeto XmlNode

### getDatasets {#getDatasets--}
```
public com.aspose.ms.System.Xml.XmlNode getDatasets()
```

Componente Datasets de XFA de un formulario XFA.

**Returns:**
Objeto XmlNode

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

Lista de nombres de campos en la plantilla del formulario.

**Returns:**
matriz de valores String

### getFieldsWithTextValuesMap {#getFieldsWithTextValuesMap--}
```
public HashMap < String , String > getFieldsWithTextValuesMap()
```

<p> Devuelve un mapa con el nombre corto del campo y su valor de cadena para todos los campos. </p>

**Returns:**
{@code HashMap<String, String>} objeto

### getFieldTemplate {#getFieldTemplate-java.lang.String-}
Devuelve el nodo XML del campo XFA de la plantilla.

### getFieldTemplates {#getFieldTemplates--}
```
public com.aspose.ms.System.Xml.XmlNodeList getFieldTemplates()
```

Devuelve la lista de todas las plantillas de campo en el formulario XFA.

**Returns:**
Lista de plantillas de campo.

### getForm {#getForm--}
```
public com.aspose.ms.System.Xml.XmlNode getForm()
```

Obtiene el componente de formulario XFA de un formulario XFA.

**Returns:**
Objeto XmlNode

### getNamespaceManager_ {#getNamespaceManager_--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager_()
```

Obtiene el espacio de nombres para el formulario XFA. Los siguientes espacios de nombres están definidos: \"data\" para datos del formulario y \"tpl\" para la plantilla del formulario.

**Returns:**
Objeto XmlNamespaceManager

### getNamespaceManager {#getNamespaceManager--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager()
```

Devuelve el administrador de espacios de nombres con los espacios de nombres utilizados para la plantilla y los datos.

**Returns:**
Objeto XmlNamespaceManager

### getTemplate {#getTemplate--}
```
public com.aspose.ms.System.Xml.XmlNode getTemplate()
```

Componente Template de XFA de un formulario XFA.

**Returns:**
Objeto XmlNode

### getXDP {#getXDP--}
```
public com.aspose.ms.System.Xml.XmlDocument getXDP()
```

Paquete de datos XML (todos los componentes del formulario XFA dentro de un contenedor XML circundante).

**Returns:**
Objeto XmlDocument

### getXfaField {#getXfaField-java.lang.String-}


### set_Item {#set_Item-java.lang.String-java.lang.String-}
Obtiene el valor del nodo de datos según {@code path}.

### setFieldImage {#setFieldImage-java.lang.String-java.io.InputStream-}
Establece la imagen para el campo XFA.

### setFieldImageInternal {#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}


### tryGetTemplateString {#tryGetTemplateString-java.lang.String-}
Intenta exportar el script de cálculo del formulario XFA. De lo contrario, devuelve la cadena vacía;
