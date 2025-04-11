---
title: PdfFileEditor.AddMarginsPct
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Redimensiona el contenido de la página y añade márgenes especificados. Los márgenes se especifican en porcentajes del tamaño inicial de la página.
type: docs
weight: 230
url: /es/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Redimensiona el contenido de la página y añade márgenes especificados. Los márgenes se especifican en porcentajes del tamaño inicial de la página.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | Stream | Flujo que contiene el documento fuente. |
| destination | Stream | Flujo donde se guardará el documento resultante. |
| pages | Int32[] | Array de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| leftMargin | Double | Margen izquierdo en porcentajes del tamaño inicial de la página. |
| rightMargin | Double | Margen derecho en porcentajes del tamaño inicial de la página. |
| topMargin | Double | Margen superior en porcentajes del tamaño inicial de la página. |
| bottomMargin | Double | Margen inferior en porcentajes del tamaño inicial de la página. |

### Valor de Retorno

true si la acción se realizó con éxito.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
    dest.Close();
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Redimensiona el contenido de la página y añade márgenes especificados. Los márgenes se especifican en porcentajes del tamaño inicial de la página.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | String | Ruta al documento fuente. |
| destination | String | Ruta donde se guardará el documento resultante. |
| pages | Int32[] | Array de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| leftMargin | Double | Margen izquierdo en porcentajes del tamaño inicial de la página. |
| rightMargin | Double | Margen derecho en porcentajes del tamaño inicial de la página. |
| topMargin | Double | Margen superior en porcentajes del tamaño inicial de la página. |
| bottomMargin | Double | Margen inferior en porcentajes del tamaño inicial de la página. |

### Valor de Retorno

true si el redimensionamiento fue exitoso.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
```

### Ver También

* clase [PdfFileEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)