---
title: PdfFileEditor.TryDelete
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Elimina las páginas especificadas por un array de números del archivo de entrada y guarda como un nuevo archivo Pdf
type: docs
weight: 400
url: /es/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

Elimina las páginas especificadas por un array de números del archivo de entrada, guarda como un nuevo archivo Pdf.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo de entrada. |
| pageNumber | Int32[] | Índice de la página del archivo de entrada. |
| outputFile | String | Ruta del archivo de salida. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryDelete es como el método Delete, excepto que el método TryDelete no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

Elimina las páginas especificadas por un array de números del archivo de entrada, guarda como un nuevo archivo Pdf.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo del archivo de entrada. |
| pageNumber | Int32[] | Índice de la página del archivo de entrada. |
| outputStream | Stream | Flujo del archivo de salida. |

### Valor de Retorno

True para éxito, o false.

## Observaciones

El método TryDelete es como el método Delete, excepto que el método TryDelete no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)


## TryDelete(string, int[], HttpResponse) {#trydelete_3}

Elimina las páginas especificadas del documento y almacena el resultado en el objeto HttpResponse.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo fuente. |
| pageNumber | Int32[] | Array de números de página que deben ser eliminados. |
| response | HttpResponse | Objeto de respuesta donde se almacenará el documento resultante. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryDelete es como el método Delete, excepto que el método TryDelete no lanza una excepción si la operación falla.

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], HttpResponse) {#trydelete_1}

Elimina las páginas especificadas del documento y guarda el resultado en el objeto HttpResponse.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo del documento fuente. |
| pageNumber | Int32[] | Array de números de página que serán eliminados. |
| response | HttpResponse | Objeto HttpResponse |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryDelete es como el método Delete, excepto que el método TryDelete no lanza una excepción si la operación falla.

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)