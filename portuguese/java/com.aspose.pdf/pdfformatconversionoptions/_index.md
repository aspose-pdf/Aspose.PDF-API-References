---
title: "PdfFormatConversionOptions"
linktitle: "PdfFormatConversionOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "representa um conjunto de opções para converter documento PDF."
type: docs
weight: 3730
url: /pt/java/com.aspose.pdf/pdfformatconversionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions

```
public class PdfFormatConversionOptions extends Object
```

representa um conjunto de opções para converter documento PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Construtor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-) | Construtor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Construtor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-) | Construtor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Construtor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Construtor |

## Métodos

| Método | Descrição |
| --- | --- |
| [addNotAccessibleFont](#addNotAccessibleFont-java.lang.String-) |  |
| [getAlignStrategy](#getAlignStrategy--) | Estratégia para alinhar texto. Este parâmetro faz sentido somente quando a flag {@code AlignText} está definida como true. |
| [getAlignText](#getAlignText--) | Esta flag controla o alinhamento de texto no documento convertido. Por padrão, a conversão de documentos não afeta o alinhamento do texto e deixa o texto como está. Contudo, em alguns casos a substituição de fontes causa sobreposição de texto ou espaços extras no documento convertido. Quando esta flag está definida, operações especiais de alinhamento serão realizadas. Esta flag deve ser definida apenas para documentos que apresentam problemas de texto sobreposto ou espaços extras, pois o uso desta flag diminui o desempenho e, em alguns casos, pode corromper o conteúdo do texto. |
| [getAutoTaggingSettings](#getAutoTaggingSettings--) | Obtém ou define as configurações para marcação automática durante a conversão de formato PDF. As configurações de marcação automática são usadas para configurar o comportamento do processo de auto‑marcação, que normalmente é empregado para melhorar a acessibilidade e a estrutura de um documento PDF durante a conversão para um formato PDF específico. |
| [getConvertSoftMaskAction](#getConvertSoftMaskAction--) | Ação para imagens com máscara suave. |
| [getDefault](#getDefault--) | Obtém o objeto PdfFormatConversionOptions com parâmetros padrão |
| [getErrorAction](#getErrorAction--) | Ação para objetos que não podem ser convertidos |
| [getExcludeFontsStrategy](#getExcludeFontsStrategy--) | Estratégia(s) para excluir fontes supérfluas e reduzir o tamanho do arquivo do documento. Este parâmetro faz sentido somente quando a flag {@code OptimizeFileSize} está definida como true. Por padrão, a combinação das estratégias {@code SubsetFonts} e {@code RemoveDuplicatedFonts} é usada. |
| [getFontEmbeddingOptions](#getFontEmbeddingOptions--) | Opções para casos em que não é possível incorporar algumas fontes ao documento PDF. |
| [getFormat](#getFormat--) | Formato PDF. |
| [getIccProfileFileName](#getIccProfileFileName--) | Obtém o nome de arquivo do perfil icc. Caso seja nulo, o perfil icc padrão será usado. |
| [getLogFileName](#getLogFileName--) | Caminho para o arquivo onde os comentários serão armazenados. |
| [getLogStream](#getLogStream--) | Fluxo onde os comentários serão armazenados. |
| [getNonSpecificationCases](#getNonSpecificationCases--) | Mantém sinalizadores para controlar o processo de conversão PDF/A em casos em que o documento de origem não corresponde à especificação PDF/A. |
| [getNotAccessibleFonts](#getNotAccessibleFonts--) | Esta propriedade é out-property. Ela contém todas as fontes (nomes das fontes) que não foram encontradas no computador na última conversão PDF/A. |
| [getOptimizeFileSize](#getOptimizeFileSize--) | Obtém um sinalizador que habilita/desabilita o modo de conversão especial para obter um documento PDF/A com tamanho de arquivo reduzido. Atualmente, esse sinalizador impacta a otimização das fontes usadas no documento PDF e, possivelmente, no futuro, também será usado para ativar a otimização de outras estruturas de dados, como gráficos. O conjunto desse sinalizador e modo pode reduzir significativamente o tamanho do arquivo, mas ao mesmo tempo pode diminuir consideravelmente o desempenho da conversão. |
| [getOutputIntent](#getOutputIntent--) | Obtém ou define o {@link OutputIntent} para a conversão de formato PDF. O {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) especifica o dispositivo de saída ou condição pretendida para a qual o documento PDF está sendo preparado. É usado para garantir que as cores no documento sejam renderizadas corretamente no dispositivo de destino. |
| [getPuaTextProcessingStrategy](#getPuaTextProcessingStrategy--) | Estratégia para processar símbolos da Área de Uso Privado (PUA) do Unicode. |
| [getSymbolicFontEncodingStrategy](#getSymbolicFontEncodingStrategy--) | Estratégia para copiar dados de codificação para fontes simbólicas se a fonte TrueType simbólica possuir mais de uma sub‑tabela de codificação. |
| [getTransparencyAction](#getTransparencyAction--) | Ação para objetos de imagem mascarados |
| [getTransparencyResolution](#getTransparencyResolution--) | Define a resolução ao converter imagens transparentes. Quanto maior a resolução, mais lenta a velocidade de conversão. O valor padrão é 300. |
| [getUnicodeProcessingRules](#getUnicodeProcessingRules--) | Regras para resolver problemas de mapeamento Unicode. Pode ser nulo. |
| [isAsyncImageStreamsConversionMode](#isAsyncImageStreamsConversionMode--) | Obtém/define a execução de fluxos de imagem em modo assíncrono. |
| [isLowMemoryMode](#isLowMemoryMode--) | Modo de conversão de baixa memória está habilitado |
| [isPageByPageFontProcess](#isPageByPageFontProcess--) | Análise de fontes página a página está habilitada Valor padrão = false |
| [isTransferInfo](#isTransferInfo--) | Obtém ou define se os dados de Info devem ser passados para Metadata ao converter para PDF 2.0. Verdadeiro por padrão. |
| [isTransparencyIgnore](#isTransparencyIgnore--) | Valor padrão FALSE e a cor de transparência será mantida para preservar a aparência do documento. Com o valor TRUE, a cor de transparência será convertida em opacidade, podendo alguns objetos ficar cobertos. |
| [setAlignStrategy](#setAlignStrategy-byte-) | Estratégia para alinhar texto. Este parâmetro faz sentido somente quando a flag {@code AlignText} está definida como true. |
| [setAlignText](#setAlignText-boolean-) | Esta flag controla o alinhamento de texto no documento convertido. Por padrão, a conversão de documentos não afeta o alinhamento do texto e deixa o texto como está. Contudo, em alguns casos a substituição de fontes causa sobreposição de texto ou espaços extras no documento convertido. Quando esta flag está definida, operações especiais de alinhamento serão realizadas. Esta flag deve ser definida apenas para documentos que apresentam problemas de texto sobreposto ou espaços extras, pois o uso desta flag diminui o desempenho e, em alguns casos, pode corromper o conteúdo do texto. |
| [setAsyncImageStreamsConversionMode](#setAsyncImageStreamsConversionMode-boolean-) | Obtém/define a execução de fluxos de imagem em modo assíncrono. |
| [setAutoTaggingSettings](#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-) | Obtém ou define as configurações para marcação automática durante a conversão de formato PDF. As configurações de marcação automática são usadas para configurar o comportamento do processo de auto‑marcação, que normalmente é empregado para melhorar a acessibilidade e a estrutura de um documento PDF durante a conversão para um formato PDF específico. |
| [setConvertSoftMaskAction](#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-) | Ação para imagens com máscara suave. |
| [setErrorAction](#setErrorAction-com.aspose.pdf.ConvertErrorAction-) | Ação para objetos que não podem ser convertidos |
| [setExcludeFontsStrategy](#setExcludeFontsStrategy-byte-) | Estratégia(s) para excluir fontes supérfluas e reduzir o tamanho do arquivo do documento. Este parâmetro faz sentido somente quando a flag {@code OptimizeFileSize} está definida como true. Por padrão, a combinação das estratégias {@code SubsetFonts} e {@code RemoveDuplicatedFonts} é usada. |
| [setFormat](#setFormat-com.aspose.pdf.PdfFormat-) | Formato PDF. |
| [setIccProfileFileName](#setIccProfileFileName-java.lang.String-) | Define o nome de arquivo do perfil icc. Caso seja nulo, o perfil icc padrão será usado. |
| [setLogFileName](#setLogFileName-java.lang.String-) | Caminho para o arquivo onde os comentários serão armazenados. |
| [setLogStream](#setLogStream-java.io.OutputStream-) | Fluxo onde os comentários serão armazenados. |
| [setLowMemoryMode](#setLowMemoryMode-boolean-) | Modo de conversão de baixa memória está habilitado |
| [setOptimizeFileSize](#setOptimizeFileSize-boolean-) | Define um sinalizador que habilita/desabilita o modo de conversão especial para obter um documento PDF/A com tamanho de arquivo reduzido. Atualmente, esse sinalizador impacta a otimização das fontes usadas no documento PDF e, possivelmente, no futuro, também será usado para ativar a otimização de outras estruturas de dados, como gráficos. O conjunto desse sinalizador e modo pode reduzir significativamente o tamanho do arquivo, mas ao mesmo tempo pode diminuir consideravelmente o desempenho da conversão. |
| [setOutputIntent](#setOutputIntent-com.aspose.pdf.OutputIntent-) | Obtém ou define o {@link OutputIntent} para a conversão de formato PDF. O {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) especifica o dispositivo de saída ou condição pretendida para a qual o documento PDF está sendo preparado. É usado para garantir que as cores no documento sejam renderizadas corretamente no dispositivo de destino. |
| [setPageByPageFontProcess](#setPageByPageFontProcess-boolean-) | Define o modo de análise de fontes página a página habilitado Valor padrão = false |
| [setPuaTextProcessingStrategy](#setPuaTextProcessingStrategy-int-) | Estratégia para processar símbolos da Área de Uso Privado (PUA) do Unicode. |
| [setSymbolicFontEncodingStrategy](#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-) | Estratégia para copiar dados de codificação para fontes simbólicas se a fonte TrueType simbólica possuir mais de uma sub‑tabela de codificação. |
| [setTransferInfo](#setTransferInfo-boolean-) | Obtém ou define se os dados de Info devem ser passados para Metadata ao converter para PDF 2.0. Verdadeiro por padrão. |
| [setTransparencyAction](#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-) | Ação para objetos de imagem mascarados |
| [setTransparencyIgnore](#setTransparencyIgnore-boolean-) | Valor padrão FALSE e a cor de transparência será mantida para preservar a aparência do documento. Com o valor TRUE, a cor de transparência será convertida em opacidade, podendo alguns objetos ficar cobertos. |
| [setTransparencyResolution](#setTransparencyResolution-int-) | Define a resolução ao converter imagens transparentes. Quanto maior a resolução, mais lenta a velocidade de conversão. O valor padrão é 300. |
| [setUnicodeProcessingRules](#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-) | Regras para resolver problemas de mapeamento Unicode. Pode ser nulo. |

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Construtor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-}
Construtor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Construtor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-}
Construtor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Construtor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Construtor

### addNotAccessibleFont {#addNotAccessibleFont-java.lang.String-}


### getAlignStrategy {#getAlignStrategy--}
```
public byte getAlignStrategy()
```

Estratégia para alinhar texto. Este parâmetro faz sentido somente quando a flag {@code AlignText} está definida como true.

**Returns:**
Elemento SegmentAlignStrategy @see SegmentAlignStrategy

### getAlignText {#getAlignText--}
```
public boolean getAlignText()
```

Esta flag controla o alinhamento de texto no documento convertido. Por padrão, a conversão de documentos não afeta o alinhamento do texto e deixa o texto como está. Contudo, em alguns casos a substituição de fontes causa sobreposição de texto ou espaços extras no documento convertido. Quando esta flag está definida, operações especiais de alinhamento serão realizadas. Esta flag deve ser definida apenas para documentos que apresentam problemas de texto sobreposto ou espaços extras, pois o uso desta flag diminui o desempenho e, em alguns casos, pode corromper o conteúdo do texto.

**Returns:**
valor booleano

### getAutoTaggingSettings {#getAutoTaggingSettings--}
```
public final AutoTaggingSettings getAutoTaggingSettings()
```

Obtém ou define as configurações para marcação automática durante a conversão de formato PDF. As configurações de marcação automática são usadas para configurar o comportamento do processo de auto‑marcação, que normalmente é empregado para melhorar a acessibilidade e a estrutura de um documento PDF durante a conversão para um formato PDF específico.

**Returns:**
Instância de AutoTaggingSettings

### getConvertSoftMaskAction {#getConvertSoftMaskAction--}
```
public final ConvertSoftMaskAction getConvertSoftMaskAction()
```

Ação para imagens com máscara suave.

**Returns:**
valor int

### getDefault {#getDefault--}
```
public static PdfFormatConversionOptions getDefault()
```

Obtém o objeto PdfFormatConversionOptions com parâmetros padrão

**Returns:**
Objeto PdfFormatConversionOptions

### getErrorAction {#getErrorAction--}
```
public ConvertErrorAction getErrorAction()
```

Ação para objetos que não podem ser convertidos

**Returns:**
Elemento ConvertErrorAction @see ConvertErrorAction

### getExcludeFontsStrategy {#getExcludeFontsStrategy--}
```
public byte getExcludeFontsStrategy()
```

Estratégia(s) para excluir fontes supérfluas e reduzir o tamanho do arquivo do documento. Este parâmetro faz sentido somente quando a flag {@code OptimizeFileSize} está definida como true. Por padrão, a combinação das estratégias {@code SubsetFonts} e {@code RemoveDuplicatedFonts} é usada.

**Returns:**
Valor byte @see RemoveFontsStrategy

### getFontEmbeddingOptions {#getFontEmbeddingOptions--}
```
public FontEmbeddingOptions getFontEmbeddingOptions()
```

Opções para casos em que não é possível incorporar algumas fontes ao documento PDF.

**Returns:**
Objeto FontEmbeddingOptions

### getFormat {#getFormat--}
```
public PdfFormat getFormat()
```

Formato PDF.

**Returns:**
Elemento PdfFormat @see PdfFormat

### getIccProfileFileName {#getIccProfileFileName--}
```
public String getIccProfileFileName()
```

Obtém o nome de arquivo do perfil icc. Caso seja nulo, o perfil icc padrão será usado.

**Returns:**
Objeto String

### getLogFileName {#getLogFileName--}
```
public String getLogFileName()
```

Caminho para o arquivo onde os comentários serão armazenados.

**Returns:**
Objeto String

### getLogStream {#getLogStream--}
```
public OutputStream getLogStream()
```

Fluxo onde os comentários serão armazenados.

**Returns:**
objeto OutputStream

### getNonSpecificationCases {#getNonSpecificationCases--}
```
public PdfFormatConversionOptions.PdfANonSpecificationFlags getNonSpecificationCases()
```

Mantém sinalizadores para controlar o processo de conversão PDF/A em casos em que o documento de origem não corresponde à especificação PDF/A.

**Returns:**
objeto PdfANonSpecificationFlags

### getNotAccessibleFonts {#getNotAccessibleFonts--}
```
public String [] getNotAccessibleFonts()
```

Esta propriedade é out-property. Ela contém todas as fontes (nomes das fontes) que não foram encontradas no computador na última conversão PDF/A.

**Returns:**
Matriz de Strings

### getOptimizeFileSize {#getOptimizeFileSize--}
```
public boolean getOptimizeFileSize()
```

Obtém um sinalizador que habilita/desabilita o modo de conversão especial para obter um documento PDF/A com tamanho de arquivo reduzido. Atualmente, esse sinalizador impacta a otimização das fontes usadas no documento PDF e, possivelmente, no futuro, também será usado para ativar a otimização de outras estruturas de dados, como gráficos. O conjunto desse sinalizador e modo pode reduzir significativamente o tamanho do arquivo, mas ao mesmo tempo pode diminuir consideravelmente o desempenho da conversão.

**Returns:**
valor booleano

### getOutputIntent {#getOutputIntent--}
```
public final OutputIntent getOutputIntent()
```

Obtém ou define o {@link OutputIntent} para a conversão de formato PDF. O {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) especifica o dispositivo de saída ou condição pretendida para a qual o documento PDF está sendo preparado. É usado para garantir que as cores no documento sejam renderizadas corretamente no dispositivo de destino.

**Returns:**
instância OutputIntent

### getPuaTextProcessingStrategy {#getPuaTextProcessingStrategy--}
```
public int getPuaTextProcessingStrategy()
```

Estratégia para processar símbolos da Área de Uso Privado (PUA) do Unicode.

**Returns:**
PuaProcessingStrategy elemento @see PuaProcessingStrategy

### getSymbolicFontEncodingStrategy {#getSymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy getSymbolicFontEncodingStrategy()
```

Estratégia para copiar dados de codificação para fontes simbólicas se a fonte TrueType simbólica possuir mais de uma sub‑tabela de codificação.

**Returns:**
objeto PdfASymbolicFontEncodingStrategy

### getTransparencyAction {#getTransparencyAction--}
```
public ConvertTransparencyAction getTransparencyAction()
```

Ação para objetos de imagem mascarados

**Returns:**
ConvertTransparencyAction elemento @see ConvertTransparencyAction

### getTransparencyResolution {#getTransparencyResolution--}
```
public int getTransparencyResolution()
```

Define a resolução ao converter imagens transparentes. Quanto maior a resolução, mais lenta a velocidade de conversão. O valor padrão é 300.

**Returns:**
valor Resolution

### getUnicodeProcessingRules {#getUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules getUnicodeProcessingRules()
```

Regras para resolver problemas de mapeamento Unicode. Pode ser nulo.

**Returns:**
objeto ToUnicodeProcessingRules

### isAsyncImageStreamsConversionMode {#isAsyncImageStreamsConversionMode--}
```
public final boolean isAsyncImageStreamsConversionMode()
```

Obtém/define a execução de fluxos de imagem em modo assíncrono.

**Returns:**
valor booleano

### isLowMemoryMode {#isLowMemoryMode--}
```
public final boolean isLowMemoryMode()
```

Modo de conversão de baixa memória está habilitado

**Returns:**
valor booleano

### isPageByPageFontProcess {#isPageByPageFontProcess--}
```
public boolean isPageByPageFontProcess()
```

Análise de fontes página a página está habilitada Valor padrão = false

**Returns:**
valor booleano

### isTransferInfo {#isTransferInfo--}
```
public final boolean isTransferInfo()
```

Obtém ou define se os dados de Info devem ser passados para Metadata ao converter para PDF 2.0. Verdadeiro por padrão.

**Returns:**
valor booleano

### isTransparencyIgnore {#isTransparencyIgnore--}
```
public boolean isTransparencyIgnore()
```

Valor padrão FALSE e a cor de transparência será mantida para preservar a aparência do documento. Com o valor TRUE, a cor de transparência será convertida em opacidade, podendo alguns objetos ficar cobertos.

**Returns:**
valor booleano

### setAlignStrategy {#setAlignStrategy-byte-}
```
public void setAlignStrategy(byte alignStrategy)
```

Estratégia para alinhar texto. Este parâmetro faz sentido somente quando a flag {@code AlignText} está definida como true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alignStrategy |  | Elemento SegmentAlignStrategy @see SegmentAlignStrategy |

### setAlignText {#setAlignText-boolean-}
```
public void setAlignText(boolean value)
```

Esta flag controla o alinhamento de texto no documento convertido. Por padrão, a conversão de documentos não afeta o alinhamento do texto e deixa o texto como está. Contudo, em alguns casos a substituição de fontes causa sobreposição de texto ou espaços extras no documento convertido. Quando esta flag está definida, operações especiais de alinhamento serão realizadas. Esta flag deve ser definida apenas para documentos que apresentam problemas de texto sobreposto ou espaços extras, pois o uso desta flag diminui o desempenho e, em alguns casos, pode corromper o conteúdo do texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setAsyncImageStreamsConversionMode {#setAsyncImageStreamsConversionMode-boolean-}
```
public final void setAsyncImageStreamsConversionMode(boolean value)
```

Obtém/define a execução de fluxos de imagem em modo assíncrono.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setAutoTaggingSettings {#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-}
Obtém ou define as configurações para marcação automática durante a conversão de formato PDF. As configurações de marcação automática são usadas para configurar o comportamento do processo de auto‑marcação, que normalmente é empregado para melhorar a acessibilidade e a estrutura de um documento PDF durante a conversão para um formato PDF específico.

### setConvertSoftMaskAction {#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-}
Ação para imagens com máscara suave.

### setErrorAction {#setErrorAction-com.aspose.pdf.ConvertErrorAction-}
Ação para objetos que não podem ser convertidos

### setExcludeFontsStrategy {#setExcludeFontsStrategy-byte-}
```
public void setExcludeFontsStrategy(byte value)
```

Estratégia(s) para excluir fontes supérfluas e reduzir o tamanho do arquivo do documento. Este parâmetro faz sentido somente quando a flag {@code OptimizeFileSize} está definida como true. Por padrão, a combinação das estratégias {@code SubsetFonts} e {@code RemoveDuplicatedFonts} é usada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setFormat {#setFormat-com.aspose.pdf.PdfFormat-}
Formato PDF.

### setIccProfileFileName {#setIccProfileFileName-java.lang.String-}
Define o nome de arquivo do perfil icc. Caso seja nulo, o perfil icc padrão será usado.

### setLogFileName {#setLogFileName-java.lang.String-}
Caminho para o arquivo onde os comentários serão armazenados.

### setLogStream {#setLogStream-java.io.OutputStream-}
Fluxo onde os comentários serão armazenados.

### setLowMemoryMode {#setLowMemoryMode-boolean-}
```
public void setLowMemoryMode(boolean value)
```

Modo de conversão de baixa memória está habilitado

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setOptimizeFileSize {#setOptimizeFileSize-boolean-}
```
public void setOptimizeFileSize(boolean value)
```

Define um sinalizador que habilita/desabilita o modo de conversão especial para obter um documento PDF/A com tamanho de arquivo reduzido. Atualmente, esse sinalizador impacta a otimização das fontes usadas no documento PDF e, possivelmente, no futuro, também será usado para ativar a otimização de outras estruturas de dados, como gráficos. O conjunto desse sinalizador e modo pode reduzir significativamente o tamanho do arquivo, mas ao mesmo tempo pode diminuir consideravelmente o desempenho da conversão.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setOutputIntent {#setOutputIntent-com.aspose.pdf.OutputIntent-}
Obtém ou define o {@link OutputIntent} para a conversão de formato PDF. O {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) especifica o dispositivo de saída ou condição pretendida para a qual o documento PDF está sendo preparado. É usado para garantir que as cores no documento sejam renderizadas corretamente no dispositivo de destino.

### setPageByPageFontProcess {#setPageByPageFontProcess-boolean-}
```
public void setPageByPageFontProcess(boolean b)
```

Define o modo de análise de fontes página a página habilitado Valor padrão = false

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| b |  | valor booleano |

### setPuaTextProcessingStrategy {#setPuaTextProcessingStrategy-int-}
```
public void setPuaTextProcessingStrategy(int value)
```

Estratégia para processar símbolos da Área de Uso Privado (PUA) do Unicode.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | PuaProcessingStrategy elemento @see PuaProcessingStrategy |

### setSymbolicFontEncodingStrategy {#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-}
Estratégia para copiar dados de codificação para fontes simbólicas se a fonte TrueType simbólica possuir mais de uma sub‑tabela de codificação.

### setTransferInfo {#setTransferInfo-boolean-}
```
public final void setTransferInfo(boolean value)
```

Obtém ou define se os dados de Info devem ser passados para Metadata ao converter para PDF 2.0. Verdadeiro por padrão.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setTransparencyAction {#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-}
Ação para objetos de imagem mascarados

### setTransparencyIgnore {#setTransparencyIgnore-boolean-}
```
public void setTransparencyIgnore(boolean value)
```

Valor padrão FALSE e a cor de transparência será mantida para preservar a aparência do documento. Com o valor TRUE, a cor de transparência será convertida em opacidade, podendo alguns objetos ficar cobertos.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setTransparencyResolution {#setTransparencyResolution-int-}
```
public void setTransparencyResolution(int dpi)
```

Define a resolução ao converter imagens transparentes. Quanto maior a resolução, mais lenta a velocidade de conversão. O valor padrão é 300.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dpi |  | valor Resolution |

### setUnicodeProcessingRules {#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-}
Regras para resolver problemas de mapeamento Unicode. Pode ser nulo.
