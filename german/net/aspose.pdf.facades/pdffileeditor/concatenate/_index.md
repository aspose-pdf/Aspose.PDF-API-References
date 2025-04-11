---
title: PdfFileEditor.Concatenate
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Verknüpft zwei Dateien
type: docs
weight: 260
url: /de/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_4}

Verknüpft zwei Dateien.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputFile | String | Erste Datei, die verknüpft werden soll. |
| secInputFile | String | Zweite Datei, die verknüpft werden soll. |
| outputFile | String | Ausgabedatei. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

Verknüpft zwei Dateien.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputStream | Stream | Stream der ersten Datei. |
| secInputStream | Stream | Stream der zweiten Datei. |
| outputStream | Stream | Stream, in dem die Ergebnisdatei gespeichert wird. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich war.

Wahr, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

Verknüpft Dokumente.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | Document[] | Array von Quelldokumenten. |
| dest | Document | Zieldokument. |

### Rückgabewert

Wahr, wenn die Verknüpfung erfolgreich ist.

### Siehe auch

* Klasse [Document](../../../aspose.pdf/document/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_6}

Verknüpft Dateien zu einer Datei.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFiles | String[] | Array von Dateien, die verknüpft werden sollen. |
| outputFile | String | Name der Ausgabedatei. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

Verknüpft Dateien

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream[] | Array von Streams, die verknüpft werden sollen. |
| outputStream | Stream | Stream, in dem die Ergebnisdatei gespeichert wird. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_5}

Vereint zwei Pdf-Dokumente in ein neues Pdf-Dokument mit Seiten in abwechselnder Reihenfolge und füllt die leeren Stellen mit leeren Seiten. z.B.: Dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. Dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden Pdf-Dokumente ergibt das Ergebnisdokument mit Seiten: p1, p1', p2, p2', p3, p3', p4, leere Seite, p5, leere Seite.

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

Wahr, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

Vereint zwei Pdf-Dokumente in ein neues Pdf-Dokument mit Seiten in abwechselnder Reihenfolge und füllt die leeren Stellen mit leeren Seiten. z.B.: Dokument1 hat 5 Seiten: p1, p2, p3, p4, p5. Dokument2 hat 3 Seiten: p1', p2', p3'. Das Zusammenführen der beiden Pdf-Dokumente ergibt das Ergebnisdokument mit Seiten: p1, p1', p2, p2', p3, p3', p4, leere Seite, p5, leere Seite.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstInputStream | Stream | Der erste Pdf-Stream. |
| secInputStream | Stream | Der zweite Pdf-Stream. |
| blankPageStream | Stream | Der Pdf-Stream mit leerer Seite. |
| outputStream | Stream | Ausgabestream für Pdf. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)


## Concatenate(string[], HttpResponse) {#concatenate_8}

Verknüpft Dateien und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFiles | String[] | Array von Dateien, die verknüpft werden sollen. |
| response | HttpResponse | Antwortobjekt. |

### Rückgabewert

wahr, wenn die Verknüpfung erfolgreich war.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], HttpResponse) {#concatenate_4}

Verknüpft Dateien und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream[] | Array von Streams, die Dateien enthalten, die verknüpft werden sollen. |
| response | HttpResponse | Antwortobjekt. |

### Rückgabewert

wahr, wenn die Operation erfolgreich war.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)