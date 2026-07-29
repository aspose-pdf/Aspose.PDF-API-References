---
title: "Matrix3D"
linktitle: "Matrix3D"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa a matriz de transformação."
type: docs
weight: 2910
url: /pt/java/com.aspose.pdf/matrix3d/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix3D

```
public final class Matrix3D extends Object
```

Classe que representa a matriz de transformação.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Matrix3D](#Matrix3D--) | <p> Construtor cria matriz padrão 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |
| [Matrix3D](#Matrix3D-double:A-) | <p> Construtor aceita uma matriz com a seguinte representação em array: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre> |
| [Matrix3D](#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-) | <p> Inicializa a matriz de transformação com os coeficientes especificados. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix3D](#Matrix3D-com.aspose.pdf.Matrix3D-) | <p> Construtor cria matriz padrão 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix3D-) | <p> Adiciona matriz a outra matriz. </p> <hr> |
| [equals](#equals-java.lang.Object-) | Compara a matriz com outro objeto. |
| [getA](#getA--) | Um membro da matriz de transformação. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Traduz rotação em ângulo (graus) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | Membro B da matriz de transformação. |
| [getC](#getC--) | Membro C da matriz de transformação. |
| [getD](#getD--) | Membro D da matriz de transformação. |
| [getE](#getE--) | Membro E da matriz de transformação. |
| [getF](#getF--) | Membro F da matriz de transformação. |
| [getG](#getG--) | Membro G da matriz de transformação. |
| [getH](#getH--) | Membro H da matriz de transformação. |
| [getI](#getI--) | Membro I da matriz de transformação. |
| [getTx](#getTx--) | Membro Tx da matriz de transformação. |
| [getTy](#getTy--) | Membro Ty da matriz de transformação. |
| [getTz](#getTz--) | Membro Tz da matriz de transformação. |
| [hashCode](#hashCode--) | <p> Código hash do objeto. </p> <hr> |
| [setA](#setA-double-) | Um membro da matriz de transformação. |
| [setB](#setB-double-) | Membro B da matriz de transformação. |
| [setC](#setC-double-) | Membro C da matriz de transformação. |
| [setD](#setD-double-) | Membro D da matriz de transformação. |
| [setE](#setE-double-) | Membro E da matriz de transformação. |
| [setF](#setF-double-) | Membro F da matriz de transformação. |
| [setG](#setG-double-) | Membro G da matriz de transformação. |
| [setH](#setH-double-) | Membro H da matriz de transformação. |
| [setI](#setI-double-) | Membro I da matriz de transformação. |
| [setTx](#setTx-double-) | Membro Tx da matriz de transformação. |
| [setTy](#setTy-double-) | Membro Ty da matriz de transformação. |
| [setTz](#setTz-double-) | Membro Tz da matriz de transformação. |
| [toString](#toString--) | Retorna a representação textual da matriz. |

### Matrix3D {#Matrix3D--}
```
public Matrix3D()
```

<p> Construtor cria matriz padrão 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### Matrix3D {#Matrix3D-double:A-}
```
public Matrix3D(double[] matrix3DArray)
```

<p> Construtor aceita uma matriz com a seguinte representação em array: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| matrix3DArray |  | Array de dados da matriz. |

### Matrix3D {#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
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
| g |  | Valor da matriz G. |
| h |  | Valor da matriz H. |
| i |  | Valor da matriz I. |
| tx |  | Valor da matriz TX. |
| ty |  | Valor da matriz TX. |
| tz |  | Valor da matriz TY. |

### Matrix3D {#Matrix3D-com.aspose.pdf.Matrix3D-}
<p> Construtor cria matriz padrão 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### add {#add-com.aspose.pdf.Matrix3D-}
<p> Adiciona matriz a outra matriz. </p> <hr>

### equals {#equals-java.lang.Object-}
Compara a matriz com outro objeto.

### getA {#getA--}
```
public double getA()
```

Um membro da matriz de transformação.

**Returns:**
valor double

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Traduz rotação em ângulo (graus) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

Membro B da matriz de transformação.

**Returns:**
valor double

### getC {#getC--}
```
public double getC()
```

Membro C da matriz de transformação.

**Returns:**
valor double

### getD {#getD--}
```
public double getD()
```

Membro D da matriz de transformação.

**Returns:**
valor double

### getE {#getE--}
```
public double getE()
```

Membro E da matriz de transformação.

**Returns:**
valor double

### getF {#getF--}
```
public double getF()
```

Membro F da matriz de transformação.

**Returns:**
valor double

### getG {#getG--}
```
public double getG()
```

Membro G da matriz de transformação.

**Returns:**
valor double

### getH {#getH--}
```
public double getH()
```

Membro H da matriz de transformação.

**Returns:**
valor double

### getI {#getI--}
```
public double getI()
```

Membro I da matriz de transformação.

**Returns:**
valor double

### getTx {#getTx--}
```
public double getTx()
```

Membro Tx da matriz de transformação.

**Returns:**
valor double

### getTy {#getTy--}
```
public double getTy()
```

Membro Ty da matriz de transformação.

**Returns:**
valor double

### getTz {#getTz--}
```
public double getTz()
```

Membro Tz da matriz de transformação.

**Returns:**
valor double

### hashCode {#hashCode--}
```
public int hashCode()
```

<p> Código hash do objeto. </p> <hr>

**Returns:**
Código hash.

### setA {#setA-double-}
```
public void setA(double value)
```

Um membro da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setB {#setB-double-}
```
public void setB(double value)
```

Membro B da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setC {#setC-double-}
```
public void setC(double value)
```

Membro C da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setD {#setD-double-}
```
public void setD(double value)
```

Membro D da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setE {#setE-double-}
```
public void setE(double value)
```

Membro E da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setF {#setF-double-}
```
public void setF(double value)
```

Membro F da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setG {#setG-double-}
```
public void setG(double value)
```

Membro G da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setH {#setH-double-}
```
public void setH(double value)
```

Membro H da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setI {#setI-double-}
```
public void setI(double value)
```

Membro I da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setTx {#setTx-double-}
```
public void setTx(double value)
```

Membro Tx da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setTy {#setTy-double-}
```
public void setTy(double value)
```

Membro Ty da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### setTz {#setTz-double-}
```
public void setTz(double value)
```

Membro Tz da matriz de transformação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |

### toString {#toString--}
```
public String toString()
```

Retorna a representação textual da matriz.

**Returns:**
Representação em string da matriz
