---
title: TextReplaceOptions
second_title: Aspose.PDF для справки по Java API
description: Представляет параметры замены текста
type: docs
weight: 384
url: /ru/java/com.aspose.pdf/textreplaceoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)
```
public final class TextReplaceOptions extends TextOptions
```

Представляет параметры замены текста
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextReplaceOptions(int scope)](#TextReplaceOptions-int-) | Инициализирует новый экземпляр объекта TextReplaceOptions для указанной области. |
| [TextReplaceOptions(int adjustment, int scope)](#TextReplaceOptions-int-int-) | Инициализирует новый экземпляр объекта TextReplaceOptions для указанного действия после замены. |
| [TextReplaceOptions()](#TextReplaceOptions--) | Инициализирует новый экземпляр объекта TextReplaceOptions для настройки и области действия по умолчанию: ReplaceAdjustment.None и Scope.REPLACE.\_ПЕРВЫЙ |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdjustmentNewLineSpacing()](#getAdjustmentNewLineSpacing--) | Получает или задает значение межстрочного интервала, которое используется, если корректировка замены принудительно создает новую строку текста. |
| [getClass()](#getClass--) |  |
| [getReplaceAdjustmentAction()](#getReplaceAdjustmentAction--) | Получает действие, которое будет выполнено после замены фрагмента текста на более короткий. |
| [getReplaceScope()](#getReplaceScope--) | Получает область, в которой применяется операция замены текста |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdjustmentNewLineSpacing(double value)](#setAdjustmentNewLineSpacing-double-) | Получает или задает значение межстрочного интервала, которое используется, если корректировка замены принудительно создает новую строку текста. |
| [setReplaceAdjustmentAction(int value)](#setReplaceAdjustmentAction-int-) | Задает действие, которое будет выполнено после замены фрагмента текста на более короткое. |
| [setReplaceScope(int value)](#setReplaceScope-int-) | Устанавливает область, в которой применяется операция замены текста |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextReplaceOptions(int scope) {#TextReplaceOptions-int-}
```
public TextReplaceOptions(int scope)
```


Инициализирует новый экземпляр объекта TextReplaceOptions для указанной области.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| scope | int | Объект области. |

### TextReplaceOptions(int adjustment, int scope) {#TextReplaceOptions-int-int-}
```
public TextReplaceOptions(int adjustment, int scope)
```


Инициализирует новый экземпляр объекта TextReplaceOptions для указанного действия после замены.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| adjustment | int | Объект ЗаменитьРегулировку. |
| scope | int | Объект области. |

### TextReplaceOptions() {#TextReplaceOptions--}
```
public TextReplaceOptions()
```


Инициализирует новый экземпляр объекта TextReplaceOptions для настройки и области действия по умолчанию: ReplaceAdjustment.None и Scope.REPLACE.\_ПЕРВЫЙ

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
### getAdjustmentNewLineSpacing() {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```


Получает или задает значение межстрочного интервала, которое используется, если корректировка замены принудительно создает новую строку текста. Ожидаемое значение является множителем размера шрифта замененного текста. По умолчанию 1.2.

**Возвращает:**
двойное - двойное значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getReplaceAdjustmentAction() {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```


Получает действие, которое будет выполнено после замены фрагмента текста на более короткий.

**Возвращает:**
int — элемент ReplaceAdjustment
### getReplaceScope() {#getReplaceScope--}
```
public int getReplaceScope()
```


Получает область, в которой применяется операция замены текста

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAdjustmentNewLineSpacing(double value) {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```


Получает или задает значение межстрочного интервала, которое используется, если корректировка замены принудительно создает новую строку текста. Ожидаемое значение является множителем размера шрифта замененного текста. По умолчанию 1.2.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setReplaceAdjustmentAction(int value) {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```


Задает действие, которое будет выполнено после замены фрагмента текста на более короткое.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ReplaceAdjustment |

### setReplaceScope(int value) {#setReplaceScope-int-}
```
public void setReplaceScope(int value)
```


Устанавливает область, в которой применяется операция замены текста

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
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
