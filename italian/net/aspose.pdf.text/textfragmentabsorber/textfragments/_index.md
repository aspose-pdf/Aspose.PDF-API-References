---
title: TextFragments
second_title: Aspose.PDF per .NET API Reference
description: Ottiene la raccolta di occorrenze di ricerca presentateTextFragmentaspose.pdf.text/textfragment oggetti.
type: docs
weight: 80
url: /it/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments property

Ottiene la raccolta di occorrenze di ricerca presentate[`TextFragment`](../../textfragment) oggetti.

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

### Esempi

L'esempio mostra come trovare del testo nella prima pagina del documento PDF e sostituire tutte le occorrenze di ricerca con un nuovo testo.

```csharp
// Modifica il testo e il carattere della prima occorrenza del testo
Document doc = new Document(@"D:\Tests\input.pdf");

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Modifica il testo e il carattere della prima occorrenza del testo
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
doc.Pages[1].Accept(absorber);

// Apri documento
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Trova il carattere che verrà utilizzato per modificare il carattere del testo del documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Guarda anche

* class [TextFragmentCollection](../../textfragmentcollection)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* spazio dei nomi [Aspose.Pdf.Text](../../textfragmentabsorber)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->