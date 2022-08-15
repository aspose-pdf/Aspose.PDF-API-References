---
title: AddImage
second_title: Referencia de API de Aspose.PDF para .NET
description: Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas.
type: docs
weight: 50
url: /es/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| imageStream | Stream | Flujo de imagen de entrada. |
| pageNum | Int32 | El número de página que recibirá la imagen. |
| lowerLeftX | Single | La x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | Single | La y inferior izquierda del rectángulo de la imagen. |
| upperRightX | Single | La x superior derecha del rectángulo de la imagen. |
| upperRightY | Single | La parte superior derecha y del rectángulo de la imagen. |

### Valor_devuelto

Verdadero si el éxito es falso en caso contrario.

### Ejemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### Ver también

* class [PdfFileMend](../../pdffilemend)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilemend)
* asamblea [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| imageStream | Stream | Flujo de imagen de entrada. |
| pageNum | Int32 | El número de página que recibirá la imagen. |
| lowerLeftX | Single | La x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | Single | La y inferior izquierda del rectángulo de la imagen. |
| upperRightX | Single | La x superior derecha del rectángulo de la imagen. |
| upperRightY | Single | La parte superior derecha y del rectángulo de la imagen. |
| compositingParameters | CompositingParameters | Los parámetros de composición de gráficos para la imagen. |

### Valor_devuelto

Verdadero si el éxito es falso en caso contrario.

### Ejemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Ver también

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilemend)
* asamblea [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| imageStream | Stream | Flujo de imagen de entrada. |
| pageNums | Int32[] | El número de páginas que recibirá la imagen. |
| lowerLeftX | Single | La x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | Single | La y inferior izquierda del rectángulo de la imagen. |
| upperRightX | Single | La x superior derecha del rectángulo de la imagen. |
| upperRightY | Single | La parte superior derecha y del rectángulo de la imagen. |

### Valor_devuelto

Verdadero si el éxito es falso en caso contrario.

### Ejemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### Ver también

* class [PdfFileMend](../../pdffilemend)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilemend)
* asamblea [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| imageStream | Stream | Flujo de imagen de entrada. |
| pageNums | Int32[] | El número de páginas que recibirá la imagen. |
| lowerLeftX | Single | La x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | Single | La y inferior izquierda del rectángulo de la imagen. |
| upperRightX | Single | La x superior derecha del rectángulo de la imagen. |
| upperRightY | Single | La parte superior derecha y del rectángulo de la imagen. |
| compositingParameters | CompositingParameters | Los parámetros de composición de gráficos para las imágenes. |

### Valor_devuelto

Verdadero si el éxito es falso en caso contrario.

### Ejemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Ver también

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilemend)
* asamblea [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| imageName | String | La ruta del archivo de imagen de entrada. |
| pageNum | Int32 | El número de página que recibirá la imagen. |
| lowerLeftX | Single | La x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | Single | La y inferior izquierda del rectángulo de la imagen. |
| upperRightX | Single | La x superior derecha del rectángulo de la imagen. |
| upperRightY | Single | La parte superior derecha y del rectángulo de la imagen. |

### Valor_devuelto

Verdadero si el éxito es falso en caso contrario.

### Ejemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Ver también

* class [PdfFileMend](../../pdffilemend)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilemend)
* asamblea [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| imageName | String | La ruta del archivo de imagen de entrada. |
| pageNum | Int32 | El número de página que recibirá la imagen. |
| lowerLeftX | Single | La x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | Single | La y inferior izquierda del rectángulo de la imagen. |
| upperRightX | Single | La x superior derecha del rectángulo de la imagen. |
| upperRightY | Single | La parte superior derecha y del rectángulo de la imagen. |
| compositingParameters | CompositingParameters | Los parámetros de composición de gráficos para las imágenes. |

### Valor_devuelto

Verdadero si el éxito es falso en caso contrario.

### Ejemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Ver también

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilemend)
* asamblea [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| imageName | String | La ruta del archivo de imagen de entrada. |
| pageNums | Int32[] | El número de páginas que recibirá la imagen. |
| lowerLeftX | Single | La x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | Single | La y inferior izquierda del rectángulo de la imagen. |
| upperRightX | Single | La x superior derecha del rectángulo de la imagen. |
| upperRightY | Single | La parte superior derecha y del rectángulo de la imagen. |

### Valor_devuelto

Verdadero si el éxito es falso en caso contrario.

### Ejemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Ver también

* class [PdfFileMend](../../pdffilemend)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilemend)
* asamblea [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| imageName | String | La ruta del archivo de imagen de entrada. |
| pageNums | Int32[] | El número de páginas que recibirá la imagen. |
| lowerLeftX | Single | La x inferior izquierda del rectángulo de la imagen. |
| lowerLeftY | Single | La y inferior izquierda del rectángulo de la imagen. |
| upperRightX | Single | La x superior derecha del rectángulo de la imagen. |
| upperRightY | Single | La parte superior derecha y del rectángulo de la imagen. |
| compositingParameters | CompositingParameters | Los parámetros de composición de gráficos para las imágenes. |

### Valor_devuelto

Verdadero si el éxito es falso en caso contrario.

### Ejemplos

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Ver también

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilemend)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
