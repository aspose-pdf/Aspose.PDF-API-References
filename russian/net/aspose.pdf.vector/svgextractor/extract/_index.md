---
title: SvgExtractor.Extract
second_title: Aspose.PDF for .NET API Reference
description: Метод SvgExtractor. Извлекает svg изображение в строку из графических элементов, представленных абсорбером с предикатным фильтром
type: docs
weight: 20
url: /ru/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

Извлекает svg изображение в строку из графических элементов, представленных !:абсорбером с предикатным фильтром.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| absorber | GraphicsAbsorber | Объект GraphicsAbsorber, который содержит графические элементы. |
| filter | Predicate`1 | Функция предиката, используемая для фильтрации графических элементов. |
| page | Page | Страница, на которой абсорбер получает графические элементы. |

### Возвращаемое значение

Строка с содержимым SVG.

### Исключения

| исключение | условие |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Если произошла ошибка при преобразовании в SVG. |

### См. также

* класс [GraphicsAbsorber](../../graphicsabsorber/)
* класс [GraphicElement](../../graphicelement/)
* класс [Page](../../../aspose.pdf/page/)
* класс [SvgExtractor](../)
* пространство имен [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* сборка [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

Извлекает svg изображение в файл из графических элементов, представленных !:абсорбером с предикатным фильтром.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| absorber | GraphicsAbsorber | Объект GraphicsAbsorber, который содержит графические элементы. |
| filter | Predicate`1 | Функция предиката, используемая для фильтрации графических элементов. |
| page | Page | Страница, на которой абсорбер получает графические элементы. |
| svgFilePath | String | Путь к целевому SVG файлу. |

### Исключения

| исключение | условие |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Если произошла ошибка при преобразовании в SVG. |

### См. также

* класс [GraphicsAbsorber](../../graphicsabsorber/)
* класс [GraphicElement](../../graphicelement/)
* класс [Page](../../../aspose.pdf/page/)
* класс [SvgExtractor](../)
* пространство имен [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* сборка [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

Извлекает графические элементы в строку SVG. Опции игнорируются - группировка, извлечение из прямоугольника

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| elements | IEnumerable`1 | Графические элементы для преобразования. |
| page | Page | Страница, на которой абсорбер получает графические элементы. |

### Возвращаемое значение

Строка с содержимым SVG.

### Исключения

| исключение | условие |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Если произошла ошибка при преобразовании в SVG. |

### См. также

* класс [GraphicElement](../../graphicelement/)
* класс [Page](../../../aspose.pdf/page/)
* класс [SvgExtractor](../)
* пространство имен [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* сборка [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

Извлекает графические элементы в один SVG файл. Опции игнорируются - группировка, извлечение из прямоугольника

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| elements | IEnumerable`1 | Графические элементы для преобразования. |
| page | Page | Страница, на которой абсорбер получает графические элементы. |
| svgFilePath | String | Путь к целевому SVG файлу. |

### Исключения

| исключение | условие |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Если произошла ошибка при преобразовании в SVG. |

### См. также

* класс [GraphicElement](../../graphicelement/)
* класс [Page](../../../aspose.pdf/page/)
* класс [SvgExtractor](../)
* пространство имен [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* сборка [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

Извлекает Svg изображения со страницы в строки.

```csharp
public List<string> Extract(Page page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Page | Страница для извлечения. |

### Возвращаемое значение

Список строк с содержимым SVG.

### Исключения

| исключение | условие |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Если произошла ошибка при преобразовании в SVG. |

### См. также

* класс [Page](../../../aspose.pdf/page/)
* класс [SvgExtractor](../)
* пространство имен [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* сборка [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

Извлекает Svg изображения со страницы в файлы.

```csharp
public void Extract(Page page, string directory)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Page | Страница для извлечения. |
| directory | String | Целевая директория для размещения SVG изображений. |

### Исключения

| исключение | условие |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Если произошла ошибка при преобразовании в SVG. |

### См. также

* класс [Page](../../../aspose.pdf/page/)
* класс [SvgExtractor](../)
* пространство имен [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* сборка [Aspose.PDF](../../../)