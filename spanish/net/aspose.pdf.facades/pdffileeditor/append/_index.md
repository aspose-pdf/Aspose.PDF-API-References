---
title: PdfFileEditor.Append
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Agrega páginas que se eligen de un array de documentos en portStreams. El documento resultante incluye firstInputFile y todas las páginas de los documentos de portStreams en el rango de startPage a endPage
type: docs
weight: 250
url: /es/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Agrega páginas, que se eligen de un array de documentos en portStreams. El documento resultante incluye firstInputFile y todas las páginas de los documentos de portStreams en el rango de startPage a endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo Pdf de entrada. |
| portStreams | Stream[] | Documentos de los cuales copiar páginas. |
| startPage | Int32 | La página comienza en los documentos de portStreams. |
| endPage | Int32 | La página termina en los documentos de portStreams. |
| outputStream | Stream | Flujo Pdf de salida. |

### Valor de Retorno

Verdadero para éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

Agrega páginas, que se eligen de los documentos portFiles. El documento resultante incluye firstInputFile y todas las páginas de los documentos portFiles en el rango de startPage a endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Archivo Pdf de entrada. |
| portFiles | String[] | Documentos de los cuales copiar páginas. |
| startPage | Int32 | La página comienza en los documentos portFiles. |
| endPage | Int32 | La página termina en los documentos portFiles. |
| outputFile | String | Documento Pdf de salida. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

Agrega páginas, que se eligen de portFile dentro del rango de startPage a endPage, en portFile al final de firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Archivo Pdf de entrada. |
| portFile | String | Páginas del archivo Pdf. |
| startPage | Int32 | La página comienza en portFile. |
| endPage | Int32 | La página termina en portFile. |
| outputFile | String | Documento Pdf de salida. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

Agrega páginas, que se eligen de portStream dentro del rango de startPage a endPage, en portStream al final de firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de archivo de entrada. |
| portStream | Stream | Páginas del flujo de archivo Pdf. |
| startPage | Int32 | La página comienza en el flujo de portFile. |
| endPage | Int32 | La página termina en el flujo de portFile. |
| outputStream | Stream | Flujo de archivo Pdf de salida. |

### Valor de Retorno

Verdadero para éxito, o falso.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)