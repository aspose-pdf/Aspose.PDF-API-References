---
title: "TextAbsorber.Visit"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo TextAbsorber. Estrae il testo nella pagina specificata."
type: docs
weight: 70
url: /it/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

Estrae il testo dalla pagina specificata

```csharp
public virtual void Visit(Page page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | Page | Oggetto pagina PDF. |

## Esempi

L'esempio dimostra come estrarre testo nella prima pagina del documento PDF.

```csharp
// apri documento
Document doc = new Document(inFile);

// crea un oggetto TextAbsorber per estrarre testo
TextAbsorber absorber = new TextAbsorber();

// accetta l'assorbitore per tutte le pagine del documento
absorber.Visit(doc.Pages[1]);

// ottieni il testo estratto
string extractedText = absorber.Text;
```

### Vedi anche

* class [Page](../../../aspose.pdf/page/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Estrae il testo sull'XForm specificato.

```csharp
public virtual void Visit(XForm form)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| modulo | XForm | Oggetto modulo Pdf. |

## Esempi

L'esempio dimostra come estrarre testo nella prima pagina del documento PDF.

```csharp
// apri documento
Document doc = new Document(inFile);

// crea un oggetto TextAbsorber per estrarre testo
TextAbsorber absorber = new TextAbsorber();

// accetta l'assorbitore per tutte le pagine del documento
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// ottieni il testo estratto
string extractedText = absorber.Text;
```

### Vedi anche

* class [XForm](../../../aspose.pdf/xform/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Estrae il testo dal documento specificato

```csharp
public virtual void Visit(Document pdf)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdf | Document | Oggetto Pdf pocument. |

## Esempi

L'esempio dimostra come estrarre il testo su un documento PDF.

```csharp
// apri documento
Document doc = new Document(inFile);

// crea un oggetto TextAbsorber per estrarre testo
TextAbsorber absorber = new TextAbsorber();

// accetta l'assorbitore per tutte le pagine del documento
absorber.Visit(doc);

// ottieni il testo estratto
string extractedText = absorber.Text;
```

### Vedi anche

* class [Document](../../../aspose.pdf/document/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


