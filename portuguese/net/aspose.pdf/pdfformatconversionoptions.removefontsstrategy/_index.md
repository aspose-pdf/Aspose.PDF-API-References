---
title: Enum PdfFormatConversionOptions.RemoveFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: Enum PdfFormatConversionOptionsRemoveFontsStrategy do Aspose.Pdf. Alguns documentos têm um tamanho grande após a conversão para o formato PDF/A. Para reduzir o tamanho do arquivo desses documentos, é necessário definir uma estratégia de remoção de fontes. Esta enumeração declara estratégias que podem ser usadas para otimizar o uso de fontes. Cada estratégia desta enumeração faz sentido apenas quando a flag OptimizeFileSize está definida
type: docs
weight: 8400
url: /pt/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## Enumeração PdfFormatConversionOptions.RemoveFontsStrategy

Alguns documentos têm um tamanho grande após a conversão para o formato PDF/A. Para reduzir o tamanho do arquivo desses documentos, é necessário definir uma estratégia de remoção de fontes. Esta enumeração declara estratégias que podem ser usadas para otimizar o uso de fontes. Cada estratégia desta enumeração faz sentido apenas quando a flag [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) está definida.

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | Esta estratégia remove todas as fontes que têm duplicatas no documento. Se o documento contém um grupo de fontes duplicadas, apenas uma fonte desse grupo é incorporada no documento. Todas as outras fontes desse grupo são removidas do documento, cada fonte removida é substituída pela já incorporada. |
| RemoveSimilarFontsWithDifferentWidths | `1` | Esta estratégia é semelhante à RemoveDuplicatedFonts, mas remove não apenas fontes totalmente duplicadas, mas fontes que são semelhantes entre si e diferem apenas pelo parâmetro "Widths". Este parâmetro contém um conjunto de algumas larguras para símbolos específicos da fonte. Cada valor de largura deste conjunto "Widths" não é a largura real do símbolo (glifo), a largura real para este símbolo já está definida nos dados binários da fonte. O valor de largura do conjunto "Widths" significa a largura visual para este símbolo - a largura que o software visualizador de PDF deve definir ao exibir o símbolo em vez da largura real definida na fonte. Mais precisamente, a especificação diz: visualizadores Acrobat 5.0 e posteriores usam as larguras dos glifos armazenadas no dicionário da fonte para substituir as larguras dos glifos no programa da fonte em si, o que melhora a consistência da exibição e impressão do documento. Esta estratégia é mais eficaz do que RemoveDuplicatedFonts, mas o uso desta estratégia em alguns casos poderia teoricamente prejudicar a apresentação visual do documento convertido. Este defeito é possível devido ao fato de que as larguras declaradas das fontes podem ser diferentes para o mesmo símbolo e, nesse caso, a largura desse símbolo será alterada para uma nova após a substituição da fonte - quando a fonte removida for substituída no documento por uma já incorporada. E se a largura visual do símbolo for alterada - ela será exibida incorretamente e essa distinção pode causar defeitos visuais, como sobreposição de texto ou outros problemas. Mas o defeito visual descrito é um caso muito raro e esta estratégia reduz o tamanho do documento de forma mais eficaz. |
| SubsetFonts | `2` | Esta é a estratégia mais eficaz para reduzir o tamanho do documento. Ela pega conjuntos de fontes totalmente incorporadas e os reduz apenas aos subconjuntos usados. É recomendável usar esta estratégia em combinação com RemoveDuplicatedFonts ou RemoveSimilarFontsWithDifferentWidths para obter um efeito de compressão múltipla para o tamanho do arquivo. O uso de todas as três estratégias simultaneamente não faz sentido e a estratégia RemoveSimilarFontsWithDifferentWidths não será usada neste caso. |

### Veja Também

* classe [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)