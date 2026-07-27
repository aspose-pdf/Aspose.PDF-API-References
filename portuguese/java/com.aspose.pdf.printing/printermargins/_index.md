---
title: "PrinterMargins"
linktitle: "PrinterMargins"
second_title: "Referência da API Aspose.PDF para Java"
description: "Especifica as dimensões das margens de uma página impressa."
type: docs
weight: 70
url: /pt/java/com.aspose.pdf.printing/printermargins/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrinterMargins

```
public class PrinterMargins extends Object
```

Especifica as dimensões das margens de uma página impressa.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PrinterMargins](#PrinterMargins--) | Inicializa uma nova instância da classe Margins com margens de 1 polegada de largura. |
| [PrinterMargins](#PrinterMargins-int-int-int-int-) | Inicializa uma nova instância da classe Margins com as margens esquerda, direita, superior e inferior especificadas. |

## Métodos

| Método | Descrição |
| --- | --- |
| [deepClone](#deepClone--) | Recupera uma duplicata deste objeto, membro a membro. |
| [equals](#equals-java.lang.Object-) | Compara este Margins ao Object especificado para determinar se eles têm as mesmas dimensões. (Substitui Object.Equals(Object).) |
| [getBottom](#getBottom--) | Obtém ou define a margem inferior, em centésimos de polegada. |
| [getLeft](#getLeft--) | Obtém ou define a largura da margem esquerda, em centésimos de polegada. |
| [getRight](#getRight--) | Obtém ou define a largura da margem direita, em centésimos de polegada. |
| [getTop](#getTop--) | Obtém ou define a largura da margem superior, em centésimos de polegada. |
| [hashCode](#hashCode--) | Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por {@link java.util.HashMap}. <p> O contrato geral de {@code hashCode} é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método {@code hashCode} deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações {@code equals} no objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método {@code equals(Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos são diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho de tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe {@code Object} retorna inteiros distintos para objetos distintos. (Isso normalmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java<span style="font-size:70%"><sup>TM</sup></span>.) |
| [op_Equality](#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Compara duas Margins para determinar se têm as mesmas dimensões. |
| [op_Inequality](#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-) | Compara duas Margins para determinar se têm larguras diferentes. |
| [setBottom](#setBottom-int-) | Obtém ou define a margem inferior, em centésimos de polegada. |
| [setLeft](#setLeft-int-) | Obtém ou define a largura da margem esquerda, em centésimos de polegada. |
| [setRight](#setRight-int-) | Obtém ou define a largura da margem direita, em centésimos de polegada. |
| [setTop](#setTop-int-) | Obtém ou define a largura da margem superior, em centésimos de polegada. |

### PrinterMargins {#PrinterMargins--}
```
public PrinterMargins()
```

Inicializa uma nova instância da classe Margins com margens de 1 polegada de largura.

### PrinterMargins {#PrinterMargins-int-int-int-int-}
```
public PrinterMargins(int left, int right, int top, int bottom)
```

Inicializa uma nova instância da classe Margins com as margens esquerda, direita, superior e inferior especificadas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| esquerda |  | valor int |
| direita |  | valor int |
| superior |  | valor int |
| inferior |  | valor int |

### deepClone {#deepClone--}
```
public PrinterMargins deepClone()
```

Recupera uma duplicata deste objeto, membro a membro.

**Returns:**
Objeto PrinterMargins

### equals {#equals-java.lang.Object-}
Compara este Margins ao Object especificado para determinar se eles têm as mesmas dimensões. (Substitui Object.Equals(Object).)

### getBottom {#getBottom--}
```
public int getBottom()
```

Obtém ou define a margem inferior, em centésimos de polegada.

**Returns:**
valor int

### getLeft {#getLeft--}
```
public int getLeft()
```

Obtém ou define a largura da margem esquerda, em centésimos de polegada.

**Returns:**
valor int

### getRight {#getRight--}
```
public int getRight()
```

Obtém ou define a largura da margem direita, em centésimos de polegada.

**Returns:**
valor int

### getTop {#getTop--}
```
public int getTop()
```

Obtém ou define a largura da margem superior, em centésimos de polegada.

**Returns:**
valor int

### hashCode {#hashCode--}
```
public int hashCode()
```

Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por {@link java.util.HashMap}. <p> O contrato geral de {@code hashCode} é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método {@code hashCode} deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações {@code equals} no objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método {@code equals(Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos são diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho de tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe {@code Object} retorna inteiros distintos para objetos distintos. (Isso normalmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java<span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
um valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### op_Equality {#op_Equality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
Compara duas Margins para determinar se têm as mesmas dimensões.

### op_Inequality {#op_Inequality-com.aspose.pdf.printing.PrinterMargins-com.aspose.pdf.printing.PrinterMargins-}
Compara duas Margins para determinar se têm larguras diferentes.

### setBottom {#setBottom-int-}
```
public void setBottom(int value)
```

Obtém ou define a margem inferior, em centésimos de polegada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setLeft {#setLeft-int-}
```
public void setLeft(int value)
```

Obtém ou define a largura da margem esquerda, em centésimos de polegada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setRight {#setRight-int-}
```
public void setRight(int value)
```

Obtém ou define a largura da margem direita, em centésimos de polegada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setTop {#setTop-int-}
```
public void setTop(int value)
```

Obtém ou define a largura da margem superior, em centésimos de polegada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
