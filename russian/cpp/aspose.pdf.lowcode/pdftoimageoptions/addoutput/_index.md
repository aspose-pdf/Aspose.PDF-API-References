---
title: "Aspose::Pdf::LowCode::PdfToImageOptions::AddOutput метод"
linktitle: "AddOutput"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LowCode::PdfToImageOptions::AddOutput метод. Устанавливает новый источник сохранения данных. Может быть только FileDataSource. Если вы хотите сохранять изображения в поток памяти, передайте null в качестве параметра в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.lowcode/pdftoimageoptions/addoutput/
---
## PdfToImageOptions::AddOutput method


Устанавливает новый источник сохранения данных. Может быть только
[FileDataSource](../../filedatasource/)


. Если вы хотите сохранять изображения в поток памяти, передайте null в качестве параметра.

```cpp
void Aspose::Pdf::LowCode::PdfToImageOptions::AddOutput(System::SharedPtr<IDataSource> saveDataSource) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| saveDataSource | System::SharedPtr\<IDataSource\> | Источник данных для сохранения. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDataSource](../../idatasource/)
* Class [PdfToImageOptions](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
