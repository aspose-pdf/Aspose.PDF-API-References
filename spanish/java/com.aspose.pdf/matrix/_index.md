---
title: "Matriz"
linktitle: "Matriz"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa una matriz de transformación."
type: docs
weight: 2900
url: /es/java/com.aspose.pdf/matrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix

```
public final class Matrix extends Object
```

Clase que representa una matriz de transformación.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Matrix](#Matrix--) | <p> El constructor crea una matriz estándar 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-double:A-) | <p> El constructor acepta una matriz con la siguiente representación de arreglo: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-double-double-double-double-double-double-) | <p> Inicializa la matriz de transformación con los coeficientes especificados. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix](#Matrix-float:A-) | <p> El constructor acepta una matriz con la siguiente representación de arreglo: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-com.aspose.pdf.Matrix-) | <p> El constructor crea una matriz estándar 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-) | <p> El constructor crea una matriz estándar 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix-) | Añade una matriz a otra matriz. |
| [equals](#equals-java.lang.Object-) | Compara la matriz con otro objeto. |
| [getA](#getA--) | Obtiene el miembro A de la matriz de transformación. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Traduce la rotación a ángulo (grados) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | Obtiene el miembro B de la matriz de transformación. |
| [getC](#getC--) | Obtiene el miembro C de la matriz de transformación. |
| [getD](#getD--) | Obtiene el miembro D de la matriz de transformación. |
| [getData](#getData--) | Obtiene datos de Matrix como matriz. |
| [getE](#getE--) | Obtiene el miembro E de la matriz de transformación. |
| [getElements](#getElements--) | Elementos de la matriz. |
| [getF](#getF--) | Obtiene el miembro F de la matriz de transformación. |
| [getFlipMatrix](#getFlipMatrix--) | Obtiene la matriz de volteo. |
| [getMatrix](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | Traduce la matriz a un objeto de matriz PDF. |
| [hashCode](#hashCode--) | Código hash para el objeto. |
| [isIdentity](#isIdentity--) | Comprueba si esta matriz es la identidad. |
| [isInt16](#isInt16-double-) | Solo para uso interno |
| [isInt16Values](#isInt16Values--) | Solo para uso interno |
| [multiply](#multiply-com.aspose.pdf.Matrix-) | <p> Multiplica la matriz por otra matriz. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre> |
| [reverse](#reverse--) | <p> Calcula la matriz inversa. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre> |
| [rotation](#rotation-double-) | <p> Crea una matriz para el ángulo de rotación dado. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre> |
| [rotation](#rotation-com.aspose.pdf.Rotation-) | Crea una matriz para la rotación dada. |
| [scale](#scale-double-double-) | <p> Crea una matriz para la escala dada. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre> |
| [scale](#scale-double-double-double:A-double:A-) | Escala x e y con la matriz usando la siguiente fórmula: x1 = A*x + C*y; y1 = B*x + D*y; |
| [scale](#scale-double-double-com.aspose.pdf.Matrix-) | Aplica escalado a la matriz dada. |
| [setA](#setA-double-) | Establece el miembro A de la matriz de transformación. |
| [setB](#setB-double-) | Establece el miembro B de la matriz de transformación. |
| [setC](#setC-double-) | Establece el miembro C de la matriz de transformación. |
| [setD](#setD-double-) | Establece el miembro D de la matriz de transformación. |
| [setE](#setE-double-) | Establece el miembro E de la matriz de transformación. |
| [setF](#setF-double-) | Establece el miembro F de la matriz de transformación. |
| [skew](#skew-double-double-) | Crea una matriz para el ángulo de rotación dado. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2); |
| [toString](#toString--) | Devuelve la representación textual de la matriz. |
| [transform](#transform-double-double-double:A-double:A-) | Transforma coordenadas usando esta matriz. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1); |
| [transform](#transform-com.aspose.pdf.Point-) | Transforma un punto usando esta matriz. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p); |
| [transform](#transform-com.aspose.pdf.Rectangle-) | Transforma el rectángulo. |
| [translate](#translate-double-double-com.aspose.pdf.Matrix-) | Traslada una matriz por la cantidad especificada en la dirección x e y. |
| [unScale](#unScale-double-double-double:A-double:A-) | Escala de nuevo x1 y y1 y devuelve x e y antes de la transformación de la matriz usando la siguiente fórmula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [unTransform](#unTransform-double-double-double:A-double:A-) | Transforma de nuevo x1 y y1 y devuelve x e y antes de la transformación de la matriz usando la siguiente fórmula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |

### Matrix {#Matrix--}
```
public Matrix()
```

<p> El constructor crea una matriz estándar 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-double:A-}
```
public Matrix(double[] matrixArray)
```

<p> El constructor acepta una matriz con la siguiente representación de arreglo: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrixArray |  | Arreglo de datos de la matriz. |

### Matrix {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
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

### Matrix {#Matrix-float:A-}
```
public Matrix(float[] matrixArray)
```

<p> El constructor acepta una matriz con la siguiente representación de arreglo: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrixArray |  | Arreglo de datos de la matriz. |

### Matrix {#Matrix-com.aspose.pdf.Matrix-}
<p> El constructor crea una matriz estándar 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-}
<p> El constructor crea una matriz estándar 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### add {#add-com.aspose.pdf.Matrix-}
Añade una matriz a otra matriz.

### equals {#equals-java.lang.Object-}
Compara la matriz con otro objeto.

### getA {#getA--}
```
public double getA()
```

Obtiene el miembro A de la matriz de transformación.

**Returns:**
valor double

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Traduce la rotación a ángulo (grados) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

Obtiene el miembro B de la matriz de transformación.

**Returns:**
valor double

### getC {#getC--}
```
public double getC()
```

Obtiene el miembro C de la matriz de transformación.

**Returns:**
valor double

### getD {#getD--}
```
public double getD()
```

Obtiene el miembro D de la matriz de transformación.

**Returns:**
valor double

### getData {#getData--}
```
public final double[] getData()
```

Obtiene datos de Matrix como matriz.

**Returns:**
arreglo de valores double

### getE {#getE--}
```
public double getE()
```

Obtiene el miembro E de la matriz de transformación.

**Returns:**
valor double

### getElements {#getElements--}
```
public float[] getElements()
```

Elementos de la matriz.

**Returns:**
float[] array

### getF {#getF--}
```
public double getF()
```

Obtiene el miembro F de la matriz de transformación.

**Returns:**
valor double

### getFlipMatrix {#getFlipMatrix--}
```
public final Matrix getFlipMatrix()
```

Obtiene la matriz de volteo.

**Returns:**
Instancia de matriz

### getMatrix {#getMatrix-com.aspose.pdf.engine.data.ITrailerable-}
Traduce la matriz a un objeto de matriz PDF.

### hashCode {#hashCode--}
```
public int hashCode()
```

Código hash para el objeto.

**Returns:**
Código hash.

### isIdentity {#isIdentity--}
```
public final boolean isIdentity()
```

Comprueba si esta matriz es la identidad.

**Returns:**
valor booleano

### isInt16 {#isInt16-double-}
```
public static boolean isInt16(double value)
```

Solo para uso interno

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

**Returns:**
valor booleano

### isInt16Values {#isInt16Values--}
```
public boolean isInt16Values()
```

Solo para uso interno

**Returns:**
valor booleano

### multiply {#multiply-com.aspose.pdf.Matrix-}
<p> Multiplica la matriz por otra matriz. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre>

### reverse {#reverse--}
```
public Matrix reverse()
```

<p> Calcula la matriz inversa. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre>

**Returns:**
Matriz inversa.

### rotation {#rotation-double-}
```
public static Matrix rotation(double alpha)
```

<p> Crea una matriz para el ángulo de rotación dado. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alpha |  | Ángulo de rotación en radianes. |

**Returns:**
Matriz de transformación.

### rotation {#rotation-com.aspose.pdf.Rotation-}
Crea una matriz para la rotación dada.

### scale {#scale-double-double-}
```
public static Matrix scale(double x, double y)
```

<p> Crea una matriz para la escala dada. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x |  | Escala x. |
| y |  | Escala y. |

**Returns:**
Matriz de transformación.

### scale {#scale-double-double-double:A-double:A-}
```
public final void scale(double x, double y, double[] x1, double[] y1)
```

Escala x e y con la matriz usando la siguiente fórmula: x1 = A*x + C*y; y1 = B*x + D*y;

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x |  | Coordenada X de entrada |
| y |  | Coordenada Y de entrada |
| x1 |  | Coordenada X de salida |
| y1 |  | Coordenada Y de salida |

### scale {#scale-double-double-com.aspose.pdf.Matrix-}
Aplica escalado a la matriz dada.

### setA {#setA-double-}
```
public void setA(double value)
```

Establece el miembro A de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setB {#setB-double-}
```
public void setB(double value)
```

Establece el miembro B de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setC {#setC-double-}
```
public void setC(double value)
```

Establece el miembro C de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setD {#setD-double-}
```
public void setD(double value)
```

Establece el miembro D de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setE {#setE-double-}
```
public void setE(double value)
```

Establece el miembro E de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setF {#setF-double-}
```
public void setF(double value)
```

Establece el miembro F de la matriz de transformación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### skew {#skew-double-double-}
```
public static Matrix skew(double alpha, double beta)
```

Crea una matriz para el ángulo de rotación dado. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alpha |  | Ángulo de sesgo x en radianes. |
| beta |  | Ángulo de sesgo y en radianes. |

**Returns:**
Matriz de transformación.

### toString {#toString--}
```
public String toString()
```

Devuelve la representación textual de la matriz.

**Returns:**
Representación en cadena de la matriz

### transform {#transform-double-double-double:A-double:A-}
```
public final void transform(double x, double y, double[] x1, double[] y1)
```

Transforma coordenadas usando esta matriz. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1);

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x |  | Coordenada X. |
| y |  | Coordenada Y. |
| x1 |  | Coordenada X transformada. |
| y1 |  | Coordenada Y transformada. |

### transform {#transform-com.aspose.pdf.Point-}
Transforma un punto usando esta matriz. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p);

### transform {#transform-com.aspose.pdf.Rectangle-}
Transforma el rectángulo.

### translate {#translate-double-double-com.aspose.pdf.Matrix-}
Traslada una matriz por la cantidad especificada en la dirección x e y.

### unScale {#unScale-double-double-double:A-double:A-}
```
public final void unScale(double x1, double y1, double[] x, double[] y)
```

Escala de nuevo x1 y y1 y devuelve x e y antes de la transformación de la matriz usando la siguiente fórmula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x1 |  | Coordenada X de entrada |
| y1 |  | Coordenada Y de entrada |
| x |  | Coordenada X de salida |
| y |  | Coordenada Y de salida |

### unTransform {#unTransform-double-double-double:A-double:A-}
```
public final void unTransform(double x1, double y1, double[] x, double[] y)
```

Transforma de nuevo x1 y y1 y devuelve x e y antes de la transformación de la matriz usando la siguiente fórmula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x1 |  | Coordenada X de entrada |
| y1 |  | Coordenada Y de entrada |
| x |  | Coordenada X de salida |
| y |  | Coordenada Y de salida |
