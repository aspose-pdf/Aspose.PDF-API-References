---
title: PdfFileEditor.TryAppend
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metod. Lägger till sidor som väljs från array av dokument i portStreams. Det resulterande dokumentet inkluderar firstInputFile och alla portStreams dokument sidor i intervallet startPage till endPage
type: docs
weight: 380
url: /sv/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Lägger till sidor, som väljs från array av dokument i portStreams. Det resulterande dokumentet inkluderar firstInputFile och alla portStreams dokument sidor i intervallet startPage till endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatnings Pdf-ström. |
| portStreams | Stream[] | Dokument att kopiera sidor från. |
| startPage | Int32 | Sida börjar i portStreams dokument. |
| endPage | Int32 | Sida slutar i portStreams dokument. |
| outputStream | Stream | Utmatnings Pdf-ström. |

### Returvärde

True för framgång, eller false.

## Anmärkningar

TryAppend-metoden är som Append-metoden, förutom att TryAppend-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

Lägger till sidor, som väljs från portFiles dokument. Det resulterande dokumentet inkluderar firstInputFile och alla portFiles dokument sidor i intervallet startPage till endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatnings Pdf-fil. |
| portFiles | String[] | Dokument att kopiera sidor från. |
| startPage | Int32 | Sida börjar i portFiles dokument. |
| endPage | Int32 | Sida slutar i portFiles dokument. |
| outputFile | String | Utmatnings Pdf-dokument. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars, false.

## Anmärkningar

TryAppend-metoden är som Append-metoden, förutom att TryAppend-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

Lägger till dokument till källdokumentet och sparar resultatet i svarobjektet.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Ström som innehåller källdokumentet. |
| portStreams | Stream[] | Array av strömmar med dokument som ska läggas till. |
| startPage | Int32 | Start sida av tillagda sidor. |
| endPage | Int32 | Slut sida av tillagda sidor. |
| response | HttpResponse | Svarobjekt där dokumentet kommer att sparas. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars, false.

## Anmärkningar

TryAppend-metoden är som Append-metoden, förutom att TryAppend-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

Lägger till dokument till källdokumentet och sparar resultatet i HttpResponse-objektet.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Namn på filen som innehåller källdokumentet. |
| portFiles | String[] | Array av filnamn som innehåller tillagda dokument. |
| startPage | Int32 | Start sida av tillagda sidor. |
| endPage | Int32 | Slut sida av tillagda sidor. |
| response | HttpResponse | Svarobjekt där dokumentet kommer att sparas. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars, false.

## Anmärkningar

TryAppend-metoden är som Append-metoden, förutom att TryAppend-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)