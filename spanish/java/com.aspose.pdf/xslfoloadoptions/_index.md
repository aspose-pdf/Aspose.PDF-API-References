---
title: "XslFoLoadOptions"
linktitle: "XslFoLoadOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa opciones para cargar/importar un archivo XSL-FO en un documento PDF."
type: docs
weight: 5780
url: /es/java/com.aspose.pdf/xslfoloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.XmlLoadOptions, com.aspose.pdf.XslFoLoadOptions

```
public final class XslFoLoadOptions extends XmlLoadOptions
```

Representa opciones para cargar/importar un archivo XSL-FO en un documento PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [XslFoLoadOptions](#XslFoLoadOptions--) | Crea un objeto {@code XslFoLoadOptions} sin datos xsl. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.io.InputStream-) | Crea un objeto {@code XslFoLoadOptions} sin datos xsl. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.lang.String-) | Crea un objeto {@code XslFoLoadOptions} sin datos xsl. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBasePath](#getBasePath--) | La ruta/base URL desde la cual se buscan rutas relativas a recursos externos (si los hay) referenciados en el archivo SVG cargado. |
| [getParsingErrorsHandlingType](#getParsingErrorsHandlingType--) | El documento XSLFO de origen puede contener errores de formato. Este enum enumera las posibles estrategias de manejo de esos errores. |
| [setBasePath](#setBasePath-java.lang.String-) |  |
| [setParsingErrorsHandlingType](#setParsingErrorsHandlingType-int-) | El documento XSLFO de origen puede contener errores de formato. Este enum enumera las posibles estrategias de manejo de esos errores. |

### XslFoLoadOptions {#XslFoLoadOptions--}
```
public XslFoLoadOptions()
```

Crea un objeto {@code XslFoLoadOptions} sin datos xsl.

### XslFoLoadOptions {#XslFoLoadOptions-java.io.InputStream-}
Crea un objeto {@code XslFoLoadOptions} sin datos xsl.

### XslFoLoadOptions {#XslFoLoadOptions-java.lang.String-}
Crea un objeto {@code XslFoLoadOptions} sin datos xsl.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

La ruta/base URL desde la cual se buscan rutas relativas a recursos externos (si los hay) referenciados en el archivo SVG cargado.

**Returns:**
Cadena

### getParsingErrorsHandlingType {#getParsingErrorsHandlingType--}
```
public int getParsingErrorsHandlingType()
```

El documento XSLFO de origen puede contener errores de formato. Este enum enumera las posibles estrategias de manejo de esos errores.

**Returns:**
Elemento ParsingErrorsHandlingTypes @see ParsingErrorsHandlingTypes

### setBasePath {#setBasePath-java.lang.String-}


### setParsingErrorsHandlingType {#setParsingErrorsHandlingType-int-}
```
public void setParsingErrorsHandlingType(int parsingErrorsHandlingType)
```

El documento XSLFO de origen puede contener errores de formato. Este enum enumera las posibles estrategias de manejo de esos errores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parsingErrorsHandlingType |  | Elemento ParsingErrorsHandlingTypes @see ParsingErrorsHandlingTypes |
