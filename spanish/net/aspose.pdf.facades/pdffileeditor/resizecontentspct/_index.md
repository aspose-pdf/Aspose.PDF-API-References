---
title: PdfFileEditor.ResizeContentsPct
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en porcentajes.
type: docs
weight: 330
url: /es/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en porcentajes.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | Stream | Stream que contiene el documento fuente. |
| destination | Stream | Stream donde se guardará el documento resultante. |
| pages | Int32[] | Array de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| newWidth | Double | Nuevo ancho del contenido de la página en porcentajes. |
| newHeight | Double | Nueva altura del contenido de la página en porcentajes. |

### Valor de Retorno

true si se redimensionó con éxito.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### Ver También

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en porcentajes.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | String | Ruta al documento fuente. |
| destination | String | Ruta donde se guardará el documento resultante. |
| pages | Int32[] | Array de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| newWidth | Double | Nuevo ancho del contenido de la página en porcentajes. |
| newHeight | Double | Nueva altura del contenido de la página en porcentajes. |

### Valor de Retorno

true si el redimensionamiento fue exitoso.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### Ver También

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)