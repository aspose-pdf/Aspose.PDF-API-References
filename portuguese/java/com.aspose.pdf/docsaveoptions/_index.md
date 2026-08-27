---
title: "DocSaveOptions"
linktitle: "DocSaveOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Opções de salvamento para exportação para o formato Doc"
type: docs
weight: 1030
url: /pt/java/com.aspose.pdf/docsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.DocSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class DocSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Opções de salvamento para exportação para o formato Doc

## Construtores

| Construtor | Descrição |
| --- | --- |
| [DocSaveOptions](#DocSaveOptions--) | Construtor |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Este manipulador pode ser usado para tratar eventos de progresso da conversão, por exemplo, pode ser usado para exibir uma barra de progresso ou mensagens sobre a quantidade atual de páginas processadas; exemplo de código do manipulador que mostra o progresso no console é : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre> |
| [getFormat](#getFormat--) | Obter formato de saída |
| [getImageResolutionX](#getImageResolutionX--) | Resolução X das imagens convertidas. |
| [getImageResolutionY](#getImageResolutionY--) | Resolução Y das imagens convertidas. |
| [getMaxDistanceBetweenTextLines](#getMaxDistanceBetweenTextLines--) | Este parâmetro é usado para agrupar linhas de texto em parágrafos. Determina quão distantes podem estar duas linhas de texto relativas. Especificado em centenas de por cento da altura das linhas de texto. |
| [getMemorySaveModePath](#getMemorySaveModePath--) | Define o caminho (nome do arquivo ou nome do diretório) para armazenar dados temporários ao converter no modo de salvamento em memória. |
| [getMode](#getMode--) | Modo de reconhecimento. |
| [getRelativeHorizontalProximity](#getRelativeHorizontalProximity--) | No PDF, as palavras podem ser representadas internamente por operadores que imprimem palavras imprimindo independentemente suas letras ou sílabas. Portanto, para detectar palavras às vezes precisamos detectar grupos de caracteres independentes que na verdade são palavras. Esta configuração define a largura do espaço entre elementos de texto (letras, sílabas) que deve ser tratada como distância entre palavras durante o reconhecimento de palavras no PDF de origem. (a presença de espaço vazio com ao menos essa largura entre letras indica que os elementos textuais pertencem a palavras diferentes). É normalizado ao tamanho da fonte – 1,0 significa 100 % do tamanho de fonte presumido da palavra. ATENÇÃO! É usado apenas nos casos em que o PDF de origem contém fontes específicas raramente usadas, para as quais o valor ideal não pode ser calculado a partir da fonte. Assim, na grande maioria dos casos este parâmetro não altera nada no documento resultante. |
| [isAddReturnToLineEnd](#isAddReturnToLineEnd--) | É usado para quebras de parágrafo ou de linha. |
| [isConvertType3Fonts](#isConvertType3Fonts--) | Obtém ou define a conversão para fontes Type3. Em fontes Type 3, os glifos são definidos por fluxos de operadores gráficos. Isso significa que na saída DOC/DOCX vemos imagens em vez de texto. Defina este sinalizador como true para converter fontes Type3 para TTF e obter texto no arquivo resultante. |
| [isRecognizeBullets](#isRecognizeBullets--) | Ative o reconhecimento de marcadores. |
| [isReSaveFonts](#isReSaveFonts--) | Obtém ou define o procedimento para regravar fontes. Se definido como true, recarregamos as fontes em cada página para evitar a influência das propriedades de fontes anteriores e carregamos a fonte recém‑criada do zero. Defina esta opção como false se quiser melhorar o desempenho. O valor padrão é true; |
| [setAddReturnToLineEnd](#setAddReturnToLineEnd-boolean-) | Use quebras de parágrafo ou de linha |
| [setBatchSize](#setBatchSize-int-) | Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino. |
| [setConvertType3Fonts](#setConvertType3Fonts-boolean-) | Obtém ou define a conversão para fontes Type3. Em fontes Type 3, os glifos são definidos por fluxos de operadores gráficos. Isso significa que na saída DOC/DOCX vemos imagens em vez de texto. Defina este sinalizador como true para converter fontes Type3 para TTF e obter texto no arquivo resultante. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Este manipulador pode ser usado para tratar eventos de progresso da conversão, por exemplo. |
| [setFormat](#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-) | Defina o formato de saída |
| [setImageResolutionX](#setImageResolutionX-int-) | Resolução X das imagens convertidas. |
| [setImageResolutionY](#setImageResolutionY-int-) | Resolução Y das imagens convertidas. |
| [setMaxDistanceBetweenTextLines](#setMaxDistanceBetweenTextLines-float-) | Este parâmetro é usado para agrupar linhas de texto em parágrafos. Determina quão distantes podem estar duas linhas de texto relativas. Especificado em centenas de por cento da altura das linhas de texto. |
| [setMemorySaveModePath](#setMemorySaveModePath-java.lang.String-) | Define o caminho (nome do arquivo ou nome do diretório) para armazenar dados temporários ao converter no modo de salvamento em memória. |
| [setMode](#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-) | Modo de reconhecimento. |
| [setRecognizeBullets](#setRecognizeBullets-boolean-) | Ative o reconhecimento de marcadores. |
| [setRelativeHorizontalProximity](#setRelativeHorizontalProximity-float-) | No PDF, as palavras podem ser representadas internamente por operadores que imprimem palavras imprimindo independentemente suas letras ou sílabas. Portanto, para detectar palavras às vezes precisamos detectar grupos de caracteres independentes que na verdade são palavras. Esta configuração define a largura do espaço entre elementos de texto (letras, sílabas) que deve ser tratada como distância entre palavras durante o reconhecimento de palavras no PDF de origem. (a presença de espaço vazio com ao menos essa largura entre letras indica que os elementos textuais pertencem a palavras diferentes). É normalizado ao tamanho da fonte – 1,0 significa 100 % do tamanho de fonte presumido da palavra. ATENÇÃO! É usado apenas nos casos em que o PDF de origem contém fontes específicas raramente usadas, para as quais o valor ideal não pode ser calculado a partir da fonte. Assim, na grande maioria dos casos este parâmetro não altera nada no documento resultante. |
| [setReSaveFonts](#setReSaveFonts-boolean-) | Obtém ou define o procedimento para regravar fontes. Se definido como true, recarregamos as fontes em cada página para evitar a influência das propriedades de fontes anteriores e carregamos a fonte recém‑criada do zero. Defina esta opção como false se quiser melhorar o desempenho. O valor padrão é true; |

### DocSaveOptions {#DocSaveOptions--}
```
public DocSaveOptions()
```

Construtor

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino.

**Returns:**
valor int

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Este manipulador pode ser usado para lidar com eventos de progresso de conversão, por exemplo, pode ser usado para exibir uma barra de progresso ou mensagens sobre a quantidade atual de páginas processadas, exemplo do código do manipulador que mostra o progresso no console é : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre>

**Returns:**
instância ConversionProgressEventHandler

### getFormat {#getFormat--}
```
public DocSaveOptions.DocFormat getFormat()
```

Obter formato de saída

**Returns:**
Elemento DocFormat @see com.aspose.pdf.DocSaveOptions.DocFormat

### getImageResolutionX {#getImageResolutionX--}
```
public int getImageResolutionX()
```

Resolução X das imagens convertidas.

**Returns:**
valor int

### getImageResolutionY {#getImageResolutionY--}
```
public int getImageResolutionY()
```

Resolução Y das imagens convertidas.

**Returns:**
valor int

### getMaxDistanceBetweenTextLines {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```

Este parâmetro é usado para agrupar linhas de texto em parágrafos. Determina quão distantes podem estar duas linhas de texto relativas. Especificado em centenas de por cento da altura das linhas de texto.

**Returns:**
valor float

### getMemorySaveModePath {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```

Define o caminho (nome do arquivo ou nome do diretório) para armazenar dados temporários ao converter no modo de salvamento em memória.

**Returns:**
valor String

### getMode {#getMode--}
```
public DocSaveOptions.RecognitionMode getMode()
```

Modo de reconhecimento.

**Returns:**
Valor RecognitionMode @see RecognitionMode

### getRelativeHorizontalProximity {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```

No PDF, as palavras podem ser representadas internamente por operadores que imprimem palavras imprimindo independentemente suas letras ou sílabas. Portanto, para detectar palavras às vezes precisamos detectar grupos de caracteres independentes que na verdade são palavras. Esta configuração define a largura do espaço entre elementos de texto (letras, sílabas) que deve ser tratada como distância entre palavras durante o reconhecimento de palavras no PDF de origem. (a presença de espaço vazio com ao menos essa largura entre letras indica que os elementos textuais pertencem a palavras diferentes). É normalizado ao tamanho da fonte – 1,0 significa 100 % do tamanho de fonte presumido da palavra. ATENÇÃO! É usado apenas nos casos em que o PDF de origem contém fontes específicas raramente usadas, para as quais o valor ideal não pode ser calculado a partir da fonte. Assim, na grande maioria dos casos este parâmetro não altera nada no documento resultante.

**Returns:**
Proximidade relativa

### isAddReturnToLineEnd {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```

É usado para quebras de parágrafo ou de linha.

**Returns:**
valor booleano.

### isConvertType3Fonts {#isConvertType3Fonts--}
```
public final boolean isConvertType3Fonts()
```

Obtém ou define a conversão para fontes Type3. Em fontes Type 3, os glifos são definidos por fluxos de operadores gráficos. Isso significa que na saída DOC/DOCX vemos imagens em vez de texto. Defina este sinalizador como true para converter fontes Type3 para TTF e obter texto no arquivo resultante.

**Returns:**
valor booleano

### isRecognizeBullets {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```

Ative o reconhecimento de marcadores.

**Returns:**
valor booleano

### isReSaveFonts {#isReSaveFonts--}
```
public final boolean isReSaveFonts()
```

Obtém ou define o procedimento para regravar fontes. Se definido como true, recarregamos as fontes em cada página para evitar a influência das propriedades de fontes anteriores e carregamos a fonte recém‑criada do zero. Defina esta opção como false se quiser melhorar o desempenho. O valor padrão é true;

**Returns:**
valor booleano

### setAddReturnToLineEnd {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```

Use quebras de parágrafo ou de linha

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano. |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  |  |

### setConvertType3Fonts {#setConvertType3Fonts-boolean-}
```
public final void setConvertType3Fonts(boolean value)
```

Obtém ou define a conversão para fontes Type3. Em fontes Type 3, os glifos são definidos por fluxos de operadores gráficos. Isso significa que na saída DOC/DOCX vemos imagens em vez de texto. Defina este sinalizador como true para converter fontes Type3 para TTF e obter texto no arquivo resultante.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Este manipulador pode ser usado para tratar eventos de progresso da conversão, por exemplo.

### setFormat {#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-}
Defina o formato de saída

### setImageResolutionX {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```

Resolução X das imagens convertidas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setImageResolutionY {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```

Resolução Y das imagens convertidas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setMaxDistanceBetweenTextLines {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```

Este parâmetro é usado para agrupar linhas de texto em parágrafos. Determina quão distantes podem estar duas linhas de texto relativas. Especificado em centenas de por cento da altura das linhas de texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setMemorySaveModePath {#setMemorySaveModePath-java.lang.String-}
Define o caminho (nome do arquivo ou nome do diretório) para armazenar dados temporários ao converter no modo de salvamento em memória.

### setMode {#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-}
Modo de reconhecimento.

### setRecognizeBullets {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```

Ative o reconhecimento de marcadores.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRelativeHorizontalProximity {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```

No PDF, as palavras podem ser representadas internamente por operadores que imprimem palavras imprimindo independentemente suas letras ou sílabas. Portanto, para detectar palavras às vezes precisamos detectar grupos de caracteres independentes que na verdade são palavras. Esta configuração define a largura do espaço entre elementos de texto (letras, sílabas) que deve ser tratada como distância entre palavras durante o reconhecimento de palavras no PDF de origem. (a presença de espaço vazio com ao menos essa largura entre letras indica que os elementos textuais pertencem a palavras diferentes). É normalizado ao tamanho da fonte – 1,0 significa 100 % do tamanho de fonte presumido da palavra. ATENÇÃO! É usado apenas nos casos em que o PDF de origem contém fontes específicas raramente usadas, para as quais o valor ideal não pode ser calculado a partir da fonte. Assim, na grande maioria dos casos este parâmetro não altera nada no documento resultante.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Proximidade relativa |

### setReSaveFonts {#setReSaveFonts-boolean-}
```
public final void setReSaveFonts(boolean value)
```

Obtém ou define o procedimento para regravar fontes. Se definido como true, recarregamos as fontes em cada página para evitar a influência das propriedades de fontes anteriores e carregamos a fonte recém‑criada do zero. Defina esta opção como false se quiser melhorar o desempenho. O valor padrão é true;

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
