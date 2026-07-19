---
title: "Метод Aspose::Pdf::XImageCollection::Add"
linktitle: "Add"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::XImageCollection::Add. Добавляет объект в конец коллекции, чтобы к объекту можно было обратиться по последнему индексу в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf/ximagecollection/add/
---
## XImageCollection::Add(const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\&) method


Добавляет элемент в конец коллекции, чтобы к элементу можно было обратиться по последнему индексу.

```cpp
System::String Aspose::Pdf::XImageCollection::Add(const System::SharedPtr<Aspose::Pdf::BitmapInfo> &bitmapInfo)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| bitmapInfo | const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\& | Объект, содержащий массив пикселей и информацию о bitmap (Width, Height, PixelFormat). |

### ReturnValue

Имя добавленного изображения.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BitmapInfo](../../bitmapinfo/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Add(const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\&, Aspose::Pdf::ImageFilterType) method


Добавляет элемент в конец коллекции, чтобы к элементу можно было обратиться по последнему индексу.

```cpp
System::String Aspose::Pdf::XImageCollection::Add(const System::SharedPtr<Aspose::Pdf::BitmapInfo> &bitmapInfo, Aspose::Pdf::ImageFilterType filterType)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| bitmapInfo | const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\& | Объект, содержащий массив пикселей и информацию о bitmap (Width, Height, PixelFormat). |
| filterType | Aspose::Pdf::ImageFilterType | Тип фильтра изображения. |

### ReturnValue

Имя добавленного изображения.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BitmapInfo](../../bitmapinfo/)
* Enum [ImageFilterType](../../imagefiltertype/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Add(const System::SharedPtr\<System::IO::Stream\>\&) method


Добавляет элемент в конец коллекции, чтобы к элементу можно было обратиться по последнему индексу.

```cpp
System::String Aspose::Pdf::XImageCollection::Add(const System::SharedPtr<System::IO::Stream> &image)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий данные изображения (в формате JPEG). |

### ReturnValue

Имя добавленного изображения.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Add(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::ImageFilterType) method


Добавляет элемент в конец коллекции, чтобы к элементу можно было обратиться по последнему индексу.

```cpp
System::String Aspose::Pdf::XImageCollection::Add(const System::SharedPtr<System::IO::Stream> &image, Aspose::Pdf::ImageFilterType filterType)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий данные изображения. |
| filterType | Aspose::Pdf::ImageFilterType | Тип фильтра изображения. |

### ReturnValue

Имя добавленного изображения.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [ImageFilterType](../../imagefiltertype/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Add(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) method


Добавляет элемент в конец коллекции, чтобы к элементу можно было обратиться по последнему индексу.

```cpp
void Aspose::Pdf::XImageCollection::Add(const System::SharedPtr<System::IO::Stream> &image, int32_t quality)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий данные изображения (в формате JPEG). |
| качество | int32_t | Качество JPEG. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
