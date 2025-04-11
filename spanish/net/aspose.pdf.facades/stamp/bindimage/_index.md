---
title: Stamp.BindImage
second_title: Aspose.PDF for .NET API Reference
description: Método Stamp. Establece la imagen como un sello
type: docs
weight: 100
url: /es/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

Establece la imagen como un sello.

```csharp
public void BindImage(string imageFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageFile | String | Nombre y ruta del archivo de imagen. |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Véase también

* clase [Stamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

Establece la imagen que se utilizará como sello.

```csharp
public void BindImage(Stream image)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | Stream | Flujo que contiene los datos de la imagen. |

### Véase también

* clase [Stamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)