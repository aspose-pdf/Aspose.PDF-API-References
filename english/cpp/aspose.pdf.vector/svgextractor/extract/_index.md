---
title: Aspose::Pdf::Vector::SvgExtractor::Extract method
linktitle: Extract
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Vector::SvgExtractor::Extract method. Exracts svg image to string from graphic elements represents by absorber with a predicate filter in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.vector/svgextractor/extract/
---
## SvgExtractor::Extract(System::SharedPtr\<GraphicsAbsorber\>, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, System::SharedPtr\<Page\>) method


Exracts svg image to string from graphic elements represents by [absorber](../) with a predicate filter.

```cpp
System::String Aspose::Pdf::Vector::SvgExtractor::Extract(System::SharedPtr<GraphicsAbsorber> absorber, System::Predicate<System::SharedPtr<GraphicElement>> filter, System::SharedPtr<Page> page)
```


| Parameter | Type | Description |
| --- | --- | --- |
| absorber | System::SharedPtr\<GraphicsAbsorber\> | The [GraphicsAbsorber](../../graphicsabsorber/) object that contains the graphic elements. |
| filter | System::Predicate\<System::SharedPtr\<GraphicElement\>\> | A predicate function used to filter the graphic elements. |
| page | System::SharedPtr\<Page\> | The page where the absorber gets graphic elements. |

### ReturnValue

The string with SVG content.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsAbsorber](../../graphicsabsorber/)
* Typedef [Predicate](../../../system/predicate/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(System::SharedPtr\<GraphicsAbsorber\>, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, System::SharedPtr\<Page\>, System::String) method


Exracts svg image to file from graphic elements represents by [absorber](../) with a predicate filter.

```cpp
void Aspose::Pdf::Vector::SvgExtractor::Extract(System::SharedPtr<GraphicsAbsorber> absorber, System::Predicate<System::SharedPtr<GraphicElement>> filter, System::SharedPtr<Page> page, System::String svgFilePath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| absorber | System::SharedPtr\<GraphicsAbsorber\> | The [GraphicsAbsorber](../../graphicsabsorber/) object that contains the graphic elements. |
| filter | System::Predicate\<System::SharedPtr\<GraphicElement\>\> | A predicate function used to filter the graphic elements. |
| page | System::SharedPtr\<Page\> | The page where the absorber gets graphic elements. |
| svgFilePath | System::String | The target SVG file path. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsAbsorber](../../graphicsabsorber/)
* Typedef [Predicate](../../../system/predicate/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(System::SharedPtr\<Page\>) method


Extracts Svg images from a page to strings.

```cpp
System::SharedPtr<System::Collections::Generic::List<System::String>> Aspose::Pdf::Vector::SvgExtractor::Extract(System::SharedPtr<Page> page)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Page\> | The page to extract. |

### ReturnValue

The list of SVG content strings.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [String](../../../system/string/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(System::SharedPtr\<Page\>, System::String) method


Extracts Svg images from a page to files.

```cpp
void Aspose::Pdf::Vector::SvgExtractor::Extract(System::SharedPtr<Page> page, System::String directory)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | System::SharedPtr\<Page\> | The page to extract. |
| directory | System::String | The target directory to place SVG images. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>, System::SharedPtr\<Page\>) method


Extracts graphic elements into a SVG string. Options ignored - grouping, extracting from rectangle.

```cpp
System::String Aspose::Pdf::Vector::SvgExtractor::Extract(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<GraphicElement>>> elements, System::SharedPtr<Page> page)
```


| Parameter | Type | Description |
| --- | --- | --- |
| elements | System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\> | The graphic elements to convert. |
| page | System::SharedPtr\<Page\> | The page where the absorber gets graphic elements. |

### ReturnValue

The string with SVG content.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>, System::SharedPtr\<Page\>, System::String) method


Extracts graphic elements into a single SVG file. Options ignored - grouping, extracting from rectangle.

```cpp
void Aspose::Pdf::Vector::SvgExtractor::Extract(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<GraphicElement>>> elements, System::SharedPtr<Page> page, System::String svgFilePath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| elements | System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\> | The graphic elements to convert. |
| page | System::SharedPtr\<Page\> | The page where the absorber gets graphic elements. |
| svgFilePath | System::String | The target SVG file path. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
