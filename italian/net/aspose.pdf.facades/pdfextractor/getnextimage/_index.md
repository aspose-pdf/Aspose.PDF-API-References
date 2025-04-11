---
title: PdfExtractor.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor method. Retrieves next image from PDF document. Note ExtractImage must be called before using of this method
type: docs
weight: 170
url: /it/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

Recupera la prossima immagine dal documento PDF. Nota: ExtractImage deve essere chiamato prima di utilizzare questo metodo.

```csharp
public bool GetNextImage(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | File dove l'immagine sarà memorizzata |

### Return Value

True se l'immagine è stata estratta con successo

## Examples

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Recupera la prossima immagine dal documento PDF con il formato immagine dato. Nota: ExtractImage deve essere chiamato prima di utilizzare questo metodo.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | File dove l'immagine sarà memorizzata |
| format | ImageFormat | Il formato dell'immagine. |

### Return Value

True se l'immagine è stata estratta con successo

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Recupera la prossima immagine dal file PDF e la memorizza nello stream con il formato immagine dato.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream dove i dati dell'immagine saranno salvati |
| format | ImageFormat | Il formato dell'immagine. |

### Return Value

True nel caso in cui l'immagine sia stata estratta con successo.

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Recupera la prossima immagine dal file PDF e la memorizza nello stream.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream dove i dati dell'immagine saranno salvati |

### Return Value

True nel caso in cui l'immagine sia stata estratta con successo.

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)