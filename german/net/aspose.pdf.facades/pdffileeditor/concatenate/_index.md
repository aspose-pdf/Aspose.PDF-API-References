---
title: Concatenate
second_title: Aspose.PDF für .NET-API-Referenz
description: Verkettet zwei Dateien.
type: docs
weight: 290
url: /de/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_5}

Verkettet zwei Dateien.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputFile | String | Erste zu verkettende Datei. |
| secInputFile | String | Zweite zu verkettende Datei. |
| outputFile | String | Ausgabedatei. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

Verkettet zwei Dateien.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputStream | Stream | Stream der ersten Datei. |
| secInputStream | Stream | Stream der zweiten Datei. |
| outputStream | Stream | Stream, in dem die Ergebnisdatei gespeichert wird. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

True, wenn der Vorgang erfolgreich war.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

Verkettet Dokumente.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | Document[] | Array von Quelldokumenten. |
| dest | Document | Zieldokument. |

### Rückgabewert

True, wenn die Verkettung erfolgreich ist.

### Siehe auch

* class [Document](../../../aspose.pdf/document)
* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_7}

Verkettet Dateien zu einer Datei.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFiles | String[] | Array von Dateien, die verkettet werden sollen. |
| outputFile | String | Name der Ausgabedatei. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

Verkettet Dateien

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream[] | Array von Streams, die verkettet werden sollen. |
| outputStream | Stream | Stream, in dem die Ergebnisdatei gespeichert wird. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_6}

Fügt zwei Pdf-Dokumente zu einem neuen Pdf-Dokument mit abwechselnden Seiten zusammen und füllt die leeren Stellen mit leeren Seiten. Beispiel: Dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. Dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden PDF-Dokumente erzeugt das Ergebnisdokument mit den Seiten: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage .

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputFile | String | Erste Datei. |
| secInputFile | String | Zweite Datei. |
| blankPageFile | String | PDF-Datei mit leerer Seite. |
| outputFile | String | Ergebnisdatei. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

Fügt zwei Pdf-Dokumente zu einem neuen Pdf-Dokument mit abwechselnden Seiten zusammen und füllt die leeren Stellen mit leeren Seiten. Beispiel: Dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. Dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden PDF-Dokumente erzeugt das Ergebnisdokument mit den Seiten: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage .

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputStream | Stream | Der erste PDF-Stream. |
| secInputStream | Stream | Der zweite Pdf-Stream. |
| blankPageStream | Stream | Der Pdf-Stream mit leerer Seite. |
| outputStream | Stream | PDF-Stream ausgeben. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Concatenate(string[], HttpResponse) {#concatenate_8}

Verkettet Dateien und speichert Ergebnisse im HttpResposnse-Objekt.

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFiles | String[] | Array von Dateien, die verkettet werden sollen. |
| response | HttpResponse | Antwortobjekt. |

### Rückgabewert

true, wenn die Verkettung erfolgreich war.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Concatenate(Stream[], HttpResponse) {#concatenate_4}

Verkettet Dateien und speichert Ergebnisse im HttpResponse-Objekt.

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream[] | Streams-Array, das zu verkettende Dateien enthält. |
| response | HttpResponse | Antwortobjekt/ |

### Rückgabewert

wahr, wenn der Vorgang erfolgreich war.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
