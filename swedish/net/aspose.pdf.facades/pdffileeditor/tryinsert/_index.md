---
title: PdfFileEditor.TryInsert
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metod. Infogar sidor från en annan fil i indata Pdf-fil
type: docs
weight: 420
url: /sv/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

Infogar sidor från en annan fil i indata Pdf-fil.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Indata Pdf-fil. |
| insertLocation | Int32 | Infogningsposition i indatafilen. |
| portFile | Sträng | Sidor från Pdf-filen. |
| pageNumber | Int32[] | Sidnumret för den importerade i portFile. |
| outputFile | Sträng | Utdata Pdf-fil. |

### Returvärde

Sant för framgång, eller falskt.

## Kommentarer

TryInsert-metoden är som Insert-metoden, förutom att TryInsert-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Infogar sidor från en annan fil i indata Pdf-fil.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indata Stream av Pdf-fil. |
| insertLocation | Int32 | Infogningsposition i indatafilen. |
| portStream | Stream | Stream av Pdf-fil för sidor. |
| pageNumber | Int32[] | Sidnumret för den importerade i portFile. |
| outputStream | Stream | Utdata Stream. |

### Returvärde

Sant om operationen slutfördes framgångsrikt; annars, falskt.

## Kommentarer

TryInsert-metoden är som Insert-metoden, förutom att TryInsert-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

Infogar innehållet i filen i källfilen och lagrar resultatet i HttpResponse-objektet.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Källfilens namn. |
| insertLocation | Int32 | Sidnummer där den andra filen kommer att infogas. |
| portFile | Sträng | Sökväg till filen som kommer att infogas. |
| pageNumber | Int32[] | Array av sidnummer i källfilen som kommer att infogas. |
| response | HttpResponse | Svarsobjekt där resultatet kommer att lagras. |

### Returvärde

Sant om operationen slutfördes framgångsrikt; annars, falskt.

## Kommentarer

TryInsert-metoden är som Insert-metoden, förutom att TryInsert-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

Infogar dokumentet i ett annat dokument och lagrar resultatet i svarsobjektet.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Stream med källdokument |
| insertLocation | Int32 | Plats där det andra dokumentet kommer att infogas. |
| portStream | Stream | Dokumentet som ska infogas. |
| pageNumber | Int32[] | Array av sidnummer i det andra dokumentet som kommer att infogas. |
| response | HttpResponse | Svarsobjekt där resultatet kommer att lagras. |

### Returvärde

Sant om operationen slutfördes framgångsrikt; annars, falskt.

## Kommentarer

TryInsert-metoden är som Insert-metoden, förutom att TryInsert-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)