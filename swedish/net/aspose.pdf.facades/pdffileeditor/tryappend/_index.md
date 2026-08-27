---
title: "PdfFileEditor.TryAppend"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor metod. Lägger till sidor som väljs från en array av dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla sidor från portStreams-dokumenten i intervallet startPage till endPage"
type: docs
weight: 380
url: /sv/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Lägger till sidor, som väljs från en array av dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla portStreams-dokumentens sidor i intervallet startPage till endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Inmatnings‑Pdf‑ström. |
| portStreams | Stream[] | Dokument att kopiera sidor från. |
| startPage | Int32 | Sidan börjar i portStreams-dokument. |
| endPage | Int32 | Sidan slutar i portStreams-dokument. |
| outputStream | Stream | Utdata Pdf-ström. |

### Returvärde

Sant för framgång, annars falskt.

## Anmärkningar

Metoden TryAppend fungerar som Append-metoden, men TryAppend kastar inte ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

Lägger till sidor, som väljs från portFiles-dokument. Resultatdokumentet inkluderar firstInputFile och alla portFiles-dokumentens sidor i intervallet startPage till endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Indata‑Pdf‑fil. |
| portFiles | String[] | Dokument att kopiera sidor från. |
| startPage | Int32 | Sidan börjar i portFiles-dokument. |
| endPage | Int32 | Sidan slutar i portFiles-dokument. |
| outputFile | String | Utdata Pdf-dokument. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Anmärkningar

Metoden TryAppend fungerar som Append-metoden, men TryAppend kastar inte ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


