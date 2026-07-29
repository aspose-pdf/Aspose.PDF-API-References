---
title: "ComparisonMode"
linktitle: "ComparisonMode"
second_title: "Referência da API Aspose.PDF para Java"
description: "A enumeração de modo de comparação."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf.comparison.sidebysidecomparison/comparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.Enum, com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode

```
public final class ComparisonMode extends com.aspose.ms.System.Enum
```

A enumeração de modo de comparação.

## Campos

| Campo | Descrição |
| --- | --- |
| [IgnoreSpaces](#IgnoreSpaces) | Todos os espaços são ignorados. As alterações são procuradas apenas nas palavras. |
| [Normal](#Normal) | Modo normal. Apenas os espaços dentro de fragmentos de texto são considerados (dependendo da forma como o documento é gerado.) |
| [ParseSpaces](#ParseSpaces) | O modo é semelhante ao normal, mas tenta levar em conta o espaçamento visual entre fragmentos de texto com base na distância. Reconhecer o número de espaços entre os fragmentos pode não ser preciso, pois isso depende muito de como os documentos são gerados. Se os documentos forem criados por geradores diferentes, podem ocorrer imprecisões ao comparar os espaços entre fragmentos de texto. Esta opção pode produzir resultados que, embora lógicos, diferem dos resultados de comparação esperados quando aplicados a documentos com estrutura complexa. |

### IgnoreSpaces {#IgnoreSpaces}
```
public static final int IgnoreSpaces
```

Todos os espaços são ignorados. As alterações são procuradas apenas nas palavras.

### Normal {#Normal}
```
public static final int Normal
```

Modo normal. Apenas os espaços dentro de fragmentos de texto são considerados (dependendo da forma como o documento é gerado.)

### ParseSpaces {#ParseSpaces}
```
public static final int ParseSpaces
```

O modo é semelhante ao normal, mas tenta levar em conta o espaçamento visual entre fragmentos de texto com base na distância. Reconhecer o número de espaços entre os fragmentos pode não ser preciso, pois isso depende muito de como os documentos são gerados. Se os documentos forem criados por geradores diferentes, podem ocorrer imprecisões ao comparar os espaços entre fragmentos de texto. Esta opção pode produzir resultados que, embora lógicos, diferem dos resultados de comparação esperados quando aplicados a documentos com estrutura complexa.
