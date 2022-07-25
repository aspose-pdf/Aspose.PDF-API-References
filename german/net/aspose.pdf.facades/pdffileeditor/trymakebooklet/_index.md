---
title: TryMakeBooklet
second_title: Aspose.PDF für .NET-API-Referenz
description: Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten.
type: docs
weight: 460
url: /de/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, PageSize, int[], int[], HttpResponse) {#trymakebooklet_6}

Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
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

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryMakeBooklet-Methode ist wie die MakeBooklet-Methode, außer dass die TryMakeBooklet -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

Broschüre aus PDF-Datei erstellen und in HttpResponse speichern.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Dokumentstrom eingeben. |
| pageSize | PageSize | Gewünschte Seitengröße. |
| leftPages | Int32[] | Array von Seitenzahlen, die links platziert werden. |
| rightPages | Int32[] | Array von Seitenzahlen, die rechts platziert werden. |
| response | HttpResponse | HttpResponse-Objekt. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryMakeBooklet-Methode ist wie die MakeBooklet-Methode, außer dass die TryMakeBooklet -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quelldateipfad. |
| pageSize | PageSize | Gewünschte Seitengröße in der Ausgabedatei. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

True, wenn der Vorgang erfolgreich ist.

### Bemerkungen

Die TryMakeBooklet-Methode ist wie die MakeBooklet-Methode, außer dass die TryMakeBooklet -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Dokumentstrom eingeben. |
| pageSize | PageSize | Gewünschte Seitengröße in der Ausgabedatei. |
| response | HttpResponse | Response-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn das Booklet erfolgreich erstellt wurde.

### Bemerkungen

Die TryMakeBooklet-Methode ist wie die MakeBooklet-Methode, außer dass die TryMakeBooklet -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Erstellt eine Broschüre aus der Eingabedatei in die Ausgabedatei.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Geben Sie Pfad und Namen der PDF-Datei ein. |
| outputFile | String | Pfad und Name der PDF-Datei ausgeben. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryMakeBooklet-Methode ist wie die MakeBooklet-Methode, außer dass die TryMakeBooklet -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet_2}

Erstellt eine Broschüre vom InputStream zum OutputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | PDF-Stream eingeben. |
| outputStream | Stream | PDF-Stream ausgeben. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryMakeBooklet-Methode ist wie die MakeBooklet-Methode, außer dass die TryMakeBooklet -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_9}

Erstellt eine Broschüre aus der Eingabedatei in die Ausgabedatei.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Geben Sie Pfad und Namen der PDF-Datei ein. |
| outputFile | String | Pfad und Name der PDF-Datei ausgeben. |
| pageSize | PageSize | Die Seitengröße der ausgegebenen PDF-Datei. |

### Rückgabewert

True, wenn der Vorgang erfolgreich ist.

### Bemerkungen

Die TryMakeBooklet-Methode ist wie die MakeBooklet-Methode, außer dass die TryMakeBooklet -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_3}

Erstellt eine Broschüre aus dem Eingabestrom und speichert das Ergebnis im Ausgabestrom.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | PDF-Stream eingeben. |
| outputStream | Stream | PDF-Stream ausgeben. |
| pageSize | PageSize | Die Seitengröße der ausgegebenen PDF-Datei. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryMakeBooklet-Methode ist wie die MakeBooklet-Methode, außer dass die TryMakeBooklet -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_11}

Erstellt ein benutzerdefiniertes Booklet von der ersten Eingabedatei bis zur Ausgabedatei.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Die Eingabedatei. |
| outputFile | String | Pfad und Name der PDF-Datei ausgeben. |
| leftPages | Int32[] | Die linken Seiten des Heftes. |
| rightPages | Int32[] | Die rechten Seiten des Heftes. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryMakeBooklet-Methode ist wie die MakeBooklet-Methode, außer dass die TryMakeBooklet -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_5}

Erstellt ein benutzerdefiniertes Booklet vom firstInputStream bis zum outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Der Eingabestrom. |
| outputStream | Stream | PDF-Stream ausgeben. |
| leftPages | Int32[] | Die linken Seiten. |
| rightPages | Int32[] | Die richtigen Seiten. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryMakeBooklet-Methode ist wie die MakeBooklet-Methode, außer dass die TryMakeBooklet -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_10}

Erstellt ein benutzerdefiniertes Booklet von der ersten Eingabedatei bis zur Ausgabedatei.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
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

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryMakeBooklet-Methode ist wie die MakeBooklet-Methode, außer dass die TryMakeBooklet -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_4}

Erstellt ein Booklet vom firstInputStream bis zum outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
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

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryMakeBooklet-Methode ist wie die MakeBooklet-Methode, außer dass die TryMakeBooklet -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
