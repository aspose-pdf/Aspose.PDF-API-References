---
title: TimestampSettings
second_title: Aspose.PDF для справки по Java API
description: Представляет параметры ocsp, используемые в процессе подписания.
type: docs
weight: 391
url: /ru/java/com.aspose.pdf/timestampsettings/
---
**Наследование:**
java.lang.Object
```
public class TimestampSettings
```

Представляет параметры ocsp, используемые в процессе подписания.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TimestampSettings(String serverUrl, String basicAuthCredentials)](#TimestampSettings-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса TimestampSettings. |
| [TimestampSettings(String serverUrl, String basicAuthCredentials, int digestHashAlgorithm)](#TimestampSettings-java.lang.String-java.lang.String-int-) | Инициализирует новый экземпляр класса TimestampSettings. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBasicAuthCredentials()](#getBasicAuthCredentials--) | Получает базовые учетные данные для проверки подлинности. Имя пользователя и пароль объединяются в строку «имя пользователя: пароль». |
| [getClass()](#getClass--) |  |
| [getDigestHashAlgorithm()](#getDigestHashAlgorithm--) | Получает/задает алгоритм дайджеста для внутренних хеш-функций. |
| [getServerUrl()](#getServerUrl--) | Получает URL-адрес сервера метки времени. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBasicAuthCredentials(String value)](#setBasicAuthCredentials-java.lang.String-) | Задает базовые учетные данные для аутентификации. Имя пользователя и пароль объединяются в строку «имя пользователя: пароль». |
| [setDigestHashAlgorithm(int value)](#setDigestHashAlgorithm-int-) | Получает/задает алгоритм дайджеста для внутренних хеш-функций. |
| [setServerUrl(String value)](#setServerUrl-java.lang.String-) | Устанавливает URL-адрес сервера временных меток. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TimestampSettings(String serverUrl, String basicAuthCredentials) {#TimestampSettings-java.lang.String-java.lang.String-}
```
public TimestampSettings(String serverUrl, String basicAuthCredentials)
```


Инициализирует новый экземпляр класса TimestampSettings.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| serverUrl | java.lang.String | URL-адрес сервера меток времени. |
| basicAuthCredentials | java.lang.String | Учетные данные базовой аутентификации, имя пользователя и пароль объединяются в строку «имя пользователя: пароль». |

### TimestampSettings(String serverUrl, String basicAuthCredentials, int digestHashAlgorithm) {#TimestampSettings-java.lang.String-java.lang.String-int-}
```
public TimestampSettings(String serverUrl, String basicAuthCredentials, int digestHashAlgorithm)
```


Инициализирует новый экземпляр класса TimestampSettings.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| serverUrl | java.lang.String | URL-адрес сервера меток времени. |
| basicAuthCredentials | java.lang.String | Учетные данные базовой аутентификации, имя пользователя и пароль объединяются в строку «имя пользователя: пароль». |
| digestHashAlgorithm | int | Имя алгоритма хэширования, если оно не указано, используется sha1. |

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
### getBasicAuthCredentials() {#getBasicAuthCredentials--}
```
public String getBasicAuthCredentials()
```


Получает базовые учетные данные для проверки подлинности. Имя пользователя и пароль объединяются в строку «имя пользователя: пароль».

**Возвращает:**
java.lang.String — строковое значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDigestHashAlgorithm() {#getDigestHashAlgorithm--}
```
public final int getDigestHashAlgorithm()
```


Получает/задает алгоритм дайджеста для внутренних хеш-функций.

**Возвращает:**
int - элемент DigestHashAlgorithm
### getServerUrl() {#getServerUrl--}
```
public String getServerUrl()
```


Получает URL-адрес сервера метки времени.

**Возвращает:**
java.lang.String — строковое значение
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




### setBasicAuthCredentials(String value) {#setBasicAuthCredentials-java.lang.String-}
```
public void setBasicAuthCredentials(String value)
```


Задает базовые учетные данные для аутентификации. Имя пользователя и пароль объединяются в строку «имя пользователя: пароль».

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setDigestHashAlgorithm(int value) {#setDigestHashAlgorithm-int-}
```
public final void setDigestHashAlgorithm(int value)
```


Получает/задает алгоритм дайджеста для внутренних хеш-функций.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент DigestHashAlgorithm |

### setServerUrl(String value) {#setServerUrl-java.lang.String-}
```
public void setServerUrl(String value)
```


Устанавливает URL-адрес сервера временных меток.

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
