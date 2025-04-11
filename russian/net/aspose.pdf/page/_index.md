---
title: Class Page
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Page. Класс, представляющий страницу PDF документа
type: docs
weight: 8050
url: /ru/net/aspose.pdf/page/
---
## Класс Page

Класс, представляющий страницу PDF документа.

```csharp
public sealed class Page : IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | Получает коллекцию свойств страницы. |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | Получает коллекцию аннотаций страницы. [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | Получает или устанавливает арт-бокс страницы. |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | Получает коллекцию артефактов на странице. |
| [Background](../../aspose.pdf/page/background/) { get; set; } | Получает или устанавливает цвет фона страницы. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | Получает или устанавливает фоновое изображение для страницы (только для генератора, не заполняется при чтении документа). |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | Получает или устанавливает бокс обрезки страницы. |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | Устанавливает тип цвета страниц на основе информации, полученной от операторов SetColor, изображений и форм. |
| [Contents](../../aspose.pdf/page/contents/) { get; } | Получает коллекцию операторов в потоке содержимого страницы. [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | Получает или устанавливает бокс обрезки страницы. |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | Получает или устанавливает продолжительность отображения страницы. Это время в секундах, в течение которого страница должна отображаться во время презентации. Возвращает -1, если продолжительность не определена. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | Получает список объектов Field в порядке вкладок на этой странице. |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | Получает или устанавливает нижний колонтитул страницы. |
| [Group](../../aspose.pdf/page/group/) { get; set; } | Получает или устанавливает класс атрибутов группы, указывающий атрибуты группы страниц для использования в модели прозрачной визуализации. |
| [Header](../../aspose.pdf/page/header/) { get; set; } | Получает или устанавливает верхний колонтитул страницы. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | Получает или устанавливает добавление абзацев после последнего абзаца страницы |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | Получает или устанавливает коллекцию слоев. |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | Получает или устанавливает медиабокс страницы. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | Получает или устанавливает стиль линии для заметок. (только для генератора, не заполняется при чтении документа) |
| [Number](../../aspose.pdf/page/number/) { get; } | Получает номер страницы. |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | Получает или устанавливает информацию о странице (только для генератора, не заполняется при чтении документа). |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | Получает абзацы. |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | Получает или устанавливает прямоугольник страницы. Для получения: возвращается бокс обрезки страницы, если он указан, в противном случае возвращается медиабокс страницы. Для установки: медиабокс страницы всегда устанавливается. Обратите внимание, что это свойство не учитывает поворот страницы. Чтобы получить прямоугольник страницы с учетом поворота, используйте ActualRect. |
| [Resources](../../aspose.pdf/page/resources/) { get; } | Получает ресурсы страницы. Объект ресурсов содержит коллекции изображений, форм и шрифтов. [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | Получает или устанавливает поворот страницы. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | Получает матрицу преобразования для страницы. |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | Получает или устанавливает порядок вкладок страницы. Возможные значения: Row, Column. По умолчанию, Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | Получает или устанавливает информацию о содержании. |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | Получает или устанавливает бокс обрезки страницы. |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | Получает или устанавливает значение UserUnit. Положительное число, указывающее размер единиц пользовательского пространства по умолчанию, в кратных 1 / 72 дюйма. Значение по умолчанию - 1. Пожалуйста, установите нулевое или отрицательное значение, чтобы очистить эту запись на странице. |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | Получает или устанавливает водяной знак страницы. |

## Методы

| Имя | Описание |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | Принимает объект посетителя [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/), который предоставляет функциональность для работы с аннотациями. |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | Принимает объект посетителя [`ImagePlacementAbsorber`](../imageplacementabsorber/), который предоставляет функциональность для работы с объектами размещения изображений. |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | Принимает объект посетителя [`TextAbsorber`](../../aspose.pdf.text/textabsorber/), который предоставляет функциональность для работы с текстовыми объектами. |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | Принимает объект посетителя [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/), который предоставляет функциональность для работы с текстовыми объектами. |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | Добавляет графику на страницу. Работает быстрее, чем добавление элементов по одному с помощью метода [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/). |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | Добавляет изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | Добавляет изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | Добавляет поисковое изображение на страницу и размещает его в центре указанного прямоугольника, сохраняя пропорции изображения. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | Добавляет изображение на страницу и размещает его в зависимости от позиции прямоугольника изображения. |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | Помещает штамп на страницу. Штамп может быть номером страницы, изображением или простым текстом, например, логотипом. |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | Преобразует текущую страницу в растровое изображение и затем возвращает массив байтов. |
| [AsXml](../../aspose.pdf/page/asxml/)() | Преобразует текущую страницу в XML в кодировке utf8. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | Вычисляет значение bbox - прямоугольник, содержащий содержимое без видимых полей. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | Преобразует страницу в PNG для DSR, OMR, OCR потока изображений. |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | Удаляет графику со страницы. Работает быстрее, чем удаление элементов по одному с помощью метода [`Remove`](../../aspose.pdf.vector/graphicelement/remove/). |
| [Dispose](../../aspose.pdf/page/dispose/)() | Освобождает память |
| [Flatten](../../aspose.pdf/page/flatten/)() | Удаляет все поля, расположенные на странице, и помещает их значения вместо этого. |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | Очищает кэшированные данные |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | Возвращает уведомления о внутренних операциях с содержимым страницы. (В настоящее время поддерживаются только уведомления о событиях абзацев в сценариях добавления текста.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | Возвращает прямоугольник страницы в соответствии с ее CropBox (или MediaBox, если CropBox равен null). |
| [GetResources](../../aspose.pdf/page/getresources/)() | Извлекает ресурсы, связанные со страницей. |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | Определяет наличие векторной графики, если она присутствует на странице. |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | Получает флаг, является ли страница пустой или нет. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | Преобразует страницу в градации серого. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | Объединяет все слои на странице в один слой с указанным новым именем слоя. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | Объединяет все слои на странице в один слой с указанным новым именем слоя и необязательным идентификатором группы содержимого. |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | Изменяет размер страницы. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | Отправляет страницу на обработку с данным устройством страницы. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | Отправляет страницу на обработку с данным устройством страницы. |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | Устанавливает размер страницы для страницы. |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | Пытается сохранить векторную графику, если она присутствует на странице. Формат сохранения - SVG. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | Переводит целочисленное значение в соответствующий член перечисления поворота. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | Переводит член перечисления поворота в целочисленное значение. |

## События

| Имя | Описание |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | Событие для настройки верхнего и нижнего колонтитулов. |

## Другие члены

| Имя | Описание |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | Процедура для настройки верхнего и нижнего колонтитулов. |

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)