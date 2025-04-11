---
title: PdfFileEditor.TryResizeContents
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Redimensiona el contenido de las páginas del documento
type: docs
weight: 450
url: /es/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Redimensiona el contenido de las páginas en el documento. Si la página se reduce, se añaden márgenes en blanco alrededor de la página. El resultado se almacena en el objeto HttpResponse.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | String | Ruta al archivo fuente. |
| pages | Int32[] | Array de páginas a redimensionar. |
| parameters | ContentsResizeParameters | Parámetros de redimensionamiento. |
| response | HttpResponse | Objeto HttpResponse donde se guarda el resultado. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Comentarios

El método TryResizeContents es similar al método ResizeContents, excepto que el método TryResizeContents no lanza una excepción si la operación falla.

### Ver También

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Redimensiona el contenido de las páginas en el documento. Si la página se reduce, se añaden márgenes en blanco alrededor de la página. El resultado se almacena en el objeto HttpResponse.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | Stream | Flujo del archivo fuente. |
| pages | Int32[] | Array de páginas a redimensionar. |
| parameters | ContentsResizeParameters | Parámetros de redimensionamiento. |
| response | HttpResponse | Objeto HttpResponse donde se guarda el resultado. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Comentarios

El método TryResizeContents es similar al método ResizeContents, excepto que el método TryResizeContents no lanza una excepción si la operación falla.

### Ver También

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

Redimensiona el contenido de las páginas del documento.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | Stream | Flujo con el documento fuente. |
| destination | Stream | Flujo con el documento de destino. |
| pages | Int32[] | Array de índices de página. |
| parameters | ContentsResizeParameters | Parámetros de redimensionamiento. |

### Valor de Retorno

Devuelve true si tiene éxito.

## Comentarios

El método TryResizeContents es similar al método ResizeContents, excepto que el método TryResizeContents no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Ver También

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y añade márgenes. El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | Stream | Flujo que contiene el documento fuente. |
| destination | Stream | Flujo donde se guardará el documento resultante. |
| pages | Int32[] | Array de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| newWidth | Double | Nuevo ancho del contenido de la página en unidades de espacio predeterminadas. |
| newHeight | Double | Nueva altura del contenido de la página en unidades de espacio predeterminadas. |

### Valor de Retorno

true si la operación se completó con éxito; de lo contrario, false.

## Comentarios

El método TryResizeContents es similar al método ResizeContents, excepto que el método TryResizeContents no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### Ver También

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Redimensiona el contenido de las páginas en el documento. Si la página se reduce, se añaden márgenes en blanco alrededor de la página.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | String | Ruta del documento fuente. |
| destination | String | Ruta del documento de destino. |
| pages | Int32[] | Array de índices de página (el índice de página comienza desde 1). |
| parameters | ContentsResizeParameters | Parámetros de redimensionamiento de la página. |

### Valor de Retorno

true si la redimensión fue exitosa.

## Comentarios

El método TryResizeContents es similar al método ResizeContents, excepto que el método TryResizeContents no lanza una excepción si la operación falla.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Ver También

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)