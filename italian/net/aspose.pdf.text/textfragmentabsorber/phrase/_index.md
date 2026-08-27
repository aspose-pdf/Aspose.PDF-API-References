---
title: "TextFragmentAbsorber.Phrase"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà TextFragmentAbsorber. Ottiene o imposta la frase che il TextFragmentAbsorber ricerca nel documento PDF o nella pagina"
type: docs
weight: 50
url: /it/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase property

Ottiene o imposta la frase che il [`TextFragmentAbsorber`](../) ricerca nel documento PDF o nella pagina.

```csharp
public string Phrase { get; set; }
```

## Esempi

L'esempio dimostra come eseguire più ricerche di testo e effettuare sostituzioni di testo.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un oggetto TextFragmentAbsorber per trovare tutte le occorrenze di testo "hello"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// cerca un'altra parola e sostituiscila
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Salva documento
doc.Save(@"D:\Tests\output.pdf");  
```

### Vedi anche

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


