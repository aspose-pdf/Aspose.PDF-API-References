---
title: "TextFragmentAbsorber.TextFragments"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà TextFragmentAbsorber. Ottiene la collezione delle occorrenze di ricerca presentate con oggetti TextFragment"
type: docs
weight: 90
url: /it/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments property

Ottiene la collezione delle occorrenze di ricerca presentate con oggetti [`TextFragment`](../../textfragment/).

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## Esempi

L'esempio dimostra come trovare il testo nella prima pagina del documento PDF e sostituire tutte le occorrenze di ricerca con nuovo testo.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Modifica il testo di tutte le occorrenze di ricerca
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi anche

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


