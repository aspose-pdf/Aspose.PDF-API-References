---
title: "HtmlSaveOptions.CssSavingInfo"
linktitle: "HtmlSaveOptions.CssSavingInfo"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Esta clase representa un conjunto de datos relacionados con el guardado personalizado de CSS durante la conversión de PDF a formato HTML"
type: docs
weight: 2010
url: /es/java/com.aspose.pdf/htmlsaveoptions.csssavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.CssSavingInfo

```
public static class HtmlSaveOptions.CssSavingInfo extends Object
```

Esta clase representa un conjunto de datos relacionados con el guardado personalizado de CSS durante la conversión de PDF a formato HTML

## Métodos

| Método | Descripción |
| --- | --- |
| [getContentStream](#getContentStream--) | Establecido por el convertidor. Representa el contenido binario del CSS guardado |
| [getCssNumber](#getCssNumber--) | Establecido por el convertidor. Durante la conversión se crean varios archivos CSS. Esta propiedad muestra el ordinal del archivo CSS guardado durante la conversión. Puede usarse en la lógica de código personalizado para decidir cómo procesar o dónde guardar el contenido CSS. |
| [getSupposedURL](#getSupposedURL--) | Establecido por el conversor. Nombre de archivo supuesto que pasa del conversor al código del método personalizado. Puede usarse en el código personalizado para decidir cómo procesar o dónde guardar el contenido. |
| [setContentStream](#setContentStream-java.io.InputStream-) | Establecido por el convertidor. Representa el contenido binario del CSS guardado |
| [setCssNumber](#setCssNumber-int-) | Establecido por el convertidor. Durante la conversión se crean varios archivos CSS. Esta propiedad muestra el ordinal del archivo CSS guardado durante la conversión. Puede usarse en la lógica de código personalizado para decidir cómo procesar o dónde guardar el contenido CSS. |
| [setSupposedURL](#setSupposedURL-java.lang.String-) | Establecido por el conversor. Nombre de archivo supuesto que pasa del conversor al código del método personalizado. Puede usarse en el código personalizado para decidir cómo procesar o dónde guardar el contenido. |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

Establecido por el convertidor. Representa el contenido binario del CSS guardado

**Returns:**
Instancia de InputStream

### getCssNumber {#getCssNumber--}
```
public int getCssNumber()
```

Establecido por el convertidor. Durante la conversión se crean varios archivos CSS. Esta propiedad muestra el ordinal del archivo CSS guardado durante la conversión. Puede usarse en la lógica de código personalizado para decidir cómo procesar o dónde guardar el contenido CSS.

**Returns:**
valor int

### getSupposedURL {#getSupposedURL--}
```
public String getSupposedURL()
```

Establecido por el conversor. Nombre de archivo supuesto que pasa del conversor al código del método personalizado. Puede usarse en el código personalizado para decidir cómo procesar o dónde guardar el contenido.

**Returns:**
valor String

### setContentStream {#setContentStream-java.io.InputStream-}
Establecido por el convertidor. Representa el contenido binario del CSS guardado

### setCssNumber {#setCssNumber-int-}
```
public void setCssNumber(int cssNumber)
```

Establecido por el convertidor. Durante la conversión se crean varios archivos CSS. Esta propiedad muestra el ordinal del archivo CSS guardado durante la conversión. Puede usarse en la lógica de código personalizado para decidir cómo procesar o dónde guardar el contenido CSS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cssNumber |  | valor int |

### setSupposedURL {#setSupposedURL-java.lang.String-}
Establecido por el conversor. Nombre de archivo supuesto que pasa del conversor al código del método personalizado. Puede usarse en el código personalizado para decidir cómo procesar o dónde guardar el contenido.
