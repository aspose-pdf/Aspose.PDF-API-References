---
title: "Метод Aspose::Pdf::Vector::SvgExtractor::Extract"
linktitle: "Extract"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Vector::SvgExtractor::Extract. Извлекает SVG‑изображение в строку из графических элементов, представленных поглотителем с предикатным фильтром, в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.vector/svgextractor/extract/
---
## SvgExtractor::Extract(const System::SharedPtr\<GraphicsAbsorber\>\&, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, const System::SharedPtr\<Page\>\&) method


Извлекает SVG‑изображение в строку из графических элементов, представленных [absorber](../) с фильтром‑предикатом.

```cpp
System::String Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<GraphicsAbsorber> &absorber, System::Predicate<System::SharedPtr<GraphicElement>> filter, const System::SharedPtr<Page> &page)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| absorber | const System::SharedPtr\<GraphicsAbsorber\>\& | Объект [GraphicsAbsorber](../../graphicsabsorber/), содержащий графические элементы. |
| фильтр | System::Predicate\<System::SharedPtr\<GraphicElement\>\> | Предикатная функция, используемая для фильтрации графических элементов. |
| страница | const System::SharedPtr\<Page\>\& | Страница, на которой поглотитель получает графические элементы. |

### ReturnValue

Строка с содержимым SVG.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsAbsorber](../../graphicsabsorber/)
* Typedef [Predicate](../../../system/predicate/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(const System::SharedPtr\<GraphicsAbsorber\>\&, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, const System::SharedPtr\<Page\>\&, const System::String\&) method


Извлекает SVG‑изображение в файл из графических элементов, представленных [absorber](../) с фильтром‑предикатом.

```cpp
void Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<GraphicsAbsorber> &absorber, System::Predicate<System::SharedPtr<GraphicElement>> filter, const System::SharedPtr<Page> &page, const System::String &svgFilePath)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| absorber | const System::SharedPtr\<GraphicsAbsorber\>\& | Объект [GraphicsAbsorber](../../graphicsabsorber/), содержащий графические элементы. |
| фильтр | System::Predicate\<System::SharedPtr\<GraphicElement\>\> | Предикатная функция, используемая для фильтрации графических элементов. |
| страница | const System::SharedPtr\<Page\>\& | Страница, на которой поглотитель получает графические элементы. |
| svgFilePath | const System::String\& | Путь к целевому файлу SVG. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsAbsorber](../../graphicsabsorber/)
* Typedef [Predicate](../../../system/predicate/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(const System::SharedPtr\<Page\>\&) method


Извлекает SVG‑изображения со страницы в строки.

```cpp
System::SharedPtr<System::Collections::Generic::List<System::String>> Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<Page> &page)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | const System::SharedPtr\<Page\>\& | Страница для извлечения. |

### ReturnValue

Список строк с содержимым SVG.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [String](../../../system/string/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(const System::SharedPtr\<Page\>\&, const System::String\&) method


Извлекает SVG‑изображения со страницы в файлы.

```cpp
void Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<Page> &page, const System::String &directory)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | const System::SharedPtr\<Page\>\& | Страница для извлечения. |
| каталог | const System::String\& | Целевой каталог для размещения SVG‑изображений. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\&, const System::SharedPtr\<Page\>\&) method


Извлекает графические элементы в строку SVG. Параметры игнорируются — группировка, извлечение из прямоугольника.

```cpp
System::String Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<GraphicElement>>> &elements, const System::SharedPtr<Page> &page)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| элементы | const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\& | Графические элементы для преобразования. |
| страница | const System::SharedPtr\<Page\>\& | Страница, на которой поглотитель получает графические элементы. |

### ReturnValue

Строка с содержимым SVG.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\&, const System::SharedPtr\<Page\>\&, const System::String\&) method


Извлекает графические элементы в единый файл SVG. Параметры игнорируются — группировка, извлечение из прямоугольника.

```cpp
void Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<GraphicElement>>> &elements, const System::SharedPtr<Page> &page, const System::String &svgFilePath)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| элементы | const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\& | Графические элементы для преобразования. |
| страница | const System::SharedPtr\<Page\>\& | Страница, на которой поглотитель получает графические элементы. |
| svgFilePath | const System::String\& | Путь к целевому файлу SVG. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
