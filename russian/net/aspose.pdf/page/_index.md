---
title: "Класс Page"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Page. Класс, представляющий страницу PDF‑документа"
type: docs
weight: 8190
url: /ru/net/aspose.pdf/page/
---
## Page class

Класс, представляющий страницу PDF document.

```csharp
public sealed class Page : IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | Получает коллекцию свойств страницы. |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | Получает коллекцию аннотаций страницы. [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | Получает или задает art‑box страницы. |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | Получает коллекцию артефактов на странице. |
| [Background](../../aspose.pdf/page/background/) { get; set; } | Получает или задает цвет фона страницы. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | Получает или задаёт фоновое изображение для страницы (только для генератора, не заполняется при чтении документа). |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | Получает или задает bleed‑box страницы. |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | Устанавливает тип цвета страниц на основе информации, полученной от операторов SetColor, изображений и форм. |
| [Contents](../../aspose.pdf/page/contents/) { get; } | Получает коллекцию операторов в потоке содержимого страницы. [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | Получает или задает crop‑box страницы. |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | Получает или задает длительность отображения страницы. Это время в секундах, в течение которого страница должна отображаться во время презентации. Возвращает -1, если длительность не определена. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | Получает список объектов Field в порядке Tab на этой странице. |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | Получает или задает нижний колонтитул страницы. |
| [Group](../../aspose.pdf/page/group/) { get; set; } | Получает или задает класс атрибутов группы, определяющий атрибуты группы страниц для использования в модели прозрачного изображения. |
| [Header](../../aspose.pdf/page/header/) { get; set; } | Получает или задает верхний колонтитул страницы. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | Получает или задает добавление абзацев после последнего абзаца страницы |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | Получает или задает коллекцию слоёв. |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | Получает или задает media‑box страницы. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | Получает или задает стиль линии для заметок (только для генератора, не заполняется при чтении документа). |
| [Number](../../aspose.pdf/page/number/) { get; } | Получить номер страницы. |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | Получает или задает информацию о странице (только для генератора, не заполняется при чтении документа). |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | Получает абзацы. |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | Получает или задает прямоугольник страницы. При получении возвращается crop‑box страницы, если он указан, иначе возвращается media‑box. При установке всегда задаётся media‑box. Обратите внимание, что это свойство не учитывает поворот страницы. Чтобы получить прямоугольник страницы с учётом поворота, используйте ActualRect. |
| [Resources](../../aspose.pdf/page/resources/) { get; } | Получает ресурсы страницы. Объект Resources содержит коллекции изображений, форм и шрифтов. [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | Получает или задает поворот страницы. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | Получает матрицу преобразования для страницы. |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | Получает или задает порядок табуляции страницы. Возможные значения: Row, Column. По умолчанию — Manual. |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | Получает или задает информацию о содержании. |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | Получает или задает TrimBox страницы. |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | Получает или задает значение UserUnit. Положительное число, определяющее размер единиц пользовательского пространства по умолчанию, в кратных 1/72 дюйма. Значение по умолчанию — 1. Установите ноль или отрицательное значение, чтобы очистить эту запись на странице. |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | Получает или задает водяной знак страницы. |

## Методы

| Имя | Описание |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | Принимает объект‑посетитель [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/), предоставляющий функциональность для работы с аннотациями. |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | Принимает объект‑посетитель [`ImagePlacementAbsorber`](../imageplacementabsorber/), предоставляющий функциональность для работы с объектами размещения изображений. |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | Принимает объект‑посетитель [`TextAbsorber`](../../aspose.pdf.text/textabsorber/), предоставляющий функциональность для работы с текстовыми объектами. |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | Принимает объект‑посетитель [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/), предоставляющий функциональность для работы с текстовыми объектами. |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | Добавляет графику на страницу. Работает быстрее, чем добавление элементов по одному с помощью метода [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/). |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | Добавляет изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | Добавляет изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | Добавляет поисковое изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | Добавляет изображение на страницу и размещает его в зависимости от позиции прямоугольника изображения. |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | Помещает штамп на страницу. Штамп может быть номером страницы, изображением или простым текстом, например, логотипом. |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | Преобразует текущую страницу в bitmap и затем возвращает массив байтов. |
| [AsXml](../../aspose.pdf/page/asxml/)() | Преобразует текущую страницу в XML с кодировкой UTF-8. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | Вычисляет значение bbox — прямоугольник, содержащий содержимое без видимых полей. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | Конвертировать страницу в PNG для потока изображений DSR, OMR, OCR. |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | Удаляет графику со страницы. Работает быстрее, чем удаление элементов по одному с помощью метода [`Remove`](../../aspose.pdf.vector/graphicelement/remove/). |
| [Dispose](../../aspose.pdf/page/dispose/)() | Освобождает память |
| [Flatten](../../aspose.pdf/page/flatten/)() | Удаляет все поля, расположенные на странице, и вместо них размещает их значения. |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | Очищает кэшированные данные |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | Возвращает уведомления о внутренних операциях с содержимым страницы. (В настоящее время поддерживаются только уведомления о событиях абзацев в сценариях добавления текста.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | Возвращает прямоугольник страницы в соответствии с её CropBox (или MediaBox, если CropBox равен null). |
| [GetResources](../../aspose.pdf/page/getresources/)() | Получает ресурсы, связанные со страницой. |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | Определяет наличие векторной графики, если она присутствует на странице. |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | Получает флаг, указывающий, пустая страница или нет. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | Преобразует страницу в градации серого. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | Объединяет все слои на странице в один слой с указанным новым именем слоя. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | Объединяет все слои на странице в один слой с указанным новым именем слоя и необязательным идентификатором группы содержимого. |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | Изменяет размер страницы. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | Отправляет страницу на обработку с указанным устройством страницы. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | Отправляет страницу на обработку с указанным устройством страницы. |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | Устанавливает размер страницы для страницы. |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | Пытается сохранить векторную графику, если она присутствует на странице. Формат сохранения — SVG. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | Преобразует целочисленное значение в соответствующий элемент перечисления вращения. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | Преобразует элемент перечисления вращения в целочисленное значение. |

## События

| Имя | Описание |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | Событие для настройки заголовка и нижнего колонтитула. |

## Другие члены

| Имя | Описание |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | Процедура настройки заголовка и нижнего колонтитула. |

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


