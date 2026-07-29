---
title: "SimpleFontSubstitution"
linktitle: "SimpleFontSubstitution"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para estratégia simples de substituição de fontes."
type: docs
weight: 90
url: /pt/java/com.aspose.pdf.text/simplefontsubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SimpleFontSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SimpleFontSubstitution

```
public final class SimpleFontSubstitution extends FontSubstitution
```

Representa uma classe para estratégia simples de substituição de fontes.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-) | Inicializa uma nova instância da classe {@code SimpleFontSubstitution}. |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-) | Inicializa uma nova instância da classe {@code SimpleFontSubstitution}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Obtém o nome da fonte original que deve ser substituído por {@code SubstitutionFontName} |
| [getSubstitutedUnicode](#getSubstitutedUnicode-char-) | Retorna substituição unicode |
| [getSubstitutionFontName](#getSubstitutionFontName--) | Obtém o nome da fonte que deve substituir o {@code OriginalFontName} |

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-}
Inicializa uma nova instância da classe {@code SimpleFontSubstitution}.

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-}
Inicializa uma nova instância da classe {@code SimpleFontSubstitution}.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Obtém o nome da fonte original que deve ser substituído por {@code SubstitutionFontName}

**Returns:**
valor String

### getSubstitutedUnicode {#getSubstitutedUnicode-char-}
```
public char getSubstitutedUnicode(char unicode)
```

Retorna substituição unicode

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| unicode |  | valor char |

**Returns:**
valor char

### getSubstitutionFontName {#getSubstitutionFontName--}
```
public String getSubstitutionFontName()
```

Obtém o nome da fonte que deve substituir o {@code OriginalFontName}

**Returns:**
valor String
