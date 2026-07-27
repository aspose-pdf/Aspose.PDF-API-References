---
title: "HtmlSaveOptions.AntialiasingProcessingType"
linktitle: "HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Referência da API Aspose.PDF para Java"
description: "Este enum descreve as possíveis medidas de antialiasing durante a conversão"
type: docs
weight: 2000
url: /pt/java/com.aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType

```
public static final class HtmlSaveOptions.AntialiasingProcessingType extends com.aspose.ms.System.Enum
```

Este enum descreve as possíveis medidas de antialiasing durante a conversão

## Campos

| Campo | Descrição |
| --- | --- |
| [NoAdditionalProcessing](#NoAdditionalProcessing) | Nenhum processamento especial de antialiasing em uso. Esta é uma opção ideal para a grande maioria dos documentos e não requer tempo adicional durante a conversão. |
| [TryCorrectResultHtml](#TryCorrectResultHtml) | Nesse caso, o conversor tenta detectar áreas com elementos gráficos de fundo adjacentes e corrigir o HTML resultante de forma adequada. Esta opção permite melhorar o resultado da exportação para documentos que contêm fundos compostos por vários elementos gráficos adjacentes (para esse tipo de documento, os renderizadores PDF, por exemplo o Acrobat Reader, geralmente tentam suavizar as bordas dos elementos durante a renderização). Com esta opção, o conversor imita esse comportamento dos renderizadores PDF. Esta opção permite melhorar o layout do resultado da exportação para alguns documentos específicos (que utilizam fundos compostos), mas requer tempo adicional para o processamento (geralmente cerca de 10-15% de tempo extra). Portanto, o uso deste modo no caso geral não é recomendado. |

### NoAdditionalProcessing {#NoAdditionalProcessing}
```
public static final int NoAdditionalProcessing
```

Nenhum processamento especial de antialiasing em uso. Esta é uma opção ideal para a grande maioria dos documentos e não requer tempo adicional durante a conversão.

### TryCorrectResultHtml {#TryCorrectResultHtml}
```
public static final int TryCorrectResultHtml
```

Nesse caso, o conversor tenta detectar áreas com elementos gráficos de fundo adjacentes e corrigir o HTML resultante de forma adequada. Esta opção permite melhorar o resultado da exportação para documentos que contêm fundos compostos por vários elementos gráficos adjacentes (para esse tipo de documento, os renderizadores PDF, por exemplo o Acrobat Reader, geralmente tentam suavizar as bordas dos elementos durante a renderização). Com esta opção, o conversor imita esse comportamento dos renderizadores PDF. Esta opção permite melhorar o layout do resultado da exportação para alguns documentos específicos (que utilizam fundos compostos), mas requer tempo adicional para o processamento (geralmente cerca de 10-15% de tempo extra). Portanto, o uso deste modo no caso geral não é recomendado.
