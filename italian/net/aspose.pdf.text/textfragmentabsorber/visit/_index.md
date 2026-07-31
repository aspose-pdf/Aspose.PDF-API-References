---
title: "TextFragmentAbsorber.Visit"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo TextFragmentAbsorber. Esegue la ricerca nella pagina specificata"
type: docs
weight: 150
url: /it/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

Esegue la ricerca sulla pagina specificata.

```csharp
public override void Visit(Page page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | Page | Oggetto pagina del documento PDF. |

## Esempi

L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire il testo.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
absorber.Visit(doc.Pages[1]);

// Modifica il testo di tutte le occorrenze di ricerca
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi anche

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Esegue la ricerca sul documento specificato.

```csharp
public override void Visit(Document pdf)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdf | Document | Oggetto documento PDF. |

## Esempi

L'esempio dimostra come trovare il testo in un documento PDF e sostituire il testo di tutte le occorrenze di ricerca.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
absorber.Visit(doc);

// Modifica il testo della prima occorrenza di testo
absorber.TextFragments[1].Text = "hi world";

// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi anche

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Esegue la ricerca sull'oggetto form specificato.

```csharp
public void Visit(XForm xForm)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xForm | XForm | Oggetto modulo Pdf. |

### Vedi anche

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


