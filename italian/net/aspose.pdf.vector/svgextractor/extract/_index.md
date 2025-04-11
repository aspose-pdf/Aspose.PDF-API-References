---
title: SvgExtractor.Extract
second_title: Aspose.PDF for .NET API Reference
description: Metodo SvgExtractor. Estrae l'immagine svg in stringa dagli elementi grafici rappresentati da absorber con un filtro predicato
type: docs
weight: 20
url: /it/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

Estrae l'immagine svg in stringa dagli elementi grafici rappresentati da !:absorber con un filtro predicato.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| absorber | GraphicsAbsorber | L'oggetto GraphicsAbsorber che contiene gli elementi grafici. |
| filter | Predicate`1 | Una funzione predicato utilizzata per filtrare gli elementi grafici. |
| page | Page | La pagina da cui l'absorber ottiene gli elementi grafici. |

### Valore di Ritorno

La stringa con il contenuto SVG.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Se si è verificato un errore durante la conversione in SVG. |

### Vedi Anche

* classe [GraphicsAbsorber](../../graphicsabsorber/)
* classe [GraphicElement](../../graphicelement/)
* classe [Page](../../../aspose.pdf/page/)
* classe [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

Estrae l'immagine svg in un file dagli elementi grafici rappresentati da !:absorber con un filtro predicato.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| absorber | GraphicsAbsorber | L'oggetto GraphicsAbsorber che contiene gli elementi grafici. |
| filter | Predicate`1 | Una funzione predicato utilizzata per filtrare gli elementi grafici. |
| page | Page | La pagina da cui l'absorber ottiene gli elementi grafici. |
| svgFilePath | String | Il percorso del file SVG di destinazione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Se si è verificato un errore durante la conversione in SVG. |

### Vedi Anche

* classe [GraphicsAbsorber](../../graphicsabsorber/)
* classe [GraphicElement](../../graphicelement/)
* classe [Page](../../../aspose.pdf/page/)
* classe [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

Estrae gli elementi grafici in una stringa SVG. Opzioni ignorate - raggruppamento, estrazione da rettangolo

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elements | IEnumerable`1 | Gli elementi grafici da convertire. |
| page | Page | La pagina da cui l'absorber ottiene gli elementi grafici. |

### Valore di Ritorno

La stringa con il contenuto SVG.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Se si è verificato un errore durante la conversione in SVG. |

### Vedi Anche

* classe [GraphicElement](../../graphicelement/)
* classe [Page](../../../aspose.pdf/page/)
* classe [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

Estrae gli elementi grafici in un singolo file SVG. Opzioni ignorate - raggruppamento, estrazione da rettangolo

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elements | IEnumerable`1 | Gli elementi grafici da convertire. |
| page | Page | La pagina da cui l'absorber ottiene gli elementi grafici. |
| svgFilePath | String | Il percorso del file SVG di destinazione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Se si è verificato un errore durante la conversione in SVG. |

### Vedi Anche

* classe [GraphicElement](../../graphicelement/)
* classe [Page](../../../aspose.pdf/page/)
* classe [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

Estrae immagini Svg da una pagina a stringhe.

```csharp
public List<string> Extract(Page page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Page | La pagina da estrarre. |

### Valore di Ritorno

L'elenco delle stringhe di contenuto SVG.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Se si è verificato un errore durante la conversione in SVG. |

### Vedi Anche

* classe [Page](../../../aspose.pdf/page/)
* classe [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

Estrae immagini Svg da una pagina a file.

```csharp
public void Extract(Page page, string directory)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Page | La pagina da estrarre. |
| directory | String | La directory di destinazione per posizionare le immagini SVG. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Se si è verificato un errore durante la conversione in SVG. |

### Vedi Anche

* classe [Page](../../../aspose.pdf/page/)
* classe [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)