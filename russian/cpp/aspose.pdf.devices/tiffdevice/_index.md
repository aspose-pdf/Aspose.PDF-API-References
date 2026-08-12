---
title: "Aspose::Pdf::Devices::TiffDevice класс"
linktitle: "TiffDevice"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Devices::TiffDevice класс. Этот класс помогает сохранять PDF‑документ постранично в одно TIFF‑изображение в C++."
type: docs
weight: 1500
url: /ru/cpp/aspose.pdf.devices/tiffdevice/
---
## TiffDevice class


Этот класс помогает сохранять pdf‑документ постранично в одно tiff‑изображение.

```cpp
class TiffDevice : public Aspose::Pdf::Devices::DocumentDevice
```

## Методы

| Метод | Описание |
| --- | --- |
| [BinarizeBradley](./binarizebradley/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, double) | Выполняет бинаризацию Брэдли для входного потока. |
| [get_FormPresentationMode](./get_formpresentationmode/)() const | Получает режим отображения формы. |
| [get_Height](./get_height/)() const | Получает высоту выходного изображения. |
| [get_RenderingOptions](./get_renderingoptions/)() const | Получает параметры рендеринга. |
| [get_Resolution](./get_resolution/)() const | Получает разрешение изображения. |
| [get_Settings](./get_settings/)() const | Получает настройки для отображения PDF в TIFF‑изображение. |
| [get_Width](./get_width/)() const | Получает ширину выходного изображения. |
| [Process](./process/)(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) override | Преобразует определённые страницы документа в TIFF и сохраняет их в выходном потоке. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Выполняет некоторую операцию над заданной страницей, например, преобразует страницу в графическое изображение. |
| [set_FormPresentationMode](./set_formpresentationmode/)(Aspose::Pdf::Devices::FormPresentationMode) | Устанавливает режим отображения формы. |
| [set_RenderingOptions](./set_renderingoptions/)(const System::SharedPtr\<Aspose::Pdf::RenderingOptions\>\&) | Устанавливает параметры рендеринга. |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<TiffSettings\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)() | Инициализирует новый экземпляр класса [TiffDevice](./) с настройками по умолчанию. |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&, const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, const System::SharedPtr\<TiffSettings\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t, const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<TiffSettings\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(int32_t, int32_t) | Инициализирует новый экземпляр класса [TiffDevice](./). |
| [TiffDevice](./tiffdevice/)(const System::SharedPtr\<PageSize\>\&) | Инициализирует новый экземпляр класса [TiffDevice](./). |
## См. также

* Class [DocumentDevice](../documentdevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
