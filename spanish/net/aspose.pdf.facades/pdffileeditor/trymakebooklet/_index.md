---
title: TryMakeBooklet
second_title: Referencia de API de Aspose.PDF para .NET
description: Crea un folleto a partir del archivo de origen y almacena el resultado en objetos HttpResponse.
type: docs
weight: 460
url: /es/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, PageSize, int[], int[], HttpResponse) {#trymakebooklet_6}

Crea un folleto a partir del archivo de origen y almacena el resultado en objetos HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo de origen. |
| pageSize | PageSize | Tamaño de página deseado. |
| leftPages | Int32[] | Una serie de números de página que se colocarán a la izquierda. |
| rightPages | Int32[] | Matriz de números de página que se colocarán a la derecha. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

Crea un folleto a partir de un archivo PDF y lo almacena en HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de documentos de entrada. |
| pageSize | PageSize | Tamaño de página deseado. |
| leftPages | Int32[] | Matriz de números de página que se colocarán a la izquierda. |
| rightPages | Int32[] | Matriz de números de página que se colocarán a la derecha. |
| response | HttpResponse | Objeto HttpResponse. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Crea un folleto a partir del archivo de origen y almacena el resultado en objetos HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo de origen. |
| pageSize | PageSize | Tamaño de página deseado en el archivo de salida. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor_devuelto

Verdadero si la operación se realiza correctamente.

### Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Crea un folleto a partir del archivo de origen y almacena el resultado en HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de documentos de entrada. |
| pageSize | PageSize | Tamaño de página deseado en el archivo de salida. |
| response | HttpResponse | Objeto de respuesta donde se guardará el resultado. |

### Valor_devuelto

true si el folleto se creó correctamente.

### Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Hace un folleto desde el archivo de entrada hasta el archivo de salida.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Ingrese la ruta y el nombre del archivo pdf. |
| outputFile | String | Nombre y ruta del archivo pdf de salida. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet_2}

Hace un folleto desde InputStream hasta outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Entrada pdf stream. |
| outputStream | Stream | flujo de salida pdf. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_9}

Crea un folleto desde el archivo de entrada hasta el archivo de salida.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Ingrese la ruta y el nombre del archivo pdf. |
| outputFile | String | Nombre y ruta del archivo pdf de salida. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |

### Valor_devuelto

Verdadero si la operación se realiza correctamente.

### Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_3}

Crea un folleto a partir del flujo de entrada y guarda el resultado en el flujo de salida.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo PDF de entrada. |
| outputStream | Stream | flujo de salida pdf. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_11}

Crea un folleto personalizado desde el primer archivo de entrada hasta el archivo de salida.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | El archivo de entrada. |
| outputFile | String | Nombre y ruta del archivo pdf de salida. |
| leftPages | Int32[] | Las páginas de la izquierda del folleto. |
| rightPages | Int32[] | Las páginas correctas del folleto. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_5}

Crea un folleto personalizado desde el primer flujo de entrada hasta el flujo de salida.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | El flujo de entrada. |
| outputStream | Stream | flujo de salida en pdf. |
| leftPages | Int32[] | Las páginas de la izquierda. |
| rightPages | Int32[] | Las páginas correctas. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_10}

Crea un folleto personalizado desde el primer archivo de entrada hasta el archivo de salida.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | El archivo de entrada. |
| outputFile | String | Nombre y ruta del archivo pdf de salida. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |
| leftPages | Int32[] | Las páginas de la izquierda. |
| rightPages | Int32[] | Las páginas correctas. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_4}

Crea un folleto desde el primer flujo de entrada hasta el flujo de salida.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | El flujo de entrada. |
| outputStream | Stream | flujo de salida en pdf. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |
| leftPages | Int32[] | Las páginas de la izquierda. |
| rightPages | Int32[] | Las páginas correctas. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
