---
title: "Stamp.BindImage"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Stamp. Imposta l'immagine come timbro"
type: docs
weight: 100
url: /it/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

Imposta l'immagine come timbro.

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

### Vedi anche

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

Imposta l'immagine che sarà usata come timbro.

```csharp
public void BindImage(Stream image)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| immagine | Stream | Stream che contiene i dati dell'immagine. |

### Vedi anche

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


