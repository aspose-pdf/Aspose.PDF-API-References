---
title: SvgExtractor.Extract
second_title: Aspose.PDF for .NET API Reference
description: Método SvgExtractor. Extrae la imagen svg a una cadena de elementos gráficos representados por el absorbedor con un filtro de predicado
type: docs
weight: 20
url: /es/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

Extrae la imagen svg a una cadena de elementos gráficos representados por !:absorber con un filtro de predicado.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absorber | GraphicsAbsorber | El objeto GraphicsAbsorber que contiene los elementos gráficos. |
| filter | Predicate`1 | Una función de predicado utilizada para filtrar los elementos gráficos. |
| page | Page | La página donde el absorbedor obtiene los elementos gráficos. |

### Valor de Retorno

La cadena con el contenido SVG.

### Excepciones

| excepción | condición |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Si ocurrió un error al convertir a SVG. |

### Ver También

* clase [GraphicsAbsorber](../../graphicsabsorber/)
* clase [GraphicElement](../../graphicelement/)
* clase [Page](../../../aspose.pdf/page/)
* clase [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

Extrae la imagen svg a un archivo de elementos gráficos representados por !:absorber con un filtro de predicado.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| absorber | GraphicsAbsorber | El objeto GraphicsAbsorber que contiene los elementos gráficos. |
| filter | Predicate`1 | Una función de predicado utilizada para filtrar los elementos gráficos. |
| page | Page | La página donde el absorbedor obtiene los elementos gráficos. |
| svgFilePath | String | La ruta del archivo SVG de destino. |

### Excepciones

| excepción | condición |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Si ocurrió un error al convertir a SVG. |

### Ver También

* clase [GraphicsAbsorber](../../graphicsabsorber/)
* clase [GraphicElement](../../graphicelement/)
* clase [Page](../../../aspose.pdf/page/)
* clase [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

Extrae elementos gráficos en una cadena SVG. Opciones ignoradas - agrupación, extracción de rectángulo

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elements | IEnumerable`1 | Los elementos gráficos a convertir. |
| page | Page | La página donde el absorbedor obtiene los elementos gráficos. |

### Valor de Retorno

La cadena con el contenido SVG.

### Excepciones

| excepción | condición |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Si ocurrió un error al convertir a SVG. |

### Ver También

* clase [GraphicElement](../../graphicelement/)
* clase [Page](../../../aspose.pdf/page/)
* clase [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

Extrae elementos gráficos en un solo archivo SVG. Opciones ignoradas - agrupación, extracción de rectángulo

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| elements | IEnumerable`1 | Los elementos gráficos a convertir. |
| page | Page | La página donde el absorbedor obtiene los elementos gráficos. |
| svgFilePath | String | La ruta del archivo SVG de destino. |

### Excepciones

| excepción | condición |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Si ocurrió un error al convertir a SVG. |

### Ver También

* clase [GraphicElement](../../graphicelement/)
* clase [Page](../../../aspose.pdf/page/)
* clase [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

Extrae imágenes Svg de una página a cadenas.

```csharp
public List<string> Extract(Page page)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Page | La página a extraer. |

### Valor de Retorno

La lista de cadenas de contenido SVG.

### Excepciones

| excepción | condición |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Si ocurrió un error al convertir a SVG. |

### Ver También

* clase [Page](../../../aspose.pdf/page/)
* clase [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

Extrae imágenes Svg de una página a archivos.

```csharp
public void Extract(Page page, string directory)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Page | La página a extraer. |
| directory | String | El directorio de destino para colocar las imágenes SVG. |

### Excepciones

| excepción | condición |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Si ocurrió un error al convertir a SVG. |

### Ver También

* clase [Page](../../../aspose.pdf/page/)
* clase [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)