---
title: PdfFileEditor.SplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Teilt von der angegebenen Position und speichert den hinteren Teil als neue Datei
type: docs
weight: 360
url: /de/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

Teilt von der angegebenen Position und speichert den hinteren Teil als neuen Datei-Stream.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Quell-Pdf-Datei-Stream. |
| location | Int32 | Die Teilungsposition. |
| outputStream | Stream | Ausgabe-Pdf-Datei-Stream. |

### Rückgabewert

True für Erfolg oder false.

## Bemerkungen

Die Streams werden NACH dieser Operation NICHT geschlossen, es sei denn, CloseConcatedStreams ist angegeben.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

Teilt von der Position und speichert den hinteren Teil als neue Datei.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quell-Pdf-Datei. |
| location | Int32 | Die Teilungsposition. |
| outputFile | String | Ausgabe-Pdf-Dateipfad. |

### Rückgabewert

True für Erfolg oder false.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

Teilt von der angegebenen Position und speichert den hinteren Teil als neuen Datei-Stream.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Quell-Pdf-Datei-Stream. |
| location | Int32 | Die Teilungsposition. |
| outputStream | Stream | Ausgabe-Pdf-Datei-Stream. |

### Rückgabewert

True für Erfolg oder false.

## Bemerkungen

Die Streams werden NACH dieser Operation NICHT geschlossen, es sei denn, CloseConcatedStreams ist angegeben.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)