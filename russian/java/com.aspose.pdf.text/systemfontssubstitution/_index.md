---
title: SystemFontsSubstitution
second_title: Aspose.PDF для справки по Java API
description: Представляет класс для стратегии замены шрифтов, которая заменяет шрифты системными шрифтами.
type: docs
weight: 19
url: /ru/java/com.aspose.pdf.text/systemfontssubstitution/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.text.FontSubstitution](../../com.aspose.pdf.text/fontsubstitution)
```
public final class SystemFontsSubstitution extends FontSubstitution
```

Представляет класс для стратегии замены шрифтов, которая заменяет шрифты системными шрифтами.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SystemFontsSubstitution(int fontCategories)](#SystemFontsSubstitution-int-) | Инициализирует новый экземпляр класса SystemFontsSubstitution. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Получает или задает подстановочный шрифт по умолчанию. |
| [getFontCategories()](#getFontCategories--) | Получает или задает категории замещающих шрифтов, которые должны быть заменены системными шрифтами. |
| [getSubstitutedUnicode(char unicode)](#getSubstitutedUnicode-char-) | Возвращает подстановку юникода |
| [getSubstitutionFontDefinition()](#getSubstitutionFontDefinition--) | Получить определение шрифта замены |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(Font value)](#setDefaultFont-com.aspose.pdf.Font-) | Получает или задает подстановочный шрифт по умолчанию. |
| [setFontCategories(int value)](#setFontCategories-int-) | Получает или задает категории замещающих шрифтов, которые должны быть заменены системными шрифтами. |
| [setSubstitutionFontDefinition(FontDefinition value)](#setSubstitutionFontDefinition-com.aspose.font.FontDefinition-) | Установить определение шрифта замены |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SystemFontsSubstitution(int fontCategories) {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```


Инициализирует новый экземпляр класса SystemFontsSubstitution.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontCategories | int | Целевые категории шрифтов для замены системными шрифтами |

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
### getDefaultFont() {#getDefaultFont--}
```
public Font getDefaultFont()
```


Получает или задает подстановочный шрифт по умолчанию. Шрифт используется, когда не найдено никакой другой допустимой замены, но исходный шрифт принадлежит к целевой категории замены ( FontCategories ).

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Объект шрифта
### getFontCategories() {#getFontCategories--}
```
public int getFontCategories()
```


Получает или задает категории замещающих шрифтов, которые должны быть заменены системными шрифтами.

**Возвращает:**
int — элемент SubstitutionFontCategories
### getSubstitutedUnicode(char unicode) {#getSubstitutedUnicode-char-}
```
public char getSubstitutedUnicode(char unicode)
```


Возвращает подстановку юникода

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| unicode | char | символьное значение |

**Возвращает:**
char - значение символа
### getSubstitutionFontDefinition() {#getSubstitutionFontDefinition--}
```
public FontDefinition getSubstitutionFontDefinition()
```


Получить определение шрифта замены

**Возвращает:**
com.aspose.font.FontDefinition — объект FontDefinition
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




### setDefaultFont(Font value) {#setDefaultFont-com.aspose.pdf.Font-}
```
public void setDefaultFont(Font value)
```


Получает или задает подстановочный шрифт по умолчанию. Шрифт используется, когда не найдено никакой другой допустимой замены, но исходный шрифт принадлежит к целевой категории замены ( FontCategories ).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | Объект шрифта |

### setFontCategories(int value) {#setFontCategories-int-}
```
public void setFontCategories(int value)
```


Получает или задает категории замещающих шрифтов, которые должны быть заменены системными шрифтами.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент SubstitutionFontCategories |

### setSubstitutionFontDefinition(FontDefinition value) {#setSubstitutionFontDefinition-com.aspose.font.FontDefinition-}
```
public void setSubstitutionFontDefinition(FontDefinition value)
```


Установить определение шрифта замены

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | com.aspose.font.FontDefinition | Объект FontDefinition |

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
