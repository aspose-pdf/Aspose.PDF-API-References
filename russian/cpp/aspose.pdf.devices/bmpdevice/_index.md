---
title: "Aspose::Pdf::Devices::BmpDevice класс"
linktitle: "BmpDevice"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Devices::BmpDevice класс. Представляет устройство изображения, которое помогает сохранять страницы pdf‑документа в bmp в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.devices/bmpdevice/
---
## BmpDevice class


Представляет устройство изображения, которое помогает сохранять страницы PDF‑документа в формат bmp.

```cpp
class BmpDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Методы

| Метод | Описание |
| --- | --- |
| [BmpDevice](./bmpdevice/)() | Инициализирует новый экземпляр класса [BmpDevice](./) с разрешением по умолчанию. |
| [BmpDevice](./bmpdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [BmpDevice](./). |
| [BmpDevice](./bmpdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [BmpDevice](./) с заданными размерами изображения и разрешением. |
| [BmpDevice](./bmpdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [BmpDevice](./) с заданным размером страницы и разрешением. |
| [BmpDevice](./bmpdevice/)(int32_t, int32_t) | Инициализирует новый экземпляр класса [BmpDevice](./) с заданными размерами изображения, разрешением по умолчанию (=150). |
| [BmpDevice](./bmpdevice/)(const System::SharedPtr\<PageSize\>\&) | Инициализирует новый экземпляр класса [BmpDevice](./) с заданным размером страницы, разрешением по умолчанию (=150). |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Преобразует страницу в bmp и сохраняет её в выходном потоке. |
## См. также

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
