---
title: TryAppend
second_title: Aspose.PDF für .NET-API-Referenz
description: Hängt Seiten an die aus einem Array von Dokumenten in portStreams ausgewählt werden. Das Ergebnisdokument enthält firstInputFile und alle portStreams-Dokumentseiten im Bereich startPage bis endPage.
type: docs
weight: 410
url: /de/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Hängt Seiten an, die aus einem Array von Dokumenten in portStreams ausgewählt werden. Das Ergebnisdokument enthält firstInputFile und alle portStreams-Dokumentseiten im Bereich startPage bis endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

### Bemerkungen

Die TryAppend-Methode ist wie die Append-Methode, außer dass die TryAppend -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_2}

Hängt Seiten an, die aus portFiles-Dokumenten ausgewählt werden. Das Ergebnisdokument enthält firstInputFile- und alle portFiles-Dokumentseiten im Bereich startPage bis endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
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

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryAppend-Methode ist wie die Append-Methode, außer dass die TryAppend -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

Hängt Dokumente an das Quelldokument an und speichert das Ergebnis im Antwortobjekt.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryAppend-Methode ist wie die Append-Methode, außer dass die TryAppend -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

Hängt Dokumente an das Quelldokument an und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
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

true, wenn der Vorgang erfolgreich abgeschlossen wurde; andernfalls falsch.

### Bemerkungen

Die TryAppend-Methode ist wie die Append-Methode, außer dass die TryAppend -Methode keine Ausnahme auslöst, wenn der Vorgang fehlschlägt.

### Siehe auch

* class [PdfFileEditor](../../pdffileeditor)
* namensraum [Aspose.Pdf.Facades](../../pdffileeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
