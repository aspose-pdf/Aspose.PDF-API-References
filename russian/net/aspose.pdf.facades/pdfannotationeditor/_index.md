---
title: "Класс PdfAnnotationEditor"
second_title: "Справочник API Aspose.PDF для .NET"
description: "класс Aspose.Pdf.Facades.PdfAnnotationEditor. Представляет класс для работы с комментариями аннотаций PDF‑документа."
type: docs
weight: 4530
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

Представляет класс для работы с аннотациями PDF Document (комментариями).

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor)() | Инициализирует новый объект `PdfAnnotationEditor`. |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor_1)(Document) | Инициализирует новый объект `PdfAnnotationEditor` на основе *document*. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает document, с которым работает фасад. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Инициализирует фасад. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Освобождает Aspose.Pdf.Document, связанный с фасадом. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | Удаляет аннотацию с указанным именем аннотации. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | Удаляет все аннотации в документе. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | Удаляет все аннотации указанного типа в документе. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | Экспортирует аннотации в поток. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Экспортирует содержимое указанных типов аннотаций в XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | Экспортирует содержимое указанных типов аннотаций в XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | Получает список аннотаций указанных типов. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | Получает список аннотаций указанных типов. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | Уплощает все аннотации в документе. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | Уплощает все аннотации в документе. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | Уплощает аннотации указанных типов. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Импортирует указанные аннотации из потока данных XFDF. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | Импортирует указанные аннотации из файла XFDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | Импортирует аннотации в документ из массива потоков других PDF‑документов. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | Импортирует аннотации в документ из массива других PDF‑документов. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | Импортирует указанные аннотации в документ из массива потоков других PDF‑документов. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | Импортирует указанные аннотации в документ из массива других PDF‑документов. |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | Импортирует все аннотации из файла FDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Импортирует все аннотации из потока данных XFDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Импортирует все аннотации из файла XFDF. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | Изменяет аннотации указанного типа в указанном диапазоне страниц. Поддерживает изменение следующих свойств аннотации: Modified, Title, Contents, Color, Subject и Open. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | Изменяет автора аннотаций в указанном диапазоне страниц. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | Редактирует область на указанной странице. Всё содержимое удаляется. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Сохраняет PDF‑документ в указанный поток. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Сохраняет PDF‑документ в указанный файл. |

### См. также

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


