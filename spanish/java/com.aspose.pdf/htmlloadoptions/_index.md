---
title: "HtmlLoadOptions"
linktitle: "HtmlLoadOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa opciones para cargar/importar un archivo html en un documento pdf."
type: docs
weight: 1960
url: /es/java/com.aspose.pdf/htmlloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.HtmlLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.HtmlLoadOptions

```
public final class HtmlLoadOptions extends LoadOptions
```

Representa opciones para cargar/importar un archivo html en un documento pdf.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [HtmlLoadOptions](#HtmlLoadOptions--) | Crea opciones de carga para convertir html en documento pdf con ruta base vacía. |
| [HtmlLoadOptions](#HtmlLoadOptions-java.lang.String-) | Crea opciones de carga para convertir html en documento pdf con ruta base vacía. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBasePath](#getBasePath--) | La ruta/base URL para el archivo HTML. |
| [getCustomLoaderOfExternalResources](#getCustomLoaderOfExternalResources--) | A veces es necesario evitar el uso del cargador interno de recursos externos (como imágenes o CSS) y proporcionar un método personalizado que obtenga los recursos solicitados de algún lugar. Por ejemplo, durante el uso de Aspose.PDF en la nube el acceso directo a los archivos referenciados es imposible: en tal caso se debe usar el código del cliente colocado en un método especial, y el delegado que hace referencia a ese método debe asignarse a este atributo. |
| [getHtmlMediaType](#getHtmlMediaType--) | Obtiene o establece los tipos de medios posibles utilizados durante la renderización. |
| [getInputEncoding](#getInputEncoding--) | Obtiene el atributo que especifica la codificación utilizada para este documento en el momento del análisis. Si este atributo es nulo, la codificación se determinará a partir del atributo de conjunto de caracteres del documento. |
| [getPageInfo](#getPageInfo--) | Obtiene la información de la página del documento |
| [getPageLayoutOption](#getPageLayoutOption--) | Obtiene o establece la opción de diseño. |
| [isEmbedFonts](#isEmbedFonts--) | Obtiene o establece la incrustación de fuentes en el documento resultante |
| [isPriorityCssPageRule](#isPriorityCssPageRule--) | Obtiene o establece la bandera que especifica que las reglas @page definidas en CSS sobrescribirán los valores definidos en PageInfo. |
| [isRenderToSinglePage](#isRenderToSinglePage--) | Obtiene o establece la renderización de todo el documento en una sola página |
| [setCustomLoaderOfExternalResources](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | A veces es necesario evitar el uso del cargador interno de recursos externos (como imágenes o CSS) y proporcionar un método personalizado que obtenga los recursos solicitados de algún lugar. |
| [setEmbedFonts](#setEmbedFonts-boolean-) | Obtiene o establece la incrustación de fuentes en el documento resultante |
| [setHtmlMediaType](#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-) | Obtiene o establece los tipos de medios posibles utilizados durante la renderización. |
| [setInputEncoding](#setInputEncoding-java.lang.String-) | Establece el atributo que especifica la codificación utilizada para este documento en el momento del análisis. Si este atributo es nulo, la codificación se determinará a partir del atributo de conjunto de caracteres del documento. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Establece la información de la página del documento |
| [setPageLayoutOption](#setPageLayoutOption-int-) | Obtiene o establece la opción de diseño. |
| [setPriorityCssPageRule](#setPriorityCssPageRule-boolean-) | Obtiene o establece la bandera que especifica que las reglas @page definidas en CSS sobrescribirán los valores definidos en PageInfo. |
| [setRenderToSinglePage](#setRenderToSinglePage-boolean-) | Obtiene o establece la renderización de todo el documento en una sola página |

### HtmlLoadOptions {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```

Crea opciones de carga para convertir html en documento pdf con ruta base vacía.

### HtmlLoadOptions {#HtmlLoadOptions-java.lang.String-}
Crea opciones de carga para convertir html en documento pdf con ruta base vacía.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

La ruta/base URL para el archivo HTML.

**Returns:**
valor String

### getCustomLoaderOfExternalResources {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```

A veces es necesario evitar el uso del cargador interno de recursos externos (como imágenes o CSS) y proporcionar un método personalizado que obtenga los recursos solicitados de algún lugar. Por ejemplo, durante el uso de Aspose.PDF en la nube el acceso directo a los archivos referenciados es imposible: en tal caso se debe usar el código del cliente colocado en un método especial, y el delegado que hace referencia a ese método debe asignarse a este atributo.

**Returns:**
Instancia de ResourceLoadingStrategy

### getHtmlMediaType {#getHtmlMediaType--}
```
public HtmlMediaType getHtmlMediaType()
```

Obtiene o establece los tipos de medios posibles utilizados durante la renderización.

**Returns:**
Elemento HtmlMediaType

### getInputEncoding {#getInputEncoding--}
```
public String getInputEncoding()
```

Obtiene el atributo que especifica la codificación utilizada para este documento en el momento del análisis. Si este atributo es nulo, la codificación se determinará a partir del atributo de conjunto de caracteres del documento.

**Returns:**
valor String

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Obtiene la información de la página del documento

**Returns:**
información de página

### getPageLayoutOption {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```

Obtiene o establece la opción de diseño.

**Returns:**
Elemento HtmlPageLayoutOption @see HtmlPageLayoutOption

### isEmbedFonts {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```

Obtiene o establece la incrustación de fuentes en el documento resultante

**Returns:**
valor booleano

### isPriorityCssPageRule {#isPriorityCssPageRule--}
```
public final boolean isPriorityCssPageRule()
```

Obtiene o establece la bandera que especifica que las reglas @page definidas en CSS sobrescribirán los valores definidos en PageInfo.

**Returns:**
valor booleano

### isRenderToSinglePage {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```

Obtiene o establece la renderización de todo el documento en una sola página

**Returns:**
valor booleano

### setCustomLoaderOfExternalResources {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
A veces es necesario evitar el uso del cargador interno de recursos externos (como imágenes o CSS) y proporcionar un método personalizado que obtenga los recursos solicitados de algún lugar.

### setEmbedFonts {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```

Obtiene o establece la incrustación de fuentes en el documento resultante

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setHtmlMediaType {#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-}
Obtiene o establece los tipos de medios posibles utilizados durante la renderización.

### setInputEncoding {#setInputEncoding-java.lang.String-}
Establece el atributo que especifica la codificación utilizada para este documento en el momento del análisis. Si este atributo es nulo, la codificación se determinará a partir del atributo de conjunto de caracteres del documento.

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Establece la información de la página del documento

### setPageLayoutOption {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```

Obtiene o establece la opción de diseño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento HtmlPageLayoutOption @see HtmlPageLayoutOption |

### setPriorityCssPageRule {#setPriorityCssPageRule-boolean-}
```
public final void setPriorityCssPageRule(boolean value)
```

Obtiene o establece la bandera que especifica que las reglas @page definidas en CSS sobrescribirán los valores definidos en PageInfo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRenderToSinglePage {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```

Obtiene o establece la renderización de todo el documento en una sola página

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
