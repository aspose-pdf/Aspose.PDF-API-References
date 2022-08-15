---
title: TryInsert
second_title: Aspose.PDF für .NET-API-Referenz
description: Fügt Seiten aus einer anderen Datei in die PDF-Eingabedatei ein.
type: docs
weight: 450
url: /de/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_2}

Fügt Seiten aus einer anderen Datei in die PDF-Eingabedatei ein.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | PDF-Datei eingeben. |
| insertLocation | Int32 | Position in Eingabedatei einfügen. |
| portFile | String | Seiten aus der Pdf-Datei. |
| pageNumber | Int32[] | Die Seitenzahl der portierten in portFile. |
| outputFile | String | PDF-Datei ausgeben. |

### Rückgabewert

Wahr für Erfolg oder falsch.

### Bemerkungen

Die TryInsert-Methode ist wie die Insert-Methode, außer dass die TryInsert -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Fügt Seiten aus einer anderen Datei in die PDF-Eingabedatei ein.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabestrom der PDF-Datei. |
| insertLocation | Int32 | Position in Eingabedatei einfügen. |
| portStream | Stream | Stream der PDF-Datei für Seiten. |
| pageNumber | Int32[] | Die Seitenzahl der portierten in portFile. |
| outputStream | Stream | Ausgabestrom. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryInsert-Methode ist wie die Insert-Methode, außer dass die TryInsert -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

Fügt den Inhalt der Datei in die Quelldatei ein und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quelldateiname. |
| insertLocation | Int32 | Seitenzahl, wo die zweite Datei eingefügt wird. |
| portFile | String | Pfad zur einzufügenden Datei. |
| pageNumber | Int32[] | Array von Seitenzahlen in der Quelldatei, die eingefügt werden. |
| response | HttpResponse | Antwortobjekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryInsert-Methode ist wie die Insert-Methode, außer dass die TryInsert -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

Fügt ein Dokument in ein anderes Dokument ein und speichert das Ergebnis im Antwortobjekt.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Mit Quelldokument streamen |
| insertLocation | Int32 | Ort, an dem ein anderes Dokument eingefügt wird. |
| portStream | Stream | Einzufügendes Dokument. |
| pageNumber | Int32[] | Array von Seitenzahlen im zweiten Dokument, das eingefügt wird. |
| response | HttpResponse | Antwortobjekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryInsert-Methode ist wie die Insert-Methode, außer dass die TryInsert -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
