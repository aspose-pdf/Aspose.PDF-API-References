---
title: "TextFragment.Text"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà TextFragment. Ottiene o imposta l'oggetto String che il TextFragment rappresenta."
type: docs
weight: 130
url: /it/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text property

Ottiene o imposta l'oggetto String che l'oggetto [`TextFragment`](../) rappresenta.

```csharp
public string Text { get; set; }
```

## Esempi

L'esempio dimostra come cercare un testo e sostituire la prima occorrenza rappresentata con l'oggetto [`TextFragment`](../).

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Cambia il font della prima occorrenza di testo
absorber.TextFragments[1].Text = "hi world";

// Salva documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Vedi anche

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


