---
title: Font.FontName
second_title: Aspose.PDF for .NET API Reference
description: Proprietà Font. Ottiene il nome del font dell'oggetto Font
type: docs
weight: 30
url: /it/net/aspose.pdf.text/font/fontname/
---
## Proprietà Font.FontName

Ottiene il nome del font dell'oggetto [`Font`](../).

```csharp
public string FontName { get; }
```

## Esempi

L'esempio dimostra come cercare testo nella prima pagina e visualizzare il nome del font della prima occorrenza di testo.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font name of first text occurrence
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### Vedi Anche

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)