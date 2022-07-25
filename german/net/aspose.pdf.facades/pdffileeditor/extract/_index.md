---
title: Extract
second_title: Aspose.PDF für .NET-API-Referenz
description: Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei.
type: docs
weight: 310
url: /de/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_3}

Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Geben Sie den Pfad der PDF-Datei ein. |
| startPage | Int32 | Seitenzahl beginnen. |
| endPage | Int32 | Seitenzahl beenden. |
| outputFile | String | Pfad der PDF-Datei ausgeben. |

### Rückgabewert

Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_4}

Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Pfad der Eingabedatei. |
| pageNumber | Int32[] | Index der Seite aus der Eingabedatei. |
| outputFile | String | Pfad der Ausgabedatei. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Extrahiert Seiten aus der Eingabedatei und speichert sie als neue PDF-Datei.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabedatei Stream. |
| startPage | Int32 | Seitenzahl beginnen. |
| endPage | Int32 | Seitenzahl beenden. |
| outputStream | Stream | PDF-Datei-Stream ausgeben. |

### Rückgabewert

Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Extrahiert Seiten, die durch ein Zahlenarray angegeben sind, und speichert sie als neue PDF-Datei.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabedatei Stream. |
| pageNumber | Int32[] | Index der Seite aus der Eingabedatei. |
| outputStream | Stream | Dateistream ausgeben. |

### Rückgabewert

Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Extract(Stream, int[], HttpResponse) {#extract_2}

Extrahiert die angegebenen Seiten aus der Quelldatei und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Stream des Quelldokuments. |
| pageNumber | Int32[] | Array von Seitenzahlen, die extrahiert werden. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Extract(string, int[], HttpResponse) {#extract_5}

Extrahiert angegebene Seiten aus der Quelldatei und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool Extract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Quelldateipfad. |
| pageNumber | Int32[] | Array von Seitenzahlen, die extrahiert werden. |
| response | HttpResponse | HttpResponse-Objekt, in dem das Ergebnis gespeichert wird. |

### Rückgabewert

true, wenn Seiten erfolgreich extrahiert wurden.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
