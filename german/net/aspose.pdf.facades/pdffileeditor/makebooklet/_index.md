---
title: PdfFileEditor.MakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Erstellt ein Booklet aus der Eingabedatei in die Ausgabedatei
type: docs
weight: 300
url: /de/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_4}

Erstellt ein Booklet aus der Eingabedatei in die Ausgabedatei.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad und Name der Eingabe-PDF-Datei. |
| outputFile | String | Pfad und Name der Ausgabepdf-Datei. |

### Rückgabewert

boolean - Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet}

Erstellt ein Booklet aus dem InputStream in den outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-PDF-Stream. |
| outputStream | Stream | Ausgabepdf-Stream. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_5}

Erstellt ein Booklet aus der inputFile in die outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad und Name der Eingabe-PDF-Datei. |
| outputFile | String | Pfad und Name der Ausgabepdf-Datei. |
| pageSize | PageSize | Die Seitengröße der Ausgabepdf-Datei. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_1}

Erstellt ein Booklet aus dem Eingabestream und speichert das Ergebnis im Ausgabestream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-PDF-Stream. |
| outputStream | Stream | Ausgabepdf-Stream. |
| pageSize | PageSize | Die Seitengröße der Ausgabepdf-Datei. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_7}

Erstellt ein angepasstes Booklet aus der firstInputFile in die outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Die Eingabedatei. |
| outputFile | String | Pfad und Name der Ausgabepdf-Datei. |
| leftPages | Int32[] | Die linken Seiten des Booklets. |
| rightPages | Int32[] | Die rechten Seiten des Booklets. |

### Rückgabewert

boolean - Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_3}

Erstellt ein angepasstes Booklet aus dem firstInputStream in den outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Der Eingabestream. |
| outputStream | Stream | Ausgabepdf-Stream. |
| leftPages | Int32[] | Die linken Seiten. |
| rightPages | Int32[] | Die rechten Seiten. |

### Rückgabewert

boolean - Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_6}

Erstellt ein angepasstes Booklet aus der firstInputFile in die outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Die Eingabedatei. |
| outputFile | String | Pfad und Name der Ausgabepdf-Datei. |
| pageSize | PageSize | Die Seitengröße der Ausgabepdf-Datei. |
| leftPages | Int32[] | Die linken Seiten. |
| rightPages | Int32[] | Die rechten Seiten. |

### Rückgabewert

boolean - Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_2}

Erstellt ein Booklet aus dem firstInputStream in den outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Der Eingabestream. |
| outputStream | Stream | Ausgabepdf-Stream. |
| pageSize | PageSize | Die Seitengröße der Ausgabepdf-Datei. |
| leftPages | Int32[] | Die linken Seiten. |
| rightPages | Int32[] | Die rechten Seiten. |

### Rückgabewert

boolean - Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)


## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad zur Quelldatei. |
| pageSize | PageSize | Gewünschte Seitengröße. |
| leftPages | Int32[] | Array von Seitennummern, die links platziert werden sollen. |
| rightPages | Int32[] | Array von Seitennummern, die rechts platziert werden sollen. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich war.

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

Erstellt ein Booklet aus der PDF-Datei und speichert es in HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabedokumentenstream. |
| pageSize | PageSize | Gewünschte Seitengröße. |
| leftPages | Int32[] | Array von Seitennummern, die links platziert werden. |
| rightPages | Int32[] | Array von Seitennummern, die rechts platziert werden. |
| response | HttpResponse | HttpResponse-Objekt. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich war.

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad zur Quelldatei. |
| pageSize | PageSize | Gewünschte Seitengröße in der Ausgabedatei. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich war.

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabedokumentenstream. |
| pageSize | PageSize | Gewünschte Seitengröße in der Ausgabedatei. |
| response | HttpResponse | Respose-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

wahr, wenn das Booklet erfolgreich erstellt wurde.

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)