---
title: Class PdfFormatConversionOptions
second_title: Aspose.PDF for .NET API Reference
description: A classe Aspose.Pdf.PdfFormatConversionOptions representa um conjunto de opções para converter documentos PDF
type: docs
weight: 8380
url: /pt/net/aspose.pdf/pdfformatconversionoptions/
---
## Classe PdfFormatConversionOptions

representa um conjunto de opções para converter documentos PDF

```csharp
public class PdfFormatConversionOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | Construtor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | Construtor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | Construtor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | Construtor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | Construtor |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Construtor |

## Propriedades

| Nome | Descrição |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | Obtém o objeto PdfFormatConversionOptions com parâmetros padrão |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | Esta flag controla o alinhamento do texto no documento convertido. Por padrão, a conversão do documento não afeta o alinhamento do texto e deixa o texto como está. Mas em alguns casos, a substituição de fonte causa sobreposição de texto ou espaços extras no documento convertido. Quando esta flag está ativada, operações de alinhamento especiais serão realizadas. Esta flag deve ser definida apenas para documentos que têm problemas com texto sobreposto ou espaços extras de texto, pois o uso desta flag diminui o desempenho e, em alguns casos, pode corromper o conteúdo do texto. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | Ação para imagens com máscara suave. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | Ação para objetos que não podem ser convertidos |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | Estratégia(s) para excluir fontes supérfluas e reduzir o tamanho do arquivo do documento. Este parâmetro faz sentido apenas quando a flag [`OptimizeFileSize`](./optimizefilesize/) está definida como verdadeira. Por padrão, uma combinação das estratégias SubsetFonts e RemoveDuplicatedFonts é usada. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | Opções para casos em que não é possível incorporar algumas fontes no documento PDF. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | Formato PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | Obtém ou define o nome do arquivo do perfil icc. No caso de nulo, o perfil icc padrão é usado. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | Obtém/define a execução de fluxos de imagem em modo assíncrono. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | O modo de conversão de baixa memória está ativado |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | Obtém ou define se os dados de Info devem ser passados para Metadata ao serem convertidos para PDF 2.0. Verdadeiro por padrão. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | Caminho para o arquivo onde os comentários serão armazenados. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | Fluxo onde os comentários serão armazenados. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | Contém flags para controlar o processo de conversão PDF/A para casos em que o documento de origem não corresponde à especificação PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | Esta propriedade é uma propriedade externa. Ela contém todas as fontes (nomes de fontes) que não foram encontradas no computador na última conversão PDF/A. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | Obtém ou define uma flag que habilita/desabilita um modo de conversão especial para obter um documento PDF/A com tamanho de arquivo reduzido. Agora, esta flag impacta na otimização das fontes usadas no documento PDF; possivelmente, no futuro, esta flag também será usada para ativar a otimização de outras estruturas de dados, como gráficos. O conjunto desta flag e modo pode reduzir significativamente o tamanho do arquivo, mas ao mesmo tempo pode diminuir significativamente o desempenho da conversão. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | Obtém ou define o [`OutputIntent`](../outputintent/) para a conversão do formato PDF. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Estratégia para processar símbolos da Área de Uso Privado (PUA) do unicode. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | Estratégia para copiar dados de codificação para fontes simbólicas se a fonte TrueType simbólica tiver mais de uma sub-tabela de codificação. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | Ação para objetos de imagem mascarados |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Regras para resolver problemas com mapeamento unicode. Pode ser nulo. |

## Campos

| Nome | Descrição |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | Estratégia para alinhar texto. Este parâmetro faz sentido apenas quando a flag [`AlignText`](./aligntext/) está definida como verdadeira. |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)