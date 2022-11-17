---
title: CustomFontSubstitutionBase.OriginalFontSpecification
second_title: Aspose.PDF для справки по Java API
description: Представляет исходную спецификацию шрифта.
type: docs
weight: 10
url: /ru/java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**Наследование:**
java.lang.Object
```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification
```

Представляет исходную спецификацию шрифта.

--------------------

Предоставляет информацию, связанную с исходным шрифтом, такую как , флаг. Также предоставляет флаг, который помогает проверить, произойдет ли замена шрифта в любом случае, и пользователь может переопределить логику замены по умолчанию.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OriginalFontSpecification(String originalFontName, boolean isEmbedded, boolean isUnavoidable)](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | Инициализирует новый объект OriginalFontSpecification. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOriginalFontName()](#getOriginalFontName--) | Получает оригинальное имя шрифта. |
| [hashCode()](#hashCode--) |  |
| [isEmbedded()](#isEmbedded--) | Получает значение, указывающее, внедрен ли шрифт. |
| [isSubstitutionUnavoidable()](#isSubstitutionUnavoidable--) | Получает значение, указывающее, что замена неизбежна. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OriginalFontSpecification(String originalFontName, boolean isEmbedded, boolean isUnavoidable) {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
```
public OriginalFontSpecification(String originalFontName, boolean isEmbedded, boolean isUnavoidable)
```


Инициализирует новый объект OriginalFontSpecification.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| originalFontName | java.lang.String | Строковый объект |
| isEmbedded | boolean | логическое значение |
| isUnavoidable | boolean | логическое значение |

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


Получает оригинальное имя шрифта.

**Возвращает:**
java.lang.String — строковое значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Получает значение, указывающее, внедрен ли шрифт.

**Возвращает:**
boolean - логическое значение
### isSubstitutionUnavoidable() {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```


Получает значение, указывающее, что замена неизбежна.

**Возвращает:**
boolean - логическое значение

--------------------

Возвращает true, если замена была запрошена из-за отсутствия исходного шрифта или если исходный шрифт нельзя использовать в контексте какой-либо задачи. В случае, если пользователь игнорирует флаг и не заменяет шрифт - выполняется процедура замены шрифта по умолчанию. Но это дает пользователю возможность изменить стандартную процедуру замены шрифта и установить лучший шрифт в системе. Возвращает false, если исходный шрифт присутствует, допустим, но пользователю разрешено заменить его.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
