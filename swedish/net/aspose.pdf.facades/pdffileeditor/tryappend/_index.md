---
title: TryAppend
second_title: Aspose.PDF för .NET API Referens
description: Lägger till sidor som väljs från en mängd dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla portStreams dokumentsidor i intervallet startPage to endPage.
type: docs
weight: 410
url: /sv/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Lägger till sidor, som väljs från en mängd dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla portStreams dokumentsidor i intervallet startPage to endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Mata in pdf-ström. |
| portStreams | Stream[] | Dokument att kopiera sidor från. |
| startPage | Int32 | Sidan startar i portStreams-dokument. |
| endPage | Int32 | Sidan slutar i portStreams-dokument. |
| outputStream | Stream | Utdata pdf-ström. |

### Returvärde

Sant för framgång, eller falskt.

### Anmärkningar

TryAppend-metoden är som Append-metoden, förutom att TryAppend -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_2}

Lägger till sidor som är valda från portFiles-dokument. Resultatdokumentet inkluderar firstInputFile och alla portFiles-dokumentsidor i intervallet startPage to endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Mata in pdf-fil. |
| portFiles | String[] | Dokument att kopiera sidor från. |
| startPage | Int32 | Sidan startar i portFiles-dokument. |
| endPage | Int32 | Sidan slutar i portFiles-dokument. |
| outputFile | String | Utdata pdf-dokument. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryAppend-metoden är som Append-metoden, förutom att TryAppend -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

Lägger till dokument till källdokument och sparar resultatet i svarsobjekt.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Stream som innehåller källdokument. |
| portStreams | Stream[] | Uppsättning strömmar med dokument som ska läggas till. |
| startPage | Int32 | Startsida för bifogad sida. |
| endPage | Int32 | Slutsida av bifogade sidor. |
| response | HttpResponse | Svarsobjekt där dokumentet kommer att sparas. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryAppend-metoden är som Append-metoden, förutom att TryAppend -metoden inte ger ett undantag om operationen misslyckas.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

Lägger till dokument till källdokument och sparar resultatet i HttpResponse-objekt.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Namnet på filen som innehåller källdokumentet. |
| portFiles | String[] | Matris med filnamn som innehåller bifogade dokument. |
| startPage | Int32 | Startsida för bifogade sidor. |
| endPage | Int32 | Slutsida av bifogade sidor. |
| response | HttpResponse | Svarsobjekt där dokumentet kommer att sparas. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryAppend-metoden är som Append-metoden, förutom att TryAppend -metoden inte ger ett undantag om operationen misslyckas.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
