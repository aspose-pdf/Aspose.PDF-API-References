---
title: PdfAnnotationEditor
second_title: Aspose.PDF для справочника API .NET
description: Представляет собой класс для работы с аннотациями комментариями PDF-документа.
type: docs
weight: 2420
url: /ru/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

Представляет собой класс для работы с аннотациями (комментариями) PDF-документа.

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor#constructor)() | Инициализирует новый объект[`PdfAnnotationEditor`](../pdfannotationeditor). |
| [PdfAnnotationEditor](pdfannotationeditor#constructor_1)(Document) | Инициализирует новый[`PdfAnnotationEditor`](../pdfannotationeditor)объект на основе*document*. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Получает фасад документа, над которым работает. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Инициализирует фасад. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Удаляет Aspose.Pdf.Document, связанный с фасадом. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation)(string) | Удаляет аннотацию с указанным именем аннотации. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations)() | Удаляет все аннотации в документе. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations_1)(string) | Удаляет все аннотации указанного типа в документе. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Удаляет фасад. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf)(Stream) | Экспорт аннотаций в поток. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Экспортирует содержимое указанных типов аннотаций в XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf_1)(Stream, int, int, string[]) | Экспортирует содержимое указанных типов аннотаций в XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations)(int, int, AnnotationType[]) | Получает список аннотаций указанных типов. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations_1)(int, int, string[]) | Получает список аннотаций указанных типов. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations)() | Сглаживает все аннотации в документе. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_1)(FlattenSettings) | Сглаживает все аннотации в документе. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_2)(int, int, AnnotationType[]) | Сглаживает аннотации указанных типов. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Импортирует указанные аннотации из потока данных XFDF. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_3)(string, AnnotationType[]) | Импортирует указанные аннотации из файла XFDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations)(Stream[]) | Импорт аннотаций в документ из массива других потоков документов PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_2)(string[]) | Импортирует аннотации в документ из массива других PDF-документов. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_1)(Stream[], AnnotationType[]) | Импортирует указанные аннотации в документ из массива других потоков документов PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_3)(string[], AnnotationType[]) | Импортирует указанные аннотации в документ из массива других документов PDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | Импорт всех аннотаций из потока данных XFDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | Импорт всех аннотаций из файла XFDF. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations#modifyannotations)(int, int, Annotation) | Изменяет аннотации указанного типа в указанном диапазоне страниц. Он поддерживает изменение следующих свойств аннотации:Изменено, Название, Содержание, Цвет, Тема и Открыть. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor)(int, int, string, string) | Изменяет автора аннотаций в указанном диапазоне страниц. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea)(int, Rectangle, Color) | Редактирует область на указанной странице. Все содержимое удалено. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Сохраняет документ PDF в указанный поток. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Сохраняет документ PDF в указанный файл. |

### Смотрите также

* class [SaveableFacade](../saveablefacade)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
