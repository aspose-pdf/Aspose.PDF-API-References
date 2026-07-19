---
title: "Aspose::Pdf::Comparison::GraphicalPdfComparer класс"
linktitle: "GraphicalPdfComparer"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Comparison::GraphicalPdfComparer. Представляет класс для графического сравнения PDF‑документов. Должен использоваться для поиска небольших изменений, в основном графического характера. Чтобы сравнить изменения текстового содержимого, используйте другие классы сравнения PDF на C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer class


Представляет класс для графического сравнения PDF‑документов. Должен использоваться для поиска небольших изменений, в основном графических. Для сравнения изменений текстового содержимого используйте другие классы сравнения PDF.

```cpp
class GraphicalPdfComparer : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [CompareDocumentsToImages](./comparedocumentstoimages/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::String\&, const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Сравнивает документы графически. Результат сравнения помещается в изображения. |
| [CompareDocumentsToPdf](./comparedocumentstopdf/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::String\&) | Сравнивает документы графически. Результат сравнения помещается в PDF‑документ. |
| [ComparePagesToImage](./comparepagestoimage/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::String\&) | Сравнивает страницы графически. Результат сравнения помещается в изображение. |
| [ComparePagesToPdf](./comparepagestopdf/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::String\&) | Сравнивает страницы графически. Результат сравнения помещается в PDF‑документ. |
| [ComparePagesToPdf](./comparepagestopdf/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Document\>\&) | Сравнивает страницы графически. Результат сравнения помещается в PDF‑документ. |
| [get_Color](./get_color/)() const | Получает и задает цвет флага изменения. Цвет по умолчанию — красный. |
| [get_Resolution](./get_resolution/)() const | Получает и задает разрешение получаемых изображений. Значение по умолчанию — 150 dpi. |
| [get_Threshold](./get_threshold/)() const | Получает и задает пороговое значение в процентах. Это значение позволяет игнорировать небольшие изменения, если они для вас незначительны. Значение по умолчанию — 0 %. |
| [GetDifference](./getdifference/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&) | Получает различия между изображениями страниц. Результат содержит изображение первой сравниваемой страницы и массив различий. |
| [GraphicalPdfComparer](./graphicalpdfcomparer/)() | Создаёт экземпляр класса [GraphicalPdfComparer](./). |
| [set_Color](./set_color/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Получает и задает цвет флага изменения. Цвет по умолчанию — красный. |
| [set_Resolution](./set_resolution/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Получает и задает разрешение получаемых изображений. Значение по умолчанию — 150 dpi. |
| [set_Threshold](./set_threshold/)(double) | Получает и задает пороговое значение в процентах. Это значение позволяет игнорировать небольшие изменения, если они для вас незначительны. Значение по умолчанию — 0 %. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
