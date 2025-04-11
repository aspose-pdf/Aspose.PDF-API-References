---
title: PdfFileEditor.Insert
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Fügt Seiten aus einer anderen Datei an einer Position in die Pdf-Datei ein
type: docs
weight: 290
url: /de/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_2}

Fügt Seiten aus einer anderen Datei an einer Position in die Pdf-Datei ein.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Eingabe-Pdf-Datei. |
| insertLocation | Int32 | Position in der Eingabedatei. |
| portFile | String | Die portierte Pdf-Datei. |
| startPage | Int32 | Startposition in portFile. |
| endPage | Int32 | Endposition in portFile. |
| outputFile | String | Ausgabe-Pdf-Datei. |

### Rückgabewert

Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

Fügt Seiten aus einer anderen Datei in die Eingabe-Pdf-Datei ein.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-Stream der Pdf-Datei. |
| insertLocation | Int32 | Einfügeposition in der Eingabedatei. |
| portStream | Stream | Stream der Pdf-Datei für Seiten. |
| startPage | Int32 | Von welcher Seite gestartet werden soll. |
| endPage | Int32 | Bis zu welcher Seite beendet werden soll. |
| outputStream | Stream | Ausgabe-Stream. |

### Rückgabewert

Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_3}

Fügt Seiten aus einer anderen Datei in die Eingabe-Pdf-Datei ein.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Eingabe-Pdf-Datei. |
| insertLocation | Int32 | Einfügeposition in der Eingabedatei. |
| portFile | String | Seiten aus der Pdf-Datei. |
| pageNumber | Int32[] | Die Seitennummer der portierten Datei in portFile. |
| outputFile | String | Ausgabe-Pdf-Datei. |

### Rückgabewert

Wahr für Erfolg oder falsch.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

Fügt Seiten aus einer anderen Datei in die Eingabe-Pdf-Datei ein.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-Stream der Pdf-Datei. |
| insertLocation | Int32 | Einfügeposition in der Eingabedatei. |
| portStream | Stream | Stream der Pdf-Datei für Seiten. |
| pageNumber | Int32[] | Die Seitennummer der portierten Datei in portFile. |
| outputStream | Stream | Ausgabe-Stream. |

### Rückgabewert

Wahr, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)