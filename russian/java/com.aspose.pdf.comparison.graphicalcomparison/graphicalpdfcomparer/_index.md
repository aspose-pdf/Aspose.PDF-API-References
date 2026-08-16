---
title: "GraphicalPdfComparer"
linktitle: "GraphicalPdfComparer"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет класс для графического сравнения PDF‑документов. Должен использоваться для поиска небольших изменений, в основном графического характера. Для сравнения изменений текстового содержимого используйте другие."
type: docs
weight: 10
url: /ru/java/com.aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.GraphicalPdfComparer

```
public class GraphicalPdfComparer extends Object
```

Представляет класс для графического сравнения PDF‑документов. Должен использоваться для поиска небольших изменений, в основном графических. Для сравнения изменений текстового содержимого используйте другие классы сравнения PDF.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GraphicalPdfComparer](#GraphicalPdfComparer--) | Создаёт экземпляр класса {@link GraphicalPdfComparer}. |

## Методы

| Метод | Описание |
| --- | --- |
| [compareDocumentsToImages](#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | Сравнивает документы графически. |
| [compareDocumentsToPdf](#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-) | Сравнивает документы графически. Результат сравнения помещается в PDF‑документ. |
| [comparePagesToImage](#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Сравнивает страницы графически. Результат сравнения помещается в изображение. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-) | Сравнивает страницы графически. Результат сравнения помещается в PDF‑документ. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Сравнивает страницы графически. Результат сравнения помещается в PDF‑документ. |
| [getColor](#getColor--) | Получает и задаёт цвет флага изменения. Цвет по умолчанию — красный. |
| [getDifference](#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-) | Получает различия между изображениями страниц. Результат содержит изображение первой сравниваемой страницы и массив различий. |
| [getResolution](#getResolution--) | Получает и задаёт разрешение получаемых изображений. Значение по умолчанию — 150 dpi. |
| [getThreshold](#getThreshold--) | Получает и задаёт пороговое значение в процентах. Это значение позволяет игнорировать небольшие изменения, если они несущественны для вас. Значение по умолчанию — 0 %. |
| [setColor](#setColor-com.aspose.pdf.Color-) | Получает и задаёт цвет флага изменения. Цвет по умолчанию — красный. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Получает и задаёт разрешение получаемых изображений. Значение по умолчанию — 150 dpi. |
| [setThreshold](#setThreshold-double-) | Получает и задаёт пороговое значение в процентах. Это значение позволяет игнорировать небольшие изменения, если они несущественны для вас. Значение по умолчанию — 0 %. |

### GraphicalPdfComparer {#GraphicalPdfComparer--}
```
public GraphicalPdfComparer()
```

Создаёт экземпляр класса {@link GraphicalPdfComparer}.

### compareDocumentsToImages {#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
Сравнивает документы графически.

### compareDocumentsToPdf {#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-}
Сравнивает документы графически. Результат сравнения помещается в PDF‑документ.

### comparePagesToImage {#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Сравнивает страницы графически. Результат сравнения помещается в изображение.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-}
Сравнивает страницы графически. Результат сравнения помещается в PDF‑документ.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Сравнивает страницы графически. Результат сравнения помещается в PDF‑документ.

### getColor {#getColor--}
```
public final Color getColor()
```

Получает и задаёт цвет флага изменения. Цвет по умолчанию — красный.

**Returns:**
Экземпляр Color

### getDifference {#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-}
Получает различия между изображениями страниц. Результат содержит изображение первой сравниваемой страницы и массив различий.

### getResolution {#getResolution--}
```
public final Resolution getResolution()
```

Получает и задаёт разрешение получаемых изображений. Значение по умолчанию — 150 dpi.

**Returns:**
Экземпляр Resolution

### getThreshold {#getThreshold--}
```
public final double getThreshold()
```

Получает и задаёт пороговое значение в процентах. Это значение позволяет игнорировать небольшие изменения, если они несущественны для вас. Значение по умолчанию — 0 %.

**Returns:**
double значение

### setColor {#setColor-com.aspose.pdf.Color-}
Получает и задаёт цвет флага изменения. Цвет по умолчанию — красный.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Получает и задаёт разрешение получаемых изображений. Значение по умолчанию — 150 dpi.

### setThreshold {#setThreshold-double-}
```
public final void setThreshold(double value)
```

Получает и задаёт пороговое значение в процентах. Это значение позволяет игнорировать небольшие изменения, если они несущественны для вас. Значение по умолчанию — 0 %.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | double значение |
