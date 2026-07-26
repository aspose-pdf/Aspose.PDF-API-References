---
title: "Matrix3D"
linktitle: "Matrix3D"
second_title: "Riferimento API Aspose.PDF per Java"
description: "La classe rappresenta la matrice di trasformazione."
type: docs
weight: 2910
url: /it/java/com.aspose.pdf/matrix3d/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix3D

```
public final class Matrix3D extends Object
```

La classe rappresenta la matrice di trasformazione.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Matrix3D](#Matrix3D--) | <p> Il costruttore crea una matrice standard 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |
| [Matrix3D](#Matrix3D-double:A-) | <p> Il costruttore accetta una matrice con la seguente rappresentazione di array: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre> |
| [Matrix3D](#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-) | <p> Inizializza la matrice di trasformazione con i coefficienti specificati. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix3D](#Matrix3D-com.aspose.pdf.Matrix3D-) | <p> Il costruttore crea una matrice standard 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix3D-) | <p> Aggiunge una matrice a un'altra matrice. </p> <hr> |
| [equals](#equals-java.lang.Object-) | Confronta la matrice con un altro oggetto. |
| [getA](#getA--) | Membro A della matrice di trasformazione. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Converte la rotazione in angolo (gradi) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | Membro B della matrice di trasformazione. |
| [getC](#getC--) | Membro C della matrice di trasformazione. |
| [getD](#getD--) | Membro D della matrice di trasformazione. |
| [getE](#getE--) | Membro E della matrice di trasformazione. |
| [getF](#getF--) | Membro F della matrice di trasformazione. |
| [getG](#getG--) | Membro G della matrice di trasformazione. |
| [getH](#getH--) | Membro H della matrice di trasformazione. |
| [getI](#getI--) | Membro I della matrice di trasformazione. |
| [getTx](#getTx--) | Membro Tx della matrice di trasformazione. |
| [getTy](#getTy--) | Membro Ty della matrice di trasformazione. |
| [getTz](#getTz--) | Membro Tz della matrice di trasformazione. |
| [hashCode](#hashCode--) | <p> Hash-code per l'oggetto. </p> <hr> |
| [setA](#setA-double-) | Membro A della matrice di trasformazione. |
| [setB](#setB-double-) | Membro B della matrice di trasformazione. |
| [setC](#setC-double-) | Membro C della matrice di trasformazione. |
| [setD](#setD-double-) | Membro D della matrice di trasformazione. |
| [setE](#setE-double-) | Membro E della matrice di trasformazione. |
| [setF](#setF-double-) | Membro F della matrice di trasformazione. |
| [setG](#setG-double-) | Membro G della matrice di trasformazione. |
| [setH](#setH-double-) | Membro H della matrice di trasformazione. |
| [setI](#setI-double-) | Membro I della matrice di trasformazione. |
| [setTx](#setTx-double-) | Membro Tx della matrice di trasformazione. |
| [setTy](#setTy-double-) | Membro Ty della matrice di trasformazione. |
| [setTz](#setTz-double-) | Membro Tz della matrice di trasformazione. |
| [toString](#toString--) | Restituisce la rappresentazione testuale della Matrix. |

### Matrix3D {#Matrix3D--}
```
public Matrix3D()
```

<p> Il costruttore crea una matrice standard 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### Matrix3D {#Matrix3D-double:A-}
```
public Matrix3D(double[] matrix3DArray)
```

<p> Il costruttore accetta una matrice con la seguente rappresentazione di array: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix3DArray |  | Array di dati della matrice. |

### Matrix3D {#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
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
| g |  | Valore della matrice G. |
| h |  | Valore della matrice H. |
| i |  | Valore della matrice I. |
| tx |  | Valore della matrice TX. |
| ty |  | Valore della matrice TX. |
| tz |  | Valore della matrice TY. |

### Matrix3D {#Matrix3D-com.aspose.pdf.Matrix3D-}
<p> Il costruttore crea una matrice standard 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### add {#add-com.aspose.pdf.Matrix3D-}
<p> Aggiunge una matrice a un'altra matrice. </p> <hr>

### equals {#equals-java.lang.Object-}
Confronta la matrice con un altro oggetto.

### getA {#getA--}
```
public double getA()
```

Membro A della matrice di trasformazione.

**Returns:**
valore double

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Converte la rotazione in angolo (gradi) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

Membro B della matrice di trasformazione.

**Returns:**
valore double

### getC {#getC--}
```
public double getC()
```

Membro C della matrice di trasformazione.

**Returns:**
valore double

### getD {#getD--}
```
public double getD()
```

Membro D della matrice di trasformazione.

**Returns:**
valore double

### getE {#getE--}
```
public double getE()
```

Membro E della matrice di trasformazione.

**Returns:**
valore double

### getF {#getF--}
```
public double getF()
```

Membro F della matrice di trasformazione.

**Returns:**
valore double

### getG {#getG--}
```
public double getG()
```

Membro G della matrice di trasformazione.

**Returns:**
valore double

### getH {#getH--}
```
public double getH()
```

Membro H della matrice di trasformazione.

**Returns:**
valore double

### getI {#getI--}
```
public double getI()
```

Membro I della matrice di trasformazione.

**Returns:**
valore double

### getTx {#getTx--}
```
public double getTx()
```

Membro Tx della matrice di trasformazione.

**Returns:**
valore double

### getTy {#getTy--}
```
public double getTy()
```

Membro Ty della matrice di trasformazione.

**Returns:**
valore double

### getTz {#getTz--}
```
public double getTz()
```

Membro Tz della matrice di trasformazione.

**Returns:**
valore double

### hashCode {#hashCode--}
```
public int hashCode()
```

<p> Hash-code per l'oggetto. </p> <hr>

**Returns:**
Hash-code.

### setA {#setA-double-}
```
public void setA(double value)
```

Membro A della matrice di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setB {#setB-double-}
```
public void setB(double value)
```

Membro B della matrice di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setC {#setC-double-}
```
public void setC(double value)
```

Membro C della matrice di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setD {#setD-double-}
```
public void setD(double value)
```

Membro D della matrice di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setE {#setE-double-}
```
public void setE(double value)
```

Membro E della matrice di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setF {#setF-double-}
```
public void setF(double value)
```

Membro F della matrice di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setG {#setG-double-}
```
public void setG(double value)
```

Membro G della matrice di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setH {#setH-double-}
```
public void setH(double value)
```

Membro H della matrice di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setI {#setI-double-}
```
public void setI(double value)
```

Membro I della matrice di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setTx {#setTx-double-}
```
public void setTx(double value)
```

Membro Tx della matrice di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setTy {#setTy-double-}
```
public void setTy(double value)
```

Membro Ty della matrice di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setTz {#setTz-double-}
```
public void setTz(double value)
```

Membro Tz della matrice di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### toString {#toString--}
```
public String toString()
```

Restituisce la rappresentazione testuale della Matrix.

**Returns:**
Rappresentazione stringa della matrice
