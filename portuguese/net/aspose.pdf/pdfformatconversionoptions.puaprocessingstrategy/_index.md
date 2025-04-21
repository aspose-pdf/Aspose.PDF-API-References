---
title: Enum PdfFormatConversionOptions.PuaProcessingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy. Alguns documentos PDF têm símbolos unicode especiais que pertencem à Área de Uso Privado - PUA, veja a descrição em https//en.wikipedia.org/wiki/Private_Use_Areas. Esses símbolos causam erros de conformidade PDF/A, como "O texto está mapeado para a Área de Uso Privado Unicode, mas nenhuma entrada ActualText está presente". Esta enumeração declara estratégias que podem ser usadas para lidar com símbolos PUA.
type: docs
weight: 8390
url: /pt/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## Enumeração PdfFormatConversionOptions.PuaProcessingStrategy

Alguns documentos PDF têm símbolos unicode especiais, que pertencem à Área de Uso Privado (PUA), veja a descrição em https://en.wikipedia.org/wiki/Private_Use_Areas. Esses símbolos causam erros de conformidade PDF/A, como "O texto está mapeado para a Área de Uso Privado Unicode, mas nenhuma entrada ActualText está presente". Esta enumeração declara estratégias que podem ser usadas para lidar com símbolos PUA.

```csharp
public enum PuaProcessingStrategy
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | `0` | Desabilitar o processamento de símbolos PUA. Esta estratégia é usada por padrão para documentos PDF/A com conformidade de Nível B. |
| SurroundPuaTextWithEmptyActualText | `1` | Insere um bloco de conteúdo marcado com uma entrada ActualText que contém texto vazio. Esta estratégia oferece bons resultados para documentos sem blocos de conteúdo marcados. Usada por padrão para documentos PDF/A com conformidade de Nível A. |
| SubstitutePuaSymbols | `2` | Esta estratégia funciona mais lentamente do que 'SurroundPuaTextWithEmptyActualText', mas pode remover erros de conformidade PUA para documentos que não podem ser tratados adequadamente por SurroundPuaTextWithEmptyActualText. Os símbolos PUA são substituídos pelo símbolo 'espaço' ou unicode especial (alguns símbolos PUA têm análogos unicode). A substituição é aplicada não ao texto do documento, mas aos dados internos da fonte ToUnicode, portanto, não afeta a visão do símbolo, mas afeta a apresentação do símbolo na operação de copiar/colar do sistema. |

### Veja Também

* classe [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)