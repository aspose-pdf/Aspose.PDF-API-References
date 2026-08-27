---
title: "Matrice"
linktitle: "Matrice"
second_title: "Riferimento API Aspose.PDF per Java"
description: "La classe rappresenta la matrice di trasformazione."
type: docs
weight: 2900
url: /it/java/com.aspose.pdf/matrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix

```
public final class Matrix extends Object
```

La classe rappresenta la matrice di trasformazione.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Matrix](#Matrix--) | <p> Il costruttore crea una matrice standard 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-double:A-) | <p> Il costruttore accetta una matrice con la seguente rappresentazione di array: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-double-double-double-double-double-double-) | <p> Inizializza la matrice di trasformazione con i coefficienti specificati. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix](#Matrix-float:A-) | <p> Il costruttore accetta una matrice con la seguente rappresentazione di array: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-com.aspose.pdf.Matrix-) | <p> Il costruttore crea una matrice standard 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-) | <p> Il costruttore crea una matrice standard 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix-) | Aggiunge una matrice a un'altra matrice. |
| [equals](#equals-java.lang.Object-) | Confronta la matrice con un altro oggetto. |
| [getA](#getA--) | Ottieni il membro A della matrice di trasformazione. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Trasforma la rotazione in angolo (gradi) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | Ottieni il membro B della matrice di trasformazione. |
| [getC](#getC--) | Ottieni il membro C della matrice di trasformazione. |
| [getD](#getD--) | Ottieni il membro D della matrice di trasformazione. |
| [getData](#getData--) | Ottiene i dati della Matrix come array. |
| [getE](#getE--) | Ottieni il membro E della Matrix di trasformazione. |
| [getElements](#getElements--) | Elementi della Matrix. |
| [getF](#getF--) | Ottieni il membro F della Matrix di trasformazione. |
| [getFlipMatrix](#getFlipMatrix--) | Ottiene la Matrix di ribaltamento. |
| [getMatrix](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | Converte la Matrix in un oggetto array PDF. |
| [hashCode](#hashCode--) | Hash-code per l'oggetto. |
| [isIdentity](#isIdentity--) | Verifica se questa Matrix è identità. |
| [isInt16](#isInt16-double-) | Solo per uso interno |
| [isInt16Values](#isInt16Values--) | Solo per uso interno |
| [multiply](#multiply-com.aspose.pdf.Matrix-) | <p> Moltiplica la Matrix per un'altra Matrix. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre> |
| [reverse](#reverse--) | <p> Calcola la Matrix inversa. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre> |
| [rotation](#rotation-double-) | <p> Crea una Matrix per l'angolo di rotazione fornito. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre> |
| [rotation](#rotation-com.aspose.pdf.Rotation-) | Crea una Matrix per la rotazione fornita. |
| [scale](#scale-double-double-) | <p> Crea una Matrix per la scala fornita. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre> |
| [scale](#scale-double-double-double:A-double:A-) | Scala x e y con la Matrix usando la seguente formula: x1 = A*x + C*y; y1 = B*x + D*y; |
| [scale](#scale-double-double-com.aspose.pdf.Matrix-) | Applica la scalatura alla Matrix fornita. |
| [setA](#setA-double-) | Imposta il membro A della Matrix di trasformazione. |
| [setB](#setB-double-) | Imposta il membro B della Matrix di trasformazione. |
| [setC](#setC-double-) | Imposta il membro C della Matrix di trasformazione. |
| [setD](#setD-double-) | Imposta il membro D della Matrix di trasformazione. |
| [setE](#setE-double-) | Imposta il membro E della Matrix di trasformazione. |
| [setF](#setF-double-) | Imposta il membro F della Matrix di trasformazione. |
| [skew](#skew-double-double-) | Crea una Matrix per l'angolo di rotazione fornito. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2); |
| [toString](#toString--) | Restituisce la rappresentazione testuale della Matrix. |
| [transform](#transform-double-double-double:A-double:A-) | Trasforma le coordinate usando questa Matrix. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1); |
| [transform](#transform-com.aspose.pdf.Point-) | Trasforma il punto usando questa Matrix. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p); |
| [transform](#transform-com.aspose.pdf.Rectangle-) | Trasforma il rettangolo. |
| [translate](#translate-double-double-com.aspose.pdf.Matrix-) | Trasla una matrice della quantità specificata nelle direzioni x e y. |
| [unScale](#unScale-double-double-double:A-double:A-) | Scala indietro x1 e y1 e restituisce x e y prima della trasformazione della matrice usando la seguente formula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [unTransform](#unTransform-double-double-double:A-double:A-) | Trasforma indietro x1 e y1 e restituisce x e y prima della trasformazione della matrice usando la seguente formula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |

### Matrix {#Matrix--}
```
public Matrix()
```

<p> Il costruttore crea una matrice standard 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-double:A-}
```
public Matrix(double[] matrixArray)
```

<p> Il costruttore accetta una matrice con la seguente rappresentazione di array: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrixArray |  | Array di dati della matrice. |

### Matrix {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
```

<p> Inizializza la matrice di trasformazione con i coefficienti specificati. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a |  | Valore della matrice A. |
| b |  | Valore della matrice B. |
| c |  | Valore della matrice C. |
| d |  | Valore della matrice D. |
| e |  | Valore della matrice E. |
| f |  | Valore della matrice F. |

### Matrix {#Matrix-float:A-}
```
public Matrix(float[] matrixArray)
```

<p> Il costruttore accetta una matrice con la seguente rappresentazione di array: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrixArray |  | Array di dati della matrice. |

### Matrix {#Matrix-com.aspose.pdf.Matrix-}
<p> Il costruttore crea una matrice standard 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-}
<p> Il costruttore crea una matrice standard 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### add {#add-com.aspose.pdf.Matrix-}
Aggiunge una matrice a un'altra matrice.

### equals {#equals-java.lang.Object-}
Confronta la matrice con un altro oggetto.

### getA {#getA--}
```
public double getA()
```

Ottieni il membro A della matrice di trasformazione.

**Returns:**
valore double

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Trasforma la rotazione in angolo (gradi) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

Ottieni il membro B della matrice di trasformazione.

**Returns:**
valore double

### getC {#getC--}
```
public double getC()
```

Ottieni il membro C della matrice di trasformazione.

**Returns:**
valore double

### getD {#getD--}
```
public double getD()
```

Ottieni il membro D della matrice di trasformazione.

**Returns:**
valore double

### getData {#getData--}
```
public final double[] getData()
```

Ottiene i dati della Matrix come array.

**Returns:**
array di valori double

### getE {#getE--}
```
public double getE()
```

Ottieni il membro E della Matrix di trasformazione.

**Returns:**
valore double

### getElements {#getElements--}
```
public float[] getElements()
```

Elementi della Matrix.

**Returns:**
float[] array

### getF {#getF--}
```
public double getF()
```

Ottieni il membro F della Matrix di trasformazione.

**Returns:**
valore double

### getFlipMatrix {#getFlipMatrix--}
```
public final Matrix getFlipMatrix()
```

Ottiene la Matrix di ribaltamento.

**Returns:**
Istanza della matrice

### getMatrix {#getMatrix-com.aspose.pdf.engine.data.ITrailerable-}
Converte la Matrix in un oggetto array PDF.

### hashCode {#hashCode--}
```
public int hashCode()
```

Hash-code per l'oggetto.

**Returns:**
Hash-code.

### isIdentity {#isIdentity--}
```
public final boolean isIdentity()
```

Verifica se questa Matrix è identità.

**Returns:**
valore booleano

### isInt16 {#isInt16-double-}
```
public static boolean isInt16(double value)
```

Solo per uso interno

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

**Returns:**
valore booleano

### isInt16Values {#isInt16Values--}
```
public boolean isInt16Values()
```

Solo per uso interno

**Returns:**
valore booleano

### multiply {#multiply-com.aspose.pdf.Matrix-}
<p> Moltiplica la Matrix per un'altra Matrix. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre>

### reverse {#reverse--}
```
public Matrix reverse()
```

<p> Calcola la Matrix inversa. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre>

**Returns:**
Matrice inversa.

### rotation {#rotation-double-}
```
public static Matrix rotation(double alpha)
```

<p> Crea una Matrix per l'angolo di rotazione fornito. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha |  | Angolo di rotazione in radianti. |

**Returns:**
Matrice di trasformazione.

### rotation {#rotation-com.aspose.pdf.Rotation-}
Crea una Matrix per la rotazione fornita.

### scale {#scale-double-double-}
```
public static Matrix scale(double x, double y)
```

<p> Crea una Matrix per la scala fornita. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x |  | Scala x. |
| y |  | Scala y. |

**Returns:**
Matrice di trasformazione.

### scale {#scale-double-double-double:A-double:A-}
```
public final void scale(double x, double y, double[] x1, double[] y1)
```

Scala x e y con la Matrix usando la seguente formula: x1 = A*x + C*y; y1 = B*x + D*y;

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x |  | Coordinata X di ingresso |
| y |  | Coordinata Y di ingresso |
| x1 |  | Coordinata X di uscita |
| y1 |  | Coordinata Y di output |

### scale {#scale-double-double-com.aspose.pdf.Matrix-}
Applica la scalatura alla Matrix fornita.

### setA {#setA-double-}
```
public void setA(double value)
```

Imposta il membro A della Matrix di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setB {#setB-double-}
```
public void setB(double value)
```

Imposta il membro B della Matrix di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setC {#setC-double-}
```
public void setC(double value)
```

Imposta il membro C della Matrix di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setD {#setD-double-}
```
public void setD(double value)
```

Imposta il membro D della Matrix di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setE {#setE-double-}
```
public void setE(double value)
```

Imposta il membro E della Matrix di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setF {#setF-double-}
```
public void setF(double value)
```

Imposta il membro F della Matrix di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### skew {#skew-double-double-}
```
public static Matrix skew(double alpha, double beta)
```

Crea una Matrix per l'angolo di rotazione fornito. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha |  | Angolo di inclinazione x in radianti. |
| beta |  | Angolo di inclinazione y in radianti. |

**Returns:**
Matrice di trasformazione.

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione testuale della Matrix.

**Returns:**
Rappresentazione stringa della matrice

### transform {#transform-double-double-double:A-double:A-}
```
public final void transform(double x, double y, double[] x1, double[] y1)
```

Trasforma le coordinate usando questa Matrix. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1);

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x |  | Coordinata X. |
| y |  | Coordinata Y. |
| x1 |  | Coordinata X trasformata. |
| y1 |  | Coordinata Y trasformata. |

### transform {#transform-com.aspose.pdf.Point-}
Trasforma il punto usando questa Matrix. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p);

### transform {#transform-com.aspose.pdf.Rectangle-}
Trasforma il rettangolo.

### translate {#translate-double-double-com.aspose.pdf.Matrix-}
Trasla una matrice della quantità specificata nelle direzioni x e y.

### unScale {#unScale-double-double-double:A-double:A-}
```
public final void unScale(double x1, double y1, double[] x, double[] y)
```

Scala indietro x1 e y1 e restituisce x e y prima della trasformazione della matrice usando la seguente formula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 |  | Coordinata X di ingresso |
| y1 |  | Coordinata Y di ingresso |
| x |  | Coordinata X di uscita |
| y |  | Coordinata Y di output |

### unTransform {#unTransform-double-double-double:A-double:A-}
```
public final void unTransform(double x1, double y1, double[] x, double[] y)
```

Trasforma indietro x1 e y1 e restituisce x e y prima della trasformazione della matrice usando la seguente formula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x1 |  | Coordinata X di ingresso |
| y1 |  | Coordinata Y di ingresso |
| x |  | Coordinata X di uscita |
| y |  | Coordinata Y di output |
