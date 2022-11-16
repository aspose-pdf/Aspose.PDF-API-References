---
title: SetAdvancedColorStroke
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий цвет, заданный оператором SCN для операций поглаживания.
type: docs
weight: 55
url: /ru/java/com.aspose.pdf.operators/setadvancedcolorstroke/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.SetColorOperator](../../com.aspose.pdf.operators/setcoloroperator), [com.aspose.pdf.operators.BasicSetColorOperator](../../com.aspose.pdf.operators/basicsetcoloroperator), [com.aspose.pdf.operators.BasicSetColorAndPatternOperator](../../com.aspose.pdf.operators/basicsetcolorandpatternoperator)
```
public class SetAdvancedColorStroke extends BasicSetColorAndPatternOperator
```

Класс, представляющий оператора SCN (установите цвет для операций поглаживания).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SetAdvancedColorStroke(int index, ICommand command)](#SetAdvancedColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Конструктор класса оператора. |
| [SetAdvancedColorStroke()](#SetAdvancedColorStroke--) | Инициализирует оператор. |
| [SetAdvancedColorStroke(double g)](#SetAdvancedColorStroke-double-) | Конструктор оператора scn |
| [SetAdvancedColorStroke(double g, String patternName)](#SetAdvancedColorStroke-double-java.lang.String-) | Конструктор для оператора scn. |
| [SetAdvancedColorStroke(double r, double g, double b, String patternName)](#SetAdvancedColorStroke-double-double-double-java.lang.String-) | Конструктор для оператора scn. |
| [SetAdvancedColorStroke(double c, double m, double y, double k, String patternName)](#SetAdvancedColorStroke-double-double-double-double-java.lang.String-) | Конструктор для оператора scn. |
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
| [getPatternName()](#getPatternName--) | Получает имя шаблона. |
| [getR()](#getR--) | Получает красную составляющую цвета |
| [getY()](#getY--) | Получает желтый компонент цвета CMYK. |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | Определяет, является ли оператор оператором, отвечающим за вывод текста (Tj, TJ и т. д.) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Только для внутреннего использования |
| [setIndex(int value)](#setIndex-int-) | Установить индекс оператора в списке операторов страницы. |
| [toString()](#toString--) | Преобразует команду и параметры в строковое представление. |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | Возвращает текстовое представление примитива Pdf (строка, массив, словарь и т. д.) в соответствии со спецификацией PDF. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SetAdvancedColorStroke(int index, ICommand command) {#SetAdvancedColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetAdvancedColorStroke(int index, ICommand command)
```


Конструктор класса оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс оператора. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Команда оператора. |

### SetAdvancedColorStroke() {#SetAdvancedColorStroke--}
```
public SetAdvancedColorStroke()
```


Инициализирует оператор.

### SetAdvancedColorStroke(double g) {#SetAdvancedColorStroke-double-}
```
public SetAdvancedColorStroke(double g)
```


Конструктор оператора scn

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| g | double | двойное значение Значение серого цвета. |

### SetAdvancedColorStroke(double g, String patternName) {#SetAdvancedColorStroke-double-java.lang.String-}
```
public SetAdvancedColorStroke(double g, String patternName)
```


Конструктор для оператора scn.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| g | double | Значение серого цвета. |
| patternName | java.lang.String | Строковое значение Имя шаблона. |

### SetAdvancedColorStroke(double r, double g, double b, String patternName) {#SetAdvancedColorStroke-double-double-double-java.lang.String-}
```
public SetAdvancedColorStroke(double r, double g, double b, String patternName)
```


Конструктор для оператора scn.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| r | double | Красная составляющая цвета/ |
| g | double | Зеленая составляющая цвета. |
| b | double | Синяя составляющая цвета. |
| patternName | java.lang.String | Строковый объект |

### SetAdvancedColorStroke(double c, double m, double y, double k, String patternName) {#SetAdvancedColorStroke-double-double-double-double-java.lang.String-}
```
public SetAdvancedColorStroke(double c, double m, double y, double k, String patternName)
```


Конструктор для оператора scn.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| c | double | Голубая составляющая цвета. |
| m | double | Пурпурный компонент цвета. |
| y | double | Желтая составляющая цвета. |
| k | double | Черная составляющая цвета |
| patternName | java.lang.String | Название узора. |

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
[Color](../../java.awt/color) - Цвет определяется оператором.
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
### getPatternName() {#getPatternName--}
```
public String getPatternName()
```


Получает имя шаблона.

**Возвращает:**
java.lang.String — строковое значение
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


Преобразует команду и параметры в строковое представление.

**Возвращает:**
java.lang.String — текст оператора
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
