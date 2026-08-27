---
title: "مصفوفة"
linktitle: "مصفوفة"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة تمثل مصفوفة التحويل."
type: docs
weight: 2900
url: /ar/java/com.aspose.pdf/matrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix

```
public final class Matrix extends Object
```

الفئة تمثل مصفوفة التحويل.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Matrix](#Matrix--) | <p> ينشئ المنشئ مصفوفة قياسية 1 إلى 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-double:A-) | <p> يقبل المنشئ مصفوفة بالتمثيل الصفري التالي: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-double-double-double-double-double-double-) | <p> يهيئ مصفوفة التحويل بالمعاملات المحددة. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix](#Matrix-float:A-) | <p> يقبل المنشئ مصفوفة بالتمثيل الصفري التالي: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-com.aspose.pdf.Matrix-) | <p> ينشئ المنشئ مصفوفة قياسية 1 إلى 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-) | <p> ينشئ المنشئ مصفوفة قياسية 1 إلى 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix-) | يضيف مصفوفة إلى مصفوفة أخرى. |
| [equals](#equals-java.lang.Object-) | يقارن المصفوفة مع كائن آخر. |
| [getA](#getA--) | احصل على العنصر A من مصفوفة التحويل. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> يحول الدوران إلى زاوية (بالدرجات) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | احصل على العنصر B من مصفوفة التحويل. |
| [getC](#getC--) | احصل على العنصر C من مصفوفة التحويل. |
| [getD](#getD--) | احصل على العنصر D من مصفوفة التحويل. |
| [getData](#getData--) | يحصل على بيانات Matrix كمصفوفة. |
| [getE](#getE--) | احصل على العنصر E من مصفوفة التحويل. |
| [getElements](#getElements--) | عناصر المصفوفة. |
| [getF](#getF--) | احصل على العنصر F من مصفوفة التحويل. |
| [getFlipMatrix](#getFlipMatrix--) | يحصل على مصفوفة الانعكاس. |
| [getMatrix](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | يحوّل Matrix إلى كائن مصفوفة PDF. |
| [hashCode](#hashCode--) | رمز التجزئة للكائن. |
| [isIdentity](#isIdentity--) | يتحقق مما إذا كانت هذه المصفوفة هوية. |
| [isInt16](#isInt16-double-) | للاستخدام الداخلي فقط |
| [isInt16Values](#isInt16Values--) | للاستخدام الداخلي فقط |
| [multiply](#multiply-com.aspose.pdf.Matrix-) | <p> يضرب المصفوفة في مصفوفة أخرى. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre> |
| [reverse](#reverse--) | <p> يحسب المصفوفة العكسية. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre> |
| [rotation](#rotation-double-) | <p> ينشئ مصفوفة لزاوية الدوران المعطاة. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre> |
| [rotation](#rotation-com.aspose.pdf.Rotation-) | ينشئ مصفوفة للدوران المعطى. |
| [scale](#scale-double-double-) | <p> ينشئ مصفوفة للمقياس المعطى. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre> |
| [scale](#scale-double-double-double:A-double:A-) | يقوم بتكبير x و y باستخدام المصفوفة وفق الصيغة التالية: x1 = A*x + C*y; y1 = B*x + D*y; |
| [scale](#scale-double-double-com.aspose.pdf.Matrix-) | يطبق التكبير على المصفوفة المعطاة. |
| [setA](#setA-double-) | عيّن العنصر A في مصفوفة التحويل. |
| [setB](#setB-double-) | عيّن العنصر B في مصفوفة التحويل. |
| [setC](#setC-double-) | عيّن العنصر C في مصفوفة التحويل. |
| [setD](#setD-double-) | عيّن العنصر D في مصفوفة التحويل. |
| [setE](#setE-double-) | عيّن العنصر E في مصفوفة التحويل. |
| [setF](#setF-double-) | عيّن العنصر F في مصفوفة التحويل. |
| [skew](#skew-double-double-) | ينشئ مصفوفة لزاوية الدوران المعطاة. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2); |
| [toString](#toString--) | يعيد تمثيل النص للمصفوفة. |
| [transform](#transform-double-double-double:A-double:A-) | يحوّل الإحداثيات باستخدام هذه المصفوفة. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1); |
| [transform](#transform-com.aspose.pdf.Point-) | يحوّل النقطة باستخدام هذه المصفوفة. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p); |
| [transform](#transform-com.aspose.pdf.Rectangle-) | يحوّل المستطيل. |
| [translate](#translate-double-double-com.aspose.pdf.Matrix-) | يُترجم مصفوفة بالمقدار المحدد في اتجاهي x و y. |
| [unScale](#unScale-double-double-double:A-double:A-) | يعيد تحجيم x1 و y1 ويعيد x و y قبل تحويل المصفوفة باستخدام الصيغة التالية: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [unTransform](#unTransform-double-double-double:A-double:A-) | يعيد تحويل x1 و y1 ويعيد x و y قبل تحويل المصفوفة باستخدام الصيغة التالية: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |

### Matrix {#Matrix--}
```
public Matrix()
```

<p> ينشئ المنشئ مصفوفة قياسية 1 إلى 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-double:A-}
```
public Matrix(double[] matrixArray)
```

<p> يقبل المنشئ مصفوفة بالتمثيل الصفري التالي: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrixArray |  | مصفوفة بيانات المصفوفة. |

### Matrix {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
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

### Matrix {#Matrix-float:A-}
```
public Matrix(float[] matrixArray)
```

<p> يقبل المنشئ مصفوفة بالتمثيل الصفري التالي: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrixArray |  | مصفوفة بيانات المصفوفة. |

### Matrix {#Matrix-com.aspose.pdf.Matrix-}
<p> ينشئ المنشئ مصفوفة قياسية 1 إلى 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-}
<p> ينشئ المنشئ مصفوفة قياسية 1 إلى 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### add {#add-com.aspose.pdf.Matrix-}
يضيف مصفوفة إلى مصفوفة أخرى.

### equals {#equals-java.lang.Object-}
يقارن المصفوفة مع كائن آخر.

### getA {#getA--}
```
public double getA()
```

احصل على العنصر A من مصفوفة التحويل.

**Returns:**
قيمة double

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> يحول الدوران إلى زاوية (بالدرجات) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

احصل على العنصر B من مصفوفة التحويل.

**Returns:**
قيمة double

### getC {#getC--}
```
public double getC()
```

احصل على العنصر C من مصفوفة التحويل.

**Returns:**
قيمة double

### getD {#getD--}
```
public double getD()
```

احصل على العنصر D من مصفوفة التحويل.

**Returns:**
قيمة double

### getData {#getData--}
```
public final double[] getData()
```

يحصل على بيانات Matrix كمصفوفة.

**Returns:**
مصفوفة من قيم double.

### getE {#getE--}
```
public double getE()
```

احصل على العنصر E من مصفوفة التحويل.

**Returns:**
قيمة double

### getElements {#getElements--}
```
public float[] getElements()
```

عناصر المصفوفة.

**Returns:**
مصفوفة float[]

### getF {#getF--}
```
public double getF()
```

احصل على العنصر F من مصفوفة التحويل.

**Returns:**
قيمة double

### getFlipMatrix {#getFlipMatrix--}
```
public final Matrix getFlipMatrix()
```

يحصل على مصفوفة الانعكاس.

**Returns:**
مثيل المصفوفة

### getMatrix {#getMatrix-com.aspose.pdf.engine.data.ITrailerable-}
يحوّل Matrix إلى كائن مصفوفة PDF.

### hashCode {#hashCode--}
```
public int hashCode()
```

رمز التجزئة للكائن.

**Returns:**
رمز التجزئة.

### isIdentity {#isIdentity--}
```
public final boolean isIdentity()
```

يتحقق مما إذا كانت هذه المصفوفة هوية.

**Returns:**
قيمة منطقية

### isInt16 {#isInt16-double-}
```
public static boolean isInt16(double value)
```

للاستخدام الداخلي فقط

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

**Returns:**
قيمة منطقية

### isInt16Values {#isInt16Values--}
```
public boolean isInt16Values()
```

للاستخدام الداخلي فقط

**Returns:**
قيمة منطقية

### multiply {#multiply-com.aspose.pdf.Matrix-}
<p> يضرب المصفوفة في مصفوفة أخرى. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre>

### reverse {#reverse--}
```
public Matrix reverse()
```

<p> يحسب المصفوفة العكسية. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre>

**Returns:**
عكس المصفوفة.

### rotation {#rotation-double-}
```
public static Matrix rotation(double alpha)
```

<p> ينشئ مصفوفة لزاوية الدوران المعطاة. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| alpha |  | زاوية الدوران بالراديان. |

**Returns:**
مصفوفة التحويل.

### rotation {#rotation-com.aspose.pdf.Rotation-}
ينشئ مصفوفة للدوران المعطى.

### scale {#scale-double-double-}
```
public static Matrix scale(double x, double y)
```

<p> ينشئ مصفوفة للمقياس المعطى. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x |  | تحجيم x. |
| y |  | تحجيم y. |

**Returns:**
مصفوفة التحويل.

### scale {#scale-double-double-double:A-double:A-}
```
public final void scale(double x, double y, double[] x1, double[] y1)
```

يقوم بتكبير x و y باستخدام المصفوفة وفق الصيغة التالية: x1 = A*x + C*y; y1 = B*x + D*y;

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x |  | إحداثي X الإدخال |
| y |  | إحداثي Y الإدخال |
| x1 |  | إحداثي X الإخراج |
| y1 |  | إحداثي Y للإخراج |

### scale {#scale-double-double-com.aspose.pdf.Matrix-}
يطبق التكبير على المصفوفة المعطاة.

### setA {#setA-double-}
```
public void setA(double value)
```

عيّن العنصر A في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setB {#setB-double-}
```
public void setB(double value)
```

عيّن العنصر B في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setC {#setC-double-}
```
public void setC(double value)
```

عيّن العنصر C في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setD {#setD-double-}
```
public void setD(double value)
```

عيّن العنصر D في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setE {#setE-double-}
```
public void setE(double value)
```

عيّن العنصر E في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setF {#setF-double-}
```
public void setF(double value)
```

عيّن العنصر F في مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### skew {#skew-double-double-}
```
public static Matrix skew(double alpha, double beta)
```

ينشئ مصفوفة لزاوية الدوران المعطاة. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| alpha |  | زاوية الانحراف x بالراديان. |
| beta |  | زاوية الانحراف y بالراديان. |

**Returns:**
مصفوفة التحويل.

### toString {#toString--}
```
public String toString()
```

يعيد تمثيل النص للمصفوفة.

**Returns:**
تمثيل النص للمصفوفة

### transform {#transform-double-double-double:A-double:A-}
```
public final void transform(double x, double y, double[] x1, double[] y1)
```

يحوّل الإحداثيات باستخدام هذه المصفوفة. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1);

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x |  | إحداثي X. |
| y |  | إحداثي Y. |
| x1 |  | إحداثي X المحوَّل. |
| y1 |  | إحداثي Y المحوَّل. |

### transform {#transform-com.aspose.pdf.Point-}
يحوّل النقطة باستخدام هذه المصفوفة. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p);

### transform {#transform-com.aspose.pdf.Rectangle-}
يحوّل المستطيل.

### translate {#translate-double-double-com.aspose.pdf.Matrix-}
يُترجم مصفوفة بالمقدار المحدد في اتجاهي x و y.

### unScale {#unScale-double-double-double:A-double:A-}
```
public final void unScale(double x1, double y1, double[] x, double[] y)
```

يعيد تحجيم x1 و y1 ويعيد x و y قبل تحويل المصفوفة باستخدام الصيغة التالية: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x1 |  | إحداثي X الإدخال |
| y1 |  | إحداثي Y الإدخال |
| x |  | إحداثي X الإخراج |
| y |  | إحداثي Y للإخراج |

### unTransform {#unTransform-double-double-double:A-double:A-}
```
public final void unTransform(double x1, double y1, double[] x, double[] y)
```

يعيد تحويل x1 و y1 ويعيد x و y قبل تحويل المصفوفة باستخدام الصيغة التالية: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x1 |  | إحداثي X الإدخال |
| y1 |  | إحداثي Y الإدخال |
| x |  | إحداثي X الإخراج |
| y |  | إحداثي Y للإخراج |
