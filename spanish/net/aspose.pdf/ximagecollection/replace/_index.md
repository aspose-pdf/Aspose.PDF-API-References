---
title: XImageCollection.Replace
second_title: Aspose.PDF for .NET API Reference
description: Método XImageCollection. Reemplazar imagen en la colección con otra imagen
type: docs
weight: 150
url: /es/net/aspose.pdf/ximagecollection/replace/
---
## Replace(int, Stream) {#replace}

Reemplazar imagen en la colección con otra imagen.

```csharp
public void Replace(int index, Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Índice del elemento de la colección que será reemplazado en el rango [1..cantidad de imágenes]. |
| stream | Stream | Stream que contiene los datos de la imagen (en formato JPEG). |

### Ver También

* clase [XImageCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)

---

## Replace(int, Stream, int, bool) {#replace_2}

Reemplazar imagen en la colección con otra imagen.

```csharp
public void Replace(int index, Stream stream, int quality, bool isBlackAndWhite)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Índice del elemento de la colección que será reemplazado en el rango [1..cantidad de imágenes]. |
| stream | Stream | Stream que contiene los datos de la imagen (en formato JPEG). |
| quality | Int32 | Calidad de la compresión JPEG, en porcentaje (valores válidos son 0..100). |
| isBlackAndWhite | Boolean | Si es verdadero, la imagen se comprime con el método de compresión CCITT que proporciona mejor compresión para imágenes en blanco y negro. Puede usarse solo para imágenes en blanco y negro. |

### Ver También

* clase [XImageCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)

---

## Replace(int, Stream, int) {#replace_1}

Reemplazar imagen en la colección con otra imagen.

```csharp
public void Replace(int index, Stream stream, int quality)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Índice del elemento de la colección que será reemplazado en el rango [1..cantidad de imágenes]. |
| stream | Stream | Stream que contiene los datos de la imagen (en formato JPEG). |
| quality | Int32 | Calidad JPEG. |

### Ver También

* clase [XImageCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)