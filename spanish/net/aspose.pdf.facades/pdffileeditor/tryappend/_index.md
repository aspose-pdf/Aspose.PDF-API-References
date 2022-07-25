---
title: TryAppend
second_title: Referencia de API de Aspose.PDF para .NET
description: Agrega páginas que se eligen de una matriz de documentos en portStreams. El documento de resultado incluye firstInputFile y todas las páginas de documentos de portStreams en el rango startPage a endPage.
type: docs
weight: 410
url: /es/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Agrega páginas, que se eligen de una matriz de documentos en portStreams. El documento de resultado incluye firstInputFile y todas las páginas de documentos de portStreams en el rango startPage a endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

### Observaciones

El método TryAppend es como el método Append, excepto que el método TryAppend no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_2}

Agrega páginas, que se eligen de los documentos portFiles. El documento de resultados incluye firstInputFile y todas las páginas de documentos portFiles en el rango startPage a endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
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

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryAppend es como el método Append, excepto que el método TryAppend no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

Agrega documentos al documento de origen y guarda el resultado en el objeto de respuesta.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryAppend es como el método Append, excepto que el método TryAppend no lanza una excepción si la operación falla.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

Agrega documentos al documento de origen y guarda el resultado en el objeto HttpResponse.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
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

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryAppend es como el método Append, excepto que el método TryAppend no lanza una excepción si la operación falla.

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
