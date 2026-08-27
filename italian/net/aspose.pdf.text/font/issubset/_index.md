---
title: "Font.IsSubset"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà Font. Ottiene o imposta un valore che indica se il carattere è un subset. Font basato su IFont verrà automaticamente sottoposto a subset e incorporato"
type: docs
weight: 70
url: /it/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset property

Restituisce o imposta un valore che indica se il font è un subset. Un font basato su IFont verrà automaticamente sottoposto a subset e incorporato.

```csharp
public bool IsSubset { get; set; }
```

## Esempi

L'esempio dimostra come cercare testo nella prima pagina e ottenere il valore che indica se il carattere è un subset.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Visualizza il valore IsSubset del carattere della prima occorrenza di testo
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### Vedi anche

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


