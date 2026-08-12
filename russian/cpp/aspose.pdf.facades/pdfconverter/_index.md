---
title: "Aspose::Pdf::Facades::PdfConverter класс"
linktitle: "PdfConverter"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfConverter класс. Представляет класс для преобразования каждой страницы pdf‑файла в изображения, теперь поддерживает BMP, JPEG, PNG и TIFF. Поддерживаемое содержимое в pdf: изображения, формы, комментарии в C++."
type: docs
weight: 1800
url: /ru/cpp/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class


Представляет класс для преобразования каждой страницы PDF‑файла в изображения, сейчас поддерживает BMP, JPEG, PNG и TIFF. Поддерживаемое содержимое PDF: изображения, формы, комментарии.

```cpp
class PdfConverter : public Aspose::Pdf::Facades::Facade
```

## Методы

| Метод | Описание |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Привязывает файл [Pdf](../../aspose.pdf/) для конвертации. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Привязывает поток [Pdf](../../aspose.pdf/) для конвертации. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Привязывает PDF‑документ к экземпляру [PdfConverter](./) для дальнейшей обработки. |
| [Close](./close/)() override | Закрывает экземпляр [PdfConverter](./) и освобождает ресурсы. |
| [DoConvert](./doconvert/)() | Выполняет некоторые начальные работы по конвертации pdf‑документа в изображения. |
| [get_CoordinateType](./get_coordinatetype/)() const | Получает тип координат страницы (Media/Crop‑коробки). Значение CropBox используется по умолчанию. |
| [get_EndPage](./get_endpage/)() | Получает конечную позицию, которую вы хотите конвертировать. |
| [get_FormPresentationMode](./get_formpresentationmode/)() const | Получает режим отображения формы. |
| [get_PageCount](./get_pagecount/)() | Получает количество страниц. |
| [get_Password](./get_password/)() const | Получает OwnerPassword документа. |
| [get_RenderingOptions](./get_renderingoptions/)() const | Получает параметры рендеринга. |
| [get_Resolution](./get_resolution/)() const | Получает разрешение при конвертации. Чем выше разрешение, тем медленнее скорость конвертации. Значение по умолчанию — 150. |
| [get_ShowHiddenAreas](./get_showhiddenareas/)() const | Получает флаг, контролирующий видимость скрытых областей на странице. |
| [get_StartPage](./get_startpage/)() const | Получает начальную позицию, которую вы хотите конвертировать. Минимальное значение — 1. |
| [get_UserPassword](./get_userpassword/)() const | Получает UserPassword документа. |
| [GetNextImage](./getnextimage/)(const System::String\&) | Сохраняет изображение в файл с форматом изображения по умолчанию — jpeg. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<PageSize\>\&) | Сохраняет изображение в файл с указанным размером страницы и форматом изображения по умолчанию — jpeg. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Сохраняет изображение в файл с указанным форматом изображения. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Сохраняет изображение в файл с указанным размером страницы и форматом изображения. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&) | Сохраняет изображение в поток с форматом изображения по умолчанию — jpeg. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) | Сохраняет изображение в поток с указанным размером страницы. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Сохраняет изображение в поток с заданным форматом изображения. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Сохраняет изображение в поток с указанным размером страницы. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t, int32_t) | Сохраняет изображение в файл с заданным форматом изображения, размерами и качеством. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t, int32_t) | Сохраняет изображение в поток с указанным форматом изображения, размерами и качеством. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, double, double, int32_t) | Сохраняет изображение в файл с указанным форматом изображения, размером изображения и качеством. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, double, double, int32_t) | Сохраняет изображение в поток с указанным форматом изображения, размером и качеством. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t) | Сохраняет изображение в файл с заданным форматом изображения и размерами. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t, int32_t) | Сохраняет изображение в поток с указанным форматом изображения, размером и качеством. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Сохраняет изображение в поток с заданным форматом изображения и качеством. |
| [GetNextImage](./getnextimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Сохраняет изображение в поток с заданным размером страницы, форматом изображения и качеством. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Сохраняет изображение в файл с заданным форматом изображения и качеством. |
| [GetNextImage](./getnextimage/)(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Сохраняет изображение в файл с заданным размером страницы, форматом изображения и качеством. |
| [HasNextImage](./hasnextimage/)() | Указывает, содержит ли PDF‑файл дополнительные изображения или нет. |
| static [MergeImages](./mergeimages/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::IO::Stream\>\>\>\&, Aspose::Pdf::Drawing::ImageFormat, ImageMergeMode, System::Nullable\<int32_t\>, System::Nullable\<int32_t\>) | Объединяет список потоков изображений в один поток изображения. Поддерживаются форматы вывода Png/jpg/tiff; при использовании неподдерживаемого формата поток вывода по умолчанию кодируется как JPEG. |
| static [MergeImagesAsTiff](./mergeimagesastiff/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::IO::Stream\>\>\>\&) | Объединяет список потоков TIFF в один поток TIFF с несколькими кадрами. |
| [PdfConverter](./pdfconverter/)() | Инициализирует новый объект [PdfConverter](./). |
| [PdfConverter](./pdfconverter/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Инициализирует новый объект [PdfConverter](./) на основе *document*. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, Devices::CompressionType) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, int32_t, int32_t) | Преобразует каждую страницу PDF‑документа в изображения с размерами и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, const System::SharedPtr\<PageSize\>\&) | Преобразует каждую страницу PDF‑документа в изображения с размером страницы и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Devices::TiffSettings\>\&) | Преобразует каждую страницу PDF‑документа в изображения с размером страницы и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, int32_t, int32_t, Devices::CompressionType) | Преобразует каждую страницу PDF‑документа в изображения с размерами и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, int32_t, int32_t, const System::SharedPtr\<Devices::TiffSettings\>\&) | Преобразует каждую страницу PDF‑документа в изображения с размерами и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, int32_t, int32_t, const System::SharedPtr\<Devices::TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Преобразует каждую страницу PDF‑документа в изображения с размерами и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, Devices::CompressionType) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) | Преобразует каждую страницу PDF‑документа в изображения с размером страницы и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Devices::TiffSettings\>\&) | Преобразует каждую страницу PDF‑документа в изображения с размером страницы и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t) | Преобразует каждую страницу PDF‑документа в изображения с размерами и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, Devices::CompressionType) | Преобразует каждую страницу PDF‑документа в изображения с размерами и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<Devices::TiffSettings\>\&) | Преобразует каждую страницу PDF‑документа в изображения с размерами и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<Devices::TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Преобразует каждую страницу PDF‑документа в изображения с размерами и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, const System::SharedPtr\<Devices::TiffSettings\>\&) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::String\&, const System::SharedPtr\<Devices::TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Devices::TiffSettings\>\&) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](./saveastiff/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Devices::TiffSettings\>\&, const System::SharedPtr\<IIndexBitmapConverter\>\&) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один поток TIFF. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::String\&, int32_t, int32_t) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один файл TIFF ClassF. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::String\&, const System::SharedPtr\<PageSize\>\&) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один файл TIFF ClassF. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один поток TIFF ClassF. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<PageSize\>\&) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один поток TIFF ClassF. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::String\&) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один файл TIFF ClassF. |
| [SaveAsTIFFClassF](./saveastiffclassf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Преобразует каждую страницу PDF‑документа в изображения и сохраняет их в один поток TIFF ClassF. |
| [set_CoordinateType](./set_coordinatetype/)(PageCoordinateType) | Устанавливает тип координат страницы (Media/Crop‑коробки). Значение CropBox используется по умолчанию. |
| [set_EndPage](./set_endpage/)(int32_t) | Устанавливает конечную позицию, которую вы хотите конвертировать. |
| [set_FormPresentationMode](./set_formpresentationmode/)(Aspose::Pdf::Devices::FormPresentationMode) | Устанавливает режим отображения формы. |
| [set_Password](./set_password/)(const System::String\&) | Устанавливает пароль владельца документа. |
| [set_RenderingOptions](./set_renderingoptions/)(const System::SharedPtr\<Aspose::Pdf::RenderingOptions\>\&) | Устанавливает параметры рендеринга. |
| [set_Resolution](./set_resolution/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Устанавливает разрешение при конвертации. Чем выше разрешение, тем медленнее скорость конвертации. Значение по умолчанию — 150. |
| [set_ShowHiddenAreas](./set_showhiddenareas/)(bool) | Устанавливает флаг, контролирующий видимость скрытых областей на странице. |
| [set_StartPage](./set_startpage/)(int32_t) | Устанавливает начальную позицию, которую вы хотите конвертировать. Минимальное значение — 1. |
| [set_UserPassword](./set_userpassword/)(const System::String\&) | Устанавливает пароль пользователя документа. |
## См. также

* Class [Facade](../facade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
