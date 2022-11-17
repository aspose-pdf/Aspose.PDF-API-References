---
title: SetCharWidthBoundingBox
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий глиф набора оператора d1 и ограничивающую рамку.
type: docs
weight: 59
url: /ru/java/com.aspose.pdf.operators/setcharwidthboundingbox/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class SetCharWidthBoundingBox extends Operator
```

Класс, представляющий оператор d1 (установите глиф и ограничивающую рамку).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)](#SetCharWidthBoundingBox-double-double-double-double-double-double-) | Инициализирует оператор. |
| [SetCharWidthBoundingBox(int index, ICommand command)](#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Конструктор класса оператора. |
## Методы

| Метод | Описание |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Принимает объект посетителя для обработки оператором. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromCommand(ICommand command)](#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | Получает команду |
| [getCommandName()](#getCommandName--) | Получает имя оператора. |
| [getIndex()](#getIndex--) | Получить индекс оператора в списке операторов страницы. |
| [getLlx()](#getLlx--) | Нижняя левая горизонтальная координата ограничивающего прямоугольника. |
| [getLly()](#getLly--) | Нижняя левая вертикальная координата ограничивающего прямоугольника. |
| [getParameters()](#getParameters--) | Получает массив параметров оператора. |
| [getUrx()](#getUrx--) | Правая верхняя горизонтальная координата ограничивающего прямоугольника. |
| [getUry()](#getUry--) | Верхняя правая вертикальная координата ограничивающего прямоугольника. |
| [getWx()](#getWx--) | Горизонтальное смещение глифа. |
| [getWy()](#getWy--) | Вертикальное смещение глифа. |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | Определяет, является ли оператор оператором, отвечающим за вывод текста (Tj, TJ и т. д.) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Только для внутреннего использования |
| [setIndex(int value)](#setIndex-int-) | Установить индекс оператора в списке операторов страницы. |
| [toCommand()](#toCommand--) |  |
| [toString()](#toString--) | Возвращает текстовое представление оператора. |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | Возвращает текстовое представление примитива Pdf (строка, массив, словарь и т. д.) в соответствии со спецификацией PDF. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury) {#SetCharWidthBoundingBox-double-double-double-double-double-double-}
```
public SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)
```


Инициализирует оператор.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| wx | double | двойное значение |
| wy | double | двойное значение |
| llx | double | двойное значение |
| lly | double | двойное значение |
| urx | double | двойное значение |
| ury | double | двойное значение |

### SetCharWidthBoundingBox(int index, ICommand command) {#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetCharWidthBoundingBox(int index, ICommand command)
```


Конструктор класса оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс оператора. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Команда оператора. |

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
### fromCommand(ICommand command) {#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public void fromCommand(ICommand command)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) |  |

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
### getIndex() {#getIndex--}
```
public int getIndex()
```


Получить индекс оператора в списке операторов страницы.

**Возвращает:**
интервал - целочисленное значение
### getLlx() {#getLlx--}
```
public double getLlx()
```


Нижняя левая горизонтальная координата ограничивающего прямоугольника.

**Возвращает:**
двойное - двойное значение
### getLly() {#getLly--}
```
public double getLly()
```


Нижняя левая вертикальная координата ограничивающего прямоугольника.

**Возвращает:**
двойное - двойное значение
### getParameters() {#getParameters--}
```
public ArrayList<CommandParameter> getParameters()
```


Получает массив параметров оператора.

**Возвращает:**
java.util.ArrayList<com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> — ArrayList значения CommandParameter
### getUrx() {#getUrx--}
```
public double getUrx()
```


Правая верхняя горизонтальная координата ограничивающего прямоугольника.

**Возвращает:**
двойное - двойное значение
### getUry() {#getUry--}
```
public double getUry()
```


Верхняя правая вертикальная координата ограничивающего прямоугольника.

**Возвращает:**
двойное - двойное значение
### getWx() {#getWx--}
```
public double getWx()
```


Горизонтальное смещение глифа.

**Возвращает:**
двойное - двойное значение
### getWy() {#getWy--}
```
public double getWy()
```


Вертикальное смещение глифа.

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

### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


Установить индекс оператора в списке операторов страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### toCommand() {#toCommand--}
```
public ICommand toCommand()
```




**Возвращает:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand)
### toString() {#toString--}
```
public String toString()
```


Возвращает текстовое представление оператора.

**Возвращает:**
java.lang.String — Текстовое представление представления
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
