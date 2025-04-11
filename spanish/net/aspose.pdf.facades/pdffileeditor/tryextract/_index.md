---
title: PdfFileEditor.TryExtract
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Extrae páginas de archivos de entrada y las guarda como un nuevo archivo Pdf
type: docs
weight: 410
url: /es/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

Extrae páginas del archivo de entrada, las guarda como un nuevo archivo Pdf.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo Pdf de entrada. |
| startPage | Int32 | Número de la página de inicio. |
| endPage | Int32 | Número de la página final. |
| outputFile | String | Ruta del archivo Pdf de salida. |

### Valor de Retorno

Verdadero si tiene éxito, o falso.

## Observaciones

El método TryExtract es como el método Extract, excepto que el método TryExtract no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

Extrae páginas especificadas por un arreglo de números, las guarda como un nuevo archivo PDF.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo de entrada. |
| pageNumber | Int32[] | Índice de la página del archivo de entrada. |
| outputFile | String | Ruta del archivo de salida. |

### Valor de Retorno

verdadero si la operación se completó con éxito; de lo contrario, falso.

## Observaciones

El método TryExtract es como el método Extract, excepto que el método TryExtract no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Extrae páginas especificadas por un arreglo de números, las guarda como un nuevo archivo Pdf.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo del archivo de entrada. |
| pageNumber | Int32[] | Índice de la página del archivo de entrada. |
| outputStream | Stream | Flujo del archivo de salida. |

### Valor de Retorno

Verdadero si tiene éxito, o falso.

## Observaciones

El método TryExtract es como el método Extract, excepto que el método TryExtract no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)


## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

Extrae páginas especificadas del archivo fuente y almacena el resultado en el objeto HttpResponse.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo del documento fuente. |
| pageNumber | Int32[] | Arreglo de números de página que serán extraídos. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor de Retorno

verdadero si la operación se completó con éxito; de lo contrario, falso.

## Observaciones

El método TryExtract es como el método Extract, excepto que el método TryExtract no lanza una excepción si la operación falla.

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

Extrae páginas especificadas del archivo fuente y almacena el resultado en el objeto HttpResponse.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo fuente. |
| pageNumber | Int32[] | Arreglo de números de página que serán extraídos. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor de Retorno

verdadero si la operación se completó con éxito; de lo contrario, falso.

## Observaciones

El método TryExtract es como el método Extract, excepto que el método TryExtract no lanza una excepción si la operación falla.

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)