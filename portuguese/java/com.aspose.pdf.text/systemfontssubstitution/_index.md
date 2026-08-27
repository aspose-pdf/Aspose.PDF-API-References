---
title: "SystemFontsSubstitution"
linktitle: "SystemFontsSubstitution"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para estratégia de substituição de fontes que substitui fontes por fontes do sistema."
type: docs
weight: 110
url: /pt/java/com.aspose.pdf.text/systemfontssubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SystemFontsSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SystemFontsSubstitution

```
public final class SystemFontsSubstitution extends FontSubstitution
```

Representa uma classe para estratégia de substituição de fontes que substitui fontes por fontes do sistema.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SystemFontsSubstitution](#SystemFontsSubstitution-int-) | Inicializa uma nova instância da classe {@code SystemFontsSubstitution}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getDefaultFont](#getDefaultFont--) | Obtém ou define a fonte de substituição padrão. A fonte é usada quando nenhuma outra substituição válida foi encontrada, mas a fonte inicial pertence à categoria de substituição alvo ({@code FontCategories}). |
| [getFontCategories](#getFontCategories--) | Obtém ou define as categorias de fontes de substituição que devem ser substituídas por fontes do sistema. |
| [setDefaultFont](#setDefaultFont-com.aspose.pdf.Font-) | Obtém ou define a fonte de substituição padrão. A fonte é usada quando nenhuma outra substituição válida foi encontrada, mas a fonte inicial pertence à categoria de substituição alvo ({@code FontCategories}). |
| [setFontCategories](#setFontCategories-int-) | Obtém ou define as categorias de fontes de substituição que devem ser substituídas por fontes do sistema. |

### SystemFontsSubstitution {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```

Inicializa uma nova instância da classe {@code SystemFontsSubstitution}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fontCategories |  | Categorias de fontes-alvo para substituir por fontes do sistema |

### getDefaultFont {#getDefaultFont--}
```
public Font getDefaultFont()
```

Obtém ou define a fonte de substituição padrão. A fonte é usada quando nenhuma outra substituição válida foi encontrada, mas a fonte inicial pertence à categoria de substituição alvo ({@code FontCategories}).

**Returns:**
objeto Font

### getFontCategories {#getFontCategories--}
```
public int getFontCategories()
```

Obtém ou define as categorias de fontes de substituição que devem ser substituídas por fontes do sistema.

**Returns:**
Elemento SubstitutionFontCategories @see SubstitutionFontCategories

### setDefaultFont {#setDefaultFont-com.aspose.pdf.Font-}
Obtém ou define a fonte de substituição padrão. A fonte é usada quando nenhuma outra substituição válida foi encontrada, mas a fonte inicial pertence à categoria de substituição alvo ({@code FontCategories}).

### setFontCategories {#setFontCategories-int-}
```
public void setFontCategories(int value)
```

Obtém ou define as categorias de fontes de substituição que devem ser substituídas por fontes do sistema.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento SubstitutionFontCategories @see SubstitutionFontCategories |
