---
title: "Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks метод"
linktitle: "AddPrinterMarks"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks метод. Добавляет метки принтера к указанной странице в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## PrinterMarkAnnotation::AddPrinterMarks(const System::SharedPtr\<Aspose::Pdf::Page\>\&, PrinterMarksKind) method


Добавляет метки принтера на указанную страницу.

```cpp
static void Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks(const System::SharedPtr<Aspose::Pdf::Page> &page, PrinterMarksKind marksKind)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | const System::SharedPtr\<Aspose::Pdf::Page\>\& | Страница, к которой будут добавлены метки принтера. |
| marksKind | PrinterMarksKind | Тип меток принтера, которые нужно добавить. |
## Примечания



Этот метод добавляет различные типы меток принтера на основе предоставленных флагов [PrinterMarksKind](../../printermarkskind/). Если указан [PrinterMarksKind::None](../../printermarkskind/), метки не добавляются.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Enum [PrinterMarksKind](../../printermarkskind/)
* Class [PrinterMarkAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## PrinterMarkAnnotation::AddPrinterMarks(const System::SharedPtr\<Document\>\&, PrinterMarksKind) method


Добавляет метки принтера на все страницы указанного документа.

```cpp
static void Aspose::Pdf::Annotations::PrinterMarkAnnotation::AddPrinterMarks(const System::SharedPtr<Document> &document, PrinterMarksKind marksKind)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | const System::SharedPtr\<Document\>\& | Документ, к которому будут добавлены метки принтера. |
| marksKind | PrinterMarksKind | Тип меток принтера, которые нужно добавить. |
## Примечания



Этот метод добавляет различные типы меток принтера на основе предоставленных флагов [PrinterMarksKind](../../printermarkskind/). Если указан [PrinterMarksKind::None](../../printermarkskind/), метки не добавляются.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Enum [PrinterMarksKind](../../printermarkskind/)
* Class [PrinterMarkAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
