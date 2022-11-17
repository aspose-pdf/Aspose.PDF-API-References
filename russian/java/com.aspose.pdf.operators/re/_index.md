---
title: Re
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий оператор re, добавляет прямоугольник к пути.
type: docs
weight: 52
url: /ru/java/com.aspose.pdf.operators/re/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class Re extends Operator
```

Класс, представляющий оператор re (добавить прямоугольник к пути).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Re(int index, ICommand command)](#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Конструктор класса оператора. |
| [Re()](#Re--) | Конструктор для извлечения голов. |
| [Re(double x, double y, double width, double height)](#Re-double-double-double-double-) | Конструктор для написания программы. |
## Методы

| Метод | Описание |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Принимает объект посетителя для обработки оператором. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | Получает команду |
| [getCommandName()](#getCommandName--) | Получает имя оператора. |
| [getHeight()](#getHeight--) | Высота прямоугольника. |
| [getIndex()](#getIndex--) | Получить индекс оператора в списке операторов страницы. |
| [getParameters()](#getParameters--) | Получает массив параметров оператора. |
| [getWidth()](#getWidth--) | Получает ширину прямоугольника. |
| [getX()](#getX--) | Координата X самой левой стороны прямоугольника. |
| [getY()](#getY--) | Координата Y нижней стороны прямоугольника. |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | Определяет, является ли оператор оператором, отвечающим за вывод текста (Tj, TJ и т. д.) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Только для внутреннего использования |
| [setHeight(double value)](#setHeight-double-) | Высота прямоугольника. |
| [setIndex(int value)](#setIndex-int-) | Установить индекс оператора в списке операторов страницы. |
| [setWidth(double value)](#setWidth-double-) | Устанавливает ширину прямоугольника. |
| [setX(double value)](#setX-double-) | Координата X самой левой стороны прямоугольника. |
| [setY(double value)](#setY-double-) | Координата Y нижней стороны прямоугольника. |
| [toString()](#toString--) | Возвращает текстовое представление оператора. |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | Возвращает текстовое представление примитива Pdf (строка, массив, словарь и т. д.) в соответствии со спецификацией PDF. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Re(int index, ICommand command) {#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public Re(int index, ICommand command)
```


Конструктор класса оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс оператора. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Команда оператора. |

### Re() {#Re--}
```
public Re()
```


Конструктор для извлечения голов.

### Re(double x, double y, double width, double height) {#Re-double-double-double-double-}
```
public Re(double x, double y, double width, double height)
```


Конструктор для написания программы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | double | Координата x нижнего левого угла прямоугольника. |
| y | double | Y-координата нижнего левого угла прямоугольника. |
| width | double | Ширина прямоугольника. |
| height | double | Высота прямоугольника. |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Принимает объект посетителя для обработки оператором.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Объект посетителя. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCommand() {#getCommand--}
```
public ICommand getCommand()
```


Получает команду

**Возвращает:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) - Объект ICommand
### getCommandName() {#getCommandName--}
```
public String getCommandName()
```


Получает имя оператора.

**Возвращает:**
java.lang.String — строковое значение
### getHeight() {#getHeight--}
```
public double getHeight()
```


Высота прямоугольника.

**Возвращает:**
double - Высота прямоугольника.
### getIndex() {#getIndex--}
```
public int getIndex()
```


Получить индекс оператора в списке операторов страницы.

**Возвращает:**
интервал - целочисленное значение
### getParameters() {#getParameters--}
```
public ArrayList<CommandParameter> getParameters()
```


Получает массив параметров оператора.

**Возвращает:**
java.util.ArrayList<com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> — ArrayList значения CommandParameter
### getWidth() {#getWidth--}
```
public double getWidth()
```


Получает ширину прямоугольника.

**Возвращает:**
double - ширина прямоугольника.
### getX() {#getX--}
```
public double getX()
```


Координата X самой левой стороны прямоугольника.

**Возвращает:**
двойное - двойное значение
### getY() {#getY--}
```
public double getY()
```


Координата Y нижней стороны прямоугольника.

**Возвращает:**
двойное - двойное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isTextShowOperator(Operator op) {#isTextShowOperator-com.aspose.pdf.Operator-}
```
public static boolean isTextShowOperator(Operator op)
```


Определяет, является ли оператор оператором, отвечающим за вывод текста (Tj, TJ и т. д.)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Объект оператора |

**Возвращает:**
boolean - True, если это оператор вывода текста
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


Только для внутреннего использования

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Высота прямоугольника.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Высота прямоугольника. |

### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


Установить индекс оператора в списке операторов страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Устанавливает ширину прямоугольника.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | ширина прямоугольника. |

### setX(double value) {#setX-double-}
```
public void setX(double value)
```


Координата X самой левой стороны прямоугольника.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Координата Y нижней стороны прямоугольника.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### toString() {#toString--}
```
public String toString()
```


Возвращает текстовое представление оператора.

**Возвращает:**
java.lang.String — Текстовое представление оператора.
### toString(IPdfPrimitive primitive) {#toString-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public static String toString(IPdfPrimitive primitive)
```


Возвращает текстовое представление примитива Pdf (строка, массив, словарь и т. д.) в соответствии со спецификацией PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| primitive | [IPdfПримитивный](../../com.aspose.pdf.engine.data/ipdfprimitive) | Primitive |

**Возвращает:**
java.lang.String — Текстовое представление примитива
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
