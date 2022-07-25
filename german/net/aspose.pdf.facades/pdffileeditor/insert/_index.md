---
title: Insert
second_title: Aspose.PDF für .NET-API-Referenz
description: Fügt an einer Position Seiten aus einer anderen Datei in die Pdf-Datei ein.
type: docs
weight: 320
url: /de/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_3}

Fügt an einer Position Seiten aus einer anderen Datei in die Pdf-Datei ein.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | PDF-Datei eingeben. |
| insertLocation | Int32 | Position in Eingabedatei. |
| portFile | String | Die Portierungs-Pdf-Datei. |
| startPage | Int32 | Startposition in portFile. |
| endPage | Int32 | Endposition in portFile. |
| outputFile | String | PDF-Datei ausgeben. |

### Rückgabewert

Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

Fügt Seiten aus einer anderen Datei in die PDF-Eingabedatei ein.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabestrom der PDF-Datei. |
| insertLocation | Int32 | Position in Eingabedatei einfügen. |
| portStream | Stream | Stream der PDF-Datei für Seiten. |
| startPage | Int32 | Ab welcher Seite beginnen. |
| endPage | Int32 | Zu welcher Seite enden soll. |
| outputStream | Stream | Ausgabestrom. |

### Rückgabewert

Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_4}

Fügt Seiten aus einer anderen Datei in die PDF-Eingabedatei ein.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
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

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

Fügt Seiten aus einer anderen Datei in die PDF-Eingabedatei ein.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
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

True, wenn der Vorgang erfolgreich war.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], HttpResponse) {#insert_5}

Fügt den Inhalt der Datei in die Quelldatei ein und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
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

true des Einfügens war erfolgreich.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], HttpResponse) {#insert_2}

Fügt ein Dokument in ein anderes Dokument ein und speichert das Ergebnis im Antwortobjekt.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
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

True, wenn der Vorgang erfolgreich war.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
