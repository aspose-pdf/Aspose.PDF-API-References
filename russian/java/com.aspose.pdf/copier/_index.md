---
title: Copier
second_title: Aspose.PDF для справки по Java API
description: Класс для копирующего объекта
type: docs
weight: 77
url: /ru/java/com.aspose.pdf/copier/
---
**Наследование:**
java.lang.Object
```
public class Copier
```

Класс для копирующего объекта
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Copier(ITrailerable trailerable)](#Copier-com.aspose.pdf.engine.data.ITrailerable-) | Конструктор |
## Методы

| Метод | Описание |
| --- | --- |
| [duplicate(IPdfPrimitive src)](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-) | Дублирует IPdfPrimitive |
| [duplicate(IPdfPrimitive src, boolean IsResourceObject)](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-) | Создает копию объекта со всеми зависимыми объектами. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowReusePageContent()](#getAllowReusePageContent--) | получить Разрешить повторное использование содержимого страницы |
| [getClass()](#getClass--) |  |
| [getIgnoreCorruptedObjects()](#getIgnoreCorruptedObjects--) | получить Игнорировать поврежденные объекты |
| [getRestrictedKeys()](#getRestrictedKeys--) | получить закрытые ключи |
| [getReuseStreams()](#getReuseStreams--) | получить повторное использование потоков |
| [getUseStubs()](#getUseStubs--) | использовать заглушки |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowReusePageContent(boolean value)](#setAllowReusePageContent-boolean-) | установить Разрешить повторное использование содержимого страницы |
| [setIgnoreCorruptedObjects(boolean value)](#setIgnoreCorruptedObjects-boolean-) | Установить игнорирование поврежденных объектов |
| [setRestrictedKeys(String[] value)](#setRestrictedKeys-java.lang.String---) | установить ограниченные ключи |
| [setReuseStreams(boolean value)](#setReuseStreams-boolean-) | установить повторное использование потоков |
| [setUseStubs(boolean value)](#setUseStubs-boolean-) | установить использование заглушек |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Copier(ITrailerable trailerable) {#Copier-com.aspose.pdf.engine.data.ITrailerable-}
```
public Copier(ITrailerable trailerable)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) | ITrailerable объект |

### duplicate(IPdfPrimitive src) {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public IPdfPrimitive duplicate(IPdfPrimitive src)
```


Дублирует IPdfPrimitive

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | Объект IPdfPrimitive |

**Возвращает:**
[IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) - Объект IPdfPrimitive
### duplicate(IPdfPrimitive src, boolean IsResourceObject) {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-}
```
public IPdfPrimitive duplicate(IPdfPrimitive src, boolean IsResourceObject)
```


Создает копию объекта со всеми зависимыми объектами. Объект может быть частью другого документа (например, копирование страниц между документами и т. д.).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | Объект IPdfPrimitive |
| IsResourceObject | boolean | логическое значение |

**Возвращает:**
[IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) - Объект IPdfPrimitive
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
### getAllowReusePageContent() {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```


получить Разрешить повторное использование содержимого страницы

**Возвращает:**
boolean - логическое значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getIgnoreCorruptedObjects() {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```


получить Игнорировать поврежденные объекты

**Возвращает:**
boolean - логическое значение
### getRestrictedKeys() {#getRestrictedKeys--}
```
public String[] getRestrictedKeys()
```


получить закрытые ключи

**Возвращает:**
java.lang.String[] - Нить[] множество
### getReuseStreams() {#getReuseStreams--}
```
public boolean getReuseStreams()
```


получить повторное использование потоков

**Возвращает:**
boolean - логическое значение
### getUseStubs() {#getUseStubs--}
```
public boolean getUseStubs()
```


использовать заглушки

**Возвращает:**
boolean - логическое значение
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




### setAllowReusePageContent(boolean value) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```


установить Разрешить повторное использование содержимого страницы

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setIgnoreCorruptedObjects(boolean value) {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```


Установить игнорирование поврежденных объектов

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setRestrictedKeys(String[] value) {#setRestrictedKeys-java.lang.String---}
```
public void setRestrictedKeys(String[] value)
```


установить ограниченные ключи

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Нить[] | String[] множество |

### setReuseStreams(boolean value) {#setReuseStreams-boolean-}
```
public void setReuseStreams(boolean value)
```


установить повторное использование потоков

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setUseStubs(boolean value) {#setUseStubs-boolean-}
```
public void setUseStubs(boolean value)
```


установить использование заглушек

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

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
