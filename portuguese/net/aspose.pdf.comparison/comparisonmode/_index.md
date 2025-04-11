---
title: Enum ComparisonMode
second_title: Aspose.PDF for .NET API Reference
description: Enumeração Aspose.Pdf.Comparison.ComparisonMode. A enumeração do modo de comparação
type: docs
weight: 3140
url: /pt/net/aspose.pdf.comparison/comparisonmode/
---
## Enumeração ComparisonMode

A enumeração do modo de comparação.

```csharp
public enum ComparisonMode
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Normal | `0` | Modo normal. Apenas espaços dentro de fragmentos de texto são levados em conta (dependendo da forma como o documento é gerado.) |
| IgnoreSpaces | `1` | Todos os espaços são ignorados. As mudanças são buscadas apenas em palavras. |
| ParseSpaces | `2` | O modo é semelhante ao normal, mas tenta levar em conta o espaçamento visual entre fragmentos de texto com base na distância. Reconhecer o número de espaços entre fragmentos pode não ser preciso, pois isso depende muito de como os documentos são gerados. Se os documentos forem criados por geradores diferentes, pode haver imprecisões na comparação de espaços entre fragmentos de texto. |

### Veja Também

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)