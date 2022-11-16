---
title: FolderFontSource
second_title: Aspose.PDF для справки по Java API
description: Представляет папку, содержащую файлы шрифтов.
type: docs
weight: 129
url: /ru/java/com.aspose.pdf/folderfontsource/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.FontSource](../../com.aspose.pdf/fontsource)
```
public final class FolderFontSource extends FontSource
```

Представляет папку, содержащую файлы шрифтов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FolderFontSource(String folderPath)](#FolderFontSource-java.lang.String-) | Инициализирует новый экземпляр класса FolderFontSource. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверьте, равны ли исходные объекты шрифта папки. |
| [getClass()](#getClass--) |  |
| [getFolderPath()](#getFolderPath--) | Путь к папке, содержащей файлы шрифтов. |
| [hashCode()](#hashCode--) | Возвращает значение хэш-кода для объекта. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFolderPath(String value)](#setFolderPath-java.lang.String-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FolderFontSource(String folderPath) {#FolderFontSource-java.lang.String-}
```
public FolderFontSource(String folderPath)
```


Инициализирует новый экземпляр класса FolderFontSource.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderPath | java.lang.String | Путь к папке. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверьте, равны ли исходные объекты шрифта папки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Исходный объект шрифта папки, который будет сравниваться. |

**Возвращает:**
boolean — True, если оба объекта являются источниками шрифтов в папке, ориентированными на одну и ту же папку.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


Путь к папке, содержащей файлы шрифтов.

**Возвращает:**
java.lang.String — строковое значение
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает значение хэш-кода для объекта. Этот метод поддерживается для хеш-таблиц, таких как предоставляемые java.util.HashMap.

Общий контракт hashCode:

 *  Всякий раз, когда он вызывается для одного и того же объекта более одного раза во время выполнения приложения Java, метод hashCode должен постоянно возвращать одно и то же целое число, при условии, что никакая информация, используемая в сравнениях на равенство для объекта, не изменяется. Это целое число не обязательно должно оставаться постоянным от одного выполнения приложения к другому выполнению того же приложения.
 *  Если два объекта равны в соответствии с методом equals(Object), то вызов метода hashCode для каждого из двух объектов должен давать одинаковый целочисленный результат.
 *   это*not*требуется, чтобы, если два объекта не равны в соответствии с java.lang.Object\#equals(java.lang.Object).equals(java.lang.Object), то вызов метода hashCode для каждого из двух объектов должен давать различные целочисленные результаты. Однако программист должен знать, что создание различных целочисленных результатов для неравных объектов может повысить производительность хеш-таблиц.

Насколько это целесообразно, метод hashCode, определенный классом Object, действительно возвращает разные целые числа для разных объектов. (Обычно это реализуется путем преобразования внутреннего адреса объекта в целое число, но этот метод реализации не требуется для языка программирования JavaTM.)

**Возвращает:**
int - значение хеш-кода для этого объекта.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public void setFolderPath(String value)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

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
