---
title: PdfFileEditor.TryMakeNUp
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Crea un documento NUp desde el primerInputFile hasta outputFile
type: docs
weight: 440
url: /es/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

Crea un documento N-up y almacena el resultado en el objeto HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta al archivo fuente. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |
| pageSize | PageSize | Tamaño de página en el archivo de resultado. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.

### Véase También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

Crea un documento N-up y almacena el resultado en el objeto HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo del documento fuente. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |
| pageSize | PageSize | Tamaño de página en el archivo de resultado. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.

### Véase También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

Crea un documento N-up y almacena el resultado en HttpResponse.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Nombre del archivo fuente. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.

### Véase También

* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

Crea un documento N-up y almacena el resultado en HttpResponse.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo del documento de entrada. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |
| response | HttpResponse | HttpResponse donde se almacenará el resultado. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.

### Véase También

* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

Crea un documento N-Up desde el primerInputFile hasta outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta y nombre del archivo pdf de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Véase También

* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

Crea un documento N-Up desde el flujo de entrada y guarda el resultado en el flujo de salida.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo pdf de entrada. |
| outputStream | Stream | Flujo pdf de salida. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### Véase También

* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

Crea un documento N-Up desde el primer flujo de entrada hasta el flujo de salida.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo pdf de entrada. |
| outputStream | Stream | Flujo pdf de salida. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Véase También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

Crea un documento N-Up desde los dos archivos PDF de entrada hasta outputFile. Cada página de outputFile contendrá dos páginas, una página es del primer archivo de entrada y otra es del segundo archivo de entrada. Las dos páginas están apiladas horizontalmente.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputFile | String | primer archivo de entrada. |
| secondInputFile | String | segundo archivo de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false

## Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Véase También

* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

Crea un documento N-Up desde los dos flujos PDF de entrada hasta outputStream.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputStream | Stream | primer flujo de entrada. |
| secondInputStream | Stream | segundo flujo de entrada. |
| outputStream | Stream | Flujo pdf de salida. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false

## Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### Véase También

* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

Crea un documento N-Up desde los múltiples archivos PDF de entrada hasta outputFile. Cada página de outputFile contendrá múltiples páginas, que son combinaciones de páginas en los archivos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFiles | String[] | Archivos Pdf de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |
| isSidewise | Boolean | Forma de apilamiento, verdadero para horizontal y falso para vertical. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Véase También

* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

Crea un documento N-Up desde los múltiples flujos PDF de entrada hasta outputStream. Cada página de outputStream contendrá múltiples páginas, que son combinaciones de páginas en los flujos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStreams | Stream[] | Flujos Pdf de entrada. |
| outputStream | Stream | Flujo pdf de salida. |
| isSidewise | Boolean | Forma de apilamiento, verdadero para horizontal y falso para vertical. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Véase También

* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

Crea un documento N-Up desde el archivo de entrada hasta outputFile.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta y nombre del archivo pdf de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryMakeNUp es como el método MakeNUp, excepto que el método TryMakeNUp no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Véase También

* clase [PageSize](../../../aspose.pdf/pagesize/)
* clase [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)