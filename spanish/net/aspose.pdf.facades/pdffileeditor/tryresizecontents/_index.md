---
title: TryResizeContents
second_title: Referencia de API de Aspose.PDF para .NET
description: Cambia el tamaño del contenido de las páginas del documento. Si la página se reduce se agregan márgenes en blanco alrededor de la página. El resultado se almacena en el objeto HttpResponse.
type: docs
weight: 480
url: /es/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents_3}

Cambia el tamaño del contenido de las páginas del documento. Si la página se reduce, se agregan márgenes en blanco alrededor de la página. El resultado se almacena en el objeto HttpResponse.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| source | String | Ruta al archivo fuente. |
| pages | Int32[] | Matriz de páginas a redimensionar. |
| parameters | ContentsResizeParameters | Cambiar el tamaño de los parámetros. |
| response | HttpResponse | Objeto HttpResponse donde se guarda el resultado. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryResizeContents es como el método ResizeContents, excepto que el método TryResizeContents no lanza una excepción si la operación falla.

### Ver también

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Cambia el tamaño del contenido de las páginas del documento. Si la página se reduce, se agregan márgenes en blanco alrededor de la página. El resultado se almacena en el objeto HttpResponse.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| source | Stream | Flujo de archivo fuente. |
| pages | Int32[] | Matriz de páginas a redimensionar. |
| parameters | ContentsResizeParameters | Cambiar el tamaño de los parámetros. |
| response | HttpResponse | Objeto HttpResponse donde se guarda el resultado. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryResizeContents es como el método ResizeContents, excepto que el método TryResizeContents no lanza una excepción si la operación falla.

### Ver también

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

Cambia el tamaño del contenido de las páginas del documento.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| source | Stream | Transmitir con el documento de origen. |
| destination | Stream | Transmitir con el documento de destino. |
| pages | Int32[] | Matriz de índices de página. |
| parameters | ContentsResizeParameters | Cambiar el tamaño de los parámetros. |

### Valor_devuelto

Devuelve verdadero si tiene éxito.

### Observaciones

El método TryResizeContents es como el método ResizeContents, excepto que el método TryResizeContents no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //margen izquierdo = 10% del ancho de la página
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //ancho del nuevo contenido calculado automáticamente como ancho - margen izquierdo - margen derecho (100% - 10% - 10% = 80%)
    null,
    //el margen derecho es el 10% de la página 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //margen superior = 10% de la altura
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //la altura del nuevo contenido se calcula automáticamente (similar al ancho)
    null,
    //el margen inferior es 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Ver también

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_2}

Cambia el tamaño del contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| source | Stream | Secuencia que contiene el documento de origen. |
| destination | Stream | Secuencia donde se guardará el documento resultante. |
| pages | Int32[] | Matriz de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| newWidth | Double | Nuevo ancho del contenido de la página en unidades de espacio predeterminadas. |
| newHeight | Double | Nueva altura del contenido de la página en unidades de espacio predeterminadas. |

### Valor_devuelto

verdadero si la operación se completó con éxito; en caso contrario, falso.

### Observaciones

El método TryResizeContents es como el método ResizeContents, excepto que el método TryResizeContents no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//cambiar el tamaño de todas las páginas del documento
null, 
//ancho del nuevo contenido = 200
200, 
// altura del nuevo contenido = 300
300);
// el área de descanso de la página estará vacía
```

### Ver también

* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_4}

Cambia el tamaño del contenido de las páginas del documento. Si la página se reduce, se agregan márgenes en blanco alrededor de la página.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| source | String | Ruta del documento de origen. |
| destination | String | Ruta del documento de destino. |
| pages | Int32[] | Matriz de índices de página (el índice de página comienza desde 1). |
| parameters | ContentsResizeParameters | Parámetros de cambio de tamaño de página. |

### Valor_devuelto

verdadero si el cambio de tamaño fue exitoso.

### Observaciones

El método TryResizeContents es como el método ResizeContents, excepto que el método TryResizeContents no lanza una excepción si la operación falla.

### Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //margen izquierdo = 10% del ancho de la página
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //ancho del nuevo contenido calculado automáticamente como ancho - margen izquierdo - margen derecho (100% - 10% - 10% = 80%)
    null,
    //el margen derecho es el 10% de la página 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //margen superior = 10% de la altura
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //la altura del nuevo contenido se calcula automáticamente (similar al ancho)
    null,
    //el margen inferior es 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Ver también

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffileeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
