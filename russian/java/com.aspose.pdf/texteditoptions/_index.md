---
title: TextEditOptions
second_title: Aspose.PDF для справки по Java API
description: Descubes варианты операций редактирования текста.
type: docs
weight: 366
url: /ru/java/com.aspose.pdf/texteditoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)
```
public final class TextEditOptions extends TextOptions
```

Descubes варианты операций редактирования текста.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) | Инициализирует новый экземпляр объекта TextEditOptions с параметрами по умолчанию. |
| [TextEditOptions(int noCharacterBehavior)](#TextEditOptions-int-) | Инициализирует новый экземпляр объекта TextEditOptions для указанного бессимвольного режима поведения. |
| [TextEditOptions(int option, Class type)](#TextEditOptions-int-java.lang.Class-) | Инициализирует новый экземпляр объекта TextEditOptions для указанного бессимвольного режима поведения. |
| [TextEditOptions(boolean allowLanguageTransformation)](#TextEditOptions-boolean-) | Инициализирует новый экземпляр объекта TextEditOptions для указанного разрешения на преобразование языка. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowLanguageTransformation()](#getAllowLanguageTransformation--) | Получает значение, разрешающее использование преобразования языка при добавлении или редактировании текста. |
| [getClass()](#getClass--) |  |
| [getClippingPathsProcessing()](#getClippingPathsProcessing--) | Получает режим обработки обтравочного контура редактируемого текста. |
| [getFontReplaceBehavior()](#getFontReplaceBehavior--) | Получает режим, определяющий поведение сценариев замены шрифтов. |
| [getLanguageTransformationBehavior()](#getLanguageTransformationBehavior--) | Получает режим, определяющий поведение для сценариев преобразования языка. |
| [getNoCharacterBehavior()](#getNoCharacterBehavior--) | Получает режим, определяющий поведение в случае, если шрифты не содержат запрошенных символов. |
| [getReplacementFont()](#getReplacementFont--) | Получает или задает шрифт, используемый для замены, если пользовательский шрифт не содержит требуемого символа. |
| [getToAttemptGetUnderlineFromSource()](#getToAttemptGetUnderlineFromSource--) | Получает или задает значение, разрешающее поиск подчеркивания текста на странице исходного документа. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowLanguageTransformation(boolean value)](#setAllowLanguageTransformation-boolean-) | Устанавливает значение, разрешающее использование преобразования языка при добавлении или редактировании текста. |
| [setClippingPathsProcessing(int value)](#setClippingPathsProcessing-int-) | Получает режим обработки обтравочного контура редактируемого текста. |
| [setFontReplaceBehavior(int value)](#setFontReplaceBehavior-int-) | Задает режим, определяющий поведение сценариев замены шрифтов. |
| [setLanguageTransformationBehavior(int value)](#setLanguageTransformationBehavior-int-) | Задает режим, определяющий поведение для сценариев преобразования языка. |
| [setNoCharacterBehavior(int value)](#setNoCharacterBehavior-int-) | Задает режим, определяющий поведение в случае, если шрифты не содержат запрошенных символов. |
| [setReplacementFont(Font value)](#setReplacementFont-com.aspose.pdf.Font-) | Получает или задает шрифт, используемый для замены, если пользовательский шрифт не содержит требуемого символа. |
| [setToAttemptGetUnderlineFromSource(boolean value)](#setToAttemptGetUnderlineFromSource-boolean-) | Получает или задает значение, разрешающее поиск подчеркивания текста на странице исходного документа. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


Инициализирует новый экземпляр объекта TextEditOptions с параметрами по умолчанию. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions(int noCharacterBehavior) {#TextEditOptions-int-}
```
public TextEditOptions(int noCharacterBehavior)
```


Инициализирует новый экземпляр объекта TextEditOptions для указанного бессимвольного режима поведения. Инициируйте fontReplaceBehavior с помощью setFontReplaceBehavior(int)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| noCharacterBehavior | int | Объект режима бессимвольного поведения. |

### TextEditOptions(int option, Class type) {#TextEditOptions-int-java.lang.Class-}
```
public TextEditOptions(int option, Class type)
```


Инициализирует новый экземпляр объекта TextEditOptions для указанного бессимвольного режима поведения. Инициируйте fontReplaceBehavior с помощью setFontReplaceBehavior(int)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| option | int | значение для одного из следующих классов: NoCharacterAction, LanguageTransformation, FontReplace, |
| type | java.lang.Class | класс опциона |

### TextEditOptions(boolean allowLanguageTransformation) {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```


Инициализирует новый экземпляр объекта TextEditOptions для указанного разрешения на преобразование языка.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| allowLanguageTransformation | boolean | Разрешает преобразование языка, если установлено значение true. |

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
### getAllowLanguageTransformation() {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```


Получает значение, разрешающее использование преобразования языка при добавлении или редактировании текста. true - трансформация языка будет применена при необходимости (значение по умолчанию). false - преобразование языка НЕ будет применено.

**Возвращает:**
boolean - логическое значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getClippingPathsProcessing() {#getClippingPathsProcessing--}
```
public final int getClippingPathsProcessing()
```


Получает режим обработки обтравочного контура редактируемого текста.

**Возвращает:**
int — элемент ClippingPathsProcessingMode
### getFontReplaceBehavior() {#getFontReplaceBehavior--}
```
public int getFontReplaceBehavior()
```


Получает режим, определяющий поведение сценариев замены шрифтов.

**Возвращает:**
int - значение FontReplace
### getLanguageTransformationBehavior() {#getLanguageTransformationBehavior--}
```
public int getLanguageTransformationBehavior()
```


Получает режим, определяющий поведение для сценариев преобразования языка.

**Возвращает:**
int — значение LanguageTransformation
### getNoCharacterBehavior() {#getNoCharacterBehavior--}
```
public int getNoCharacterBehavior()
```


Получает режим, определяющий поведение в случае, если шрифты не содержат запрошенных символов.

**Возвращает:**
int - значение NoCharacterAction
### getReplacementFont() {#getReplacementFont--}
```
public final Font getReplacementFont()
```


Получает или задает шрифт, используемый для замены, если пользовательский шрифт не содержит требуемого символа.

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Экземпляр шрифта
### getToAttemptGetUnderlineFromSource() {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```


Получает или задает значение, разрешающее поиск подчеркивания текста на странице исходного документа. (Устарело) Вместо этого используйте TextSearchOptions.SearchForTextRelatedGraphics.

**Возвращает:**
boolean - логическое значение
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




### setAllowLanguageTransformation(boolean value) {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```


Устанавливает значение, разрешающее использование преобразования языка при добавлении или редактировании текста. true - трансформация языка будет применена при необходимости (значение по умолчанию). false - преобразование языка НЕ будет применено.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setClippingPathsProcessing(int value) {#setClippingPathsProcessing-int-}
```
public final void setClippingPathsProcessing(int value)
```


Получает режим обработки обтравочного контура редактируемого текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ClippingPathsProcessingMode |

### setFontReplaceBehavior(int value) {#setFontReplaceBehavior-int-}
```
public void setFontReplaceBehavior(int value)
```


Задает режим, определяющий поведение сценариев замены шрифтов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение FontReplace |

### setLanguageTransformationBehavior(int value) {#setLanguageTransformationBehavior-int-}
```
public void setLanguageTransformationBehavior(int value)
```


Задает режим, определяющий поведение для сценариев преобразования языка.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение LanguageTransformation |

### setNoCharacterBehavior(int value) {#setNoCharacterBehavior-int-}
```
public void setNoCharacterBehavior(int value)
```


Задает режим, определяющий поведение в случае, если шрифты не содержат запрошенных символов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение NoCharacterAction |

### setReplacementFont(Font value) {#setReplacementFont-com.aspose.pdf.Font-}
```
public final void setReplacementFont(Font value)
```


Получает или задает шрифт, используемый для замены, если пользовательский шрифт не содержит требуемого символа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | Экземпляр шрифта |

### setToAttemptGetUnderlineFromSource(boolean value) {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```


Получает или задает значение, разрешающее поиск подчеркивания текста на странице исходного документа. (Устарело) Вместо этого используйте TextSearchOptions.SearchForTextRelatedGraphics.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

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
