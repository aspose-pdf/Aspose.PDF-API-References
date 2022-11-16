---
title: CustomFontSubstitutionBase
second_title: Aspose.PDF для справки по Java API
description: Представляет базовый класс для пользовательской стратегии замены шрифта.
type: docs
weight: 10
url: /ru/java/com.aspose.pdf.text/customfontsubstitutionbase/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.text.FontSubstitution](../../com.aspose.pdf.text/fontsubstitution)
```
public class CustomFontSubstitutionBase extends FontSubstitution
```

Представляет базовый класс для пользовательской стратегии замены шрифта.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CustomFontSubstitutionBase()](#CustomFontSubstitutionBase--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSubstitutedUnicode(char unicode)](#getSubstitutedUnicode-char-) | Возвращает подстановку юникода |
| [getSubstitutionFontDefinition()](#getSubstitutionFontDefinition--) | Получить определение шрифта замены |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setSubstitutionFontDefinition(FontDefinition value)](#setSubstitutionFontDefinition-com.aspose.font.FontDefinition-) | Установить определение шрифта замены |
| [toString()](#toString--) |  |
| [trySubstitute(CustomFontSubstitutionBase.OriginalFontSpecification originalFontSpecification, Font[] substitutionFont)](#trySubstitute-com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification-com.aspose.pdf.Font---) | Заменяет исходный шрифт другим шрифтом. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomFontSubstitutionBase() {#CustomFontSubstitutionBase--}
```
public CustomFontSubstitutionBase()
```


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
### trySubstitute(CustomFontSubstitutionBase.OriginalFontSpecification originalFontSpecification, Font[] substitutionFont) {#trySubstitute-com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification-com.aspose.pdf.Font---}
```
public boolean trySubstitute(CustomFontSubstitutionBase.OriginalFontSpecification originalFontSpecification, Font[] substitutionFont)
```


Заменяет исходный шрифт другим шрифтом.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| originalFontSpecification | [OriginalFontSpecification](../../com.aspose.pdf.text/originalfontspecification) | Оригинальная спецификация шрифта. |
| substitutionFont | [Font\[\]](../../com.aspose.pdf/font) | Подстановочный шрифт.

--------------------

 Класс CustomFontSubstitutionBase должен быть унаследован для реализации пользовательской логики подстановки шрифтов. Метод TrySubstitute должен быть правильно переопределен: должен возвращать значение true, если требуется подстановка. Для substitutionFont должен быть установлен допустимый объект Font. Должен возвращать false, если замена не требуется. substitutionFont может иметь значение null.|

**Возвращает:**
boolean - Истинно, если подстановка прошла успешно.
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
