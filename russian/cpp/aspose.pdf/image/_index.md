---
title: "Класс Aspose::Pdf::Image"
linktitle: "Image"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Image. Представляет изображение в C++."
type: docs
weight: 7900
url: /ru/cpp/aspose.pdf/image/
---
## Image class


Представляет изображение.

```cpp
class Image : public Aspose::Pdf::BaseParagraph
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Клонировать изображение. |
| [get_BitmapInfo](./get_bitmapinfo/)() const | Получает несжатые байты изображения. |
| [get_BitmapSize](./get_bitmapsize/)() | Получает размер битовой карты изображения. |
| [get_File](./get_file/)() const | Получает файл изображения. |
| [get_FileType](./get_filetype/)() const | Получает тип файла изображения. |
| [get_FixHeight](./get_fixheight/)() const | Получает высоту изображения. |
| [get_FixWidth](./get_fixwidth/)() const | Получает ширину изображения. |
| [get_ImageScale](./get_imagescale/)() const | Получает масштаб изображения. |
| [get_ImageStream](./get_imagestream/)() const | Получает поток изображения. |
| [get_IsApplyResolution](./get_isapplyresolution/)() const | Получает логическое значение, указывающее, использует ли изображение разрешение при генерации. |
| [get_IsBlackWhite](./get_isblackwhite/)() const | Получает логическое значение, указывающее, принудительно ли изображение должно быть черно-белым. Если используется TIFF‑изображение субформата CCITT, это свойство должно быть установлено в true. |
| [get_Title](./get_title/)() const | Получает строковое значение, указывающее заголовок изображения. |
| static [GetMimeType](./getmimetype/)(const System::SharedPtr\<System::Drawing::Image\>\&) | Возвращает MIME‑тип изображения. |
| [Image](./image/)() |  |
| [set_BitmapInfo](./set_bitmapinfo/)(const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\&) | Устанавливает несжатые байты изображения. |
| [set_File](./set_file/)(const System::String\&) | Устанавливает файл изображения. |
| [set_FileType](./set_filetype/)(ImageFileType) | Устанавливает тип файла изображения. |
| [set_FixHeight](./set_fixheight/)(double) | Устанавливает высоту изображения. |
| [set_FixWidth](./set_fixwidth/)(double) | Устанавливает ширину изображения. |
| [set_ImageScale](./set_imagescale/)(double) | Устанавливает масштаб изображения. |
| [set_ImageStream](./set_imagestream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает поток изображения. |
| [set_IsApplyResolution](./set_isapplyresolution/)(bool) | Устанавливает логическое значение, указывающее, использует ли изображение разрешение при генерации. |
| [set_IsBlackWhite](./set_isblackwhite/)(bool) | Устанавливает логическое значение, указывающее, принудительно ли изображение должно быть черно-белым. Если используется TIFF‑изображение субформата CCITT, это свойство должно быть установлено в true. |
| [set_Title](./set_title/)(const System::SharedPtr\<Text::TextFragment\>\&) | Устанавливает строковое значение, указывающее заголовок изображения. |
## См. также

* Class [BaseParagraph](../baseparagraph/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
