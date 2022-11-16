---
title: Matrix
second_title: Aspose.PDF для справки по Java API
description: Класс представляет собой матрицу преобразования.
type: docs
weight: 209
url: /ru/java/com.aspose.pdf/matrix/
---
**Наследование:**
java.lang.Object
```
public final class Matrix
```

Класс представляет собой матрицу преобразования.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Matrix()](#Matrix--) |  Конструктор создает стандартную матрицу 1 к 1:[ АВСДЕФ] =[ 1, 0, 0, 1, 0, 0] |
| [Matrix(double[] matrixArray)](#Matrix-double---) |  Конструктор принимает матрицу со следующим представлением массива:[ АБВДЕФ] |
| [Matrix(float[] matrixArray)](#Matrix-float---) |  Конструктор принимает матрицу со следующим представлением массива:[ АБВДЕФ] |
| [Matrix(Matrix matrix)](#Matrix-com.aspose.pdf.Matrix-) | Конструктор принимает матрицу для создания копии |
| [Matrix(double a, double b, double c, double d, double e, double f)](#Matrix-double-double-double-double-double-double-) | Инициализирует матрицу преобразования с указанными коэффициентами. |
## Методы

| Метод | Описание |
| --- | --- |
| [add(Matrix other)](#add-com.aspose.pdf.Matrix-) | Добавляет матрицу к другой матрице. |
| [equals(Object obj)](#equals-java.lang.Object-) | Сравнивает матрицу с другим объектом. |
| [getA()](#getA--) | Получить элемент матрицы преобразования. |
| [getAngle(int rotation)](#getAngle-int-) | Преобразует вращение в угол (градусы) |
| [getB()](#getB--) | Получите член B матрицы преобразования. |
| [getC()](#getC--) | Получите член C матрицы преобразования. |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | Получите член D матрицы преобразования. |
| [getData()](#getData--) | Получает данные Matrix в виде массива. |
| [getE()](#getE--) | Получите член E матрицы преобразования. |
| [getElements()](#getElements--) | Элементы матрицы. |
| [getF()](#getF--) | Получите член F матрицы преобразования. |
| [getMatrix(ITrailerable trailer)](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | Преобразует матрицу в объект массива PDF. |
| [hashCode()](#hashCode--) | Хэш-код для объекта. |
| [isInt16(double value)](#isInt16-double-) | Только для внутреннего использования |
| [isInt16Values()](#isInt16Values--) | Только для внутреннего использования |
| [multiply(Matrix other)](#multiply-com.aspose.pdf.Matrix-) | Умножает матрицу на другую матрицу. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reverse()](#reverse--) | Вычисляет обратную матрицу. |
| [rotation(double alpha)](#rotation-double-) | Создает матрицу для заданного угла поворота. |
| [rotation(int rotation)](#rotation-int-) | Создает матрицу для заданного поворота. |
| [scale(double x, double y)](#scale-double-double-) | Создает матрицу для заданного масштаба. |
| [setA(double value)](#setA-double-) | Установите элемент матрицы преобразования. |
| [setB(double value)](#setB-double-) | Установите элемент B матрицы преобразования. |
| [setC(double value)](#setC-double-) | Установите элемент C матрицы преобразования. |
| [setD(double value)](#setD-double-) | Установите член D матрицы преобразования. |
| [setE(double value)](#setE-double-) | Установите член E матрицы преобразования. |
| [setF(double value)](#setF-double-) | Установите член F матрицы преобразования. |
| [skew(double alpha, double beta)](#skew-double-double-) | Создает матрицу для заданного угла поворота. |
| [toString()](#toString--) | Возвращает текстовое представление матрицы. |
| [transform(Point p)](#transform-com.aspose.pdf.Point-) | Преобразует точку, используя эту матрицу. |
| [transform(Rectangle rect)](#transform-com.aspose.pdf.Rectangle-) | Превращает прямоугольник. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


 Конструктор создает стандартную матрицу 1 к 1:[ АВСДЕФ] =[ 1, 0, 0, 1, 0, 0]

--------------------

```
Matrix m = new Matrix();
```

### Matrix(double[] matrixArray) {#Matrix-double---}
```
public Matrix(double[] matrixArray)
```


 Конструктор принимает матрицу со следующим представлением массива:[ АБВДЕФ]

--------------------

```
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
 Matrix m = new Matrix(c);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrixArray | double[] | Массив данных матрицы. |

### Matrix(float[] matrixArray) {#Matrix-float---}
```
public Matrix(float[] matrixArray)
```


 Конструктор принимает матрицу со следующим представлением массива:[ АБВДЕФ]

--------------------

```
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
 Matrix m = new Matrix(c);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrixArray | float[] | Массив данных матрицы. |

### Matrix(Matrix matrix) {#Matrix-com.aspose.pdf.Matrix-}
```
public Matrix(Matrix matrix)
```


Конструктор принимает матрицу для создания копии

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.pdf/matrix) | Матричный объект. |

### Matrix(double a, double b, double c, double d, double e, double f) {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
```


Инициализирует матрицу преобразования с указанными коэффициентами.

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

### add(Matrix other) {#add-com.aspose.pdf.Matrix-}
```
public Matrix add(Matrix other)
```


Добавляет матрицу к другой матрице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [Matrix](../../com.aspose.pdf/matrix) | Добавляемая матрица. |

**Возвращает:**
[Matrix](../../com.aspose.pdf/matrix) - Результат добавления матрицы.
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
boolean — возвращает true, если другой объект — Matrix, и все элементы матрицы равны соответствующим элементам матрицы.
### getA() {#getA--}
```
public double getA()
```


Получить элемент матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### getAngle(int rotation) {#getAngle-int-}
```
public static double getAngle(int rotation)
```


Преобразует вращение в угол (градусы)

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


Получите член B матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### getC() {#getC--}
```
public double getC()
```


Получите член C матрицы преобразования.

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


Получите член D матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### getData() {#getData--}
```
public final double[] getData()
```


Получает данные Matrix в виде массива.

**Возвращает:**
двойной[] - массив двойных значений
### getE() {#getE--}
```
public double getE()
```


Получите член E матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### getElements() {#getElements--}
```
public float[] getElements()
```


Элементы матрицы.

**Возвращает:**
плавать[] - плавать[] множество
### getF() {#getF--}
```
public double getF()
```


Получите член F матрицы преобразования.

**Возвращает:**
двойное - двойное значение
### getMatrix(ITrailerable trailer) {#getMatrix-com.aspose.pdf.engine.data.ITrailerable-}
```
public IPdfArray getMatrix(ITrailerable trailer)
```


Преобразует матрицу в объект массива PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| trailer | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) | Прицепной объект |

**Возвращает:**
[IPdfArray](../../com.aspose.pdf.engine.data/ipdfarray) - Результат преобразования
### hashCode() {#hashCode--}
```
public int hashCode()
```


Хэш-код для объекта.

**Возвращает:**
int - Хэш-код.
### isInt16(double value) {#isInt16-double-}
```
public static boolean isInt16(double value)
```


Только для внутреннего использования

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

**Возвращает:**
boolean - логическое значение
### isInt16Values() {#isInt16Values--}
```
public boolean isInt16Values()
```


Только для внутреннего использования

**Возвращает:**
boolean - логическое значение
### multiply(Matrix other) {#multiply-com.aspose.pdf.Matrix-}
```
public Matrix multiply(Matrix other)
```


Умножает матрицу на другую матрицу.

--------------------

```
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
 Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
 Matrix c= a.multiply(b);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [Matrix](../../com.aspose.pdf/matrix) | Матрица множителей. |

**Возвращает:**
[Matrix](../../com.aspose.pdf/matrix) - Результат умножения.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reverse() {#reverse--}
```
public Matrix reverse()
```


Вычисляет обратную матрицу.

--------------------

```
Matrix m = Matrix.rotation(Math.PI / 2);
 Matrix m1 = m.reverse();
```

**Возвращает:**
[Matrix](../../com.aspose.pdf/matrix) - обратная матрица.
### rotation(double alpha) {#rotation-double-}
```
public static Matrix rotation(double alpha)
```


Создает матрицу для заданного угла поворота.

--------------------

```
Matrix m = Matrix.Rotation(Math.PI / 2);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| alpha | double | Угол поворота в радианах. |

**Возвращает:**
[Matrix](../../com.aspose.pdf/matrix) - Матрица преобразования.
### rotation(int rotation) {#rotation-int-}
```
public static Matrix rotation(int rotation)
```


Создает матрицу для заданного поворота.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rotation | int | Вращение. Допустимые значения: None, on90, on180, on270. |

**Возвращает:**
[Matrix](../../com.aspose.pdf/matrix) - Экземпляр матрицы с поворотом.
### scale(double x, double y) {#scale-double-double-}
```
public static Matrix scale(double x, double y)
```


Создает матрицу для заданного масштаба.

--------------------

```
Matrix m = Matrix.scale(x, y);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | double | Масштаб х. |
| y | double | Масштаб у. |

**Возвращает:**
[Matrix](../../com.aspose.pdf/matrix) - Матрица преобразования.
### setA(double value) {#setA-double-}
```
public void setA(double value)
```


Установите элемент матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setB(double value) {#setB-double-}
```
public void setB(double value)
```


Установите элемент B матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setC(double value) {#setC-double-}
```
public void setC(double value)
```


Установите элемент C матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setD(double value) {#setD-double-}
```
public void setD(double value)
```


Установите член D матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setE(double value) {#setE-double-}
```
public void setE(double value)
```


Установите член E матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setF(double value) {#setF-double-}
```
public void setF(double value)
```


Установите член F матрицы преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### skew(double alpha, double beta) {#skew-double-double-}
```
public static Matrix skew(double alpha, double beta)
```


Создает матрицу для заданного угла поворота.

```
Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| alpha | double | Угол наклона x в радианах. |
| beta | double | Угол наклона y в радианах. |

**Возвращает:**
[Matrix](../../com.aspose.pdf/matrix) - Матрица преобразования.
### toString() {#toString--}
```
public String toString()
```


Возвращает текстовое представление матрицы.

**Возвращает:**
java.lang.String — строковое представление матрицы
### transform(Point p) {#transform-com.aspose.pdf.Point-}
```
public Point transform(Point p)
```


Преобразует точку, используя эту матрицу.

--------------------

```
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
 Point p = new Point(5, 5);
 Point p1 = m.transform(p);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| p | [Point](../../com.aspose.pdf/point) | Точка, которая будет преобразована. |

**Возвращает:**
[Point](../../com.aspose.pdf/point) - Результат трансформации.
### transform(Rectangle rect) {#transform-com.aspose.pdf.Rectangle-}
```
public Rectangle transform(Rectangle rect)
```


 Превращает прямоугольник. Если угол не 90\* N градусов, затем возвращается ограничивающий прямоугольник.

--------------------

```
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
 Rectangle r = new Rectangle(0, 0, 100, 100);
 Rectangle r1 = m.transform(r1);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольник, который нужно преобразовать. |

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Преобразованный прямоугольник.
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
