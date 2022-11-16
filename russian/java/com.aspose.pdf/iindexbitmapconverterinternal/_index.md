---
title: IIndexBitmapConverterInternal
second_title: Aspose.PDF для справки по Java API
description: Этот интерфейс заявлен для настройки алгоритмов квантования.
type: docs
weight: 436
url: /ru/java/com.aspose.pdf/iindexbitmapconverterinternal/
---
```
public interface IIndexBitmapConverterInternal
```

Этот интерфейс заявлен для настройки алгоритмов квантования. Пользователи могут реализовать свои собственные реализации этих алгоритмов (например, алгоритмы, основанные на неуправляемом коде).
## Методы

| Метод | Описание |
| --- | --- |
| [get1BppImageInternal(System.Drawing.Bitmap src)](#get1BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-) | Только для внутреннего использования Возвращает растровое представление 1Bpp |
| [get4BppImageInternal(System.Drawing.Bitmap src)](#get4BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-) | Только для внутреннего использования Возвращает растровое представление 4Bpp |
| [get8BppImageInternal(System.Drawing.Bitmap src)](#get8BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-) | Только для внутреннего использования Возвращает растровое представление 8Bpp |
### get1BppImageInternal(System.Drawing.Bitmap src) {#get1BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-}
```
public abstract System.Drawing.Bitmap get1BppImageInternal(System.Drawing.Bitmap src)
```


Только для внутреннего использования Возвращает растровое представление 1Bpp

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | com.aspose.ms.System.Drawing.Bitmap | Исходное растровое изображение. |

**Возвращает:**
com.aspose.ms.System.Drawing.Bitmap — растровое изображение в формате изображения 1 бит на пиксель.
### get4BppImageInternal(System.Drawing.Bitmap src) {#get4BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-}
```
public abstract System.Drawing.Bitmap get4BppImageInternal(System.Drawing.Bitmap src)
```


Только для внутреннего использования Возвращает растровое представление 4Bpp

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | com.aspose.ms.System.Drawing.Bitmap | Исходное растровое изображение. |

**Возвращает:**
com.aspose.ms.System.Drawing.Bitmap — растровое изображение в формате 4 бит/пиксель.
### get8BppImageInternal(System.Drawing.Bitmap src) {#get8BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-}
```
public abstract System.Drawing.Bitmap get8BppImageInternal(System.Drawing.Bitmap src)
```


Только для внутреннего использования Возвращает растровое представление 8Bpp

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | com.aspose.ms.System.Drawing.Bitmap | Исходное растровое изображение. |

**Возвращает:**
com.aspose.ms.System.Drawing.Bitmap — растровое изображение в формате изображения 8 бит на пиксель.