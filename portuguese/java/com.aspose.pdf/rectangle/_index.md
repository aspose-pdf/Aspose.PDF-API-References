---
title: "Rectangle"
linktitle: "Rectangle"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa um retângulo."
type: docs
weight: 4100
url: /pt/java/com.aspose.pdf/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Rectangle

**All Implemented Interfaces:**
Cloneable, Comparable < Object >

```
public final class Rectangle extends Object implements Comparable < Object >, Cloneable
```

Classe que representa um retângulo.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Rectangle](#Rectangle-double-double-double-double-) | Construtor de Rectangle. |
| [Rectangle](#Rectangle-double-double-double-double-boolean-) | Construtor de Rectangle. |

## Métodos

| Método | Descrição |
| --- | --- |
| [_Intersect](#Z:Z_Intersect-com.aspose.pdf.Rectangle-) | Intersecciona retângulos. Método obsoleto. Por favor, use Intersect em vez disso. |
| [center](#center--) | Retorna coordenadas do centro do retângulo. |
| [clone](#clone--) | Clona o objeto Rectangle. |
| [compareTo](#compareTo-java.lang.Object-) | CompareTo |
| [contains](#contains-com.aspose.pdf.Point-) | Determina se o ponto fornecido está dentro do retângulo. |
| [contains](#contains-com.aspose.pdf.Point-boolean-) | Determina se o ponto fornecido está dentro do retângulo. |
| [containsLine](#containsLine-double-double-double-double-) | Determina se o retângulo contém uma linha representada por dois pontos. |
| [containsPoint](#containsPoint-double-double-) | Determina se o ponto fornecido está contido dentro do retângulo. |
| [deepClone](#deepClone--) | Clona o objeto Rectangle. |
| [equals](#equals-java.lang.Object-) | Verifica se os retângulos são iguais, ou seja, têm a mesma posição e tamanho. |
| [fromRect](#fromRect-java.awt.Rectangle-) | Inicializa um novo retângulo a partir da instância fornecida de System.Drawing.Rectangle. |
| [fromRect](#fromRect-java.awt.geom.Rectangle2D.Float-) | Inicializa um novo retângulo a partir da instância fornecida de System.Drawing.Rectangle. |
| [fromRectInternal](#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [getArea](#getArea--) | Calcula a área do retângulo. |
| [getEmpty](#getEmpty--) | Obtém retângulo vazio |
| [getHeight](#getHeight--) | Obtém a altura do retângulo. |
| [getLLX](#getLLX--) | Obtém a coordenada X do canto inferior esquerdo. |
| [getLLY](#getLLY--) | Obtém a coordenada Y do canto inferior esquerdo. |
| [getTrivial](#getTrivial--) | Inicializa um retângulo trivial, ou seja, um retângulo com posição e tamanho zero. |
| [getURX](#getURX--) | Obtém a coordenada X do canto superior direito. |
| [getURY](#getURY--) | Obtém a coordenada Y do canto superior direito. |
| [getWidth](#getWidth--) | Obtém a largura do retângulo. |
| [hashCode](#hashCode--) | Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por {@link java.util.HashMap}. <p> O contrato geral de {@code hashCode} é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método {@code hashCode} deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações {@code equals} no objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método {@code equals(Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos são diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho de tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe {@code Object} retorna inteiros distintos para objetos distintos. (Isso normalmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java<span style="font-size:70%"><sup>TM</sup></span>.) |
| [intersect](#intersect-com.aspose.pdf.Rectangle-) | Intersecciona dois retângulos. |
| [isEmpty](#isEmpty--) | Verifica se o retângulo está vazio. |
| [isInclude](#isInclude-com.aspose.pdf.Rectangle-double-) | Verifica se este retângulo inclui todo outro retângulo. Ou seja, todo o outro retângulo está dentro deste retângulo. A diferença com o método IsIntersect é que IsIntersect retornará verdadeiro para retângulos parcialmente intersectados, mas IsInclude retornará falso. |
| [isIntersect](#isIntersect-com.aspose.pdf.Rectangle-) | Determina se este retângulo intersecta com outro retângulo. |
| [isPoint](#isPoint--) | Verifica se o retângulo é um ponto, ou seja, LLX é igual a URX e LLY é igual a URY. |
| [isTrivial](#isTrivial--) | Verifica se o retângulo é trivial, ou seja, tem tamanho zero e posição. |
| [join](#join-com.aspose.pdf.Rectangle-) | Une retângulos. |
| [moveBy](#moveBy-double-double-) | Desloca o retângulo pelos deltas especificados. |
| [nearEquals](#nearEquals-com.aspose.pdf.Rectangle-double-) | Verifica se os retângulos são quase iguais, ou seja, têm posição e tamanhos quase os mesmos (até delta). |
| [parse](#parse-java.lang.String-) | Tenta analisar a string e extrair dela os componentes do retângulo llx, lly, urx, ury. |
| [rotate](#rotate-com.aspose.pdf.Rotation-) | Gira o retângulo pelo ângulo especificado. |
| [rotateAngle](#rotateAngle-int-) | Gira o retângulo pelo ângulo especificado. |
| [setLLX](#setLLX-double-) | Define a coordenada X do canto inferior esquerdo. |
| [setLLY](#setLLY-double-) | Define a coordenada Y do canto inferior esquerdo. |
| [setURX](#setURX-double-) | Define a coordenada X do canto superior direito. |
| [setURY](#setURY-double-) | Define a coordenada Y do canto superior direito. |
| [toArray](#toArray-com.aspose.pdf.engine.data.ITrailerable-) |  |
| [toPoints](#toPoints--) | Converte o retângulo em um array de pontos ("QuadPoints"). |
| [toRect](#toRect--) | Converte o retângulo em uma instância de System.Drawing.Rectangle. Posicionamentos e tamanhos em ponto flutuante são truncados. |
| [toString](#toString--) | Obtém a representação em string do retângulo. |

### Rectangle {#Rectangle-double-double-double-double-}
```
public Rectangle(double llx, double lly, double urx, double ury)
```

Construtor de Rectangle.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| llx |  | X do canto inferior esquerdo. |
| lly |  | Y do canto inferior esquerdo. |
| urx |  | X do canto superior direito. |
| ury |  | Y do canto superior direito. |

### Rectangle {#Rectangle-double-double-double-double-boolean-}
```
public Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)
```

Construtor de Rectangle.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| llx |  | X do canto inferior esquerdo. |
| lly |  | Y do canto inferior esquerdo. |
| urx |  | X do canto superior direito. |
| ury |  | Y do canto superior direito. |
| normalizeCoordinates |  | Normaliza as coordenadas do retângulo. |

### _Intersect {#Z:Z_Intersect-com.aspose.pdf.Rectangle-}
Intersecciona retângulos. Método obsoleto. Por favor, use Intersect em vez disso.

### center {#center--}
```
public Point center()
```

Retorna coordenadas do centro do retângulo.

**Returns:**
Ponto que é o centro do retângulo.

### clone {#clone--}
```
public Rectangle clone()
```

Clona o objeto Rectangle.

**Returns:**
Clonar objeto.

### compareTo {#compareTo-java.lang.Object-}
CompareTo

### contains {#contains-com.aspose.pdf.Point-}
Determina se o ponto fornecido está dentro do retângulo.

### contains {#contains-com.aspose.pdf.Point-boolean-}
Determina se o ponto fornecido está dentro do retângulo.

### containsLine {#containsLine-double-double-double-double-}
```
public final boolean containsLine(double x1, double y1, double x2, double y2)
```

Determina se o retângulo contém uma linha representada por dois pontos.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x1 |  | A coordenada X do ponto inicial da linha. |
| y1 |  | A coordenada Y do ponto inicial da linha. |
| x2 |  | A coordenada X do ponto final da linha. |
| y2 |  | A coordenada Y do ponto final da linha. |

**Returns:**
{@code true} se o retângulo contém a linha; caso contrário, {@code false}.

### containsPoint {#containsPoint-double-double-}
```
public final boolean containsPoint(double x, double y)
```

Determina se o ponto fornecido está contido dentro do retângulo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x |  | Coordenada X do ponto. |
| y |  | Coordenada Y do ponto. |

**Returns:**
{@code true} se o ponto está contido dentro do retângulo; caso contrário, {@code false}.

### deepClone {#deepClone--}
```
public Rectangle deepClone()
```

Clona o objeto Rectangle.

**Returns:**
Clonar objeto.

### equals {#equals-java.lang.Object-}
Verifica se os retângulos são iguais, ou seja, têm a mesma posição e tamanho.

### fromRect {#fromRect-java.awt.Rectangle-}
Inicializa um novo retângulo a partir da instância fornecida de System.Drawing.Rectangle.

### fromRect {#fromRect-java.awt.geom.Rectangle2D.Float-}
Inicializa um novo retângulo a partir da instância fornecida de System.Drawing.Rectangle.

### fromRectInternal {#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-}


### getArea {#getArea--}
```
public final double getArea()
```

Calcula a área do retângulo.

**Returns:**
A área do retângulo como um double, calculada multiplicando a largura e a altura.

### getEmpty {#getEmpty--}
```
public static Rectangle getEmpty()
```

Obtém retângulo vazio

**Returns:**
novo objeto Rectangle

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtém a altura do retângulo.

**Returns:**
valor double

### getLLX {#getLLX--}
```
public double getLLX()
```

Obtém a coordenada X do canto inferior esquerdo.

**Returns:**
valor double

### getLLY {#getLLY--}
```
public double getLLY()
```

Obtém a coordenada Y do canto inferior esquerdo.

**Returns:**
valor double

### getTrivial {#getTrivial--}
```
public static Rectangle getTrivial()
```

Inicializa um retângulo trivial, ou seja, um retângulo com posição e tamanho zero.

**Returns:**
novo objeto Rectangle

### getURX {#getURX--}
```
public double getURX()
```

Obtém a coordenada X do canto superior direito.

**Returns:**
valor double

### getURY {#getURY--}
```
public double getURY()
```

Obtém a coordenada Y do canto superior direito.

**Returns:**
valor double

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtém a largura do retângulo.

**Returns:**
valor double

### hashCode {#hashCode--}
```
public int hashCode()
```

Retorna um valor de código hash para o objeto. Este método é suportado em benefício de tabelas hash, como as fornecidas por {@link java.util.HashMap}. <p> O contrato geral de {@code hashCode} é: <ul> <li>Sempre que for invocado no mesmo objeto mais de uma vez durante a execução de uma aplicação Java, o método {@code hashCode} deve retornar consistentemente o mesmo inteiro, desde que nenhuma informação usada nas comparações {@code equals} no objeto seja modificada. Esse inteiro não precisa permanecer consistente de uma execução da aplicação para outra execução da mesma aplicação. <li>Se dois objetos são iguais de acordo com o método {@code equals(Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos deve produzir o mesmo resultado inteiro. <li>Não é <em>necessário</em> que, se dois objetos são diferentes de acordo com o método {@link java.lang.Object#equals(java.lang.Object)}, então chamar o método {@code hashCode} em cada um dos dois objetos produza resultados inteiros distintos. Contudo, o programador deve estar ciente de que produzir resultados inteiros distintos para objetos diferentes pode melhorar o desempenho de tabelas hash. </ul> <p> Na medida do razoavelmente prático, o método hashCode definido pela classe {@code Object} retorna inteiros distintos para objetos distintos. (Isso normalmente é implementado convertendo o endereço interno do objeto em um inteiro, mas essa técnica de implementação não é exigida pela linguagem de programação Java<span style="font-size:70%"><sup>TM</sup></span>.)

**Returns:**
um valor de código hash para este objeto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### intersect {#intersect-com.aspose.pdf.Rectangle-}
Intersecciona dois retângulos.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Verifica se o retângulo está vazio.

**Returns:**
valor booleano

### isInclude {#isInclude-com.aspose.pdf.Rectangle-double-}
Verifica se este retângulo inclui todo outro retângulo. Ou seja, todo o outro retângulo está dentro deste retângulo. A diferença com o método IsIntersect é que IsIntersect retornará verdadeiro para retângulos parcialmente intersectados, mas IsInclude retornará falso.

### isIntersect {#isIntersect-com.aspose.pdf.Rectangle-}
Determina se este retângulo intersecta com outro retângulo.

### isPoint {#isPoint--}
```
public boolean isPoint()
```

Verifica se o retângulo é um ponto, ou seja, LLX é igual a URX e LLY é igual a URY.

**Returns:**
valor booleano

### isTrivial {#isTrivial--}
```
public boolean isTrivial()
```

Verifica se o retângulo é trivial, ou seja, tem tamanho zero e posição.

**Returns:**
valor booleano

### join {#join-com.aspose.pdf.Rectangle-}
Une retângulos.

### moveBy {#moveBy-double-double-}
```
public final void moveBy(double dx, double dy)
```

Desloca o retângulo pelos deltas especificados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dx |  | Valor do deslocamento no eixo X. |
| dy |  | Valor do deslocamento no eixo Y. |

### nearEquals {#nearEquals-com.aspose.pdf.Rectangle-double-}
Verifica se os retângulos são quase iguais, ou seja, têm posição e tamanhos quase os mesmos (até delta).

### parse {#parse-java.lang.String-}
Tenta analisar a string e extrair dela os componentes do retângulo llx, lly, urx, ury.

### rotate {#rotate-com.aspose.pdf.Rotation-}
Gira o retângulo pelo ângulo especificado.

### rotateAngle {#rotateAngle-int-}
```
public void rotateAngle(int angle)
```

Gira o retângulo pelo ângulo especificado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| angle |  | Ângulo de rotação em graus entre 0 e 360. |

### setLLX {#setLLX-double-}
```
public void setLLX(double value)
```

Define a coordenada X do canto inferior esquerdo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setLLY {#setLLY-double-}
```
public void setLLY(double value)
```

Define a coordenada Y do canto inferior esquerdo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setURX {#setURX-double-}
```
public void setURX(double value)
```

Define a coordenada X do canto superior direito.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setURY {#setURY-double-}
```
public void setURY(double value)
```

Define a coordenada Y do canto superior direito.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### toArray {#toArray-com.aspose.pdf.engine.data.ITrailerable-}


### toPoints {#toPoints--}
```
public final Point [] toPoints()
```

Converte o retângulo em um array de pontos ("QuadPoints").

**Returns:**
Array de pontos.

### toRect {#toRect--}
```
public Rectangle toRect()
```

Converte o retângulo em uma instância de System.Drawing.Rectangle. Posicionamentos e tamanhos em ponto flutuante são truncados.

**Returns:**
Resultado da conversão.

### toString {#toString--}
```
public String toString()
```

Obtém a representação em string do retângulo.

**Returns:**
String tem o formato llx,lly,urx,ury.
