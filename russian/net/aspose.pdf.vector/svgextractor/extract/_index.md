---
title: "SvgExtractor.Extract"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод SvgExtractor. Извлекает SVG‑изображение в строку из графических элементов, представленных абсорбером, с использованием предикатного фильтра"
type: docs
weight: 20
url: /ru/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

Извлекает SVG‑изображение в строку из графических элементов, представленных !:absorber, с предикатным фильтром.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| абсорбер | GraphicsAbsorber | Объект GraphicsAbsorber, который содержит графические элементы. |
| фильтр | Predicate`1 | Функция‑предикат, используемая для фильтрации графических элементов. |
| страница | Страница | Страница, на которой абсорбер получает графические элементы. |

### Возвращаемое значение

Строка с содержимым SVG.

### Исключения

| исключение | условие |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Если произошла ошибка при преобразовании в SVG. |

### См. также

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

Извлекает SVG‑изображение в файл из графических элементов, представленных !:absorber, с предикатным фильтром.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| абсорбер | GraphicsAbsorber | Объект GraphicsAbsorber, который содержит графические элементы. |
| фильтр | Predicate`1 | Функция‑предикат, используемая для фильтрации графических элементов. |
| страница | Страница | Страница, на которой абсорбер получает графические элементы. |
| svgFilePath | String | Путь к целевому файлу SVG. |

### Исключения

| исключение | условие |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Если произошла ошибка при преобразовании в SVG. |

### См. также

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

Извлекает графические элементы в SVG‑строку. Параметры игнорируются — группировка, извлечение из прямоугольника.

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| элементы | IEnumerable`1 | Графические элементы для преобразования. |
| страница | Страница | Страница, на которой абсорбер получает графические элементы. |

### Возвращаемое значение

Строка с содержимым SVG.

### Исключения

| исключение | условие |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Если произошла ошибка при преобразовании в SVG. |

### См. также

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

Извлекает графические элементы в один SVG‑файл. Параметры игнорируются — группировка, извлечение из прямоугольника.

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| элементы | IEnumerable`1 | Графические элементы для преобразования. |
| страница | Страница | Страница, на которой абсорбер получает графические элементы. |
| svgFilePath | String | Путь к целевому файлу SVG. |

### Исключения

| исключение | условие |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Если произошла ошибка при преобразовании в SVG. |

### См. также

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

Извлекает SVG‑изображения со страницы в строки.

```csharp
public List<string> Extract(Page page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | Страница | Страница для извлечения. |

### Возвращаемое значение

Список строк с содержимым SVG.

### Исключения

| исключение | условие |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Если произошла ошибка при преобразовании в SVG. |

### См. также

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

Извлекает SVG‑изображения со страницы в файлы.

```csharp
public void Extract(Page page, string directory)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | Страница | Страница для извлечения. |
| директория | String | Целевая директория для размещения SVG‑изображений. |

### Исключения

| исключение | условие |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | Если произошла ошибка при преобразовании в SVG. |

### См. также

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


