---
title: "ToUnicodeProcessingRules"
linktitle: "ToUnicodeProcessingRules"
second_title: "Referência da API Aspose.PDF para Java"
description: "Esta classe descreve regras que podem ser usadas para resolver o erro do Adobe Preflight \"Text cannot be mapped to Unicode\"."
type: docs
weight: 5380
url: /pt/java/com.aspose.pdf/tounicodeprocessingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ToUnicodeProcessingRules

```
public class ToUnicodeProcessingRules extends Object
```

Esta classe descreve regras que podem ser usadas para resolver o erro do Adobe Preflight "Text cannot be mapped to Unicode".

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules--) | Inicializa uma nova instância da classe {@link ToUnicodeProcessingRules}. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-) | Inicializa uma nova instância da classe {@link ToUnicodeProcessingRules} com a opção especificada para remover espaços dos nomes CMap. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-boolean-) | Inicializa uma nova instância da classe {@link ToUnicodeProcessingRules} com opções especificadas. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getMapNonLinkedSymbolsOnSpace](#getMapNonLinkedSymbolsOnSpace--) | Algumas fontes não fornecem informações sobre unicodes para alguns símbolos de texto. Essa falta de informação gera um erro "Text cannot be mapped to Unicode". Use esta flag para mapear símbolos não vinculados para o unicode "space" (código 32). |
| [getRemoveSpacesFromCMapNames](#getRemoveSpacesFromCMapNames--) | Algumas fontes têm mapas de códigos de caracteres ToUnicode com espaços nos nomes. Esses espaços podem gerar erros no mapeamento de texto Unicode. Esta flag indica a remoção de espaços dos nomes dos mapas de códigos de caracteres ToUnicode. Por padrão, false. |
| [setMapNonLinkedSymbolsOnSpace](#setMapNonLinkedSymbolsOnSpace-boolean-) | Algumas fontes não fornecem informações sobre unicodes para alguns símbolos de texto. Essa falta de informação gera um erro "Text cannot be mapped to Unicode". Use esta flag para mapear símbolos não vinculados para o unicode "space" (código 32). |
| [setRemoveSpacesFromCMapNames](#setRemoveSpacesFromCMapNames-boolean-) | Algumas fontes têm mapas de códigos de caracteres ToUnicode com espaços nos nomes. Esses espaços podem gerar erros no mapeamento de texto Unicode. Esta flag indica a remoção de espaços dos nomes dos mapas de códigos de caracteres ToUnicode. Por padrão, false. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```

Inicializa uma nova instância da classe {@link ToUnicodeProcessingRules}.

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```

Inicializa uma nova instância da classe {@link ToUnicodeProcessingRules} com a opção especificada para remover espaços dos nomes CMap.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| removeSpaces |  | Um valor booleano que indica se deve remover espaços dos nomes CMap. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```

Inicializa uma nova instância da classe {@link ToUnicodeProcessingRules} com opções especificadas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| removeSpaces |  | Indica se os espaços devem ser removidos dos nomes CMap. |
| mapNonLinkedUnicodesOnSpace |  | Indica se símbolos Unicode não vinculados devem ser mapeados para espaços. |

### getMapNonLinkedSymbolsOnSpace {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```

Algumas fontes não fornecem informações sobre unicodes para alguns símbolos de texto. Essa falta de informação gera um erro "Text cannot be mapped to Unicode". Use esta flag para mapear símbolos não vinculados para o unicode "space" (código 32).

**Returns:**
valor booleano

### getRemoveSpacesFromCMapNames {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```

Algumas fontes têm mapas de códigos de caracteres ToUnicode com espaços nos nomes. Esses espaços podem gerar erros no mapeamento de texto Unicode. Esta flag indica a remoção de espaços dos nomes dos mapas de códigos de caracteres ToUnicode. Por padrão, false.

**Returns:**
valor booleano

### setMapNonLinkedSymbolsOnSpace {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```

Algumas fontes não fornecem informações sobre unicodes para alguns símbolos de texto. Essa falta de informação gera um erro "Text cannot be mapped to Unicode". Use esta flag para mapear símbolos não vinculados para o unicode "space" (código 32).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRemoveSpacesFromCMapNames {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```

Algumas fontes têm mapas de códigos de caracteres ToUnicode com espaços nos nomes. Esses espaços podem gerar erros no mapeamento de texto Unicode. Esta flag indica a remoção de espaços dos nomes dos mapas de códigos de caracteres ToUnicode. Por padrão, false.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
