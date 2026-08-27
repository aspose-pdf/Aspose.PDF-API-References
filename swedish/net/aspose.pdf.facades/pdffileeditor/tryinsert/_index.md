---
title: "PdfFileEditor.TryInsert"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileEditor‑metod. Infogar sidor från en annan fil i indata‑Pdf‑filen"
type: docs
weight: 420
url: /sv/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

Infogar sidor från en annan fil i inmatnings-Pdf-filen.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Indata‑Pdf‑fil. |
| insertLocation | Int32 | Infogningsposition i indatafilen. |
| portFile | String | Sidor från Pdf‑filen. |
| pageNumber | Int32[] | Sidnumret för den porterade i portFile. |
| outputFile | String | Utdata‑Pdf‑fil. |

### Returvärde

Sant för framgång, annars falskt.

## Anmärkningar

TryInsert‑metoden är som Insert‑metoden, förutom att TryInsert‑metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Infogar sidor från en annan fil i inmatnings-Pdf-filen.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indataström för Pdf‑fil. |
| insertLocation | Int32 | Infogningsposition i indatafilen. |
| portStream | Stream | Ström av Pdf‑fil för sidor. |
| pageNumber | Int32[] | Sidnumret för den porterade i portFile. |
| outputStream | Stream | Utdata‑ström. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Anmärkningar

TryInsert‑metoden är som Insert‑metoden, förutom att TryInsert‑metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Se även

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


