---
title: PdfFileEditor.TryMakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Crea un folleto a partir del archivo de entrada al archivo de salida
type: docs
weight: 430
url: /es/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

Crea un folleto a partir del archivo fuente y almacena el resultado en objetos HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
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

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Véase También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

Crea un folleto a partir del archivo PDF y lo almacena en HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo del documento de entrada. |
| pageSize | PageSize | Tamaño de página deseado. |
| leftPages | Int32[] | Arreglo de números de página que se colocarán a la izquierda. |
| rightPages | Int32[] | Arreglo de números de página que se colocarán a la derecha. |
| response | HttpResponse | Objeto HttpResponse. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Véase También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

Crea un folleto a partir del archivo fuente y almacena el resultado en objetos HttpResponse.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo fuente. |
| pageSize | PageSize | Tamaño de página deseado en el archivo de salida. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor de Retorno

True si la operación tuvo éxito.

## Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Véase También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

Crea un folleto a partir del archivo fuente y almacena el resultado en HttpResponse.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo del documento de entrada. |
| pageSize | PageSize | Tamaño de página deseado en el archivo de salida. |
| response | HttpResponse | Objeto donde se guardará el resultado. |

### Valor de Retorno

true si el folleto se construyó con éxito.

## Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

### Véase También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

Crea un folleto a partir del archivo de entrada al archivo de salida.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta y nombre del archivo pdf de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### Véase También

* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

Crea un folleto a partir del InputStream al outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo pdf de entrada. |
| outputStream | Stream | flujo pdf de salida. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### Véase También

* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

Crea un folleto a partir del inputFile al outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta y nombre del archivo pdf de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |

### Valor de Retorno

True si la operación tuvo éxito.

## Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### Véase También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

Crea un folleto a partir del flujo de entrada y guarda el resultado en el flujo de salida.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo PDF de entrada. |
| outputStream | Stream | flujo pdf de salida. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### Véase También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

Crea un folleto personalizado a partir del firstInputFile al outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | El archivo de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |
| leftPages | Int32[] | Las páginas izquierdas del folleto. |
| rightPages | Int32[] | Las páginas derechas del folleto. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Véase También

* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

Crea un folleto personalizado a partir del firstInputStream al outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | El flujo de entrada. |
| outputStream | Stream | flujo pdf de salida. |
| leftPages | Int32[] | Las páginas izquierdas. |
| rightPages | Int32[] | Las páginas derechas. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Véase También

* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

Crea un folleto personalizado a partir del firstInputFile al outputFile.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
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

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Véase También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

Crea un folleto a partir del firstInputStream al outputStream.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
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

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeBooklet es como el método MakeBooklet, excepto que el método TryMakeBooklet no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### Véase También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)