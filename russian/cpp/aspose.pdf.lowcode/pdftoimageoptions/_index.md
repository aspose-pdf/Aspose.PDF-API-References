---
title: "Класс Aspose::Pdf::LowCode::PdfToImageOptions"
linktitle: "PdfToImageOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::LowCode::PdfToImageOptions. Представляет параметры для плагина PdfToImage в C++."
type: docs
weight: 6500
url: /ru/cpp/aspose.pdf.lowcode/pdftoimageoptions/
---
## PdfToImageOptions class


Представляет параметры для плагина [PdfToImage](../pdftoimage/).

```cpp
class PdfToImageOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                          public Aspose::Pdf::LowCode::IDataContainer,
                          public Aspose::Pdf::LowCode::ISaveInstruction
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [ImageConversionMode](./imageconversionmode/) | Определяет различные режимы, которые могут использоваться при конвертации PDF‑документа в изображение [Jpeg](../jpeg/). См. класс [JpegOptions](../jpegoptions/). |
## Методы

| Метод | Описание |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Добавляет новый источник данных в коллекцию данных плагина [PdfToImage](../pdftoimage/). |
|  | [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Устанавливает новый источник сохранения данных. Может быть только |
[FileDataSource](../filedatasource/)


. Если вы хотите сохранять изображения в потоки памяти, передайте null в качестве параметра. |
| [get_ConversionMode](./get_conversionmode/)() | Получает режим конвертации изображения. |
| [get_Inputs](./get_inputs/)() override | Возвращает коллекцию данных плагина [PdfToImage](../pdftoimage/). |
| virtual [get_OperationName](./get_operationname/)() | Возвращает имя операции. |
| [get_OutputResolution](./get_outputresolution/)() const | Получает значение разрешения полученных изображений. |
| [get_Outputs](./get_outputs/)() override | Получает коллекцию добавленных целей (файловых или потоковых источников данных) для сохранения результатов операции. |
| [get_PageList](./get_pagelist/)() const | Получает список страниц для процесса. |
| [set_OutputResolution](./set_outputresolution/)(int32_t) | Устанавливает значение разрешения полученных изображений. |
| [set_PageList](./set_pagelist/)(const System::SharedPtr\<System::Collections::Generic::List\<int32_t\>\>\&) | Устанавливает список страниц для процесса. |
## Примечания


Класс PdfImageOptions содержит базовые функции для добавления данных (файлов, потоков), представляющих входные PDF‑документы.
## См. также

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
