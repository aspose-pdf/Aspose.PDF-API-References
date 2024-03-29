---
title: BindImage
second_title: Referencia de API de Aspose.PDF para .NET
description: Establece la imagen como un sello.
type: docs
weight: 100
url: /es/net/aspose.pdf.facades/stamp/bindimage/
---
## BindImage(string) {#bindimage_1}

Establece la imagen como un sello.

```csharp
public void BindImage(string imageFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| imageFile | String | Nombre del archivo de imagen y ruta. |

### Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Ver también

* class [Stamp](../../stamp)
* espacio de nombres [Aspose.Pdf.Facades](../../stamp)
* asamblea [Aspose.PDF](../../../)

---

## BindImage(Stream) {#bindimage}

Establece la imagen que se usará como sello.

```csharp
public void BindImage(Stream image)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | Stream | Stream que contiene datos de imagen. |

### Ver también

* class [Stamp](../../stamp)
* espacio de nombres [Aspose.Pdf.Facades](../../stamp)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
