---
title: "Matriz"
linktitle: "Matriz"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa a matriz de transformação."
type: docs
weight: 2900
url: /pt/java/com.aspose.pdf/matrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix

```
public final class Matrix extends Object
```

Classe que representa a matriz de transformação.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Matrix](#Matrix--) | <p> Construtor cria matriz padrão 1 para 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-double:A-) | <p> Construtor aceita uma matriz com a seguinte representação de array: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-double-double-double-double-double-double-) | <p> Inicializa a matriz de transformação com os coeficientes especificados. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix](#Matrix-float:A-) | <p> Construtor aceita uma matriz com a seguinte representação de array: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-com.aspose.pdf.Matrix-) | <p> Construtor cria matriz padrão 1 para 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-) | <p> Construtor cria matriz padrão 1 para 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix-) | Adiciona matriz a outra matriz. |
| [equals](#equals-java.lang.Object-) | Compara matriz com outro objeto. |
| [getA](#getA--) | Obtém o membro A da matriz de transformação. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Traduz rotação em ângulo (graus) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | Obtém o membro B da matriz de transformação. |
| [getC](#getC--) | Obtém o membro C da matriz de transformação. |
| [getD](#getD--) | Obtém o membro D da matriz de transformação. |
| [getData](#getData--) | Obtém os dados da Matrix como array. |
| [getE](#getE--) | Obtenha o membro E da matriz de transformação. |
| [getElements](#getElements--) | Elementos da matriz. |
| [getF](#getF--) | Obtenha o membro F da matriz de transformação. |
| [getFlipMatrix](#getFlipMatrix--) | Obtém a matriz de inversão. |
| [getMatrix](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | Traduz a matriz para um objeto de array PDF. |
| [hashCode](#hashCode--) | Código hash para o objeto. |
| [isIdentity](#isIdentity--) | Verifica se esta matriz é identidade. |
| [isInt16](#isInt16-double-) | Somente para uso interno |
| [isInt16Values](#isInt16Values--) | Somente para uso interno |
| [multiply](#multiply-com.aspose.pdf.Matrix-) | <p> Multiplica a matriz por outra matriz. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre> |
| [reverse](#reverse--) | <p> Calcula a matriz inversa. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre> |
| [rotation](#rotation-double-) | <p> Cria uma matriz para o ângulo de rotação fornecido. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre> |
| [rotation](#rotation-com.aspose.pdf.Rotation-) | Cria uma matriz para a rotação fornecida. |
| [scale](#scale-double-double-) | <p> Cria uma matriz para a escala fornecida. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre> |
| [scale](#scale-double-double-double:A-double:A-) | Escala x e y com a matriz usando a seguinte fórmula: x1 = A*x + C*y; y1 = B*x + D*y; |
| [scale](#scale-double-double-com.aspose.pdf.Matrix-) | Aplica escala à matriz fornecida. |
| [setA](#setA-double-) | Define o membro A da matriz de transformação. |
| [setB](#setB-double-) | Define o membro B da matriz de transformação. |
| [setC](#setC-double-) | Define o membro C da matriz de transformação. |
| [setD](#setD-double-) | Define o membro D da matriz de transformação. |
| [setE](#setE-double-) | Define o membro E da matriz de transformação. |
| [setF](#setF-double-) | Define o membro F da matriz de transformação. |
| [skew](#skew-double-double-) | Cria uma matriz para o ângulo de rotação fornecido. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2); |
| [toString](#toString--) | Retorna a representação textual da matriz. |
| [transform](#transform-double-double-double:A-double:A-) | Transforma coordenadas usando esta matriz. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1); |
| [transform](#transform-com.aspose.pdf.Point-) | Transforma ponto usando esta matriz. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p); |
| [transform](#transform-com.aspose.pdf.Rectangle-) | Transforma retângulo. |
| [translate](#translate-double-double-com.aspose.pdf.Matrix-) | Translada uma matriz pela quantidade especificada nas direções x e y. |
| [unScale](#unScale-double-double-double:A-double:A-) | Redimensiona de volta x1 e y1 e retorna x e y antes da transformação da matriz usando a seguinte fórmula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [unTransform](#unTransform-double-double-double:A-double:A-) | Transforma de volta x1 e y1 e retorna x e y antes da transformação da matriz usando a seguinte fórmula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |

### Matrix {#Matrix--}
```
public Matrix()
```

<p> Construtor cria matriz padrão 1 para 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-double:A-}
```
public Matrix(double[] matrixArray)
```

<p> Construtor aceita uma matriz com a seguinte representação de array: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| matrixArray |  | Array de dados da matriz. |

### Matrix {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
```

<p> Inicializa a matriz de transformação com os coeficientes especificados. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a |  | Um valor de matriz. |
| b |  | Valor da matriz B. |
| c |  | Valor da matriz C. |
| d |  | Valor da matriz D. |
| e |  | Valor da matriz E. |
| f |  | Valor da matriz F. |

### Matrix {#Matrix-float:A-}
```
public Matrix(float[] matrixArray)
```

<p> Construtor aceita uma matriz com a seguinte representação de array: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| matrixArray |  | Array de dados da matriz. |

### Matrix {#Matrix-com.aspose.pdf.Matrix-}
<p> Construtor cria matriz padrão 1 para 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-}
<p> Construtor cria matriz padrão 1 para 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### add {#add-com.aspose.pdf.Matrix-}
Adiciona matriz a outra matriz.

### equals {#equals-java.lang.Object-}
Compara matriz com outro objeto.

### getA {#getA--}
```
public double getA()
```

Obtém o membro A da matriz de transformação.

**Returns:**
valor double

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Traduz rotação em ângulo (graus) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

Obtém o membro B da matriz de transformação.

**Returns:**
valor double

### getC {#getC--}
```
public double getC()
```

Obtém o membro C da matriz de transformação.

**Returns:**
valor double

### getD {#getD--}
```
public double getD()
```

Obtém o membro D da matriz de transformação.

**Returns:**
valor double

### getData {#getData--}
```
public final double[] getData()
```

Obtém os dados da Matrix como array.

**Returns:**
array de valores double

### getE {#getE--}
```
public double getE()
```

Obtenha o membro E da matriz de transformação.

**Returns:**
valor double

### getElements {#getElements--}
```
public float[] getElements()
```

Elementos da matriz.

**Returns:**
array float[]

### getF {#getF--}
```
public double getF()
```

Obtenha o membro F da matriz de transformação.

**Returns:**
valor double

### getFlipMatrix {#getFlipMatrix--}
```
public final Matrix getFlipMatrix()
```

Obtém a matriz de inversão.

**Returns:**
Instância da matriz

### getMatrix {#getMatrix-com.aspose.pdf.engine.data.ITrailerable-}
Traduz a matriz para um objeto de array PDF.

### hashCode {#hashCode--}
```
public int hashCode()
```

Código hash para o objeto.

**Returns:**
Código hash.

### isIdentity {#isIdentity--}
```
public final boolean isIdentity()
```

Verifica se esta matriz é identidade.

**Returns:**
valor booleano

### isInt16 {#isInt16-double-}
```
public static boolean isInt16(double value)
```

Somente para uso interno

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

**Returns:**
valor booleano

### isInt16Values {#isInt16Values--}
```
public boolean isInt16Values()
```

Somente para uso interno

**Returns:**
valor booleano

### multiply {#multiply-com.aspose.pdf.Matrix-}
<p> Multiplica a matriz por outra matriz. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre>

### reverse {#reverse--}
```
public Matrix reverse()
```

<p> Calcula a matriz inversa. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre>

**Returns:**
Matriz inversa.

### rotation {#rotation-double-}
```
public static Matrix rotation(double alpha)
```

<p> Cria uma matriz para o ângulo de rotação fornecido. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alpha |  | Ângulo de rotação em radianos. |

**Returns:**
Matriz de transformação.

### rotation {#rotation-com.aspose.pdf.Rotation-}
Cria uma matriz para a rotação fornecida.

### scale {#scale-double-double-}
```
public static Matrix scale(double x, double y)
```

<p> Cria uma matriz para a escala fornecida. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x |  | Escala x. |
| y |  | Escala y. |

**Returns:**
Matriz de transformação.

### scale {#scale-double-double-double:A-double:A-}
```
public final void scale(double x, double y, double[] x1, double[] y1)
```

Escala x e y com a matriz usando a seguinte fórmula: x1 = A*x + C*y; y1 = B*x + D*y;

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x |  | Coordenada X de entrada |
| y |  | Coordenada Y de entrada |
| x1 |  | Coordenada X de saída |
| y1 |  | Coordenada Y de saída |

### scale {#scale-double-double-com.aspose.pdf.Matrix-}
Aplica escala à matriz fornecida.

### setA {#setA-double-}
```
public void setA(double value)
```

Define o membro A da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setB {#setB-double-}
```
public void setB(double value)
```

Define o membro B da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setC {#setC-double-}
```
public void setC(double value)
```

Define o membro C da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setD {#setD-double-}
```
public void setD(double value)
```

Define o membro D da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setE {#setE-double-}
```
public void setE(double value)
```

Define o membro E da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setF {#setF-double-}
```
public void setF(double value)
```

Define o membro F da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### skew {#skew-double-double-}
```
public static Matrix skew(double alpha, double beta)
```

Cria uma matriz para o ângulo de rotação fornecido. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alpha |  | Ângulo de inclinação x em radianos. |
| beta |  | Ângulo de inclinação y em radianos. |

**Returns:**
Matriz de transformação.

### toString {#toString--}
```
public String toString()
```

Retorna a representação textual da matriz.

**Returns:**
Representação em string da matriz

### transform {#transform-double-double-double:A-double:A-}
```
public final void transform(double x, double y, double[] x1, double[] y1)
```

Transforma coordenadas usando esta matriz. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1);

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x |  | Coordenada X. |
| y |  | Coordenada Y. |
| x1 |  | Coordenada X transformada. |
| y1 |  | Coordenada Y transformada. |

### transform {#transform-com.aspose.pdf.Point-}
Transforma ponto usando esta matriz. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p);

### transform {#transform-com.aspose.pdf.Rectangle-}
Transforma retângulo.

### translate {#translate-double-double-com.aspose.pdf.Matrix-}
Translada uma matriz pela quantidade especificada nas direções x e y.

### unScale {#unScale-double-double-double:A-double:A-}
```
public final void unScale(double x1, double y1, double[] x, double[] y)
```

Redimensiona de volta x1 e y1 e retorna x e y antes da transformação da matriz usando a seguinte fórmula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x1 |  | Coordenada X de entrada |
| y1 |  | Coordenada Y de entrada |
| x |  | Coordenada X de saída |
| y |  | Coordenada Y de saída |

### unTransform {#unTransform-double-double-double:A-double:A-}
```
public final void unTransform(double x1, double y1, double[] x, double[] y)
```

Transforma de volta x1 e y1 e retorna x e y antes da transformação da matriz usando a seguinte fórmula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x1 |  | Coordenada X de entrada |
| y1 |  | Coordenada Y de entrada |
| x |  | Coordenada X de saída |
| y |  | Coordenada Y de saída |
