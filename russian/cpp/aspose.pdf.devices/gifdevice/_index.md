---
title: "Aspose::Pdf::Devices::GifDevice класс"
linktitle: "GifDevice"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Devices::GifDevice класс. Представляет устройство изображения, которое помогает сохранять страницы PDF‑документа в gif на C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf.devices/gifdevice/
---
## GifDevice class


Представляет устройство изображения, которое помогает сохранять страницы PDF‑документа в формат gif.

```cpp
class GifDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Методы

| Метод | Описание |
| --- | --- |
| [GifDevice](./gifdevice/)() | Инициализирует новый экземпляр класса [GifDevice](./) с разрешением по умолчанию. |
| [GifDevice](./gifdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [GifDevice](./). |
| [GifDevice](./gifdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [GifDevice](./) с указанными размерами изображения и разрешением. |
| [GifDevice](./gifdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [GifDevice](./) с указанным размером страницы и разрешением. |
| [GifDevice](./gifdevice/)(int32_t, int32_t) | Инициализирует новый экземпляр класса [GifDevice](./) с указанными размерами изображения, разрешением по умолчанию (=150). |
| [GifDevice](./gifdevice/)(const System::SharedPtr\<PageSize\>\&) | Инициализирует новый экземпляр класса [GifDevice](./) с указанным размером страницы, разрешением по умолчанию (=150). |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Преобразует страницу в gif и сохраняет её в выходном потоке. |
## См. также

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
