---
title: "Aspose::Pdf::Devices::PngDevice класс"
linktitle: "PngDevice"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Devices::PngDevice класс. Представляет устройство изображения, которое помогает сохранять страницы pdf‑документа в png в C++."
type: docs
weight: 1100
url: /ru/cpp/aspose.pdf.devices/pngdevice/
---
## PngDevice class


Представляет устройство изображения, которое помогает сохранять страницы PDF‑документа в формат png.

```cpp
class PngDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_TransparentBackground](./get_transparentbackground/)() const | Определяет, имеет ли изображение прозрачный фон. |
| [PngDevice](./pngdevice/)() | Инициализирует новый экземпляр класса [PngDevice](./) с разрешением по умолчанию. |
| [PngDevice](./pngdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [PngDevice](./). |
| [PngDevice](./pngdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [PngDevice](./) с заданными размерами изображения и разрешением. |
| [PngDevice](./pngdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [PngDevice](./) с заданным размером страницы и разрешением. |
| [PngDevice](./pngdevice/)(int32_t, int32_t) | Инициализирует новый экземпляр класса [PngDevice](./) с заданными размерами изображения, разрешением по умолчанию (=150). |
| [PngDevice](./pngdevice/)(const System::SharedPtr\<PageSize\>\&) | Инициализирует новый экземпляр класса [PngDevice](./) с заданным размером страницы, разрешением по умолчанию (=150). |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Преобразует страницу в PNG и сохраняет её в выходном потоке. |
| [set_TransparentBackground](./set_transparentbackground/)(bool) | Устанавливает, имеет ли изображение прозрачный фон. |
## См. также

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
