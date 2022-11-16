---
title: SimpleFontSubstitution
second_title: Aspose.PDF для справки по Java API
description: Представляет класс для простой стратегии замены шрифта.
type: docs
weight: 17
url: /ru/java/com.aspose.pdf.text/simplefontsubstitution/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.text.FontSubstitution](../../com.aspose.pdf.text/fontsubstitution)
```
public final class SimpleFontSubstitution extends FontSubstitution
```

Представляет класс для простой стратегии замены шрифта.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SimpleFontSubstitution(String originalFontName, String substitutionFontName, boolean isForcedBySaveOption)](#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-) | Инициализирует новый экземпляр класса SimpleFontSubstitution. |
| [SimpleFontSubstitution(String originalFontName, String substitutionFontName)](#SimpleFontSubstitution-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса SimpleFontSubstitution. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOriginalFontName()](#getOriginalFontName--) | Получает исходное имя шрифта, которое следует заменить на SubstitutionFontName.  |
| [getSubstitutedUnicode(char unicode)](#getSubstitutedUnicode-char-) | Возвращает подстановку юникода |
| [getSubstitutionFontDefinition()](#getSubstitutionFontDefinition--) | Получить определение шрифта замены |
| [getSubstitutionFontName()](#getSubstitutionFontName--) | Получает имя шрифта, которое должно заменить OriginalFontName.  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setSubstitutionFontDefinition(FontDefinition value)](#setSubstitutionFontDefinition-com.aspose.font.FontDefinition-) | Установить определение шрифта замены |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SimpleFontSubstitution(String originalFontName, String substitutionFontName, boolean isForcedBySaveOption) {#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-}
```
public SimpleFontSubstitution(String originalFontName, String substitutionFontName, boolean isForcedBySaveOption)
```


Инициализирует новый экземпляр класса SimpleFontSubstitution.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| originalFontName | java.lang.String | Оригинальное название шрифта. |
| substitutionFontName | java.lang.String | Замена имени шрифта. |
| isForcedBySaveOption | boolean | Замена, вызванная параметром сохранения DefaultFontName. |

### SimpleFontSubstitution(String originalFontName, String substitutionFontName) {#SimpleFontSubstitution-java.lang.String-java.lang.String-}
```
public SimpleFontSubstitution(String originalFontName, String substitutionFontName)
```


Инициализирует новый экземпляр класса SimpleFontSubstitution.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| originalFontName | java.lang.String | Оригинальное название шрифта. |
| substitutionFontName | java.lang.String | Замена имени шрифта. |

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
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Получает исходное имя шрифта, которое следует заменить на SubstitutionFontName. 

**Возвращает:**
java.lang.String — строковое значение
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
### getSubstitutionFontName() {#getSubstitutionFontName--}
```
public String getSubstitutionFontName()
```


Получает имя шрифта, которое должно заменить OriginalFontName. 

**Возвращает:**
java.lang.String — строковое значение
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
