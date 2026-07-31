---
title: "Font.IsAccessible"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà Font. Ottiene un valore che indica se il carattere è presente installato nel sistema"
type: docs
weight: 50
url: /it/net/aspose.pdf.text/font/isaccessible/
---
## Font.IsAccessible property

Restituisce un'indicazione se il font è presente (installato) nel sistema.

```csharp
public bool IsAccessible { get; }
```

## Osservazioni

Alcune operazioni non sono disponibili con i caratteri che non possono essere trovati nel sistema.

## Esempi

L'esempio dimostra come cercare testo nella prima pagina e ottenere il valore che indica se il carattere è installato nel sistema.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Visualizza il valore IsSubset del carattere della prima occorrenza di testo
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### Vedi anche

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


