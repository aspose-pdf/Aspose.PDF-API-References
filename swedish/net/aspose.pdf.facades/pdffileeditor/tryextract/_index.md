---
title: TryExtract
second_title: Aspose.PDF för .NET API Referens
description: Extraherar sidor från indatafilen sparar som en ny pdf-fil.
type: docs
weight: 440
url: /sv/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_2}

Extraherar sidor från indatafilen, sparar som en ny pdf-fil.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatning av pdf-filsökväg. |
| startPage | Int32 | Startsidans nummer. |
| endPage | Int32 | Slutsidans nummer. |
| outputFile | String | Utdata pdf-fil sökväg. |

### Returvärde

Sant för framgång, eller falskt.

### Anmärkningar

TryExtract-metoden är som Extract-metoden, förutom att TryExtract -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_3}

Extraherar sidor specificerade av nummermatris, sparar som en ny PDF-fil.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Indatafilsökväg. |
| pageNumber | Int32[] | Index av sidan från indatafilen. |
| outputFile | String | Utdatafilens sökväg. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryExtract-metoden är som Extract-metoden, förutom att TryExtract -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Extraherar sidor specificerade av nummermatris, sparar som en ny pdf-fil.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indatafil Stream. |
| pageNumber | Int32[] | Index av sidan från indatafilen. |
| outputStream | Stream | Utdatafilström. |

### Returvärde

Sant för framgång, eller falskt.

### Anmärkningar

TryExtract-metoden är som Extract-metoden, förutom att TryExtract -metoden inte ger ett undantag om operationen misslyckas.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

Extraherar specificerade sidor från källfilen och lagrar resultatet i HttpResponse-objekt.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Ström av källdokument. |
| pageNumber | Int32[] | Array av sidnummer som kommer att extraheras. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryExtract-metoden är som Extract-metoden, förutom att TryExtract -metoden inte ger ett undantag om operationen misslyckas.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

Extraherar specificerade sidor från källfilen och lagrar resultatet i HttpResponse-objekt.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Källfilens sökväg. |
| pageNumber | Int32[] | Array av sidnummer som kommer att extraheras. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

sant om operationen slutfördes framgångsrikt; annars falskt.

### Anmärkningar

TryExtract-metoden är som Extract-metoden, förutom att TryExtract -metoden inte ger ett undantag om operationen misslyckas.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
