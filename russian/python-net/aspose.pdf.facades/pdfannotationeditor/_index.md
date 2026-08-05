---
title: "PdfAnnotationEditor"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Представляет класс для работы с аннотациями PDF‑документа (комментариями)."
type: docs
weight: 170
url: /ru/python-net/aspose.pdf.facades/pdfannotationeditor/
---

## PdfAnnotationEditor class

Представляет класс для работы с аннотациями PDF‑документа (комментариями).

Тип PdfAnnotationEditor раскрывает следующие члены:
## Конструкторы
| Имя | Описание |
| :- | :- |
| PdfAnnotationEditor() | Инициализирует новый объект [PdfAnnotationEditor](/pdf/python-net/aspose.pdf.facades/pdfannotationeditor/). |
| PdfAnnotationEditor(document) | Инициализирует новый экземпляр класса PdfAnnotationEditor |
## Свойства
| Имя | Описание |
| :- | :- |
| document | Получает фасад документа, над которым работает. |
## Методы
| Имя | Описание |
| :- | :- |
| bind_pdf(src_file) | Привязывает PDF-документ для редактирования. |
| bind_pdf(src_stream) | Привязывает PDF-документ для редактирования. |
| bind_pdf(src_doc) | Привязывает PDF-документ для редактирования. |
| save(dest_file) | Сохраняет документ PDF в указанный файл. |
| save(dest_stream) | Сохраняет документ PDF в указанный поток. |
| import_annotations_from_xfdf(xfdf_file) | Импортирует все аннотации из файла XFDF. |
| import_annotations_from_xfdf(xfdf_stream) | Импортирует все аннотации из потока данных XFDF. |
| import_annotation_from_xfdf(xfdf_file) | Импортирует все аннотации из файла XFDF. |
| import_annotation_from_xfdf(xfdf_file, annot_type) | Импортирует указанные аннотации из файла XFDF. |
| import_annotation_from_xfdf(xfdf_stream, annot_type) | Импортирует указанные аннотации из потока данных XFDF. |
| import_annotation_from_xfdf(xfdf_stream) | Импортирует указанные аннотации из потока данных XFDF. |
| import_annotations(annot_file, annot_type) | Импортирует указанные аннотации в документ из массива других PDF‑документов. |
| import_annotations(annot_file) | Импортирует указанные аннотации в документ из массива других PDF‑документов. |
| import_annotations(annot_file_stream, annot_type) | Импортирует указанные аннотации в документ из массива потоков другого PDF‑документа. |
| import_annotations(annot_file_stream) | Импортирует указанные аннотации в документ из массива потоков другого PDF‑документа. |
| flattening_annotations() | Уплощает все аннотации в документе. |
| flattening_annotations(flatten_settings) | Уплощает все аннотации в документе. |
| flattening_annotations(start, end, annot_type) | Уплощает аннотации указанных типов. |
| delete_annotations() | Удаляет все аннотации в документе. |
| delete_annotations(annot_type) | Удаляет все аннотации указанного типа в документе. |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Экспортирует содержимое указанных типов аннотаций в XFDF. |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Экспортирует содержимое указанных типов аннотаций в XFDF. |
| extract_annotations(start, end, annot_types) | Получает список аннотаций указанных типов. |
| extract_annotations(start, end, annot_types) | Получает список аннотаций указанных типов. |
| close() | Освобождает любые ресурсы, связанные с текущим фасадом. |
| modify_annotations_author(start, end, src_author, des_author) | Изменяет автора аннотаций в указанном диапазоне страниц. |
| delete_annotation(annot_name) | Удаляет все аннотации указанного типа в документе. |
| export_annotations_to_xfdf(xml_output_stream) | Экспортирует аннотации в поток. |
| modify_annotations(start, end, annotation) | Изменяет аннотации указанного типа в заданном диапазоне страниц.<br/>            Поддерживает изменение следующих свойств аннотации: Modified, Title, Contents, Color, Subject и Open. |
| redact_area(page_index, rect, color) | Редактирует область на указанной странице. Всё содержимое удаляется. |

### См. также

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

