---
title: "PdfExtractor.GetNextImage"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfExtractor. Recupera l'immagine successiva dal documento PDF. Nota: ExtractImage deve essere chiamato prima di utilizzare questo metodo"
type: docs
weight: 170
url: /it/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

Recupera l'immagine successiva dal documento PDF. Nota: ExtractImage deve essere chiamato prima dell'uso di questo metodo.

```csharp
public bool GetNextImage(string outputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | File in cui l'immagine sarà memorizzata |

### Valore di ritorno

True se l'immagine è stata estratta con successo

## Esempi

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

### Vedi anche

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

Recupera l'immagine successiva dal documento PDF con il formato immagine specificato. Nota: ExtractImage deve essere chiamato prima dell'uso di questo metodo.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | String | File in cui l'immagine sarà memorizzata |
| format | ImageFormat | Il formato dell'immagine. |

### Valore di ritorno

True se l'immagine è stata estratta con successo

### Vedi anche

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Recupera l'immagine successiva dal file PDF e la memorizza nello stream con il formato immagine specificato.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Stream in cui i dati dell'immagine saranno salvati |
| format | ImageFormat | Il formato dell'immagine. |

### Valore di ritorno

True nel caso l'immagine sia estratta con successo.

### Vedi anche

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Recupera l'immagine successiva dal file PDF e la memorizza nello stream.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputStream | Stream | Stream in cui i dati dell'immagine saranno salvati |

### Valore di ritorno

True nel caso l'immagine sia estratta con successo.

### Vedi anche

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


