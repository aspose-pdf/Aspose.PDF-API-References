---
title: Append
second_title: Referencia de API de Aspose.PDF para .NET
description: Agrega páginas que se eligen de una matriz de documentos en portStreams. El documento de resultado incluye firstInputFile y todas las páginas de documentos de portStreams en el rango startPage a endPage.
type: docs
weight: 280
url: /es/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

Agrega páginas, que se eligen de una matriz de documentos en portStreams. El documento de resultado incluye firstInputFile y todas las páginas de documentos de portStreams en el rango startPage a endPage.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de PDF de entrada. |
| portStreams | Stream[] | Documentos de los que copiar páginas. |
| startPage | Int32 | La página comienza en los documentos de portStreams. |
| endPage | Int32 | La página termina en documentos portStreams. |
| outputStream | Stream | Flujo de PDF de salida. |

### Valor_devuelto

Verdadero para el éxito, o falso.

### Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_4}

Agrega páginas, que se eligen de los documentos portFiles. El documento de resultados incluye firstInputFile y todas las páginas de documentos portFiles en el rango startPage a endPage.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Archivo PDF de entrada. |
| portFiles | String[] | Documentos de los que copiar páginas. |
| startPage | Int32 | La página comienza en los documentos portFiles. |
| endPage | Int32 | La página termina en documentos portFiles. |
| outputFile | String | Documento PDF de salida. |

### Valor_devuelto

Verdadero si la operación se realizó correctamente.

### Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_3}

Agrega páginas, que se eligen de portFile dentro del rango de startPage a endPage, en portFile al final de firstInputFile.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Archivo PDF de entrada. |
| portFile | String | Páginas del archivo Pdf. |
| startPage | Int32 | La página comienza en portFile. |
| endPage | Int32 | La página termina en portFile. |
| outputFile | String | Documento PDF de salida. |

### Valor_devuelto

Verdadero si la operación se realizó correctamente.

### Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

Agrega páginas, que se eligen de portStream dentro del rango de startPage a endPage, en portStream al final de firstInputStream.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Archivo de entrada Stream. |
| portStream | Stream | Páginas del archivo Pdf Stream. |
| startPage | Int32 | La página comienza en portFile Stream. |
| endPage | Int32 | La página termina en portFile Stream. |
| outputStream | Stream | Archivo PDF de salida Stream. |

### Valor_devuelto

Verdadero para el éxito, o falso.

### Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Append(Stream, Stream[], int, int, HttpResponse) {#append_2}

Agrega documentos al documento de origen y guarda el resultado en el objeto de respuesta.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputStream | Stream | Secuencia que contiene el documento de origen. |
| portStreams | Stream[] | Matriz de secuencias con documentos que se adjuntarán. |
| startPage | Int32 | Página de inicio de la página adjunta. |
| endPage | Int32 | Página final de las páginas anexas. |
| response | HttpResponse | Objeto de respuesta donde se guardará el documento. |

### Valor_devuelto

verdadero si la operación fue exitosa.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, HttpResponse) {#append_5}

Agrega documentos al documento de origen y guarda el resultado en el objeto HttpResponse.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| inputFile | String | Nombre del archivo que contiene el documento de origen. |
| portFiles | String[] | Matriz de nombres de archivos que contienen documentos adjuntos. |
| startPage | Int32 | Página de inicio de las páginas anexas. |
| endPage | Int32 | Página final de las páginas anexas. |
| response | HttpResponse | Objeto de respuesta donde se guardará el documento. |

### Valor_devuelto

verdadero si la operación se realizó correctamente.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
