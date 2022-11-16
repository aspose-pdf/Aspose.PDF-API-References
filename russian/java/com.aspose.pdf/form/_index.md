---
title: Form
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий объект формы.
type: docs
weight: 139
url: /ru/java/com.aspose.pdf/form/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public final class Form implements Iterable<WidgetAnnotation>
```

Класс, представляющий объект формы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Form(IDocument document)](#Form-com.aspose.pdf.IDocument-) | Конструктор |
## Методы

| Метод | Описание |
| --- | --- |
| [add(Field field)](#add-com.aspose.pdf.Field-) | Добавляет поле в форму. |
| [add(Field field, int pageNumber)](#add-com.aspose.pdf.Field-int-) | Добавляет поле в форму. |
| [add(Field field, String partialName, int pageNumber)](#add-com.aspose.pdf.Field-java.lang.String-int-) | Добавляет новое поле в форму; Если это поле уже размещено на другой или этой форме, создается копия поля. |
| [add(WidgetAnnotation field)](#add-com.aspose.pdf.WidgetAnnotation-) | Добавляет поле в форму. |
| [addFieldAppearance(Field field, int pageNumber, Rectangle rect)](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | Добавляет дополнительный вид поля на указанную страницу документа в указанном месте. |
| [addFieldToAcroForm(Field field)](#addFieldToAcroForm-com.aspose.pdf.Field-) | Добавляет дополнительный вид поля на указанную страницу документа. |
| [assignXfa(System.Xml.XmlDocument xml)](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | Устанавливает XFA формы в указанное значение. |
| [clear()](#clear--) | Удаляет все поля из формы. |
| [contains(WidgetAnnotation field)](#contains-com.aspose.pdf.WidgetAnnotation-) | Определяет, представлено ли поле в форме. |
| [copyTo(Field[] array, int index)](#copyTo-com.aspose.pdf.Field---int-) | Копирует поля, размещенные на форме, в массив. |
| [copyTo(WidgetAnnotation[] array, int arrayIndex)](#copyTo-com.aspose.pdf.WidgetAnnotation---int-) | Копирует поля формы в массив. |
| [delete(Field field)](#delete-com.aspose.pdf.Field-) | Удалить поле из формы. |
| [delete(String fieldName)](#delete-java.lang.String-) | Удаляет поле из формы по его имени. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Удаляет все статические поля формы и размещает их значения прямо на странице. |
| [get(int index)](#get-int-) |  |
| [get(String name)](#get-java.lang.String-) | Поиск поля по имени поля. |
| [getAutoRecalculate()](#getAutoRecalculate--) | Если установлено, все поля формы будут пересчитываться при изменении любого поля. |
| [getAutoRestoreForm()](#getAutoRestoreForm--) | Если установлено, отсутствующие поля формы будут создаваться автоматически, если они присутствуют в аннотациях. |
| [getClass()](#getClass--) |  |
| [getDefaultAppearance()](#getDefaultAppearance--) | Получает внешний вид формы по умолчанию (объект, который описывает шрифт по умолчанию, размер текста и цвет для полей в форме). |
| [getDefaultResources()](#getDefaultResources--) | Получает ресурсы по умолчанию, размещенные в этой форме. |
| [getDocument()](#getDocument--) | Только для внутреннего использования |
| [getEmulateRequierdGroups()](#getEmulateRequierdGroups--) | Если это свойство истинно, то для необходимых контейнеров элементов Xfa exclGroup будут отрисовываться дополнительные красные граничные прямоугольники. Это свойство было введено из-за отсутствия аналогий для exclGroup при преобразовании Xfa представления форм в стандартное. |
| [getFields()](#getFields--) | Получает список всех полей на самом низком уровне иерархической формы. |
| [getFieldsInRect(Rectangle rect)](#getFieldsInRect-com.aspose.pdf.Rectangle-) | Возвращает поля внутри указанного прямоугольника. |
| [getIgnoreNeedsRendering()](#getIgnoreNeedsRendering--) | Если это свойство имеет значение true, значение ключа NeedsRendering будет игнорироваться при преобразовании формы XFA в стандартную форму. |
| [getRemovePermission()](#getRemovePermission--) | Если это свойство имеет значение true, то словарь "Perms" будет удален из pdf-документа после преобразования динамических документов в стандартные. |
| [getSignDependentElementsRenderingModeWhenConverted()](#getSignDependentElementsRenderingModeWhenConverted--) | Формы могут содержать информацию для подписи, т.е. могут быть подписаны или не подписаны. |
| [getSignaturesAppendOnly()](#getSignaturesAppendOnly--) | Если установлено, документ содержит подписи, которые могут быть признаны недействительными, если файл сохраняется (записывается) таким образом, что изменяется его предыдущее содержимое, в отличие от добавочного обновления. |
| [getSignaturesExist()](#getSignaturesExist--) | Если установлено, документ содержит как минимум одно поле для подписи. |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |
| [getType()](#getType--) | Получает тип формы. |
| [getXFA()](#getXFA--) | Получает данные XFA формы (если есть). |
| [get_Item(int index)](#get-Item-int-) | Получает поле формы по индексу поля. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Получает поле формы по имени поля. |
| [get_xfa()](#get-xfa--) | Только для внутреннего использования |
| [hasField(Field field)](#hasField-com.aspose.pdf.Field-) | Проверьте, есть ли в форме уже указанное поле. |
| [hasField(String fieldName)](#hasField-java.lang.String-) | Определяет, добавлено ли уже поле с указанным именем в форму. |
| [hasXfa()](#hasXfa--) | Возвращает true, если hasXfa |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Определяет, доступна ли коллекция только для чтения. |
| [isSynchronized()](#isSynchronized--) | Возвращает true, если объект потокобезопасен. |
| [iterator()](#iterator--) | Получает перечисление полей формы. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(WidgetAnnotation field)](#remove-com.aspose.pdf.WidgetAnnotation-) | Удаляет поле из формы. |
| [setAutoRecalculate(boolean value)](#setAutoRecalculate-boolean-) | Если установлено, все поля формы будут пересчитываться при изменении любого поля. |
| [setAutoRestoreForm(boolean value)](#setAutoRestoreForm-boolean-) | Если установлено, отсутствующие поля формы будут создаваться автоматически, если они присутствуют в аннотациях. |
| [setCalculatedFields(List<Field> value)](#setCalculatedFields-java.util.List-com.aspose.pdf.Field--) | Позволяет задать порядок расчета полей. |
| [setDefaultAppearance(DefaultAppearance value)](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Задает внешний вид формы по умолчанию (объект, который описывает шрифт по умолчанию, размер текста и цвет для полей формы). |
| [setEmulateRequierdGroups(boolean value)](#setEmulateRequierdGroups-boolean-) | Если это свойство истинно, то для необходимых контейнеров элементов Xfa exclGroup будут отрисовываться дополнительные красные граничные прямоугольники. Это свойство было введено из-за отсутствия аналогий для exclGroup при преобразовании Xfa представления форм в стандартное. |
| [setIgnoreNeedsRendering(boolean value)](#setIgnoreNeedsRendering-boolean-) | Если это свойство имеет значение true, значение ключа NeedsRendering будет игнорироваться при преобразовании формы XFA в стандартную форму. |
| [setRemovePermission(boolean value)](#setRemovePermission-boolean-) | Если это свойство имеет значение true, то словарь "Perms" будет удален из pdf-документа после преобразования динамических документов в стандартные. |
| [setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)](#setSignDependentElementsRenderingModeWhenConverted-int-) | Формы могут содержать информацию для подписи, т.е. могут быть подписаны или не подписаны. |
| [setSignaturesAppendOnly(boolean value)](#setSignaturesAppendOnly-boolean-) | Если установлено, документ содержит подписи, которые могут быть признаны недействительными, если файл сохраняется (записывается) таким образом, что изменяется его предыдущее содержимое, в отличие от добавочного обновления. |
| [setSignaturesExist(boolean value)](#setSignaturesExist-boolean-) | Если установлено, документ содержит как минимум одно поле для подписи. |
| [setType(int value)](#setType-int-) | Получает тип формы. |
| [size()](#size--) | Получает количество полей в этой форме. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Form(IDocument document) {#Form-com.aspose.pdf.IDocument-}
```
public Form(IDocument document)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Объект IDocument |

### add(Field field) {#add-com.aspose.pdf.Field-}
```
public void add(Field field)
```


Добавляет поле в форму.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | Поле, которое необходимо добавить. |

### add(Field field, int pageNumber) {#add-com.aspose.pdf.Field-int-}
```
public void add(Field field, int pageNumber)
```


Добавляет поле в форму.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | Поле, которое необходимо добавить. |
| pageNumber | int | Индекс страницы, где будет размещено добавленное поле. |

### add(Field field, String partialName, int pageNumber) {#add-com.aspose.pdf.Field-java.lang.String-int-}
```
public Field add(Field field, String partialName, int pageNumber)
```


Добавляет новое поле в форму; Если это поле уже размещено на другой или этой форме, создается копия поля.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | Имя поля. |
| partialName | java.lang.String | Название поля в форме. |
| pageNumber | int | Номер страницы, на которой будет добавлено поле. |

**Возвращает:**
[Field](../../com.aspose.pdf/field) - Добавлено поле возвращено. Если копия поля была создана, она будет возвращена.
### add(WidgetAnnotation field) {#add-com.aspose.pdf.WidgetAnnotation-}
```
public boolean add(WidgetAnnotation field)
```


Добавляет поле в форму.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) | Поле, которое необходимо добавить. |

**Возвращает:**
boolean - логическое значение
### addFieldAppearance(Field field, int pageNumber, Rectangle rect) {#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-}
```
public void addFieldAppearance(Field field, int pageNumber, Rectangle rect)
```


Добавляет дополнительный вид поля на указанную страницу документа в указанном месте.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | Поле, внешний вид которого необходимо добавить на форму. |
| pageNumber | int | Номер страницы, на которой должно быть размещено поле. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольник, в котором будет размещено поле. |

### addFieldToAcroForm(Field field) {#addFieldToAcroForm-com.aspose.pdf.Field-}
```
public void addFieldToAcroForm(Field field)
```


Добавляет дополнительный вид поля на указанную страницу документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | Полевой объект |

### assignXfa(System.Xml.XmlDocument xml) {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
```
public void assignXfa(System.Xml.XmlDocument xml)
```


Устанавливает XFA формы в указанное значение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xml | com.aspose.ms.System.Xml.XmlDocument | XML-документ, содержащий новые данные XFA. |

### clear() {#clear--}
```
public void clear()
```


Удаляет все поля из формы. Не поддерживается.

### contains(WidgetAnnotation field) {#contains-com.aspose.pdf.WidgetAnnotation-}
```
public boolean contains(WidgetAnnotation field)
```


Определяет, представлено ли поле в форме.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) | Поле для поиска. |

**Возвращает:**
boolean - логическое значение
### copyTo(Field[] array, int index) {#copyTo-com.aspose.pdf.Field---int-}
```
public void copyTo(Field[] array, int index)
```


Копирует поля, размещенные на форме, в массив.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [Field\[\]](../../com.aspose.pdf/field) | Массив, в котором должны быть размещены поля. |
| index | int | Начальный индекс. |

### copyTo(WidgetAnnotation[] array, int arrayIndex) {#copyTo-com.aspose.pdf.WidgetAnnotation---int-}
```
public void copyTo(WidgetAnnotation[] array, int arrayIndex)
```


Копирует поля формы в массив.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [WidgetAnnotation\[\]](../../com.aspose.pdf/widgetannotation) | Массив для копирования. |
| arrayIndex | int | Индекс элемента массива, с которого начинается копирование. |

### delete(Field field) {#delete-com.aspose.pdf.Field-}
```
public void delete(Field field)
```


Удалить поле из формы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | Поле, которое необходимо удалить. |

### delete(String fieldName) {#delete-java.lang.String-}
```
public void delete(String fieldName)
```


Удаляет поле из формы по его имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя файла, который необходимо удалить. |

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
### flatten() {#flatten--}
```
public void flatten()
```


Удаляет все статические поля формы и размещает их значения прямо на странице.

### get(int index) {#get-int-}
```
public WidgetAnnotation get(int index)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation)
### get(String name) {#get-java.lang.String-}
```
public WidgetAnnotation get(String name)
```


Поиск поля по имени поля. Возвращает null, если поле не найдено.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя поля. |

**Возвращает:**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - Полевой объект.
### getAutoRecalculate() {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```


Если установлено, все поля формы будут пересчитываться при изменении любого поля. Значение по умолчанию — истина. Установите значение false, чтобы повысить производительность при заполнении формы с большим количеством вычисляемых полей.

**Возвращает:**
boolean - логическое значение
### getAutoRestoreForm() {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```


Если установлено, отсутствующие поля формы будут создаваться автоматически, если они присутствуют в аннотациях.

**Возвращает:**
boolean - логическое значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDefaultAppearance() {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```


Получает внешний вид формы по умолчанию (объект, который описывает шрифт по умолчанию, размер текста и цвет для полей в форме).

**Возвращает:**
[DefaultAppearance](../../com.aspose.pdf/defaultappearance) - Объект DefaultAppearance
### getDefaultResources() {#getDefaultResources--}
```
public Resources getDefaultResources()
```


Получает ресурсы по умолчанию, размещенные в этой форме.

**Возвращает:**
[Resources](../../com.aspose.pdf/resources) - Стоимость ресурсов
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Только для внутреннего использования

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - Объект IDocument
### getEmulateRequierdGroups() {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```


Если это свойство истинно, то для необходимых контейнеров элементов Xfa exclGroup будут отрисовываться дополнительные красные граничные прямоугольники. Это свойство было введено из-за отсутствия аналогий для exclGroup при преобразовании Xfa представления форм в стандартное. По умолчанию это ложь.

**Возвращает:**
boolean - логическое значение
### getFields() {#getFields--}
```
public Field[] getFields()
```


Получает список всех полей на самом низком уровне иерархической формы.

**Возвращает:**
com.aspose.pdf.Поле[] - Массив с найденными полями.
### getFieldsInRect(Rectangle rect) {#getFieldsInRect-com.aspose.pdf.Rectangle-}
```
public Field[] getFieldsInRect(Rectangle rect)
```


Возвращает поля внутри указанного прямоугольника.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольник, в котором должны быть найдены поля. |

**Возвращает:**
com.aspose.pdf.Поле[] - Массив с найденными полями.
### getIgnoreNeedsRendering() {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```


Если это свойство имеет значение true, значение ключа NeedsRendering будет игнорироваться при преобразовании формы XFA в стандартную форму. По умолчанию это ложь.

**Возвращает:**
boolean - логическое значение
### getRemovePermission() {#getRemovePermission--}
```
public boolean getRemovePermission()
```


Если это свойство имеет значение true, то словарь "Perms" будет удален из pdf-документа после преобразования динамических документов в стандартные. Словарь "Пермь" может содержать правила, препятствующие отображению выделения обязательных полей в программе Adobe Acrobat reader. По умолчанию это ложь.

**Возвращает:**
boolean - логическое значение
### getSignDependentElementsRenderingModeWhenConverted() {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```


Формы могут содержать информацию для подписи, т.е. могут быть подписаны или не подписаны. А вид формы иногда должен зависеть от того, подписана форма или нет. Это свойство сообщает преобразователю формы (например, во время преобразования формы XFA в стандартную форму), должна ли результирующая форма отображаться как подписанная или как беззнаковая.

**Возвращает:**
int — элемент SignDependentElementsRenderingModes
### getSignaturesAppendOnly() {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```


Если установлено, документ содержит подписи, которые могут быть признаны недействительными, если файл сохраняется (записывается) таким образом, что изменяется его предыдущее содержимое, в отличие от добавочного обновления.

**Возвращает:**
boolean - логическое значение
### getSignaturesExist() {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```


Если установлено, документ содержит как минимум одно поле для подписи.

**Возвращает:**
boolean - логическое значение
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Возвращает объект синхронизации.

**Возвращает:**
java.lang.Object — Объект для синхронизации
### getType() {#getType--}
```
public int getType()
```


Получает тип формы. Возможные значения: Стандартный, Статический, Динамический.

**Возвращает:**
int - значение типа формы
### getXFA() {#getXFA--}
```
public XFA getXFA()
```


Получает данные XFA формы (если есть).

**Возвращает:**
[XFA](../../com.aspose.pdf/xfa) - Значение РФА
### get_Item(int index) {#get-Item-int-}
```
public WidgetAnnotation get_Item(int index)
```


Получает поле формы по индексу поля.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс поля. |

**Возвращает:**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - Восстановленное поле.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public WidgetAnnotation get_Item(String name)
```


Получает поле формы по имени поля. Выдает исключение, если поле не найдено.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя поля. |

**Возвращает:**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - Восстановленное поле.
### get_xfa() {#get-xfa--}
```
public XFA get_xfa()
```


Только для внутреннего использования

**Возвращает:**
[XFA](../../com.aspose.pdf/xfa) - XFA-объект
### hasField(Field field) {#hasField-com.aspose.pdf.Field-}
```
public final boolean hasField(Field field)
```


Проверьте, есть ли в форме уже указанное поле.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | Поле для проверки. |

**Возвращает:**
boolean - true, если указанное имя поля добавлено в форму; в противном случае ложь.
### hasField(String fieldName) {#hasField-java.lang.String-}
```
public final boolean hasField(String fieldName)
```


Определяет, добавлено ли уже поле с указанным именем в форму.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | PartialName поля. |

**Возвращает:**
boolean - true, если указанное имя поля добавлено в форму; в противном случае ложь.
### hasXfa() {#hasXfa--}
```
public boolean hasXfa()
```


Возвращает true, если hasXfa

**Возвращает:**
boolean - логическое значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Определяет, доступна ли коллекция только для чтения. Всегда возвращает ложь.

**Возвращает:**
boolean - логическое значение
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Возвращает true, если объект потокобезопасен.

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public Iterator<WidgetAnnotation> iterator()
```


Получает перечисление полей формы.

**Возвращает:**
java.util.Iterator<com.aspose.pdf.WidgetAnnotation> — перечислитель полей.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(WidgetAnnotation field) {#remove-com.aspose.pdf.WidgetAnnotation-}
```
public boolean remove(WidgetAnnotation field)
```


Удаляет поле из формы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| field | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) | Поле для удаления. |

**Возвращает:**
boolean — Истинно, если поле было удалено. False, если поле не было найдено в форме.
### setAutoRecalculate(boolean value) {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```


Если установлено, все поля формы будут пересчитываться при изменении любого поля. Значение по умолчанию — истина. Установите значение false, чтобы повысить производительность при заполнении формы с большим количеством вычисляемых полей.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setAutoRestoreForm(boolean value) {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```


Если установлено, отсутствующие поля формы будут создаваться автоматически, если они присутствуют в аннотациях.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setCalculatedFields(List<Field> value) {#setCalculatedFields-java.util.List-com.aspose.pdf.Field--}
```
public void setCalculatedFields(List<Field> value)
```


Позволяет задать порядок расчета полей.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.List<com.aspose.pdf.Field> | объект java.util.List. |

### setDefaultAppearance(DefaultAppearance value) {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
```
public void setDefaultAppearance(DefaultAppearance value)
```


Задает внешний вид формы по умолчанию (объект, который описывает шрифт по умолчанию, размер текста и цвет для полей формы).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DefaultAppearance](../../com.aspose.pdf/defaultappearance) | Объект DefaultAppearance |

### setEmulateRequierdGroups(boolean value) {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```


Если это свойство истинно, то для необходимых контейнеров элементов Xfa exclGroup будут отрисовываться дополнительные красные граничные прямоугольники. Это свойство было введено из-за отсутствия аналогий для exclGroup при преобразовании Xfa представления форм в стандартное. По умолчанию это ложь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setIgnoreNeedsRendering(boolean value) {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```


Если это свойство имеет значение true, значение ключа NeedsRendering будет игнорироваться при преобразовании формы XFA в стандартную форму. По умолчанию это ложь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setRemovePermission(boolean value) {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```


Если это свойство имеет значение true, то словарь "Perms" будет удален из pdf-документа после преобразования динамических документов в стандартные. Словарь "Пермь" может содержать правила, препятствующие отображению выделения обязательных полей в программе Adobe Acrobat reader. По умолчанию это ложь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted) {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```


Формы могут содержать информацию для подписи, т.е. могут быть подписаны или не подписаны. А вид формы иногда должен зависеть от того, подписана форма или нет. Это свойство сообщает преобразователю формы (например, во время преобразования формы XFA в стандартную форму), должна ли результирующая форма отображаться как подписанная или как беззнаковая.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted | int | Элемент SignDependentElementsRenderingModes |

### setSignaturesAppendOnly(boolean value) {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```


Если установлено, документ содержит подписи, которые могут быть признаны недействительными, если файл сохраняется (записывается) таким образом, что изменяется его предыдущее содержимое, в отличие от добавочного обновления.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSignaturesExist(boolean value) {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```


Если установлено, документ содержит как минимум одно поле для подписи.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Получает тип формы. Возможные значения: Стандартный, Статический, Динамический.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение типа формы |

### size() {#size--}
```
public final int size()
```


Получает количество полей в этой форме.

**Возвращает:**
интервал - целочисленное значение
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
