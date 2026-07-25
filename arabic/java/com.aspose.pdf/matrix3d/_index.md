---
title: "Matrix3D"
linktitle: "Matrix3D"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة تمثل مصفوفة التحويل."
type: docs
weight: 2910
url: /ar/java/com.aspose.pdf/matrix3d/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix3D

```
public final class Matrix3D extends Object
```

الفئة تمثل مصفوفة التحويل.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Matrix3D](#Matrix3D--) | <p> المُنشئ ينشئ مصفوفة قياسية 1 إلى 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |
| [Matrix3D](#Matrix3D-double:A-) | <p> المُنشئ يقبل مصفوفة بالتمثيل التالي: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre> |
| [Matrix3D](#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-) | <p> يهيئ مصفوفة التحويل بالمعاملات المحددة. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix3D](#Matrix3D-com.aspose.pdf.Matrix3D-) | <p> المُنشئ ينشئ مصفوفة قياسية 1 إلى 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix3D-) | <p> يضيف المصفوفة إلى مصفوفة أخرى. </p> <hr> |
| [equals](#equals-java.lang.Object-) | يقارن المصفوفة مع كائن آخر. |
| [getA](#getA--) | عضو في مصفوفة التحويل. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> يحوّل الدوران إلى زاوية (بالدرجات) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | عضو B في مصفوفة التحويل. |
| [getC](#getC--) | عضو C في مصفوفة التحويل. |
| [getD](#getD--) | عضو D في مصفوفة التحويل. |
| [getE](#getE--) | عضو E في مصفوفة التحويل. |
| [getF](#getF--) | عضو F في مصفوفة التحويل. |
| [getG](#getG--) | عضو G في مصفوفة التحويل. |
| [getH](#getH--) | عضو H في مصفوفة التحويل. |
| [getI](#getI--) | عضو I في مصفوفة التحويل. |
| [getTx](#getTx--) | عضو Tx في مصفوفة التحويل. |
| [getTy](#getTy--) | عضو Ty في مصفوفة التحويل. |
| [getTz](#getTz--) | عضو Tz في مصفوفة التحويل. |
| [hashCode](#hashCode--) | <p> رمز التجزئة للكائن. </p> <hr> |
| [setA](#setA-double-) | عضو في مصفوفة التحويل. |
| [setB](#setB-double-) | عضو B في مصفوفة التحويل. |
| [setC](#setC-double-) | عضو C في مصفوفة التحويل. |
| [setD](#setD-double-) | عضو D في مصفوفة التحويل. |
| [setE](#setE-double-) | عضو E في مصفوفة التحويل. |
| [setF](#setF-double-) | عضو F في مصفوفة التحويل. |
| [setG](#setG-double-) | عضو G في مصفوفة التحويل. |
| [setH](#setH-double-) | عضو H في مصفوفة التحويل. |
| [setI](#setI-double-) | عضو I في مصفوفة التحويل. |
| [setTx](#setTx-double-) | عضو Tx في مصفوفة التحويل. |
| [setTy](#setTy-double-) | عضو Ty في مصفوفة التحويل. |
| [setTz](#setTz-double-) | عضو Tz في مصفوفة التحويل. |
| [toString](#toString--) | يعيد تمثيل النص للمصفوفة. |

### Matrix3D {#Matrix3D--}
```
public Matrix3D()
```

<p> المُنشئ ينشئ مصفوفة قياسية 1 إلى 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### Matrix3D {#Matrix3D-double:A-}
```
public Matrix3D(double[] matrix3DArray)
```

<p> المُنشئ يقبل مصفوفة بالتمثيل التالي: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix3DArray |  | مصفوفة بيانات المصفوفة. |

### Matrix3D {#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
```

<p> يهيئ مصفوفة التحويل بالمعاملات المحددة. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a |  | قيمة المصفوفة A. |
| b |  | قيمة المصفوفة B. |
| c |  | قيمة المصفوفة C. |
| d |  | قيمة المصفوفة D. |
| e |  | قيمة المصفوفة E. |
| f |  | قيمة المصفوفة F. |
| g |  | قيمة مصفوفة G. |
| h |  | قيمة مصفوفة H. |
| i |  | قيمة مصفوفة I. |
| tx |  | قيمة مصفوفة TX. |
| ty |  | قيمة مصفوفة TX. |
| tz |  | قيمة مصفوفة TY. |

### Matrix3D {#Matrix3D-com.aspose.pdf.Matrix3D-}
<p> المُنشئ ينشئ مصفوفة قياسية 1 إلى 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### add {#add-com.aspose.pdf.Matrix3D-}
<p> يضيف المصفوفة إلى مصفوفة أخرى. </p> <hr>

### equals {#equals-java.lang.Object-}
يقارن المصفوفة مع كائن آخر.

### getA {#getA--}
```
public double getA()
```

عضو في مصفوفة التحويل.

**Returns:**
قيمة double

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> يحوّل الدوران إلى زاوية (بالدرجات) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

عضو B في مصفوفة التحويل.

**Returns:**
قيمة double

### getC {#getC--}
```
public double getC()
```

عضو C في مصفوفة التحويل.

**Returns:**
قيمة double

### getD {#getD--}
```
public double getD()
```

عضو D في مصفوفة التحويل.

**Returns:**
قيمة double

### getE {#getE--}
```
public double getE()
```

عضو E في مصفوفة التحويل.

**Returns:**
قيمة double

### getF {#getF--}
```
public double getF()
```

عضو F في مصفوفة التحويل.

**Returns:**
قيمة double

### getG {#getG--}
```
public double getG()
```

عضو G في مصفوفة التحويل.

**Returns:**
قيمة double

### getH {#getH--}
```
public double getH()
```

عضو H في مصفوفة التحويل.

**Returns:**
قيمة double

### getI {#getI--}
```
public double getI()
```

عضو I في مصفوفة التحويل.

**Returns:**
قيمة double

### getTx {#getTx--}
```
public double getTx()
```

عضو Tx في مصفوفة التحويل.

**Returns:**
قيمة double

### getTy {#getTy--}
```
public double getTy()
```

عضو Ty في مصفوفة التحويل.

**Returns:**
قيمة double

### getTz {#getTz--}
```
public double getTz()
```

عضو Tz في مصفوفة التحويل.

**Returns:**
قيمة double

### hashCode {#hashCode--}
```
public int hashCode()
```

<p> رمز التجزئة للكائن. </p> <hr>

**Returns:**
رمز التجزئة.

### setA {#setA-double-}
```
public void setA(double value)
```

عضو في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setB {#setB-double-}
```
public void setB(double value)
```

عضو B في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setC {#setC-double-}
```
public void setC(double value)
```

عضو C في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setD {#setD-double-}
```
public void setD(double value)
```

عضو D في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setE {#setE-double-}
```
public void setE(double value)
```

عضو E في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setF {#setF-double-}
```
public void setF(double value)
```

عضو F في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setG {#setG-double-}
```
public void setG(double value)
```

عضو G في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setH {#setH-double-}
```
public void setH(double value)
```

عضو H في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setI {#setI-double-}
```
public void setI(double value)
```

عضو I في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setTx {#setTx-double-}
```
public void setTx(double value)
```

عضو Tx في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setTy {#setTy-double-}
```
public void setTy(double value)
```

عضو Ty في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setTz {#setTz-double-}
```
public void setTz(double value)
```

عضو Tz في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### toString {#toString--}
```
public String toString()
```

يعيد تمثيل النص للمصفوفة.

**Returns:**
تمثيل النص للمصفوفة
