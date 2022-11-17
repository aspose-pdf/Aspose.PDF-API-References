---
title: LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF для справки по Java API
description: Результат пользовательской загрузки ресурса
type: docs
weight: 12
url: /ru/java/com.aspose.pdf/loadoptions.resourceloadingresult/
---
**Наследование:**
java.lang.Object
```
public static class LoadOptions.ResourceLoadingResult
```

Результат пользовательской загрузки ресурса
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ResourceLoadingResult(byte[] data)](#ResourceLoadingResult-byte---) | Создает экземпляр загрузки результата |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Бинарные данные, загруженные с помощью пользовательского загрузчика - должны быть установлены после загрузки |
| [getEncodingIfKnown()](#getEncodingIfKnown--) | Иногда кодировка ресурса известна после или во время загрузки. |
| [getExceptionOfLoadingIfAny()](#getExceptionOfLoadingIfAny--) | Иногда по каким-либо причинам невозможно загрузить запрошенный ресурс. |
| [getMIMETypeIfKnown()](#getMIMETypeIfKnown--) | Иногда знание MIME-типа загружаемого ресурса полезно для конвертера. Вы можете указать MIME-тип (если он был известен после загрузки) в этом параметре. |
| [hashCode()](#hashCode--) |  |
| [isLoadingCancelled()](#isLoadingCancelled--) | Иногда по каким-то причинам не должна происходить загрузка пользовательского кода. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncodingIfKnown(Charset encodingIfKnown)](#setEncodingIfKnown-java.nio.charset.Charset-) | Иногда кодировка ресурса известна после или во время загрузки. |
| [setExceptionOfLoadingIfAny(System.Exception exceptionOfLoadingIfAny)](#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-) | Иногда по каким-либо причинам невозможно загрузить запрошенный ресурс. |
| [setLoadingCancelled(boolean loadingCancelled)](#setLoadingCancelled-boolean-) | Иногда по каким-то причинам не должна происходить загрузка пользовательского кода. |
| [setMIMETypeIfKnown(String MIMETypeIfKnown)](#setMIMETypeIfKnown-java.lang.String-) | Иногда знание MIME-типа загружаемого ресурса полезно для конвертера. Вы можете указать MIME-тип (если он был известен после загрузки) в этом параметре. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceLoadingResult(byte[] data) {#ResourceLoadingResult-byte---}
```
public ResourceLoadingResult(byte[] data)
```


Создает экземпляр загрузки результата

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | byte[] | результат пользовательской загрузки должен быть всегда предоставлен, это может быть массив нулевой длины, если невозможно получить какой-либо результат |

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
### getData() {#getData--}
```
public byte[] getData()
```


Бинарные данные, загруженные с помощью пользовательского загрузчика - должны быть установлены после загрузки

**Возвращает:**
байт[] - массив байтовых значений
### getEncodingIfKnown() {#getEncodingIfKnown--}
```
public Charset getEncodingIfKnown()
```


Иногда кодировка ресурса известна после или во время загрузки. В таком случае пользовательский код может предоставить конвертеру эти знания через этот параметр. Вы можете оставить null в этом параметре, если кодировка неизвестна или не имеет значения.

**Возвращает:**
java.nio.charset.Charset — экземпляр набора символов
### getExceptionOfLoadingIfAny() {#getExceptionOfLoadingIfAny--}
```
public System.Exception getExceptionOfLoadingIfAny()
```


Иногда по каким-либо причинам невозможно загрузить запрошенный ресурс. Недоступность ресурса часто не приводит к сбою конвертации, и результирующий документ может быть создан в любом случае (но, возможно, в несколько худшем качестве, без изображений и т.д.). Если во время загрузки возникло исключение, просто перехватите его и укажите в этом параметре - иногда эта информация полезна конвертеру для отрисовки результата.

**Возвращает:**
com.aspose.ms.System.Exception — Исключение
### getMIMETypeIfKnown() {#getMIMETypeIfKnown--}
```
public String getMIMETypeIfKnown()
```


Иногда знание MIME-типа загружаемого ресурса полезно для конвертера. Вы можете указать MIME-тип (если он был известен после загрузки) в этом параметре. Пожалуйста, оставьте параметр равным нулю, если тип MIME неизвестен или нет необходимости его указывать.

**Возвращает:**
java.lang.String — строковое значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isLoadingCancelled() {#isLoadingCancelled--}
```
public boolean isLoadingCancelled()
```


Иногда по каким-то причинам не должна происходить загрузка пользовательского кода. В таком случае установите этот флаг как True. В таком случае преобразователь попытается использовать внутренний загрузчик ресурсов по умолчанию, чтобы получить этот результат (как он ведет себя в ситуации, когда пользовательская стратегия не указана).

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




### setEncodingIfKnown(Charset encodingIfKnown) {#setEncodingIfKnown-java.nio.charset.Charset-}
```
public void setEncodingIfKnown(Charset encodingIfKnown)
```


Иногда кодировка ресурса известна после или во время загрузки. В таком случае пользовательский код может предоставить конвертеру эти знания через этот параметр. Вы можете оставить null в этом параметре, если кодировка неизвестна или не имеет значения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| encodingIfKnown | java.nio.charset.Charset | Экземпляр набора символов |

### setExceptionOfLoadingIfAny(System.Exception exceptionOfLoadingIfAny) {#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-}
```
public void setExceptionOfLoadingIfAny(System.Exception exceptionOfLoadingIfAny)
```


Иногда по каким-либо причинам невозможно загрузить запрошенный ресурс. Недоступность ресурса часто не приводит к сбою конвертации, и результирующий документ может быть создан в любом случае (но, возможно, в несколько худшем качестве, без изображений и т.д.). Если во время загрузки возникло исключение, просто перехватите его и укажите в этом параметре - иногда эта информация полезна конвертеру для отрисовки результата.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| exceptionOfLoadingIfAny | com.aspose.ms.System.Исключение | Exception |

### setLoadingCancelled(boolean loadingCancelled) {#setLoadingCancelled-boolean-}
```
public void setLoadingCancelled(boolean loadingCancelled)
```


Иногда по каким-то причинам не должна происходить загрузка пользовательского кода. В таком случае установите этот флаг как True. В таком случае преобразователь попытается использовать внутренний загрузчик ресурсов по умолчанию, чтобы получить этот результат (как он ведет себя в ситуации, когда пользовательская стратегия не указана).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| loadingCancelled | boolean | логическое значение |

### setMIMETypeIfKnown(String MIMETypeIfKnown) {#setMIMETypeIfKnown-java.lang.String-}
```
public void setMIMETypeIfKnown(String MIMETypeIfKnown)
```


Иногда знание MIME-типа загружаемого ресурса полезно для конвертера. Вы можете указать MIME-тип (если он был известен после загрузки) в этом параметре. Пожалуйста, оставьте параметр равным нулю, если тип MIME неизвестен или нет необходимости его указывать.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| MIMETypeIfKnown | java.lang.String | Строковое значение |

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
