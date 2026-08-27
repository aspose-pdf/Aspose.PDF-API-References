---
title: "Position"
linktitle: "Position"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um objeto de posição."
type: docs
weight: 3940
url: /pt/java/com.aspose.pdf/position/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Position

```
public final class Position extends Object
```

Representa um objeto de posição.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Position](#Position-double-double-) | Inicializa uma nova instância da classe {@code Position} |

## Métodos

| Método | Descrição |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Determina se o objeto especificado é igual ao objeto {@code Position} atual. |
| [getXIndent](#getXIndent--) | Obtém a coordenada X do objeto |
| [getYIndent](#getYIndent--) | Obtém a coordenada Y do objeto |
| [hashCode](#hashCode--) | Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por {@link java.util.HashMap}. <p> O contrato geral de {@code hashCode} é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método {@code hashCode} deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações {@code equals} no objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método {@code equals(Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos são diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho de tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe {@code Object} retorna inteiros distintos para objetos distintos. (Isso normalmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java<span style="font-size:70%"><sup>TM</sup></span>.) |
| [setXIndent](#setXIndent-double-) | Define a coordenada X do objeto |
| [setYIndent](#setYIndent-double-) | Define a coordenada Y do objeto |
| [toString](#toString--) | Obtém a representação em string do objeto {@code Position} atual. |

### Position {#Position-double-double-}
```
public Position(double xIndent, double yIndent)
```

Inicializa uma nova instância da classe {@code Position}

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xIndent |  | Valor da coordenada X. |
| yIndent |  | Valor da coordenada Y. |

### equals {#equals-java.lang.Object-}
Determina se o objeto especificado é igual ao objeto {@code Position} atual.

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Obtém a coordenada X do objeto

**Returns:**
valor double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Obtém a coordenada Y do objeto

**Returns:**
valor double

### hashCode {#hashCode--}
```
public int hashCode()
```

Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por {@link java.util.HashMap}. <p> O contrato geral de {@code hashCode} é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método {@code hashCode} deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações {@code equals} no objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método {@code equals(Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos são diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho de tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe {@code Object} retorna inteiros distintos para objetos distintos. (Isso normalmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java<span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
um valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Define a coordenada X do objeto

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Define a coordenada Y do objeto

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### toString {#toString--}
```
public String toString()
```

Obtém a representação em string do objeto {@code Position} atual.

**Returns:**
Representação em string do objeto Position.
