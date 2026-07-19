---
title: "Aspose::Pdf::LowCode::PdfAConverter::Process метод"
linktitle: "Process"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LowCode::PdfAConverter::Process метод. Начинает процесс конвертации или проверки PDF/A с заданными параметрами в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.lowcode/pdfaconverter/process/
---
## PdfAConverter::Process method


Запускает процесс конвертации или проверки PDF/A с заданными параметрами.

```cpp
System::SharedPtr<ResultContainer> Aspose::Pdf::LowCode::PdfAConverter::Process(System::SharedPtr<IPluginOptions> options) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| options | System::SharedPtr\<IPluginOptions\> | Объект параметров, содержащий инструкции для плагина. Должен быть экземпляром класса [PdfAConvertOptions](../../pdfaconvertoptions/) или класса [PdfAValidateOptions](../../pdfavalidateoptions/). |

### ReturnValue

Объект [ResultContainer](../../resultcontainer/), содержащий результат обработки.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ResultContainer](../../resultcontainer/)
* Class [IPluginOptions](../../ipluginoptions/)
* Class [PdfAConverter](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
