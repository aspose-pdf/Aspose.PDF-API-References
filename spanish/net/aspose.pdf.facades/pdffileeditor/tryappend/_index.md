---
title: PdfFileEditor.TryAppend
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Agrega páginas que se eligen de un array de documentos en portStreams. El documento resultante incluye firstInputFile y todas las páginas de los documentos de portStreams en el rango de startPage a endPage
type: docs
weight: 380
url: /es/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Agrega páginas, que se eligen de un array de documentos en portStreams. El documento resultante incluye firstInputFile y todas las páginas de los documentos de portStreams en el rango de startPage a endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo Pdf de entrada. |
| portStreams | Stream[] | Documentos de los que copiar páginas. |
| startPage | Int32 | La página comienza en los documentos de portStreams. |
| endPage | Int32 | La página termina en los documentos de portStreams. |
| outputStream | Stream | Flujo Pdf de salida. |

### Valor de Retorno

Verdadero si tiene éxito, o falso.

## Observaciones

El método TryAppend es como el método Append, excepto que el método TryAppend no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

Agrega páginas, que se eligen de los documentos portFiles. El documento resultante incluye firstInputFile y todas las páginas de los documentos portFiles en el rango de startPage a endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Archivo Pdf de entrada. |
| portFiles | String[] | Documentos de los que copiar páginas. |
| startPage | Int32 | La página comienza en los documentos portFiles. |
| endPage | Int32 | La página termina en los documentos portFiles. |
| outputFile | String | Documento Pdf de salida. |

### Valor de Retorno

verdadero si la operación se completó con éxito; de lo contrario, falso.

## Observaciones

El método TryAppend es como el método Append, excepto que el método TryAppend no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)


## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

Agrega documentos al documento fuente y guarda el resultado en el objeto de respuesta.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo que contiene el documento fuente. |
| portStreams | Stream[] | Array de flujos con documentos a ser agregados. |
| startPage | Int32 | Página de inicio de la página agregada. |
| endPage | Int32 | Página final de las páginas agregadas. |
| response | HttpResponse | Objeto de respuesta donde se guardará el documento. |

### Valor de Retorno

verdadero si la operación se completó con éxito; de lo contrario, falso.

## Observaciones

El método TryAppend es como el método Append, excepto que el método TryAppend no lanza una excepción si la operación falla.

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

Agrega documentos al documento fuente y guarda el resultado en el objeto HttpResponse.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Nombre del archivo que contiene el documento fuente. |
| portFiles | String[] | Array de nombres de archivos que contienen documentos agregados. |
| startPage | Int32 | Página de inicio de las páginas agregadas. |
| endPage | Int32 | Página final de las páginas agregadas. |
| response | HttpResponse | Objeto de respuesta donde se guardará el documento. |

### Valor de Retorno

verdadero si la operación se completó con éxito; de lo contrario, falso.

## Observaciones

El método TryAppend es como el método Append, excepto que el método TryAppend no lanza una excepción si la operación falla.

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)