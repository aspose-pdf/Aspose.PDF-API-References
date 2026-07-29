---
title: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Si la propiedad SplitToPages de HtmlSaveOptions está activada, se crean varios archivos HTML (un archivo HTML por página convertida) durante la conversión de PDF a HTML. Esta clase representa un conjunto de."
type: docs
weight: 2100
url: /es/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo

```
public static class HtmlSaveOptions.HtmlPageMarkupSavingInfo extends Object
```

Si la propiedad SplitToPages de HtmlSaveOptions está activada, se crean varios archivos HTML (un archivo HTML por página convertida) durante la conversión de PDF a HTML. Esta clase representa un conjunto de datos relacionados con el guardado personalizado del marcado de una página HTML durante la conversión de PDF a HTML.

## Métodos

| Método | Descripción |
| --- | --- |
| [getContentStream](#getContentStream--) | Establecido por el conversor. Representa el HTML guardado como flujo. |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Establecido por el conversor. Si la propiedad SplitToPages está activada, se crean varios archivos HTML (un archivo HTML por página convertida) durante la conversión. Esta propiedad contiene el ordinal del archivo de la página HTML guardada. La propiedad puede usarse en la lógica del código personalizado para decidir cómo procesar o dónde guardar la página HTML y, si la división en páginas está desactivada, este valor siempre contiene '1' ya que en ese caso solo se genera una única página HTML grande para todo el documento fuente. |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Establecido por el conversor. Si la propiedad SplitToPages está activada, se crean varios archivos HTML (un archivo HTML por página convertida) durante la conversión. Esta propiedad indica al código personalizado de qué página del PDF original se generó el marcado HTML guardado. Si el número de página original es desconocido por alguna razón o SplitToPages=false, entonces esta propiedad siempre contiene '0', lo que indica que el conversor no puede proporcionar el número exacto de página del PDF original para el archivo de marcado HTML suministrado. |
| [getSupposedFileName](#getSupposedFileName--) | Establecido por el conversor. Nombre de archivo supuesto que pasa del conversor al código del método personalizado. Puede usarse en el código personalizado para decidir cómo procesar o dónde guardar el contenido. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Debe establecerse en el código personalizado cuando sea necesario. Esta bandera debe establecerse en "true" en el código personalizado si, por alguna razón, el marcado HTML suministrado debe procesarse no con el código personalizado sino con el propio código del conversor de forma estándar. Por lo tanto, establecer esta bandera en el código personalizado significa que el código personalizado no procesó el archivo referenciado y el conversor debe manejarlo él mismo. |
| [setContentStream](#setContentStream-java.io.InputStream-) | Establecido por el conversor. Representa el HTML guardado como flujo. |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Debe establecerse en el código personalizado cuando sea necesario. Esta bandera debe establecerse en "true" en el código personalizado si, por alguna razón, el marcado HTML suministrado debe procesarse no con el código personalizado sino con el propio código del conversor de forma estándar. Por lo tanto, establecer esta bandera en el código personalizado significa que el código personalizado no procesó el archivo referenciado y el conversor debe manejarlo él mismo. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Establecido por el conversor. Si la propiedad SplitToPages está activada, se crean varios archivos HTML (un archivo HTML por página convertida) durante la conversión. Esta propiedad contiene el ordinal del archivo de la página HTML guardada. La propiedad puede usarse en la lógica del código personalizado para decidir cómo procesar o dónde guardar la página HTML y, si la división en páginas está desactivada, este valor siempre contiene '1' ya que en ese caso solo se genera una única página HTML grande para todo el documento fuente. |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Establecido por el conversor. Si la propiedad SplitToPages está activada, se crean varios archivos HTML (un archivo HTML por página convertida) durante la conversión. Esta propiedad indica al código personalizado de qué página del PDF original se generó el marcado HTML guardado. Si el número de página original es desconocido por alguna razón o SplitToPages=false, entonces esta propiedad siempre contiene '0', lo que indica que el conversor no puede proporcionar el número exacto de página del PDF original para el archivo de marcado HTML suministrado. |
| [setSupposedFileName](#setSupposedFileName-java.lang.String-) | Establecido por el conversor. Nombre de archivo supuesto que pasa del conversor al código del método personalizado. Puede usarse en el código personalizado para decidir cómo procesar o dónde guardar el contenido. |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

Establecido por el conversor. Representa el HTML guardado como flujo.

**Returns:**
Instancia de InputStream

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Establecido por el conversor. Si la propiedad SplitToPages está activada, se crean varios archivos HTML (un archivo HTML por página convertida) durante la conversión. Esta propiedad contiene el ordinal del archivo de la página HTML guardada. La propiedad puede usarse en la lógica del código personalizado para decidir cómo procesar o dónde guardar la página HTML y, si la división en páginas está desactivada, este valor siempre contiene '1' ya que en ese caso solo se genera una única página HTML grande para todo el documento fuente.

**Returns:**
valor int

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Establecido por el conversor. Si la propiedad SplitToPages está activada, se crean varios archivos HTML (un archivo HTML por página convertida) durante la conversión. Esta propiedad indica al código personalizado de qué página del PDF original se generó el marcado HTML guardado. Si el número de página original es desconocido por alguna razón o SplitToPages=false, entonces esta propiedad siempre contiene '0', lo que indica que el conversor no puede proporcionar el número exacto de página del PDF original para el archivo de marcado HTML suministrado.

**Returns:**
valor int

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Establecido por el conversor. Nombre de archivo supuesto que pasa del conversor al código del método personalizado. Puede usarse en el código personalizado para decidir cómo procesar o dónde guardar el contenido.

**Returns:**
valor String

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Debe establecerse en el código personalizado cuando sea necesario. Esta bandera debe establecerse en "true" en el código personalizado si, por alguna razón, el marcado HTML suministrado debe procesarse no con el código personalizado sino con el propio código del conversor de forma estándar. Por lo tanto, establecer esta bandera en el código personalizado significa que el código personalizado no procesó el archivo referenciado y el conversor debe manejarlo él mismo.

**Returns:**
valor booleano

### setContentStream {#setContentStream-java.io.InputStream-}
Establecido por el conversor. Representa el HTML guardado como flujo.

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Debe establecerse en el código personalizado cuando sea necesario. Esta bandera debe establecerse en "true" en el código personalizado si, por alguna razón, el marcado HTML suministrado debe procesarse no con el código personalizado sino con el propio código del conversor de forma estándar. Por lo tanto, establecer esta bandera en el código personalizado significa que el código personalizado no procesó el archivo referenciado y el conversor debe manejarlo él mismo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| customProcessingCancelled |  | valor booleano |

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Establecido por el conversor. Si la propiedad SplitToPages está activada, se crean varios archivos HTML (un archivo HTML por página convertida) durante la conversión. Esta propiedad contiene el ordinal del archivo de la página HTML guardada. La propiedad puede usarse en la lógica del código personalizado para decidir cómo procesar o dónde guardar la página HTML y, si la división en páginas está desactivada, este valor siempre contiene '1' ya que en ese caso solo se genera una única página HTML grande para todo el documento fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| htmlHostPageNumber |  | valor int |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Establecido por el conversor. Si la propiedad SplitToPages está activada, se crean varios archivos HTML (un archivo HTML por página convertida) durante la conversión. Esta propiedad indica al código personalizado de qué página del PDF original se generó el marcado HTML guardado. Si el número de página original es desconocido por alguna razón o SplitToPages=false, entonces esta propiedad siempre contiene '0', lo que indica que el conversor no puede proporcionar el número exacto de página del PDF original para el archivo de marcado HTML suministrado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdfHostPageNumber |  | valor int |

### setSupposedFileName {#setSupposedFileName-java.lang.String-}
Establecido por el conversor. Nombre de archivo supuesto que pasa del conversor al código del método personalizado. Puede usarse en el código personalizado para decidir cómo procesar o dónde guardar el contenido.
