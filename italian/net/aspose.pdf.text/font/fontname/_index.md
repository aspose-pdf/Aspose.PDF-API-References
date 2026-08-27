---
title: "Font.FontName"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà Font. Ottiene il nome del carattere dell'oggetto Font"
type: docs
weight: 30
url: /it/net/aspose.pdf.text/font/fontname/
---
## Font.FontName property

Ottiene il nome del carattere dell'oggetto [`Font`](../).

```csharp
public string FontName { get; }
```

## Esempi

L'esempio dimostra come cercare testo nella prima pagina e visualizzare il nome del carattere della prima occorrenza di testo.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Visualizza il nome del carattere della prima occorrenza di testo
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### Vedi anche

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


