---
title: PdfFileEditor.SplitToBulks
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Teilt die Pdf-Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein.
type: docs
weight: 350
url: /de/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Teilt die Pdf-Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Eingabe-PDF-Datei. |
| numberOfPage | Int32[][] | Array, das ein Array von doppelten Elementen enthält, das die Start- und Endseiten des Dokuments angibt. |

### Rückgabewert

Ausgabe-PDF-Streams, jeder Stream puffert ein PDF-Dokument.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Teilt die Pdf-Datei in mehrere Dokumente. Die Dokumente können einseitig oder mehrseitig sein.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-PDF-Stream. |
| numberOfPage | Int32[][] | Die Startseite und die Endseite jedes Dokuments. |

### Rückgabewert

Ausgabe-PDF-Streams, jeder Stream puffert ein PDF-Dokument.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)