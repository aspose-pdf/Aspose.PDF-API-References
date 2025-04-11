---
title: Font.IsAccessible
second_title: Aspose.PDF for .NET API Reference
description: Proprietà Font. Ottiene l'indicazione se il font è presente installato nel sistema
type: docs
weight: 50
url: /it/net/aspose.pdf.text/font/isaccessible/
---
## Proprietà Font.IsAccessible

Ottiene l'indicazione se il font è presente (installato) nel sistema.

```csharp
public bool IsAccessible { get; }
```

## Osservazioni

Al alcune operazioni non sono disponibili con i font che non possono essere trovati nel sistema.

## Esempi

L'esempio dimostra come cercare testo nella prima pagina e ottenere il valore che indica se il font è installato nel sistema.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### Vedi Anche

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)