---
title: "Group"
linktitle: "Group"
second_title: "Referência da API Aspose.PDF para Java"
description: "Uma classe de atributos de grupo que especifica os atributos do grupo de páginas da página para uso no modelo de imagem transparente."
type: docs
weight: 1850
url: /pt/java/com.aspose.pdf/group/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Group

```
public final class Group extends Object
```

Uma classe de atributos de grupo que especifica os atributos do grupo de páginas da página para uso no modelo de imagem transparente.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Group](#Group-com.aspose.pdf.Page-) | O construtor. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getColorSpace](#getColorSpace--) | Obtém ColorSpace <p> |
| [isKnockout](#isKnockout--) | Para uso interno somente. Se este sinalizador for false, objetos posteriores dentro do grupo são compostos com os anteriores com os quais se sobrepõem; se true, eles são compostos com o fundo inicial do grupo e sobrescrevem ("knock out") quaisquer objetos anteriores sobrepostos. |
| [isTransparency](#isTransparency--) | para uso interno apenas retorna a bandeira de transparência do grupo. |
| [setColorSpace](#setColorSpace-com.aspose.pdf.ColorSpace-) | O espaço de cores do grupo. |
| [setKnockout](#setKnockout-com.aspose.pdf.ExtendedBoolean-) | Se esta bandeira for falsa, os objetos posteriores dentro do grupo são compostos com os anteriores com os quais se sobrepõem; se for verdadeira, eles são compostos com o fundo inicial do grupo e sobrescrevem (\"knock out\") quaisquer objetos anteriores que se sobreponham. |

### Group {#Group-com.aspose.pdf.Page-}
O construtor.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

Obtém ColorSpace <p>

**Returns:**
Valor de ColorSpace. @see ColorSpace

### isKnockout {#isKnockout--}
```
public ExtendedBoolean isKnockout()
```

Para uso interno somente. Se este sinalizador for false, objetos posteriores dentro do grupo são compostos com os anteriores com os quais se sobrepõem; se true, eles são compostos com o fundo inicial do grupo e sobrescrevem ("knock out") quaisquer objetos anteriores sobrepostos.

**Returns:**
Elemento ExtendedBoolean @see ExtendedBoolean

### isTransparency {#isTransparency--}
```
public boolean isTransparency()
```

para uso interno apenas retorna a bandeira de transparência do grupo.

**Returns:**
valor booleano

### setColorSpace {#setColorSpace-com.aspose.pdf.ColorSpace-}
O espaço de cores do grupo.

### setKnockout {#setKnockout-com.aspose.pdf.ExtendedBoolean-}
Se esta bandeira for falsa, os objetos posteriores dentro do grupo são compostos com os anteriores com os quais se sobrepõem; se for verdadeira, eles são compostos com o fundo inicial do grupo e sobrescrevem (\"knock out\") quaisquer objetos anteriores que se sobreponham.
