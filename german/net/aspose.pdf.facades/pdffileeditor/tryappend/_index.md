---
title: PdfFileEditor.TryAppend
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-Methode. Fügt Seiten hinzu, die aus einem Array von Dokumenten in portStreams ausgewählt wurden. Das Ergebnisdokument enthält firstInputFile und alle Seiten der portStreams-Dokumente im Bereich von startPage bis endPage.
type: docs
weight: 380
url: /de/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Fügt Seiten hinzu, die aus einem Array von Dokumenten in portStreams ausgewählt wurden. Das Ergebnisdokument enthält firstInputFile und alle Seiten der portStreams-Dokumente im Bereich von startPage bis endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

## Anmerkungen

Die TryAppend-Methode ist wie die Append-Methode, mit dem Unterschied, dass die TryAppend-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

Fügt Seiten hinzu, die aus portFiles-Dokumenten ausgewählt wurden. Das Ergebnisdokument enthält firstInputFile und alle Seiten der portFiles-Dokumente im Bereich von startPage bis endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
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

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die TryAppend-Methode ist wie die Append-Methode, mit dem Unterschied, dass die TryAppend-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

## Beispiele

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)


## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

Fügt Dokumente zum Quelldokument hinzu und speichert das Ergebnis im Antwortobjekt.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Stream, der das Quelldokument enthält. |
| portStreams | Stream[] | Array von Streams mit Dokumenten, die hinzugefügt werden sollen. |
| startPage | Int32 | Startseite der hinzugefügten Seite. |
| endPage | Int32 | Endseite der hinzugefügten Seiten. |
| response | HttpResponse | Antwortobjekt, in dem das Dokument gespeichert wird. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die TryAppend-Methode ist wie die Append-Methode, mit dem Unterschied, dass die TryAppend-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

Fügt Dokumente zum Quelldokument hinzu und speichert das Ergebnis im HttpResponse-Objekt.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | Name der Datei, die das Quelldokument enthält. |
| portFiles | String[] | Array von Dateinamen, die die hinzugefügten Dokumente enthalten. |
| startPage | Int32 | Startseite der hinzugefügten Seiten. |
| endPage | Int32 | Endseite der hinzugefügten Seiten. |
| response | HttpResponse | Antwortobjekt, in dem das Dokument gespeichert wird. |

### Rückgabewert

true, wenn die Operation erfolgreich abgeschlossen wurde; andernfalls false.

## Anmerkungen

Die TryAppend-Methode ist wie die Append-Methode, mit dem Unterschied, dass die TryAppend-Methode keine Ausnahme auslöst, wenn die Operation fehlschlägt.

### Siehe auch

* Klasse [PdfFileEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)