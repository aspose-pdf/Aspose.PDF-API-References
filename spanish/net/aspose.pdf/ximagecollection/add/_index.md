---
title: XImageCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: Método XImageCollection. Agrega una nueva imagen a la lista de imágenes. Este método agrega la imagen como referencia al mismo PdfObject, lo que permite reducir el tamaño del archivo
type: docs
weight: 70
url: /es/net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add_2}

Agrega una nueva imagen a la lista de imágenes. Este método agrega la imagen como referencia al mismo PdfObject (lo que permite reducir el tamaño del archivo)

```csharp
public string Add(XImage image)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | XImage | XImage que se va a agregar. |

### Valor de Retorno

Nombre de la imagen agregada.

### Ver También

* clase [XImage](../../ximage/)
* clase [XImageCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Add(Stream) {#add_3}

Agrega una entidad al final de la colección, para que la entidad pueda ser accedida por el último índice.

```csharp
public string Add(Stream image)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | Stream | Stream que contiene datos de imagen (en formato JPEG). |

### Valor de Retorno

Nombre de la imagen agregada.

### Ver También

* clase [XImageCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Add(BitmapInfo) {#add}

Agrega una entidad al final de la colección, para que la entidad pueda ser accedida por el último índice.

```csharp
public string Add(BitmapInfo bitmapInfo)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Objeto que contiene un arreglo de píxeles e información de bitmap (Ancho, Alto, Formato de Píxel). |

### Valor de Retorno

Nombre de la imagen agregada.

### Ver También

* clase [BitmapInfo](../../bitmapinfo/)
* clase [XImageCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_4}

Agrega una entidad al final de la colección, para que la entidad pueda ser accedida por el último índice.

```csharp
public string Add(Stream image, ImageFilterType filterType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | Stream | Stream que contiene datos de imagen. |
| filterType | ImageFilterType | El tipo de filtro de imagen. |

### Valor de Retorno

Nombre de la imagen agregada.

### Ver También

* enum [ImageFilterType](../../imagefiltertype/)
* clase [XImageCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Add(BitmapInfo, ImageFilterType) {#add_1}

Agrega una entidad al final de la colección, para que la entidad pueda ser accedida por el último índice.

```csharp
public string Add(BitmapInfo bitmapInfo, ImageFilterType filterType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Objeto que contiene un arreglo de píxeles e información de bitmap (Ancho, Alto, Formato de Píxel). |
| filterType | ImageFilterType | El tipo de filtro de imagen. |

### Valor de Retorno

Nombre de la imagen agregada.

### Ver También

* clase [BitmapInfo](../../bitmapinfo/)
* enum [ImageFilterType](../../imagefiltertype/)
* clase [XImageCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_5}

Agrega una entidad al final de la colección, para que la entidad pueda ser accedida por el último índice.

```csharp
public void Add(Stream image, int quality)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | Stream | Stream que contiene datos de imagen (en formato JPEG). |
| quality | Int32 | Calidad JPEG. |

### Ver También

* clase [XImageCollection](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)