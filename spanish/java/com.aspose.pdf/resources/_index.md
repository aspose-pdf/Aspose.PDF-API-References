---
title: "Resources"
linktitle: "Resources"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa recursos de página."
type: docs
weight: 4220
url: /es/java/com.aspose.pdf/resources/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Resources

```
public final class Resources extends Object
```

Clase que representa recursos de página.

## Métodos

| Método | Descripción |
| --- | --- |
| [clearImagesCache](#clearImagesCache--) |  |
| [freeMemory](#freeMemory--) | Limpia los datos en caché, libera memoria, etc. |
| [getExtGStates](#getExtGStates--) | Obtiene todos los ExGStates de los recursos. |
| [getFonts](#getFonts--) | Obtiene la colección de recursos {@code Fonts} |
| [getFonts](#getFonts-boolean-) | Devuelve la colección de fuentes. Si los recursos no contienen una entrada de fuentes, se creará según la bandera CreateIfAbsent. |
| [getForms](#getForms--) | Obtiene la colección de formularios {@code Forms} |
| [getImages](#getImages--) | Obtiene la colección de imágenes {@code Images} |
| [getResourceDictionary](#getResourceDictionary--) | Campo interno |
| [getResourcesFor](#getResourcesFor-com.aspose.pdf.Form-) | Obtiene recursos para |
| [isCommonResource](#isCommonResource--) | Verdadero si estos recursos son comunes, es decir, se comparten en varias páginas (colocados en el diccionario de páginas o en cada página como referencia de objeto). La manipulación de recursos comunes debe realizarse con mucho cuidado; por ejemplo, eliminar un objeto de los recursos comunes en una página puede causar errores en otras páginas si el objeto eliminado se utilizó en esas páginas. |
| [setResourceDictionary](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | ¡Solo para uso interno! |

### clearImagesCache {#clearImagesCache--}
```
public final void clearImagesCache()
```



### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Limpia los datos en caché, libera memoria, etc.

### getExtGStates {#getExtGStates--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , Resources.ExtGStateValue > getExtGStates()
```

Obtiene todos los ExGStates de los recursos.

**Returns:**
Devuelve un diccionario con los nombres de claves de ExGStates.

### getFonts {#getFonts--}
```
public FontCollection getFonts()
```

Obtiene la colección de recursos {@code Fonts}

**Returns:**
Objeto FontCollection

### getFonts {#getFonts-boolean-}
```
public FontCollection getFonts(boolean createIfAbsent)
```

Devuelve la colección de fuentes. Si los recursos no contienen una entrada de fuentes, se creará según la bandera CreateIfAbsent.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| createIfAbsent |  | Si esta bandera es verdadera, entonces las fuentes se crearán si esta entrada está ausente. |

**Returns:**
Colección de fuentes.

### getForms {#getForms--}
```
public XFormCollection getForms()
```

Obtiene la colección de formularios {@code Forms}

**Returns:**
Objeto XFormCollection

### getImages {#getImages--}
```
public XImageCollection getImages()
```

Obtiene la colección de imágenes {@code Images}

**Returns:**
Objeto XImageCollection

### getResourceDictionary {#getResourceDictionary--}
```
public com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary getResourceDictionary()
```

Campo interno

### getResourcesFor {#getResourcesFor-com.aspose.pdf.Form-}
Obtiene recursos para

### isCommonResource {#isCommonResource--}
```
public boolean isCommonResource()
```

Verdadero si estos recursos son comunes, es decir, se comparten en varias páginas (colocados en el diccionario de páginas o en cada página como referencia de objeto). La manipulación de recursos comunes debe realizarse con mucho cuidado; por ejemplo, eliminar un objeto de los recursos comunes en una página puede causar errores en otras páginas si el objeto eliminado se utilizó en esas páginas.

**Returns:**
valor booleano

### setResourceDictionary {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
¡Solo para uso interno!
