---
title: "Метод System::Drawing::Image::FromStream"
linktitle: "FromStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Drawing::Image::FromStream. Создаёт объект Image из указанного потока в C++."
type: docs
weight: 2900
url: /ru/cpp/system.drawing/image/fromstream/
---
## Image::FromStream method


Создаёт объект [Image](../) из указанного потока.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=true)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| поток | const SharedPtr\<System::IO::Stream\>\& | Поток, содержащий данные изображения |
| use_embedded_color_management | bool | IGNORED |
| validate_image_data | bool | IGNORED |

### ReturnValue

Указатель shared pointer на созданный объект [Image](../).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../)
* Class [Stream](../../../system.io/stream/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
