---
title: "Класс Aspose::Pdf::PdfPageStamp"
linktitle: "PdfPageStamp"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::PdfPageStamp. Класс представляет штамп, использующий страницу PDF в качестве штампа в C++."
type: docs
weight: 15100
url: /ru/cpp/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp class


Класс представляет штамп, который использует страницу PDF в качестве штампа.

```cpp
class PdfPageStamp : public Aspose::Pdf::Stamp
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_PdfPage](./get_pdfpage/)() const | Возвращает страницу, которая будет использоваться в качестве штампа. |
| [PdfPageStamp](./pdfpagestamp/)(const System::SharedPtr\<Page\>\&) | Конструктор [PdfPageStamp](./). |
| [PdfPageStamp](./pdfpagestamp/)(const System::String\&, int32_t) | Создаёт штамп страницы [Pdf](../) из указанной страницы документа в заданном файле. |
| [PdfPageStamp](./pdfpagestamp/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) | Создаёт штамп страницы [Pdf](../) из указанной страницы документа из потока. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Поместите штамп на указанную страницу. |
| [set_PdfPage](./set_pdfpage/)(const System::SharedPtr\<Page\>\&) | Устанавливает страницу, которая будет использоваться в качестве штампа. |
## См. также

* Class [Stamp](../stamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
