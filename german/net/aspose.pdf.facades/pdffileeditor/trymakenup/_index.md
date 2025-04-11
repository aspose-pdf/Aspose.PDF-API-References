---
title: PdfFileEditor.TryMakeNUp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Erstellt ein NUp-Dokument von der firstInputFile zur outputFile
type: docs
weight: 440
url: /de/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad zur Quelldatei. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl der Zeilen. |
| pageSize | PageSize | Seitengröße in der Ergebnisdatei. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeNUp ist wie die Methode MakeNUp, mit dem Unterschied, dass die Methode TryMakeNUp keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Stream des Quelldokuments. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl der Zeilen. |
| pageSize | PageSize | Seitengröße in der Ergebnisdatei. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeNUp ist wie die Methode MakeNUp, mit dem Unterschied, dass die Methode TryMakeNUp keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Name der Quelldatei. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl der Zeilen. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeNUp ist wie die Methode MakeNUp, mit dem Unterschied, dass die Methode TryMakeNUp keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

Erstellt ein N-up-Dokument und speichert das Ergebnis im HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Stream des Eingabedokuments. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl der Zeilen. |
| response | HttpResponse | HttpResponse, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeNUp ist wie die Methode MakeNUp, mit dem Unterschied, dass die Methode TryMakeNUp keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

Erstellt ein N-Up-Dokument von der firstInputFile zur outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad und Name der Eingabe-PDF-Datei. |
| outputFile | String | Pfad und Name der Ausgabepdf-Datei. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl der Zeilen. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeNUp ist wie die Methode MakeNUp, mit dem Unterschied, dass die Methode TryMakeNUp keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

Erstellt ein N-Up-Dokument aus dem Eingabestream und speichert das Ergebnis im Ausgabestream.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-PDF-Stream. |
| outputStream | Stream | Ausgabe-PDF-Stream. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl der Zeilen. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeNUp ist wie die Methode MakeNUp, mit dem Unterschied, dass die Methode TryMakeNUp keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

Erstellt ein N-Up-Dokument vom ersten Eingabestream zum Ausgabestream.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-PDF-Stream. |
| outputStream | Stream | Ausgabe-PDF-Stream. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl der Zeilen. |
| pageSize | PageSize | Die Seitengröße der Ausgabepdf-Datei. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeNUp ist wie die Methode MakeNUp, mit dem Unterschied, dass die Methode TryMakeNUp keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

Erstellt ein N-Up-Dokument aus den beiden Eingabe-PDF-Dateien zur outputFile. Jede Seite der outputFile enthält zwei Seiten, eine Seite stammt aus der ersten Eingabedatei und die andere aus der zweiten Eingabedatei. Die beiden Seiten sind horizontal übereinander gestapelt.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputFile | String | erste Eingabedatei. |
| secondInputFile | String | zweite Eingabedatei. |
| outputFile | String | Pfad und Name der Ausgabepdf-Datei. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false

## Anmerkungen

Die Methode TryMakeNUp ist wie die Methode MakeNUp, mit dem Unterschied, dass die Methode TryMakeNUp keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

Erstellt ein N-Up-Dokument aus den beiden Eingabe-PDF-Streams zum outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputStream | Stream | erster Eingabestream. |
| secondInputStream | Stream | zweiter Eingabestream. |
| outputStream | Stream | Ausgabe-PDF-Stream. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false

## Anmerkungen

Die Methode TryMakeNUp ist wie die Methode MakeNUp, mit dem Unterschied, dass die Methode TryMakeNUp keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

Erstellt ein N-Up-Dokument aus mehreren Eingabe-PDF-Dateien zur outputFile. Jede Seite der outputFile enthält mehrere Seiten, die mit den Seiten in den Eingabedateien der gleichen Seitennummer kombiniert werden. Die mehreren Seiten sind horizontal übereinander gestapelt, wenn isSidewise true ist, und vertikal übereinander gestapelt, wenn isSidewise false ist.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFiles | String[] | Eingabe-PDF-Dateien. |
| outputFile | String | Pfad und Name der Ausgabepdf-Datei. |
| isSidewise | Boolean | Stapelweise, true für horizontal und false für vertikal. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeNUp ist wie die Methode MakeNUp, mit dem Unterschied, dass die Methode TryMakeNUp keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

Erstellt ein N-Up-Dokument aus mehreren Eingabe-PDF-Streams zum outputStream. Jede Seite des outputStream enthält mehrere Seiten, die mit den Seiten in den Eingabeströmen der gleichen Seitennummer kombiniert werden. Die mehreren Seiten sind horizontal übereinander gestapelt, wenn isSidewise true ist, und vertikal übereinander gestapelt, wenn isSidewise false ist.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStreams | Stream[] | Eingabe-PDF-Streams. |
| outputStream | Stream | Ausgabe-PDF-Stream. |
| isSidewise | Boolean | Stapelweise, true für horizontal und false für vertikal. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeNUp ist wie die Methode MakeNUp, mit dem Unterschied, dass die Methode TryMakeNUp keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

Erstellt ein N-Up-Dokument von der Eingabedatei zur outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad und Name der Eingabe-PDF-Datei. |
| outputFile | String | Pfad und Name der Ausgabepdf-Datei. |
| x | Int32 | Anzahl der Spalten. |
| y | Int32 | Anzahl der Zeilen. |
| pageSize | PageSize | Die Seitengröße der Ausgabepdf-Datei. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeNUp ist wie die Methode MakeNUp, mit dem Unterschied, dass die Methode TryMakeNUp keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)