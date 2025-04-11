---
title: PdfFileEditor.MakeNUp
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Crea un documento NUp a partir de los dos flujos PDF de entrada a outputStream
type: docs
weight: 310
url: /es/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

Crea un documento N-Up a partir del firstInputFile a outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta y nombre del archivo pdf de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |

### Valor de retorno

boolean - Verdadero si tiene éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Véase también

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

Crea un documento N-Up a partir del flujo de entrada y guarda el resultado en el flujo de salida.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo pdf de entrada. |
| outputStream | Stream | Flujo pdf de salida. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |

### Valor de retorno

boolean - Verdadero si tiene éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Véase también

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

Crea un documento N-Up a partir del primer flujo de entrada al flujo de salida.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo pdf de entrada. |
| outputStream | Stream | Flujo pdf de salida. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |

### Valor de retorno

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Véase también

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

Crea un documento N-Up a partir de los dos archivos PDF de entrada a outputFile. Cada página de outputFile contendrá dos páginas, una página es del primer archivo de entrada y otra es del segundo archivo de entrada. Las dos páginas están apiladas horizontalmente.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputFile | String | primer archivo de entrada. |
| secondInputFile | String | segundo archivo de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |

### Valor de retorno

boolean - Verdadero si tiene éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Véase también

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

Crea un documento N-Up a partir de los dos flujos PDF de entrada a outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputStream | Stream | primer flujo de entrada. |
| secondInputStream | Stream | segundo flujo de entrada. |
| outputStream | Stream | Flujo pdf de salida. |

### Valor de retorno

boolean - Verdadero si tiene éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### Véase también

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

Crea un documento N-Up a partir de los múltiples archivos PDF de entrada a outputFile. Cada página de outputFile contendrá múltiples páginas, que son combinaciones de páginas en los archivos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFiles | String[] | Archivos Pdf de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |
| isSidewise | Boolean | Forma de apilamiento, verdadero para horizontal y falso para vertical. |

### Valor de retorno

boolean - Verdadero si tiene éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### Véase también

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

Crea un documento N-Up a partir de los múltiples flujos PDF de entrada a outputStream. Cada página de outputStream contendrá múltiples páginas, que son combinaciones de páginas en los flujos de entrada del mismo número de página. Las múltiples páginas se apilan horizontalmente si isSidewise es verdadero y se apilan verticalmente si isSidewise es falso.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStreams | Stream[] | Flujos Pdf de entrada. |
| outputStream | Stream | Flujo pdf de salida. |
| isSidewise | Boolean | Forma de apilamiento, verdadero para horizontal y falso para vertical. |

### Valor de retorno

boolean - Verdadero si tiene éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### Véase también

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_5}

Crea un documento N-Up a partir del archivo de entrada a outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta y nombre del archivo pdf de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |

### Valor de retorno

boolean - Verdadero si tiene éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### Véase también

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

Crea un documento N-Up a partir del firstInputFile a outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta y nombre del archivo pdf de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |

### Valor de retorno

boolean - Verdadero si tiene éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### Véase también

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

Crea un documento N-Up a partir del flujo de entrada y guarda el resultado en el flujo de salida.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo pdf de entrada. |
| outputStream | Stream | Flujo pdf de salida. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |

### Valor de retorno

boolean - Verdadero si tiene éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### Véase también

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

Crea un documento N-Up a partir del primer flujo de entrada al flujo de salida.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo pdf de entrada. |
| outputStream | Stream | Flujo pdf de salida. |
| x | Int32 | Número de columnas. |
| y | Int32 | Número de filas. |
| pageSize | PageSize | El tamaño de página del archivo pdf de salida. |

### Valor de retorno

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### Véase también

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

Crea un documento N-Up a partir de los dos archivos PDF de entrada a outputFile. Cada página de outputFile contendrá dos páginas, una página es del primer archivo de entrada y otra es del segundo archivo de entrada. Las dos páginas están apiladas horizontalmente.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputFile | String | primer archivo de entrada. |
| secondInputFile | String | segundo archivo de entrada. |
| outputFile | String | Ruta y nombre del archivo pdf de salida. |

### Valor de retorno

boolean - Verdadero si tiene éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### Véase también

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)