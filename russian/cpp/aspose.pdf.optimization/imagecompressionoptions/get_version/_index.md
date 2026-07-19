---
title: "Aspose::Pdf::Optimization::ImageCompressionOptions::get_Version метод"
linktitle: "get_Version"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Optimization::ImageCompressionOptions::get_Version метод. Версия алгоритма сжатия. Возможные значения: 1. стандартное сжатие, 2. быстрое (улучшенное сжатие, которое быстрее стандартного, но может быть неприменимо ко всем изображениям), 3. смешанное (стандартное сжатие применяется к изображениям, которые нельзя сжать более быстрым алгоритмом; это может дать лучшее сжатие, но работает медленнее, чем алгоритм \\\"fast\\\"). Версия \\\"Fast\\\" не применяется для изменения размера изображений (будет использован стандартный метод). По умолчанию \\\"Standard\\\" в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.pdf.optimization/imagecompressionoptions/get_version/
---
## ImageCompressionOptions::get_Version method


Версия алгоритма сжатия. Возможные значения: 1. стандартное сжатие, 2. быстрое (улучшенное сжатие, которое быстрее, чем стандартное, но может быть неприменимо не ко всем изображениям), 3. смешанное (стандартное сжатие применяется к изображениям, которые не могут быть сжаты более быстрым алгоритмом; это может дать лучшее сжатие, но медленнее, чем алгоритм \"fast\". Версия \"Fast\" не применяется для изменения размера изображений (будет использован стандартный метод). По умолчанию — \"Standard\").

```cpp
ImageCompressionVersion Aspose::Pdf::Optimization::ImageCompressionOptions::get_Version() const
```

## См. также

* Enum [ImageCompressionVersion](../../imagecompressionversion/)
* Class [ImageCompressionOptions](../)
* Namespace [Aspose::Pdf::Optimization](../../)
* Library [Aspose.PDF for C++](../../../)
