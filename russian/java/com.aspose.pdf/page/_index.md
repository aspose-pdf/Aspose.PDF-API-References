---
title: Page
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий страницу документа PDF.
type: docs
weight: 257
url: /ru/java/com.aspose.pdf/page/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
com.aspose.ms.System.IDisposable, java.io.Closeable, com.aspose.pdf.ISupportsMemoryCleanup
```
public final class Page implements System.IDisposable, Closeable, ISupportsMemoryCleanup
```

Класс, представляющий страницу документа PDF.
## Методы

| Метод | Описание |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Принимает объект посетителя AnnotationSelector, предоставляющий функциональные возможности для работы с аннотациями. |
| [accept(ImagePlacementAbsorber visitor)](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Принимает объект посетителя ImagePlacementAbsorber, предоставляющий функциональные возможности для работы с объектами размещения изображения. |
| [accept(TextAbsorber visitor)](#accept-com.aspose.pdf.TextAbsorber-) | Принимает объект посетителя TextAbsorber, предоставляющий функциональные возможности для работы с текстовыми объектами. |
| [accept(TextFragmentAbsorber visitor)](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Принимает объект посетителя TextFragmentAbsorber, предоставляющий функциональные возможности для работы с текстовыми объектами. |
| [addImage(InputStream imageStream, Rectangle imageRect)](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | Добавляет изображение на страницу и размещает его в середине указанного прямоугольника, сохраняя пропорции изображения. |
| [addImage(InputStream stream, Rectangle rectangle, CompositingParameters compositingParameters)](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | Добавляет изображение на страницу и размещает его в середине указанного прямоугольника, сохраняя пропорции изображения. |
| [addImage(InputStream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, boolean saveImageProportions)](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) | Добавляет доступное для поиска изображение на страницу и размещает его в середине указанного прямоугольника, сохраняя пропорции изображения. |
| [addImage(String imagePath, Rectangle rectangle)](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | Добавляет изображение на страницу и размещает его в середине указанного прямоугольника, сохраняя пропорции изображения. |
| [addImage(String hocr, InputStream imageStream, Rectangle imageRect)](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | Добавляет доступное для поиска изображение на страницу и размещает его в середине указанного прямоугольника, сохраняя пропорции изображения. |
| [addStamp(Stamp stamp)](#addStamp-com.aspose.pdf.Stamp-) | Поместите штамп на страницу. |
| [asByteArray(Resolution resolution)](#asByteArray-com.aspose.pdf.devices.Resolution-) | Преобразует текущую страницу в растровое изображение BMP, а затем возвращает массив байтов. |
| [asXml()](#asXml--) | Преобразует текущую страницу в xml в кодировке utf8. |
| [calculateContentBBox()](#calculateContentBBox--) | Вычисляет значение bbox - прямоугольник, содержащий содержимое без видимых полей. |
| [clearContents()](#clearContents--) | Только для внутреннего использования |
| [close()](#close--) | Закрывает все ресурсы, используемые этим документом. |
| [convertToPNGMemoryStream()](#convertToPNGMemoryStream--) | Конвертируйте страницу в PNG для потока изображений DSR, OMR, OCR. |
| [deleteUnusedResources(System.Collections.Generic.Dictionary<Integer,Integer> usageTable)](#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer--) |  |
| [dispose()](#dispose--) | Освобождает память |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillUsedObjectsTable(System.Collections.Generic.Dictionary<Integer,Integer> usageTable, IPdfDictionary CommonResources)](#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer--com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [findReferences(OperatorCollection contents, String name)](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Возвращает список операторов, использующих ресурс с указанным именем. |
| [findReferences(String name)](#findReferences-java.lang.String-) | Найти ссылки |
| [flatten()](#flatten--) | Удаляет все статические поля, расположенные на странице, и помещает вместо них их значения. |
| [freeMemory()](#freeMemory--) | Очищает кэшированные данные |
| [getActions()](#getActions--) | Получает коллекцию свойств страницы. |
| [getAnnotations()](#getAnnotations--) | Получает коллекцию аннотаций страницы. |
| [getArtBox()](#getArtBox--) | Получает художественное поле страницы. |
| [getArtifacts()](#getArtifacts--) | Получает коллекцию артефактов на странице. |
| [getBackground()](#getBackground--) | Получает цвет фона страницы. |
| [getBackgroundImage()](#getBackgroundImage--) | Получает или задает фоновое изображение для страницы (только для генератора). |
| [getBleedBox()](#getBleedBox--) | Получает поле за обрез страницы. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Получает цветотип страниц на основе информации, получаемой от операторов SetColor, изображений и форм. |
| [getContents()](#getContents--) | Получает коллекцию операторов в потоке содержимого страницы. |
| [getContentsAppender()](#getContentsAppender--) | Получает приложение с текущим содержимым. |
| [getCropBox()](#getCropBox--) | Получает поле обрезки страницы. |
| [getDocument()](#getDocument--) | Получить документ |
| [getDuration()](#getDuration--) | Получает продолжительность отображения страницы. |
| [getEnginePage()](#getEnginePage--) | Только для внутреннего использования |
| [getFieldsInTabOrder()](#getFieldsInTabOrder--) | Получает список объектов Field в порядке табуляции на этой странице. |
| [getFooter()](#getFooter--) | Получает нижний колонтитул страницы. |
| [getGroup()](#getGroup--) | Получает класс атрибутов группы, определяющий атрибуты группы страниц страницы для использования в модели прозрачного изображения. |
| [getHeader()](#getHeader--) | Получает заголовок страницы. |
| [getLayers()](#getLayers--) | Получает коллекцию слоев. |
| [getMediaBox()](#getMediaBox--) | Получает медиабокс страницы. |
| [getNoteLineStyle()](#getNoteLineStyle--) | Получает стиль линии для заметок. |
| [getNotifications()](#getNotifications--) | Возвращает уведомления о внутренних операциях с содержимым страницы. |
| [getNumber()](#getNumber--) | Получить номер страницы. |
| [getOnBeforePageGenerate()](#getOnBeforePageGenerate--) | Событие для настройки верхнего и нижнего колонтитула. |
| [getPageInfo()](#getPageInfo--) | Получает информацию о странице. |
| [getPageRect(boolean considerRotation)](#getPageRect-boolean-) | Возвращает прямоугольник страницы в соответствии с его CropBox (или MediaBox, если CropBox null). |
| [getParagraphs()](#getParagraphs--) | Получает абзацы. |
| [getRect()](#getRect--) | Возвращает прямоугольник страницы в соответствии с его CropBox и MediaBox; Для получения: возвращается поле обрезки страницы, если указано, в противном случае возвращается поле медиа страницы. |
| [getRect_Rename_Namesake()](#getRect-Rename-Namesake--) | Возвращает прямоугольник страницы в соответствии с его CropBox и MediaBox; |
| [getResources()](#getResources--) | Получает ресурсы страницы. |
| [getRotate()](#getRotate--) | Получает поворот страницы. |
| [getRotationMatrix()](#getRotationMatrix--) | Получает матрицу преобразования для страницы. |
| [getTabOrder()](#getTabOrder--) | Получает порядок табуляции страницы. |
| [getTocInfo()](#getTocInfo--) | Получает информацию о содержании. |
| [getTrimBox()](#getTrimBox--) | Получает поле обрезки страницы. |
| [getUserUnit()](#getUserUnit--) | Получает или задает значение UserUnit. |
| [getWatermark()](#getWatermark--) | Получает водяной знак страницы. |
| [hashCode()](#hashCode--) |  |
| [intToRotation(int rotation)](#intToRotation-int-) | Преобразует целочисленное значение в соответствующий член перечисления вращения. |
| [isAddParagraphsAfterLast()](#isAddParagraphsAfterLast--) | Получает или задает добавление абзацев после последнего абзаца страницы. |
| [isBlank(double fillThresholdFactor)](#isBlank-double-) | Получает флаг, является ли страница пустой или нет. |
| [makeGrayscale()](#makeGrayscale--) | Преобразует страницу в оттенки серого. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeObjectReferences(OperatorCollection contents, String name)](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Удалить ссылки на объекты |
| [removeObjectReferences(String name)](#removeObjectReferences-java.lang.String-) | Удалите ссылки на XObject из содержимого страницы (т.е. все операторы Do, использующие имя объекта). |
| [rotationToInt(int rotation)](#rotationToInt-int-) | Преобразует элемент перечисления вращения в целочисленное значение. |
| [sendTo(PageDevice device, OutputStream output)](#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-) | Отправляет страницу для обработки с заданным страничным устройством. |
| [sendTo(PageDevice device, String outputFileName)](#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-) | Отправляет страницу для обработки с заданным страничным устройством. |
| [setAddParagraphsAfterLast(boolean value)](#setAddParagraphsAfterLast-boolean-) | Получает или задает добавление абзацев после последнего абзаца страницы. |
| [setArtBox(Rectangle value)](#setArtBox-com.aspose.pdf.Rectangle-) | Устанавливает художественную рамку страницы. |
| [setBackground(Color value)](#setBackground-com.aspose.pdf.Color-) | Устанавливает цвет фона страницы. |
| [setBackground(Color value)](#setBackground-java.awt.Color-) | Устанавливает цвет фона страницы. |
| [setBackgroundImage(Image value)](#setBackgroundImage-com.aspose.pdf.Image-) | Получает или задает фоновое изображение для страницы (только для генератора). |
| [setBleedBox(Rectangle value)](#setBleedBox-com.aspose.pdf.Rectangle-) | Устанавливает поле выпуска страницы. |
| [setCropBox(Rectangle value)](#setCropBox-com.aspose.pdf.Rectangle-) | Устанавливает поле обрезки страницы. |
| [setDuration(double value)](#setDuration-double-) | Устанавливает продолжительность отображения страницы. |
| [setEnginePage(IPage enginePage)](#setEnginePage-com.aspose.pdf.engine.commondata.IPage-) | Только для внутреннего использования |
| [setFooter(HeaderFooter value)](#setFooter-com.aspose.pdf.HeaderFooter-) | Устанавливает нижний колонтитул страницы. |
| [setGroup(Group value)](#setGroup-com.aspose.pdf.Group-) | Задает класс атрибутов группы, определяющий атрибуты группы страниц страницы для использования в модели прозрачного изображения. |
| [setHeader(HeaderFooter value)](#setHeader-com.aspose.pdf.HeaderFooter-) | Устанавливает заголовок страницы. |
| [setLayers(ArrayList<Layer> value)](#setLayers-java.util.ArrayList-com.aspose.pdf.Layer--) | Устанавливает коллекцию слоев. |
| [setLayersInternal(System.Collections.Generic.List<Layer> value)](#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Layer--) | Устанавливает коллекцию слоев. |
| [setMediaBox(Rectangle value)](#setMediaBox-com.aspose.pdf.Rectangle-) | Устанавливает медиа-бокс страницы. |
| [setNoteLineStyle(GraphInfo value)](#setNoteLineStyle-com.aspose.pdf.GraphInfo-) | Устанавливает стиль линии для заметок. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Устанавливает информацию о странице. |
| [setPageSize(double width, double height)](#setPageSize-double-double-) | Устанавливает размер страницы для страницы. |
| [setParagraphs(Paragraphs value)](#setParagraphs-com.aspose.pdf.Paragraphs-) | Устанавливает абзацы. |
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) | Получает или задает прямоугольник страницы. |
| [setRotate(int value)](#setRotate-int-) | Устанавливает поворот страницы. |
| [setTabOrder(int value)](#setTabOrder-int-) | Устанавливает порядок табуляции страницы. |
| [setTocInfo(TocInfo value)](#setTocInfo-com.aspose.pdf.TocInfo-) | Устанавливает информацию о содержании. |
| [setTransition(IPdfDictionary transition)](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) | Установить переход |
| [setTrimBox(Rectangle value)](#setTrimBox-com.aspose.pdf.Rectangle-) | Устанавливает поле обрезки страницы. |
| [setUserUnit(double value)](#setUserUnit-double-) | Получает или задает значение UserUnit. |
| [setWatermark(Watermark value)](#setWatermark-com.aspose.pdf.Watermark-) | Устанавливает водяной знак страницы. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Принимает объект посетителя AnnotationSelector, предоставляющий функциональные возможности для работы с аннотациями.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Объект выбора аннотаций. |

### accept(ImagePlacementAbsorber visitor) {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
```
public void accept(ImagePlacementAbsorber visitor)
```


Принимает объект посетителя ImagePlacementAbsorber, предоставляющий функциональные возможности для работы с объектами размещения изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [ImagePlacementAbsorber](../../com.aspose.pdf/imageplacementabsorber) | Объект поглотителя размещения изображения. |

### accept(TextAbsorber visitor) {#accept-com.aspose.pdf.TextAbsorber-}
```
public void accept(TextAbsorber visitor)
```


Принимает объект посетителя TextAbsorber, предоставляющий функциональные возможности для работы с текстовыми объектами.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [TextAbsorber](../../com.aspose.pdf/textabsorber) | Объект поглотителя текста. |

### accept(TextFragmentAbsorber visitor) {#accept-com.aspose.pdf.TextFragmentAbsorber-}
```
public void accept(TextFragmentAbsorber visitor)
```


Принимает объект посетителя TextFragmentAbsorber, предоставляющий функциональные возможности для работы с текстовыми объектами.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) | Объект поглотителя текста. |

### addImage(InputStream imageStream, Rectangle imageRect) {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-}
```
public void addImage(InputStream imageStream, Rectangle imageRect)
```


Добавляет изображение на страницу и размещает его в середине указанного прямоугольника, сохраняя пропорции изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | java.io.InputStream | Поток изображения. |
| imageRect | [Rectangle](../../com.aspose.pdf/rectangle) | Положение изображения. |

### addImage(InputStream stream, Rectangle rectangle, CompositingParameters compositingParameters) {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
```
public void addImage(InputStream stream, Rectangle rectangle, CompositingParameters compositingParameters)
```


Добавляет изображение на страницу и размещает его в середине указанного прямоугольника, сохраняя пропорции изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток изображения. |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | Положение изображения. |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | Параметры композиции. |

### addImage(InputStream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, boolean saveImageProportions) {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
```
public void addImage(InputStream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, boolean saveImageProportions)
```


Добавляет доступное для поиска изображение на страницу и размещает его в середине указанного прямоугольника, сохраняя пропорции изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | java.io.InputStream | Объект InputStream |
| imageRect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |
| imageWidth | int | целое значение |
| imageHeight | int | целое значение |
| saveImageProportions | boolean | логическое значение |

### addImage(String imagePath, Rectangle rectangle) {#addImage-java.lang.String-com.aspose.pdf.Rectangle-}
```
public void addImage(String imagePath, Rectangle rectangle)
```


Добавляет изображение на страницу и размещает его в середине указанного прямоугольника, сохраняя пропорции изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imagePath | java.lang.String | Путь к изображению. |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | Положение изображения. |

### addImage(String hocr, InputStream imageStream, Rectangle imageRect) {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-}
```
public void addImage(String hocr, InputStream imageStream, Rectangle imageRect)
```


Добавляет доступное для поиска изображение на страницу и размещает его в середине указанного прямоугольника, сохраняя пропорции изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| hocr | java.lang.String | Хокр изображения. |
| imageStream | java.io.InputStream | Поток изображения. |
| imageRect | [Rectangle](../../com.aspose.pdf/rectangle) | Положение изображения. |

### addStamp(Stamp stamp) {#addStamp-com.aspose.pdf.Stamp-}
```
public void addStamp(Stamp stamp)
```


Поместите штамп на страницу. Штамп может быть номером страницы, изображением или простым текстом, например логотипом.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stamp | [Stamp](../../com.aspose.pdf/stamp) | Штамп для добавления на страницу. Каждый штамп имеет свои координаты и соответствующие свойства относительно вида штампа, т.е. изображение или текстовое значение. |

### asByteArray(Resolution resolution) {#asByteArray-com.aspose.pdf.devices.Resolution-}
```
public byte[] asByteArray(Resolution resolution)
```


Преобразует текущую страницу в растровое изображение BMP, а затем возвращает массив байтов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Разрешение. |

**Возвращает:**
байт[] - преобразованный массив байтов изображения.
### asXml() {#asXml--}
```
public String asXml()
```


Преобразует текущую страницу в xml в кодировке utf8.

**Возвращает:**
java.lang.String — преобразованная строка xml.
### calculateContentBBox() {#calculateContentBBox--}
```
public Rectangle calculateContentBBox()
```


Вычисляет значение bbox - прямоугольник, содержащий содержимое без видимых полей.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Значение Bbox - прямоугольник, содержащий содержимое без видимых полей
### clearContents() {#clearContents--}
```
public void clearContents()
```


Только для внутреннего использования

### close() {#close--}
```
public void close()
```


Закрывает все ресурсы, используемые этим документом.

### convertToPNGMemoryStream() {#convertToPNGMemoryStream--}
```
public byte[] convertToPNGMemoryStream()
```


Конвертируйте страницу в PNG для потока изображений DSR, OMR, OCR.

**Возвращает:**
байт[] - поток изображения в байтах[] множество.
### deleteUnusedResources(System.Collections.Generic.Dictionary<Integer,Integer> usageTable) {#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer--}
```
public void deleteUnusedResources(System.Collections.Generic.Dictionary<Integer,Integer> usageTable)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| usageTable | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.Integer> |  |

### dispose() {#dispose--}
```
public void dispose()
```


Освобождает память

Этот метод устарел, вместо него используйте close().

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### fillUsedObjectsTable(System.Collections.Generic.Dictionary<Integer,Integer> usageTable, IPdfDictionary CommonResources) {#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer--com.aspose.pdf.engine.data.IPdfDictionary-}
```
public void fillUsedObjectsTable(System.Collections.Generic.Dictionary<Integer,Integer> usageTable, IPdfDictionary CommonResources)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| usageTable | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.Integer> |  |
| CommonResources | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

### findReferences(OperatorCollection contents, String name) {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
```
public static List<Object> findReferences(OperatorCollection contents, String name)
```


Возвращает список операторов, использующих ресурс с указанным именем.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| contents | [OperatorCollection](../../com.aspose.pdf/operatorcollection) | Значение OperatorCollection |
| name | java.lang.String | Строковое значение |

**Возвращает:**
java.util.List<java.lang.Object> — Список объектов
### findReferences(String name) {#findReferences-java.lang.String-}
```
public List<Object> findReferences(String name)
```


Найти ссылки

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Строковое значение |

**Возвращает:**
java.util.List<java.lang.Object> — объект списка
### flatten() {#flatten--}
```
public void flatten()
```


Удаляет все статические поля, расположенные на странице, и помещает вместо них их значения.

### freeMemory() {#freeMemory--}
```
public void freeMemory()
```


Очищает кэшированные данные

### getActions() {#getActions--}
```
public PageActionCollection getActions()
```


Получает коллекцию свойств страницы.

**Возвращает:**
[PageActionCollection](../../com.aspose.pdf/pageactioncollection) - Значение PageActionCollection
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


Получает коллекцию аннотаций страницы. Аннотации 

**Возвращает:**
[AnnotationCollection](../../com.aspose.pdf/annotationcollection) - Значение коллекции аннотаций
### getArtBox() {#getArtBox--}
```
public Rectangle getArtBox()
```


Получает художественное поле страницы.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Значение прямоугольника

--------------------

```
Example demonstrates how to get art box of the page:


 Document document = new Document("sample.pdf");
 Rectangle artBox = document.getPages().get(1).getArtBox();
```
### getArtifacts() {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```


Получает коллекцию артефактов на странице.

**Возвращает:**
[ArtifactCollection](../../com.aspose.pdf/artifactcollection) - Значение ArtifactCollection
### getBackground() {#getBackground--}
```
public Color getBackground()
```


Получает цвет фона страницы.

**Возвращает:**
[Color](../../java.awt/color) - Значение цвета
### getBackgroundImage() {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```


Получает или задает фоновое изображение для страницы (только для генератора).

**Возвращает:**
[Image](../../com.aspose.pdf/image) - Экземпляр изображения
### getBleedBox() {#getBleedBox--}
```
public Rectangle getBleedBox()
```


Получает поле за обрез страницы.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Значение прямоугольника

--------------------

```
Example demonstrates how to get bleed box of the page:


 Document document = new Document("sample.pdf");
 Rectangle bleedBox = document.getPages().get(1).getBleedBox();
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


Получает цветотип страниц на основе информации, получаемой от операторов SetColor, изображений и форм.

**Возвращает:**
int - элемент ColorType
### getContents() {#getContents--}
```
public OperatorCollection getContents()
```


Получает коллекцию операторов в потоке содержимого страницы. Коллекция Операторов 

**Возвращает:**
[OperatorCollection](../../com.aspose.pdf/operatorcollection) - Объект OperatorCollection

--------------------

```
Example is demonstrates how to scan operators stream of page.


 Document document = new Document("sample.pdf");
 Operators contents = document.getPages().get_Item(1).getContents();
 for(Operator op : ```
(Iterable)
```contents)
 {
     System.out.println(op);
 }
```
### getContentsAppender() {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```


Получает приложение с текущим содержимым. СодержаниеAppender 

**Возвращает:**
[ContentsAppender](../../com.aspose.pdf/contentsappender) - Значение ContentsAppender
### getCropBox() {#getCropBox--}
```
public Rectangle getCropBox()
```


Получает поле обрезки страницы.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Значение прямоугольника

--------------------

```
Example demonstrates how to get crop box of the page:


 Document document = new Document("sample.pdf");
 Rectangle cropBox = document.getPages().get_Item(1).getCropBox();
```
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Получить документ

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - Объект IDocument
### getDuration() {#getDuration--}
```
public double getDuration()
```


Получает продолжительность отображения страницы. Это время в секундах, в течение которого страница должна отображаться во время презентации. Возвращает -1, если продолжительность не определена.

--------------------

Пример демонстрирует, как получить продолжительность страницы

Документ документ = новый документ ("sample.pdf"); Страница страницы = document.getPages().get(1); int pageRect = page.getDuration();

**Возвращает:**
двойное - двойное значение
### getEnginePage() {#getEnginePage--}
```
public IPage getEnginePage()
```


Только для внутреннего использования

**Возвращает:**
[IPage](../../com.aspose.pdf.engine.commondata/ipage) - внутренний экземпляр
### getFieldsInTabOrder() {#getFieldsInTabOrder--}
```
public List<Field> getFieldsInTabOrder()
```


Получает список объектов Field в порядке табуляции на этой странице.

**Возвращает:**
java.util.List<com.aspose.pdf.Field> — Список объектов поля
### getFooter() {#getFooter--}
```
public HeaderFooter getFooter()
```


Получает нижний колонтитул страницы.

**Возвращает:**
[HeaderFooter](../../com.aspose.pdf/headerfooter) - Нижний колонтитул страницы.
### getGroup() {#getGroup--}
```
public Group getGroup()
```


Получает класс атрибутов группы, определяющий атрибуты группы страниц страницы для использования в модели прозрачного изображения.

**Возвращает:**
[Group](../../com.aspose.pdf/group) - Значение группы
### getHeader() {#getHeader--}
```
public HeaderFooter getHeader()
```


Получает заголовок страницы.

**Возвращает:**
[HeaderFooter](../../com.aspose.pdf/headerfooter) Заголовок страницы.
### getLayers() {#getLayers--}
```
public List<Layer> getLayers()
```


Получает коллекцию слоев.

**Возвращает:**
java.util.List<com.aspose.pdf.Layer> — значение: коллекция слоев.
### getMediaBox() {#getMediaBox--}
```
public Rectangle getMediaBox()
```


Получает медиабокс страницы.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Значение прямоугольника

--------------------

```
Example demonstrates how to get media box of the page:


 Document document = new Document("sample.pdf");
 Rectangle mediaBox = document.getPages().get(1).getMediaBox();
```
### getNoteLineStyle() {#getNoteLineStyle--}
```
public GraphInfo getNoteLineStyle()
```


Получает стиль линии для заметок (только для генератора).

**Возвращает:**
[GraphInfo](../../com.aspose.pdf/graphinfo) - Значение ГрафИнфо
### getNotifications() {#getNotifications--}
```
public String getNotifications()
```


Возвращает уведомления о внутренних операциях с содержимым страницы. (Теперь поддерживаются только уведомления о событиях абзаца в сценариях добавления текста.)

**Возвращает:**
java.lang.String — строка, представляющая уведомления о внутренних операциях с содержимым страницы.
### getNumber() {#getNumber--}
```
public final int getNumber()
```


Получить номер страницы.

**Возвращает:**
интервал - целочисленное значение
### getOnBeforePageGenerate() {#getOnBeforePageGenerate--}
```
public PdfEvent<Page.BeforePageGenerate> getOnBeforePageGenerate()
```


Событие для настройки верхнего и нижнего колонтитула.

**Возвращает:**
[PdfEvent](../../com.aspose.pdf/pdfevent) - Экземпляр PdfEvent 
### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


Получает информацию о странице (только для генератора, не заполняется при чтении файла).

**Возвращает:**
[PageInfo](../../com.aspose.pdf/pageinfo) - Информация о странице.
### getPageRect(boolean considerRotation) {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```


Возвращает прямоугольник страницы в соответствии с его CropBox (или MediaBox, если CropBox null).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| considerRotation | boolean | Если true, то при прямом расчете будет учитываться поворот страницы. |

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольник страницы.
### getParagraphs() {#getParagraphs--}
```
public Paragraphs getParagraphs()
```


Получает абзацы.

**Возвращает:**
[Paragraphs](../../com.aspose.pdf/paragraphs) - Пункты.
### getRect() {#getRect--}
```
public Rectangle getRect()
```


Возвращает прямоугольник страницы в соответствии с его CropBox и MediaBox; Для получения: возвращается поле обрезки страницы, если указано, в противном случае возвращается поле медиа страницы. Для установки: медиабокс страницы всегда установлен.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Значение прямоугольника

--------------------

```
Example demonstrates how to get page rectangle:

 Document document = new Document("sample.pdf");
 Page page = document.getPages().get(1);
 Rectangle pageRect = page.getRect();
```
### getRect_Rename_Namesake() {#getRect-Rename-Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```


Возвращает прямоугольник страницы в соответствии с его CropBox и MediaBox;

Внутренний

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Значение прямоугольника

--------------------

```
Example demonstrates how to get page rectangle:

 Document document = new Document("sample.pdf");
 Page page = document.getPages().get(1);
 Rectangle pageRect = page.getRect();
```
### getResources() {#getResources--}
```
public Resources getResources()
```


Получает ресурсы страницы. Объект Resources содержит коллекции изображений, форм и шрифтов. Ресурсы 

**Возвращает:**
[Resources](../../com.aspose.pdf/resources) - Стоимость ресурсов

--------------------

```
Example demonstrates scan through page images:


 Document document = new Document("sample.pdf");
 DocumentActions actions = document.getActions();
 Resources resources = document.getPages().get(1).getResources();
 for(XImage image : ```
(Ierable)resources
```.getImages())
 {
   System.out.println(image.getWidth() + ":" + image.getHeight());
 }
```
### getRotate() {#getRotate--}
```
public int getRotate()
```


Получает поворот страницы.

**Возвращает:**
int - Элемент вращения

--------------------

```
Example demonstrates how to determine page rotation.


 Document document = new Document("sample.pdf");
 System.out.println(document.getPages().get(1).getRotate());
```
### getRotationMatrix() {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```


Получает матрицу преобразования для страницы.

**Возвращает:**
[Matrix](../../com.aspose.pdf/matrix) Значение матрицы
### getTabOrder() {#getTabOrder--}
```
public int getTabOrder()
```


Получает порядок табуляции страницы. Возможные значения: Строка, Столбец. По умолчанию, вручную

**Возвращает:**
int - значение TabOrder
### getTocInfo() {#getTocInfo--}
```
public TocInfo getTocInfo()
```


Получает информацию о содержании.

**Возвращает:**
[TocInfo](../../com.aspose.pdf/tocinfo) - Информация о содержании - по умолчанию ноль. Если он установлен, эта страница будет содержать оглавление.
### getTrimBox() {#getTrimBox--}
```
public Rectangle getTrimBox()
```


Получает поле обрезки страницы.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Значение прямоугольника

--------------------

```
Example demonstrates how to get trim box of the page:


 Document document = new Document("sample.pdf");
 Rectangle trimBox = document.getPages().get(1).getTrimBox();
```
### getUserUnit() {#getUserUnit--}
```
public final double getUserUnit()
```


 Получает или задает значение UserUnit. Положительное число, указывающее размер единиц пользовательского пространства по умолчанию, кратное 1.\\u0432\\u0403\> 72 дюйма. Значение по умолчанию — 1. Пожалуйста, установите нулевое или отрицательное значение, чтобы очистить эту запись на странице.

**Возвращает:**
двойное - двойное значение
### getWatermark() {#getWatermark--}
```
public Watermark getWatermark()
```


Получает водяной знак страницы.

**Возвращает:**
[Watermark](../../com.aspose.pdf/watermark) - Значение водяного знака
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### intToRotation(int rotation) {#intToRotation-int-}
```
public static int intToRotation(int rotation)
```


Преобразует целочисленное значение в соответствующий член перечисления вращения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rotation | int | Целое значение для преобразования |

**Возвращает:**
int - член перечисления вращения
### isAddParagraphsAfterLast() {#isAddParagraphsAfterLast--}
```
public final boolean isAddParagraphsAfterLast()
```


Получает или задает добавление абзацев после последнего абзаца страницы.

Значение: Значение указывает, будут ли добавлены абзацы после последнего абзаца страницы. Абзацы будут добавлены после последнего абзаца страницы, если значение равно true.

**Возвращает:**
boolean - логическое значение
### isBlank(double fillThresholdFactor) {#isBlank-double-}
```
public boolean isBlank(double fillThresholdFactor)
```


Получает флаг, является ли страница пустой или нет.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fillThresholdFactor | double | Пороговое значение заполнения, которое управляет чувствительностью обнаружения. Должно быть равно или больше 0,01. |

**Возвращает:**
boolean - логическое значение True - если страница пуста; в противном случае ложно.
### makeGrayscale() {#makeGrayscale--}
```
public final void makeGrayscale()
```


Преобразует страницу в оттенки серого.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeObjectReferences(OperatorCollection contents, String name) {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
```
public static void removeObjectReferences(OperatorCollection contents, String name)
```


Удалить ссылки на объекты

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| contents | [OperatorCollection](../../com.aspose.pdf/operatorcollection) | Объект OperatorCollection |
| name | java.lang.String | ценность |

### removeObjectReferences(String name) {#removeObjectReferences-java.lang.String-}
```
public void removeObjectReferences(String name)
```


Удалите ссылки на XObject из содержимого страницы (т.е. все операторы Do, использующие имя объекта).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Строковое значение |

### rotationToInt(int rotation) {#rotationToInt-int-}
```
public static int rotationToInt(int rotation)
```


Преобразует элемент перечисления вращения в целочисленное значение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rotation | int | Элемент перечисления вращения. |

**Возвращает:**
int — соответствующее целочисленное значение
### sendTo(PageDevice device, OutputStream output) {#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-}
```
public void sendTo(PageDevice device, OutputStream output)
```


Отправляет страницу для обработки с заданным страничным устройством.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| device | [PageDevice](../../com.aspose.pdf.devices/pagedevice) | Устройство для обработки страницы. |
| output | java.io.OutputStream | Поток результатов, который используется с устройством для сохранения его вывода. |

### sendTo(PageDevice device, String outputFileName) {#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-}
```
public void sendTo(PageDevice device, String outputFileName)
```


Отправляет страницу для обработки с заданным страничным устройством.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| device | [PageDevice](../../com.aspose.pdf.devices/pagedevice) | Устройство для обработки страницы. |
| outputFileName | java.lang.String | Файл, который используется с устройством для сохранения его вывода. |

### setAddParagraphsAfterLast(boolean value) {#setAddParagraphsAfterLast-boolean-}
```
public final void setAddParagraphsAfterLast(boolean value)
```


Получает или задает добавление абзацев после последнего абзаца страницы.

Значение: Значение указывает, будут ли добавлены абзацы после последнего абзаца страницы. Абзацы будут добавлены после последнего абзаца страницы, если значение равно true.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setArtBox(Rectangle value) {#setArtBox-com.aspose.pdf.Rectangle-}
```
public void setArtBox(Rectangle value)
```


Устанавливает художественную рамку страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Значение прямоугольника |

### setBackground(Color value) {#setBackground-com.aspose.pdf.Color-}
```
public void setBackground(Color value)
```


Устанавливает цвет фона страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Цвет объекта |

### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public void setBackground(Color value)
```


Устанавливает цвет фона страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.Color | Цвет объекта |

### setBackgroundImage(Image value) {#setBackgroundImage-com.aspose.pdf.Image-}
```
public final void setBackgroundImage(Image value)
```


Получает или задает фоновое изображение для страницы (только для генератора).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Image](../../com.aspose.pdf/image) | Экземпляр изображения |

### setBleedBox(Rectangle value) {#setBleedBox-com.aspose.pdf.Rectangle-}
```
public void setBleedBox(Rectangle value)
```


Устанавливает поле выпуска страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Значение прямоугольника |

### setCropBox(Rectangle value) {#setCropBox-com.aspose.pdf.Rectangle-}
```
public void setCropBox(Rectangle value)
```


Устанавливает поле обрезки страницы.

--------------------

```
Example demonstrates how to get crop box of the page:


 Document document = new Document("sample.pdf");
 document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |

### setDuration(double value) {#setDuration-double-}
```
public void setDuration(double value)
```


Устанавливает продолжительность отображения страницы. Это время в секундах, в течение которого страница должна отображаться во время презентации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | продолжительность показа страницы. |

### setEnginePage(IPage enginePage) {#setEnginePage-com.aspose.pdf.engine.commondata.IPage-}
```
public void setEnginePage(IPage enginePage)
```


Только для внутреннего использования

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| enginePage | [IPage](../../com.aspose.pdf.engine.commondata/ipage) | внутренний экземпляр |

### setFooter(HeaderFooter value) {#setFooter-com.aspose.pdf.HeaderFooter-}
```
public void setFooter(HeaderFooter value)
```


Устанавливает нижний колонтитул страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [HeaderFooter](../../com.aspose.pdf/headerfooter) | Нижний колонтитул страницы. |

### setGroup(Group value) {#setGroup-com.aspose.pdf.Group-}
```
public void setGroup(Group value)
```


Задает класс атрибутов группы, определяющий атрибуты группы страниц страницы для использования в модели прозрачного изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Group](../../com.aspose.pdf/group) | Значение группы |

### setHeader(HeaderFooter value) {#setHeader-com.aspose.pdf.HeaderFooter-}
```
public void setHeader(HeaderFooter value)
```


Устанавливает заголовок страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [HeaderFooter](../../com.aspose.pdf/headerfooter) | Заголовок страницы. |

### setLayers(ArrayList<Layer> value) {#setLayers-java.util.ArrayList-com.aspose.pdf.Layer--}
```
public void setLayers(ArrayList<Layer> value)
```


Устанавливает коллекцию слоев.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.ArrayList<com.aspose.pdf.Layer> | : Коллекция слоев. |

### setLayersInternal(System.Collections.Generic.List<Layer> value) {#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Layer--}
```
public void setLayersInternal(System.Collections.Generic.List<Layer> value)
```


Устанавливает коллекцию слоев.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Layer> | : Коллекция слоев. |

### setMediaBox(Rectangle value) {#setMediaBox-com.aspose.pdf.Rectangle-}
```
public void setMediaBox(Rectangle value)
```


Устанавливает медиа-бокс страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Прямоугольник](../../com.aspose.pdf/rectangle) | Rectangle |

### setNoteLineStyle(GraphInfo value) {#setNoteLineStyle-com.aspose.pdf.GraphInfo-}
```
public void setNoteLineStyle(GraphInfo value)
```


Устанавливает стиль линии для заметок (только для генератора).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [GraphInfo](../../com.aspose.pdf/graphinfo) | : значение графинфо |

### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


Устанавливает информацию о странице (только для генератора, не заполняется при чтении файла).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | Информация о странице. |

### setPageSize(double width, double height) {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```


Устанавливает размер страницы для страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | double | Ширина страницы. |
| height | double | Размер страницы. |

### setParagraphs(Paragraphs value) {#setParagraphs-com.aspose.pdf.Paragraphs-}
```
public void setParagraphs(Paragraphs value)
```


Устанавливает абзацы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Paragraphs](../../com.aspose.pdf/paragraphs) | Значение абзаца |

### setRect(Rectangle value) {#setRect-com.aspose.pdf.Rectangle-}
```
public void setRect(Rectangle value)
```


Получает или задает прямоугольник страницы. Для получения: возвращается поле обрезки страницы, если указано, в противном случае возвращается поле медиа страницы. Для установки: медиабокс страницы всегда установлен. возвращается. Обратите внимание, что это свойство не учитывает поворот страницы. Чтобы получить прямоугольник страницы с учетом поворота, используйте ActualRect.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |

### setRotate(int value) {#setRotate-int-}
```
public void setRotate(int value)
```


Устанавливает поворот страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент вращения |

### setTabOrder(int value) {#setTabOrder-int-}
```
public void setTabOrder(int value)
```


Устанавливает порядок табуляции страницы. Возможные значения: Строка, Столбец. По умолчанию, вручную

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Объект TabOrder |

### setTocInfo(TocInfo value) {#setTocInfo-com.aspose.pdf.TocInfo-}
```
public void setTocInfo(TocInfo value)
```


Устанавливает информацию о содержании.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TocInfo](../../com.aspose.pdf/tocinfo) | Информация о содержании - по умолчанию ноль. Если он установлен, эта страница будет содержать оглавление. |

### setTransition(IPdfDictionary transition) {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public void setTransition(IPdfDictionary transition)
```


Установить переход

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| transition | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) | Объект IPdfDictionary |

### setTrimBox(Rectangle value) {#setTrimBox-com.aspose.pdf.Rectangle-}
```
public void setTrimBox(Rectangle value)
```


Устанавливает поле обрезки страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Значение прямоугольника |

### setUserUnit(double value) {#setUserUnit-double-}
```
public final void setUserUnit(double value)
```


 Получает или задает значение UserUnit. Положительное число, указывающее размер единиц пользовательского пространства по умолчанию, кратное 1.\\u0432\\u0403\> 72 дюйма. Значение по умолчанию — 1. Пожалуйста, установите нулевое или отрицательное значение, чтобы очистить эту запись на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setWatermark(Watermark value) {#setWatermark-com.aspose.pdf.Watermark-}
```
public void setWatermark(Watermark value)
```


Устанавливает водяной знак страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Watermark](../../com.aspose.pdf/watermark) | Объект водяного знака |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
