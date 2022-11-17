---
title: XFA
second_title: Aspose.PDF для справки по Java API
description: Представляет XML-форму относительно XML Forms Architecture XFA.
type: docs
weight: 406
url: /ru/java/com.aspose.pdf/xfa/
---
**Наследование:**
java.lang.Object
```
public final class XFA
```

Представляет XML-форму с учетом архитектуры XML-форм (XFA).
## Методы

| Метод | Описание |
| --- | --- |
| [beginCachedUpdates()](#beginCachedUpdates--) | Запустите режим кэшированных обновлений. |
| [endCachedUpdates()](#endCachedUpdates--) | Завершает кэшированные обновления и сохраняет все данные в структуру документа. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flattenXfaField(System.Xml.XmlNode field)](#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-) | Выравнивание поля формы XFA. |
| [getClass()](#getClass--) |  |
| [getConfig()](#getConfig--) | Компонент XFA Config формы XFA. |
| [getDatasets()](#getDatasets--) | Компонент наборов данных XFA формы XFA. |
| [getFieldNames()](#getFieldNames--) | Список имен полей в шаблоне формы. |
| [getFieldTemplate(String fieldName)](#getFieldTemplate-java.lang.String-) | Возвращает узел XML шаблона поля XFA. |
| [getFieldTemplates()](#getFieldTemplates--) | Возвращает список всех шаблонов полей в форме XFA. |
| [getFieldsWithTextValuesMap()](#getFieldsWithTextValuesMap--) | Возвращает карту с коротким именем поля и его строковым значением для всех полей. |
| [getForm()](#getForm--) | Получает компонент формы XFA формы XFA. |
| [getNamespaceManager()](#getNamespaceManager--) | Возвращает диспетчер пространств имен с пространствами имен, используемыми для шаблона и данных. |
| [getNamespaceManager_()](#getNamespaceManager---) | Получает пространство имен для формы XFA. |
| [getTemplate()](#getTemplate--) | Компонент шаблона XFA формы XFA. |
| [getXDP()](#getXDP--) | Пакет данных XML (все компоненты формы XFA в окружающем XML-контейнере). |
| [getXfaField(String path)](#getXfaField-java.lang.String-) |  |
| [get_Item(String path)](#get-Item-java.lang.String-) | Получает значение узла данных по пути. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFieldImage(String fieldName, InputStream image)](#setFieldImage-java.lang.String-java.io.InputStream-) | Задает изображение для поля XFA. |
| [setFieldImageInternal(String fieldName, System.IO.Stream image)](#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [set_Item(String path, String value)](#set-Item-java.lang.String-java.lang.String-) | Получает значение узла данных по пути. |
| [toString()](#toString--) |  |
| [tryGetTemplateString(String value)](#tryGetTemplateString-java.lang.String-) | Пытается экспортировать сценарий расчета из формы XFA. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### beginCachedUpdates() {#beginCachedUpdates--}
```
public void beginCachedUpdates()
```


Запустите режим кэшированных обновлений. Все изменения, внесенные в XFA, будут кэшированы и сохранены в структуре документа при вызове EndCachedUpdates. Это позволяет улучшить преформирование, избегая избыточных операций по сохранению XML-пакетов в документ при внесении большого количества изменений в XFA.

### endCachedUpdates() {#endCachedUpdates--}
```
public void endCachedUpdates()
```


Завершает кэшированные обновления и сохраняет все данные в структуру документа.

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
### flattenXfaField(System.Xml.XmlNode field) {#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-}
```
public static void flattenXfaField(System.Xml.XmlNode field)
```


Выравнивание поля формы XFA.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | com.aspose.ms.System.Xml.XmlNode | Узел поля формы XFA. |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getConfig() {#getConfig--}
```
public System.Xml.XmlNode getConfig()
```


Компонент XFA Config формы XFA.

**Возвращает:**
com.aspose.ms.System.Xml.XmlNode — объект XmlNode
### getDatasets() {#getDatasets--}
```
public System.Xml.XmlNode getDatasets()
```


Компонент наборов данных XFA формы XFA.

**Возвращает:**
com.aspose.ms.System.Xml.XmlNode — объект XmlNode
### getFieldNames() {#getFieldNames--}
```
public String[] getFieldNames()
```


Список имен полей в шаблоне формы.

**Возвращает:**
java.lang.String[] - массив строковых значений
### getFieldTemplate(String fieldName) {#getFieldTemplate-java.lang.String-}
```
public System.Xml.XmlNode getFieldTemplate(String fieldName)
```


Возвращает узел XML шаблона поля XFA.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Путь к полю, шаблон которого необходимо найти. |

**Возвращает:**
com.aspose.ms.System.Xml.XmlNode — узел XL с шаблоном поля.
### getFieldTemplates() {#getFieldTemplates--}
```
public System.Xml.XmlNodeList getFieldTemplates()
```


Возвращает список всех шаблонов полей в форме XFA.

**Возвращает:**
com.aspose.ms.System.Xml.XmlNodeList — список шаблонов полей.
### getFieldsWithTextValuesMap() {#getFieldsWithTextValuesMap--}
```
public HashMap<String,String> getFieldsWithTextValuesMap()
```


Возвращает карту с коротким именем поля и его строковым значением для всех полей.

**Возвращает:**
java.util.HashMap<java.lang.String,java.lang.String> — объект HashMap
### getForm() {#getForm--}
```
public System.Xml.XmlNode getForm()
```


Получает компонент формы XFA формы XFA.

**Возвращает:**
com.aspose.ms.System.Xml.XmlNode — объект XmlNode
### getNamespaceManager() {#getNamespaceManager--}
```
public System.Xml.XmlNamespaceManager getNamespaceManager()
```


Возвращает диспетчер пространств имен с пространствами имен, используемыми для шаблона и данных.

**Возвращает:**
com.aspose.ms.System.Xml.XmlNamespaceManager — объект XmlNamespaceManager
### getNamespaceManager_() {#getNamespaceManager---}
```
public System.Xml.XmlNamespaceManager getNamespaceManager_()
```


Получает пространство имен для формы XFA. Определены следующие пространства имен: "data" для данных формы и "tpl" для шаблона формы.

**Возвращает:**
com.aspose.ms.System.Xml.XmlNamespaceManager — объект XmlNamespaceManager
### getTemplate() {#getTemplate--}
```
public System.Xml.XmlNode getTemplate()
```


Компонент шаблона XFA формы XFA.

**Возвращает:**
com.aspose.ms.System.Xml.XmlNode — объект XmlNode
### getXDP() {#getXDP--}
```
public System.Xml.XmlDocument getXDP()
```


Пакет данных XML (все компоненты формы XFA в окружающем XML-контейнере).

**Возвращает:**
com.aspose.ms.System.Xml.XmlDocument — объект XmlDocument
### getXfaField(String path) {#getXfaField-java.lang.String-}
```
public final XfaFieldInteractive getXfaField(String path)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String |  |

**Возвращает:**
com.aspose.pdf.XfaFieldInteractive
### get_Item(String path) {#get-Item-java.lang.String-}
```
public String get_Item(String path)
```


Получает значение узла данных по пути.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь к узлу данных, например form1[0].Подчиненная1[0].Подчиненная2[0].Подформа3[0].Текстовое поле[0]. Обязательно включите индексы, даже если данные содержат только единичные вхождения каждого узла, т.е. запишите node1[0].узел2[0]... вместо node1.node2... |

**Возвращает:**
java.lang.String — значение узла данных.
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




### setFieldImage(String fieldName, InputStream image) {#setFieldImage-java.lang.String-java.io.InputStream-}
```
public void setFieldImage(String fieldName, InputStream image)
```


Задает изображение для поля XFA.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля. |
| image | java.io.InputStream | Поток, содержащий изображение. |

### setFieldImageInternal(String fieldName, System.IO.Stream image) {#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public void setFieldImageInternal(String fieldName, System.IO.Stream image)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String |  |
| image | com.aspose.ms.System.IO.Stream |  |

### set_Item(String path, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public void set_Item(String path, String value)
```


Получает значение узла данных по пути.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Строковое значение |
| value | java.lang.String | Строковое значение |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### tryGetTemplateString(String value) {#tryGetTemplateString-java.lang.String-}
```
public String tryGetTemplateString(String value)
```


Пытается экспортировать сценарий расчета из формы XFA. В противном случае возвращает пустую строку;

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Имя тега |

**Возвращает:**
java.lang.String — экземпляр строки
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
