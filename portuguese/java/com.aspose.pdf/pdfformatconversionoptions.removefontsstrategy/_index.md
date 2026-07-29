---
title: "PdfFormatConversionOptions.RemoveFontsStrategy"
linktitle: "PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Referência da API Aspose.PDF para Java"
description: "Alguns documentos têm tamanho grande após a conversão para o formato PDF/A. Para reduzir o tamanho de arquivo desses documentos, é necessário definir uma estratégia de remoção de fontes. Esta enumeração."
type: docs
weight: 3760
url: /pt/java/com.aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy

```
public static class PdfFormatConversionOptions.RemoveFontsStrategy extends com.aspose.ms.System.Enum
```

Alguns documentos têm tamanho grande após a conversão para o formato PDF/A. Para reduzir o tamanho do arquivo desses documentos, é necessário definir uma estratégia de remoção de fontes. Esta enumeração declara estratégias que podem ser usadas para otimizar o uso de fontes. Cada estratégia desta enumeração só faz sentido quando a flag {@code OptimizeFileSize} está definida.

## Campos

| Campo | Descrição |
| --- | --- |
| [RemoveDuplicatedFonts](#RemoveDuplicatedFonts) | Esta estratégia remove todas as fontes que têm duplicatas no documento. Se o documento contiver um grupo de fontes duplicadas, apenas uma fonte desse grupo será incorporada ao documento. Todas as demais fontes desse grupo são removidas do documento, e cada fonte removida é substituída pelo análogo já incorporado. |
| [RemoveSimilarFontsWithDifferentWidths](#RemoveSimilarFontsWithDifferentWidths) | Esta estratégia se assemelha a {@code RemoveDuplicatedFonts}, mas remove não fontes totalmente duplicadas, e sim fontes que são semelhantes entre si e diferem apenas pelo parâmetro \"Widths\". Esse parâmetro contém um conjunto de larguras para símbolos específicos da fonte. Cada valor de largura desse conjunto \"Widths\" não é a largura real do símbolo (glifo); a largura real do símbolo já está definida nos dados binários da fonte. O valor de largura do conjunto \"Widths\" representa a largura visual desse símbolo – a largura que o software visualizador de PDF deve usar ao exibir o símbolo, em vez da largura real definida na fonte. Mais precisamente, a especificação indica: visualizadores Acrobat 5.0 e posteriores utilizam as larguras de glifos armazenadas no dicionário da fonte para sobrescrever as larguras dos glifos no próprio programa da fonte, o que melhora a consistência da exibição e impressão do documento. Esta estratégia é mais eficaz que {@code RemoveDuplicatedFonts}, porém o uso desta estratégia em alguns casos pode teoricamente danificar a apresentação visual do documento convertido. Esse defeito é possível porque as larguras declaradas das fontes podem ser diferentes para o mesmo símbolo e, nesse caso, a largura desse símbolo será alterada para uma nova após a substituição da fonte – quando a fonte removida for substituída no documento por uma já incorporada. E se a largura visual do símbolo for alterada, ele será exibido incorretamente, podendo causar defeitos visuais como sobreposição de texto ou outros problemas. Contudo, o defeito visual descrito é muito raro e esta estratégia reduz o tamanho do documento de forma mais eficaz. |
| [SubsetFonts](#SubsetFonts) | Esta é a estratégia mais eficaz para reduzir o tamanho do documento. Ela utiliza conjuntos de fontes totalmente incorporados e os reduz apenas aos subconjuntos usados. Recomenda‑se usar esta estratégia em combinação com {@code RemoveDuplicatedFonts} ou {@code RemoveSimilarFontsWithDifferentWidths} para obter múltiplos efeitos de compressão no tamanho do arquivo. O uso simultâneo das três estratégias não faz sentido e a estratégia {@code RemoveSimilarFontsWithDifferentWidths} não será utilizada neste caso. |

### RemoveDuplicatedFonts {#RemoveDuplicatedFonts}
```
public static final byte RemoveDuplicatedFonts
```

Esta estratégia remove todas as fontes que têm duplicatas no documento. Se o documento contiver um grupo de fontes duplicadas, apenas uma fonte desse grupo será incorporada ao documento. Todas as demais fontes desse grupo são removidas do documento, e cada fonte removida é substituída pelo análogo já incorporado.

### RemoveSimilarFontsWithDifferentWidths {#RemoveSimilarFontsWithDifferentWidths}
```
public static final byte RemoveSimilarFontsWithDifferentWidths
```

Esta estratégia se assemelha a {@code RemoveDuplicatedFonts}, mas remove não fontes totalmente duplicadas, e sim fontes que são semelhantes entre si e diferem apenas pelo parâmetro \"Widths\". Esse parâmetro contém um conjunto de larguras para símbolos específicos da fonte. Cada valor de largura desse conjunto \"Widths\" não é a largura real do símbolo (glifo); a largura real do símbolo já está definida nos dados binários da fonte. O valor de largura do conjunto \"Widths\" representa a largura visual desse símbolo – a largura que o software visualizador de PDF deve usar ao exibir o símbolo, em vez da largura real definida na fonte. Mais precisamente, a especificação indica: visualizadores Acrobat 5.0 e posteriores utilizam as larguras de glifos armazenadas no dicionário da fonte para sobrescrever as larguras dos glifos no próprio programa da fonte, o que melhora a consistência da exibição e impressão do documento. Esta estratégia é mais eficaz que {@code RemoveDuplicatedFonts}, porém o uso desta estratégia em alguns casos pode teoricamente danificar a apresentação visual do documento convertido. Esse defeito é possível porque as larguras declaradas das fontes podem ser diferentes para o mesmo símbolo e, nesse caso, a largura desse símbolo será alterada para uma nova após a substituição da fonte – quando a fonte removida for substituída no documento por uma já incorporada. E se a largura visual do símbolo for alterada, ele será exibido incorretamente, podendo causar defeitos visuais como sobreposição de texto ou outros problemas. Contudo, o defeito visual descrito é muito raro e esta estratégia reduz o tamanho do documento de forma mais eficaz.

### SubsetFonts {#SubsetFonts}
```
public static final byte SubsetFonts
```

Esta é a estratégia mais eficaz para reduzir o tamanho do documento. Ela utiliza conjuntos de fontes totalmente incorporados e os reduz apenas aos subconjuntos usados. Recomenda‑se usar esta estratégia em combinação com {@code RemoveDuplicatedFonts} ou {@code RemoveSimilarFontsWithDifferentWidths} para obter múltiplos efeitos de compressão no tamanho do arquivo. O uso simultâneo das três estratégias não faz sentido e a estratégia {@code RemoveSimilarFontsWithDifferentWidths} não será utilizada neste caso.
