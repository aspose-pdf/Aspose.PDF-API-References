---
title: PdfFileEditor.MakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metod. Gör ett häfte från indatafilen till utdatafilen
type: docs
weight: 300
url: /sv/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_4}

Gör ett häfte från indatafilen till utdatafilen.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg och namn på indata pdf-fil. |
| outputFile | Sträng | Sökväg och namn på utdata pdf-fil. |

### Returvärde

boolean - Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet}

Gör ett häfte från InputStream till outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indata pdf-ström. |
| outputStream | Stream | utdata pdf-ström. |

### Returvärde

Sant om operationen lyckades.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_5}

Gör ett häfte från inputFile till outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg och namn på indata pdf-fil. |
| outputFile | Sträng | Sökväg och namn på utdata pdf-fil. |
| pageSize | PageSize | Sidstorleken på utdata pdf-fil. |

### Returvärde

Sant om operationen lyckades.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_1}

Gör ett häfte från indataströmmen och spara resultatet i utdataströmmen.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indata PDF-ström. |
| outputStream | Stream | utdata pdf-ström. |
| pageSize | PageSize | Sidstorleken på utdata pdf-fil. |

### Returvärde

Sant om operationen lyckades.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_7}

Gör ett anpassat häfte från firstInputFile till outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Indatafilen. |
| outputFile | Sträng | Sökväg och namn på utdata pdf-fil. |
| leftPages | Int32[] | De vänstra sidorna av häftet. |
| rightPages | Int32[] | De högra sidorna av häftet. |

### Returvärde

boolean - Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_3}

Gör ett anpassat häfte från firstInputStream till outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indataströmmen. |
| outputStream | Stream | utdata pdf-ström. |
| leftPages | Int32[] | De vänstra sidorna. |
| rightPages | Int32[] | De högra sidorna. |

### Returvärde

boolean - Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se Även

* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_6}

Gör ett anpassat häfte från firstInputFile till outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Indatafilen. |
| outputFile | Sträng | Sökväg och namn på utdata pdf-fil. |
| pageSize | PageSize | Sidstorleken på utdata pdf-fil. |
| leftPages | Int32[] | De vänstra sidorna. |
| rightPages | Int32[] | De högra sidorna. |

### Returvärde

boolean - Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_2}

Gör ett häfte från firstInputStream till outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indataströmmen. |
| outputStream | Stream | utdata pdf-ström. |
| pageSize | PageSize | Sidstorleken på utdata pdf-fil. |
| leftPages | Int32[] | De vänstra sidorna. |
| rightPages | Int32[] | De högra sidorna. |

### Returvärde

boolean - Sant för framgång, eller falskt.

## Exempel

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)


## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

Gör ett häfte från källfilen och lagrar resultatet i HttpResponse-objekt.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg till källfilen. |
| pageSize | PageSize | Önskad sidstorlek. |
| leftPages | Int32[] | Array av sidnummer som ska placeras till vänster. |
| rightPages | Int32[] | Array av sidnummer som ska placeras till höger. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

Sant om operationen lyckades.

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

Gör ett häfte från PDF-filen och lagrar det i HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indata dokumentström. |
| pageSize | PageSize | Önskad sidstorlek. |
| leftPages | Int32[] | Array av sidnummer som kommer att placeras till vänster. |
| rightPages | Int32[] | Array av sidnummer som kommer att placeras till höger. |
| response | HttpResponse | HttpResponse-objekt. |

### Returvärde

Sant om operationen lyckades.

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

Gör ett häfte från källfilen och lagrar resultatet i HttpResponse-objekt.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFile | Sträng | Sökväg till källfilen. |
| pageSize | PageSize | Önskad sidstorlek i utdatafilen. |
| response | HttpResponse | HttpResponse-objekt där resultatet kommer att lagras. |

### Returvärde

Sant om operationen lyckades.

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

Gör ett häfte från källfilen och lagrar resultatet i HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Indata dokumentström. |
| pageSize | PageSize | Önskad sidstorlek i utdatafilen. |
| response | HttpResponse | Respose-objekt där resultatet kommer att sparas. |

### Returvärde

sant om häftet byggdes framgångsrikt.

### Se Även

* klass [PageSize](../../../aspose.pdf/pagesize/)
* klass [PdfFileEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)