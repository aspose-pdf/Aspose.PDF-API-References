---
title: Rectangle
second_title: Aspose.PDF для справки по Java API
description: Класс представляет прямоугольник.
type: docs
weight: 300
url: /ru/java/com.aspose.pdf/rectangle/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Comparable, java.lang.Cloneable
```
public final class Rectangle implements Comparable<Object>, Cloneable
```

Класс представляет прямоугольник.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Rectangle(double llx, double lly, double urx, double ury)](#Rectangle-double-double-double-double-) | Конструктор прямоугольника. |
| [Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)](#Rectangle-double-double-double-double-boolean-) | Конструктор прямоугольника. |
## Методы

| Метод | Описание |
| --- | --- |
| [_Intersect(Rectangle otherRect)](#-Intersect-com.aspose.pdf.Rectangle-) | Пересекает прямоугольники. |
| [center()](#center--) | Возвращает координаты центра прямоугольника. |
| [clone()](#clone--) | Клонирует объект Rectangle. |
| [compareTo(Object arg0)](#compareTo-java.lang.Object-) | По сравнению с |
| [contains(Point point)](#contains-com.aspose.pdf.Point-) | Определяет, находится ли заданная точка внутри прямоугольника. |
| [deepClone()](#deepClone--) | Клонирует объект Rectangle. |
| [equals(Object other)](#equals-java.lang.Object-) | Проверьте, равны ли прямоугольники, т.е. имеют ли они одинаковое положение и размеры. |
| [fromRect(Rectangle src)](#fromRect-java.awt.Rectangle-) | Инициализирует новый прямоугольник из заданного экземпляра System.Drawing.Rectangle. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Получает пустой прямоугольник |
| [getHeight()](#getHeight--) | Получить высоту прямоугольника. |
| [getLLX()](#getLLX--) | Получает координату X нижнего левого угла. |
| [getLLY()](#getLLY--) | Получает Y - координату нижнего левого угла. |
| [getTrivial()](#getTrivial--) | Инициализирует простой прямоугольник, т.е. прямоугольник с нулевой позицией и размером. |
| [getURX()](#getURX--) | Получает X - координату правого верхнего угла. |
| [getURY()](#getURY--) | Получает Y - координату правого верхнего угла. |
| [getWidth()](#getWidth--) | Получает ширину прямоугольника. |
| [hashCode()](#hashCode--) | Возвращает значение хэш-кода для объекта. |
| [intersect(Rectangle otherRect)](#intersect-com.aspose.pdf.Rectangle-) | Пересекается с прямоугольниками. |
| [isEmpty()](#isEmpty--) | Проверяет, является ли прямоугольник пустым. |
| [isInclude(Rectangle otherRect, double rotationAngle)](#isInclude-com.aspose.pdf.Rectangle-double-) | Проверяет, что этот прямоугольник включает в себя другой прямоугольник целиком. |
| [isIntersect(Rectangle otherRect)](#isIntersect-com.aspose.pdf.Rectangle-) | Определяет, пересекается ли этот прямоугольник с другим прямоугольником. |
| [isPoint()](#isPoint--) | Проверяет, является ли прямоугольник точкой, т.е. |
| [isTrivial()](#isTrivial--) | Проверяет, является ли прямоугольник тривиальным, т.е. имеет нулевой размер и положение. |
| [join(Rectangle otherRect)](#join-com.aspose.pdf.Rectangle-) | Соединяет прямоугольники. |
| [nearEquals(Rectangle other, double delta)](#nearEquals-com.aspose.pdf.Rectangle-double-) | Проверьте, являются ли прямоугольники почти равными, т.е. имеют ли они примерно одинаковое (с точностью до дельты) положение и размеры. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String value)](#parse-java.lang.String-) | Попробуйте разобрать строку и извлечь из нее компоненты прямоугольника llx, lly, urx, ury. |
| [rotate(int angle)](#rotate-int-) | Повернуть прямоугольник на указанный угол. |
| [rotateAngle(int angle)](#rotateAngle-int-) | Повернуть прямоугольник на указанный угол. |
| [setLLX(double value)](#setLLX-double-) | Устанавливает координату X нижнего левого угла. |
| [setLLY(double value)](#setLLY-double-) | Устанавливает Y - координату нижнего левого угла. |
| [setURX(double value)](#setURX-double-) | Устанавливает X - координату правого верхнего угла. |
| [setURY(double value)](#setURY-double-) | Задает Y - координату правого верхнего угла. |
| [toArray(ITrailerable trailerable)](#toArray-com.aspose.pdf.engine.data.ITrailerable-) |  |
| [toPoints()](#toPoints--) | Преобразует прямоугольник в массив точек ("QuadPoints"). |
| [toRect()](#toRect--) | Преобразует прямоугольник в экземпляр System.Drawing.Rectangle. |
| [toString()](#toString--) | Получает прямоугольное строковое представление. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle(double llx, double lly, double urx, double ury) {#Rectangle-double-double-double-double-}
```
public Rectangle(double llx, double lly, double urx, double ury)
```


Конструктор прямоугольника.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| llx | double | X нижнего левого угла. |
| lly | double | Y нижнего левого угла. |
| urx | double | X правого верхнего угла. |
| ury | double | Y в правом верхнем углу. |

### Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates) {#Rectangle-double-double-double-double-boolean-}
```
public Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)
```


Конструктор прямоугольника.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| llx | double | X нижнего левого угла. |
| lly | double | Y нижнего левого угла. |
| urx | double | X правого верхнего угла. |
| ury | double | Y в правом верхнем углу. |
| normalizeCoordinates | boolean | Нормировать координаты прямоугольника. |

### _Intersect(Rectangle otherRect) {#-Intersect-com.aspose.pdf.Rectangle-}
```
public void _Intersect(Rectangle otherRect)
```


Пересекает прямоугольники. Устаревший метод. Пожалуйста, используйте Intersect вместо этого.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |

### center() {#center--}
```
public Point center()
```


Возвращает координаты центра прямоугольника.

**Возвращает:**
[Point](../../com.aspose.pdf/point) - Точка, являющаяся центром прямоугольника.
### clone() {#clone--}
```
public Object clone()
```


Клонирует объект Rectangle.

**Возвращает:**
java.lang.Object — Клонировать объект.
### compareTo(Object arg0) {#compareTo-java.lang.Object-}
```
public int compareTo(Object arg0)
```


По сравнению с

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object | Объект для сравнения |

**Возвращает:**
интервал - целочисленное значение
### contains(Point point) {#contains-com.aspose.pdf.Point-}
```
public boolean contains(Point point)
```


Определяет, находится ли заданная точка внутри прямоугольника.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.pdf/point) | Точка для проверки. |

**Возвращает:**
boolean — Истинно, если точка находится внутри перехвата.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонирует объект Rectangle.

**Возвращает:**
java.lang.Object — Клонировать объект.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Проверьте, равны ли прямоугольники, т.е. имеют ли они одинаковое положение и размеры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | java.lang.Object | Прямоугольник, который будет сравниваться. |

**Возвращает:**
boolean - True, если прямоугольники равны, иначе false.
### fromRect(Rectangle src) {#fromRect-java.awt.Rectangle-}
```
public static Rectangle fromRect(Rectangle src)
```


Инициализирует новый прямоугольник из заданного экземпляра System.Drawing.Rectangle.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | java.awt.Rectangle | Исходный прямоугольник, положение и размер которого будут установлены в новый прямоугольник. |

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Новый прямоугольник.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Получает пустой прямоугольник

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - новый объект Прямоугольник
### getHeight() {#getHeight--}
```
public double getHeight()
```


Получить высоту прямоугольника.

**Возвращает:**
двойное - двойное значение
### getLLX() {#getLLX--}
```
public double getLLX()
```


Получает координату X нижнего левого угла.

**Возвращает:**
двойное - двойное значение
### getLLY() {#getLLY--}
```
public double getLLY()
```


Получает Y - координату нижнего левого угла.

**Возвращает:**
двойное - двойное значение
### getTrivial() {#getTrivial--}
```
public static Rectangle getTrivial()
```


Инициализирует простой прямоугольник, т.е. прямоугольник с нулевой позицией и размером.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - новый объект Прямоугольник
### getURX() {#getURX--}
```
public double getURX()
```


Получает X - координату правого верхнего угла.

**Возвращает:**
двойное - двойное значение
### getURY() {#getURY--}
```
public double getURY()
```


Получает Y - координату правого верхнего угла.

**Возвращает:**
двойное - двойное значение
### getWidth() {#getWidth--}
```
public double getWidth()
```


Получает ширину прямоугольника.

**Возвращает:**
двойное - двойное значение
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает значение хэш-кода для объекта. Этот метод поддерживается для хеш-таблиц, таких как предоставляемые java.util.HashMap.

Общий контракт hashCode:

 *  Всякий раз, когда он вызывается для одного и того же объекта более одного раза во время выполнения приложения Java, метод hashCode должен постоянно возвращать одно и то же целое число, при условии, что никакая информация, используемая в сравнениях на равенство для объекта, не изменяется. Это целое число не обязательно должно оставаться постоянным от одного выполнения приложения к другому выполнению того же приложения.
 *  Если два объекта равны в соответствии с методом equals(Object), то вызов метода hashCode для каждого из двух объектов должен давать одинаковый целочисленный результат.
 *   это*not* требуется, чтобы, если два объекта не равны в соответствии с java.lang.Object\#equals(java.lang.Object).equals(java.lang.Object), то вызов метода hashCode для каждого из двух объектов должен давать различные целочисленные результаты. Однако программист должен знать, что создание различных целочисленных результатов для неравных объектов может повысить производительность хеш-таблиц.

Насколько это целесообразно, метод hashCode, определенный классом Object, действительно возвращает разные целые числа для разных объектов. (Обычно это реализуется путем преобразования внутреннего адреса объекта в целое число, но этот метод реализации не требуется для языка программирования JavaTM.)

**Возвращает:**
int - значение хеш-кода для этого объекта.
### intersect(Rectangle otherRect) {#intersect-com.aspose.pdf.Rectangle-}
```
public Rectangle intersect(Rectangle otherRect)
```


Пересекается с прямоугольниками.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольник, с которым пересекается этот треугольник. |

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Пересечение прямоугольников; null, если прямоугольники не пересекаются.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Проверяет, является ли прямоугольник пустым.

**Возвращает:**
boolean - логическое значение
### isInclude(Rectangle otherRect, double rotationAngle) {#isInclude-com.aspose.pdf.Rectangle-double-}
```
public boolean isInclude(Rectangle otherRect, double rotationAngle)
```


Проверяет, что этот прямоугольник включает в себя другой прямоугольник целиком. Т.е. внутри этого прямоугольника находится целый другой прямоугольник. Разница с методом IsIntersect заключается в том, что IsIntersect будет истинным для частично пересекающихся прямоугольников, а IsInclude будет ложным.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольник, для которого проверяется включение. |
| rotationAngle | double | Угол поворота другого прямоугольника в радианах. |

**Возвращает:**
boolean - Истинно, если этот прямоугольник включает в себя весь указанный прямоугольник. В противном случае ложь.
### isIntersect(Rectangle otherRect) {#isIntersect-com.aspose.pdf.Rectangle-}
```
public boolean isIntersect(Rectangle otherRect)
```


Определяет, пересекается ли этот прямоугольник с другим прямоугольником.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | Пересечение будет проверено с указанным прямоугольником. |

**Возвращает:**
boolean - Истинно, если этот прямоугольник пересекается с указанным прямоугольником. В противном случае ложь.
### isPoint() {#isPoint--}
```
public boolean isPoint()
```


Проверяет, является ли прямоугольник точкой, т.е. LLX равен URX, а LLY равен URY.

**Возвращает:**
boolean - логическое значение
### isTrivial() {#isTrivial--}
```
public boolean isTrivial()
```


Проверяет, является ли прямоугольник тривиальным, т.е. имеет нулевой размер и положение.

**Возвращает:**
boolean - логическое значение
### join(Rectangle otherRect) {#join-com.aspose.pdf.Rectangle-}
```
public Rectangle join(Rectangle otherRect)
```


Соединяет прямоугольники.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольник, к которому этот прямоугольник должен быть присоединен. |

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Описанный прямоугольник.
### nearEquals(Rectangle other, double delta) {#nearEquals-com.aspose.pdf.Rectangle-double-}
```
public boolean nearEquals(Rectangle other, double delta)
```


Проверьте, являются ли прямоугольники почти равными, т.е. имеют ли они примерно одинаковое (с точностью до дельты) положение и размеры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольник, который будет сравниваться. |
| delta | double | Значение допуска сравнения. |

**Возвращает:**
boolean - True, если прямоугольники равны, иначе false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse(String value) {#parse-java.lang.String-}
```
public static Rectangle parse(String value)
```


Попробуйте разобрать строку и извлечь из нее компоненты прямоугольника llx, lly, urx, ury.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строка для разбора. |

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольный объект.
### rotate(int angle) {#rotate-int-}
```
public void rotate(int angle)
```


Повернуть прямоугольник на указанный угол.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | int | Угол поворота. Член перечисления Rotation. |

### rotateAngle(int angle) {#rotateAngle-int-}
```
public void rotateAngle(int angle)
```


Повернуть прямоугольник на указанный угол.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | int | Угол поворота в градусах от 0 до 360. |

### setLLX(double value) {#setLLX-double-}
```
public void setLLX(double value)
```


Устанавливает координату X нижнего левого угла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setLLY(double value) {#setLLY-double-}
```
public void setLLY(double value)
```


Устанавливает Y - координату нижнего левого угла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setURX(double value) {#setURX-double-}
```
public void setURX(double value)
```


Устанавливает X - координату правого верхнего угла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setURY(double value) {#setURY-double-}
```
public void setURY(double value)
```


Задает Y - координату правого верхнего угла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### toArray(ITrailerable trailerable) {#toArray-com.aspose.pdf.engine.data.ITrailerable-}
```
public PdfArray toArray(ITrailerable trailerable)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) |  |

**Возвращает:**
[PdfArray](../../com.aspose.pdf.engine.data/pdfarray)
### toPoints() {#toPoints--}
```
public final Point[] toPoints()
```


Преобразует прямоугольник в массив точек ("QuadPoints").

**Возвращает:**
com.aspose.pdf.Point[] - Массив точек.
### toRect() {#toRect--}
```
public Rectangle toRect()
```


Преобразует прямоугольник в экземпляр System.Drawing.Rectangle. Позиции и размер с плавающей запятой усекаются.

**Возвращает:**
[Rectangle](../../java.awt/rectangle) - Результат преобразования.
### toString() {#toString--}
```
public String toString()
```


Получает прямоугольное строковое представление.

**Возвращает:**
java.lang.String — строка имеет формат llx,lly,urx,ury.
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
