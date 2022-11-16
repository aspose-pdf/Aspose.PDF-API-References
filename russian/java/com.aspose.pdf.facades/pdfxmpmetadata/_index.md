---
title: PdfXmpMetadata
second_title: Aspose.PDF для справки по Java API
description: Класс для работы с метаданными XMP.
type: docs
weight: 54
url: /ru/java/com.aspose.pdf.facades/pdfxmpmetadata/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)

**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary
```
public final class PdfXmpMetadata extends SaveableFacade implements System.Collections.Generic.IGenericDictionary<String,XmpValue>
```

Класс для работы с метаданными XMP.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfXmpMetadata()](#PdfXmpMetadata--) | Конструктор для PdfXmpMetadata. |
| [PdfXmpMetadata(IDocument document)](#PdfXmpMetadata-com.aspose.pdf.IDocument-) | Инициализирует новый объект PdfXmpMetadata на основе документа. |
## Методы

| Метод | Описание |
| --- | --- |
| [add(XmpPdfAExtensionObject xmpPdfAExtensionObject, String namespacePrefix, String namespaceUri, String schemaDescription)](#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-) | Добавляет поле расширения в метаданные. |
| [addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | Добавляет пару с ключом и значением в словарь. |
| [addItem(int key, XmpValue value)](#addItem-int-com.aspose.pdf.XmpValue-) | Добавляет ценность метаданным XMP. |
| [addItem(String key, XmpValue value)](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | Добавляет новый элемент в объект словаря. |
| [addItem(String key, Object value)](#addItem-java.lang.String-java.lang.Object-) | Добавляет новый элемент в объект словаря. |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Инициализирует фасад. |
| [clear()](#clear--) | Удаляет все элементы из объекта. |
| [close()](#close--) | Удаляет документ, связанный с фасадом. |
| [contains(int property)](#contains-int-) | Проверяет, содержит ли словарь указанное свойство. |
| [contains(String key)](#contains-java.lang.String-) | Проверяет, содержит ли словарь указанный ключ. |
| [containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | Проверяет, содержится ли указанная пара ключ-значение в словаре. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Определяет, содержит ли этот словарь указанный ключ. |
| [copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue----int-) | Скопируйте метаданные в массив. |
| [dispose()](#dispose--) | Располагает фасад. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getByDefaultMetadataProperties(int key)](#getByDefaultMetadataProperties-int-) | Получает значение метаданных XMP по ключу. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Получает фасад документа, над которым работает. |
| [getExtensionFields()](#getExtensionFields--) | Получает словарь полей расширения. |
| [getKeys()](#getKeys--) | Получает ключи из словаря. |
| [getNamespaceURIByPrefix(String prefix)](#getNamespaceURIByPrefix-java.lang.String-) | Получает URI пространства имен по префиксу. |
| [getPrefixByNamespaceURI(String namespaceURI)](#getPrefixByNamespaceURI-java.lang.String-) | Получает префикс по URI пространства имен. |
| [getSyncRoot()](#getSyncRoot--) | Получает объект синхронизации коллекции. |
| [getValues()](#getValues--) | Получает коллекцию значений в словаре. |
| [getXmpMetadata()](#getXmpMetadata--) | Получите XmpMetadata входного PDF-файла в формате xml. |
| [getXmpMetadata(String name)](#getXmpMetadata-java.lang.String-) | Получите часть XmpMetadata входного PDF-файла в соответствии с мета-именем. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Получает значение по ключу. |
| [hashCode()](#hashCode--) |  |
| [isFixedSize()](#isFixedSize--) | Возвращает true, если коллекция имеет фиксированный размер. |
| [isReadOnly()](#isReadOnly--) | Возвращает true, если коллекция доступна только для чтения. |
| [isSynchronized()](#isSynchronized--) | Возвращает true, если коллекция синхронизирована. |
| [iterator()](#iterator--) | Получает объект перечислителя словаря. |
| [iteratorIt()](#iteratorIt--) | Получает объект перечислителя коллекции. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceURI(String prefix, String namespaceURI)](#registerNamespaceURI-java.lang.String-java.lang.String-) | Регистрирует URI пространства имен. |
| [removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | Удаляет пару ключ/значение из коллекции. |
| [removeItemByKey(int key)](#removeItemByKey-int-) | Удаляет элемент с указанным ключом. |
| [removeItemByKey(String key)](#removeItemByKey-java.lang.String-) | Удаляет ключ из словаря. |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Сохраняет документ PDF в указанный поток. |
| [save(String destFile)](#save-java.lang.String-) | Сохраняет документ PDF в указанный файл. |
| [setByDefaultMetadataProperties(int key, XmpValue value)](#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-) | Устанавливает значение метаданных XMP по ключу. |
| [set_Item(String key, XmpValue value)](#set-Item-java.lang.String-com.aspose.pdf.XmpValue-) | Устанавливает значение по ключу. |
| [size()](#size--) | Получает количество элементов в коллекции. |
| [toString()](#toString--) |  |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | Пытается найти ключ в словаре и извлекает значение, если оно найдено. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfXmpMetadata() {#PdfXmpMetadata--}
```
public PdfXmpMetadata()
```


Конструктор для PdfXmpMetadata.

--------------------

```
PdfXmlMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
```

### PdfXmpMetadata(IDocument document) {#PdfXmpMetadata-com.aspose.pdf.IDocument-}
```
public PdfXmpMetadata(IDocument document)
```


Инициализирует новый объект PdfXmpMetadata на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |

### add(XmpPdfAExtensionObject xmpPdfAExtensionObject, String namespacePrefix, String namespaceUri, String schemaDescription) {#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-}
```
public void add(XmpPdfAExtensionObject xmpPdfAExtensionObject, String namespacePrefix, String namespaceUri, String schemaDescription)
```


Добавляет поле расширения в метаданные.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmpPdfAExtensionObject | [XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject) | Объект расширения pdf для добавления. |
| namespacePrefix | java.lang.String | Префикс схемы. |
| namespaceUri | java.lang.String | URI пространства имен схемы. |
| schemaDescription | java.lang.String | Необязательное описание схемы. |

### addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public void addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


Добавляет пару с ключом и значением в словарь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | Товар, который нужно добавить. |

### addItem(int key, XmpValue value) {#addItem-int-com.aspose.pdf.XmpValue-}
```
public void addItem(int key, XmpValue value)
```


Добавляет ценность метаданным XMP.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.add(DefaultMetadataProperties.Nickname, "name1");
 xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | int | Ключевое имя. |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | Значение, которое будет добавлено. |

### addItem(String key, XmpValue value) {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
```
public void addItem(String key, XmpValue value)
```


Добавляет новый элемент в объект словаря.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.add("xmp:Nickname", "Nickname1");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ нового элемента. |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | Значение элемента. |

### addItem(String key, Object value) {#addItem-java.lang.String-java.lang.Object-}
```
public void addItem(String key, Object value)
```


Добавляет новый элемент в объект словаря.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ нового элемента. |
| value | java.lang.Object | Значение элемента. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | Объект Документ. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Поток файла PDF. |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Поток файла PDF. |
| password | java.lang.String | Пароль документа PDF. |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFile | java.lang.String | PDF-файл. |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFile | java.lang.String | PDF-файл |
| password | java.lang.String | Пароль документа PDF. |

### clear() {#clear--}
```
public void clear()
```


Удаляет все элементы из объекта.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.clear();
```

### close() {#close--}
```
public void close()
```


Удаляет документ, связанный с фасадом.

### contains(int property) {#contains-int-}
```
public boolean contains(int property)
```


Проверяет, содержит ли словарь указанное свойство.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| property | int | Недвижимость, которая будет проверена. |

**Возвращает:**
boolean - True - если словарь содержит указанное свойство; в противном случае ложно.
### contains(String key) {#contains-java.lang.String-}
```
public boolean contains(String key)
```


Проверяет, содержит ли словарь указанный ключ.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.add("xmp:Nickname", "Nickname1");
 if (!xmp.contains("xmp:Nickname"))
   System.out.println("Key does not exists");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ, который будет проверяться. |

**Возвращает:**
boolean - True - если словарь содержит указанный ключ; в противном случае ложно.
### containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public boolean containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


Проверяет, содержится ли указанная пара ключ-значение в словаре.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | Пара ключ-значение. |

**Возвращает:**
boolean - true, если этот файл был найден.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Определяет, содержит ли этот словарь указанный ключ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ для поиска в словаре. |

**Возвращает:**
boolean - истина, если ключ найден.
### copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index) {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue----int-}
```
public void copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index)
```


Скопируйте метаданные в массив.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>[] | Целевой массив. |
| index | int | Начальный индекс. |

### dispose() {#dispose--}
```
public void dispose()
```


Располагает фасад.

Этот метод устарел, вместо него используйте close().

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
### getByDefaultMetadataProperties(int key) {#getByDefaultMetadataProperties-int-}
```
public XmpValue getByDefaultMetadataProperties(int key)
```


Получает значение метаданных XMP по ключу.

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | int | Ключ значения. |

**Возвращает:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - Значение из метаданных XMP.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Получает фасад документа, над которым работает.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - элемент IDocument
### getExtensionFields() {#getExtensionFields--}
```
public Hashtable<String,XmpPdfAExtensionSchema> getExtensionFields()
```


Получает словарь полей расширения.

**Возвращает:**
java.util.Hashtable<java.lang.String,com.aspose.pdf.XmpPdfAExtensionSchema> — объект Hashtable
### getKeys() {#getKeys--}
```
public System.Collections.Generic.IGenericCollection<String> getKeys()
```


Получает ключи из словаря.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<java.lang.String> — элемент ICollection
### getNamespaceURIByPrefix(String prefix) {#getNamespaceURIByPrefix-java.lang.String-}
```
public String getNamespaceURIByPrefix(String prefix)
```


Получает URI пространства имен по префиксу.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
 System.out.println(xmp.getNamespaceURIByPrefix("xmp"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | java.lang.String | Префикс. |

**Возвращает:**
java.lang.String — URI пространства имен.
### getPrefixByNamespaceURI(String namespaceURI) {#getPrefixByNamespaceURI-java.lang.String-}
```
public String getPrefixByNamespaceURI(String namespaceURI)
```


Получает префикс по URI пространства имен.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
 System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| namespaceURI | java.lang.String | URI пространства имен. |

**Возвращает:**
java.lang.String — значение префикса.
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Получает объект синхронизации коллекции.

**Возвращает:**
java.lang.Object — элемент объекта
### getValues() {#getValues--}
```
public System.Collections.Generic.IGenericCollection<XmpValue> getValues()
```


Получает коллекцию значений в словаре.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.pdf.XmpValue> — объект ICollection
### getXmpMetadata() {#getXmpMetadata--}
```
public byte[] getXmpMetadata()
```


Получите XmpMetadata входного PDF-файла в формате xml.

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 byte[] data = pxm.getXmpMetadata();
```

**Возвращает:**
байт[] — байты XmpMetadata.
### getXmpMetadata(String name) {#getXmpMetadata-java.lang.String-}
```
public byte[] getXmpMetadata(String name)
```


Получите часть XmpMetadata входного PDF-файла в соответствии с мета-именем.

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 byte[] data = pxm.getXmpMetadata("dc:creator");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя метаданных. |

**Возвращает:**
байт[] - Байты метаданных.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public XmpValue get_Item(String key)
```


Получает значение по ключу.

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 System.out.println(pxm.get_Item("xmp:Nickname"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Имя ключа, которое необходимо получить. |

**Возвращает:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - Объект по ключу
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isFixedSize() {#isFixedSize--}
```
public boolean isFixedSize()
```


Возвращает true, если коллекция имеет фиксированный размер.

**Возвращает:**
boolean - логическое значение
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Возвращает true, если коллекция доступна только для чтения.

**Возвращает:**
boolean - логическое значение
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Возвращает true, если коллекция синхронизирована.

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,XmpValue>> iterator()
```


Получает объект перечислителя словаря.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>> — объект перечислителя.
### iteratorIt() {#iteratorIt--}
```
public System.Collections.IEnumerator iteratorIt()
```


Получает объект перечислителя коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator — объект IEnumerator
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator iterator_Rename_Namesake()
```




**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerNamespaceURI(String prefix, String namespaceURI) {#registerNamespaceURI-java.lang.String-java.lang.String-}
```
public void registerNamespaceURI(String prefix, String namespaceURI)
```


Регистрирует URI пространства имен.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
 xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | java.lang.String | Префикс. |
| namespaceURI | java.lang.String | URI пространства имен. |

### removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public boolean removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


Удаляет пару ключ/значение из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | Пара ключ/значение, которую нужно удалить. |

**Возвращает:**
boolean - true, если пара была найдена и удалена.
### removeItemByKey(int key) {#removeItemByKey-int-}
```
public void removeItemByKey(int key)
```


Удаляет элемент с указанным ключом.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.remove(DefaultMetadataProperties.Nickname);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | int | Ключ элемента, который будет удален. |

### removeItemByKey(String key) {#removeItemByKey-java.lang.String-}
```
public boolean removeItemByKey(String key)
```


Удаляет ключ из словаря.

--------------------

```
PdfXmpMetadata xmp = new PdfXmpMetadata();
 xmp.bindPdf("input.pdf");
 xmp.remove("xmp:Nickname");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ, который будет удален. |

**Возвращает:**
boolean - True - если ключ удален; в противном случае ложно.
### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


Сохраняет документ PDF в указанный поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destStream | java.io.OutputStream | Целевой поток. |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


Сохраняет документ PDF в указанный файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destFile | java.lang.String | Файл назначения. |

### setByDefaultMetadataProperties(int key, XmpValue value) {#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-}
```
public void setByDefaultMetadataProperties(int key, XmpValue value)
```


Устанавливает значение метаданных XMP по ключу.

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | int | Ключ значения DefaultMetadataProperties. |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | Объект. |

### set_Item(String key, XmpValue value) {#set-Item-java.lang.String-com.aspose.pdf.XmpValue-}
```
public void set_Item(String key, XmpValue value)
```


Устанавливает значение по ключу.

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 System.out.println(pxm.get_Item("xmp:Nickname"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Имя ключа для установки. |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | Значение для установки. |

### size() {#size--}
```
public int size()
```


Получает количество элементов в коллекции.

**Возвращает:**
интервал - целочисленное значение

--------------------

```
PdfXmpMetadata pxm = new PdfXmpMetadata();
 pxm.bindPdf("PdfFile.pdf");
 System.out.println("Count = " + pxm.size());
```
### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### tryGetValue(String key, Object[] value) {#tryGetValue-java.lang.String-java.lang.Object---}
```
public boolean tryGetValue(String key, Object[] value)
```


Пытается найти ключ в словаре и извлекает значение, если оно найдено.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ для поиска в словаре. |
| value | java.lang.Object[] | Полученное значение. |

**Возвращает:**
boolean - истина, если ключ найден.
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
