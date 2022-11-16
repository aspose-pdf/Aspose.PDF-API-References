---
title: FileFontSource
second_title: Aspose.PDF для справки по Java API
description: Представляет один исходный файл шрифта.
type: docs
weight: 112
url: /ru/java/com.aspose.pdf/filefontsource/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.FontSource](../../com.aspose.pdf/fontsource)
```
public final class FileFontSource extends FontSource
```

Представляет один исходный файл шрифта.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FileFontSource(String filePath)](#FileFontSource-java.lang.String-) | Инициализирует новый экземпляр класса FileFontSource. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверьте, равны ли исходные объекты файла шрифта. |
| [getClass()](#getClass--) |  |
| [getFilePath()](#getFilePath--) | Путь к файлу шрифта. |
| [hashCode()](#hashCode--) | Возвращает значение хэш-кода для объекта. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFilePath(String value)](#setFilePath-java.lang.String-) | Путь к файлу шрифта. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileFontSource(String filePath) {#FileFontSource-java.lang.String-}
```
public FileFontSource(String filePath)
```


Инициализирует новый экземпляр класса FileFontSource.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу шрифта. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверьте, равны ли исходные объекты файла шрифта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Исходный объект файла шрифта, который будет сравниваться. |

**Возвращает:**
boolean — True, если оба объекта являются источниками файлов шрифтов, предназначенными для одного и того же файла.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Путь к файлу шрифта.

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
 *   это*not* требуется, чтобы, если два объекта не равны в соответствии с java.lang.Object\#equals(java.lang.Object).equals(java.lang.Object), то вызов метода hashCode для каждого из двух объектов должен давать различные целочисленные результаты. Однако программист должен знать, что создание различных целочисленных результатов для неравных объектов может повысить производительность хеш-таблиц.

Насколько это целесообразно, метод hashCode, определенный классом Object, действительно возвращает разные целые числа для разных объектов. (Обычно это реализуется путем преобразования внутреннего адреса объекта в целое число, но этот метод реализации не требуется языком программирования Java TM.)

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




### setFilePath(String value) {#setFilePath-java.lang.String-}
```
public void setFilePath(String value)
```


Путь к файлу шрифта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

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
