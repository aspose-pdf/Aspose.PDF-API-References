---
title: "CustomFontSubstitutionBase.OriginalFontSpecification"
linktitle: "CustomFontSubstitutionBase.OriginalFontSpecification"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa a especificação da fonte original. </p> <hr> <p> Fornece informações relacionadas à fonte original, como , flag. Também fornece uma flag que ajuda a verificar se a substituição ocorrerá.</p>"
type: docs
weight: 20
url: /pt/java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification

```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification extends Object
```

<p> Representa a especificação da fonte original. </p> <hr> <p> Fornece informações relacionadas à fonte original, como , flag. Também fornece uma flag que ajuda a verificar se a substituição ocorrerá de qualquer forma com a fonte e o usuário pode sobrescrever a lógica padrão de substituição. </p>

## Construtores

| Construtor | Descrição |
| --- | --- |
| [OriginalFontSpecification](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | Inicializa um novo objeto OriginalFontSpecification. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Obtém o nome da fonte original. |
| [isEmbedded](#isEmbedded--) | Obtém um valor que indica se a fonte está incorporada. |
| [isSubstitutionUnavoidable](#isSubstitutionUnavoidable--) | <p> Obtém um valor que indica que a substituição é inevitável. </p> |

### OriginalFontSpecification {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
Inicializa um novo objeto OriginalFontSpecification.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Obtém o nome da fonte original.

**Returns:**
valor String

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

Obtém um valor que indica se a fonte está incorporada.

**Returns:**
valor booleano

### isSubstitutionUnavoidable {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```

<p> Obtém um valor que indica que a substituição é inevitável. </p>

**Returns:**
boolean value <hr> <p> Retorna true caso a substituição tenha sido solicitada devido à ausência da fonte original ou caso a fonte original não possa ser usada no contexto de alguma tarefa. Caso o usuário ignore a flag e não substitua a fonte – o procedimento padrão de substituição de fontes é executado. Mas isso oferece ao usuário a oportunidade de alterar o procedimento padrão de substituição de fontes e definir uma fonte melhor para o sistema. Retorna false caso a fonte original esteja presente, seja válida, mas seja permitido ao usuário substituí‑la. </p>
