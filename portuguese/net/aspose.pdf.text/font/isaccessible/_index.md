---
title: Font.IsAccessible
second_title: Aspose.PDF for .NET API Reference
description: Propriedade Font. Obtém indicando se a fonte está instalada no sistema
type: docs
weight: 50
url: /pt/net/aspose.pdf.text/font/isaccessible/
---
## Propriedade Font.IsAccessible

Obtém indicando se a fonte está presente (instalada) no sistema.

```csharp
public bool IsAccessible { get; }
```

## Observações

Algumas operações não estão disponíveis com fontes que não puderam ser encontradas no sistema.

## Exemplos

O exemplo demonstra como pesquisar texto na primeira página e obter o valor que indica se a fonte está instalada no sistema.

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

### Veja Também

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)