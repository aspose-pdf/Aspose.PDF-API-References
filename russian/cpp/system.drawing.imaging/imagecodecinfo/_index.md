---
title: "System::Drawing::Imaging::ImageCodecInfo класс"
linktitle: "ImageCodecInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Imaging::ImageCodecInfo класс. Предоставляет информацию о кодеке изображения. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1000
url: /ru/cpp/system.drawing.imaging/imagecodecinfo/
---
## ImageCodecInfo class


Предоставляет информацию о кодеке изображения. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ImageCodecInfo : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_FormatID](./get_formatid/)() const | Возвращает GUID, связанный с форматом кодека, представленного текущим объектом. |
| [get_MimeType](./get_mimetype/)() | Возвращает тип Multipurpose Internet Mail Extensions (MIME) кодека, представленного текущим объектом. |
| static [GetImageDecoders](./getimagedecoders/)() | Возвращает массив объектов [ImageCodecInfo](./), представляющих поддерживаемые декодеры изображений. |
| static [GetImageEncoders](./getimageencoders/)() | Возвращает массив объектов [ImageCodecInfo](./), представляющих поддерживаемые кодировщики изображений. |
| [set_FormatID](./set_formatid/)(const Guid\&) | Устанавливает GUID, связанный с форматом кодека, представленного текущим объектом. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
