---
title: "SvgExtractor.Extract"
second_title: "Aspose.PDF för .NET API‑referens"
description: "SvgExtractor-metod. Extraherar SVG-bild till en sträng från grafiska element som representeras av absorber med ett predikatfilter"
type: docs
weight: 20
url: /sv/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

Extraherar svg‑bild till sträng från grafikelement som representeras av !:absorber med ett predikatfilter.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absorber | GraphicsAbsorber | GraphicsAbsorber-objektet som innehåller de grafiska elementen. |
| filter | Predicate`1 | En predikatfunktion som används för att filtrera de grafiska elementen. |
| sida | Page | Sidan där absorberen hämtar grafiska element. |

### Returvärde

Strängen med SVG-innehåll.

### Undantag

| undantag | villkor |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Om ett fel uppstod vid konvertering till SVG. |

### Se även

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

Extraherar svg‑bild till fil från grafikelement som representeras av !:absorber med ett predikatfilter.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absorber | GraphicsAbsorber | GraphicsAbsorber-objektet som innehåller de grafiska elementen. |
| filter | Predicate`1 | En predikatfunktion som används för att filtrera de grafiska elementen. |
| sida | Page | Sidan där absorberen hämtar grafiska element. |
| svgFilePath | String | Målsökvägen för SVG-filen. |

### Undantag

| undantag | villkor |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Om ett fel uppstod vid konvertering till SVG. |

### Se även

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

Extraherar grafikelement till en SVG‑sträng. Alternativ ignoreras – gruppering, extrahering från rektangel.

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | IEnumerable`1 | De grafiska elementen att konvertera. |
| sida | Page | Sidan där absorberen hämtar grafiska element. |

### Returvärde

Strängen med SVG-innehåll.

### Undantag

| undantag | villkor |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Om ett fel uppstod vid konvertering till SVG. |

### Se även

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

Extraherar grafikelement till en enda SVG‑fil. Alternativ ignoreras – gruppering, extrahering från rektangel.

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | IEnumerable`1 | De grafiska elementen att konvertera. |
| sida | Page | Sidan där absorberen hämtar grafiska element. |
| svgFilePath | String | Målsökvägen för SVG-filen. |

### Undantag

| undantag | villkor |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Om ett fel uppstod vid konvertering till SVG. |

### Se även

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

Extraherar Svg‑bilder från en sida till strängar.

```csharp
public List<string> Extract(Page page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Page | Sidan att extrahera. |

### Returvärde

Listan med SVG-innehållssträngar.

### Undantag

| undantag | villkor |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Om ett fel uppstod vid konvertering till SVG. |

### Se även

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

Extraherar Svg‑bilder från en sida till filer.

```csharp
public void Extract(Page page, string directory)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Page | Sidan att extrahera. |
| katalog | String | Målkatalogen för att placera SVG-bilder. |

### Undantag

| undantag | villkor |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Om ett fel uppstod vid konvertering till SVG. |

### Se även

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


