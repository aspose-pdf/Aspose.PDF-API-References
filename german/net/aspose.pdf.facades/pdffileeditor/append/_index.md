---
title: Append
second_title: Aspose.PDF für .NET-API-Referenz
description: Hängt Seiten an die aus einem Array von Dokumenten in portStreams ausgewählt werden. Das Ergebnisdokument enthält firstInputFile und alle portStreams-Dokumentseiten im Bereich startPage bis endPage.
type: docs
weight: 280
url: /de/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Hängt Seiten an, die aus einem Array von Dokumenten in portStreams ausgewählt werden. Das Ergebnisdokument enthält firstInputFile und alle portStreams-Dokumentseiten im Bereich startPage bis endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | PDF-Stream eingeben. |
| portStreams | Stream[] | Dokumente, aus denen Seiten kopiert werden sollen. |
| startPage | Int32 | Die Seite beginnt in portStreams-Dokumenten. |
| endPage | Int32 | Die Seite endet in portStreams-Dokumenten. |
| outputStream | Stream | PDF-Stream ausgeben. |

### Rückgabewert

Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_4}

Hängt Seiten an, die aus portFiles-Dokumenten ausgewählt werden. Das Ergebnisdokument enthält firstInputFile- und alle portFiles-Dokumentseiten im Bereich startPage bis endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | PDF-Datei eingeben. |
| portFiles | String[] | Dokumente, aus denen Seiten kopiert werden sollen. |
| startPage | Int32 | Die Seite beginnt in portFiles-Dokumenten. |
| endPage | Int32 | Die Seite endet in portFiles-Dokumenten. |
| outputFile | String | PDF-Dokument ausgeben. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_3}

Fügt Seiten, die aus portFile im Bereich von startPage bis endPage ausgewählt werden, in portFile an das Ende von firstInputFile an.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | PDF-Datei eingeben. |
| portFile | String | Seiten aus Pdf-Datei. |
| startPage | Int32 | Die Seite beginnt in portFile. |
| endPage | Int32 | Die Seite endet in portFile. |
| outputFile | String | PDF-Dokument ausgeben. |

### Rückgabewert

True, wenn der Vorgang erfolgreich war.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

Fügt Seiten, die aus portStream im Bereich von startPage bis endPage ausgewählt werden, in portStream am Ende von firstInputStream an.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabedatei Stream. |
| portStream | Stream | Seiten aus Pdf-Datei Stream. |
| startPage | Int32 | Die Seite beginnt im portFile Stream. |
| endPage | Int32 | Seite endet in portFile Stream. |
| outputStream | Stream | PDF-Datei-Stream ausgeben. |

### Rückgabewert

Wahr für Erfolg oder falsch.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Append(Stream, Stream[], int, int, HttpResponse) {#append_2}

Hängt Dokumente an das Quelldokument an und speichert das Ergebnis im Antwortobjekt.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Stream, der das Quelldokument enthält. |
| portStreams | Stream[] | Array von Streams mit anzuhängenden Dokumenten. |
| startPage | Int32 | Startseite der angehängten Seite. |
| endPage | Int32 | Endseite der angehängten Seiten. |
| response | HttpResponse | Antwortobjekt, in dem das Dokument gespeichert wird. |

### Rückgabewert

true, wenn der Vorgang erfolgreich war.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, HttpResponse) {#append_5}

Hängt Dokumente an das Quelldokument an und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Name der Datei, die das Quelldokument enthält. |
| portFiles | String[] | Array von Dateinamen, die angehängte Dokumente enthalten. |
| startPage | Int32 | Startseite von angehängten Seiten. |
| endPage | Int32 | Endseite der angehängten Seiten. |
| response | HttpResponse | Antwortobjekt, in dem das Dokument gespeichert wird. |

### Rückgabewert

wahr, wenn der Vorgang erfolgreich war.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
