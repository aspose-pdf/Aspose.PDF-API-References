---
title: PdfFileEditor.Append
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Fügt Seiten hinzu, die aus einem Array von Dokumenten in portStreams ausgewählt wurden. Das Ergebnisdokument umfasst firstInputFile und alle Seiten der portStreams-Dokumente im Bereich von startPage bis endPage.
type: docs
weight: 250
url: /de/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Fügt Seiten hinzu, die aus einem Array von Dokumenten in portStreams ausgewählt wurden. Das Ergebnisdokument umfasst firstInputFile und alle Seiten der portStreams-Dokumente im Bereich von startPage bis endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabe-Pdf-Stream. |
| portStreams | Stream[] | Dokumente, aus denen Seiten kopiert werden. |
| startPage | Int32 | Seite beginnt in portStreams-Dokumenten. |
| endPage | Int32 | Seite endet in portStreams-Dokumenten. |
| outputStream | Stream | Ausgabe-Pdf-Stream. |

### Rückgabewert

True bei Erfolg, oder false.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

Fügt Seiten hinzu, die aus portFiles-Dokumenten ausgewählt wurden. Das Ergebnisdokument umfasst firstInputFile und alle Seiten der portFiles-Dokumente im Bereich von startPage bis endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Eingabe-Pdf-Datei. |
| portFiles | String[] | Dokumente, aus denen Seiten kopiert werden. |
| startPage | Int32 | Seite beginnt in portFiles-Dokumenten. |
| endPage | Int32 | Seite endet in portFiles-Dokumenten. |
| outputFile | String | Ausgabe-Pdf-Dokument. |

### Rückgabewert

True, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

Fügt Seiten hinzu, die aus portFile im Bereich von startPage bis endPage ausgewählt wurden, in portFile am Ende von firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Eingabe-Pdf-Datei. |
| portFile | String | Seiten aus der Pdf-Datei. |
| startPage | Int32 | Seite beginnt in portFile. |
| endPage | Int32 | Seite endet in portFile. |
| outputFile | String | Ausgabe-Pdf-Dokument. |

### Rückgabewert

True, wenn die Operation erfolgreich war.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

Fügt Seiten hinzu, die aus portStream im Bereich von startPage bis endPage ausgewählt wurden, in portStream am Ende von firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabedatei-Stream. |
| portStream | Stream | Seiten aus dem Pdf-Datei-Stream. |
| startPage | Int32 | Seite beginnt im portFile-Stream. |
| endPage | Int32 | Seite endet im portFile-Stream. |
| outputStream | Stream | Ausgabe-Pdf-Datei-Stream. |

### Rückgabewert

True bei Erfolg, oder false.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)