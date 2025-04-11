---
title: PdfFileEditor.AddMargins
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileEditor. Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en unidades de espacio predeterminadas.
type: docs
weight: 220
url: /es/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en unidades de espacio predeterminadas.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | Stream | Flujo que contiene el documento fuente. |
| destination | Stream | Flujo donde se guardará el documento resultante. |
| pages | Int32[] | Array de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| leftMargin | Double | Margen izquierdo. |
| rightMargin | Double | Margen derecho. |
| topMargin | Double | Margen superior. |
| bottomMargin | Double | Margen inferior. |

### Valor de Retorno

true si la operación fue exitosa.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
    dest.Close();
```

### Ver También

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en unidades de espacio predeterminadas.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | String | Ruta al documento fuente. |
| destination | String | Ruta donde se guardará el documento resultante. |
| pages | Int32[] | Array de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| leftMargin | Double | Margen izquierdo. |
| rightMargin | Double | Margen derecho. |
| topMargin | Double | Margen superior. |
| bottomMargin | Double | Margen inferior. |

### Valor de Retorno

true si el redimensionamiento fue exitoso.

## Ejemplos

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
```

### Ver También

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)