---
title: "Класс Aspose::Pdf::PdfANonSpecificationFlags"
linktitle: "PdfANonSpecificationFlags"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::PdfANonSpecificationFlags. Этот класс содержит флаги для управления конвертацией PDF/A в случаях, когда исходный PDF‑документ не соответствует спецификации PDF. Если использовать флаги этого класса, производительность снижается, но это необходимо, когда исходный PDF‑документ нельзя преобразовать в формат PDF/A обычным способом. По умолчанию все флаги установлены в false в C++."
type: docs
weight: 14800
url: /ru/cpp/aspose.pdf/pdfanonspecificationflags/
---
## PdfANonSpecificationFlags class


Этот класс содержит флаги для управления конвертацией PDF/A в случаях, когда исходный PDF‑документ не соответствует спецификации PDF. Если использовать флаги этого класса, производительность снижается, но это необходимо, когда исходный PDF‑документ нельзя преобразовать в формат PDF/A обычным способом. По умолчанию все флаги установлены в значение false.

```cpp
class PdfANonSpecificationFlags : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_CheckDifferentNamesInFontDictionaries](./get_checkdifferentnamesinfontdictionaries/)() const | Некоторые PDF‑документы содержат шрифты, у которых в внутренних данных разные имена. Использование этого флага заставляет применять специальную логику обработки в случаях, когда поля BaseFont и FontDescriptor.FontName различаются. |
| [PdfANonSpecificationFlags](./pdfanonspecificationflags/)() | Конструктор. |
| [set_CheckDifferentNamesInFontDictionaries](./set_checkdifferentnamesinfontdictionaries/)(bool) | Некоторые PDF‑документы содержат шрифты, у которых в внутренних данных разные имена. Использование этого флага заставляет применять специальную логику обработки в случаях, когда поля BaseFont и FontDescriptor.FontName различаются. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
