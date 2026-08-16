---
title: "Matrix3D"
linktitle: "Matrix3D"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa una matriz de transformación."
type: docs
weight: 2910
url: /es/java/com.aspose.pdf/matrix3d/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix3D

```
public final class Matrix3D extends Object
```

Clase que representa una matriz de transformación.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Matrix3D](#Matrix3D--) | <p> El constructor crea una matriz estándar 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |
| [Matrix3D](#Matrix3D-double:A-) | <p> El constructor acepta una matriz con la siguiente representación de arreglo: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre> |
| [Matrix3D](#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-) | <p> Inicializa la matriz de transformación con los coeficientes especificados. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix3D](#Matrix3D-com.aspose.pdf.Matrix3D-) | <p> El constructor crea una matriz estándar 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix3D-) | <p> Añade una matriz a otra matriz. </p> <hr> |
| [equals](#equals-java.lang.Object-) | Compara la matriz con otro objeto. |
| [getA](#getA--) | A miembro de la matriz de transformación. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Traduce la rotación a ángulo (grados) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | B miembro de la matriz de transformación. |
| [getC](#getC--) | C miembro de la matriz de transformación. |
| [getD](#getD--) | D miembro de la matriz de transformación. |
| [getE](#getE--) | E miembro de la matriz de transformación. |
| [getF](#getF--) | F miembro de la matriz de transformación. |
| [getG](#getG--) | G miembro de la matriz de transformación. |
| [getH](#getH--) | H miembro de la matriz de transformación. |
| [getI](#getI--) | I miembro de la matriz de transformación. |
| [getTx](#getTx--) | Tx miembro de la matriz de transformación. |
| [getTy](#getTy--) | Ty miembro de la matriz de transformación. |
| [getTz](#getTz--) | Tz miembro de la matriz de transformación. |
| [hashCode](#hashCode--) | <p> Código hash del objeto. </p> <hr> |
| [setA](#setA-double-) | A miembro de la matriz de transformación. |
| [setB](#setB-double-) | B miembro de la matriz de transformación. |
| [setC](#setC-double-) | C miembro de la matriz de transformación. |
| [setD](#setD-double-) | D miembro de la matriz de transformación. |
| [setE](#setE-double-) | E miembro de la matriz de transformación. |
| [setF](#setF-double-) | F miembro de la matriz de transformación. |
| [setG](#setG-double-) | G miembro de la matriz de transformación. |
| [setH](#setH-double-) | H miembro de la matriz de transformación. |
| [setI](#setI-double-) | I miembro de la matriz de transformación. |
| [setTx](#setTx-double-) | Tx miembro de la matriz de transformación. |
| [setTy](#setTy-double-) | Ty miembro de la matriz de transformación. |
| [setTz](#setTz-double-) | Tz miembro de la matriz de transformación. |
| [toString](#toString--) | Devuelve la representación textual de la matriz. |

### Matrix3D {#Matrix3D--}
```
public Matrix3D()
```

<p> El constructor crea una matriz estándar 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### Matrix3D {#Matrix3D-double:A-}
```
public Matrix3D(double[] matrix3DArray)
```

<p> El constructor acepta una matriz con la siguiente representación de arreglo: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix3DArray |  | Arreglo de datos de la matriz. |

### Matrix3D {#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
```

<p> Inicializa la matriz de transformación con los coeficientes especificados. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a |  | Un valor de matriz. |
| b |  | Valor de la matriz B. |
| c |  | Valor de la matriz C. |
| d |  | Valor de la matriz D. |
| e |  | Valor de la matriz E. |
| f |  | Valor de la matriz F. |
| g |  | Valor de la matriz G. |
| h |  | Valor de la matriz H. |
| i |  | Valor de la matriz I. |
| tx |  | Valor de la matriz TX. |
| ty |  | Valor de la matriz TX. |
| tz |  | Valor de la matriz TY. |

### Matrix3D {#Matrix3D-com.aspose.pdf.Matrix3D-}
<p> El constructor crea una matriz estándar 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### add {#add-com.aspose.pdf.Matrix3D-}
<p> Añade una matriz a otra matriz. </p> <hr>

### equals {#equals-java.lang.Object-}
Compara la matriz con otro objeto.

### getA {#getA--}
```
public double getA()
```

A miembro de la matriz de transformación.

**Returns:**
valor double

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Traduce la rotación a ángulo (grados) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

B miembro de la matriz de transformación.

**Returns:**
valor double

### getC {#getC--}
```
public double getC()
```

C miembro de la matriz de transformación.

**Returns:**
valor double

### getD {#getD--}
```
public double getD()
```

D miembro de la matriz de transformación.

**Returns:**
valor double

### getE {#getE--}
```
public double getE()
```

E miembro de la matriz de transformación.

**Returns:**
valor double

### getF {#getF--}
```
public double getF()
```

F miembro de la matriz de transformación.

**Returns:**
valor double

### getG {#getG--}
```
public double getG()
```

G miembro de la matriz de transformación.

**Returns:**
valor double

### getH {#getH--}
```
public double getH()
```

H miembro de la matriz de transformación.

**Returns:**
valor double

### getI {#getI--}
```
public double getI()
```

I miembro de la matriz de transformación.

**Returns:**
valor double

### getTx {#getTx--}
```
public double getTx()
```

Tx miembro de la matriz de transformación.

**Returns:**
valor double

### getTy {#getTy--}
```
public double getTy()
```

Ty miembro de la matriz de transformación.

**Returns:**
valor double

### getTz {#getTz--}
```
public double getTz()
```

Tz miembro de la matriz de transformación.

**Returns:**
valor double

### hashCode {#hashCode--}
```
public int hashCode()
```

<p> Código hash del objeto. </p> <hr>

**Returns:**
Código hash.

### setA {#setA-double-}
```
public void setA(double value)
```

A miembro de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setB {#setB-double-}
```
public void setB(double value)
```

B miembro de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setC {#setC-double-}
```
public void setC(double value)
```

C miembro de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setD {#setD-double-}
```
public void setD(double value)
```

D miembro de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setE {#setE-double-}
```
public void setE(double value)
```

E miembro de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setF {#setF-double-}
```
public void setF(double value)
```

F miembro de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setG {#setG-double-}
```
public void setG(double value)
```

G miembro de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setH {#setH-double-}
```
public void setH(double value)
```

H miembro de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setI {#setI-double-}
```
public void setI(double value)
```

I miembro de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setTx {#setTx-double-}
```
public void setTx(double value)
```

Tx miembro de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setTy {#setTy-double-}
```
public void setTy(double value)
```

Ty miembro de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setTz {#setTz-double-}
```
public void setTz(double value)
```

Tz miembro de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### toString {#toString--}
```
public String toString()
```

Devuelve la representación textual de la matriz.

**Returns:**
Representación en cadena de la matriz
