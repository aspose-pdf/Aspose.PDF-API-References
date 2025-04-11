---
title: TextFragment.TextState
second_title: Aspose.PDF for .NET API Reference
description: Propriedade TextFragment. Obtém ou define o estado do texto para o texto que o objeto TextFragment representa
type: docs
weight: 150
url: /pt/net/aspose.pdf.text/textfragment/textstate/
---
## Propriedade TextFragment.TextState

Obtém ou define o estado do texto para o texto que o objeto [`TextFragment`](../) representa.

```csharp
public TextFragmentState TextState { get; }
```

## Observações

Fornece uma maneira de alterar as seguintes propriedades do texto: Fonte Tamanho da Fonte Estilo da Fonte Cor do Primeiro Plano Cor de Fundo

## Exemplos

O exemplo demonstra como alterar a cor do texto e o tamanho da fonte do texto com o objeto `TextState`.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Veja Também

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [TextFragmentState](../../textfragmentstate/)
* classe [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)