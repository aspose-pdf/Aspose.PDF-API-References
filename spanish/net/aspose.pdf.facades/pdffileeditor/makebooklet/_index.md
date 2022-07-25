---
title: MakeBooklet
second_title: Referencia de API de Aspose.PDF para .NET
description: Hace un folleto desde el archivo de entrada hasta el archivo de salida.
type: docs
weight: 330
url: /es/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_8}

Hace un folleto desde el archivo de entrada hasta el archivo de salida.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Ingrese la ruta y el nombre del archivo pdf. |
| outputFile | String | Nombre y ruta del archivo pdf de salida. |

### Valor_devuelto

booleano: verdadero para el éxito o falso.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet_2}

Hace un folleto desde InputStream hasta outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Entrada pdf stream. |
| outputStream | Stream | flujo de salida pdf. |

### Valor_devuelto

Verdadero si la operación se realizó correctamente.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_9}

Crea un folleto desde el archivo de entrada hasta el archivo de salida.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Ingrese la ruta y el nombre del archivo pdf. |
| outputFile | String | Nombre y ruta del archivo pdf de salida. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |

### Valor_devuelto

Verdadero si la operación se realiza correctamente.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_3}

Crea un folleto a partir del flujo de entrada y guarda el resultado en el flujo de salida.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo PDF de entrada. |
| outputStream | Stream | flujo de salida pdf. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |

### Valor_devuelto

Verdadero si la operación se realizó correctamente.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_11}

Crea un folleto personalizado desde el primer archivo de entrada hasta el archivo de salida.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | El archivo de entrada. |
| outputFile | String | Nombre y ruta del archivo pdf de salida. |
| leftPages | Int32[] | Las páginas de la izquierda del folleto. |
| rightPages | Int32[] | Las páginas correctas del folleto. |

### Valor_devuelto

booleano: verdadero para el éxito o falso.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_5}

Crea un folleto personalizado desde el primer flujo de entrada hasta el flujo de salida.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | El flujo de entrada. |
| outputStream | Stream | flujo de salida en pdf. |
| leftPages | Int32[] | Las páginas de la izquierda. |
| rightPages | Int32[] | Las páginas correctas. |

### Valor_devuelto

booleano: verdadero para el éxito o falso.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_10}

Crea un folleto personalizado desde el primer archivo de entrada hasta el archivo de salida.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
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

booleano: verdadero para el éxito o falso.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_4}

Crea un folleto desde el primer flujo de entrada hasta el flujo de salida.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
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

booleano: verdadero para el éxito o falso.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

Crea un folleto a partir del archivo de origen y almacena el resultado en objetos HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
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

Verdadero si la operación se realizó correctamente.

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

Crea un folleto a partir de un archivo PDF y lo almacena en HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de documentos de entrada. |
| pageSize | PageSize | Tamaño de página deseado. |
| leftPages | Int32[] | Matriz de números de página que se colocarán a la izquierda. |
| rightPages | Int32[] | Matriz de números de página que se colocarán a la derecha. |
| response | HttpResponse | Objeto HttpResponse. |

### Valor_devuelto

Verdadero si la operación se realizó correctamente.

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

Crea un folleto a partir del archivo de origen y almacena el resultado en objetos HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo de origen. |
| pageSize | PageSize | Tamaño de página deseado en el archivo de salida. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor_devuelto

Verdadero si la operación se realiza correctamente.

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

Crea un folleto a partir del archivo de origen y almacena el resultado en HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de documentos de entrada. |
| pageSize | PageSize | Tamaño de página deseado en el archivo de salida. |
| response | HttpResponse | Objeto de respuesta donde se guardará el resultado. |

### Valor_devuelto

true si el folleto se creó correctamente.

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
