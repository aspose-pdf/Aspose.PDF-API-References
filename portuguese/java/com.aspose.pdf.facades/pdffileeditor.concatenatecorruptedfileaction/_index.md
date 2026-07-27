---
title: "PdfFileEditor.ConcatenateCorruptedFileAction"
linktitle: "PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Referência da API Aspose.PDF para Java"
description: "Ação executada quando um arquivo corrompido é encontrado no processo de concatenação."
type: docs
weight: 420
url: /pt/java/com.aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.Enum, com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction

```
public static final class PdfFileEditor.ConcatenateCorruptedFileAction extends com.aspose.ms.System.Enum
```

Ação executada quando um arquivo corrompido é encontrado no processo de concatenação.

## Campos

| Campo | Descrição |
| --- | --- |
| [ConcatenateIgnoringCorrupted](#ConcatenateIgnoringCorrupted) | Se um arquivo corrompido for encontrado, então não interrompa a concatenação e não processe o arquivo corrompido. A lista de arquivos corrompidos está acessível na propriedade Failures. |
| [ConcatenateIgnoringCorruptedObjects](#ConcatenateIgnoringCorruptedObjects) | Quando um objeto corrompido for encontrado no documento de origem, o processo não será interrompido e apenas o objeto corrompido será ignorado. |
| [StopWithError](#StopWithError) | Se um arquivo corrompido for encontrado, então interrompa o processo de concatenação e retorne um erro. |

### ConcatenateIgnoringCorrupted {#ConcatenateIgnoringCorrupted}
```
public static final int ConcatenateIgnoringCorrupted
```

Se um arquivo corrompido for encontrado, então não interrompa a concatenação e não processe o arquivo corrompido. A lista de arquivos corrompidos está acessível na propriedade Failures.

### ConcatenateIgnoringCorruptedObjects {#ConcatenateIgnoringCorruptedObjects}
```
public static final int ConcatenateIgnoringCorruptedObjects
```

Quando um objeto corrompido for encontrado no documento de origem, o processo não será interrompido e apenas o objeto corrompido será ignorado.

### StopWithError {#StopWithError}
```
public static final int StopWithError
```

Se um arquivo corrompido for encontrado, então interrompa o processo de concatenação e retorne um erro.
