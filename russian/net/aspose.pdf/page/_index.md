---
title: Page
second_title: Aspose.PDF для справочника API .NET
description: Класс представляющий страницу документа PDF.
type: docs
weight: 5790
url: /ru/net/aspose.pdf/page/
---
## Page class

Класс, представляющий страницу документа PDF.

```csharp
public sealed class Page : IDisposable
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions) { get; } | Получает коллекцию свойств страницы. |
| [Annotations](../../aspose.pdf/page/annotations) { get; } | Получает коллекцию аннотаций страницы. [`Annotations`](./annotations) |
| [ArtBox](../../aspose.pdf/page/artbox) { get; set; } | Получает или устанавливает художественное поле страницы. |
| [Artifacts](../../aspose.pdf/page/artifacts) { get; } | Получает коллекцию артефактов на странице. |
| [Background](../../aspose.pdf/page/background) { get; set; } | Получает или задает цвет фона страницы. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage) { get; set; } | Получает или устанавливает фоновое изображение для страницы (только для генератора). |
| [BleedBox](../../aspose.pdf/page/bleedbox) { get; set; } | Получает или задает поле выхода за обрез страницы. |
| [ColorType](../../aspose.pdf/page/colortype) { get; } | Устанавливает цветотип страниц на основании информации, полученной от операторов SetColor, изображений и форм. |
| [Contents](../../aspose.pdf/page/contents) { get; } | Получает набор операторов в потоке содержимого страницы. [`OperatorCollection`](../operatorcollection) |
| [CropBox](../../aspose.pdf/page/cropbox) { get; set; } | Получает или устанавливает поле обрезки страницы. |
| [Duration](../../aspose.pdf/page/duration) { get; set; } | Получает установленную продолжительность отображения страницы. Это время в секундах, в течение которого страница должна отображаться во время презентации. Возвращает -1, если продолжительность не определена. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder) { get; } | Получает список объектов Field в порядке табуляции на этой странице. |
| [Footer](../../aspose.pdf/page/footer) { get; set; } | Получает или устанавливает нижний колонтитул страницы. |
| [Group](../../aspose.pdf/page/group) { get; set; } | Получает или задает класс атрибутов группы, определяющий атрибуты группы страниц страницы для использования в модели прозрачного изображения. |
| [Header](../../aspose.pdf/page/header) { get; set; } | Получает или задает заголовок страницы. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast) { get; set; } | Получает или задает добавление абзацев после последнего абзаца страницы |
| [Layers](../../aspose.pdf/page/layers) { get; set; } | Получает или устанавливает коллекцию слоев. |
| [MediaBox](../../aspose.pdf/page/mediabox) { get; set; } | Получает или устанавливает медиа-бокс страницы. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle) { get; set; } | Получает или устанавливает стиль линии для заметок. (только для генератора) |
| [Number](../../aspose.pdf/page/number) { get; } | Получить номер страницы. |
| [PageInfo](../../aspose.pdf/page/pageinfo) { get; set; } | Получает или устанавливает информацию о странице (только для генератора, не заполняется при чтении файла). |
| [Paragraphs](../../aspose.pdf/page/paragraphs) { get; set; } | Получает абзацы. |
| [Rect](../../aspose.pdf/page/rect) { get; set; } | Получает или задает прямоугольник страницы. Поле обрезки страницы возвращается, если указано, в противном случае возвращается поле мультимедиа страницы. Обратите внимание, что это свойство не учитывает поворот страницы. Чтобы получить прямоугольник страницы с учетом поворота, используйте ActualRect. |
| [Resources](../../aspose.pdf/page/resources) { get; } | Получает ресурсы страницы. Объект Resources содержит коллекции изображений, форм и шрифтов. [`Resources`](./resources) |
| [Rotate](../../aspose.pdf/page/rotate) { get; set; } | Получает или задает поворот страницы. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix) { get; } | Получает матрицу преобразования для страницы. |
| [TabOrder](../../aspose.pdf/page/taborder) { get; set; } | Получает или устанавливает порядок табуляции страницы. Возможные значения:Строка, Столбец. По умолчанию, Вручную |
| [TocInfo](../../aspose.pdf/page/tocinfo) { get; set; } | Получает или устанавливает информацию о содержании. |
| [TrimBox](../../aspose.pdf/page/trimbox) { get; set; } | Получает или устанавливает поле обрезки страницы. |
| [UserUnit](../../aspose.pdf/page/userunit) { get; set; } | Получает или задает значение UserUnit. Положительное число, указывающее размер единиц пользовательского пространства по умолчанию, кратных 1 ⁄ 72 дюйма. Значение по умолчанию 1. Пожалуйста, установите нулевое или отрицательное значение, чтобы очистить эту запись на странице. |
| [Watermark](../../aspose.pdf/page/watermark) { get; set; } | Получает или задает водяной знак страницы. |

## Методы

| Имя | Описание |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept#accept)(AnnotationSelector) | Принимает[`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector)объект посетителя, предоставляющий функциональные возможности для работы с аннотациями. |
| [Accept](../../aspose.pdf/page/accept#accept_1)(ImagePlacementAbsorber) | Принимает[`ImagePlacementAbsorber`](../imageplacementabsorber)объект посетителя, предоставляющий функциональные возможности для работы с объектами размещения изображения. |
| [Accept](../../aspose.pdf/page/accept#accept_2)(TextAbsorber) | Принимает[`TextAbsorber`](../../aspose.pdf.text/textabsorber)объект посетителя, предоставляющий функциональные возможности для работы с текстовыми объектами. |
| [Accept](../../aspose.pdf/page/accept#accept_3)(TextFragmentAbsorber) | Принимает[`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber)объект посетителя, предоставляющий функциональные возможности для работы с текстовыми объектами. |
| [AddImage](../../aspose.pdf/page/addimage#addimage)(Stream, Rectangle) | Добавляет изображение на страницу и размещает его в середине указанного прямоугольника, сохраняя пропорции изображения. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_2)(string, Rectangle) | Добавляет изображение на страницу и размещает его в середине указанного прямоугольника, сохраняя пропорции изображения. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_3)(string, Stream, Rectangle) | Добавляет доступное для поиска изображение на страницу и размещает его в середине указанного прямоугольника, сохраняя пропорции изображения. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_1)(Stream, Rectangle, int, int, bool) | Добавляет изображение на страницу и размещает его в зависимости от положения прямоугольника изображения. |
| [AddStamp](../../aspose.pdf/page/addstamp)(Stamp) | Поставить штамп на страницу. Штамп может быть номером страницы, изображением или простым текстом, например логотипом. |
| [AsByteArray](../../aspose.pdf/page/asbytearray)(Resolution) | Преобразует текущую страницу в растровое изображение, а затем возвращает массив байтов. |
| [AsXml](../../aspose.pdf/page/asxml)() | Преобразует текущую страницу в xml в кодировке utf8. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox)() | Вычисляет значение bbox - прямоугольник, содержащий содержимое без видимых полей. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream)() | Преобразование страницы в PNG для потока изображений DSR, OMR, OCR. |
| [Dispose](../../aspose.pdf/page/dispose)() | Освобождает память |
| [Flatten](../../aspose.pdf/page/flatten)() | Удаляет все поля, расположенные на странице, и ставит вместо них их значения. |
| [FreeMemory](../../aspose.pdf/page/freememory)() | Очищает кэшированные данные |
| [GetNotifications](../../aspose.pdf/page/getnotifications)() | Возвращает уведомления о внутренних операциях с содержимым страницы. (Теперь поддерживаются только уведомления о событиях абзаца в сценариях добавления текста.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect)(bool) | Возвращает прямоугольник страницы. |
| [IsBlank](../../aspose.pdf/page/isblank)(double) | Получает флаг, является ли страница пустой или нет. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale)() | Преобразует страницу в оттенки серого. |
| [SendTo](../../aspose.pdf/page/sendto#sendto)(PageDevice, Stream) | Отправляет страницу для обработки с заданным страничным устройством. |
| [SendTo](../../aspose.pdf/page/sendto#sendto_1)(PageDevice, string) | Отправляет страницу для обработки с заданным страничным устройством. |
| [SetPageSize](../../aspose.pdf/page/setpagesize)(double, double) | Устанавливает размер страницы для страницы. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation)(int) | Преобразует целочисленное значение в соответствующий член перечисления вращения. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint)(Rotation) | Преобразует элемент перечисления вращения в целочисленное значение. |

## Другие члены

| Имя | Описание |
| --- | --- |
| delegate [BeforePageGenerate](page.beforepagegenerate) | Процедура настройки верхнего и нижнего колонтитула. |

### Смотрите также

* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
