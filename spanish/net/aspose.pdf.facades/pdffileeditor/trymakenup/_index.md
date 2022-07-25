---
title: TryMakeNUp
second_title: Referencia de API de Aspose.PDF para .NET
description: Crea un documento N-up y almacena el resultado en el objeto HttpResponse.
type: docs
weight: 470
url: /es/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, int, int, PageSize, HttpResponse) {#trymakenup_6}

Crea un documento N-up y almacena el resultado en el objeto HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta al archivo fuente. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |
| pageSize | PageSize | Tamaño de página en el archivo de resultados. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no genera una excepción si la operación falla.

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

Crea un documento N-up y almacena el resultado en el objeto HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de documento de origen. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |
| pageSize | PageSize | Tamaño de página en el archivo de resultados. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no genera una excepción si la operación falla.

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

Crea un documento N-up y almacena el resultado en HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Nombre del archivo de origen. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no genera una excepción si la operación falla.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

Crea un documento N-up y almacena el resultado en HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de documento de entrada. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |
| response | HttpResponse | HttpResponse donde se almacenará el resultado. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no genera una excepción si la operación falla.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

Crea un documento N-Up desde el primer archivo de entrada hasta el archivo de salida.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Ingrese la ruta y el nombre del archivo pdf. |
| outputFile | String | Nombre y ruta del archivo pdf de salida. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no genera una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup_2}

Crea un documento N-Up a partir del flujo de entrada y guarda el resultado en el flujo de salida.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Entrada pdf stream. |
| outputStream | Stream | Flujo de salida pdf. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no genera una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_3}

Crea un documento N-Up desde el primer flujo de entrada hasta el flujo de salida.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Entrada pdf stream. |
| outputStream | Stream | Flujo de salida pdf. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no genera una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_10}

Crea un documento N-Up a partir de los dos archivos PDF de entrada en el archivo de salida. Cada página de archivo de salida contendrá dos páginas, una página es del primer archivo de entrada y otra es del segundo archivo de entrada. Las dos páginas se apilan horizontalmente.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| firstInputFile | String | primer archivo de entrada. |
| secondInputFile | String | segundo archivo de entrada. |
| outputFile | String | Nombre y ruta del archivo pdf de salida. |

### Valor_devuelto

verdadero si la operación se completó con éxito; de lo contrario, falso

### Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no genera una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_4}

Crea un documento N-Up desde los dos flujos de PDF de entrada a outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| firstInputStream | Stream | primer flujo de entrada. |
| secondInputStream | Stream | segundo flujo de entrada. |
| outputStream | Stream | Flujo de salida pdf. |

### Valor_devuelto

verdadero si la operación se completó con éxito; de lo contrario, falso

### Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no genera una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_11}

Hace un documento N-Up desde los archivos PDF de entrada múltiple a archivo de salida. Cada página de archivo de salida contendrá varias páginas, que se combinan con las páginas en los archivos de entrada del mismo número de página. Las páginas múltiples se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFiles | String[] | Entrada de archivos PDF. |
| outputFile | String | Nombre y ruta del archivo pdf de salida. |
| isSidewise | Boolean | Forma apilada, verdadero para horizontal y falso para vertical. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no genera una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_5}

Crea un documento N-Up desde los flujos de PDF de múltiples entradas a outputStream. Cada página de outputStream contendrá varias páginas, que se combinan con las páginas en los flujos de entrada del mismo número de página. Las páginas múltiples se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStreams | Stream[] | Flujos de PDF de entrada. |
| outputStream | Stream | Flujo de salida en pdf. |
| isSidewise | Boolean | Forma apilada, verdadero para horizontal y falso para vertical. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no genera una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_9}

Crea un documento N-Up desde el archivo de entrada hasta el archivo de salida.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Ingrese la ruta y el nombre del archivo pdf. |
| outputFile | String | Nombre y ruta del archivo pdf de salida. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no genera una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Ver también

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
