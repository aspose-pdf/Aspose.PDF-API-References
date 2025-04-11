---
title: PdfFileEditor.Extract
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Extrae páginas de archivos de entrada y las guarda como un nuevo archivo Pdf
type: docs
weight: 280
url: /es/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_2}

Extrae páginas del archivo de entrada, las guarda como un nuevo archivo Pdf.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo Pdf de entrada. |
| startPage | Int32 | Número de la página de inicio. |
| endPage | Int32 | Número de la página final. |
| outputFile | String | Ruta del archivo Pdf de salida. |

### Valor de Retorno

Verdadero si tiene éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_3}

Extrae páginas especificadas por un arreglo de números, las guarda como un nuevo archivo PDF.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Ruta del archivo de entrada. |
| pageNumber | Int32[] | Índice de la página del archivo de entrada. |
| outputFile | String | Ruta del archivo de salida. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Extrae páginas del archivo de entrada, las guarda como un nuevo archivo Pdf.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo del archivo de entrada. |
| startPage | Int32 | Número de la página de inicio. |
| endPage | Int32 | Número de la página final. |
| outputStream | Stream | Flujo del archivo Pdf de salida. |

### Valor de Retorno

Verdadero si tiene éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Extrae páginas especificadas por un arreglo de números, las guarda como un nuevo archivo Pdf.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo del archivo de entrada. |
| pageNumber | Int32[] | Índice de la página del archivo de entrada. |
| outputStream | Stream | Flujo del archivo de salida. |

### Valor de Retorno

Verdadero si tiene éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)