---
title: "Класс Aspose::Pdf::Page"
linktitle: "Page"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Page. Класс, представляющий страницу PDF‑документа в C++."
type: docs
weight: 13000
url: /ru/cpp/aspose.pdf/page/
---
## Page class


Класс, представляющий страницу PDF‑документа.

```cpp
class Page : public System::IDisposable,
             public Aspose::Pdf::ISupportsMemoryCleanup,
             public Aspose::Pdf::IOperatorContainer
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::Annotations::AnnotationSelector\>\&) | Принимает объект‑посетитель [AnnotationSelector](../), который предоставляет возможности работы с аннотациями. |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::Text::TextFragmentAbsorber\>\&) | Принимает объект‑посетитель **TextFragmentAbsorber**, предоставляющий возможности работы с текстовыми объектами. |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::ImagePlacementAbsorber\>\&) | Принимает объект‑посетитель [ImagePlacementAbsorber](../imageplacementabsorber/), который предоставляет возможности работы с объектами размещения изображений. |
| [Accept](./accept/)(const System::SharedPtr\<Aspose::Pdf::Text::TextAbsorber\>\&) | Принимает объект‑посетитель **TextAbsorber**, предоставляющий возможности работы с текстовыми объектами. |
| [AddGraphics](./addgraphics/)(const System::SharedPtr\<Aspose::Pdf::Vector::GraphicElementCollection\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Добавляет графику на страницу. Работает быстрее, чем добавление элементов по одному с помощью метода [GraphicElement::AddOnPage(Page)](../). |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, bool) | Добавляет изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения. |
| [AddImage](./addimage/)(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Добавляет в страницу поисковое изображение и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<Aspose::Pdf::Rectangle\>, int32_t, int32_t, bool, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Добавляет изображение на страницу и размещает его в зависимости от позиции прямоугольника изображения. |
| [AddImage](./addimage/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Добавляет изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения. |
| [AddStamp](./addstamp/)(const System::SharedPtr\<Aspose::Pdf::Stamp\>\&) | Помещает штамп на страницу. [Stamp](../stamp/) может быть номером страницы, изображением или простым текстом, например логотипом. |
| [AsByteArray](./asbytearray/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Преобразует текущую страницу в bitmap и затем возвращает массив байтов. |
| [AsXml](./asxml/)() | Преобразует текущую страницу в XML в кодировке UTF‑8. |
| [CalculateContentBBox](./calculatecontentbbox/)() | Вычисляет значение bbox — прямоугольник, содержащий содержимое без видимых полей. |
| [ConvertToPNGMemoryStream](./converttopngmemorystream/)() | Конвертировать страницу в PNG для потока изображений DSR, OMR, OCR. |
| [DeleteGraphics](./deletegraphics/)(const System::SharedPtr\<Aspose::Pdf::Vector::GraphicElementCollection\>\&) | Удаляет графику со страницы. Работает быстрее, чем удаление элементов по одному с помощью метода [GraphicElement::Remove](../). |
| [Dispose](./dispose/)() override | Освобождает память. |
| [Flatten](./flatten/)() | Удаляет все поля, расположенные на странице, и вместо них размещает их значения. |
| [FreeMemory](./freememory/)() override | Очищает кэшированные данные. |
| [get_Actions](./get_actions/)() | Получает коллекцию свойств страницы. |
| [get_Annotations](./get_annotations/)() | Получает коллекцию аннотаций страницы. [Annotations](../../aspose.pdf.annotations/) |
| [get_ArtBox](./get_artbox/)() | Получает art‑box страницы. |
| [get_Artifacts](./get_artifacts/)() | Получает коллекцию артефактов на странице. |
| [get_Background](./get_background/)() | Получает цвет фона страницы. |
| [get_BackgroundImage](./get_backgroundimage/)() const | Получает фоновое изображение для страницы (только для генератора, не заполняется при чтении документа). |
| [get_BleedBox](./get_bleedbox/)() | Получает bleed‑box страницы. |
| [get_ColorType](./get_colortype/)() | Устанавливает тип цвета страниц на основе информации, получаемой от операторов SetColor, изображений и форм. |
| [get_Contents](./get_contents/)() override | Получает коллекцию операторов в потоке содержимого страницы. [OperatorCollection](../operatorcollection/) |
| [get_CropBox](./get_cropbox/)() | Получает crop box страницы. |
| [get_Duration](./get_duration/)() | Получает установленную длительность отображения страницы. Это время в секундах, в течение которого страница должна отображаться во время презентации. Возвращает -1, если длительность не определена. |
| [get_FieldsInTabOrder](./get_fieldsintaborder/)() | Получает список объектов Field в порядке табуляции на этой странице. |
| [get_Footer](./get_footer/)() const | Получает нижний колонтитул страницы. |
| [get_Group](./get_group/)() | Получает класс атрибутов группы, определяющий атрибуты группы страниц для использования в модели прозрачного изображения. |
| [get_Header](./get_header/)() const | Получает верхний колонтитул страницы. |
| [get_IsAddParagraphsAfterLast](./get_isaddparagraphsafterlast/)() const | Получает добавление абзацев после последнего абзаца страницы. |
| [get_Layers](./get_layers/)() | Получает коллекцию слоёв. |
| [get_MediaBox](./get_mediabox/)() | Получает media box страницы. |
| [get_NoteLineStyle](./get_notelinestyle/)() | Получает стиль линии для заметок (только для генератора, не заполняется при чтении документа). |
| [get_Number](./get_number/)() | Получает номер страницы. |
| [get_PageInfo](./get_pageinfo/)() | Получает информацию о странице (только для генератора, не заполняется при чтении документа). |
| [get_Paragraphs](./get_paragraphs/)() | Получает абзацы. |
| [get_Rect](./get_rect/)() | Получает прямоугольник страницы. При получении: возвращается crop box страницы, если он указан, иначе возвращается media box страницы. При установке: всегда устанавливается media box страницы. Обратите внимание, что это свойство не учитывает вращение страницы. Чтобы получить прямоугольник страницы с учётом вращения, используйте ActualRect. |
| [get_Resources](./get_resources/)() override | Получает ресурсы страницы. Объект [Resources](../resources/) содержит коллекции изображений, форм и шрифтов. [Resources](../resources/) |
| [get_Rotate](./get_rotate/)() | Получает вращение страницы. |
| [get_RotationMatrix](./get_rotationmatrix/)() | Получает матрицу преобразования для страницы. |
| [get_TabOrder](./get_taborder/)() | Получает порядок табуляции страницы. Возможные значения: [Row](../row/), Column. По умолчанию, Manual. |
| [get_TocInfo](./get_tocinfo/)() const | Получает информацию о содержании (table of contents). |
| [get_TrimBox](./get_trimbox/)() | Получает trim box страницы. |
| [get_UserUnit](./get_userunit/)() | Получает значение UserUnit. Положительное число, задающее размер единиц пользовательского пространства по умолчанию, в кратных 1/72 дюйма. Значение по умолчанию — 1. Установите ноль или отрицательное значение, чтобы очистить эту запись на странице. |
| [get_Watermark](./get_watermark/)() | Получает водяной знак страницы. |
| [GetNotifications](./getnotifications/)() | Возвращает уведомления о внутренних операциях с содержимым страницы. (В настоящее время поддерживаются только уведомления о событиях абзацев в сценариях добавления текста.) |
| [GetPageRect](./getpagerect/)(bool) | Возвращает прямоугольник страницы в соответствии с её CropBox (или MediaBox, если CropBox пуст). |
| [GetResources](./getresources/)() override | Получает ресурсы, связанные со страницей. |
| [HasVectorGraphics](./hasvectorgraphics/)() | Обнаруживает наличие векторной графики, если она присутствует на странице. |
| static [IntToRotation](./inttorotation/)(int32_t) | Преобразует целочисленное значение в соответствующий элемент перечисления вращения. |
| [IsBlank](./isblank/)(double) | Получает флаг, указывающий, является ли страница пустой. |
| [MakeGrayscale](./makegrayscale/)() | Преобразует страницу в градации серого. |
| [MergeLayers](./mergelayers/)(const System::String\&) | Объединяет все слои на странице в один слой с указанным новым именем слоя. |
| [MergeLayers](./mergelayers/)(const System::String\&, const System::String\&) | Объединяет все слои на странице в один слой с указанным новым именем слоя и необязательной группой содержимого [Id](../id/). |
| [Resize](./resize/)(System::SharedPtr\<Aspose::Pdf::PageSize\>) | Изменяет размер страницы. |
| static [RotationToInt](./rotationtoint/)(Aspose::Pdf::Rotation) | Преобразует элемент перечисления вращения в целочисленное значение. |
| [SendTo](./sendto/)(const System::SharedPtr\<Aspose::Pdf::Devices::PageDevice\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Отправляет страницу на обработку с заданным устройством страницы. |
| [SendTo](./sendto/)(const System::SharedPtr\<Aspose::Pdf::Devices::PageDevice\>\&, const System::String\&) | Отправляет страницу на обработку с заданным устройством страницы. |
| [set_ArtBox](./set_artbox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Устанавливает art‑box страницы. |
| [set_Background](./set_background/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Устанавливает цвет фона страницы. |
| [set_BackgroundImage](./set_backgroundimage/)(const System::SharedPtr\<Aspose::Pdf::Image\>\&) | Устанавливает фоновое изображение для страницы (только для генератора, не заполняется при чтении документа). |
| [set_BleedBox](./set_bleedbox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Устанавливает bleed‑box страницы. |
| [set_CropBox](./set_cropbox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Устанавливает crop‑box страницы. |
| [set_Duration](./set_duration/)(double) | Получает установленную длительность отображения страницы. Это время в секундах, в течение которого страница должна отображаться во время презентации. Возвращает -1, если длительность не определена. |
| [set_Footer](./set_footer/)(const System::SharedPtr\<Aspose::Pdf::HeaderFooter\>\&) | Устанавливает нижний колонтитул страницы. |
| [set_Group](./set_group/)(const System::SharedPtr\<Aspose::Pdf::Group\>\&) | Устанавливает класс атрибутов группы, определяющий атрибуты группы страниц для использования в модели прозрачного изображения. |
| [set_Header](./set_header/)(const System::SharedPtr\<Aspose::Pdf::HeaderFooter\>\&) | Устанавливает верхний колонтитул страницы. |
| [set_IsAddParagraphsAfterLast](./set_isaddparagraphsafterlast/)(bool) | Устанавливает добавление абзацев после последнего абзаца страницы. |
| [set_Layers](./set_layers/)(const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<Aspose::Pdf::Layer\>\>\>\&) | Устанавливает коллекцию слоёв. |
| [set_MediaBox](./set_mediabox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Устанавливает media‑box страницы. |
| [set_NoteLineStyle](./set_notelinestyle/)(const System::SharedPtr\<Aspose::Pdf::GraphInfo\>\&) | Устанавливает стиль линии для заметок (только для генератора, не заполняется при чтении документа). |
| [set_PageInfo](./set_pageinfo/)(const System::SharedPtr\<Aspose::Pdf::PageInfo\>\&) | Устанавливает информацию о странице (только для генератора, не заполняется при чтении документа). |
| [set_Paragraphs](./set_paragraphs/)(const System::SharedPtr\<Aspose::Pdf::Paragraphs\>\&) | Получает абзацы. |
| [set_Rect](./set_rect/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Устанавливает прямоугольник страницы. При получении: возвращается crop‑box страницы, если он указан, иначе возвращается media‑box страницы. При установке: всегда устанавливается media‑box страницы. Обратите внимание, что это свойство не учитывает вращение страницы. Чтобы получить прямоугольник страницы с учётом вращения, используйте ActualRect. |
| [set_Rotate](./set_rotate/)(Aspose::Pdf::Rotation) | Устанавливает вращение страницы. |
| [set_TabOrder](./set_taborder/)(Aspose::Pdf::TabOrder) | Устанавливает порядок табуляции страницы. Возможные значения: [Row](../row/), Column. По умолчанию, Manual. |
| [set_TocInfo](./set_tocinfo/)(const System::SharedPtr\<Aspose::Pdf::TocInfo\>\&) | Устанавливает информацию о содержании. |
| [set_TrimBox](./set_trimbox/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Устанавливает обрезную рамку страницы. |
| [set_UserUnit](./set_userunit/)(double) | Устанавливает значение UserUnit. Положительное число, задающее размер единиц пользовательского пространства по умолчанию, в кратных 1/72 дюйма. Значение по умолчанию — 1. Установите ноль или отрицательное значение, чтобы очистить эту запись на странице. |
| [set_Watermark](./set_watermark/)(const System::SharedPtr\<Aspose::Pdf::Watermark\>\&) | Устанавливает водяной знак страницы. |
| [SetPageSize](./setpagesize/)(double, double) | Устанавливает размер страницы. |
| [TrySaveVectorGraphics](./trysavevectorgraphics/)(const System::String\&) | Пытается сохранить векторную графику, если она присутствует на странице. Формат сохранения — SVG. |
## Typedefs

| Типовое определение | Описание |
| --- | --- |
| [BeforePageGenerate](./beforepagegenerate/) | Процедура настройки заголовка и нижнего колонтитула. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Class [IOperatorContainer](../ioperatorcontainer/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
