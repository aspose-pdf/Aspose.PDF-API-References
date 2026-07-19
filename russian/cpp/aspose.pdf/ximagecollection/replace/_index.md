---
title: "Aspose::Pdf::XImageCollection::Replace метод"
linktitle: "Заменить"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::XImageCollection::Replace метод. Заменить изображение в коллекции другим изображением в C++."
type: docs
weight: 1600
url: /ru/cpp/aspose.pdf/ximagecollection/replace/
---
## XImageCollection::Replace(int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Заменить изображение в коллекции другим изображением.

```cpp
void Aspose::Pdf::XImageCollection::Replace(int32_t index, const System::SharedPtr<System::IO::Stream> &stream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int32_t | Индекс элемента коллекции, который будет заменён в диапазоне [1..images count]. |
| поток | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий данные изображения (в формате JPEG). |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Replace(int32_t, const System::SharedPtr\<System::IO::Stream\>\&, int32_t) method


Заменить изображение в коллекции другим изображением.

```cpp
void Aspose::Pdf::XImageCollection::Replace(int32_t index, const System::SharedPtr<System::IO::Stream> &stream, int32_t quality)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int32_t | Индекс элемента коллекции, который будет заменён в диапазоне [1..images count]. |
| поток | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий данные изображения (в формате JPEG). |
| качество | int32_t | Качество JPEG. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## XImageCollection::Replace(int32_t, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, bool) method


Заменить изображение в коллекции другим изображением.

```cpp
void Aspose::Pdf::XImageCollection::Replace(int32_t index, const System::SharedPtr<System::IO::Stream> &stream, int32_t quality, bool isBlackAndWhite)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int32_t | Индекс элемента коллекции, который будет заменён в диапазоне [1..images count]. |
| поток | const System::SharedPtr\<System::IO::Stream\>\& | Поток, содержащий данные изображения (в формате JPEG). |
| качество | int32_t | Качество JPEG‑сжатия в процентах (допустимые значения от 0 до 100). |
| isBlackAndWhite | bool | Если true, изображение сжимается методом CCITT, который обеспечивает лучшее сжатие для чёрно‑белого изображения. Может использоваться только для чёрно‑белых изображений. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XImageCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
