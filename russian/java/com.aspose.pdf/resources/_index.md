---
title: Resources
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий ресурсы страницы.
type: docs
weight: 310
url: /ru/java/com.aspose.pdf/resources/
---
**Наследование:**
java.lang.Object
```
public final class Resources
```

Класс, представляющий ресурсы страницы.
## Методы

| Метод | Описание |
| --- | --- |
| [clearImagesCache()](#clearImagesCache--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFonts()](#getFonts--) | Получает коллекцию ресурсов Fonts |
| [getFonts(boolean createIfAbsent)](#getFonts-boolean-) | Возвращает коллекцию шрифтов. |
| [getForms()](#getForms--) | Получает коллекцию форм Forms |
| [getImages()](#getImages--) | Получает коллекцию изображений изображений |
| [getResourcesFor(Form form)](#getResourcesFor-com.aspose.pdf.Form-) | Получает ресурсы для |
| [hashCode()](#hashCode--) |  |
| [isCommonResource()](#isCommonResource--) | Истинно, если эти ресурсы являются общими, т.е. общими для нескольких страниц (размещаются в словаре страниц или на каждой странице как ссылка на объект). Манипуляции с общими ресурсами должны выполняться очень осторожно, например, удаление объекта из общих ресурсов на одной странице может вызвать ошибки на других страницах если удаленный объект использовался для других страниц. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setResourceDictionary(IResourceDictionary resourceDictionary)](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | Только для внутреннего использования! |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearImagesCache() {#clearImagesCache--}
```
public final void clearImagesCache()
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
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Получает коллекцию ресурсов Fonts

**Возвращает:**
[FontCollection](../../com.aspose.pdf/fontcollection) - Объект FontCollection
### getFonts(boolean createIfAbsent) {#getFonts-boolean-}
```
public FontCollection getFonts(boolean createIfAbsent)
```


Возвращает коллекцию шрифтов. Если ресурсы не содержат запись о шрифтах, она будет создана в зависимости от флага CreateIfAbsent.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| createIfAbsent | boolean | Если этот флаг установлен, шрифты будут созданы, если эта запись отсутствует. |

**Возвращает:**
[FontCollection](../../com.aspose.pdf/fontcollection) - Коллекция шрифтов.
### getForms() {#getForms--}
```
public XFormCollection getForms()
```


Получает коллекцию форм Forms

**Возвращает:**
[XFormCollection](../../com.aspose.pdf/xformcollection) - Объект XFormCollection
### getImages() {#getImages--}
```
public XImageCollection getImages()
```


Получает коллекцию изображений изображений

**Возвращает:**
[XImageCollection](../../com.aspose.pdf/ximagecollection) - Объект XImageCollection
### getResourcesFor(Form form) {#getResourcesFor-com.aspose.pdf.Form-}
```
public static Resources getResourcesFor(Form form)
```


Получает ресурсы для

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| form | [Form](../../com.aspose.pdf/form) | Объект формы |

**Возвращает:**
[Resources](../../com.aspose.pdf/resources) - Объект ресурсов
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isCommonResource() {#isCommonResource--}
```
public boolean isCommonResource()
```


Истинно, если эти ресурсы являются общими, т.е. общими для нескольких страниц (размещаются в словаре страниц или на каждой странице как ссылка на объект). Манипуляции с общими ресурсами должны выполняться очень осторожно, например, удаление объекта из общих ресурсов на одной странице может вызвать ошибки на других страницах если удаленный объект использовался для других страниц.

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




### setResourceDictionary(IResourceDictionary resourceDictionary) {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
```
public void setResourceDictionary(IResourceDictionary resourceDictionary)
```


Только для внутреннего использования!

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| resourceDictionary | [IResourceDictionary](../../com.aspose.pdf.engine.commondata.pagecontent/iresourcedictionary) | внутренний экземпляр |

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
