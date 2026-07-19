---
title: "Aspose::Pdf::Annotations::SubmitFormAction class"
linktitle: "SubmitFormAction"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::SubmitFormAction class. Класс, описывающий действие submit-form в C++."
type: docs
weight: 11000
url: /ru/cpp/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction class


Класс, описывающий действие отправки формы.

```cpp
class SubmitFormAction : public Aspose::Pdf::Annotations::PdfAction
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Flags](./get_flags/)() | Получает флаги действия submit. |
| [get_Url](./get_url/)() | URL назначения. |
| [set_Flags](./set_flags/)(int32_t) | Устанавливает флаги действия submit. |
| [set_Url](./set_url/)(const System::SharedPtr\<FileSpecification\>\&) | URL назначения. |
| [SubmitFormAction](./submitformaction/)() | Инициализирует объект [SubmitFormAction](./). |
## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [CanonicalFormat](./canonicalformat/) | Если установлено, любые отправленные значения полей, представляющие даты, будут преобразованы в стандартный формат. |
| static constexpr [EmbedForm](./embedform/) | Если установлено, запись F в отправленном FDF должна быть спецификацией файла, содержащей встроенный поток файла, представляющий PDF-файл, из которого отправляется FDF. |
| static constexpr [ExclFKey](./exclfkey/) | Если установлено, отправленный FDF должен исключать запись F. |
| static constexpr [ExclNonUserAnnots](./exclnonuserannots/) | Если установлено, он должен включать только те аннотации разметки, у которых запись T совпадает с именем текущего пользователя. |
| static constexpr [Exclude](./exclude/) | Если не установлено, массив Fields указывает, какие поля включать в отправку. |
| static constexpr [ExportFormat](./exportformat/) | Если установлено, имена полей и их значения будут отправлены в формате HTML-формы. |
| static constexpr [GetMethod](./getmethod/) | Если установлено, имена полей и их значения будут отправлены с помощью HTTP GET запроса. |
| static constexpr [IncludeAnnotations](./includeannotations/) | Если установлено, отправленный файл FDF должен включать все аннотации разметки в базовом PDF-документе. |
| static constexpr [IncludeAppendSaves](./includeappendsaves/) | Если установлено, отправленный файл FDF должен включать содержимое всех инкрементных обновлений. |
| static constexpr [IncludeNoValueFields](./includenovaluefields/) | Если установлено, все поля, указанные в массиве Fields и флагом Include/Exclude, будут отправлены. |
| static constexpr [SubmitCoordinates](./submitcoordinates/) | Если установлено, координаты щелчка мыши, вызвавшего действие submit-form, будут переданы как часть данных формы. |
| static constexpr [SubmitPdf](./submitpdf/) | Если установлено, документ будет отправлен в виде PDF, используя MIME‑тип application/pdf. |
| static constexpr [Xfdf](./xfdf/) | Если установлено, имена полей и их значения будут отправлены как XFDF. |
## См. также

* Class [PdfAction](../pdfaction/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
