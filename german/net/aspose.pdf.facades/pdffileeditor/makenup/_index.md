---
title: PdfFileEditor.MakeNUp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Erstellt ein NUp-Dokument aus den beiden Eingabe-PDF-Streams in outputStream
type: docs
weight: 310
url: /de/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

Erstellt ein N-Up-Dokument aus der firstInputFile in outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Eingabe-PDF-Dateipfad und -name. |
| outputFile | String | Ausgabe-PDF-Dateipfad und -name. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl der Zeilen. |

### Rückgabewert

boolean - Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

Erstellt ein N-Up-Dokument aus dem Eingabestream und speichert das Ergebnis im Ausgabestream.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-PDF-Stream. |
| outputStream | Stream | Ausgabe-PDF-Stream. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl der Zeilen. |

### Rückgabewert

boolean - Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

Erstellt ein N-Up-Dokument aus dem ersten Eingabestream in den Ausgabestream.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-PDF-Stream. |
| outputStream | Stream | Ausgabe-PDF-Stream. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl der Zeilen. |
| pageSize | PageSize | Die Seitengröße der Ausgabepdf-Datei. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

Erstellt ein N-Up-Dokument aus den beiden Eingabe-PDF-Dateien in outputFile. Jede Seite von outputFile enthält zwei Seiten, eine Seite stammt aus der ersten Eingabedatei und die andere aus der zweiten Eingabedatei. Die beiden Seiten sind horizontal übereinander gestapelt.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputFile | String | erste Eingabedatei. |
| secondInputFile | String | zweite Eingabedatei. |
| outputFile | String | Ausgabe-PDF-Dateipfad und -name. |

### Rückgabewert

boolean - Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

Erstellt ein N-Up-Dokument aus den beiden Eingabe-PDF-Streams in outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputStream | Stream | erster Eingabestream. |
| secondInputStream | Stream | zweiter Eingabestream. |
| outputStream | Stream | Ausgabe-PDF-Stream. |

### Rückgabewert

boolean - Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

Erstellt ein N-Up-Dokument aus den mehreren Eingabe-PDF-Dateien in outputFile. Jede Seite von outputFile enthält mehrere Seiten, die eine Kombination aus Seiten in den Eingabedateien mit derselben Seitennummer sind. Die mehreren Seiten sind horizontal übereinander gestapelt, wenn isSidewise wahr ist, und vertikal, wenn isSidewise falsch ist.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFiles | String[] | Eingabe-PDF-Dateien. |
| outputFile | String | Ausgabe-PDF-Dateipfad und -name. |
| isSidewise | Boolean | Stapelweise, wahr für horizontal und falsch für vertikal. |

### Rückgabewert

boolean - Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

Erstellt ein N-Up-Dokument aus den mehreren Eingabe-PDF-Streams in outputStream. Jede Seite von outputStream enthält mehrere Seiten, die eine Kombination aus Seiten in den Eingabestreams mit derselben Seitennummer sind. Die Mehrfachseiten sind horizontal übereinander gestapelt, wenn isSidewise wahr ist, und vertikal, wenn isSidewise falsch ist.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStreams | Stream[] | Eingabe-PDF-Streams. |
| outputStream | Stream | Ausgabe-PDF-Stream. |
| isSidewise | Boolean | Stapelweise, wahr für horizontal und falsch für vertikal. |

### Rückgabewert

boolean - Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_5}

Erstellt ein N-Up-Dokument aus der Eingabedatei in outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Eingabe-PDF-Dateipfad und -name. |
| outputFile | String | Ausgabe-PDF-Dateipfad und -name. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl der Zeilen. |
| pageSize | PageSize | Die Seitengröße der Ausgabepdf-Datei. |

### Rückgabewert

boolean - Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

Erstellt ein N-Up-Dokument aus der firstInputFile in outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Eingabe-PDF-Dateipfad und -name. |
| outputFile | String | Ausgabe-PDF-Dateipfad und -name. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl der Zeilen. |

### Rückgabewert

boolean - Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

Erstellt ein N-Up-Dokument aus dem Eingabestream und speichert das Ergebnis im Ausgabestream.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-PDF-Stream. |
| outputStream | Stream | Ausgabe-PDF-Stream. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl der Zeilen. |

### Rückgabewert

boolean - Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

Erstellt ein N-Up-Dokument aus dem ersten Eingabestream in den Ausgabestream.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-PDF-Stream. |
| outputStream | Stream | Ausgabe-PDF-Stream. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl der Zeilen. |
| pageSize | PageSize | Die Seitengröße der Ausgabepdf-Datei. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

Erstellt ein N-Up-Dokument aus den beiden Eingabe-PDF-Dateien in outputFile. Jede Seite von outputFile enthält zwei Seiten, eine Seite stammt aus der ersten Eingabedatei und die andere aus der zweiten Eingabedatei. Die beiden Seiten sind horizontal übereinander gestapelt.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputFile | String | erste Eingabedatei. |
| secondInputFile | String | zweite Eingabedatei. |
| outputFile | String | Ausgabe-PDF-Dateipfad und -name. |

### Rückgabewert

boolean - Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)