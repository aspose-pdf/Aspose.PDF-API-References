---
title: Extract
second_title: Referencia de API de Aspose.PDF para .NET
description: Extrae páginas del archivo de entrada las guarda como un nuevo archivo PDF.
type: docs
weight: 310
url: /es/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_3}

Extrae páginas del archivo de entrada, las guarda como un nuevo archivo PDF.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Introduzca la ruta del archivo PDF. |
| startPage | Int32 | Número de página de inicio. |
| endPage | Int32 | Número de página final. |
| outputFile | String | Ruta del archivo PDF de salida. |

### Valor_devuelto

Verdadero para el éxito, o falso.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_4}

Extrae las páginas especificadas por matriz de números y las guarda como un nuevo archivo PDF.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo de entrada. |
| pageNumber | Int32[] | Índice de página fuera del archivo de entrada. |
| outputFile | String | Ruta del archivo de salida. |

### Valor_devuelto

Verdadero si la operación se realizó correctamente.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Extrae páginas del archivo de entrada, las guarda como un nuevo archivo PDF.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Archivo de entrada Stream. |
| startPage | Int32 | Número de página de inicio. |
| endPage | Int32 | Número de página final. |
| outputStream | Stream | Archivo PDF de salida Stream. |

### Valor_devuelto

Verdadero para el éxito, o falso.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Extrae las páginas especificadas por matriz de números y las guarda como un nuevo archivo PDF.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Archivo de entrada Stream. |
| pageNumber | Int32[] | Índice de página fuera del archivo de entrada. |
| outputStream | Stream | Flujo de archivos de salida. |

### Valor_devuelto

Verdadero para el éxito, o falso.

### Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Extract(Stream, int[], HttpResponse) {#extract_2}

Extrae las páginas especificadas del archivo de origen y almacena el resultado en el objeto HttpResponse.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de documento de origen. |
| pageNumber | Int32[] | Matriz de números de página que se extraerán. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor_devuelto

Verdadero si la operación se realizó correctamente.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Extract(string, int[], HttpResponse) {#extract_5}

Extrae las páginas especificadas del archivo de origen y almacena el resultado en el objeto HttpResponse.

```csharp
public bool Extract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo de origen. |
| pageNumber | Int32[] | Matriz de números de página que se extraerán. |
| response | HttpResponse | Objeto HttpResponse donde se almacenará el resultado. |

### Valor_devuelto

true si las páginas se extrajeron correctamente.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
