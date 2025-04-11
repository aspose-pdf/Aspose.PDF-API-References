---
title: Font.IsSubset
second_title: Aspose.PDF for .NET API Reference
description: Proprietà Font. Ottiene o imposta un valore che indica se il font è un sottoinsieme. I font basati su IFont saranno automaticamente sottoinsieme e incorporati
type: docs
weight: 70
url: /it/net/aspose.pdf.text/font/issubset/
---
## Proprietà Font.IsSubset

Ottiene o imposta un valore che indica se il font è un sottoinsieme. I font basati su IFont saranno automaticamente sottoinsieme e incorporati

```csharp
public bool IsSubset { get; set; }
```

## Esempi

L'esempio dimostra come cercare testo nella prima pagina e ottenere il valore che indica se il font è un sottoinsieme.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### Vedi Anche

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)