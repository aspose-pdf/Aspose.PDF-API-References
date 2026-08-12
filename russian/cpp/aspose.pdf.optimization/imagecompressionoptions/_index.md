---
title: "Класс Aspose::Pdf::Optimization::ImageCompressionOptions"
linktitle: "ImageCompressionOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Optimization::ImageCompressionOptions. Класс содержит набор параметров для сжатия изображений в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class


Класс содержит набор параметров для сжатия изображений.

```cpp
class ImageCompressionOptions : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_CompressImages](./get_compressimages/)() const | Если этот флаг установлен в true, изображения будут сжаты в документе. Уровень сжатия указывается свойством ImageQuality. |
| [get_Encoding](./get_encoding/)() const | Получает кодировку, используемую для сохранения изображений. |
| [get_ImageQuality](./get_imagequality/)() const | Указывает уровень сжатия изображения, когда используется флаг CompressImages. |
| [get_MaxResolution](./get_maxresolution/)() const | Указывает максимальное разрешение изображений. Если изображение имеет более высокое разрешение, оно будет масштабировано. |
| [get_ResizeImages](./get_resizeimages/)() const | Если этот флаг установлен в true и CompressImages также true, изображения будут изменены в размере, если их разрешение превышает указанный параметр MaxResolution. |
| [get_Version](./get_version/)() const | Версия алгоритма сжатия. Возможные значения: 1. стандартное сжатие, 2. быстрое (улучшенное сжатие, которое быстрее, чем стандартное, но может быть неприменимо не ко всем изображениям), 3. смешанное (стандартное сжатие применяется к изображениям, которые не могут быть сжаты более быстрым алгоритмом; это может дать лучшее сжатие, но медленнее, чем алгоритм \"fast\". Версия \"Fast\" не применяется для изменения размера изображений (будет использован стандартный метод). По умолчанию — \"Standard\"). |
| [ImageCompressionOptions](./imagecompressionoptions/)() |  |
| [set_CompressImages](./set_compressimages/)(bool) | Если этот флаг установлен в true, изображения будут сжаты в документе. Уровень сжатия указывается свойством ImageQuality. |
| [set_Encoding](./set_encoding/)(ImageEncoding) | Устанавливает кодировку, используемую для сохранения изображений. |
| [set_ImageQuality](./set_imagequality/)(int32_t) | Указывает уровень сжатия изображения, когда используется флаг CompressImages. |
| [set_MaxResolution](./set_maxresolution/)(int32_t) | Указывает максимальное разрешение изображений. Если изображение имеет более высокое разрешение, оно будет масштабировано. |
| [set_ResizeImages](./set_resizeimages/)(bool) | Если этот флаг установлен в true и CompressImages также true, изображения будут изменены в размере, если их разрешение превышает указанный параметр MaxResolution. |
| [set_Version](./set_version/)(ImageCompressionVersion) | Версия алгоритма сжатия. Возможные значения: 1. стандартное сжатие, 2. быстрое (улучшенное сжатие, которое быстрее, чем стандартное, но может быть неприменимо не ко всем изображениям), 3. смешанное (стандартное сжатие применяется к изображениям, которые не могут быть сжаты более быстрым алгоритмом; это может дать лучшее сжатие, но медленнее, чем алгоритм \"fast\". Версия \"Fast\" не применяется для изменения размера изображений (будет использован стандартный метод). По умолчанию — \"Standard\"). |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Optimization](../)
* Library [Aspose.PDF for C++](../../)
