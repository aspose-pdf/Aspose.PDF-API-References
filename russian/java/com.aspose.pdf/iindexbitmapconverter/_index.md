---
title: IIndexBitmapConverter
second_title: Aspose.PDF для справки по Java API
description: Этот интерфейс заявлен для настройки алгоритмов квантования.
type: docs
weight: 435
url: /ru/java/com.aspose.pdf/iindexbitmapconverter/
---
```
public interface IIndexBitmapConverter
```

Этот интерфейс заявлен для настройки алгоритмов квантования. Пользователи могут реализовать свои собственные реализации этих алгоритмов (например, алгоритмы, основанные на неуправляемом коде).
## Методы

| Метод | Описание |
| --- | --- |
| [get1BppImage(BufferedImage src)](#get1BppImage-java.awt.image.BufferedImage-) | Возвращает растровое представление 1Bpp |
| [get4BppImage(BufferedImage src)](#get4BppImage-java.awt.image.BufferedImage-) | Возвращает растровое представление 4Bpp |
| [get8BppImage(BufferedImage src)](#get8BppImage-java.awt.image.BufferedImage-) | Возвращает растровое представление 4Bpp |
### get1BppImage(BufferedImage src) {#get1BppImage-java.awt.image.BufferedImage-}
```
public abstract BufferedImage get1BppImage(BufferedImage src)
```


Возвращает растровое представление 1Bpp

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | java.awt.image.BufferedImage | Исходное растровое изображение. |

**Возвращает:**
java.awt.image.BufferedImage — растровое изображение в формате изображения 1 бит на пиксель.
### get4BppImage(BufferedImage src) {#get4BppImage-java.awt.image.BufferedImage-}
```
public abstract BufferedImage get4BppImage(BufferedImage src)
```


Возвращает растровое представление 4Bpp

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | java.awt.image.BufferedImage | Исходное растровое изображение. |

**Возвращает:**
java.awt.image.BufferedImage — растровое изображение в формате 4 бит/пиксель.
### get8BppImage(BufferedImage src) {#get8BppImage-java.awt.image.BufferedImage-}
```
public abstract BufferedImage get8BppImage(BufferedImage src)
```


Возвращает растровое представление 4Bpp

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | java.awt.image.BufferedImage | Исходное растровое изображение. |

**Возвращает:**
java.awt.image.BufferedImage — растровое изображение в формате 4 бит/пиксель.