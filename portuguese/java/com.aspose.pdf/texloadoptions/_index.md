---
title: "TeXLoadOptions"
linktitle: "TeXLoadOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa opções para carregar/importar arquivo TeX em documento PDF."
type: docs
weight: 4870
url: /pt/java/com.aspose.pdf/texloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.TeXLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.TeXLoadOptions

```
public class TeXLoadOptions extends LoadOptions
```

Representa opções para carregar/importar arquivo TeX em documento PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TeXLoadOptions](#TeXLoadOptions--) | Cria opções de carregamento padrão para converter arquivo TeX em documento PDF. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getDateTime](#getDateTime--) | Obtém/define um determinado valor para primitivas de data/hora como ano, mês, dia e hora. |
| [getInputDirectory](#getInputDirectory--) | Obtém/define o diretório de entrada do TeX. |
| [getJobName](#getJobName--) | Obtém/define o nome do trabalho. |
| [getLoadResult](#getLoadResult--) | Obtém o resultado do carregamento e compilação do TeX - tudo ocorreu sem problemas ou houve comentários/erros. |
| [getNoLigatures](#getNoLigatures--) | Obtém/define um sinalizador que cancela ligaduras em todas as fontes. |
| [getOutputDirectory](#getOutputDirectory--) | Obtém/define o diretório de saída do TeX. |
| [getRasterizeFormulas](#getRasterizeFormulas--) | Obtém/define um sinalizador que permite rasterizar fórmulas matemáticas. |
| [getRepeat](#getRepeat--) | Obtém/define o sinalizador que indica se é necessário executar o trabalho TeX duas vezes, caso, por exemplo, existam referências nos arquivos TeX de entrada. Em geral, esse comportamento é útil quando o mecanismo coleta alguns dados durante o processo de composição e os armazena em um arquivo auxiliar na primeira execução. E na segunda execução, o mecanismo de alguma forma utiliza esses dados. |
| [getRequiredInputDirectory](#getRequiredInputDirectory--) | Obtém/define o diretório de entrada exigido pelo TeX. A entrada necessária são os arquivos que são de alguma forma incluídos no arquivo .tex principal, por exemplo, pacotes para os quais não há suporte nativo. |
| [getShowTerminalOutput](#getShowTerminalOutput--) | Obtém/define o sinalizador que indica se deve mostrar a saída do terminal no console. |
| [getSubsetFonts](#getSubsetFonts--) | Obtém/define a bandeira que indica se deve subdefinir fontes no arquivo de saída ou não. |
| [setDateTime](#setDateTime-java.util.Date-) | Obtém/define um determinado valor para primitivas de data/hora como ano, mês, dia e hora. |
| [setInputDirectory](#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Obtém/define o diretório de entrada do TeX. |
| [setJobName](#setJobName-java.lang.String-) | Obtém/define o nome do trabalho. |
| [setNoLigatures](#setNoLigatures-boolean-) | Obtém/define um sinalizador que cancela ligaduras em todas as fontes. |
| [setOutputDirectory](#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-) | Obtém/define o diretório de saída do TeX. |
| [setRasterizeFormulas](#setRasterizeFormulas-boolean-) | Obtém/define um sinalizador que permite rasterizar fórmulas matemáticas. |
| [setRepeat](#setRepeat-boolean-) | Obtém/define o sinalizador que indica se é necessário executar o trabalho TeX duas vezes, caso, por exemplo, existam referências nos arquivos TeX de entrada. Em geral, esse comportamento é útil quando o mecanismo coleta alguns dados durante o processo de composição e os armazena em um arquivo auxiliar na primeira execução. E na segunda execução, o mecanismo de alguma forma utiliza esses dados. |
| [setRequiredInputDirectory](#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Obtém/define o diretório de entrada exigido pelo TeX. A entrada necessária são os arquivos que são de alguma forma incluídos no arquivo .tex principal, por exemplo, pacotes para os quais não há suporte nativo. |
| [setShowTerminalOutput](#setShowTerminalOutput-boolean-) | Obtém/define o sinalizador que indica se deve mostrar a saída do terminal no console. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Obtém/define a bandeira que indica se deve subdefinir fontes no arquivo de saída ou não. |

### TeXLoadOptions {#TeXLoadOptions--}
```
public TeXLoadOptions()
```

Cria opções de carregamento padrão para converter arquivo TeX em documento PDF.

### getDateTime {#getDateTime--}
```
public final Date getDateTime()
```

Obtém/define um determinado valor para primitivas de data/hora como ano, mês, dia e hora.

**Returns:**
Instância de Date

### getInputDirectory {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```

Obtém/define o diretório de entrada do TeX.

**Returns:**
Instância de ITeXInputDirectory

### getJobName {#getJobName--}
```
public final String getJobName()
```

Obtém/define o nome do trabalho.

**Returns:**
valor String

### getLoadResult {#getLoadResult--}
```
public final int getLoadResult()
```

Obtém o resultado do carregamento e compilação do TeX - tudo ocorreu sem problemas ou houve comentários/erros.

**Returns:**
Elemento TeXLoadResult

### getNoLigatures {#getNoLigatures--}
```
public final boolean getNoLigatures()
```

Obtém/define um sinalizador que cancela ligaduras em todas as fontes.

**Returns:**
valor booleano

### getOutputDirectory {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```

Obtém/define o diretório de saída do TeX.

**Returns:**
Instância de ITeXOutputDirectory

### getRasterizeFormulas {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```

Obtém/define um sinalizador que permite rasterizar fórmulas matemáticas.

**Returns:**
valor booleano

### getRepeat {#getRepeat--}
```
public final boolean getRepeat()
```

Obtém/define o sinalizador que indica se é necessário executar o trabalho TeX duas vezes, caso, por exemplo, existam referências nos arquivos TeX de entrada. Em geral, esse comportamento é útil quando o mecanismo coleta alguns dados durante o processo de composição e os armazena em um arquivo auxiliar na primeira execução. E na segunda execução, o mecanismo de alguma forma utiliza esses dados.

**Returns:**
valor booleano

### getRequiredInputDirectory {#getRequiredInputDirectory--}
```
public final ITeXInputDirectory getRequiredInputDirectory()
```

Obtém/define o diretório de entrada exigido pelo TeX. A entrada necessária são os arquivos que são de alguma forma incluídos no arquivo .tex principal, por exemplo, pacotes para os quais não há suporte nativo.

**Returns:**
Instância de ITeXInputDirectory

### getShowTerminalOutput {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```

Obtém/define o sinalizador que indica se deve mostrar a saída do terminal no console.

**Returns:**
valor booleano

### getSubsetFonts {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```

Obtém/define a bandeira que indica se deve subdefinir fontes no arquivo de saída ou não.

**Returns:**
valor booleano

### setDateTime {#setDateTime-java.util.Date-}
Obtém/define um determinado valor para primitivas de data/hora como ano, mês, dia e hora.

### setInputDirectory {#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Obtém/define o diretório de entrada do TeX.

### setJobName {#setJobName-java.lang.String-}
Obtém/define o nome do trabalho.

### setNoLigatures {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```

Obtém/define um sinalizador que cancela ligaduras em todas as fontes.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setOutputDirectory {#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-}
Obtém/define o diretório de saída do TeX.

### setRasterizeFormulas {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```

Obtém/define um sinalizador que permite rasterizar fórmulas matemáticas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRepeat {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```

Obtém/define o sinalizador que indica se é necessário executar o trabalho TeX duas vezes, caso, por exemplo, existam referências nos arquivos TeX de entrada. Em geral, esse comportamento é útil quando o mecanismo coleta alguns dados durante o processo de composição e os armazena em um arquivo auxiliar na primeira execução. E na segunda execução, o mecanismo de alguma forma utiliza esses dados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRequiredInputDirectory {#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Obtém/define o diretório de entrada exigido pelo TeX. A entrada necessária são os arquivos que são de alguma forma incluídos no arquivo .tex principal, por exemplo, pacotes para os quais não há suporte nativo.

### setShowTerminalOutput {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```

Obtém/define o sinalizador que indica se deve mostrar a saída do terminal no console.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Obtém/define a bandeira que indica se deve subdefinir fontes no arquivo de saída ou não.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
