---
title: HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF для справки по Java API
description: Этот класс представляет собой набор данных, связанных с сохранением файлов изображений внешних ресурсов во время преобразования PDF в HTML.
type: docs
weight: 17
url: /ru/java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.SaveOptions.ResourceSavingInfo](../../com.aspose.pdf/resourcesavinginfo)
```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

Этот класс представляет собой набор данных, связанных с сохранением файла изображения внешнего ресурса во время преобразования PDF в HTML.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HtmlImageSavingInfo()](#HtmlImageSavingInfo--) | создает новый экземпляр HtmlImageSavingInfo |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentStream()](#getContentStream--) | Устанавливается конвертером. |
| [getHtmlHostPageNumber()](#getHtmlHostPageNumber--) | Сообщает пользовательскому коду, к какой странице сгенерированного набора HTML-файлов страниц относится сохраненное изображение. |
| [getImageType()](#getImageType--) | Представляет тип сохраненного изображения, на которое ссылается HTML. |
| [getParentType()](#getParentType--) | Сохраненное изображение может принадлежать самому HTML или может быть извлечено. из SVG, встроенного в HTML. |
| [getPdfHostPageNumber()](#getPdfHostPageNumber--) | Сообщает пользовательскому коду, к какой странице исходного PDF-документа относится сохраненное изображение. Поскольку возможно, что будут сохранены не все страницы исходного документа, это значение говорит нам о номере главной страницы в исходном PDF-файле. |
| [getResourceType()](#getResourceType--) | Устанавливается конвертером. |
| [getSupposedFileName()](#getSupposedFileName--) | Устанавливается конвертером. |
| [hashCode()](#hashCode--) |  |
| [isCustomProcessingCancelled()](#isCustomProcessingCancelled--) | этот флаг должен быть установлен в "true" в пользовательском коде, если по каким-либо причинам предлагаемый файл должен обрабатываться не пользовательским кодом, а самим кодом конвертера стандартным для конвертера способом. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomProcessingCancelled(boolean customProcessingCancelled)](#setCustomProcessingCancelled-boolean-) | этот флаг должен быть установлен в "true" в пользовательском коде, если по каким-либо причинам предлагаемый файл должен обрабатываться не пользовательским кодом, а самим кодом конвертера стандартным для конвертера способом. |
| [setHtmlHostPageNumber(int htmlHostPageNumber)](#setHtmlHostPageNumber-int-) | Сообщает пользовательскому коду, к какой странице сгенерированного набора HTML-файлов страниц относится сохраненное изображение. |
| [setImageType(int imageType)](#setImageType-int-) | Представляет тип сохраненного изображения, на которое ссылается HTML. |
| [setParentType(int parentType)](#setParentType-int-) | Сохраненное изображение может принадлежать самому HTML или может быть извлечено. из SVG, встроенного в HTML. |
| [setPdfHostPageNumber(int pdfHostPageNumber)](#setPdfHostPageNumber-int-) | Сообщает пользовательскому коду, к какой странице исходного PDF-документа относится сохраненное изображение. Поскольку возможно, что будут сохранены не все страницы исходного документа, это значение говорит нам о номере главной страницы в исходном PDF-файле. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlImageSavingInfo() {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
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
### getHtmlHostPageNumber() {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```


Сообщает пользовательскому коду, к какой странице сгенерированного набора HTML-файлов страниц относится сохраненное изображение. Если разбиение на страницы отключено, это значение всегда содержит '1', т.к. в этом случае генерируется только одна HTML-страница.

**Возвращает:**
интервал - целочисленное значение
### getImageType() {#getImageType--}
```
public int getImageType()
```


Представляет тип сохраненного изображения, на которое ссылается HTML. Устанавливается преобразователем и может использоваться в пользовательском коде, чтобы решить, что следует делать.

**Возвращает:**
int — элемент HtmlImageType
### getParentType() {#getParentType--}
```
public int getParentType()
```


Сохраненное изображение может принадлежать самому HTML или может быть извлечено. из SVG, встроенного в HTML. Это свойство может сообщить пользовательскому коду, что это за тип родителя обрабатываемого изображения. Он устанавливается конвертером и может использоваться в пользовательском коде, чтобы решить, что следует делать с этим изображением (например, пользовательский код может решить, где сохранить изображение или как на него следует ссылаться в родительском контенте).

**Возвращает:**
int — элемент ImageParentTypes
### getPdfHostPageNumber() {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```


Сообщает пользовательскому коду, к какой странице исходного PDF-документа относится сохраненное изображение. Поскольку возможно, что будут сохранены не все страницы исходного документа, это значение говорит нам о номере главной страницы в исходном PDF-файле. Если исходный номер страницы по какой-либо причине неизвестен, он всегда возвращает «1».

**Возвращает:**
интервал - целочисленное значение
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

### setHtmlHostPageNumber(int htmlHostPageNumber) {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```


Сообщает пользовательскому коду, к какой странице сгенерированного набора HTML-файлов страниц относится сохраненное изображение. Если разбиение на страницы отключено, это значение всегда содержит '1', т.к. в этом случае генерируется только одна HTML-страница.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlHostPageNumber | int | целое значение |

### setImageType(int imageType) {#setImageType-int-}
```
public void setImageType(int imageType)
```


Представляет тип сохраненного изображения, на которое ссылается HTML. Устанавливается преобразователем и может использоваться в пользовательском коде, чтобы решить, что следует делать.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageType | int | Элемент HtmlImageType |

### setParentType(int parentType) {#setParentType-int-}
```
public void setParentType(int parentType)
```


Сохраненное изображение может принадлежать самому HTML или может быть извлечено. из SVG, встроенного в HTML. Это свойство может сообщить пользовательскому коду, что это за тип родителя обрабатываемого изображения. Он устанавливается конвертером и может использоваться в пользовательском коде, чтобы решить, что следует делать с этим изображением (например, пользовательский код может решить, где сохранить изображение или как на него следует ссылаться в родительском контенте).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| parentType | int | Элемент ImageParentTypes |

### setPdfHostPageNumber(int pdfHostPageNumber) {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```


Сообщает пользовательскому коду, к какой странице исходного PDF-документа относится сохраненное изображение. Поскольку возможно, что будут сохранены не все страницы исходного документа, это значение говорит нам о номере главной страницы в исходном PDF-файле. Если исходный номер страницы по какой-либо причине неизвестен, он всегда возвращает «1».

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfHostPageNumber | int | целое значение |

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
