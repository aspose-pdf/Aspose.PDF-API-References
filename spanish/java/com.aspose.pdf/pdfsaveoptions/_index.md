---
title: "PdfSaveOptions"
linktitle: "PdfSaveOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Opciones de guardado para exportar al formato Pdf"
type: docs
weight: 3790
url: /es/java/com.aspose.pdf/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.PdfSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.PdfSaveOptions

```
public class PdfSaveOptions extends SaveOptions
```

Opciones de guardado para exportar al formato Pdf

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfSaveOptions](#PdfSaveOptions--) | Constructor |

## Métodos

| Método | Descripción |
| --- | --- |
| [getDefaultFontName](#getDefaultFontName--) | Nombre de fuente usado por defecto para fuentes que están ausentes en el equipo. Cuando el documento PDF que se guarda en PDF contiene fuentes que no están disponibles en el propio documento ni en el dispositivo, la API reemplaza estas fuentes con la fuente predeterminada (si se encuentra una fuente con {@code DefaultFontName} en el dispositivo) |
| [getTempPath](#getTempPath--) | Ruta para archivos temporales. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Nombre de fuente usado por defecto para fuentes que están ausentes en el equipo. Cuando el documento PDF que se guarda en PDF contiene fuentes que no están disponibles en el propio documento ni en el dispositivo, la API reemplaza estas fuentes con la fuente predeterminada (si se encuentra una fuente con {@code DefaultFontName} en el dispositivo) |
| [setTempPath](#setTempPath-java.lang.String-) | Ruta para archivos temporales. |

### PdfSaveOptions {#PdfSaveOptions--}
```
public PdfSaveOptions()
```

Constructor

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Nombre de fuente usado por defecto para fuentes que están ausentes en el equipo. Cuando el documento PDF que se guarda en PDF contiene fuentes que no están disponibles en el propio documento ni en el dispositivo, la API reemplaza estas fuentes con la fuente predeterminada (si se encuentra una fuente con {@code DefaultFontName} en el dispositivo)

**Returns:**
valor String

### getTempPath {#getTempPath--}
```
public final String getTempPath()
```

Ruta para archivos temporales.

**Returns:**
valor String

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Nombre de fuente usado por defecto para fuentes que están ausentes en el equipo. Cuando el documento PDF que se guarda en PDF contiene fuentes que no están disponibles en el propio documento ni en el dispositivo, la API reemplaza estas fuentes con la fuente predeterminada (si se encuentra una fuente con {@code DefaultFontName} en el dispositivo)

### setTempPath {#setTempPath-java.lang.String-}
Ruta para archivos temporales.
