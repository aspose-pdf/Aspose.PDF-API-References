---
title: PdfFileEditor.TryConcatenate
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Concatena dos archivos
type: docs
weight: 390
url: /es/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_3}

Concatena dos archivos.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputFile | String | Primer archivo a concatenar. |
| secInputFile | String | Segundo archivo a concatenar. |
| outputFile | String | Archivo de salida. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryConcatenate es como el método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

Concatena documentos.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | Document[] | Array de documentos fuente. |
| dest | Document | Documento de destino. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryConcatenate es como el método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.

### Véase También

* clase [Document](../../../aspose.pdf/document/)
* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

Concatena archivos en un solo archivo.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFiles | String[] | Array de archivos a concatenar. |
| outputFile | String | Nombre del archivo de salida. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryConcatenate es como el método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

Concatena archivos

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream[] | Array de flujos a concatenar. |
| outputStream | Stream | Flujo donde se almacenará el archivo resultante. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryConcatenate es como el método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de manera alterna y llena los espacios en blanco con páginas en blanco. p.ej.: el documento1 tiene 5 páginas: p1, p2, p3, p4, p5. el documento2 tiene 3 páginas: p1', p2', p3'. Fusionar los dos documentos Pdf producirá el documento resultante con páginas: p1, p1', p2, p2', p3, p3', p4, página en blanco, p5, página en blanco.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputFile | String | Primer archivo. |
| secInputFile | String | Segundo archivo. |
| blankPageFile | String | Archivo PDF con página en blanco. |
| outputFile | String | Archivo resultante. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryConcatenate es como el método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

Fusiona dos documentos Pdf en un nuevo documento Pdf con páginas de manera alterna y llena los espacios en blanco con páginas en blanco. p.ej.: el documento1 tiene 5 páginas: p1, p2, p3, p4, p5. el documento2 tiene 3 páginas: p1', p2', p3'. Fusionar los dos documentos Pdf producirá el documento resultante con páginas: p1, p1', p2, p2', p3, p3', p4, página en blanco, p5, página en blanco.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstInputStream | Stream | El primer flujo Pdf. |
| secInputStream | Stream | El segundo flujo Pdf. |
| blankPageStream | Stream | El flujo Pdf con página en blanco. |
| outputStream | Stream | Flujo Pdf de salida. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryConcatenate es como el método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)


## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

Concatena archivos y guarda el resultado en el objeto HttpResponse.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFiles | String[] | Array de archivos a concatenar. |
| response | HttpResponse | Objeto de respuesta. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryConcatenate es como el método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

Concatena archivos y almacena el resultado en el objeto HttpResponse.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream[] | Array de flujos que contienen archivos a concatenar. |
| response | HttpResponse | Objeto de respuesta. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Observaciones

El método TryConcatenate es como el método Concatenate, excepto que el método TryConcatenate no lanza una excepción si la operación falla.

### Véase También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)