---
title: "Класс Aspose::Pdf::Comparison::TextPdfComparer"
linktitle: "TextPdfComparer"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Comparison::TextPdfComparer. Представляет класс для сравнения двух PDF‑страниц или PDF‑документов в C++."
type: docs
weight: 1900
url: /ru/cpp/aspose.pdf.comparison/textpdfcomparer/
---
## TextPdfComparer class


Представляет класс для сравнения двух страниц PDF или PDF‑документов.

```cpp
class TextPdfComparer : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [AssemblyDestinationPageText](./assemblydestinationpagetext/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) | Восстанавливает изменённый текст из списка изменений. |
| static [AssemblySourcePageText](./assemblysourcepagetext/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) | Восстанавливает оригинальный текст из списка изменений. |
| static [CompareDocumentsPageByPage](./comparedocumentspagebypage/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&) | Сравнивает два документа постранично. |
| static [CompareDocumentsPageByPage](./comparedocumentspagebypage/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&, const System::String\&) | Сравнивает два документа постранично. Результат сохраняется в PDF‑файл. |
| static [CompareFlatDocuments](./compareflatdocuments/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&) | Сравнивает два документа постранично. Документы сравниваются целиком. Перед сравнением текста тексты страниц документов объединяются в один текст. |
| static [CompareFlatDocuments](./compareflatdocuments/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<ComparisonOptions\>\&, const System::String\&) | Сравнивает два документа постранично. Результат сохраняется в PDF‑файл. Документы сравниваются целиком. Перед сравнением текста тексты страниц документов объединяются в один текст. |
| static [ComparePages](./comparepages/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::SharedPtr\<ComparisonOptions\>\&) | Сравнивает страницы документов. |
| static [CreateComparisonStatistics](./createcomparisonstatistics/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\&) | Получает статистику сравнения. |
| static [CreateComparisonStatistics](./createcomparisonstatistics/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>\&) | Получает статистику сравнения документов. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
