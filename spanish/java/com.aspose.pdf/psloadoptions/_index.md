---
title: "PsLoadOptions"
linktitle: "PsLoadOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa opciones para cargar/importar un archivo .mht en un documento pdf."
type: docs
weight: 4060
url: /es/java/com.aspose.pdf/psloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PsLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PsLoadOptions

```
public final class PsLoadOptions extends LoadOptions
```

Representa opciones para cargar/importar un archivo .mht en un documento pdf.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PsLoadOptions](#PsLoadOptions--) | Crea opciones de carga para convertir PostScript en un documento pdf con una ruta base vacía. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getFontsFolders](#getFontsFolders--) | Obtiene las rutas de las carpetas de fuentes. Las carpetas con fuentes adicionales para la conversión. |
| [isConvertFontsToTTF](#isConvertFontsToTTF--) | Especifica si se deben guardar las fuentes no TrueType en TTF. Reduce significativamente el volumen del documento resultante en la conversión de PS a PDF y aumenta la velocidad de conversión de archivos PS con una gran cantidad de texto en fuentes no TrueType a cualquier formato de salida. Sin embargo, hay un pequeño desplazamiento vertical del texto al convertir un archivo PostSctipt a imagen. |
| [setConvertFontsToTTF](#setConvertFontsToTTF-boolean-) | Especifica si se deben guardar las fuentes no TrueType en TTF. Reduce significativamente el volumen del documento resultante en la conversión de PS a PDF y aumenta la velocidad de conversión de archivos PS con una gran cantidad de texto en fuentes no TrueType a cualquier formato de salida. Sin embargo, hay un pequeño desplazamiento vertical del texto al convertir un archivo PostSctipt a imagen. |
| [setFontsFolders](#setFontsFolders-java.lang.String:A-) | Establece las rutas de las carpetas de fuentes. Las carpetas con fuentes adicionales para la conversión. |

### PsLoadOptions {#PsLoadOptions--}
```
public PsLoadOptions()
```

Crea opciones de carga para convertir PostScript en un documento pdf con una ruta base vacía.

### getFontsFolders {#getFontsFolders--}
```
public String [] getFontsFolders()
```

Obtiene las rutas de las carpetas de fuentes. Las carpetas con fuentes adicionales para la conversión.

**Returns:**
matriz de valores String

### isConvertFontsToTTF {#isConvertFontsToTTF--}
```
public final boolean isConvertFontsToTTF()
```

Especifica si se deben guardar las fuentes no TrueType en TTF. Reduce significativamente el volumen del documento resultante en la conversión de PS a PDF y aumenta la velocidad de conversión de archivos PS con una gran cantidad de texto en fuentes no TrueType a cualquier formato de salida. Sin embargo, hay un pequeño desplazamiento vertical del texto al convertir un archivo PostSctipt a imagen.

**Returns:**
valor booleano

### setConvertFontsToTTF {#setConvertFontsToTTF-boolean-}
```
public final void setConvertFontsToTTF(boolean value)
```

Especifica si se deben guardar las fuentes no TrueType en TTF. Reduce significativamente el volumen del documento resultante en la conversión de PS a PDF y aumenta la velocidad de conversión de archivos PS con una gran cantidad de texto en fuentes no TrueType a cualquier formato de salida. Sin embargo, hay un pequeño desplazamiento vertical del texto al convertir un archivo PostSctipt a imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setFontsFolders {#setFontsFolders-java.lang.String:A-}
Establece las rutas de las carpetas de fuentes. Las carpetas con fuentes adicionales para la conversión.
