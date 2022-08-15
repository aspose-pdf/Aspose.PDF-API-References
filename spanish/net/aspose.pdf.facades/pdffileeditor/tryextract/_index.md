---
title: TryExtract
second_title: Referencia de API de Aspose.PDF para .NET
description: Extrae páginas del archivo de entrada las guarda como un nuevo archivo PDF.
type: docs
weight: 440
url: /es/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_2}

Extrae páginas del archivo de entrada, las guarda como un nuevo archivo PDF.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Introduzca la ruta del archivo PDF. |
| startPage | Int32 | Número de página de inicio. |
| endPage | Int32 | Número de página final. |
| outputFile | String | Ruta del archivo PDF de salida. |

### Valor_devuelto

Verdadero para el éxito, o falso.

### Observaciones

El método TryExtract es como el método Extract, excepto que el método TryExtract no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_3}

Extrae las páginas especificadas por matriz de números y las guarda como un nuevo archivo PDF.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo de entrada. |
| pageNumber | Int32[] | Índice de página fuera del archivo de entrada. |
| outputFile | String | Ruta del archivo de salida. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryExtract es como el método Extract, excepto que el método TryExtract no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

Extrae las páginas especificadas por matriz de números y las guarda como un nuevo archivo PDF.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Archivo de entrada Stream. |
| pageNumber | Int32[] | Índice de página fuera del archivo de entrada. |
| outputStream | Stream | Flujo de archivos de salida. |

### Valor_devuelto

Verdadero para el éxito, o falso.

### Observaciones

El método TryExtract es como el método Extract, excepto que el método TryExtract no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

Extrae las páginas especificadas del archivo de origen y almacena el resultado en el objeto HttpResponse.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de documento de origen. |
| pageNumber | Int32[] | Matriz de números de página que se extraerán. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryExtract es como el método Extract, excepto que el método TryExtract no lanza una excepción si la operación falla.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

Extrae las páginas especificadas del archivo de origen y almacena el resultado en el objeto HttpResponse.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo de origen. |
| pageNumber | Int32[] | Matriz de números de página que se extraerán. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryExtract es como el método Extract, excepto que el método TryExtract no lanza una excepción si la operación falla.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
