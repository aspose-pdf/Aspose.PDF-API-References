---
title: "PdfFileSanitization"
linktitle: "PdfFileSanitization"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la API de sanitización y recuperación. Úsala si no puedes crear/abrir documentos de otra manera."
type: docs
weight: 510
url: /es/java/com.aspose.pdf.facades/pdffilesanitization/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSanitization

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSanitization extends SaveableFacade implements com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery
```

Representa la API de sanitización y recuperación. Úsala si no puedes crear/abrir documentos de otra manera.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfFileSanitization](#PdfFileSanitization--) | Inicializa una nueva instancia. |

## Métodos

| Método | Descripción |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Inicializa la fachada. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Vincula una secuencia Pdf para sanitizar. |
| [bindPdf](#bindPdf-java.lang.String-) | Vincula un archivo Pdf para sanitizar. |
| [close](#close--) | Cierra la fachada. |
| [getLog](#getLog--) | Después de que el archivo se haya guardado, puedes comprobar qué se hizo con el archivo. |
| [getUseRebuildXrefAndTrailer](#getUseRebuildXrefAndTrailer--) | Permite generar un nuevo xref y trailer para el documento. |
| [getUseTrimBottom](#getUseTrimBottom--) | Permite eliminar datos después de los datos pdf. |
| [getUseTrimTop](#getUseTrimTop--) | Permite eliminar datos antes de los datos pdf. |
| [rebuildXrefAndTrailer](#rebuildXrefAndTrailer--) | Elimina el xref antiguo con trailer y crea un nuevo xref con trailer. |
| [recover](#recover--) | Recupera el documento. Usa propiedades para personalizar. |
| [save](#save-java.io.OutputStream-) | Guarda el PDF resultante en un flujo. |
| [save](#save-java.lang.String-) | Guarda el PDF resultante en un archivo. |
| [setUseRebuildXrefAndTrailer](#setUseRebuildXrefAndTrailer-boolean-) | Permite generar un nuevo xref y trailer para el documento. |
| [setUseTrimBottom](#setUseTrimBottom-boolean-) | Permite eliminar datos después de los datos pdf. |
| [setUseTrimTop](#setUseTrimTop-boolean-) | Permite eliminar datos antes de los datos pdf. |
| [trimBottom](#trimBottom--) | Elimina datos después del último %%EOF. |
| [trimTop](#trimTop--) | Elimina datos antes de %PDF. |

### PdfFileSanitization {#PdfFileSanitization--}
```
public PdfFileSanitization()
```

Inicializa una nueva instancia.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Inicializa la fachada.

### bindPdf {#bindPdf-java.io.InputStream-}
Vincula una secuencia Pdf para sanitizar.

### bindPdf {#bindPdf-java.lang.String-}
Vincula un archivo Pdf para sanitizar.

### close {#close--}
```
public void close()
```

Cierra la fachada.

### getLog {#getLog--}
```
public final List < String > getLog()
```

Después de que el archivo se haya guardado, puedes comprobar qué se hizo con el archivo.

**Returns:**
lista de elementos String

### getUseRebuildXrefAndTrailer {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```

Permite generar un nuevo xref y trailer para el documento.

**Returns:**
valor booleano

### getUseTrimBottom {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```

Permite eliminar datos después de los datos pdf.

**Returns:**
valor booleano

### getUseTrimTop {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```

Permite eliminar datos antes de los datos pdf.

**Returns:**
valor booleano

### rebuildXrefAndTrailer {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```

Elimina el xref antiguo con trailer y crea un nuevo xref con trailer.

### recover {#recover--}
```
public final void recover()
```

Recupera el documento. Usa propiedades para personalizar.

### save {#save-java.io.OutputStream-}
Guarda el PDF resultante en un flujo.

### save {#save-java.lang.String-}
Guarda el PDF resultante en un archivo.

### setUseRebuildXrefAndTrailer {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```

Permite generar un nuevo xref y trailer para el documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseTrimBottom {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```

Permite eliminar datos después de los datos pdf.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseTrimTop {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```

Permite eliminar datos antes de los datos pdf.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### trimBottom {#trimBottom--}
```
public final void trimBottom()
```

Elimina datos después del último %%EOF.

### trimTop {#trimTop--}
```
public final void trimTop()
```

Elimina datos antes de %PDF.
