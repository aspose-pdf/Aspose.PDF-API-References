---
title: PdfFileEditor.SplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Teilt die Pdf-Datei von der ersten Seite an bis zu einem angegebenen Ort und speichert den vorderen Teil als neue Datei
type: docs
weight: 340
url: /de/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

Teilt die Pdf-Datei von der ersten Seite an bis zu einem angegebenen Ort und speichert den vorderen Teil als neue Datei.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quell-Pdf-Datei. |
| location | Int32 | Der Teilungspunkt. |
| outputFile | String | Ausgabedatei Pdf. |

### Rückgabewert

True für Erfolg, oder false.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

Teilt von Anfang bis zu einem angegebenen Ort und speichert den vorderen Teil im Ausgabestream.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Quell-Pdf-Datei Stream. |
| location | Int32 | Der Teilungspunkt. |
| outputStream | Stream | Ausgabedatei Stream. |

### Rückgabewert

True für Erfolg, oder false.

## Bemerkungen

Die Streams werden NACH dieser Operation NICHT geschlossen.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)