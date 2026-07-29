---
title: "Matrix3D"
linktitle: "Matrix3D"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "La classe représente une matrice de transformation."
type: docs
weight: 2910
url: /fr/java/com.aspose.pdf/matrix3d/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix3D

```
public final class Matrix3D extends Object
```

La classe représente une matrice de transformation.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Matrix3D](#Matrix3D--) | <p> Le constructeur crée une matrice standard 1 à 1 : [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |
| [Matrix3D](#Matrix3D-double:A-) | <p> Le constructeur accepte une matrice avec la représentation de tableau suivante : [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre> |
| [Matrix3D](#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-) | Ajoute une matrice à une autre matrice. |
| [Matrix3D](#Matrix3D-com.aspose.pdf.Matrix3D-) | <p> Le constructeur crée une matrice standard 1 à 1 : [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix3D-) | <p> Ajoute une matrice à une autre matrice. </p> <hr> |
| [equals](#equals-java.lang.Object-) | Compare la matrice avec un autre objet. |
| [getA](#getA--) | Un membre de la matrice de transformation. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Convertit la rotation en angle (degrés) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | Membre B de la matrice de transformation. |
| [getC](#getC--) | Membre C de la matrice de transformation. |
| [getD](#getD--) | Membre D de la matrice de transformation. |
| [getE](#getE--) | Membre E de la matrice de transformation. |
| [getF](#getF--) | Membre F de la matrice de transformation. |
| [getG](#getG--) | Membre G de la matrice de transformation. |
| [getH](#getH--) | Membre H de la matrice de transformation. |
| [getI](#getI--) | Membre I de la matrice de transformation. |
| [getTx](#getTx--) | Membre Tx de la matrice de transformation. |
| [getTy](#getTy--) | Membre Ty de la matrice de transformation. |
| [getTz](#getTz--) | Membre Tz de la matrice de transformation. |
| [hashCode](#hashCode--) | <p> Code de hachage pour l'objet. </p> <hr> |
| [setA](#setA-double-) | Un membre de la matrice de transformation. |
| [setB](#setB-double-) | Membre B de la matrice de transformation. |
| [setC](#setC-double-) | Membre C de la matrice de transformation. |
| [setD](#setD-double-) | Membre D de la matrice de transformation. |
| [setE](#setE-double-) | Membre E de la matrice de transformation. |
| [setF](#setF-double-) | Membre F de la matrice de transformation. |
| [setG](#setG-double-) | Membre G de la matrice de transformation. |
| [setH](#setH-double-) | Membre H de la matrice de transformation. |
| [setI](#setI-double-) | Membre I de la matrice de transformation. |
| [setTx](#setTx-double-) | Membre Tx de la matrice de transformation. |
| [setTy](#setTy-double-) | Membre Ty de la matrice de transformation. |
| [setTz](#setTz-double-) | Membre Tz de la matrice de transformation. |
| [toString](#toString--) | Renvoie la représentation textuelle de la matrice. |

### Matrix3D {#Matrix3D--}
```
public Matrix3D()
```

<p> Le constructeur crée une matrice standard 1 à 1 : [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### Matrix3D {#Matrix3D-double:A-}
```
public Matrix3D(double[] matrix3DArray)
```

<p> Le constructeur accepte une matrice avec la représentation de tableau suivante : [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrix3DArray |  | Tableau de données de la matrice. |

### Matrix3D {#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
```

Ajoute une matrice à une autre matrice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a |  | Une valeur de matrice. |
| b |  | Valeur de la matrice B. |
| c |  | Valeur de la matrice C. |
| d |  | Valeur de la matrice D. |
| e |  | Valeur de la matrice E. |
| f |  | Valeur de la matrice F. |
| g |  | Valeur de la matrice G. |
| h |  | Valeur de la matrice H. |
| i |  | Valeur de la matrice I. |
| tx |  | Valeur de la matrice TX. |
| ty |  | Valeur de la matrice TX. |
| tz |  | Valeur de la matrice TY. |

### Matrix3D {#Matrix3D-com.aspose.pdf.Matrix3D-}
<p> Le constructeur crée une matrice standard 1 à 1 : [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### add {#add-com.aspose.pdf.Matrix3D-}
<p> Ajoute une matrice à une autre matrice. </p> <hr>

### equals {#equals-java.lang.Object-}
Compare la matrice avec un autre objet.

### getA {#getA--}
```
public double getA()
```

Un membre de la matrice de transformation.

**Returns:**
valeur double

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Convertit la rotation en angle (degrés) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

Membre B de la matrice de transformation.

**Returns:**
valeur double

### getC {#getC--}
```
public double getC()
```

Membre C de la matrice de transformation.

**Returns:**
valeur double

### getD {#getD--}
```
public double getD()
```

Membre D de la matrice de transformation.

**Returns:**
valeur double

### getE {#getE--}
```
public double getE()
```

Membre E de la matrice de transformation.

**Returns:**
valeur double

### getF {#getF--}
```
public double getF()
```

Membre F de la matrice de transformation.

**Returns:**
valeur double

### getG {#getG--}
```
public double getG()
```

Membre G de la matrice de transformation.

**Returns:**
valeur double

### getH {#getH--}
```
public double getH()
```

Membre H de la matrice de transformation.

**Returns:**
valeur double

### getI {#getI--}
```
public double getI()
```

Membre I de la matrice de transformation.

**Returns:**
valeur double

### getTx {#getTx--}
```
public double getTx()
```

Membre Tx de la matrice de transformation.

**Returns:**
valeur double

### getTy {#getTy--}
```
public double getTy()
```

Membre Ty de la matrice de transformation.

**Returns:**
valeur double

### getTz {#getTz--}
```
public double getTz()
```

Membre Tz de la matrice de transformation.

**Returns:**
valeur double

### hashCode {#hashCode--}
```
public int hashCode()
```

<p> Code de hachage pour l'objet. </p> <hr>

**Returns:**
Code de hachage.

### setA {#setA-double-}
```
public void setA(double value)
```

Un membre de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setB {#setB-double-}
```
public void setB(double value)
```

Membre B de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setC {#setC-double-}
```
public void setC(double value)
```

Membre C de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setD {#setD-double-}
```
public void setD(double value)
```

Membre D de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setE {#setE-double-}
```
public void setE(double value)
```

Membre E de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setF {#setF-double-}
```
public void setF(double value)
```

Membre F de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setG {#setG-double-}
```
public void setG(double value)
```

Membre G de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setH {#setH-double-}
```
public void setH(double value)
```

Membre H de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setI {#setI-double-}
```
public void setI(double value)
```

Membre I de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setTx {#setTx-double-}
```
public void setTx(double value)
```

Membre Tx de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setTy {#setTy-double-}
```
public void setTy(double value)
```

Membre Ty de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setTz {#setTz-double-}
```
public void setTz(double value)
```

Membre Tz de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation textuelle de la matrice.

**Returns:**
Représentation sous forme de chaîne de la matrice
