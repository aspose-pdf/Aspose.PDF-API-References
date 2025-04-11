---
title: PdfFileEditor.Extract
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Extrahiert Seiten aus Eingabedateien und speichert sie als neue Pdf-Datei
type: docs
weight: 280
url: /de/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_2}

Extrahiert Seiten aus der Eingabedatei und speichert sie als neue Pdf-Datei.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad zur Eingabe-Pdf-Datei. |
| startPage | Int32 | Startseitenzahl. |
| endPage | Int32 | Endseitenzahl. |
| outputFile | String | Pfad zur Ausgabepdf-Datei. |

### Rückgabewert

True bei Erfolg, oder false.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_3}

Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad zur Eingabedatei. |
| pageNumber | Int32[] | Index der Seite aus der Eingabedatei. |
| outputFile | String | Pfad zur Ausgabedatei. |

### Rückgabewert

True, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Extrahiert Seiten aus der Eingabedatei und speichert sie als neue Pdf-Datei.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabedatei-Stream. |
| startPage | Int32 | Startseitenzahl. |
| endPage | Int32 | Endseitenzahl. |
| outputStream | Stream | Ausgabepdf-Datei-Stream. |

### Rückgabewert

True bei Erfolg, oder false.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue Pdf-Datei.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabedatei-Stream. |
| pageNumber | Int32[] | Index der Seite aus der Eingabedatei. |
| outputStream | Stream | Ausgabedatei-Stream. |

### Rückgabewert

True bei Erfolg, oder false.

## Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)