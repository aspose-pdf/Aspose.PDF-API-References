---
title: DocumentPrivilege
second_title: Aspose.PDF для справки по Java API
description: Представляет привилегии для доступа к файлу Pdf.
type: docs
weight: 19
url: /ru/java/com.aspose.pdf.facades/documentprivilege/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Comparable
```
public final class DocumentPrivilege implements Comparable<Object>
```

Представляет привилегии для доступа к файлу Pdf. Обратитесь к PdfFileSecurity. Существует 4 способа использования этого класса: 1. Непосредственное использование предопределенных привилегий. 2. На основе предопределенных привилегий и изменения некоторых конкретных разрешений. 3. На основе предопределенной привилегии и изменения определенной комбинации разрешений Adobe Professional. 4. Смешивает путь 2 и способ 3.

--------------------

```
//Способ 1: прямое использование предопределенной привилегии.
  DocumentPrivilege privilege = DocumentPrivilege.getPrint();
  //Way2: На основе предопределенной привилегии и изменения некоторых конкретных разрешений.
  DocumentPrivilege privilege = DocumentPrivilege.getAllowAll();
  privilege.setAllowPrint(false);
  privilege.setAllowModifyContents(false);
  //Способ 3: на основе предопределенной привилегии и изменения определенной комбинации разрешений Adobe Professional.
  DocumentPrivilege privilege = DocumentPrivilege.getForbidAll();
  privilege.setChangeAllowLevel(1);
  privilege.setPrintAllowLevel(2);
  //Way4: смешивает way2 и way3
  DocumentPrivilege privilege = DocumentPrivilege.getForbidAll();
  privilege.setChangeAllowLevel(1);
  privilege.setAllowPrint(true);
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DocumentPrivilege(int value)](#DocumentPrivilege-int-) | Конструктор |
## Методы

| Метод | Описание |
| --- | --- |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Сравнивает два объекта DocumentPrivilege. |
| [equals(Object obj)](#equals-java.lang.Object-) | Указывает, является ли какой-либо другой объект «равным» этому. |
| [getAllowAll()](#getAllowAll--) | Все разрешено. |
| [getAssembly()](#getAssembly--) | Позволяет собирать файл. |
| [getClass()](#getClass--) |  |
| [getCopy()](#getCopy--) | Позволяет копировать файл. |
| [getDegradedPrinting()](#getDegradedPrinting--) | Допускает некачественную печать. |
| [getFillIn()](#getFillIn--) | Позволяет заполнять формы в файле. |
| [getForbidAll()](#getForbidAll--) | Все Запрещено. |
| [getModifyAnnotations()](#getModifyAnnotations--) | Позволяет изменять аннотации файла. |
| [getModifyContents()](#getModifyContents--) | Позволяет изменять файл. |
| [getPrint()](#getPrint--) | Позволяет распечатать файл. |
| [getScreenReaders()](#getScreenReaders--) | Позволяет читать только на экране. |
| [getValue()](#getValue--) | Получает значение |
| [hashCode()](#hashCode--) | Возвращает значение хэш-кода для объекта. |
| [isAllowAssembly()](#isAllowAssembly--) | Устанавливает разрешение, которое разрешает сборку или нет. true — разрешено, false — запрещено. |
| [isAllowCopy()](#isAllowCopy--) | Устанавливает разрешение, которое разрешает копирование или нет. true — разрешено, false — запрещено. |
| [isAllowDegradedPrinting()](#isAllowDegradedPrinting--) | Устанавливает разрешение, которое разрешает печать с ухудшенным качеством или нет. true — разрешено, false — запрещено. |
| [isAllowFillIn()](#isAllowFillIn--) | Устанавливает разрешение, позволяющее заполнять формы или нет. true — разрешено, false — запрещено. |
| [isAllowModifyAnnotations()](#isAllowModifyAnnotations--) | Устанавливает разрешение, которое позволяет изменять аннотации или нет. true — разрешено, false — запрещено. |
| [isAllowModifyContents()](#isAllowModifyContents--) | Устанавливает разрешение, которое позволяет изменять содержимое или нет. true — разрешено, false — запрещено. |
| [isAllowPrint()](#isAllowPrint--) | Устанавливает разрешение, которое разрешает печать или нет. true — разрешено, false — запрещено. |
| [isAllowScreenReaders()](#isAllowScreenReaders--) | Устанавливает разрешение, разрешающее или запрещающее чтение с экрана. true — разрешено, false — запрещено. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowAssembly(boolean value)](#setAllowAssembly-boolean-) | Устанавливает разрешение, которое разрешает сборку или нет. true — разрешено, false — запрещено. |
| [setAllowCopy(boolean value)](#setAllowCopy-boolean-) | Устанавливает разрешение, которое разрешает копирование или нет. true — разрешено, false — запрещено. |
| [setAllowDegradedPrinting(boolean value)](#setAllowDegradedPrinting-boolean-) | Устанавливает разрешение, которое разрешает печать с ухудшенным качеством или нет. true — разрешено, false — запрещено. |
| [setAllowFillIn(boolean value)](#setAllowFillIn-boolean-) | Устанавливает разрешение, позволяющее заполнять формы или нет. true — разрешено, false — запрещено. |
| [setAllowModifyAnnotations(boolean value)](#setAllowModifyAnnotations-boolean-) | Устанавливает разрешение, которое позволяет изменять аннотации или нет. true — разрешено, false — запрещено. |
| [setAllowModifyContents(boolean value)](#setAllowModifyContents-boolean-) | Устанавливает разрешение, которое позволяет изменять содержимое или нет. true — разрешено, false — запрещено. |
| [setAllowPrint(boolean value)](#setAllowPrint-boolean-) | Устанавливает разрешение, которое разрешает печать или нет. true — разрешено, false — запрещено. |
| [setAllowScreenReaders(boolean value)](#setAllowScreenReaders-boolean-) | Устанавливает разрешение, разрешающее или запрещающее чтение с экрана. true — разрешено, false — запрещено. |
| [setChangeAllowLevel(int value)](#setChangeAllowLevel-int-) | Устанавливает уровень изменения прав доступа к документу. |
| [setCopyAllowLevel(int value)](#setCopyAllowLevel-int-) | Устанавливает уровень привилегий копирования документа. |
| [setPrintAllowLevel(int value)](#setPrintAllowLevel-int-) | Устанавливает уровень привилегий печати документа. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DocumentPrivilege(int value) {#DocumentPrivilege-int-}
```
public DocumentPrivilege(int value)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Разрешения документа |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public int compareTo(Object obj)
```


Сравнивает два объекта DocumentPrivilege.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения. |

**Возвращает:**
int — целое число со знаком, указывающее относительные значения этого экземпляра и значения. Меньше нуля этот экземпляр меньше значения. Ноль этого экземпляра равен значению. Больше нуля этот экземпляр больше значения.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Указывает, является ли какой-либо другой объект «равным» этому.

`equals` метод реализует отношение эквивалентности для ненулевых ссылок на объекты:

 *   это*reflexive* : для любого ненулевого опорного значения`x`, `x.equals(x)` должен вернуться`true`.
 *   это*symmetric* : для любых ненулевых опорных значений`x` а также`y`, `x.equals(y)` должен вернуться`true` если и только если`y.equals(x)` возвращается`true`.
 *   это*transitive* : для любых ненулевых опорных значений`x`, `y` , а также`z` , если`x.equals(y)` возвращается`true` а также`y.equals(z)` возвращается`true` , тогда`x.equals(z)` должен вернуться`true`.
 *   это*consistent* : для любых ненулевых опорных значений`x` а также`y` , множественные вызовы x.equals(y) последовательно возвращают`true` или постоянно возвращаться`false` , при условии, что информация не использовалась в`equals` сравнения на объектах изменены.
 *   Для любого ненулевого опорного значения`x`, `x.equals(null)` должен вернуться`false`.

 Метод equals для класса`Object` реализует максимально различающее отношение эквивалентности к объектам; то есть для любых ненулевых опорных значений`x` а также`y` , этот метод возвращает`true` если и только если`x` а также`y` относятся к одному и тому же объекту (`x == y`имеет значение`true`).

Обратите внимание, что обычно необходимо переопределять метод hashCode всякий раз, когда этот метод переопределяется, чтобы сохранить общий контракт для метода hashCode, в котором говорится, что одинаковые объекты должны иметь одинаковые хеш-коды.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | эталонный объект для сравнения. |

**Возвращает:**
 логический -`true` если этот объект совпадает с аргументом obj;`false` в противном случае.
### getAllowAll() {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```


Все разрешено.

**Возвращает:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - Элемент DocumentPrivilege
### getAssembly() {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```


Позволяет собирать файл.

**Возвращает:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - Элемент DocumentPrivilege
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCopy() {#getCopy--}
```
public static DocumentPrivilege getCopy()
```


Позволяет копировать файл.

**Возвращает:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - Элемент DocumentPrivilege
### getDegradedPrinting() {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```


Допускает некачественную печать.

**Возвращает:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - Элемент DocumentPrivilege
### getFillIn() {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```


Позволяет заполнять формы в файле.

**Возвращает:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - Элемент DocumentPrivilege
### getForbidAll() {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```


Все Запрещено.

**Возвращает:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - Элемент DocumentPrivilege
### getModifyAnnotations() {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```


Позволяет изменять аннотации файла.

**Возвращает:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - Элемент DocumentPrivilege
### getModifyContents() {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```


Позволяет изменять файл.

**Возвращает:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - Элемент DocumentPrivilege
### getPrint() {#getPrint--}
```
public static DocumentPrivilege getPrint()
```


Позволяет распечатать файл.

**Возвращает:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - Элемент DocumentPrivilege
### getScreenReaders() {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```


Позволяет читать только на экране.

**Возвращает:**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - Элемент DocumentPrivilege
### getValue() {#getValue--}
```
public int getValue()
```


Получает значение

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public int hashCode()
```


 Возвращает значение хэш-кода для объекта. Этот метод поддерживается в интересах хэш-таблиц, таких как предоставляемые`java.util.Hashtable`.

 Генеральный договор`hashCode` является:

 *  Всякий раз, когда он вызывается для одного и того же объекта более одного раза во время выполнения приложения Java, метод hashCode должен постоянно возвращать одно и то же целое число, при условии, что никакая информация, используемая в сравнениях на равенство для объекта, не изменяется. Это целое число не обязательно должно оставаться постоянным от одного выполнения приложения к другому выполнению того же приложения.
 *  Если два объекта равны по методу equals(Object), то вызов метода`hashCode` Метод для каждого из двух объектов должен давать один и тот же целочисленный результат.
 *   это*not*требуется, чтобы, если два объекта не равны в соответствии с java.lang.Object\#equals(java.lang.Object).equals(java.lang.Object), то вызов метода hashCode для каждого из двух объектов должен давать различные целочисленные результаты. Однако программист должен знать, что получение различных целочисленных результатов для неравных объектов может повысить производительность хеш-таблиц.

Насколько это целесообразно, метод hashCode, определенный классом Object, действительно возвращает разные целые числа для разных объектов. (Обычно это реализуется путем преобразования внутреннего адреса объекта в целое число, но этот метод реализации не требуется для языка программирования JavaTM.)

**Возвращает:**
int - значение хеш-кода для этого объекта.
### isAllowAssembly() {#isAllowAssembly--}
```
public boolean isAllowAssembly()
```


Устанавливает разрешение, которое разрешает сборку или нет. true — разрешено, false — запрещено.

**Возвращает:**
boolean - логическое значение
### isAllowCopy() {#isAllowCopy--}
```
public boolean isAllowCopy()
```


Устанавливает разрешение, которое разрешает копирование или нет. true — разрешено, false — запрещено.

**Возвращает:**
boolean - логическое значение
### isAllowDegradedPrinting() {#isAllowDegradedPrinting--}
```
public boolean isAllowDegradedPrinting()
```


Устанавливает разрешение, которое разрешает печать с ухудшенным качеством или нет. true — разрешено, false — запрещено.

**Возвращает:**
boolean - логическое значение
### isAllowFillIn() {#isAllowFillIn--}
```
public boolean isAllowFillIn()
```


Устанавливает разрешение, позволяющее заполнять формы или нет. true — разрешено, false — запрещено.

**Возвращает:**
boolean - логическое значение
### isAllowModifyAnnotations() {#isAllowModifyAnnotations--}
```
public boolean isAllowModifyAnnotations()
```


Устанавливает разрешение, которое позволяет изменять аннотации или нет. true — разрешено, false — запрещено.

**Возвращает:**
boolean - логическое значение
### isAllowModifyContents() {#isAllowModifyContents--}
```
public boolean isAllowModifyContents()
```


Устанавливает разрешение, которое позволяет изменять содержимое или нет. true — разрешено, false — запрещено.

**Возвращает:**
boolean - логическое значение
### isAllowPrint() {#isAllowPrint--}
```
public boolean isAllowPrint()
```


Устанавливает разрешение, которое разрешает печать или нет. true — разрешено, false — запрещено.

**Возвращает:**
boolean - логическое значение
### isAllowScreenReaders() {#isAllowScreenReaders--}
```
public boolean isAllowScreenReaders()
```


Устанавливает разрешение, разрешающее или запрещающее чтение с экрана. true — разрешено, false — запрещено.

**Возвращает:**
boolean - логическое значение
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAllowAssembly(boolean value) {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```


Устанавливает разрешение, которое разрешает сборку или нет. true — разрешено, false — запрещено.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setAllowCopy(boolean value) {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```


Устанавливает разрешение, которое разрешает копирование или нет. true — разрешено, false — запрещено.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setAllowDegradedPrinting(boolean value) {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```


Устанавливает разрешение, которое разрешает печать с ухудшенным качеством или нет. true — разрешено, false — запрещено.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setAllowFillIn(boolean value) {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```


Устанавливает разрешение, позволяющее заполнять формы или нет. true — разрешено, false — запрещено.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setAllowModifyAnnotations(boolean value) {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```


Устанавливает разрешение, которое позволяет изменять аннотации или нет. true — разрешено, false — запрещено.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setAllowModifyContents(boolean value) {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```


Устанавливает разрешение, которое позволяет изменять содержимое или нет. true — разрешено, false — запрещено.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setAllowPrint(boolean value) {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```


Устанавливает разрешение, которое разрешает печать или нет. true — разрешено, false — запрещено.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setAllowScreenReaders(boolean value) {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```


Устанавливает разрешение, разрешающее или запрещающее чтение с экрана. true — разрешено, false — запрещено.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setChangeAllowLevel(int value) {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```


Устанавливает уровень изменения прав доступа к документу. Так же, как настройки разрешенных изменений Adobe Professional. 0: Нет. 1: Вставка, удаление и поворот страниц. 2: Заполнение полей формы и подписание существующих полей подписи. 3: Комментирование, заполнение полей формы и подписание существующих полей подписи. 4: Любой, кроме извлечения страниц.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setCopyAllowLevel(int value) {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```


Устанавливает уровень привилегий копирования документа. Так же, как настройки разрешений Adobe Professional. 0: Нет. 1: разрешить доступ к тексту для устройств чтения с экрана для слабовидящих. 2: Включить копирование текста, изображений и другого контента.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setPrintAllowLevel(int value) {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```


Устанавливает уровень привилегий печати документа. Так же, как настройки разрешенной печати Adobe Professional. 0: Нет. 1: Низкое разрешение (150 dpi). 2: Высокое разрешение.

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
