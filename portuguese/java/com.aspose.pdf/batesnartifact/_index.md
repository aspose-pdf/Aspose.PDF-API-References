---
title: "BatesNArtifact"
linktitle: "BatesNArtifact"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe descreve o artefato de numeração Bates."
type: docs
weight: 290
url: /pt/java/com.aspose.pdf/batesnartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.PaginationArtifact, com.aspose.pdf.BatesNArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class BatesNArtifact extends PaginationArtifact
```

Classe descreve o artefato de numeração Bates.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [BatesNArtifact](#BatesNArtifact--) | Inicializa uma nova instância da classe {@link BatesNArtifact}. Este construtor é interno e cria uma instância de artefato de cabeçalho com valores padrão. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getNumberOfDigits](#getNumberOfDigits--) | Obtém ou define o número de dígitos para a numeração Bates. O valor deve estar entre 3 e 15, inclusive. Se for definido um valor menor que 3, ele será ajustado para 3. Se for definido um valor maior que 15, ele será ajustado para 15. O valor padrão é 6. |
| [getPrefix](#getPrefix--) | Obtém ou define o prefixo a ser adicionado ao número Bates. |
| [getStartNumber](#getStartNumber--) | Obtém ou define o número inicial para a numeração Bates. O valor deve ser maior ou igual a 1. Se for definido um valor menor que 1, ele será ajustado para 1. |
| [getSuffix](#getSuffix--) | Obtém ou define o sufixo a ser adicionado ao número Bates. |
| [setNumberOfDigits](#setNumberOfDigits-int-) | Obtém ou define o número de dígitos para a numeração Bates. O valor deve estar entre 3 e 15, inclusive. Se for definido um valor menor que 3, ele será ajustado para 3. Se for definido um valor maior que 15, ele será ajustado para 15. O valor padrão é 6. |
| [setPrefix](#setPrefix-java.lang.String-) | Obtém ou define o prefixo a ser adicionado ao número Bates. |
| [setStartNumber](#setStartNumber-int-) | Obtém ou define o número inicial para a numeração Bates. O valor deve ser maior ou igual a 1. Se for definido um valor menor que 1, ele será ajustado para 1. |
| [setSuffix](#setSuffix-java.lang.String-) | Obtém ou define o sufixo a ser adicionado ao número Bates. |

### BatesNArtifact {#BatesNArtifact--}
```
public BatesNArtifact()
```

Inicializa uma nova instância da classe {@link BatesNArtifact}. Este construtor é interno e cria uma instância de artefato de cabeçalho com valores padrão.

### getNumberOfDigits {#getNumberOfDigits--}
```
public final int getNumberOfDigits()
```

Obtém ou define o número de dígitos para a numeração Bates. O valor deve estar entre 3 e 15, inclusive. Se for definido um valor menor que 3, ele será ajustado para 3. Se for definido um valor maior que 15, ele será ajustado para 15. O valor padrão é 6.

**Returns:**
valor int

### getPrefix {#getPrefix--}
```
public final String getPrefix()
```

Obtém ou define o prefixo a ser adicionado ao número Bates.

**Returns:**
valor String

### getStartNumber {#getStartNumber--}
```
public final int getStartNumber()
```

Obtém ou define o número inicial para a numeração Bates. O valor deve ser maior ou igual a 1. Se for definido um valor menor que 1, ele será ajustado para 1.

**Returns:**
valor int

### getSuffix {#getSuffix--}
```
public final String getSuffix()
```

Obtém ou define o sufixo a ser adicionado ao número Bates.

**Returns:**
valor String

### setNumberOfDigits {#setNumberOfDigits-int-}
```
public final void setNumberOfDigits(int value)
```

Obtém ou define o número de dígitos para a numeração Bates. O valor deve estar entre 3 e 15, inclusive. Se for definido um valor menor que 3, ele será ajustado para 3. Se for definido um valor maior que 15, ele será ajustado para 15. O valor padrão é 6.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setPrefix {#setPrefix-java.lang.String-}
Obtém ou define o prefixo a ser adicionado ao número Bates.

### setStartNumber {#setStartNumber-int-}
```
public final void setStartNumber(int value)
```

Obtém ou define o número inicial para a numeração Bates. O valor deve ser maior ou igual a 1. Se for definido um valor menor que 1, ele será ajustado para 1.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setSuffix {#setSuffix-java.lang.String-}
Obtém ou define o sufixo a ser adicionado ao número Bates.
