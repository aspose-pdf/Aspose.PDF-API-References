---
title: Insert
second_title: Aspose.PDF för .NET API Referens
description: Infogar sidor från en annan fil i Pdf-filen på en plats.
type: docs
weight: 320
url: /sv/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_3}

Infogar sidor från en annan fil i Pdf-filen på en plats.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Mata in pdf-fil. |
| insertLocation | Int32 | Position i inmatningsfil. |
| portFile | String | Den porterande pdf-filen. |
| startPage | Int32 | Startposition i portFile. |
| endPage | Int32 | Slutposition i portFile. |
| outputFile | String | Utdata pdf-fil. |

### Returvärde

Sant för framgång, eller falskt.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

Infogar sidor från en annan fil i indata-Pdf-filen.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indataström av pdf-fil. |
| insertLocation | Int32 | Infoga position i inmatningsfilen. |
| portStream | Stream | Ström av pdf-fil för sidor. |
| startPage | Int32 | Från vilken sida man ska börja. |
| endPage | Int32 | Till vilken sida som ska sluta. |
| outputStream | Stream | Utgångsström. |

### Returvärde

Sant för framgång, eller falskt.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_4}

Infogar sidor från en annan fil i indata-Pdf-filen.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Mata in pdf-fil. |
| insertLocation | Int32 | Infoga position i inmatningsfilen. |
| portFile | String | Sidor från pdf-filen. |
| pageNumber | Int32[] | Sidnumret för den portade i portFile. |
| outputFile | String | Utdata pdf-fil. |

### Returvärde

Sant för framgång, eller falskt.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

Infogar sidor från en annan fil i indata-Pdf-filen.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indataström av pdf-fil. |
| insertLocation | Int32 | Infoga position i inmatningsfilen. |
| portStream | Stream | Ström av pdf-fil för sidor. |
| pageNumber | Int32[] | Sidnumret för den portade i portFile. |
| outputStream | Stream | Utgångsström. |

### Returvärde

Sant om operationen lyckades.

### Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], HttpResponse) {#insert_5}

Infogar innehållet i filen i källfilen och lagrar resultatet i HttpResponse-objektet.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | String | Källfilens namn. |
| insertLocation | Int32 | Sidnummer där den andra filen kommer att infogas. |
| portFile | String | Sökväg till fil som kommer att infogas. |
| pageNumber | Int32[] | Matris med sidnummer i källfilen som kommer att infogas. |
| response | HttpResponse | Svarsobjekt där resultatet kommer att lagras. |

### Returvärde

sant att infoga lyckades.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], HttpResponse) {#insert_2}

Infogar dokument i annat dokument och lagrar resultatet i svarsobjekt.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Streama med källdokument |
| insertLocation | Int32 | Plats där annat dokument kommer att infogas. |
| portStream | Stream | Dokument som ska infogas. |
| pageNumber | Int32[] | Matris med sidnummer i det andra dokumentet som kommer att infogas. |
| response | HttpResponse | Svarsobjekt där resultatet kommer att lagras. |

### Returvärde

Sant om operationen lyckades.

### Se även

* class [PdfFileEditor](../../pdffileeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdffileeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
