---
title: "класс Aspose::Pdf::Forms::Field"
linktitle: "Поле"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Forms::Field. Базовый класс для полей AcroForm в C++."
type: docs
weight: 900
url: /ru/cpp/aspose.pdf.forms/field/
---
## Field class


Базовый класс для полей AcroForm.

```cpp
class Field : public Aspose::Pdf::Annotations::WidgetAnnotation,
              public System::Collections::Generic::ICollection<System::SharedPtr<Annotations::WidgetAnnotation>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [CopyTo](./copyto/)(const System::ArrayPtr\<System::SharedPtr\<Field\>\>\&, int32_t) | Копирует подполя этого поля в массив, начиная с указанного индекса. |
| [CopyToWidgetArray](./copytowidgetarray/)(const System::ArrayPtr\<System::SharedPtr\<Annotations::WidgetAnnotation\>\>\&, int32_t) | Копирует подполя этого поля в массив, начиная с указанного индекса. |
| [ExecuteFieldJavaScript](./executefieldjavascript/)(const System::SharedPtr\<Annotations::JavascriptAction\>\&) | Выполняет указанное действие JavaScript для поля. |
| [Field](./field/)(const System::SharedPtr\<Document\>\&) | Создаёт поле для использования в Generator. |
| [Flatten](./flatten/)() override | Удаляет это поле и размещает его значение непосредственно на странице. |
| [get_AlternateName](./get_alternatename/)() | Получает альтернативное имя поля (альтернативное имя поля, которое должно использоваться вместо фактического имени поля везде, где поле идентифицируется в пользовательском интерфейсе). Альтернативное имя используется как всплывающая подсказка поля в Adobe Acrobat. |
| [get_AnnotationIndex](./get_annotationindex/)() | Получает индекс этой аннотации на странице. |
| [get_Count](./get_count/)() const override | Получает количество подполей в этом поле. (Например, количество элементов в поле переключателя). |
| static [get_FitIntoRectangle](./get_fitintorectangle/)() | Если true, размер шрифта будет уменьшен, чтобы вписать текст в указанный прямоугольник. |
| [get_IsGroup](./get_isgroup/)() const | Получает логическое значение, указывающее, является ли это поле нетерминальным, т.е. группой полей. |
| [get_IsSharedField](./get_issharedfield/)() const | Свойство для поддержки Generator. Используется, когда поле добавляется в заголовок или нижний колонтитул. Если true, это поле будет создано один раз, и его внешний вид будет виден на всех страницах документа. Если false, отдельное поле будет создано для каждой страницы документа. |
| [get_IsSynchronized](./get_issynchronized/)() | Возвращает true, если словарь синхронизирован. |
| [get_MappingName](./get_mappingname/)() | Получает имя сопоставления поля, которое будет использоваться при экспорте данных интерактивных полей формы из документа. |
| static [get_MaxFontSize](./get_maxfontsize/)() | Максимальный размер шрифта, который может использоваться для содержимого поля. -1 — не проверять размер. |
| static [get_MinFontSize](./get_minfontsize/)() | Минимальный размер шрифта, который может использоваться для содержимого поля. -1 — не проверять размер. |
| [get_PageIndex](./get_pageindex/)() override | Получает индекс страницы, содержащей это поле. |
| [get_PartialName](./get_partialname/)() | Получает частичное имя поля. |
| [get_Rect](./get_rect/)() override | Получает прямоугольник поля. |
| [get_SyncRoot](./get_syncroot/)() const | Объект синхронизации. |
| [get_TabOrder](./get_taborder/)() | Получает порядок табуляции поля. |
| virtual [get_Value](./get_value/)() | Получает значение поля. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель содержащихся полей. |
| [idx_get](./idx_get/)(const System::String\&) | Получает подполе, содержащееся в этом поле, по имени подполя. |
| [idx_get](./idx_get/)(int32_t) | Получает подполе, содержащееся в этом поле, по индексу. |
| [Recalculate](./recalculate/)() | Пересчитывает все вычисляемые поля в форме. |
| [set_AlternateName](./set_alternatename/)(const System::String\&) | Устанавливает альтернативное имя поля (альтернативное имя поля, которое будет использоваться вместо фактического имени поля везде, где поле должно быть идентифицировано в пользовательском интерфейсе). Альтернативное имя используется как всплывающая подсказка поля в Adobe Acrobat. |
| [set_AnnotationIndex](./set_annotationindex/)(int32_t) | Устанавливает индекс этой аннотации на странице. |
| static [set_FitIntoRectangle](./set_fitintorectangle/)(bool) | Если true, размер шрифта будет уменьшен, чтобы вписать текст в указанный прямоугольник. |
| [set_IsSharedField](./set_issharedfield/)(bool) | Свойство для поддержки Generator. Используется, когда поле добавляется в заголовок или нижний колонтитул. Если true, это поле будет создано один раз, и его внешний вид будет виден на всех страницах документа. Если false, отдельное поле будет создано для каждой страницы документа. |
| [set_MappingName](./set_mappingname/)(const System::String\&) | Устанавливает имя отображения поля, которое будет использоваться при экспорте данных интерактивных полей формы из документа. |
| static [set_MaxFontSize](./set_maxfontsize/)(double) | Максимальный размер шрифта, который может использоваться для содержимого поля. -1 — не проверять размер. |
| static [set_MinFontSize](./set_minfontsize/)(double) | Минимальный размер шрифта, который может использоваться для содержимого поля. -1 — не проверять размер. |
| [set_PartialName](./set_partialname/)(const System::String\&) | Устанавливает частичное имя поля. |
| [set_Rect](./set_rect/)(System::SharedPtr\<Rectangle\>) override | Устанавливает прямоугольник поля. |
| [set_TabOrder](./set_taborder/)(int32_t) | Устанавливает порядок табуляции поля. |
| virtual [set_Value](./set_value/)(System::String) | Устанавливает значение поля. |
| virtual [SetPosition](./setposition/)(System::SharedPtr\<Point\>) | Установить позицию поля. |
## См. также

* Class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
