---
title: PKCS7Detached
second_title: Aspose.PDF для справки по Java API
description: Представляет объект PKCS7, соответствующий спецификации PKCS7 в Internet RFC 2315 PKCS 7 Синтаксис криптографических сообщений версии 1.5.
type: docs
weight: 256
url: /ru/java/com.aspose.pdf/pkcs7detached/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.Signature](../../com.aspose.pdf/signature)
```
public final class PKCS7Detached extends Signature
```

Представляет PKCS\Объект #7, соответствующий PKCS\ Спецификация #7 в Internet RFC 2315, PKCS\#7: Синтаксис криптографических сообщений, версия 1.5. Дайджест исходного подписанного сообщения в диапазоне байтов документа включается как обычный PKCS.\# 7 Поле SignedData. Никакие данные не должны инкапсулироваться в PKCS.\# 7 Поле SignedData.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PKCS7Detached(InputStream image)](#PKCS7Detached-java.io.InputStream-) | Инициализирует новый экземпляр класса PKCS7Detached. |
| [PKCS7Detached()](#PKCS7Detached--) | Инициализирует новый экземпляр класса PKCS7Detached. |
| [PKCS7Detached(String pfx, String password)](#PKCS7Detached-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса PKCS7Detached. |
| [PKCS7Detached(InputStream pfx, String password)](#PKCS7Detached-java.io.InputStream-java.lang.String-) | Инициализирует новый экземпляр класса PKCS7Detached. |
## Методы

| Метод | Описание |
| --- | --- |
| [close()](#close--) | Деструктор, закрывающий временные потоки (при необходимости). |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAuthority()](#getAuthority--) | Имя лица или органа, подписавшего документ. |
| [getByteRange()](#getByteRange--) | Получить массив пар целых чисел (начальное смещение в байтах, длина в байтах), которые должны описывать точный диапазон байтов для вычисления дайджеста. |
| [getClass()](#getClass--) |  |
| [getContactInfo()](#getContactInfo--) | Получите информацию, предоставленную подписывающей стороной, чтобы получатель мог связаться с подписывающей стороной для проверки подписи, например, номер телефона. |
| [getCustomAppearance()](#getCustomAppearance--) | Получает/задает настраиваемый внешний вид. |
| [getDate()](#getDate--) | Получает время подписания. |
| [getImageInternal()](#getImageInternal--) | Получает поток изображения. |
| [getLocation()](#getLocation--) | Получает имя хоста ЦП или физическое расположение подписи. |
| [getOcspSettings()](#getOcspSettings--) | Получает/устанавливает настройки ocsp. |
| [getReason()](#getReason--) | Получает причину подписания, например (я согласен\\u0420\\u0406\\u0420\\u201a\\u0412�). |
| [getSignatureReferences()](#getSignatureReferences--) | получить ссылки на подписи |
| [getTimestampSettings()](#getTimestampSettings--) | Получает настройки метки времени. |
| [getUseLtv()](#getUseLtv--) | Получает/устанавливает флаг проверки LTV. |
| [hashCode()](#hashCode--) |  |
| [isShowProperties()](#isShowProperties--) | Принудительно показать/скрыть свойства подписи. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAuthority(String value)](#setAuthority-java.lang.String-) | Устанавливает имя лица или органа, подписывающего документ. |
| [setContactInfo(String value)](#setContactInfo-java.lang.String-) | Задайте информацию, предоставленную подписывающей стороной, чтобы получатель мог связаться с подписывающей стороной для проверки подписи, например, номер телефона. |
| [setCustomAppearance(SignatureCustomAppearance value)](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | Получает/задает настраиваемый внешний вид. |
| [setDate(Date value)](#setDate-java.util.Date-) | Установите время подписания. |
| [setImage(InputStream _signatureAppearanceStream)](#setImage-java.io.InputStream-) | Устанавливает поток изображения. |
| [setImageInternal(System.IO.Stream value)](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [setLocation(String value)](#setLocation-java.lang.String-) | Задает имя хоста ЦП или физическое расположение подписи. |
| [setOcspSettings(OcspSettings value)](#setOcspSettings-com.aspose.pdf.OcspSettings-) | Получает/устанавливает настройки ocsp. |
| [setReason(String value)](#setReason-java.lang.String-) | Устанавливает причину подписания, например (Я согласен\\u0420\\u0406\\u0420\\u201a\\u0412�). |
| [setShowProperties(boolean value)](#setShowProperties-boolean-) | Принудительно показать/скрыть свойства подписи. |
| [setTimestampSettings(TimestampSettings value)](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | Устанавливает настройки метки времени. |
| [setUseLtv(boolean value)](#setUseLtv-boolean-) | Получает/устанавливает флаг проверки LTV. |
| [toString()](#toString--) |  |
| [verify()](#verify--) | Проверьте документ относительно этой подписи и верните true, если документ действителен или в противном случае ложен. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PKCS7Detached(InputStream image) {#PKCS7Detached-java.io.InputStream-}
```
public PKCS7Detached(InputStream image)
```


Инициализирует новый экземпляр класса PKCS7Detached.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | java.io.InputStream | Это изображение будет определять внешний вид подписи на странице. |

### PKCS7Detached() {#PKCS7Detached--}
```
public PKCS7Detached()
```


Инициализирует новый экземпляр класса PKCS7Detached.

### PKCS7Detached(String pfx, String password) {#PKCS7Detached-java.lang.String-java.lang.String-}
```
public PKCS7Detached(String pfx, String password)
```


Инициализирует новый экземпляр класса PKCS7Detached.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pfx | java.lang.String | Pfx-файл, содержащий сертификат для подписи. |
| password | java.lang.String | Пароль для доступа к закрытому ключу в сертификате. |

### PKCS7Detached(InputStream pfx, String password) {#PKCS7Detached-java.io.InputStream-java.lang.String-}
```
public PKCS7Detached(InputStream pfx, String password)
```


Инициализирует новый экземпляр класса PKCS7Detached.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pfx | java.io.InputStream | Поток с данными сертификата, организованными как pfx. |
| password | java.lang.String | Пароль для доступа к закрытому ключу в сертификате. |

### close() {#close--}
```
public void close()
```


Деструктор, закрывающий временные потоки (при необходимости).

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
### getAuthority() {#getAuthority--}
```
public final String getAuthority()
```


Имя лица или органа, подписавшего документ.

**Возвращает:**
java.lang.String — строковое значение
### getByteRange() {#getByteRange--}
```
public int[] getByteRange()
```


Получить массив пар целых чисел (начальное смещение в байтах, длина в байтах), которые должны описывать точный диапазон байтов для вычисления дайджеста.

**Возвращает:**
инт[] - массив значений int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getContactInfo() {#getContactInfo--}
```
public String getContactInfo()
```


Получите информацию, предоставленную подписывающей стороной, чтобы получатель мог связаться с подписывающей стороной для проверки подписи, например, номер телефона.

**Возвращает:**
java.lang.String — строковое значение
### getCustomAppearance() {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```


Получает/задает настраиваемый внешний вид.

**Возвращает:**
[SignatureCustomAppearance](../../com.aspose.pdf/signaturecustomappearance) - Экземпляр SignatureCustomAppearance
### getDate() {#getDate--}
```
public Date getDate()
```


Получает время подписания.

**Возвращает:**
[Date](../../java.util/date) - Значение даты
### getImageInternal() {#getImageInternal--}
```
public System.IO.Stream getImageInternal()
```


Получает поток изображения.

Только для внутреннего использования

**Возвращает:**
com.aspose.ms.System.IO.Stream — объект потока
### getLocation() {#getLocation--}
```
public String getLocation()
```


Получает имя хоста ЦП или физическое расположение подписи.

**Возвращает:**
java.lang.String — строковое значение
### getOcspSettings() {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```


Получает/устанавливает настройки ocsp.

**Возвращает:**
[OcspSettings](../../com.aspose.pdf/ocspsettings) - Экземпляр OcspSettings
### getReason() {#getReason--}
```
public String getReason()
```


Получает причину подписания, например (я согласен\\u0420\\u0406\\u0420\\u201a\\u0412�).

**Возвращает:**
java.lang.String — строковое значение
### getSignatureReferences() {#getSignatureReferences--}
```
public List<SignatureReference> getSignatureReferences()
```


получить ссылки на подписи

**Возвращает:**
java.util.List<com.aspose.pdf.engine.security.impl.signatures.SignatureReference> — объект java.util.List 
### getTimestampSettings() {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```


Получает настройки метки времени.

**Возвращает:**
[TimestampSettings](../../com.aspose.pdf/timestampsettings) - Настройки метки времени
### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


Получает/устанавливает флаг проверки LTV.

**Возвращает:**
boolean - логическое значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isShowProperties() {#isShowProperties--}
```
public boolean isShowProperties()
```


Принудительно показать/скрыть свойства подписи. В случае, если ShowProperties имеет значение true, поле подписи имеет предопределенный формат отображения (строки для представления): -------------------------------- ----------- С цифровой подписью\{тема сертификата\ } Свидание:\{Дата подписания\ } Причина:\{подпись.Причина\ } Расположение:\{подпись.Расположение\ } ------------------------------------------- куда\{ИКС\} является заполнителем для значения X. Также подпись может иметь изображение, в этом случае перечисленные строки размещаются поверх изображения. ShowProperties по умолчанию имеет значение true.

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




### setAuthority(String value) {#setAuthority-java.lang.String-}
```
public void setAuthority(String value)
```


Устанавливает имя лица или органа, подписывающего документ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public void setContactInfo(String value)
```


Задайте информацию, предоставленную подписывающей стороной, чтобы получатель мог связаться с подписывающей стороной для проверки подписи, например, номер телефона.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setCustomAppearance(SignatureCustomAppearance value) {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
```
public final void setCustomAppearance(SignatureCustomAppearance value)
```


Получает/задает настраиваемый внешний вид.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SignatureCustomAppearance](../../com.aspose.pdf/signaturecustomappearance) | Экземпляр SignatureCustomAppearance |

### setDate(Date value) {#setDate-java.util.Date-}
```
public void setDate(Date value)
```


Установите время подписания.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date | Объект даты |

### setImage(InputStream _signatureAppearanceStream) {#setImage-java.io.InputStream-}
```
public void setImage(InputStream _signatureAppearanceStream)
```


Устанавливает поток изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| _signatureAppearanceStream | java.io.InputStream | Паровой объект |

### setImageInternal(System.IO.Stream value) {#setImageInternal-com.aspose.ms.System.IO.Stream-}
```
public void setImageInternal(System.IO.Stream value)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | com.aspose.ms.System.IO.Stream |  |

### setLocation(String value) {#setLocation-java.lang.String-}
```
public void setLocation(String value)
```


Задает имя хоста ЦП или физическое расположение подписи.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setOcspSettings(OcspSettings value) {#setOcspSettings-com.aspose.pdf.OcspSettings-}
```
public void setOcspSettings(OcspSettings value)
```


Получает/устанавливает настройки ocsp.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [OcspSettings](../../com.aspose.pdf/ocspsettings) | Экземпляр OcspSettings |

### setReason(String value) {#setReason-java.lang.String-}
```
public void setReason(String value)
```


Устанавливает причину подписания, например (Я согласен\\u0420\\u0406\\u0420\\u201a\\u0412�).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```


Принудительно показать/скрыть свойства подписи. В случае, если ShowProperties имеет значение true, поле подписи имеет предопределенный формат отображения (строки для представления): -------------------------------- ----------- С цифровой подписью\{тема сертификата\ } Свидание:\{Дата подписания\ } Причина:\{подпись.Причина\ } Расположение:\{подпись.Расположение\ } ------------------------------------------- куда\{ИКС\} является заполнителем для значения X. Также подпись может иметь изображение, в этом случае перечисленные строки размещаются поверх изображения. ShowProperties по умолчанию имеет значение true.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setTimestampSettings(TimestampSettings value) {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
```
public void setTimestampSettings(TimestampSettings value)
```


Устанавливает настройки метки времени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Отметка времениНастройки](../../com.aspose.pdf/timestampsettings) | TimestampSettings |

### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


Получает/устанавливает флаг проверки LTV.

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
### verify() {#verify--}
```
public boolean verify()
```


Проверьте документ относительно этой подписи и верните true, если документ действителен или в противном случае ложен.

**Возвращает:**
boolean - истина, если документ действителен.
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
