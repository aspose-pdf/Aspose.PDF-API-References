---
title: HtmlLoadOptions
second_title: Aspose.PDF для справки по Java API
description: Представляет параметры загрузки/импорта html-файла в pdf-документ.
type: docs
weight: 158
url: /ru/java/com.aspose.pdf/htmlloadoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class HtmlLoadOptions extends LoadOptions
```

Представляет параметры загрузки/импорта html-файла в pdf-документ.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HtmlLoadOptions()](#HtmlLoadOptions--) | Создает параметры загрузки для преобразования html в документ pdf с пустым базовым путем. |
| [HtmlLoadOptions(String basePath)](#HtmlLoadOptions-java.lang.String-) | Создает параметры загрузки для преобразования html в документ pdf с определенным базовым путем. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBasePath()](#getBasePath--) | Базовый путь/URL для html-файла. |
| [getClass()](#getClass--) |  |
| [getCustomLoaderOfExternalResources()](#getCustomLoaderOfExternalResources--) | Иногда необходимо избегать использования внутреннего загрузчика внешних ресурсов (таких как изображения или CSS) и предоставлять собственный метод, который откуда-то будет получать запрошенные ресурсы. |
| [getHtmlMediaType()](#getHtmlMediaType--) | Получает или задает возможные типы мультимедиа, используемые во время рендеринга. |
| [getInputEncoding()](#getInputEncoding--) | Получает атрибут, указывающий кодировку, используемую для этого документа во время синтаксического анализа. |
| [getLoadFormat()](#getLoadFormat--) | Представляет формат файла, который описывает LoadOptions. |
| [getPageInfo()](#getPageInfo--) | Получает информацию о странице документа |
| [getPageLayoutOption()](#getPageLayoutOption--) | Получает или задает параметр макета. |
| [getWarningHandler()](#getWarningHandler--) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [hashCode()](#hashCode--) |  |
| [isEmbedFonts()](#isEmbedFonts--) | Получает или задает встроенные шрифты в результирующий документ |
| [isRenderToSinglePage()](#isRenderToSinglePage--) | Получает или задает отображение всего документа на одной странице |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomLoaderOfExternalResources(LoadOptions.ResourceLoadingStrategy customLoaderOfExternalResources)](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | Иногда необходимо избегать использования внутреннего загрузчика внешних ресурсов (таких как изображения или CSS) и предоставлять собственный метод, который откуда-то будет получать запрошенные ресурсы. |
| [setEmbedFonts(boolean value)](#setEmbedFonts-boolean-) | Получает или задает встроенные шрифты в результирующий документ |
| [setHtmlMediaType(int value)](#setHtmlMediaType-int-) | Получает или задает возможные типы мультимедиа, используемые во время рендеринга. |
| [setInputEncoding(String value)](#setInputEncoding-java.lang.String-) | Задает атрибут, указывающий кодировку, используемую для этого документа во время синтаксического анализа. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Устанавливает информацию о странице документа |
| [setPageLayoutOption(int value)](#setPageLayoutOption-int-) | Получает или задает параметр макета. |
| [setRenderToSinglePage(boolean value)](#setRenderToSinglePage-boolean-) | Получает или задает отображение всего документа на одной странице |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlLoadOptions() {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```


Создает параметры загрузки для преобразования html в документ pdf с пустым базовым путем.

### HtmlLoadOptions(String basePath) {#HtmlLoadOptions-java.lang.String-}
```
public HtmlLoadOptions(String basePath)
```


Создает параметры загрузки для преобразования html в документ pdf с определенным базовым путем.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| basePath | java.lang.String | Базовый путь/URL для html-файла. |

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
### getBasePath() {#getBasePath--}
```
public String getBasePath()
```


Базовый путь/URL для html-файла.

**Возвращает:**
java.lang.String — строковое значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCustomLoaderOfExternalResources() {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```


Иногда необходимо избегать использования внутреннего загрузчика внешних ресурсов (таких как изображения или CSS) и предоставлять собственный метод, который откуда-то будет получать запрошенные ресурсы. Например, при использовании Aspose.PDF в облаке прямой доступ к файлам, на которые ссылаются, невозможен: в таком случае необходимо использовать какой-либо код заказчика, помещенный в специальный метод, а делегат, который ссылается на этот метод, должен быть назначен этому атрибуту.

**Возвращает:**
[ResourceLoadingStrategy](../../com.aspose.pdf/resourceloadingstrategy) - Экземпляр ResourceLoadingStrategy
### getHtmlMediaType() {#getHtmlMediaType--}
```
public int getHtmlMediaType()
```


Получает или задает возможные типы мультимедиа, используемые во время рендеринга.

**Возвращает:**
int — элемент HtmlMediaType
### getInputEncoding() {#getInputEncoding--}
```
public String getInputEncoding()
```


Получает атрибут, указывающий кодировку, используемую для этого документа во время синтаксического анализа. Если этот атрибут равен нулю, кодировка будет определяться атрибутом набора символов документа.

**Возвращает:**
java.lang.String — строковое значение
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


Представляет формат файла, который описывает LoadOptions.

**Возвращает:**
[LoadFormat](../../com.aspose.pdf/loadformat) - Элемент формата загрузки
### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


Получает информацию о странице документа

**Возвращает:**
[PageInfo](../../com.aspose.pdf/pageinfo) - информация о странице
### getPageLayoutOption() {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```


Получает или задает параметр макета.

**Возвращает:**
int — элемент HtmlPageLayoutOption
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. Продолжить — это действие по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть команду Abort, и в этом случае операция загрузки должна быть прекращена.

**Возвращает:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - Значение IWarningCallback
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isEmbedFonts() {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```


Получает или задает встроенные шрифты в результирующий документ

**Возвращает:**
boolean - логическое значение
### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```


Получает или задает отображение всего документа на одной странице

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




### setCustomLoaderOfExternalResources(LoadOptions.ResourceLoadingStrategy customLoaderOfExternalResources) {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
```
public void setCustomLoaderOfExternalResources(LoadOptions.ResourceLoadingStrategy customLoaderOfExternalResources)
```


Иногда необходимо избегать использования внутреннего загрузчика внешних ресурсов (таких как изображения или CSS) и предоставлять собственный метод, который откуда-то будет получать запрошенные ресурсы. Например, при использовании Aspose.PDF в облаке прямой доступ к файлам, на которые ссылаются, невозможен: в таком случае необходимо использовать какой-либо код заказчика, помещенный в специальный метод, а делегат, который ссылается на этот метод, должен быть назначен этому атрибуту.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| customLoaderOfExternalResources | [ResourceLoadingStrategy](../../com.aspose.pdf/resourceloadingstrategy) | Экземпляр ResourceLoadingStrategy |

### setEmbedFonts(boolean value) {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```


Получает или задает встроенные шрифты в результирующий документ

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setHtmlMediaType(int value) {#setHtmlMediaType-int-}
```
public void setHtmlMediaType(int value)
```


Получает или задает возможные типы мультимедиа, используемые во время рендеринга.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент HtmlMediaType |

### setInputEncoding(String value) {#setInputEncoding-java.lang.String-}
```
public void setInputEncoding(String value)
```


Задает атрибут, указывающий кодировку, используемую для этого документа во время синтаксического анализа. Если этот атрибут равен нулю, кодировка будет определяться атрибутом набора символов документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


Устанавливает информацию о странице документа

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | информация о странице |

### setPageLayoutOption(int value) {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```


Получает или задает параметр макета.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент HtmlPageLayoutOption |

### setRenderToSinglePage(boolean value) {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```


Получает или задает отображение всего документа на одной странице

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. Продолжить — это действие по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть команду Abort, и в этом случае операция загрузки должна быть прекращена.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | Значение IWarningCallback |

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
