---
title: PdfFileEditor.TryInsert
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Fügt Seiten aus einer anderen Datei in die Eingabe-Pdf-Datei ein
type: docs
weight: 420
url: /de/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

Fügt Seiten aus einer anderen Datei in die Eingabe-Pdf-Datei ein.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Eingabe-Pdf-Datei. |
| insertLocation | Int32 | Einfügeposition in der Eingabedatei. |
| portFile | String | Seiten aus der Pdf-Datei. |
| pageNumber | Int32[] | Die Seitennummer der in portFile portierten Datei. |
| outputFile | String | Ausgabe-Pdf-Datei. |

### Rückgabewert

Wahr für Erfolg oder falsch.

## Bemerkungen

Die TryInsert-Methode ist wie die Insert-Methode, mit dem Unterschied, dass die TryInsert-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Fügt Seiten aus einer anderen Datei in die Eingabe-Pdf-Datei ein.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-Stream der Pdf-Datei. |
| insertLocation | Int32 | Einfügeposition in der Eingabedatei. |
| portStream | Stream | Stream der Pdf-Datei für Seiten. |
| pageNumber | Int32[] | Die Seitennummer der in portFile portierten Datei. |
| outputStream | Stream | Ausgabe-Stream. |

### Rückgabewert

wahr, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls falsch.

## Bemerkungen

Die TryInsert-Methode ist wie die Insert-Methode, mit dem Unterschied, dass die TryInsert-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)


## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

Fügt den Inhalt der Datei in die Quelldatei ein und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Name der Quelldatei. |
| insertLocation | Int32 | Seitennummer, an der die zweite Datei eingefügt wird. |
| portFile | String | Pfad zur Datei, die eingefügt werden soll. |
| pageNumber | Int32[] | Array von Seitennummern in der Quelldatei, die eingefügt werden sollen. |
| response | HttpResponse | Antwortobjekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

wahr, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls falsch.

## Bemerkungen

Die TryInsert-Methode ist wie die Insert-Methode, mit dem Unterschied, dass die TryInsert-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

Fügt das Dokument in ein anderes Dokument ein und speichert das Ergebnis im Antwortobjekt.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Stream mit dem Quelldokument |
| insertLocation | Int32 | Position, an der das andere Dokument eingefügt wird. |
| portStream | Stream | Dokument, das eingefügt werden soll. |
| pageNumber | Int32[] | Array von Seitennummern im zweiten Dokument, das eingefügt werden soll. |
| response | HttpResponse | Antwortobjekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

wahr, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls falsch.

## Bemerkungen

Die TryInsert-Methode ist wie die Insert-Methode, mit dem Unterschied, dass die TryInsert-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)