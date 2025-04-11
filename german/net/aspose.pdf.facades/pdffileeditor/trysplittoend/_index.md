---
title: PdfFileEditor.TrySplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Teilt von der Position und speichert den hinteren Teil als neue Datei
type: docs
weight: 470
url: /de/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

Teilt von der Position und speichert den hinteren Teil als neue Datei.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quell-Pdf-Datei. |
| location | Int32 | Die Teilungsposition. |
| outputFile | String | Ausgabepfad der Pdf-Datei. |

### Rückgabewert

Wahr für Erfolg oder falsch.

## Bemerkungen

Die TrySplitToEnd-Methode ist wie die SplitToEnd-Methode, mit dem Unterschied, dass die TrySplitToEnd-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Teilt von der angegebenen Position und speichert den hinteren Teil als neue Datei-Stream.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Quell-Pdf-Datei-Stream. |
| location | Int32 | Die Teilungsposition. |
| outputStream | Stream | Ausgabepdf-Datei-Stream. |

### Rückgabewert

Wahr für Erfolg oder falsch.

## Bemerkungen

Die Streams werden NACH dieser Operation NICHT geschlossen, es sei denn, CloseConcatedStreams ist angegeben. Die TrySplitToEnd-Methode ist wie die SplitToEnd-Methode, mit dem Unterschied, dass die TrySplitToEnd-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)


## TrySplitToEnd(Stream, int, HttpResponse) {#trysplittoend_1}

Teilt von der angegebenen Position und speichert den hinteren Teil in das HttpResponse-Objekt.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Quell-Dokumentenstream. |
| location | Int32 | Teilungspunkt. |
| response | HttpResponse | HttpResponse-Objekt. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls falsch.

## Bemerkungen

Die TrySplitToEnd-Methode ist wie die SplitToEnd-Methode, mit dem Unterschied, dass die TrySplitToEnd-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(string, int, HttpResponse) {#trysplittoend_3}

Teilt von der angegebenen Position und speichert den hinteren Teil in das HttpResponse-Objekt.

```csharp
public bool TrySplitToEnd(string inputFile, int location, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quell-Dateiname. |
| location | Int32 | Teilungspunkt. |
| response | HttpResponse | HttpResponse-Objekte. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls falsch.

## Bemerkungen

Die TrySplitToEnd-Methode ist wie die SplitToEnd-Methode, mit dem Unterschied, dass die TrySplitToEnd-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)