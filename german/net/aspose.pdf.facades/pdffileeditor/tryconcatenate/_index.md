---
title: TryConcatenate
second_title: Aspose.PDF für .NET-API-Referenz
description: Verkettet zwei Dateien.
type: docs
weight: 420
url: /de/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_4}

Verkettet zwei Dateien.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputFile | String | Erste zu verkettende Datei. |
| secInputFile | String | Zweite zu verkettende Datei. |
| outputFile | String | Ausgabedatei. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate-Methode, außer dass die TryConcatenate -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Verkettet Dokumente.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | Document[] | Array von Quelldokumenten. |
| dest | Document | Zieldokument. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate-Methode, außer dass die TryConcatenate-Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [Document](../../../aspose.pdf/document)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_6}

Verkettet Dateien zu einer Datei.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFiles | String[] | Array von Dateien, die verkettet werden sollen. |
| outputFile | String | Name der Ausgabedatei. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate-Methode, außer dass die TryConcatenate-Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Verkettet Dateien

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream[] | Array von Streams, die verkettet werden sollen. |
| outputStream | Stream | Stream, in dem die Ergebnisdatei gespeichert wird. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate-Methode, außer dass die TryConcatenate-Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_5}

Fügt zwei Pdf-Dokumente zu einem neuen Pdf-Dokument mit abwechselnden Seiten zusammen und füllt die leeren Stellen mit leeren Seiten. Beispiel: Dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. Dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden PDF-Dokumente erzeugt das Ergebnisdokument mit den Seiten: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage .

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

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate -Methode, außer dass die TryConcatenate-Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Fügt zwei Pdf-Dokumente zu einem neuen Pdf-Dokument mit abwechselnden Seiten zusammen und füllt die leeren Stellen mit leeren Seiten. Beispiel: Dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. Dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden PDF-Dokumente erzeugt das Ergebnisdokument mit den Seiten: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage .

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputStream | Stream | Der erste PDF-Stream. |
| secInputStream | Stream | Der zweite Pdf-Stream. |
| blankPageStream | Stream | Der Pdf-Stream mit leerer Seite. |
| outputStream | Stream | PDF-Stream ausgeben. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate -Methode, außer dass die TryConcatenate-Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

Verkettet Dateien und speichert Ergebnisse im HttpResposnse-Objekt.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFiles | String[] | Array von Dateien, die verkettet werden sollen. |
| response | HttpResponse | Antwortobjekt. |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate-Methode, außer dass die TryConcatenate -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

Verkettet Dateien und speichert Ergebnisse im HttpResponse-Objekt.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream[] | Streams-Array, das zu verkettende Dateien enthält. |
| response | HttpResponse | Antwortobjekt/ |

### Rückgabewert

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryConcatenate-Methode ist wie die Concatenate-Methode, außer dass die TryConcatenate -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
