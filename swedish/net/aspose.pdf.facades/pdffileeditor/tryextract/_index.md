---
title: PdfFileEditor.TryExtract
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metod. Extraherar sidor från indatafiler och sparar som en ny Pdf-fil
type: docs
weight: 410
url: /sv/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

Extraherar sidor från indatafil, sparar som en ny Pdf-fil.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg till indata Pdf-fil. |
| startPage | Int32 | Start sidnummer. |
| endPage | Int32 | Slut sidnummer. |
| outputFile | Sträng | Sökväg till utdata Pdf-fil. |

### Returvärde

Sant för framgång, eller falskt.

## Kommentarer

TryExtract-metoden är som Extract-metoden, förutom att TryExtract-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

Extraherar sidor specificerade av nummerarray, sparar som en ny PDF-fil.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg till indatafil. |
| pageNumber | Int32[] | Index av sidan från indatafilen. |
| outputFile | Sträng | Sökväg till utdatafil. |

### Returvärde

Sant om operationen slutfördes framgångsrikt; annars, falskt.

## Kommentarer

TryExtract-metoden är som Extract-metoden, förutom att TryExtract-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Extraherar sidor specificerade av nummerarray, sparar som en ny Pdf-fil.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indatafil Stream. |
| pageNumber | Int32[] | Index av sidan från indatafilen. |
| outputStream | Stream | Utdatafil stream. |

### Returvärde

Sant för framgång, eller falskt.

## Kommentarer

TryExtract-metoden är som Extract-metoden, förutom att TryExtract-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

Extraherar specificerade sidor från källfil och lagrar resultatet i HttpResponse-objektet.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Stream av källdokumentet. |
| pageNumber | Int32[] | Array av sidnummer som kommer att extraheras. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

Sant om operationen slutfördes framgångsrikt; annars, falskt.

## Kommentarer

TryExtract-metoden är som Extract-metoden, förutom att TryExtract-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

Extraherar specificerade sidor från källfil och lagrar resultatet i HttpResponse-objektet.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg till källfil. |
| pageNumber | Int32[] | Array av sidnummer som kommer att extraheras. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

Sant om operationen slutfördes framgångsrikt; annars, falskt.

## Kommentarer

TryExtract-metoden är som Extract-metoden, förutom att TryExtract-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)