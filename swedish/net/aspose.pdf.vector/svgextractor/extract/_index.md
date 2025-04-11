---
title: SvgExtractor.Extract
second_title: Aspose.PDF for .NET API Reference
description: SvgExtractor-metod. Extraherar svg-bild till sträng från grafiska element representerade av absorber med en predikatfilter
type: docs
weight: 20
url: /sv/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

Extraherar svg-bild till sträng från grafiska element representerade av !:absorber med en predikatfilter.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absorber | GraphicsAbsorber | GraphicsAbsorber-objektet som innehåller de grafiska elementen. |
| filter | Predicate`1 | En predikatfunktion som används för att filtrera de grafiska elementen. |
| page | Page | Den sida där absorber får grafiska element. |

### Return Value

Strängen med SVG-innehåll.

### Exceptions

| undantag | villkor |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Om ett fel inträffade vid konvertering till SVG. |

### Se Även

* klass [GraphicsAbsorber](../../graphicsabsorber/)
* klass [GraphicElement](../../graphicelement/)
* klass [Page](../../../aspose.pdf/page/)
* klass [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

Extraherar svg-bild till fil från grafiska element representerade av !:absorber med en predikatfilter.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absorber | GraphicsAbsorber | GraphicsAbsorber-objektet som innehåller de grafiska elementen. |
| filter | Predicate`1 | En predikatfunktion som används för att filtrera de grafiska elementen. |
| page | Page | Den sida där absorber får grafiska element. |
| svgFilePath | Sträng | Den mål-SVG-filvägen. |

### Exceptions

| undantag | villkor |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Om ett fel inträffade vid konvertering till SVG. |

### Se Även

* klass [GraphicsAbsorber](../../graphicsabsorber/)
* klass [GraphicElement](../../graphicelement/)
* klass [Page](../../../aspose.pdf/page/)
* klass [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

Extraherar grafiska element till en SVG-sträng. Alternativ ignoreras - gruppering, extrahera från rektangel

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| elements | IEnumerable`1 | De grafiska elementen som ska konverteras. |
| page | Page | Den sida där absorber får grafiska element. |

### Return Value

Strängen med SVG-innehåll.

### Exceptions

| undantag | villkor |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Om ett fel inträffade vid konvertering till SVG. |

### Se Även

* klass [GraphicElement](../../graphicelement/)
* klass [Page](../../../aspose.pdf/page/)
* klass [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

Extraherar grafiska element till en enda SVG-fil. Alternativ ignoreras - gruppering, extrahera från rektangel

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| elements | IEnumerable`1 | De grafiska elementen som ska konverteras. |
| page | Page | Den sida där absorber får grafiska element. |
| svgFilePath | Sträng | Den mål-SVG-filvägen. |

### Exceptions

| undantag | villkor |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Om ett fel inträffade vid konvertering till SVG. |

### Se Även

* klass [GraphicElement](../../graphicelement/)
* klass [Page](../../../aspose.pdf/page/)
* klass [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

Extraherar Svg-bilder från en sida till strängar.

```csharp
public List<string> Extract(Page page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Page | Den sida som ska extraheras. |

### Return Value

Listan med SVG-innehållssträngar.

### Exceptions

| undantag | villkor |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Om ett fel inträffade vid konvertering till SVG. |

### Se Även

* klass [Page](../../../aspose.pdf/page/)
* klass [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

Extraherar Svg-bilder från en sida till filer.

```csharp
public void Extract(Page page, string directory)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Page | Den sida som ska extraheras. |
| directory | Sträng | Den mål-mapp där SVG-bilder ska placeras. |

### Exceptions

| undantag | villkor |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Om ett fel inträffade vid konvertering till SVG. |

### Se Även

* klass [Page](../../../aspose.pdf/page/)
* klass [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)