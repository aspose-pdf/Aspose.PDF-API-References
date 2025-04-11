---
title: PdfFileEditor.TrySplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Teilt die Pdf-Datei von der ersten Seite an an einen angegebenen Ort und speichert den vorderen Teil als neue Datei
type: docs
weight: 460
url: /de/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Teilt die Pdf-Datei von der ersten Seite an an einen angegebenen Ort und speichert den vorderen Teil als neue Datei.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quell-Pdf-Datei. |
| location | Int32 | Der Teilungspunkt. |
| outputFile | String | Ausgabepdf-Datei. |

### Rückgabewert

True bei Erfolg, oder false.

## Anmerkungen

Die Methode TrySplitFromFirst ist wie die Methode SplitFromFirst, mit dem Unterschied, dass die Methode TrySplitFromFirst keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Teilt von Anfang an an einen angegebenen Ort und speichert den vorderen Teil im Ausgabestream.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Quell-Pdf-Datei-Stream. |
| location | Int32 | Der Teilungspunkt. |
| outputStream | Stream | Ausgabedatei-Stream. |

### Rückgabewert

True bei Erfolg, oder false.

## Anmerkungen

Die Streams werden NACH dieser Operation NICHT geschlossen. Die Methode TrySplitFromFirst ist wie die Methode SplitFromFirst, mit dem Unterschied, dass die Methode TrySplitFromFirst keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)


## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

Teilt das Dokument von der ersten Seite an an einen Ort und speichert das Ergebnis in HttpResponse-Objekten.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quell-Dateiname. |
| location | Int32 | Teilungspunkt. |
| response | HttpResponse | HttpResponse-Objekte. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TrySplitFromFirst ist wie die Methode SplitFromFirst, mit dem Unterschied, dass die Methode TrySplitFromFirst keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

Teilt das Dokument von Anfang an an einen angegebenen Ort und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Stream des Quelldokuments. |
| location | Int32 | Der Teilungspunkt. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TrySplitFromFirst ist wie die Methode SplitFromFirst, mit dem Unterschied, dass die Methode TrySplitFromFirst keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)