---
title: Page.AddImage
second_title: Aspose.PDF for .NET API Reference
description: Método de página. Agrega una imagen en la página y la ubica en el medio del rectángulo especificado, manteniendo la proporción de las imágenes.
type: docs
weight: 350
url: /es/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

Agrega una imagen en la página y la ubica en el medio del rectángulo especificado, manteniendo la proporción de la imagen.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageStream | Stream | El flujo de la imagen. |
| imageRect | Rectangle | La posición de la imagen. |
| bbox | Rectangle | Bbox de la imagen. |
| autoAdjustRectangle | Boolean | Ajustar la imagen en el centro del rectángulo de entrada. |

### Ver También

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

Agrega una imagen buscable en la página y la ubica en el medio del rectángulo especificado, manteniendo la proporción de la imagen.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hocr | String | El hocr de la imagen. |
| imageStream | Stream | El flujo de la imagen. |
| imageRect | Rectangle | La posición de la imagen. |
| bbox | Rectangle | El bbox de la imagen. |

### Ver También

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

Agrega una imagen en la página y la coloca dependiendo de la posición del rectángulo de la imagen.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageStream | Stream | El flujo de la imagen. |
| imageRect | Rectangle | La posición predeterminada de la imagen en la página. |
| imageWidth | Int32 | El ancho de la imagen. |
| imageHeight | Int32 | La altura de la imagen. |
| saveImageProportions | Boolean | Si la bandera se establece en verdadero, la imagen se coloca en la posición del rectángulo; de lo contrario, el tamaño del rectángulo se vuelve igual al tamaño de la imagen. |
| bbox | Rectangle | El bbox de la imagen. |

### Ver También

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

Agrega una imagen en la página y la ubica en el medio del rectángulo especificado, manteniendo la proporción de la imagen.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagePath | String | La ruta a la imagen. |
| rectangle | Rectangle | La posición de la imagen. |

### Ver También

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)