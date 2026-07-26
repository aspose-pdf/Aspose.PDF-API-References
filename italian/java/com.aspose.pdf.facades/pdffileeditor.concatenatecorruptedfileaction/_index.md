---
title: "PdfFileEditor.ConcatenateCorruptedFileAction"
linktitle: "PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Azione eseguita quando si incontra un file corrotto nel processo di concatenazione."
type: docs
weight: 420
url: /it/java/com.aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.Enum, com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction

```
public static final class PdfFileEditor.ConcatenateCorruptedFileAction extends com.aspose.ms.System.Enum
```

Azione eseguita quando si incontra un file corrotto nel processo di concatenazione.

## Campi

| Campo | Descrizione |
| --- | --- |
| [ConcatenateIgnoringCorrupted](#ConcatenateIgnoringCorrupted) | Se si incontra un file corrotto, non interrompere la concatenazione e non elaborare il file corrotto. L'elenco dei file corrotti è accessibile nella proprietà Failures. |
| [ConcatenateIgnoringCorruptedObjects](#ConcatenateIgnoringCorruptedObjects) | Quando si incontra un oggetto corrotto nel documento di origine, il processo non verrà interrotto e verrà ignorato solo l'oggetto corrotto. |
| [StopWithError](#StopWithError) | Se si incontra un file corrotto, interrompere il processo di concatenazione e restituire un errore. |

### ConcatenateIgnoringCorrupted {#ConcatenateIgnoringCorrupted}
```
public static final int ConcatenateIgnoringCorrupted
```

Se si incontra un file corrotto, non interrompere la concatenazione e non elaborare il file corrotto. L'elenco dei file corrotti è accessibile nella proprietà Failures.

### ConcatenateIgnoringCorruptedObjects {#ConcatenateIgnoringCorruptedObjects}
```
public static final int ConcatenateIgnoringCorruptedObjects
```

Quando si incontra un oggetto corrotto nel documento di origine, il processo non verrà interrotto e verrà ignorato solo l'oggetto corrotto.

### StopWithError {#StopWithError}
```
public static final int StopWithError
```

Se si incontra un file corrotto, interrompere il processo di concatenazione e restituire un errore.
