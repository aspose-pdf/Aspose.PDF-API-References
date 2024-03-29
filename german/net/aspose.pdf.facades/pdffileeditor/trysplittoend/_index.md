---
title: TrySplitToEnd
second_title: Aspose.PDF für .NET-API-Referenz
description: Trennt den Speicherort und speichert den hinteren Teil als neue Datei.
type: docs
weight: 500
url: /de/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_2}

Trennt den Speicherort und speichert den hinteren Teil als neue Datei.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quell-Pdf-Datei. |
| location | Int32 | Die Splitting-Position. |
| outputFile | String | Pfad der PDF-Datei ausgeben. |

### Rückgabewert

Wahr für Erfolg oder falsch.

### Bemerkungen

Die TrySplitToEnd-Methode ist wie die SplitToEnd-Methode, außer dass die TrySplitToEnd -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Trennt den angegebenen Speicherort und speichert den hinteren Teil als neuen Dateistream.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Quell-Pdf-Datei-Stream. |
| location | Int32 | Die Splitting-Position. |
| outputStream | Stream | PDF-Datei-Stream ausgeben. |

### Rückgabewert

Wahr für Erfolg oder falsch.

### Bemerkungen

Die Streams werden nach dieser Operation NICHT geschlossen, es sei denn, CloseConcatedStreams ist angegeben. Die TrySplitToEnd-Methode ist wie die SplitToEnd-Methode, außer dass die TrySplitToEnd -Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, HttpResponse) {#trysplittoend_1}

Teilt vom angegebenen Ort und speichert den hinteren Teil im HttpResponse-Objekt.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Quelldokument-Stream. |
| location | Int32 | Split-Punkt. |
| response | HttpResponse | HttpResponse-Objekt. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TrySplitToEnd-Methode ist wie die SplitToEnd-Methode, außer dass die TrySplitToEnd -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TrySplitToEnd(string, int, HttpResponse) {#trysplittoend_3}

Teilt vom angegebenen Ort und speichert den hinteren Teil im HttpResponse-Objekt.

```csharp
public bool TrySplitToEnd(string inputFile, int location, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quelldateiname. |
| location | Int32 | Split-Punkt. |
| response | HttpResponse | HttpResponse-Objekte. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TrySplitToEnd-Methode ist wie die SplitToEnd-Methode, außer dass die TrySplitToEnd -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
