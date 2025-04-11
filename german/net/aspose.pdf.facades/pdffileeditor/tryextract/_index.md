---
title: PdfFileEditor.TryExtract
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Extrahiert Seiten aus Eingabedateien und speichert sie als neue Pdf-Datei
type: docs
weight: 410
url: /de/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

Extrahiert Seiten aus der Eingabedatei und speichert sie als neue Pdf-Datei.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad zur Eingabe-Pdf-Datei. |
| startPage | Int32 | Startseitenzahl. |
| endPage | Int32 | Endseitenzahl. |
| outputFile | String | Pfad zur Ausgabepdf-Datei. |

### Rückgabewert

True bei Erfolg, oder false.

## Bemerkungen

Die TryExtract-Methode ist wie die Extract-Methode, mit dem Unterschied, dass die TryExtract-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad zur Eingabedatei. |
| pageNumber | Int32[] | Index der Seite aus der Eingabedatei. |
| outputFile | String | Pfad zur Ausgabedatei. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Bemerkungen

Die TryExtract-Methode ist wie die Extract-Methode, mit dem Unterschied, dass die TryExtract-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue Pdf-Datei.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabedatei-Stream. |
| pageNumber | Int32[] | Index der Seite aus der Eingabedatei. |
| outputStream | Stream | Ausgabedatei-Stream. |

### Rückgabewert

True bei Erfolg, oder false.

## Bemerkungen

Die TryExtract-Methode ist wie die Extract-Methode, mit dem Unterschied, dass die TryExtract-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)


## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

Extrahiert die angegebenen Seiten aus der Quelldatei und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Stream des Quelldokuments. |
| pageNumber | Int32[] | Array von Seitennummern, die extrahiert werden. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Bemerkungen

Die TryExtract-Methode ist wie die Extract-Methode, mit dem Unterschied, dass die TryExtract-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

Extrahiert die angegebenen Seiten aus der Quelldatei und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad zur Quelldatei. |
| pageNumber | Int32[] | Array von Seitennummern, die extrahiert werden. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Bemerkungen

Die TryExtract-Methode ist wie die Extract-Methode, mit dem Unterschied, dass die TryExtract-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)