---
title: License
second_title: Aspose.PDF для справки по Java API
description: Предоставляет методы для лицензирования компонента.
type: docs
weight: 192
url: /ru/java/com.aspose.pdf/license/
---
**Наследование:**
java.lang.Object
```
public class License
```

Предоставляет методы для лицензирования компонента.

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке входной сборки, а затем во встроенных ресурсах вызов сборки.

Лицензия лицензия = новая лицензия();
license.setLicense("MyLicense.lic");
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [License()](#License--) | Инициализирует новый экземпляр этого класса. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isInternalFIPSSecurity()](#isInternalFIPSSecurity--) | По умолчанию мы используем безопасность jdk по умолчанию. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setInternalFIPSSecurity(boolean internalFIPSSecurity)](#setInternalFIPSSecurity-boolean-) | По умолчанию мы используем безопасность jre по умолчанию. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Лицензирует компонент. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Лицензирует компонент. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


Инициализирует новый экземпляр этого класса.

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке входной сборки, а затем во встроенных ресурсах вызов сборки.

Лицензия лицензия = новая лицензия();
license.setLicense("MyLicense.lic");

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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isInternalFIPSSecurity() {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```


По умолчанию мы используем безопасность jdk по умолчанию. Значение по умолчанию == ложь. В некоторых случаях настроенная среда Java не может поддерживать требуемые алгоритмы, поэтому мы можем предложить использовать внутреннюю встроенную защиту FIPS.

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




### setInternalFIPSSecurity(boolean internalFIPSSecurity) {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```


По умолчанию мы используем безопасность jre по умолчанию. Значение по умолчанию == ложь. В некоторых случаях настроенная среда Java не может поддерживать требуемые алгоритмы, поэтому мы можем предложить использовать внутреннюю встроенную защиту FIPS.

Обратите также внимание: в соответствии с алгоритмом JVM SecureRandom в некоторых операционных системах /dev/random ожидает определенное количество\шум\= будет сгенерирован на хост-компьютере перед возвратом результата. Библиотека, используемая для генерации случайных чисел в Oracle.\\u2019s JVM по умолчанию использует /dev/random для платформ UNIX. Хотя /dev/random более безопасен, он\Рекомендуется использовать /dev/urandom, если в конфигурации JVM по умолчанию есть задержки, или добавить устройства, генерирующие энтропию для /dev/random.

Следующая опция Java может помочь избежать задержек и переопределить параметр securerandom.source. -Djava.security.egd=файл:/dev/./urandom

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| internalFIPSSecurity | boolean | логическое значение |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Лицензирует компонент.

Поток, содержащий лицензию.

Используйте этот метод для загрузки лицензии из потока.

Лицензия лицензия = новая лицензия();
license.setLicense (мой поток);

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | лицензионный поток |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Лицензирует компонент.

Пытается найти лицензию в следующих местах:

1. Явный путь.

2. Папка файла jar компонента.

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке входной сборки, а затем во встроенных ресурсах вызов сборки.

Лицензия лицензия = новая лицензия();
license.setLicense("MyLicense.lic");

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseName | java.lang.String | Может быть полным или коротким именем файла или именем встроенного ресурса. Используйте пустую строку для переключения в режим оценки. |

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
