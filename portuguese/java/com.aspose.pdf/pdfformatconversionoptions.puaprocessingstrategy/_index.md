---
title: "PdfFormatConversionOptions.PuaProcessingStrategy"
linktitle: "PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Referência da API Aspose.PDF para Java"
description: "Alguns documentos PDF contêm símbolos unicode especiais, que pertencem à Área de Uso Privado (PUA), veja a descrição em https://en.wikipedia.org/wiki/Private_Use_Areas. Esses símbolos."
type: docs
weight: 3750
url: /pt/java/com.aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy

```
public static final class PdfFormatConversionOptions.PuaProcessingStrategy extends com.aspose.ms.System.Enum
```

Alguns documentos PDF contêm símbolos unicode especiais, que pertencem à Área de Uso Privado (PUA); veja a descrição em https://en.wikipedia.org/wiki/Private_Use_Areas. Esses símbolos causam erros de conformidade PDF/A como "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Esta enumeração declara estratégias que podem ser usadas para lidar com símbolos PUA.

## Campos

| Campo | Descrição |
| --- | --- |
| [None](#None) | Desabilita o processamento de símbolos PUA. Essa estratégia é usada por padrão para documentos PDF/A com conformidade de Nível B. |
| [SubstitutePuaSymbols](#SubstitutePuaSymbols) | Essa estratégia funciona mais lentamente que 'SurroundPuaTextWithEmptyActualText', mas pode remover erros de conformidade PUA em documentos que não podem ser tratados adequadamente por SurroundPuaTextWithEmptyActualText. Os símbolos PUA são substituídos pelo símbolo 'espaço' ou por unicode especial (alguns símbolos PUA têm equivalentes unicode). A substituição é aplicada não ao texto do documento, mas aos dados internos da fonte ToUnicode, de modo que não afeta a visualização do símbolo, mas afeta a apresentação do símbolo nas operações de copiar/colar da área de transferência do sistema. |
| [SurroundPuaTextWithEmptyActualText](#SurroundPuaTextWithEmptyActualText) | Insere um bloco de conteúdo marcado com entrada ActualText que contém texto vazio. Essa estratégia oferece bons resultados para documentos sem blocos de conteúdo marcado. É usada por padrão para documentos PDF/A com conformidade de Nível A. |

### None {#None}
```
public static final int None
```

Desabilita o processamento de símbolos PUA. Essa estratégia é usada por padrão para documentos PDF/A com conformidade de Nível B.

### SubstitutePuaSymbols {#SubstitutePuaSymbols}
```
public static final int SubstitutePuaSymbols
```

Essa estratégia funciona mais lentamente que 'SurroundPuaTextWithEmptyActualText', mas pode remover erros de conformidade PUA em documentos que não podem ser tratados adequadamente por SurroundPuaTextWithEmptyActualText. Os símbolos PUA são substituídos pelo símbolo 'espaço' ou por unicode especial (alguns símbolos PUA têm equivalentes unicode). A substituição é aplicada não ao texto do documento, mas aos dados internos da fonte ToUnicode, de modo que não afeta a visualização do símbolo, mas afeta a apresentação do símbolo nas operações de copiar/colar da área de transferência do sistema.

### SurroundPuaTextWithEmptyActualText {#SurroundPuaTextWithEmptyActualText}
```
public static final int SurroundPuaTextWithEmptyActualText
```

Insere um bloco de conteúdo marcado com entrada ActualText que contém texto vazio. Essa estratégia oferece bons resultados para documentos sem blocos de conteúdo marcado. É usada por padrão para documentos PDF/A com conformidade de Nível A.
