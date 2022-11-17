---
title: Matrix3D
second_title: Aspose.PDF для справки по Java API
description: Класс представляет собой матрицу преобразования.
type: docs
weight: 210
url: /ru/java/com.aspose.pdf/matrix3d/
---
**Наследование:**
java.lang.Object
```
public final class Matrix3D
```

Класс представляет собой матрицу преобразования.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Matrix3D()](#Matrix3D--) |  Конструктор создает стандартную матрицу 1 к 1:[ ABCDEFGHI Tx Ty Tz] =[ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0] |
| [Matrix3D(double[] matrix3DArray)](#Matrix3D-double---) |  Конструктор принимает матрицу со следующим представлением массива:[ ABCDEFGHI Tx Ty Tz] |
| [Matrix3D(Matrix3D matrix)](#Matrix3D-com.aspose.pdf.Matrix3D-) | Конструктор принимает матрицу для создания копии |
| [Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)](#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-) | Преобразует точку, используя эту матрицу. |
## Методы

| Метод | Описание |
| --- | --- |
| [add(Matrix3D other)](#add-com.aspose.pdf.Matrix3D-) | Умножает матрицу на другую матрицу. |
| [equals(Object obj)](#equals-java.lang.Object-) | Сравнивает матрицу с другим объектом. |
| [getA()](#getA--) | Член матрицы преобразования. |
| [getAngle(int rotation)](#getAngle-int-) | Создает матрицу для заданного угла поворота. |
| [getB()](#getB--) | B член матрицы преобразования. |
| [getC()](#getC--) | C член матрицы преобразования. |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | D член матрицы преобразования. |
| [getE()](#getE--) | E член матрицы преобразования. |
| [getF()](#getF--) | F член матрицы преобразования. |
| [getG()](#getG--) | G член матрицы преобразования. |
| [getH()](#getH--) | H член матрицы преобразования. |
| [getI()](#getI--) | Я член матрицы трансформации. |
| [getTx()](#getTx--) | Tx элемент матрицы преобразования. |
| [getTy()](#getTy--) | Ty член матрицы преобразования. |
| [getTz()](#getTz--) | Tz член матрицы преобразования. |
| [hashCode()](#hashCode--) | Вычисляет обратную матрицу. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(double value)](#setA-double-) | Член матрицы преобразования. |
| [setB(double value)](#setB-double-) | B член матрицы преобразования. |
| [setC(double value)](#setC-double-) | C член матрицы преобразования. |
| [setD(double value)](#setD-double-) | D член матрицы преобразования. |
| [setE(double value)](#setE-double-) | E член матрицы преобразования. |
| [setF(double value)](#setF-double-) | F член матрицы преобразования. |
| [setG(double value)](#setG-double-) | G член матрицы преобразования. |
| [setH(double value)](#setH-double-) | H член матрицы преобразования. |
| [setI(double value)](#setI-double-) | Я член матрицы трансформации. |
| [setTx(double value)](#setTx-double-) | Tx элемент матрицы преобразования. |
| [setTy(double value)](#setTy-double-) | Ty член матрицы преобразования. |
| [setTz(double value)](#setTz-double-) | Tz член матрицы преобразования. |
| [toString()](#toString--) | Возвращает текстовое представление матрицы. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix3D() {#Matrix3D--}
```
public Matrix3D()
```


 Конструктор создает стандартную матрицу 1 к 1:[ ABCDEFGHI Tx Ty Tz] =[ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0, 0]

--------------------

```
Matrix3D m = new Matrix3D();
```

### Matrix3D(double[] matrix3DArray) {#Matrix3D-double---}
```
public Matrix3D(double[] matrix3DArray)
```


 Конструктор принимает матрицу со следующим представлением массива:[ ABCDEFGHI Tx Ty Tz]

--------------------

```
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
 Matrix3D m = new Matrix3D(c);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix3DArray | double[] | Массив данных матрицы. |

### Matrix3D(Matrix3D matrix) {#Matrix3D-com.aspose.pdf.Matrix3D-}
```
public Matrix3D(Matrix3D matrix)
```


Конструктор принимает матрицу для создания копии

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix3D](../../com.aspose.pdf/matrix3d) | Объект Matrix3D. |

### Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz) {#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
```


Преобразует точку, используя эту матрицу.

 Преобразует прямоугольник. Если угол не 90\* N градусов, затем возвращается ограничивающий прямоугольник.

Инициализирует матрицу преобразования с указанными коэффициентами.

--------------------

```
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
  Point p = new Point(5, 5);
  Point p1 = m.transform(p);
```

--------------------

```
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
  Rectangle r = new Rectangle(0, 0, 100, 100);
  Rectangle r1 = m.transform(r1);
```

--------------------

```
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | double | Значение матрицы. |
| b | double | Значение матрицы B. |
| c | double | Значение матрицы C. |
| d | double | Значение матрицы D. |
| e | double | Значение матрицы E. |
| f | double | Значение F-матрицы. |
| g | double | Значение матрицы G. |
| h | double | Значение матрицы H. |
| i | double | I значение матрицы. |
| tx | double | Значение матрицы TX. |
| ty | double | Значение матрицы TX. |
| tz | double | Значение матрицы TY. |

### add(Matrix3D other) {#add-com.aspose.pdf.Matrix3D-}
```
public Matrix3D add(Matrix3D other)
```


Умножает матрицу на другую матрицу.

Добавляет матрицу к другой матрице.

--------------------

```
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
  Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
  Matrix c= a.Multiply(b);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [Matrix3D](../../com.aspose.pdf/matrix3d) | Добавляемая матрица. |

**Возвращает:**
[Matrix3D](../../com.aspose.pdf/matrix3d) - Результат добавления матрицы.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Сравнивает матрицу с другим объектом.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения. |

**Возвращает:**
boolean — возвращает true, если другой объект — Matrix3D, и все элементы матрицы равны соответствующим элементам матрицы.
### getA() {#getA--}
```
public double getA()
```


Член матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### getAngle(int rotation) {#getAngle-int-}
```
public static double getAngle(int rotation)
```


Создает матрицу для заданного угла поворота.

Создает матрицу для заданного угла поворота.

Создает матрицу для заданного масштаба.

Переводит вращение в угол (градусы)

--------------------

```
Matrix m = Matrix.Rotation(Math.PI / 2);
```

--------------------

```
Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);
```

--------------------

```
Matrix m = Matrix.scale(x, y);
```

--------------------

```
double angle = Matrix.getAngle(Rotation.on90);
 Matrix m = Matrix.rotation(angle);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rotation | int | Значение вращения. |

**Возвращает:**
double - Значение угла.
### getB() {#getB--}
```
public double getB()
```


B член матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### getC() {#getC--}
```
public double getC()
```


C член матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getD() {#getD--}
```
public double getD()
```


D член матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### getE() {#getE--}
```
public double getE()
```


E член матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### getF() {#getF--}
```
public double getF()
```


F член матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### getG() {#getG--}
```
public double getG()
```


G член матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### getH() {#getH--}
```
public double getH()
```


H член матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### getI() {#getI--}
```
public double getI()
```


Я член матрицы трансформации.

**Возвращает:**
двойное - двойное значение
### getTx() {#getTx--}
```
public double getTx()
```


Tx элемент матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### getTy() {#getTy--}
```
public double getTy()
```


Ty член матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### getTz() {#getTz--}
```
public double getTz()
```


Tz член матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### hashCode() {#hashCode--}
```
public int hashCode()
```


Вычисляет обратную матрицу.

Хэш-код для объекта.

--------------------

```
Matrix m = Matrix.Rotation(Math.PI / 2);
  Matrix m1 = m.reverse();
```

**Возвращает:**
int - Хэш-код.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setA(double value) {#setA-double-}
```
public void setA(double value)
```


Член матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setB(double value) {#setB-double-}
```
public void setB(double value)
```


B член матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setC(double value) {#setC-double-}
```
public void setC(double value)
```


C член матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setD(double value) {#setD-double-}
```
public void setD(double value)
```


D член матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setE(double value) {#setE-double-}
```
public void setE(double value)
```


E член матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setF(double value) {#setF-double-}
```
public void setF(double value)
```


F член матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setG(double value) {#setG-double-}
```
public void setG(double value)
```


G член матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setH(double value) {#setH-double-}
```
public void setH(double value)
```


H член матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setI(double value) {#setI-double-}
```
public void setI(double value)
```


Я член матрицы трансформации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setTx(double value) {#setTx-double-}
```
public void setTx(double value)
```


Tx элемент матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setTy(double value) {#setTy-double-}
```
public void setTy(double value)
```


Ty член матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setTz(double value) {#setTz-double-}
```
public void setTz(double value)
```


Tz член матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### toString() {#toString--}
```
public String toString()
```


Возвращает текстовое представление матрицы.

**Возвращает:**
java.lang.String — строковое представление матрицы
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
