---
title: Stamp.BindImage
second_title: Aspose.PDF for .NET API Reference
description: Metodo Stamp. Imposta l'immagine come un timbro
type: docs
weight: 100
url: /it/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

Imposta l'immagine come un timbro.

```csharp
public void BindImage(string imageFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageFile | String | Nome e percorso del file immagine. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Vedi Anche

* classe [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

Imposta l'immagine che sarà utilizzata come timbro.

```csharp
public void BindImage(Stream image)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | Stream | Stream che contiene i dati dell'immagine. |

### Vedi Anche

* classe [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)