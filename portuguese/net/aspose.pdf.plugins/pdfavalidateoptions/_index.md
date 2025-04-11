---
title: Class PdfAValidateOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.PdfAValidateOptions. Representa opções para validar a conformidade PDF/A de documentos PDF com o plugin PdfAConverter
type: docs
weight: 9030
url: /pt/net/aspose.pdf.plugins/pdfavalidateoptions/
---
## Classe PdfAValidateOptions

Representa opções para validar a conformidade PDF/A de documentos PDF com o [`PdfAConverter`](../pdfaconverter/) plugin.

```csharp
public sealed class PdfAValidateOptions : PdfAOptionsBase
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfAValidateOptions](pdfavalidateoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | Obtém ou define um valor indicando se meios adicionais são necessários para preservar o alinhamento do texto durante o processo de conversão PDF/A. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Obtém ou define a ação a ser tomada para objetos que não podem ser convertidos. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | Obtém ou define a estratégia para remover fontes para minimizar o tamanho do arquivo de saída durante o processo de conversão PDF/A. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Obtém as opções para processar fontes que não podem ser incorporadas ao documento. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | Obtém ou define o nome do arquivo do perfil ICC (International Color Consortium) a ser usado para a conversão PDF/A em vez do padrão. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Obtém a coleção de fontes de dados |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | Obtém ou define um valor indicando se o modo de baixa memória está habilitado durante o processo de conversão PDF/A. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Obtém ou define a fonte de dados para a saída do log. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Obtém as flags que controlam a conversão PDF/A para casos em que o documento PDF de origem não corresponde à especificação PDF. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | Obtém ou define um valor indicando se deve tentar reduzir o tamanho do arquivo durante o processo de conversão PDF/A. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Obtém ou define a versão do padrão PDF/A a ser usada para validação ou conversão. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Obtém ou define a estratégia para processar símbolos da Área de Uso Privado (PUA) no documento PDF. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Obtém ou define a ação a ser tomada durante a conversão de imagens com máscaras suaves. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Obtém ou define a estratégia para codificação de fontes simbólicas ao converter para o formato PDF/A. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Obtém ou define as regras para processar tabelas CMap ToUnicode e não vinculadas a símbolos Unicode durante o processo de conversão PDF/A. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Adiciona nova fonte de dados à coleção |

### Veja Também

* classe [PdfAOptionsBase](../pdfaoptionsbase/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)