---
title: "FontEmbeddingOptions"
linktitle: "FontEmbeddingOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "O padrão PDF/A requer que todas as fontes sejam incorporadas ao documento. Esta classe inclui sinalizadores para casos em que não é possível incorporar alguma fonte porque essa fonte está ausente."
type: docs
weight: 1680
url: /pt/java/com.aspose.pdf/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontEmbeddingOptions

```
public class FontEmbeddingOptions extends Object
```

O padrão PDF/A requer que todas as fontes sejam incorporadas ao documento. Esta classe inclui sinalizadores para casos em que não é possível incorporar alguma fonte porque essa fonte está ausente no PC de destino.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [FontEmbeddingOptions](#FontEmbeddingOptions--) | Inicializa uma nova instância da classe {@link FontEmbeddingOptions}. Este construtor define o valor padrão para a propriedade {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}) como {@code }. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getUseDefaultSubstitution](#getUseDefaultSubstitution--) | Indica se deve substituir fonte não incorporada usando a estratégia padrão de substituição de fontes. Por padrão, false; |
| [setUseDefaultSubstitution](#setUseDefaultSubstitution-boolean-) | Indica se deve substituir fonte não incorporada usando a estratégia padrão de substituição de fontes. Por padrão, false; |

### FontEmbeddingOptions {#FontEmbeddingOptions--}
```
public FontEmbeddingOptions()
```

Inicializa uma nova instância da classe {@link FontEmbeddingOptions}. Este construtor define o valor padrão para a propriedade {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}) como {@code }.

### getUseDefaultSubstitution {#getUseDefaultSubstitution--}
```
public boolean getUseDefaultSubstitution()
```

Indica se deve substituir fonte não incorporada usando a estratégia padrão de substituição de fontes. Por padrão, false;

**Returns:**
valor booleano

### setUseDefaultSubstitution {#setUseDefaultSubstitution-boolean-}
```
public void setUseDefaultSubstitution(boolean value)
```

Indica se deve substituir fonte não incorporada usando a estratégia padrão de substituição de fontes. Por padrão, false;

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
