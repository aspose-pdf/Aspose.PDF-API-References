---
title: PdfFileEditor.TrySplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metod. Dela Pdf-fil från första sidan till angiven plats och spara den främre delen som en ny fil
type: docs
weight: 460
url: /sv/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Dela Pdf-fil från första sidan till angiven plats och spara den främre delen som en ny fil.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Käll Pdf-fil. |
| location | Int32 | Delningspunkt. |
| outputFile | Sträng | Utdata Pdf-fil. |

### Returvärde

Sant för framgång, eller falskt.

## Kommentarer

TrySplitFromFirst-metoden är som SplitFromFirst-metoden, förutom att TrySplitFromFirst-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Dela från början till angiven plats och spara den främre delen i utdata Stream.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Käll Pdf-fil Stream. |
| location | Int32 | Delningspunkt. |
| outputStream | Stream | Utdata fil Stream. |

### Returvärde

Sant för framgång, eller falskt.

## Kommentarer

Strömmarna stängs INTE efter denna operation. TrySplitFromFirst-metoden är som SplitFromFirst-metoden, förutom att TrySplitFromFirst-metoden inte kastar ett undantag om operationen misslyckas.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

Dela dokumentet från första sidan till plats och spara resultatet i HttpResponse-objekt.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Källfilens namn. |
| location | Int32 | Delningspunkt. |
| response | HttpResponse | HttpResponse-objekt. |

### Returvärde

Sant om operationen slutfördes framgångsrikt; annars, falskt.

## Kommentarer

TrySplitFromFirst-metoden är som SplitFromFirst-metoden, förutom att TrySplitFromFirst-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

Dela dokumentet från början till angiven plats och lagra resultatet i HttpResponse-objekt.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Stream av källdokumentet. |
| location | Int32 | Delningspunkt. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

Sant om operationen slutfördes framgångsrikt; annars, falskt.

## Kommentarer

TrySplitFromFirst-metoden är som SplitFromFirst-metoden, förutom att TrySplitFromFirst-metoden inte kastar ett undantag om operationen misslyckas.

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)