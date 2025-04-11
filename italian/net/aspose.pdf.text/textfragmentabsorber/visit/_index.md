---
title: TextFragmentAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Metodo TextFragmentAbsorber. Esegue la ricerca nella pagina specificata
type: docs
weight: 150
url: /it/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

Esegue la ricerca nella pagina specificata.

```csharp
public override void Visit(Page page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Page | Oggetto pagina del documento PDF. |

## Esempi

L'esempio dimostra come trovare testo nella prima pagina del documento PDF e sostituire il testo.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi Anche

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Esegue la ricerca nel documento specificato.

```csharp
public override void Visit(Document pdf)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdf | Document | Oggetto documento PDF. |

## Esempi

L'esempio dimostra come trovare testo nel documento PDF e sostituire il testo di tutte le occorrenze di ricerca.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi Anche

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Esegue la ricerca nell'oggetto modulo specificato.

```csharp
public void Visit(XForm xForm)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xForm | XForm | Oggetto modulo Pdf. |

### Vedi Anche

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)