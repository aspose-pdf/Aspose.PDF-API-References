---
title: OperatorCollection
second_title: Aspose.PDF для справки по Java API
description: Класс представляет собой набор операторов
type: docs
weight: 233
url: /ru/java/com.aspose.pdf/operatorcollection/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.BaseOperatorCollection](../../com.aspose.pdf/baseoperatorcollection)
```
public class OperatorCollection extends BaseOperatorCollection
```

Класс представляет собой набор операторов
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OperatorCollection(IPdfPrimitive contents)](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | Только для внутреннего использования! |
## Методы

| Метод | Описание |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Принимает объект посетителя IOperatorSelector для обработки операторов. |
| [add(Operator op)](#add-com.aspose.pdf.Operator-) | Добавляет новый оператор в коллекцию. |
| [add(Operator[] ops)](#add-com.aspose.pdf.Operator---) | Добавьте операторы в конце операторов содержимого. |
| [add(Iterable<Operator> ops)](#add-java.lang.Iterable-com.aspose.pdf.Operator--) | Добавляет в коллекцию все операторы из другой коллекции. |
| [cancelUpdate()](#cancelUpdate--) | Отменяет последнее обновление. |
| [clear()](#clear--) | Удаляет всех операторов из списка. |
| [contains(Operator op)](#contains-com.aspose.pdf.Operator-) | Возвращает true, если коллекция содержит заданный оператор. |
| [delete(Operator[] ops)](#delete-com.aspose.pdf.Operator---) | Удаляет операторы из коллекции. |
| [delete(int index)](#delete-int-) | Удаляет оператора из коллекции. |
| [delete(Iterable<Operator> list)](#delete-java.lang.Iterable-com.aspose.pdf.Operator--) | Удаляет операторы из коллекции. |
| [deleteUnrestricted(int index)](#deleteUnrestricted-int-) | внутренняя неограниченная версия Delete(index) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getUnrestricted(int index)](#getUnrestricted-int-) | Внутренняя неограниченная версия индексатора |
| [get_Item(int index)](#get-Item-int-) | Получает оператор по его индексу. |
| [hashCode()](#hashCode--) |  |
| [insert(int index, Operator op)](#insert-int-com.aspose.pdf.Operator-) | Вставляет оператор в коллекцию. |
| [insert(int at, Operator[] ops)](#insert-int-com.aspose.pdf.Operator---) | Вставьте операторы в заданную позицию. |
| [insert(int at, Iterable<Operator> ops)](#insert-int-java.lang.Iterable-com.aspose.pdf.Operator--) | Вставьте операторы в заданную позицию. |
| [isBracketed()](#isBracketed--) | Получает заключенный в квадратные скобки статус последовательности операторов, т. е. эти операторы находятся внутри блоков q - Q |
| [isCommandsParsed()](#isCommandsParsed--) | Получает анализируемые команды |
| [isEmpty()](#isEmpty--) | Возвращает TRUE, если коллекция пуста. |
| [isFastTextExtractionMode()](#isFastTextExtractionMode--) | Указывает, ограничена ли коллекция быстрым извлечением текста |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступна ли коллекция только для чтения. |
| [iterator()](#iterator--) | Возвращает перечислитель для коллекции |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Operator op)](#remove-com.aspose.pdf.Operator-) | Удалить оператора из коллекции. |
| [replace(Operator[] operators)](#replace-com.aspose.pdf.Operator---) | Замените операторы в коллекции другими операторами. |
| [replace(Iterable<Operator> operators)](#replace-java.lang.Iterable-com.aspose.pdf.Operator--) | Замените операторы в коллекции другими операторами. |
| [resumeUpdate()](#resumeUpdate--) | Возобновление обновления документа. |
| [set_Item(int index, Operator value)](#set-Item-int-com.aspose.pdf.Operator-) | Устанавливает оператор по его индексу. |
| [size()](#size--) | Получает количество операторов в коллекции. |
| [suppressUpdate()](#suppressUpdate--) | Подавляет обновление данных содержимого. Поток содержимого не обновляется до тех пор, пока не будет вызвано ResumeUpdate. |
| [toList()](#toList--) | Возвращает список операторов. |
| [toString()](#toString--) | Возвращает текстовое представление оператора. |
| [updateData()](#updateData--) | Обновить поток объектов. |
| [updateNormalizedData()](#updateNormalizedData--) | Обновление потока объектов с исправлением отсутствующих операторов GSave/GRestore. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OperatorCollection(IPdfPrimitive contents) {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public OperatorCollection(IPdfPrimitive contents)
```


Только для внутреннего использования!

Конструктор OperatorCollection. Создает операторы из примитива, содержащего список операторов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| contents | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | Объект IPdfPrimitive |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Принимает объект посетителя IOperatorSelector для обработки операторов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Объект посетителя |

### add(Operator op) {#add-com.aspose.pdf.Operator-}
```
public void add(Operator op)
```


Добавляет новый оператор в коллекцию.

--------------------

Пример демонстрирует, как добавить операторы в конец page.contents.

Документ doc = новый документ ("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q());

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Оператор, который необходимо добавить |

### add(Operator[] ops) {#add-com.aspose.pdf.Operator---}
```
public void add(Operator[] ops)
```


Добавьте операторы в конце операторов содержимого.

--------------------

Пример демонстрирует, как добавить оператор в конец содержимого страницы.

Документ doc = новый документ ("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(новый оператор[ ]\ { новый com.aspose.pdf.operators.q(), новый com.aspose.pdf.operators.Q()\});

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ops | [Operator\[\]](../../com.aspose.pdf/operator) | Массив операторов для добавления. Каждый оператор может иметь любой индекс (по умолчанию -1), потому что они идут в конец содержимого операторов, т.е. индексы назначаются автоматически. |

### add(Iterable<Operator> ops) {#add-java.lang.Iterable-com.aspose.pdf.Operator--}
```
public void add(Iterable<Operator> ops)
```


Добавляет в коллекцию все операторы из другой коллекции.

--------------------

```
Example demonstrates how to add operator collection to the page contents.

 Document doc = new Document("input.pdf");
 OperatorCollection oc = doc.getPages(1).getContents();
 ArrayList opList = new ArrayList();
 opList.add(new com.aspose.pdf.operators.q());
 opList.add(new com.aspose.pdf.operators.Q());
 oc.add(opList);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ops | java.lang.Iterable<com.aspose.pdf.Operator> | коллекция, содержащая операторы, которые будут добавлены. |

### cancelUpdate() {#cancelUpdate--}
```
public void cancelUpdate()
```


Отменяет последнее обновление. Этот метод может быть вызван, когда изменение не должно вызывать обновление содержимого.

### clear() {#clear--}
```
public void clear()
```


Удаляет всех операторов из списка.

--------------------

Пример демонстрирует, как очистить содержимое страницы.

Документ doc = новый документ ("input.pdf"); doc.getPages().get(1).clear();

### contains(Operator op) {#contains-com.aspose.pdf.Operator-}
```
public boolean contains(Operator op)
```


Возвращает true, если коллекция содержит заданный оператор.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Экземпляр оператора |

**Возвращает:**
boolean - логическое значение True - если оператор найден; в противном случае ложно.
### delete(Operator[] ops) {#delete-com.aspose.pdf.Operator---}
```
public void delete(Operator[] ops)
```


Удаляет операторы из коллекции.

--------------------

Пример демонстрирует, как удалить оператор из содержимого страницы.

Документ doc = новый документ ("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete (новый оператор[ ]\{ ок[ 1]\});

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| ops | [Operator\[\]](../../com.aspose.pdf/operator) | Массив операторов для удаления |

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Удаляет оператора из коллекции.

--------------------

Пример демонстрирует, как удалить оператор по его индексу.

Документ doc = новый документ ("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); ок.удалить(3);

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс оператора, который необходимо удалить. Нумерация операторов начинается с 1. |

### delete(Iterable<Operator> list) {#delete-java.lang.Iterable-com.aspose.pdf.Operator--}
```
public void delete(Iterable<Operator> list)
```


Удаляет операторы из коллекции.

--------------------

Пример демонстрирует, как удалить оператор из содержимого страницы.

Документ doc = новый документ ("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); ArrayList<Operator> opList = новый ArrayList<Operator>(); opList.add(oc[1]); oc.delete (opList);

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| list | java.lang.Iterable<com.aspose.pdf.Operator> | Список операторов для удаления |

### deleteUnrestricted(int index) {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```


внутренняя неограниченная версия Delete(index)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | целое значение |

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
### getUnrestricted(int index) {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```


Внутренняя неограниченная версия индексатора

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | целое значение |

**Возвращает:**
[Operator](../../com.aspose.pdf/operator) - Объект оператора
### get_Item(int index) {#get-Item-int-}
```
public Operator get_Item(int index)
```


Получает оператор по его индексу.

--------------------

Пример демонстрирует, как получить оператор содержимого страницы по индексу.

```
Document doc = new Document("input.pdf");
 OperatorCollection oc = doc.getPages().get(1).getContents();
 Operator first = oc.get_Item(1);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс оператора. Нумерация начинается с 1. |

**Возвращает:**
[Operator](../../com.aspose.pdf/operator) - Оператор из запрошенного индекса
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### insert(int index, Operator op) {#insert-int-com.aspose.pdf.Operator-}
```
public void insert(int index, Operator op)
```


Вставляет оператор в коллекцию.

--------------------

Пример демонстрирует, как вставить оператор в содержимое страницы.

Документ doc = новый документ ("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, новый com.aspose.pdf.operators.q()); oc.add(новый com.aspose.pdf.operators.Q());

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс, в который необходимо добавить новый оператор |
| op | [Operator](../../com.aspose.pdf/operator) | Оператор, который будет вставлен |

### insert(int at, Operator[] ops) {#insert-int-com.aspose.pdf.Operator---}
```
public void insert(int at, Operator[] ops)
```


Вставьте операторы в заданную позицию.

--------------------

Пример демонстрирует, как вставить оператор в содержимое страницы.

Документ doc = новый документ ("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, новый оператор[ ]\ { новый com.aspose.pdf.operators.q(), новый com.aspose.pdf.operators.Q()\});

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| at | int | Индекс, с которого начинается вставка операторов. |
| ops | [Operator\[\]](../../com.aspose.pdf/operator) | Массив операторов для вставки. Каждый оператор может иметь любой индекс (по умолчанию -1), потому что их индексы настраиваются автоматически, начиная с . |

### insert(int at, Iterable<Operator> ops) {#insert-int-java.lang.Iterable-com.aspose.pdf.Operator--}
```
public void insert(int at, Iterable<Operator> ops)
```


Вставьте операторы в заданную позицию.

--------------------

Пример демонстрирует, как вставлять операторы в содержимое страницы.

Документ doc = новый документ ("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); ArrayList<Operator> opList = новый список<Operator>(); opList.add(новый com.aspose.pdf.operators.q()); opList.add(новый com.aspose.pdf.operators.Q()); oc.insert(1, opList);

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| at | int | Индекс, с которого начинается вставка операторов. |
| ops | java.lang.Iterable<com.aspose.pdf.Operator> | Массив операторов для вставки. |

### isBracketed() {#isBracketed--}
```
public boolean isBracketed()
```


Получает заключенный в квадратные скобки статус последовательности операторов, т. е. эти операторы находятся внутри блоков q - Q

**Возвращает:**
boolean - логическое значение
### isCommandsParsed() {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```


Получает анализируемые команды

**Возвращает:**
boolean - логическое значение
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Возвращает TRUE, если коллекция пуста.

**Возвращает:**
boolean - логическое значение
### isFastTextExtractionMode() {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```


Указывает, ограничена ли коллекция быстрым извлечением текста

**Возвращает:**
boolean - логическое значение
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Получает значение, указывающее, доступна ли коллекция только для чтения.

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<Operator> iterator()
```


Возвращает перечислитель для коллекции

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.Operator> — перечислитель коллекции
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Operator op) {#remove-com.aspose.pdf.Operator-}
```
public boolean remove(Operator op)
```


Удалить оператора из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Оператор, которого нужно удалить. |

**Возвращает:**
boolean - Истинно, если оператор был найден и удален. False, если оператор не принадлежит коллекции.
### replace(Operator[] operators) {#replace-com.aspose.pdf.Operator---}
```
public void replace(Operator[] operators)
```


Замените операторы в коллекции другими операторами.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| operators | [Оператор\[\]](../../com.aspose.pdf/operator) | Operator[ ] массив, который заменит операторы, содержащиеся в коллекции. Каждый оператор из списка должен иметь правильный индекс в диапазоне[1..N], где N — количество операторов в коллекции |

### replace(Iterable<Operator> operators) {#replace-java.lang.Iterable-com.aspose.pdf.Operator--}
```
public void replace(Iterable<Operator> operators)
```


Замените операторы в коллекции другими операторами.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| operators | java.lang.Iterable<com.aspose.pdf.Operator> |  Список операторов, которые заменят операторы, содержащиеся в настоящее время в коллекции. Каждый оператор из списка должен иметь правильный индекс в диапазоне[1..N], где N — количество операторов в коллекции |

### resumeUpdate() {#resumeUpdate--}
```
public void resumeUpdate()
```


Возобновление обновления документа. Обновляет поток содержимого, если есть какие-либо ожидающие изменения.

### set_Item(int index, Operator value) {#set-Item-int-com.aspose.pdf.Operator-}
```
public void set_Item(int index, Operator value)
```


Устанавливает оператор по его индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | целое значение |
| value | [Operator](../../com.aspose.pdf/operator) | Объект оператора |

### size() {#size--}
```
public int size()
```


Получает количество операторов в коллекции.

**Возвращает:**
интервал - целочисленное значение
### suppressUpdate() {#suppressUpdate--}
```
public void suppressUpdate()
```


Подавляет обновление данных содержимого. Поток содержимого не обновляется до тех пор, пока не будет вызвано ResumeUpdate.

### toList() {#toList--}
```
public System.Collections.Generic.List<Operator> toList()
```


Возвращает список операторов.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> - список операторов.
### toString() {#toString--}
```
public String toString()
```


Возвращает текстовое представление оператора.

**Возвращает:**
java.lang.String — Текстовое представление оператора.
### updateData() {#updateData--}
```
public void updateData()
```


Обновить поток объектов.

### updateNormalizedData() {#updateNormalizedData--}
```
public void updateNormalizedData()
```


Обновление потока объектов с исправлением отсутствующих операторов GSave/GRestore.

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
