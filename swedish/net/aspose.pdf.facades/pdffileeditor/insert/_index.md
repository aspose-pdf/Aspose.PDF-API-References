---
title: PdfFileEditor.Insert
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor-metod. Infogar sidor från en annan fil i Pdf-filen på en position
type: docs
weight: 290
url: /sv/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_2}

Infogar sidor från en annan fil i Pdf-filen på en position.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Inmatnings-Pdf-fil. |
| insertLocation | Int32 | Position i inmatningsfilen. |
| portFile | Sträng | Den portade Pdf-filen. |
| startPage | Int32 | Startposition i portFile. |
| endPage | Int32 | Slutposition i portFile. |
| outputFile | Sträng | Utmatnings-Pdf-fil. |

### Returvärde

Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

Infogar sidor från en annan fil i inmatnings-Pdf-filen.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Ström | Inmatningsström av Pdf-fil. |
| insertLocation | Int32 | Infogningsposition i inmatningsfilen. |
| portStream | Ström | Ström av Pdf-fil för sidor. |
| startPage | Int32 | Från vilken sida som ska börja. |
| endPage | Int32 | Till vilken sida som ska sluta. |
| outputStream | Ström | Utmatningsström. |

### Returvärde

Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_3}

Infogar sidor från en annan fil i inmatnings-Pdf-filen.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Inmatnings-Pdf-fil. |
| insertLocation | Int32 | Infogningsposition i inmatningsfilen. |
| portFile | Sträng | Sidor från Pdf-filen. |
| pageNumber | Int32[] | Sidnumret av den portade i portFile. |
| outputFile | Sträng | Utmatnings-Pdf-fil. |

### Returvärde

Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

Infogar sidor från en annan fil i inmatnings-Pdf-filen.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Ström | Inmatningsström av Pdf-fil. |
| insertLocation | Int32 | Infogningsposition i inmatningsfilen. |
| portStream | Ström | Ström av Pdf-fil för sidor. |
| pageNumber | Int32[] | Sidnumret av den portade i portFile. |
| outputStream | Ström | Utmatningsström. |

### Returvärde

Sant om operationen lyckades.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)