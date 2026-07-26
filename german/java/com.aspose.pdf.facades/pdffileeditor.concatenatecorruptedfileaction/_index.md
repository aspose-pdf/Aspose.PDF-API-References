---
title: "PdfFileEditor.ConcatenateCorruptedFileAction"
linktitle: "PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Aktion, die ausgeführt wird, wenn im Zusammenführungsprozess eine beschädigte Datei gefunden wird."
type: docs
weight: 420
url: /de/java/com.aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.Enum, com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction

```
public static final class PdfFileEditor.ConcatenateCorruptedFileAction extends com.aspose.ms.System.Enum
```

Aktion, die ausgeführt wird, wenn im Zusammenführungsprozess eine beschädigte Datei gefunden wird.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [ConcatenateIgnoringCorrupted](#ConcatenateIgnoringCorrupted) | Wenn eine beschädigte Datei gefunden wurde, dann stoppen Sie die Verkettung nicht und verarbeiten die beschädigte Datei nicht. Die Liste der beschädigten Dateien ist über die Eigenschaft Failures zugänglich. |
| [ConcatenateIgnoringCorruptedObjects](#ConcatenateIgnoringCorruptedObjects) | Wenn ein beschädigtes Objekt im Quelldokument gefunden wird, wird der Vorgang nicht gestoppt und das beschädigte Objekt wird nur ignoriert. |
| [StopWithError](#StopWithError) | Wenn eine beschädigte Datei gefunden wurde, dann stoppen Sie den Verkettungsprozess und geben einen Fehler zurück. |

### ConcatenateIgnoringCorrupted {#ConcatenateIgnoringCorrupted}
```
public static final int ConcatenateIgnoringCorrupted
```

Wenn eine beschädigte Datei gefunden wurde, dann stoppen Sie die Verkettung nicht und verarbeiten die beschädigte Datei nicht. Die Liste der beschädigten Dateien ist über die Eigenschaft Failures zugänglich.

### ConcatenateIgnoringCorruptedObjects {#ConcatenateIgnoringCorruptedObjects}
```
public static final int ConcatenateIgnoringCorruptedObjects
```

Wenn ein beschädigtes Objekt im Quelldokument gefunden wird, wird der Vorgang nicht gestoppt und das beschädigte Objekt wird nur ignoriert.

### StopWithError {#StopWithError}
```
public static final int StopWithError
```

Wenn eine beschädigte Datei gefunden wurde, dann stoppen Sie den Verkettungsprozess und geben einen Fehler zurück.
