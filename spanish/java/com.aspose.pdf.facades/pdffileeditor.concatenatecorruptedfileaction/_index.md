---
title: "PdfFileEditor.ConcatenateCorruptedFileAction"
linktitle: "PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Acción realizada cuando se encontró un archivo corrupto en el proceso de concatenación."
type: docs
weight: 420
url: /es/java/com.aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.Enum, com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction

```
public static final class PdfFileEditor.ConcatenateCorruptedFileAction extends com.aspose.ms.System.Enum
```

Acción realizada cuando se encontró un archivo corrupto en el proceso de concatenación.

## Campos

| Campo | Descripción |
| --- | --- |
| [ConcatenateIgnoringCorrupted](#ConcatenateIgnoringCorrupted) | Si se encontró un archivo corrupto, entonces no detenga la concatenación y no procese el archivo corrupto. La lista de archivos corruptos es accesible en la propiedad Failures. |
| [ConcatenateIgnoringCorruptedObjects](#ConcatenateIgnoringCorruptedObjects) | Cuando se encuentre un objeto corrupto en el documento fuente, el proceso no se detendrá y solo se ignorará el objeto corrupto. |
| [StopWithError](#StopWithError) | Si se encontró un archivo corrupto, entonces detenga el proceso de concatenación y devuelva un error. |

### ConcatenateIgnoringCorrupted {#ConcatenateIgnoringCorrupted}
```
public static final int ConcatenateIgnoringCorrupted
```

Si se encontró un archivo corrupto, entonces no detenga la concatenación y no procese el archivo corrupto. La lista de archivos corruptos es accesible en la propiedad Failures.

### ConcatenateIgnoringCorruptedObjects {#ConcatenateIgnoringCorruptedObjects}
```
public static final int ConcatenateIgnoringCorruptedObjects
```

Cuando se encuentre un objeto corrupto en el documento fuente, el proceso no se detendrá y solo se ignorará el objeto corrupto.

### StopWithError {#StopWithError}
```
public static final int StopWithError
```

Si se encontró un archivo corrupto, entonces detenga el proceso de concatenación y devuelva un error.
