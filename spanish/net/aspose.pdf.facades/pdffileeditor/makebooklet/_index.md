---
title: PdfFileEditor.MakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Crea un folleto a partir del archivo de entrada al archivo de salida
type: docs
weight: 300
url: /es/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_4}

Crea un folleto a partir del archivo de entrada al archivo de salida.

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta y nombre del archivo pdf de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |

### Valor de Retorno

boolean - Verdadero para éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet}

Crea un folleto a partir del InputStream al outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo pdf de entrada. |
| outputStream | Stream | flujo pdf de salida. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_5}

Crea un folleto a partir del inputFile al outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta y nombre del archivo pdf de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Ver También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_1}

Crea un folleto a partir del flujo de entrada y guarda el resultado en el flujo de salida.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo PDF de entrada. |
| outputStream | Stream | flujo pdf de salida. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Ver También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_7}

Crea un folleto personalizado a partir del firstInputFile al outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | El archivo de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |
| leftPages | Int32[] | Las páginas izquierdas del folleto. |
| rightPages | Int32[] | Las páginas derechas del folleto. |

### Valor de Retorno

boolean - Verdadero para éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_3}

Crea un folleto personalizado a partir del firstInputStream al outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | El flujo de entrada. |
| outputStream | Stream | flujo pdf de salida. |
| leftPages | Int32[] | Las páginas izquierdas. |
| rightPages | Int32[] | Las páginas derechas. |

### Valor de Retorno

boolean - Verdadero para éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_6}

Crea un folleto personalizado a partir del firstInputFile al outputFile.

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | El archivo de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |
| leftPages | Int32[] | Las páginas izquierdas. |
| rightPages | Int32[] | Las páginas derechas. |

### Valor de Retorno

boolean - Verdadero para éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ver También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_2}

Crea un folleto a partir del firstInputStream al outputStream.

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | El flujo de entrada. |
| outputStream | Stream | flujo pdf de salida. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |
| leftPages | Int32[] | Las páginas izquierdas. |
| rightPages | Int32[] | Las páginas derechas. |

### Valor de Retorno

boolean - Verdadero para éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Ver También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)


## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

Crea un folleto a partir del archivo fuente y almacena el resultado en objetos HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo fuente. |
| pageSize | PageSize | Tamaño de página deseado. |
| leftPages | Int32[] | Arreglo de números de página que se colocarán a la izquierda. |
| rightPages | Int32[] | Arreglo de números de página que se colocarán a la derecha. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

### Ver También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

Crea un folleto a partir del archivo PDF y lo almacena en HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de documento de entrada. |
| pageSize | PageSize | Tamaño de página deseado. |
| leftPages | Int32[] | Arreglo de números de página que se colocarán a la izquierda. |
| rightPages | Int32[] | Arreglo de números de página que se colocarán a la derecha. |
| response | HttpResponse | Objeto HttpResponse. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

### Ver También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

Crea un folleto a partir del archivo fuente y almacena el resultado en objetos HttpResponse.

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo fuente. |
| pageSize | PageSize | Tamaño de página deseado en el archivo de salida. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

### Ver También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

Crea un folleto a partir del archivo fuente y almacena el resultado en HttpResponse.

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de documento de entrada. |
| pageSize | PageSize | Tamaño de página deseado en el archivo de salida. |
| response | HttpResponse | Objeto Respose donde se guardará el resultado. |

### Valor de Retorno

verdadero si el folleto se construyó con éxito.

### Ver También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)