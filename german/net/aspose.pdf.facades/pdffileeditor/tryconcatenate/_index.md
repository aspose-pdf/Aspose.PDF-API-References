---
title: PdfFileEditor.TryConcatenate
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Verknüpft zwei Dateien
type: docs
weight: 390
url: /de/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_3}

Verknüpft zwei Dateien.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputFile | String | Erste Datei zum Verknüpfen. |
| secInputFile | String | Zweite Datei zum Verknüpfen. |
| outputFile | String | Ausgabedatei. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate-Methode, mit dem Unterschied, dass die TryConcatenate-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Verknüpft Dokumente.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | Document[] | Array von Quelldokumenten. |
| dest | Document | Zieldokument. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate-Methode, mit dem Unterschied, dass die TryConcatenate-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

Verknüpft Dateien zu einer Datei.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFiles | String[] | Array von Dateien zum Verknüpfen. |
| outputFile | String | Name der Ausgabedatei. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate-Methode, mit dem Unterschied, dass die TryConcatenate-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Verknüpft Dateien

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream[] | Array von Streams, die verknüpft werden sollen. |
| outputStream | Stream | Stream, in dem die Ergebnisdatei gespeichert wird. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate-Methode, mit dem Unterschied, dass die TryConcatenate-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

Fügt zwei Pdf-Dokumente in ein neues Pdf-Dokument zusammen, wobei die Seiten abwechselnd angeordnet werden und die leeren Stellen mit leeren Seiten gefüllt werden. z.B.: dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden Pdf-Dokumente ergibt das Ergebnisdokument mit Seiten: p1, p1', p2, p2', p3, p3', p4, leere Seite, p5, leere Seite.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputFile | String | Erste Datei. |
| secInputFile | String | Zweite Datei. |
| blankPageFile | String | PDF-Datei mit leerer Seite. |
| outputFile | String | Ergebnisdatei. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate-Methode, mit dem Unterschied, dass die TryConcatenate-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Fügt zwei Pdf-Dokumente in ein neues Pdf-Dokument zusammen, wobei die Seiten abwechselnd angeordnet werden und die leeren Stellen mit leeren Seiten gefüllt werden. z.B.: dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden Pdf-Dokumente ergibt das Ergebnisdokument mit Seiten: p1, p1', p2, p2', p3, p3', p4, leere Seite, p5, leere Seite.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputStream | Stream | Der erste Pdf-Stream. |
| secInputStream | Stream | Der zweite Pdf-Stream. |
| blankPageStream | Stream | Der Pdf-Stream mit leerer Seite. |
| outputStream | Stream | Ausgabestream für Pdf. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate-Methode, mit dem Unterschied, dass die TryConcatenate-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)


## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

Verknüpft Dateien und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFiles | String[] | Array von Dateien zum Verknüpfen. |
| response | HttpResponse | Antwortobjekt. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate-Methode, mit dem Unterschied, dass die TryConcatenate-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

Verknüpft Dateien und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream[] | Streams-Array, das Dateien zum Verknüpfen enthält. |
| response | HttpResponse | Antwortobjekt. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate-Methode, mit dem Unterschied, dass die TryConcatenate-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)