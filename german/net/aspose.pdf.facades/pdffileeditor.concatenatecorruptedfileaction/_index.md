---
title: Enum PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction Enum. Aktion, die ausgeführt wird, wenn eine beschädigte Datei im Verknüpfungsprozess gefunden wurde
type: docs
weight: 4470
url: /de/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction Enumeration

Aktion, die ausgeführt wird, wenn eine beschädigte Datei im Verknüpfungsprozess gefunden wurde.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| StopWithError | `0` | Wenn eine beschädigte Datei gefunden wurde, dann stoppe den Verknüpfungsprozess und gebe einen Fehler zurück. |
| ConcatenateIgnoringCorrupted | `1` | Wenn eine beschädigte Datei gefunden wurde, dann stoppe die Verknüpfung nicht und verarbeite die beschädigte Datei nicht. Die Liste der beschädigten Dateien ist im Failures-Eigenschaft zugänglich. |
| ConcatenateIgnoringCorruptedObjects | `2` | Wenn ein beschädigtes Objekt im Quelldokument gefunden wird, wird der Prozess nicht gestoppt und das beschädigte Objekt wird nur ignoriert. |

### Siehe auch

* Klasse [PdfFileEditor](../pdffileeditor/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)