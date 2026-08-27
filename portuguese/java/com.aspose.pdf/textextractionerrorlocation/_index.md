---
title: "TextExtractionErrorLocation"
linktitle: "TextExtractionErrorLocation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a localização no documento PDF onde o erro de extração de texto apareceu."
type: docs
weight: 5050
url: /pt/java/com.aspose.pdf/textextractionerrorlocation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextExtractionErrorLocation

```
public final class TextExtractionErrorLocation extends Object
```

Representa a localização no documento PDF onde o erro de extração de texto apareceu.

## Métodos

| Método | Descrição |
| --- | --- |
| [getFontUsedKey](#getFontUsedKey--) | Chave (nome) do objeto PDF Font que é usado para exibir o operador que causa erro de extração de texto. |
| [getFormKey](#getFormKey--) | Chave (nome) do PDF Form XObject no qual o erro de extração de texto do fluxo de conteúdo está localizado. Não vazio se ObjectType == 'xForm'. |
| [getObjectType](#getObjectType--) | Tipo do objeto PDF (Page ou xForm) no qual o erro de extração de texto do fluxo de conteúdo está localizado. |
| [getOperatorIndex](#getOperatorIndex--) | Índice do operador de exibição de texto no fluxo de conteúdo (coleção de operadores) que causa erro de extração de texto. |
| [getOperatorString](#getOperatorString--) | Operador de exibição de texto que causa erro de extração de texto. |
| [getPageNumber](#getPageNumber--) | Número da página do documento onde o erro de extração de texto está localizado. |
| [getPath](#getPath--) | Localização do documento PDF onde o erro de extração de texto apareceu. |
| [getTextStartPoint](#getTextStartPoint--) | Chave (nome) do objeto PDF Font que é usado para exibir o operador que causa erro de extração de texto. |
| [toString](#toString--) | Retorna a representação em string. |

### getFontUsedKey {#getFontUsedKey--}
```
public String getFontUsedKey()
```

Chave (nome) do objeto PDF Font que é usado para exibir o operador que causa erro de extração de texto.

**Returns:**
valor String

### getFormKey {#getFormKey--}
```
public String getFormKey()
```

Chave (nome) do PDF Form XObject no qual o erro de extração de texto do fluxo de conteúdo está localizado. Não vazio se ObjectType == 'xForm'.

**Returns:**
valor String

### getObjectType {#getObjectType--}
```
public String getObjectType()
```

Tipo do objeto PDF (Page ou xForm) no qual o erro de extração de texto do fluxo de conteúdo está localizado.

**Returns:**
valor String

### getOperatorIndex {#getOperatorIndex--}
```
public int getOperatorIndex()
```

Índice do operador de exibição de texto no fluxo de conteúdo (coleção de operadores) que causa erro de extração de texto.

**Returns:**
valor int

### getOperatorString {#getOperatorString--}
```
public String getOperatorString()
```

Operador de exibição de texto que causa erro de extração de texto.

**Returns:**
valor String

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Número da página do documento onde o erro de extração de texto está localizado.

**Returns:**
valor int

### getPath {#getPath--}
```
public String getPath()
```

Localização do documento PDF onde o erro de extração de texto apareceu.

**Returns:**
valor String

### getTextStartPoint {#getTextStartPoint--}
```
public Point getTextStartPoint()
```

Chave (nome) do objeto PDF Font que é usado para exibir o operador que causa erro de extração de texto.

**Returns:**
Instância de Point

### toString {#toString--}
```
public String toString()
```

Retorna a representação em string.

**Returns:**
Representação em string.
