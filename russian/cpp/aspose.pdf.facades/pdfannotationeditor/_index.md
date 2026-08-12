---
title: "Класс Aspose::Pdf::Facades::PdfAnnotationEditor"
linktitle: "PdfAnnotationEditor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Facades::PdfAnnotationEditor. Представляет класс для работы с аннотациями (комментариями) PDF‑документов в C++."
type: docs
weight: 1500
url: /ru/cpp/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class


Представляет класс для работы с аннотациями PDF‑документа (комментариями).

```cpp
class PdfAnnotationEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Методы

| Метод | Описание |
| --- | --- |
| [DeleteAnnotation](./deleteannotation/)(const System::String\&) | Удаляет аннотацию с указанным именем аннотации. |
| [DeleteAnnotations](./deleteannotations/)() | Удаляет все аннотации в документе. |
| [DeleteAnnotations](./deleteannotations/)(const System::String\&) | Удаляет все аннотации указанного типа в документе. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Экспортирует аннотации в поток. |
| [ExportAnnotationsXfdf](./exportannotationsxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::ArrayPtr\<System::String\>\&) | Экспортирует содержимое указанных типов аннотаций в XFDF. |
| [ExportAnnotationsXfdf](./exportannotationsxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Экспортирует содержимое указанных типов аннотаций в XFDF. |
| [ExtractAnnotations](./extractannotations/)(int32_t, int32_t, const System::ArrayPtr\<System::String\>\&) | Получает список аннотаций указанных типов. |
| [ExtractAnnotations](./extractannotations/)(int32_t, int32_t, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Получает список аннотаций указанных типов. |
| [FlatteningAnnotations](./flatteningannotations/)() | Преобразует все аннотации в документе в плоские. |
| [FlatteningAnnotations](./flatteningannotations/)(const System::SharedPtr\<Forms::Form::FlattenSettings\>\&) | Преобразует все аннотации в документе в плоские. |
| [FlatteningAnnotations](./flatteningannotations/)(int32_t, int32_t, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Уплощает аннотации указанных типов. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(const System::String\&) | Импортирует все аннотации из файла XFDF. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(const System::String\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Импортирует указанные аннотации из файла XFDF. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Импортирует указанные аннотации из потока данных XFDF. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Импортирует все аннотации из потока данных XFDF. |
| [ImportAnnotations](./importannotations/)(const System::ArrayPtr\<System::String\>\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Импортирует указанные аннотации в документ из массива других PDF‑документов. |
| [ImportAnnotations](./importannotations/)(const System::ArrayPtr\<System::String\>\&) | Импортирует аннотации в документ из массива других PDF‑документов. |
| [ImportAnnotations](./importannotations/)(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Импортирует указанные аннотации в документ из массива потоков других PDF‑документов. |
| [ImportAnnotations](./importannotations/)(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&) | Импортирует аннотации в документ из массива потоков других PDF‑документов. |
| [ImportAnnotationsFromFdf](./importannotationsfromfdf/)(const System::String\&) | Импортирует все аннотации из файла FDF. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(const System::String\&) | Импортирует все аннотации из файла XFDF. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Импортирует все аннотации из потока данных XFDF. |
| [ModifyAnnotations](./modifyannotations/)(int32_t, int32_t, const System::SharedPtr\<Annotations::Annotation\>\&) | Изменяет аннотации указанного типа в заданном диапазоне страниц. Поддерживает изменение следующих свойств аннотации: Modified, Title, Contents, [Color](../../aspose.pdf/color/), Subject и Open. |
| [ModifyAnnotationsAuthor](./modifyannotationsauthor/)(int32_t, int32_t, const System::String\&, const System::String\&) | Изменяет автора аннотаций в заданном диапазоне страниц. |
| [PdfAnnotationEditor](./pdfannotationeditor/)() | Инициализирует новый объект [PdfAnnotationEditor](./). |
| [PdfAnnotationEditor](./pdfannotationeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Инициализирует новый объект [PdfAnnotationEditor](./) на основе *document*. |
| [RedactArea](./redactarea/)(int32_t, System::SharedPtr\<Rectangle\>, System::Drawing::Color) | Редактирует область на указанной странице. Всё содержимое удаляется. |
## См. также

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
