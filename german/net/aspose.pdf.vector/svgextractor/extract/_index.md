---
title: SvgExtractor.Extract
second_title: Aspose.PDF for .NET API Reference
description: SvgExtractor-Methode. Extrahiert SVG-Bild als String aus grafischen Elementen, die durch einen Absorber mit einem Prädikatsfilter dargestellt werden
type: docs
weight: 20
url: /de/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

Extrahiert SVG-Bild als String aus grafischen Elementen, die durch !:absorber mit einem Prädikatsfilter dargestellt werden.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| absorber | GraphicsAbsorber | Das GraphicsAbsorber-Objekt, das die grafischen Elemente enthält. |
| filter | Predicate`1 | Eine Prädikatsfunktion, die verwendet wird, um die grafischen Elemente zu filtern. |
| page | Page | Die Seite, von der der Absorber grafische Elemente erhält. |

### Rückgabewert

Der String mit SVG-Inhalt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Wenn ein Fehler beim Konvertieren in SVG aufgetreten ist. |

### Siehe auch

* Klasse [GraphicsAbsorber](../../graphicsabsorber/)
* Klasse [GraphicElement](../../graphicelement/)
* Klasse [Page](../../../aspose.pdf/page/)
* Klasse [SvgExtractor](../)
* Namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* Assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

Extrahiert SVG-Bild in eine Datei aus grafischen Elementen, die durch !:absorber mit einem Prädikatsfilter dargestellt werden.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| absorber | GraphicsAbsorber | Das GraphicsAbsorber-Objekt, das die grafischen Elemente enthält. |
| filter | Predicate`1 | Eine Prädikatsfunktion, die verwendet wird, um die grafischen Elemente zu filtern. |
| page | Page | Die Seite, von der der Absorber grafische Elemente erhält. |
| svgFilePath | String | Der Ziel-SVG-Dateipfad. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Wenn ein Fehler beim Konvertieren in SVG aufgetreten ist. |

### Siehe auch

* Klasse [GraphicsAbsorber](../../graphicsabsorber/)
* Klasse [GraphicElement](../../graphicelement/)
* Klasse [Page](../../../aspose.pdf/page/)
* Klasse [SvgExtractor](../)
* Namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* Assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

Extrahiert grafische Elemente in einen SVG-String. Optionen ignoriert - Gruppierung, Extrahieren aus Rechteck

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| elements | IEnumerable`1 | Die grafischen Elemente, die konvertiert werden sollen. |
| page | Page | Die Seite, von der der Absorber grafische Elemente erhält. |

### Rückgabewert

Der String mit SVG-Inhalt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Wenn ein Fehler beim Konvertieren in SVG aufgetreten ist. |

### Siehe auch

* Klasse [GraphicElement](../../graphicelement/)
* Klasse [Page](../../../aspose.pdf/page/)
* Klasse [SvgExtractor](../)
* Namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* Assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

Extrahiert grafische Elemente in eine einzelne SVG-Datei. Optionen ignoriert - Gruppierung, Extrahieren aus Rechteck

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| elements | IEnumerable`1 | Die grafischen Elemente, die konvertiert werden sollen. |
| page | Page | Die Seite, von der der Absorber grafische Elemente erhält. |
| svgFilePath | String | Der Ziel-SVG-Dateipfad. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Wenn ein Fehler beim Konvertieren in SVG aufgetreten ist. |

### Siehe auch

* Klasse [GraphicElement](../../graphicelement/)
* Klasse [Page](../../../aspose.pdf/page/)
* Klasse [SvgExtractor](../)
* Namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* Assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

Extrahiert SVG-Bilder von einer Seite in Strings.

```csharp
public List<string> Extract(Page page)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Page | Die Seite, die extrahiert werden soll. |

### Rückgabewert

Die Liste der SVG-Inhaltsstrings.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Wenn ein Fehler beim Konvertieren in SVG aufgetreten ist. |

### Siehe auch

* Klasse [Page](../../../aspose.pdf/page/)
* Klasse [SvgExtractor](../)
* Namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* Assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

Extrahiert SVG-Bilder von einer Seite in Dateien.

```csharp
public void Extract(Page page, string directory)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Page | Die Seite, die extrahiert werden soll. |
| directory | String | Das Zielverzeichnis, in dem SVG-Bilder abgelegt werden sollen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Wenn ein Fehler beim Konvertieren in SVG aufgetreten ist. |

### Siehe auch

* Klasse [Page](../../../aspose.pdf/page/)
* Klasse [SvgExtractor](../)
* Namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* Assembly [Aspose.PDF](../../../)