---
title: PdfFileEditor.Concatenate
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Concatena dos archivos
type: docs
weight: 260
url: /es/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_4}

Concatena dos archivos.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputFile | String | Primer archivo a concatenar. |
| secInputFile | String | Segundo archivo a concatenar. |
| outputFile | String | Archivo de salida. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

Concatena dos archivos.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputStream | Stream | Flujo del primer archivo. |
| secInputStream | Stream | Flujo del segundo archivo. |
| outputStream | Stream | Flujo donde se almacenará el archivo resultante. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

Concatena documentos.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | Document[] | Array de documentos fuente. |
| dest | Document | Documento de destino. |

### Valor de Retorno

Verdadero si la concatenación es exitosa.

### Ver También

* clase [Document](../../../aspose.pdf/document/)
* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_6}

Concatena archivos en un solo archivo.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFiles | String[] | Array de archivos a concatenar. |
| outputFile | String | Nombre del archivo de salida. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

Concatena archivos

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream[] | Array de flujos a ser concatenados. |
| outputStream | Stream | Flujo donde se almacenará el archivo resultante. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_5}

Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de manera alterna y llena los espacios en blanco con páginas en blanco. por ejemplo: el documento1 tiene 5 páginas: p1, p2, p3, p4, p5. el documento2 tiene 3 páginas: p1', p2', p3'. Fusionar los dos documentos Pdf producirá el documento resultante con páginas: p1, p1', p2, p2', p3, p3', p4, página en blanco, p5, página en blanco.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputFile | String | Primer archivo. |
| secInputFile | String | Segundo archivo. |
| blankPageFile | String | Archivo PDF con página en blanco. |
| outputFile | String | Archivo resultante. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de manera alterna y llena los espacios en blanco con páginas en blanco. por ejemplo: el documento1 tiene 5 páginas: p1, p2, p3, p4, p5. el documento2 tiene 3 páginas: p1', p2', p3'. Fusionar los dos documentos Pdf producirá el documento resultante con páginas: p1, p1', p2, p2', p3, p3', p4, página en blanco, p5, página en blanco.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputStream | Stream | El primer flujo Pdf. |
| secInputStream | Stream | El segundo flujo Pdf. |
| blankPageStream | Stream | El flujo Pdf con página en blanco. |
| outputStream | Stream | Flujo Pdf de salida. |

### Valor de Retorno

Verdadero si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)


## Concatenate(string[], HttpResponse) {#concatenate_8}

Concatena archivos y guarda el resultado en el objeto HttpResponse.

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFiles | String[] | Array de archivos a concatenar. |
| response | HttpResponse | Objeto de respuesta. |

### Valor de Retorno

verdadero si la concatenación fue exitosa.

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Concatenate(Stream[], HttpResponse) {#concatenate_4}

Concatena archivos y almacena el resultado en el objeto HttpResponse.

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream[] | Array de flujos que contienen archivos a concatenar. |
| response | HttpResponse | Objeto de respuesta. |

### Valor de Retorno

verdadero si la operación fue exitosa.

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)