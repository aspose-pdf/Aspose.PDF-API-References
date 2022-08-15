---
title: MakeBooklet
second_title: Aspose.PDF für .NET-API-Referenz
description: Erstellt eine Broschüre aus der Eingabedatei in die Ausgabedatei.
type: docs
weight: 330
url: /de/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_8}

Erstellt eine Broschüre aus der Eingabedatei in die Ausgabedatei.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Geben Sie Pfad und Namen der PDF-Datei ein. |
| outputFile | String | Pfad und Name der PDF-Datei ausgeben. |

### Rückgabewert

boolean – Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet_2}

Erstellt eine Broschüre vom InputStream zum OutputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | PDF-Stream eingeben. |
| outputStream | Stream | PDF-Stream ausgeben. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_9}

Erstellt eine Broschüre aus der Eingabedatei in die Ausgabedatei.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Geben Sie Pfad und Namen der PDF-Datei ein. |
| outputFile | String | Pfad und Name der PDF-Datei ausgeben. |
| pageSize | PageSize | Die Seitengröße der ausgegebenen PDF-Datei. |

### Rückgabewert

True, wenn der Vorgang erfolgreich ist.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_3}

Erstellt eine Broschüre aus dem Eingabestrom und speichert das Ergebnis im Ausgabestrom.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | PDF-Stream eingeben. |
| outputStream | Stream | PDF-Stream ausgeben. |
| pageSize | PageSize | Die Seitengröße der ausgegebenen PDF-Datei. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_11}

Erstellt ein benutzerdefiniertes Booklet von der ersten Eingabedatei bis zur Ausgabedatei.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Die Eingabedatei. |
| outputFile | String | Pfad und Name der PDF-Datei ausgeben. |
| leftPages | Int32[] | Die linken Seiten des Heftes. |
| rightPages | Int32[] | Die rechten Seiten des Heftes. |

### Rückgabewert

boolean – Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_5}

Erstellt ein benutzerdefiniertes Booklet vom firstInputStream bis zum outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Der Eingabestrom. |
| outputStream | Stream | PDF-Stream ausgeben. |
| leftPages | Int32[] | Die linken Seiten. |
| rightPages | Int32[] | Die richtigen Seiten. |

### Rückgabewert

boolean – Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_10}

Erstellt ein benutzerdefiniertes Booklet von der ersten Eingabedatei bis zur Ausgabedatei.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Die Eingabedatei. |
| outputFile | String | Pfad und Name der PDF-Datei ausgeben. |
| pageSize | PageSize | Die Seitengröße der ausgegebenen PDF-Datei. |
| leftPages | Int32[] | Die linken Seiten. |
| rightPages | Int32[] | Die richtigen Seiten. |

### Rückgabewert

boolean – Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_4}

Erstellt ein Booklet vom firstInputStream bis zum outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Der Eingabestrom. |
| outputStream | Stream | PDF-Stream ausgeben. |
| pageSize | PageSize | Die Seitengröße der ausgegebenen PDF-Datei. |
| leftPages | Int32[] | Die linken Seiten. |
| rightPages | Int32[] | Die richtigen Seiten. |

### Rückgabewert

boolean – Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quelldateipfad. |
| pageSize | PageSize | Gewünschte Seitengröße. |
| leftPages | Int32[] | Array von Seitenzahlen, die links platziert werden sollen. |
| rightPages | Int32[] | Array von Seitenzahlen, die rechts platziert werden sollen. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

Broschüre aus PDF-Datei erstellen und in HttpResponse speichern.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Dokumentstrom eingeben. |
| pageSize | PageSize | Gewünschte Seitengröße. |
| leftPages | Int32[] | Array von Seitenzahlen, die links platziert werden. |
| rightPages | Int32[] | Array von Seitenzahlen, die rechts platziert werden. |
| response | HttpResponse | HttpResponse-Objekt. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quelldateipfad. |
| pageSize | PageSize | Gewünschte Seitengröße in der Ausgabedatei. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

True, wenn der Vorgang erfolgreich ist.

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Dokumentstrom eingeben. |
| pageSize | PageSize | Gewünschte Seitengröße in der Ausgabedatei. |
| response | HttpResponse | Response-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn das Booklet erfolgreich erstellt wurde.

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
