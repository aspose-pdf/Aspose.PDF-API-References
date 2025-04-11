---
title: Stamp.BindImage
second_title: Aspose.PDF for .NET API Reference
description: Método Stamp. Define a imagem como um carimbo
type: docs
weight: 100
url: /pt/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

Define a imagem como um carimbo.

```csharp
public void BindImage(string imageFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageFile | String | Nome e caminho do arquivo de imagem. |

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Veja Também

* classe [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

Define a imagem que será usada como carimbo.

```csharp
public void BindImage(Stream image)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | Stream | Stream que contém os dados da imagem. |

### Veja Também

* classe [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)