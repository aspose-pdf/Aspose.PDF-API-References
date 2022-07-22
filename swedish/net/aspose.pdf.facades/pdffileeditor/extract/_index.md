---
title: Extract
second_title: Aspose.PDF för .NET API Referens
description: Extraherar sidor från indatafilen sparar som en ny pdf-fil.
type: docs
weight: 310
url: /sv/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_3}

Extraherar sidor från indatafilen, sparar som en ny pdf-fil.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Inmatning av pdf-filsökväg. |
| startPage | Int32 | Startsidans nummer. |
| endPage | Int32 | Slutsidans nummer. |
| outputFile | String | Utdata pdf-fil sökväg. |

### Returvärde

Sant för framgång, eller falskt.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_4}

Extraherar sidor specificerade av nummermatris, sparar som en ny PDF-fil.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Indatafilsökväg. |
| pageNumber | Int32[] | Index av sidan från indatafilen. |
| outputFile | String | Utdatafilens sökväg. |

### Returvärde

Sant om operationen lyckades.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Extraherar sidor från indatafilen, sparar som en ny pdf-fil.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indatafil Stream. |
| startPage | Int32 | Startsidans nummer. |
| endPage | Int32 | Slutsidans nummer. |
| outputStream | Stream | Utdata pdf-fil Stream. |

### Returvärde

Sant för framgång, eller falskt.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Extraherar sidor specificerade av nummermatris, sparar som en ny pdf-fil.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indatafil Stream. |
| pageNumber | Int32[] | Index av sidan från indatafilen. |
| outputStream | Stream | Utdatafilström. |

### Returvärde

Sant för framgång, eller falskt.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## Extract(Stream, int[], HttpResponse) {#extract_2}

Extraherar specificerade sidor från källfilen och lagrar resultatet i HttpResponse-objekt.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Ström av källdokument. |
| pageNumber | Int32[] | Array av sidnummer som kommer att extraheras. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

Sant om operationen lyckades.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## Extract(string, int[], HttpResponse) {#extract_5}

Extraherar specificerade sidor från källfilen och lagrar resultatet i HttpResponse-objekt.

```csharp
public bool Extract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Källfilens sökväg. |
| pageNumber | Int32[] | Array av sidnummer som kommer att extraheras. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

sant om sidor extraherades framgångsrikt.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
