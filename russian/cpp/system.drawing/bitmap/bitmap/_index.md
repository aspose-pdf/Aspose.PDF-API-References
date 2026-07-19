---
title: "System::Drawing::Bitmap::Bitmap конструктор"
linktitle: "Bitmap"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Bitmap::Bitmap конструктор. Создает новый объект Bitmap из указанного существующего изображения в C++."
type: docs
weight: 100
url: /ru/cpp/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) constructor


Создает новый объект [Bitmap](../) из указанного существующего изображения.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| оригинал | const SharedPtr\<Image\>\& | Существующее изображение, из которого создается растровое изображение |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) constructor


Создает новый объект [Bitmap](../) из указанного существующего изображения, масштабированного до указанного размера.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| оригинал | const SharedPtr\<Image\>\& | Существующее изображение, из которого создается растровое изображение |
| size | const Size\& | Размер нового изображения |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Size](../../size/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) constructor


Создает новый объект [Bitmap](../) из указанного существующего изображения с шириной и высотой, масштабированными до указанных значений.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| оригинал | const SharedPtr\<Image\>\& | Существующее изображение, из которого создается растровое изображение |
| width | int | Ширина нового изображения |
| height | int | Высота нового изображения |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) constructor


Создает новый объект [Bitmap](../) из указанного потока.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | const SharedPtr\<System::IO::Stream\>\& | Поток, содержащий данные изображения |
| useIcm | bool | IGNORED |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const String\&) constructor


Создает новый объект [Bitmap](../) из указанного файла.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const String\& | Имя файла, содержащего данные изображения |

## См. также

* Class [String](../../../system/string/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(const String\&, bool) constructor


Создает новый объект [Bitmap](../) из указанного файла.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const String\& | Имя файла, содержащего данные изображения |
| useIcm | bool | IGNORED |

## См. также

* Class [String](../../../system/string/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
## Bitmap::Bitmap(int, int, Imaging::PixelFormat) constructor


Создает новый объект [Bitmap](../), который представляет растровое изображение с указанной шириной, высотой, форматом пикселей и данными пикселей.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина изображения |
| height | int | Высота изображения |
| формат | Imaging::PixelFormat | Формат пикселей изображения |

## См. также

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
