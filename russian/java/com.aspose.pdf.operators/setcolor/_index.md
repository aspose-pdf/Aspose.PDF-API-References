---
title: SetColor
second_title: Aspose.PDF для справки по Java API
description: Представляет класс для оператора sc, задающего цвет для операций без штриха.
type: docs
weight: 61
url: /ru/java/com.aspose.pdf.operators/setcolor/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.SetColorOperator](../../com.aspose.pdf.operators/setcoloroperator), [com.aspose.pdf.operators.BasicSetColorOperator](../../com.aspose.pdf.operators/basicsetcoloroperator)
```
public class SetColor extends BasicSetColorOperator
```

Представляет класс для оператора sc (устанавливает цвет для операций без штриха).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SetColor()](#SetColor--) | Инициализирует оператор. |
| [SetColor(int index, ICommand command)](#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Конструктор класса оператора. |
| [SetColor(double g)](#SetColor-double-) | Установите цвет для операторов штриховки для цветовых пространств DeviceGrey, CalGrey и Indexed. |
| [SetColor(double r, double g, double b)](#SetColor-double-double-double-) | Установить цвет для оператора поглаживания для цветовых пространств DeviceRGB, CalRGB и Lab |
| [SetColor(double c, double m, double y, double k)](#SetColor-double-double-double-double-) | Установить цвет для оператора без штриха для цветового пространства CMYK |
| [SetColor(double[] color)](#SetColor-double---) | Конструктор, позволяющий задавать компоненты цвета. |
## Методы

| Метод | Описание |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Принимает объект посетителя для обработки оператором. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getB()](#getB--) | Получает красную составляющую цвета |
| [getC()](#getC--) | Получает голубой компонент цвета CMYK. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Пока не поддерживается. |
| [getColorArray()](#getColorArray--) | Получает массив компонентов цвета. |
| [getCommand()](#getCommand--) | Получает команду |
| [getCommandName()](#getCommandName--) | Получает имя оператора. |
| [getG()](#getG--) | Получает зеленую составляющую цвета |
| [getGrey()](#getGrey--) | Получает черную составляющую серого цвета. |
| [getIndex()](#getIndex--) | Получить индекс оператора в списке операторов страницы. |
| [getK()](#getK--) | Получает черный компонент цвета CMYK. |
| [getM()](#getM--) | Получает пурпурный компонент цвета CMYK. |
| [getParameters()](#getParameters--) | Получает массив параметров оператора. |
| [getR()](#getR--) | Получает красную составляющую цвета |
| [getY()](#getY--) | Получает желтый компонент цвета CMYK. |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | Определяет, является ли оператор оператором, отвечающим за вывод текста (Tj, TJ и т. д.) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Только для внутреннего использования |
| [setIndex(int value)](#setIndex-int-) | Установить индекс оператора в списке операторов страницы. |
| [toString()](#toString--) | Возвращает строковое представление цвета. |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | Возвращает текстовое представление примитива Pdf (строка, массив, словарь и т. д.) в соответствии со спецификацией PDF. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SetColor() {#SetColor--}
```
public SetColor()
```


Инициализирует оператор.

### SetColor(int index, ICommand command) {#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetColor(int index, ICommand command)
```


Конструктор класса оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс оператора. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Команда оператора. |

### SetColor(double g) {#SetColor-double-}
```
public SetColor(double g)
```


Установите цвет для операторов штриховки для цветовых пространств DeviceGrey, CalGrey и Indexed.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| g | double | Значение цвета. |

### SetColor(double r, double g, double b) {#SetColor-double-double-double-}
```
public SetColor(double r, double g, double b)
```


Установить цвет для оператора поглаживания для цветовых пространств DeviceRGB, CalRGB и Lab

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| r | double | Красный компонент. |
| g | double | Зеленый компонент. |
| b | double | Синий компонент. |

### SetColor(double c, double m, double y, double k) {#SetColor-double-double-double-double-}
```
public SetColor(double c, double m, double y, double k)
```


Установить цвет для оператора без штриха для цветового пространства CMYK

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| c | double | Голубой компонент. |
| m | double | Пурпурный компонент. |
| y | double | Желтый компонент. |
| k | double | Черный компонент. |

### SetColor(double[] color) {#SetColor-double---}
```
public SetColor(double[] color)
```


Конструктор, позволяющий задавать компоненты цвета.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| color | double[] | Массив цветовых компонентов. |

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
### getB() {#getB--}
```
public double getB()
```


Получает красную составляющую цвета

**Возвращает:**
двойное - двойное значение
### getC() {#getC--}
```
public double getC()
```


Получает голубой компонент цвета CMYK.

**Возвращает:**
двойное - двойное значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Пока не поддерживается.

Возвращает цвет, указанный оператором.

**Возвращает:**
[Color](../../java.awt/color) - Цвет оператора.
### getColorArray() {#getColorArray--}
```
public double[] getColorArray()
```


Получает массив компонентов цвета.

**Возвращает:**
двойной[] - двойной массив
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
### getG() {#getG--}
```
public double getG()
```


Получает зеленую составляющую цвета

**Возвращает:**
двойное - двойное значение
### getGrey() {#getGrey--}
```
public double getGrey()
```


Получает черную составляющую серого цвета.

**Возвращает:**
двойное - двойное значение
### getIndex() {#getIndex--}
```
public int getIndex()
```


Получить индекс оператора в списке операторов страницы.

**Возвращает:**
интервал - целочисленное значение
### getK() {#getK--}
```
public double getK()
```


Получает черный компонент цвета CMYK.

**Возвращает:**
двойное - двойное значение
### getM() {#getM--}
```
public double getM()
```


Получает пурпурный компонент цвета CMYK.

**Возвращает:**
двойное - двойное значение
### getParameters() {#getParameters--}
```
public ArrayList<CommandParameter> getParameters()
```


Получает массив параметров оператора.

**Возвращает:**
java.util.ArrayList<com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> — ArrayList значения CommandParameter
### getR() {#getR--}
```
public double getR()
```


Получает красную составляющую цвета

**Возвращает:**
двойное - двойное значение
### getY() {#getY--}
```
public double getY()
```


Получает желтый компонент цвета CMYK.

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

### toString() {#toString--}
```
public String toString()
```


Возвращает строковое представление цвета.

**Возвращает:**
java.lang.String — строковое представление цвета.
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
