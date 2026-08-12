---
title: "Aspose::Pdf::Annotations::PageInformationAnnotation class"
linktitle: "PageInformationAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::PageInformationAnnotation class. Представляет аннотацию информации о странице в PDF‑документе. Эта аннотация содержит имя файла, номер страницы и дату и время создания аннотации в C++."
type: docs
weight: 7000
url: /ru/cpp/aspose.pdf.annotations/pageinformationannotation/
---
## PageInformationAnnotation class


Представляет аннотацию информации о [Page](../../aspose.pdf/page/) в PDF‑документе. Эта аннотация содержит имя файла, номер страницы и дату и время создания аннотации.

```cpp
class PageInformationAnnotation : public Aspose::Pdf::Annotations::PrinterMarkAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает посетитель для обработки аннотации. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [PageInformationAnnotation](./pageinformationannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Инициализирует новый экземпляр класса [PageInformationAnnotation](./) на указанной странице в заданном месте. |
## Примечания


Этот класс в основном используется для добавления метаданных к конкретной странице PDF‑документа, что может быть полезно для отслеживания и ссылок. Например, его можно использовать для пометки страниц во время процесса печати или для предоставления дополнительной информации о странице при просмотре документа.
## См. также

* Class [PrinterMarkAnnotation](../printermarkannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
