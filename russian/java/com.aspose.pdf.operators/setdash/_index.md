---
title: SetDash
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий d-оператор, задающий штрихпунктирную линию.
type: docs
weight: 67
url: /ru/java/com.aspose.pdf.operators/setdash/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class SetDash extends Operator
```

Класс, представляющий оператор d (установить штрихпунктирную линию).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SetDash(int index, ICommand command)](#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Конструктор класса оператора. |
| [SetDash(int[] pattern, int phase)](#SetDash-int---int-) | Создает оператор набора штрихов. |
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
| [getParameters()](#getParameters--) | Получает массив параметров оператора. |
| [getPattern()](#getPattern--) | Штриховой узор. |
| [getPhase()](#getPhase--) | Фаза рывка. |
| [hashCode()](#hashCode--) |  |
| [isTextShowOperator(Operator op)](#isTextShowOperator-com.aspose.pdf.Operator-) | Определяет, является ли оператор оператором, отвечающим за вывод текста (Tj, TJ и т. д.) |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Только для внутреннего использования |
| [setIndex(int value)](#setIndex-int-) | Установить индекс оператора в списке операторов страницы. |
| [setPattern(int[] value)](#setPattern-int---) | Штриховой узор. |
| [setPhase(int value)](#setPhase-int-) | Фаза рывка. |
| [toCommand()](#toCommand--) |  |
| [toString()](#toString--) | Получает строковое представление оператора. |
| [toString(IPdfPrimitive primitive)](#toString-com.aspose.pdf.engine.data.IPdfPrimitive-) | Возвращает текстовое представление примитива Pdf (строка, массив, словарь и т. д.) в соответствии со спецификацией PDF. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SetDash(int index, ICommand command) {#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetDash(int index, ICommand command)
```


Конструктор класса оператора.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс оператора. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Команда оператора. |

### SetDash(int[] pattern, int phase) {#SetDash-int---int-}
```
public SetDash(int[] pattern, int phase)
```


Создает оператор набора штрихов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pattern | int[] | Массив, определяющий шаблон штриховки. |
| phase | int | Фаза рывка. |

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
### getParameters() {#getParameters--}
```
public ArrayList<CommandParameter> getParameters()
```


Получает массив параметров оператора.

**Возвращает:**
java.util.ArrayList<com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> — ArrayList значения CommandParameter
### getPattern() {#getPattern--}
```
public int[] getPattern()
```


Штриховой узор. Элементами массива должны быть числа, определяющие длину чередующихся дефисов и пробелов. В случае одноэлементного массива длины штриха и пробела равны.

**Возвращает:**
инт[] - целочисленный массив
### getPhase() {#getPhase--}
```
public int getPhase()
```


Фаза рывка. Прежде чем начать обводку контура, массив штрихов следует циклически перебирать, суммируя длины штрихов и пробелов. Когда накопленная длина становится равной значению, заданному фазой тире, начинается штриховка пути, и массив тире должен использоваться циклически, начиная с этой точки.

**Возвращает:**
интервал - целочисленное значение
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

### setPattern(int[] value) {#setPattern-int---}
```
public void setPattern(int[] value)
```


Штриховой узор. Элементами массива должны быть числа, определяющие длину чередующихся дефисов и пробелов. В случае одноэлементного массива длины штриха и пробела равны.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] | массив целых чисел |

### setPhase(int value) {#setPhase-int-}
```
public void setPhase(int value)
```


Фаза рывка. Прежде чем начать обводку контура, массив штрихов следует циклически перебирать, суммируя длины штрихов и пробелов. Когда накопленная длина становится равной значению, заданному фазой тире, начинается штриховка пути, и массив тире должен использоваться циклически, начиная с этой точки.

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


Получает строковое представление оператора.

**Возвращает:**
 java.lang.String -[x1 x2] yd, где x1 - длина штриха, x2 - длина промежутка, y - фаза.
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
