---
title: SvgSaveOptions.SvgImageSavingInfo
second_title: Aspose.PDF для справки по Java API
description: Этот класс представляет собой набор данных, связанных с сохранением файлов изображений внешних ресурсов во время преобразования PDF в HTML.
type: docs
weight: 11
url: /ru/java/com.aspose.pdf/svgsaveoptions.svgimagesavinginfo/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.SaveOptions.ResourceSavingInfo](../../com.aspose.pdf/resourcesavinginfo)
```
public static class SvgSaveOptions.SvgImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

Этот класс представляет собой набор данных, связанных с сохранением файла изображения внешнего ресурса во время преобразования PDF в HTML.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SvgImageSavingInfo()](#SvgImageSavingInfo--) | создает новый экземпляр HtmlImageSavingInfo |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentStream()](#getContentStream--) | Устанавливается конвертером. |
| [getImageType()](#getImageType--) | представляют собой сохраненное изображение типа OS, на которое ссылается HTML. |
| [getResourceType()](#getResourceType--) | Устанавливается конвертером. |
| [getSupposedFileName()](#getSupposedFileName--) | Устанавливается конвертером. |
| [hashCode()](#hashCode--) |  |
| [isCustomProcessingCancelled()](#isCustomProcessingCancelled--) | этот флаг должен быть установлен в "true" в пользовательском коде, если по каким-либо причинам предлагаемый файл должен обрабатываться не пользовательским кодом, а самим кодом конвертера стандартным для конвертера способом. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProcessingCancelled(boolean customProcessingCancelled)](#setCustomProcessingCancelled-boolean-) | этот флаг должен быть установлен в "true" в пользовательском коде, если по каким-либо причинам предлагаемый файл должен обрабатываться не пользовательским кодом, а самим кодом конвертера стандартным для конвертера способом. |
| [setImageType(int imageType)](#setImageType-int-) | представляют собой сохраненное изображение типа OS, на которое ссылается HTML. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SvgImageSavingInfo() {#SvgImageSavingInfo--}
```
public SvgImageSavingInfo()
```


создает новый экземпляр HtmlImageSavingInfo

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
### getContentStream() {#getContentStream--}
```
public byte[] getContentStream()
```


Устанавливается конвертером. Представляет двоичное содержимое сохраненного файла.

**Возвращает:**
байт[] - массив байтов
### getImageType() {#getImageType--}
```
public int getImageType()
```


представляют собой сохраненное изображение типа OS, на которое ссылается HTML. Устанавливается преобразователем и может использоваться в пользовательском коде, чтобы решить, что следует делать.

**Возвращает:**
int — элемент SvgExternalImageType
### getResourceType() {#getResourceType--}
```
public int getResourceType()
```


Устанавливается конвертером. Предполагаемое имя файла, которое переходит от преобразователя к коду пользовательского метода. Может использоваться в пользовательском коде, чтобы решить, как обрабатывать или где сохранить этот файл.

**Возвращает:**
int - элемент NodeLevelResourceType
### getSupposedFileName() {#getSupposedFileName--}
```
public String getSupposedFileName()
```


Устанавливается конвертером. Предполагаемое имя файла, которое переходит от преобразователя к коду пользовательского метода. Может использоваться в пользовательском коде, чтобы решить, как обрабатывать или где сохранить этот файл.

**Возвращает:**
java.lang.String — строковое значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isCustomProcessingCancelled() {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```


этот флаг должен быть установлен в "true" в пользовательском коде, если по каким-либо причинам предлагаемый файл должен обрабатываться не пользовательским кодом, а самим кодом конвертера стандартным для конвертера способом. Таким образом, установка значения true означает, что пользовательский код не обрабатывал ссылочный файл, и конвертер должен обработать его сам (в обоих смыслах - для сохранения куда-либо и для именования в ссылочном файле).

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




### setCustomProcessingCancelled(boolean customProcessingCancelled) {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```


этот флаг должен быть установлен в "true" в пользовательском коде, если по каким-либо причинам предлагаемый файл должен обрабатываться не пользовательским кодом, а самим кодом конвертера стандартным для конвертера способом. Таким образом, его установка в true означает, что пользовательский код не обрабатывал ссылочный файл, и конвертер должен обрабатывать его сам (в обоих смыслах - для сохранения куда-то и для именования в ссылочном файле).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| customProcessingCancelled | boolean | логическое значение |

### setImageType(int imageType) {#setImageType-int-}
```
public void setImageType(int imageType)
```


представляют собой сохраненное изображение типа OS, на которое ссылается HTML. Устанавливается преобразователем и может использоваться в пользовательском коде, чтобы решить, что следует делать.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageType | int | Элемент SvgExternalImageType |

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
