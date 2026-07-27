---
title: "PsLoadOptions"
linktitle: "PsLoadOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa opções para carregamento/importação de arquivo .mht em documento PDF."
type: docs
weight: 4060
url: /pt/java/com.aspose.pdf/psloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PsLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PsLoadOptions

```
public final class PsLoadOptions extends LoadOptions
```

Representa opções para carregamento/importação de arquivo .mht em documento PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PsLoadOptions](#PsLoadOptions--) | Cria opções de carregamento para converter PostScript em documento PDF com caminho base vazio. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getFontsFolders](#getFontsFolders--) | Obtém os caminhos das pastas de fontes. As pastas com fontes adicionais para conversão. |
| [isConvertFontsToTTF](#isConvertFontsToTTF--) | Especifica se deve salvar fontes não TrueType como TTF. Isso diminui significativamente o volume do documento resultante na conversão de PS para PDF e aumenta a velocidade de conversão de arquivos PS com grande quantidade de texto em fontes não TrueType para qualquer formato de saída. No entanto, há um pequeno deslocamento vertical do texto ao converter um arquivo PostSctipt para imagem. |
| [setConvertFontsToTTF](#setConvertFontsToTTF-boolean-) | Especifica se deve salvar fontes não TrueType como TTF. Isso diminui significativamente o volume do documento resultante na conversão de PS para PDF e aumenta a velocidade de conversão de arquivos PS com grande quantidade de texto em fontes não TrueType para qualquer formato de saída. No entanto, há um pequeno deslocamento vertical do texto ao converter um arquivo PostSctipt para imagem. |
| [setFontsFolders](#setFontsFolders-java.lang.String:A-) | Define os caminhos das pastas de fontes. As pastas com fontes adicionais para conversão. |

### PsLoadOptions {#PsLoadOptions--}
```
public PsLoadOptions()
```

Cria opções de carregamento para converter PostScript em documento PDF com caminho base vazio.

### getFontsFolders {#getFontsFolders--}
```
public String [] getFontsFolders()
```

Obtém os caminhos das pastas de fontes. As pastas com fontes adicionais para conversão.

**Returns:**
array de valores String

### isConvertFontsToTTF {#isConvertFontsToTTF--}
```
public final boolean isConvertFontsToTTF()
```

Especifica se deve salvar fontes não TrueType como TTF. Isso diminui significativamente o volume do documento resultante na conversão de PS para PDF e aumenta a velocidade de conversão de arquivos PS com grande quantidade de texto em fontes não TrueType para qualquer formato de saída. No entanto, há um pequeno deslocamento vertical do texto ao converter um arquivo PostSctipt para imagem.

**Returns:**
valor booleano

### setConvertFontsToTTF {#setConvertFontsToTTF-boolean-}
```
public final void setConvertFontsToTTF(boolean value)
```

Especifica se deve salvar fontes não TrueType como TTF. Isso diminui significativamente o volume do documento resultante na conversão de PS para PDF e aumenta a velocidade de conversão de arquivos PS com grande quantidade de texto em fontes não TrueType para qualquer formato de saída. No entanto, há um pequeno deslocamento vertical do texto ao converter um arquivo PostSctipt para imagem.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setFontsFolders {#setFontsFolders-java.lang.String:A-}
Define os caminhos das pastas de fontes. As pastas com fontes adicionais para conversão.
