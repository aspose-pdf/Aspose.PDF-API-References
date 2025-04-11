---
title: PdfFileEditor.TryDelete
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-metod. Tar bort sidor som anges av nummerarray från indatafilen och sparar som en ny Pdf-fil
type: docs
weight: 400
url: /sv/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

Tar bort sidor som anges av nummerarray från indatafilen, sparar som en ny Pdf-fil.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg till indatafil. |
| pageNumber | Int32[] | Index för sidan i indatafilen. |
| outputFile | Sträng | Sökväg till utdatafil. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryDelete-metoden är som Delete-metoden, förutom att TryDelete-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

Tar bort sidor som anges av nummerarray från indatafilen, sparar som en ny Pdf-fil.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indatafil Stream. |
| pageNumber | Int32[] | Index för sidan i indatafilen. |
| outputStream | Stream | Utdatafil stream. |

### Returvärde

True för framgång, eller false.

## Kommentarer

TryDelete-metoden är som Delete-metoden, förutom att TryDelete-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryDelete(string, int[], HttpResponse) {#trydelete_3}

Tar bort angivna sidor från dokumentet och lagrar resultatet i HttpResponse-objektet.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg till källfil. |
| pageNumber | Int32[] | Array av sidnummer som måste tas bort. |
| response | HttpResponse | Svarsobjekt där resultatdokumentet kommer att lagras. |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryDelete-metoden är som Delete-metoden, förutom att TryDelete-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], HttpResponse) {#trydelete_1}

Tar bort angivna sidor från dokumentet och sparar resultatet i HttpResponse-objektet.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Källdokument stream. |
| pageNumber | Int32[] | Array av sidnummer som kommer att tas bort. |
| response | HttpResponse | HttpResponse-objekt |

### Returvärde

true om operationen slutfördes framgångsrikt; annars false.

## Kommentarer

TryDelete-metoden är som Delete-metoden, förutom att TryDelete-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)