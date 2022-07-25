---
title: MakeNUp
second_title: Aspose.PDF für .NET-API-Referenz
description: Erstellt ein N-up-Dokument aus der ersten Eingabedatei in die Ausgabedatei.
type: docs
weight: 340
url: /de/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(string, string, int, int) {#makenup_8}

Erstellt ein N-up-Dokument aus der ersten Eingabedatei in die Ausgabedatei.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Geben Sie Pfad und Namen der PDF-Datei ein. |
| outputFile | String | Pfad und Name der PDF-Datei ausgeben. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl Zeilen. |

### Rückgabewert

boolean – Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

Erstellt ein N-up-Dokument aus dem Eingabestrom und speichert das Ergebnis im Ausgabestrom.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | PDF-Stream eingeben. |
| outputStream | Stream | PDF-Stream ausgeben. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl Zeilen. |

### Rückgabewert

boolean – Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

Erstellt ein N-up-Dokument vom ersten Eingabestrom zum Ausgabestrom.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | PDF-Stream eingeben. |
| outputStream | Stream | PDF-Stream ausgeben. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl Zeilen. |
| pageSize | PageSize | Die Seitengröße der ausgegebenen PDF-Datei. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

Erstellt ein N-up-Dokument aus den beiden PDF-Eingabedateien in eine Ausgabedatei. Jede Seite der Ausgabedatei enthält zwei Seiten, eine Seite stammt aus der ersten Eingabedatei und eine andere aus der zweiten Eingabedatei. Die beiden Seiten werden horizontal gestapelt.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputFile | String | erste Eingabedatei. |
| secondInputFile | String | zweite Eingabedatei. |
| outputFile | String | Pfad und Name der PDF-Datei ausgeben. |

### Rückgabewert

boolean – Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

Erzeugt ein N-up-Dokument aus den beiden PDF-Eingabeströmen in outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputStream | Stream | erster Eingabestrom. |
| secondInputStream | Stream | zweiter Eingabestrom. |
| outputStream | Stream | PDF-Stream ausgeben. |

### Rückgabewert

boolean – Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_11}

Erstellt ein N-up-Dokument aus den PDF-Dateien mit mehreren Eingaben in eine Ausgabedatei. Jede Seite der Ausgabedatei enthält mehrere Seiten, die mit den Seiten in den Eingabedateien mit derselben Seitenzahl kombiniert werden. Die Multi-Seiten werden horizontal gestapelt, wenn isSidewise wahr ist, und vertikal gestapelt, wenn isSidewise falsch ist.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFiles | String[] | Geben Sie PDF-Dateien ein. |
| outputFile | String | Pfad und Name der PDF-Datei ausgeben. |
| isSidewise | Boolean | Aufgestapelt, wahr für horizontal und falsch für vertikal. |

### Rückgabewert

boolean – Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_5}

Erzeugt N-up-Dokumente aus den Multi-Input-PDF-Streams in OutputStream. Jede Seite von OutputStream enthält mehrere Seiten, die mit den Seiten in den Input-Streams derselben Seitennummer kombiniert werden. Die mehreren Seiten werden horizontal gestapelt , wenn isSidewise wahr ist, und vertikal gestapelt, wenn isSidewise falsch ist.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStreams | Stream[] | Geben Sie PDF-Streams ein. |
| outputStream | Stream | PDF-Stream ausgeben. |
| isSidewise | Boolean | Aufgestapelt, wahr für horizontal und falsch für vertikal. |

### Rückgabewert

boolean – Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_9}

Erstellt ein N-up-Dokument aus der Eingabedatei in die Ausgabedatei.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Geben Sie Pfad und Namen der PDF-Datei ein. |
| outputFile | String | Pfad und Name der PDF-Datei ausgeben. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl Zeilen. |
| pageSize | PageSize | Die Seitengröße der ausgegebenen PDF-Datei. |

### Rückgabewert

boolean – Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeNUp(Stream, int, int, PageSize, HttpResponse) {#makenup}

Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool MakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Stream des Quelldokuments. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Reihenanzahl. |
| pageSize | PageSize | Seitengröße in der Ergebnisdatei. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeNUp(string, int, int, PageSize, HttpResponse) {#makenup_6}

Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool MakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad zur Quelldatei. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Reihenanzahl. |
| pageSize | PageSize | Seitengröße in der Ergebnisdatei. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Siehe auch

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeNUp(string, int, int, HttpResponse) {#makenup_7}

Erstellt ein Dokument mit mehreren Seiten und speichert das Ergebnis in HttpResponse.

```csharp
public bool MakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quelldateiname. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Reihenanzahl. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## MakeNUp(Stream, int, int, HttpResponse) {#makenup_1}

Erstellt ein Dokument mit mehreren Seiten und speichert das Ergebnis in HttpResponse.

```csharp
public bool MakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Stream des Eingabedokuments. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Reihenanzahl. |
| response | HttpResponse | HttpResponse wo das Ergebnis gespeichert wird. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
