---
title: PdfFileEditor.TryMakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Erstellt ein Booklet aus der Eingabedatei in die Ausgabedatei
type: docs
weight: 430
url: /de/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
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

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeBooklet ist wie die Methode MakeBooklet, mit dem Unterschied, dass die Methode TryMakeBooklet keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

Erstellt ein Booklet aus der PDF-Datei und speichert es in HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabedokumentstream. |
| pageSize | PageSize | Gewünschte Seitengröße. |
| leftPages | Int32[] | Array von Seitennummern, die links platziert werden. |
| rightPages | Int32[] | Array von Seitennummern, die rechts platziert werden. |
| response | HttpResponse | HttpResponse-Objekt. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeBooklet ist wie die Methode MakeBooklet, mit dem Unterschied, dass die Methode TryMakeBooklet keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse-Objekten.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad zur Quelldatei. |
| pageSize | PageSize | Gewünschte Seitengröße in der Ausgabedatei. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

True, wenn die Operation erfolgreich war.

## Anmerkungen

Die Methode TryMakeBooklet ist wie die Methode MakeBooklet, mit dem Unterschied, dass die Methode TryMakeBooklet keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Erstellt ein Booklet aus der Quelldatei und speichert das Ergebnis in HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabedokumentstream. |
| pageSize | PageSize | Gewünschte Seitengröße in der Ausgabedatei. |
| response | HttpResponse | Respose-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn das Booklet erfolgreich erstellt wurde.

## Anmerkungen

Die Methode TryMakeBooklet ist wie die Methode MakeBooklet, mit dem Unterschied, dass die Methode TryMakeBooklet keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Erstellt ein Booklet aus der Eingabedatei in die Ausgabedatei.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad und Name der Eingabe-PDF-Datei. |
| outputFile | String | Pfad und Name der Ausgabepdf-Datei. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeBooklet ist wie die Methode MakeBooklet, mit dem Unterschied, dass die Methode TryMakeBooklet keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

Erstellt ein Booklet vom InputStream zum OutputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-PDF-Stream. |
| outputStream | Stream | Ausgabe-PDF-Stream. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeBooklet ist wie die Methode MakeBooklet, mit dem Unterschied, dass die Methode TryMakeBooklet keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

Erstellt ein Booklet aus der inputFile in die outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad und Name der Eingabe-PDF-Datei. |
| outputFile | String | Pfad und Name der Ausgabepdf-Datei. |
| pageSize | PageSize | Die Seitengröße der Ausgabepdf-Datei. |

### Rückgabewert

True, wenn die Operation erfolgreich war.

## Anmerkungen

Die Methode TryMakeBooklet ist wie die Methode MakeBooklet, mit dem Unterschied, dass die Methode TryMakeBooklet keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

Erstellt ein Booklet aus dem Eingabestream und speichert das Ergebnis im Ausgabestream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-PDF-Stream. |
| outputStream | Stream | Ausgabe-PDF-Stream. |
| pageSize | PageSize | Die Seitengröße der Ausgabepdf-Datei. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeBooklet ist wie die Methode MakeBooklet, mit dem Unterschied, dass die Methode TryMakeBooklet keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

Erstellt ein angepasstes Booklet aus der firstInputFile in die outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Die Eingabedatei. |
| outputFile | String | Pfad und Name der Ausgabepdf-Datei. |
| leftPages | Int32[] | Die linken Seiten des Booklets. |
| rightPages | Int32[] | Die rechten Seiten des Booklets. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeBooklet ist wie die Methode MakeBooklet, mit dem Unterschied, dass die Methode TryMakeBooklet keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

Erstellt ein angepasstes Booklet aus dem firstInputStream in den outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Der Eingabestream. |
| outputStream | Stream | Ausgabe-PDF-Stream. |
| leftPages | Int32[] | Die linken Seiten. |
| rightPages | Int32[] | Die rechten Seiten. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeBooklet ist wie die Methode MakeBooklet, mit dem Unterschied, dass die Methode TryMakeBooklet keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

Erstellt ein angepasstes Booklet aus der firstInputFile in die outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
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

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeBooklet ist wie die Methode MakeBooklet, mit dem Unterschied, dass die Methode TryMakeBooklet keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

Erstellt ein Booklet vom firstInputStream zum outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Der Eingabestream. |
| outputStream | Stream | Ausgabe-PDF-Stream. |
| pageSize | PageSize | Die Seitengröße der Ausgabepdf-Datei. |
| leftPages | Int32[] | Die linken Seiten. |
| rightPages | Int32[] | Die rechten Seiten. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die Methode TryMakeBooklet ist wie die Methode MakeBooklet, mit dem Unterschied, dass die Methode TryMakeBooklet keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Siehe auch

* Klasse [PageSize](../../../aspose.pdf/pagesize/)
* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)