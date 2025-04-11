---
title: DocSaveOptions.RelativeHorizontalProximity
second_title: Aspose.PDF for .NET API Reference
description: Propriedade DocSaveOptions. Em PDF, as palavras podem ser representadas internamente com operadores que imprimem palavras imprimindo independentemente suas letras ou sílabas. Portanto, para detectar palavras, às vezes precisamos detectar grupos de caracteres independentes que são, de fato, palavras. Esta configuração define a largura do espaço entre elementos de texto (letras, sílabas) que devem ser tratados como distância entre palavras durante o reconhecimento de palavras no PDF de origem. A presença de espaço vazio, pelo menos com essa largura entre letras, significa que os elementos textuais pertencem a palavras diferentes. É normalizado para o tamanho da fonte - 1.0 significa 100% do tamanho da fonte da palavra suposta. ATENÇÃO! É usado apenas em casos em que o PDF de origem contém fontes específicas raramente usadas para as quais o valor ótimo não pode ser calculado a partir da fonte. Portanto, na grande maioria dos casos, este parâmetro não altera nada no documento resultante.
type: docs
weight: 120
url: /pt/net/aspose.pdf/docsaveoptions/relativehorizontalproximity/
---
## Propriedade DocSaveOptions.RelativeHorizontalProximity

Em PDF, as palavras podem ser representadas internamente com operadores que imprimem palavras imprimindo independentemente suas letras ou sílabas. Portanto, para detectar palavras, às vezes precisamos detectar grupos de caracteres independentes que são, de fato, palavras. Esta configuração define a largura do espaço entre elementos de texto (letras, sílabas) que devem ser tratados como distância entre palavras durante o reconhecimento de palavras no PDF de origem. (A presença de espaço vazio, pelo menos com essa largura entre letras, significa que os elementos textuais pertencem a palavras diferentes). É normalizado para o tamanho da fonte - 1.0 significa 100% do tamanho da fonte da palavra suposta. ATENÇÃO! É usado apenas em casos em que o PDF de origem contém fontes específicas raramente usadas para as quais o valor ótimo não pode ser calculado a partir da fonte. Portanto, na grande maioria dos casos, este parâmetro não altera nada no documento resultante.

```csharp
public float RelativeHorizontalProximity { get; set; }
```

### Veja Também

* classe [DocSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)